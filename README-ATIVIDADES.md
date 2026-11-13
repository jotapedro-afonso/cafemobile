# Café Mobile — atividades Dia 5 e Dia 6

## Estrutura
- `index.html`: estrutura das telas, campo de busca e aviso offline.
- `css/style.css`: estilos do aplicativo e das duas funcionalidades adicionadas.
- `js/dados.js`: lista de produtos.
- `js/app.js`: navegação, pedidos, busca por nome e aviso de conexão.
- `js/camera.js`: câmera e galeria.
- `js/pwa.js`: registro do Service Worker, instalação e compartilhamento.
- `manifest.json`: metadados e ícones do PWA.
- `sw.js`: cache dos arquivos para uso offline.

## Funcionalidades adicionadas para o Dia 6
1. Faixa “Você está offline”: acompanha `navigator.onLine` e os eventos `online` e `offline`.
2. Busca por nome: filtra produtos conforme o usuário digita, sem perder o filtro de categoria.

## Dia 5 — PWA
O projeto já continha `manifest.json`, `sw.js` e `js/pwa.js`. O Manifest identifica o aplicativo; o Service Worker armazena os arquivos listados no cache; e `pwa.js` registra o Service Worker, oferece instalação quando suportada e implementa compartilhamento.

## Como testar
Abra o projeto por `localhost` ou publique-o em HTTPS. Service Worker e câmera não funcionam corretamente ao abrir o HTML diretamente por `file://`. Para testar offline, carregue o site uma vez online e depois use as ferramentas do navegador para ficar offline ou desligue a conexão. As capturas de tela para entrega devem ser feitas no navegador, GitHub e celular reais.
