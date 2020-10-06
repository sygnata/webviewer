# Webviewer
Navegador compacto que sempre fica sobre as demais janelas, feito em [**Electron**](https://www.electronjs.org/)

### :speaker: Funcionamento
- O Webviwer vai olhar  por padrão a URL "http://localhost:5500/", pode alterar no config.js

### :point_right: Atalhos
- CTRL+J para abrir/fechar devTools
- F11 para fullscreen
- Pode adicionar mais atalhos na função createShortcuts(), conforme necessidade
### :hand: Instalação
- npm install
- npm start (ja consegue visualizar a aplicação)
- npm install electron-packager -g
- electron-packager 'sourcedir'  'appname'
- Executar o .exe criado no passo anterior
