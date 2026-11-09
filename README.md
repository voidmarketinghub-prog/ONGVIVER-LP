# LP Campanha Tijolinho — ONG Viver

Landing page da campanha Construtores da Esperança (Tijolinho) da ONG Viver.

## Estrutura

index.html — página principal (HTML, CSS e JS em um único arquivo).

maquete.html — maquete 3D interativa da nova sede (página independente, acessada pelo botão "Explorar a maquete 3D interativa" no site).

assets/ — imagens, vídeo e favicon.

## Hospedagem

Site 100% estático, sem build, dependências ou back-end. Basta servir o conteúdo desta pasta na raiz do domínio (Apache, Nginx, cPanel, Vercel, Netlify, Cloudflare Pages etc.).

Fontes carregadas via Google Fonts (requer acesso a fonts.googleapis.com). O feed do Instagram usa o embed oficial (instagram.com/ongviver/embed). A maquete 3D carrega a biblioteca three.js via CDN (unpkg.com).

## Pendências de conteúdo

1. Botão "Adquirir meu tijolinho" aponta para o WhatsApp oficial da Viver. Substituir pelo link do checkout quando definido (marcado com TODO no index.html).
2. CNPJ da instituição no rodapé.

Mockup de desenvolvimento: https://tijolinho-viver.pages.dev
