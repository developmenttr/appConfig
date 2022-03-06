# REMOTE CONFIG

## Variables

### Parameters

| Parameter | Value | Description |
| ------ | ------ | ------ |
| app | "es.devtr.config" | Paquete de la aplicación |
| version | "4.0.4" | Nombre de la versión afectada |

#### Config

| Key | Value | Default | Description |
| ------ | ------ | ------ | ------ |
| specialPriority | "admob", "huawei" | "priority" | Indica qué anuncio mostrar si ambos se han cargado. No atiende a prioridad.
| huaweiGDPRPriority | "100" | 0 | Indica la prioridad que tendrán los usuarios Europeos en ver anuncios de Huawei |

#### Alert

| Key | Value | Description |
| ------ | ------ | ------ |
| id | "87sga7d" | ID de la alerta |
| title | "Title" | Título de la alerta |
| url | "https://..." | Dirección web de la alerta |
| single | true, false | Indica si la alerta se mostrará solo una vez (Todavía sin implementar) |
| cancelable | true, false | Indica si la alerta se puede cancelar |
| start | "189273" | Indica la fecha de inicio en la que comenzar a mostrar la alerta |
| end | "389274" | Indica la fecha en la que se dejará de mostrar la alerta |

## JSON Example
```
[
  {
    "app": "color.dev.com.whatsremoved",
    "version": "8.0.1G",
    "config": [
      {
        "key": "clave",
        "value": "value"
      },
      {
        "key": "clave",
        "value": "value"
      }
    ],
    "alerts": [
      {
        "id": "asldklkj",
        "title": "Titulo",
        "url": "https://",
        "single": true,
        "cancelable": true,
        "start": "3894782374",
        "end": "92884908234"
      }
    ]
  },
  {
    "app": "color.dev.com.whatsremoved",
    "version": "8.0.1G",
    "config": [
      {
        "key": "clave",
        "value": "value"
      },
      {
        "key": "clave",
        "value": "value"
      }
    ],
    "alerts": [
      {
        "id": "asldklkj",
        "title": "Titulo",
        "url": "https://",
        "single": true,
        "cancelable": true,
        "start": "3894782374",
        "end": "92884908234"
      }
    ]
  }
]
```
