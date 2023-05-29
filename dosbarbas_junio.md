# Reunion junio
## Integrantes
- Estefania Flores
- Hugo Gonzalez
    - Desarrollador documento excel
- Nicolas Cofre
- Aaron Cruces 
    - desarrollador web
- Rodrigo Dominguez
    - desarollador web

## Descripcion
Vamos a desarrollar la parte de economia  
El sistema lleva un registro de costos  

### Jerarquia
- proyecto (definido en hoja de excel)
    - cursos
        - costos de items 
    - ingresos operacionales
        - item (p/ejemplo Material Oficina)
            - fotocopia (cuanto se ha gastado) 
### Tarea
Redefinir el documento de excel pero en angular/laravel

### A desarrollar
- Es importante tener fecha asociada a gastos
- Tiene numero de folio, correlativo depende de proyecto, no curso
- Poder añadir no solo costos, si no que tambien diferenciales (me falto o sobro plata)
    - Debe atachearse como una nueva solicitud, pero relacionarce con su solicitud "parent"
- Tambien hay ingresos  asociados a un curso, dados sus proyectos
- Registrar fecha en la que registra la factura
- Registrar fecha en la que se paga
- Existen proyectos que se empieza mucho antes en los que se realizan pagos y facturas
- Un proyecto puede tener multiples estados
    - A menos que no este preaprobado/aprobado, no va a aplicarse el presupuesto en el resumen
    - Al estar aprobado, tambien se aplican los costos realies
- Realizar una tabla de cuanto y en que se va agastar en esta semana
    - ¿Cada mes?
    - poder añadir mas dias a un rango
    - Filtrarlo por diferentes criterios
- Idem con solicitudes
- Resumen final, flujos financieros. 
    - Integrar mas tipos de fecha (las mencionadas antes).
    - Agregar distintos tipos de filtros
- tener la capacidad de presionar o atrasar pagos dependiendo de cuanto se gasta y cuanto hay en caja


### Preguntas
- ¿como esta hecha la macro?
    - extenciones
        - ir a appscript en el menu
- ¿las solicitudes tienen boletas u otros documentos?
    - no, pero deberia
- ¿pueden haber proyectos con varios cursos?
    - por supuesto



