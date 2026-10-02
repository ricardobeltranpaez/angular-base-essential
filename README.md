
# Angular - Base essential

A base scaffold for Angular applications that requires minimal implementation of 3-pary libraries.
*Una estructura base para aplicaciones Angular que requiere una implementación mínima de librerías de terceros.*

Minimal stable, readable, scalable, self document easy mantenible base structure.
*Estructura base mínima, estable, legible, escalable, autodocumentada y de fácil mantenimiento.*

We'll Start with "[Build your first Angular app](https://v17.angular.io/tutorial/first-app/first-app-lesson-14)" app from the [Angular official site](https://angular.dev/) and a [repository own](https://github.com/ricardobeltranpaez/webapp-crud-node-base-mvc) Express Js based uses for CMS type admin and API server.

*Comenzaremos con la aplicación «Build your first Angular app» del sitio oficial de Angular y con un repositorio propio basado en Express.js, utilizado como servidor API y panel de administración tipo CMS.*

---

- [Installation and Intro tour][installation]
- [API Reference][apireference]
- [Usages examples][examples]
- [Appendix][appendix]

[installation]: #installation-and-intro-tour
[apireference]: #api-reference
[examples]: #usages-examples
[appendix]: #appendix

## Installation and Intro tour

### Requirements

Needs to have [Node.js](https://nodejs.org/en/download) installed.

### Install

Install angular-base-essential with npm or pnpm, [recommended](https://www.kochan.io/nodejs/pnpms-strictness-helps-to-avoid-silly-bugs.html).

```bash
  npm install angular-base-essential
  cd angular-base-essential
```
### ...and then!

Lorem ipsum

---

## API Reference

#### Response same body request for test
```http
POST /api/echo
```` 
| Parameter | Type | Description |
| :-------: | :--: | :---------- |
|   `{*}`   | `JSON` | Receives JSON data and echoes it back |
## Usages examples

````console
# Console example

curl -X POST http://localhost:5000/api/echo -H "Content-Type: application/json" -d '{"framework": "Express", "runtime": "Node"}'
````

## Appendix

Loren ipsum
