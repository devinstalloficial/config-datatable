# config-datatable

```JS
$('.datatable-historico-storie').DataTable({
        "iDisplayLength": 25,
        "lengthMenu": [25, 75, 125],
        "pageLength": 25,
        "searching": true,
        "responsive": true,
        // "ordering": false,
        "language": {
            "decimal": ",",
            "thousands": ".",
            "info": "",
            "infoEmpty": "",
            "infoPostFix": "",
            "infoFiltered": "FILTRADO DE UM TOTAL DE MAX REGISTROS",
            "loadingRecords": "Carregando...",
            "lengthMenu": "<strong>EXIBIR: </strong> MENU",
            "paginate": {
                "first": "PRIMEIRO",
                "last": "ÚLTIMO",
                "next": "SEGUINTE",
                "previous": "ANTERIOR"
            },
            "processing": "Processando...",
            "search": "<strong>PESQUISAR: </strong>",
            "searchPlaceholder": "",
            "zeroRecords": null,
            "emptyTable": null,
            "aria": {
                "sortAscending": ": Ativar para ordenar a coluna de maneira ascendente",
                "sortDescending": ": Ativar para ordenar a coluna de maneira descendente"
            },
            "buttons": {
                "create": "Novo",
                "edit": "Editar",
                "remove": "Apagar",
                "copy": "Copiar",
                "csv": "CSV",
                "excel": "tabla Excel",
                "pdf": "documento PDF",
                "print": "Imprimir",
                "colvis": "Visibilidade colunas",
                "collection": "Coleção",
                "upload": "Selecione fichero...."
            },
            "select": {
                "rows": {
                    _: '%d filas seleccionadas',
                    0: 'clica para selecionar',
                    1: 'uma linha selecionada'
                }
            },
        }
    });
```
