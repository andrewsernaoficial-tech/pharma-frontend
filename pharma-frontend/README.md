# PharmaSoft (pharma-frontend)

SPA Angular 22 que consume PharmaBackend (Spring Boot). Sesión 7 – LP II, UPeU.

## Ejecutar
```bash
npm install
ng serve -o          # http://localhost:4200
```
Requiere PharmaBackend en http://localhost:8080 (rama feature/consultas-reportes, con CORS para :4200).

## Estructura
- `core/` configuración del menú, modelos comunes y utilidades de errores
- `shared/` páginas reutilizables (404)
- `layout/` encabezado, sidebar y MainLayout
- `features/` un módulo por tabla (inicio, categorias)

## Reto 02
Agregar `features/clientes` con la misma arquitectura y descomentar la línea de Clientes en `core/config/menu.ts`.
