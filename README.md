# Quasar-Boilerplate

> A Boilerplate for creating web apps with Quasar & Bootstrap-Vue.

### System Requirements
- Node.js (https://nodejs.org/en/download/)
- Quasar-CLI (https://quasar.dev/quasar-cli/installation)
- VS-Code (https://code.visualstudio.com/)

### Setup

Run following commands sequentially

```
$> git clone https://github.com/maulik-neosoft/Quasar-Boilerplate
$> cd Quasar-Boilerplate
$> npm install
```

### Commands
Devlopment:
```$> quasar dev```

Production Build:
```$> quasar build```

### Configurtation
- All app related configuration can be found in `quasar.conf.js` file.
- CSS/Styling has to be written in `src/css/app.scss` file.
- Routes need to be specified in `src/router/routes.js` file.
- All stastic assets like Images need to be places in `src/assets` directory.
- Pages are need to be kept inside `src/pages` directory in their separate files.

### Deployment
Copy all static files from `/project-dir/dist/spa/` to the public folder of server
