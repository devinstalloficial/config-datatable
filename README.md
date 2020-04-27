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
                "sortAscending": ": Activar para ordenar la columna de manera ascendente",
                "sortDescending": ": Activar para ordenar la columna de manera descendente"
            },
            "buttons": {
                "create": "Novo",
                "edit": "Cambiar",
                "remove": "Apagar",
                "copy": "COPIAR",
                "csv": "CSV",
                "excel": "tabla Excel",
                "pdf": "documento PDF",
                "print": "IMPRIMIR",
                "colvis": "Visibilidad columnas",
                "collection": "Colección",
                "upload": "Selecione fichero...."
            },
            "select": {
                "rows": {
                    _: '%d filas seleccionadas',
                    0: 'clic fila para seleccionar',
                    1: 'uma linha selecionada'
                }
            },
        }
    });
```
