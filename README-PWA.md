# Nextgen United — PWA

Ficheiros preparados para transformar o site atual numa PWA:

- `index.html` — versão do teu site com os metadados PWA e registo do Service Worker.
- `manifest.webmanifest` — nome, ícone, cores e comportamento de instalação.
- `sw.js` — cache da aplicação e suporte básico offline.

## Antes de publicar

Mantém também o ficheiro de imagem que o site já usa:

`logo.png.png`

Coloca-o na mesma pasta do `index.html`.

## GitHub Pages

1. Coloca estes ficheiros na raiz do repositório, juntamente com `logo.png.png`.
2. Ativa o GitHub Pages para a branch/pasta onde está o `index.html`.
3. Abre o site através de HTTPS.
4. No telemóvel, usa a opção do navegador **Adicionar ao ecrã inicial / Instalar aplicação**.

## Firebase

Não é necessário criar outro Firebase. O `index.html` continua a usar a configuração Firebase que já estava no site.

Nota: o Service Worker não interceta os pedidos externos do Firebase; assim, a sincronização continua a funcionar normalmente quando existe ligação à Internet.
