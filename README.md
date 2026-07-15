# Stock

Aplicación de escritorio para **gestión de stock** (productos, rubros y movimientos)
desarrollada en **Visual Basic 6**, con base de datos **SQLite** local.

> ⚠️ Proyecto *legacy* (VB6). Se mantiene por referencia histórica.

## Tecnología

- **Visual Basic 6** (`Stock.vbp` / `Stock.vbw`)
- Base de datos **SQLite** (`base.s3db`) — esquema en [`cosas/script.sql`](./cosas/script.sql)
- Arquitectura por formularios (`formularios/`) y clases reutilizables (`clases/`)

## Estructura

```
Stock.vbp        Proyecto VB6
formularios/     Login, Principal, Producto, Rubro, Movimiento, Lista, Selección...
clases/          Clases utilitarias (CLista, CString, CAnchor, CCommonDialog...)
cosas/           Iconos y script.sql (esquema de la BD)
base.s3db        Base SQLite
config.ini       Configuración
```

## Uso

Abrir `Stock.vbp` con el IDE de Visual Basic 6. La base `base.s3db` se accede
mediante la configuración de `config.ini`.
