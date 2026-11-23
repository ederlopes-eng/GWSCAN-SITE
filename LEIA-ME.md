# Site GWSCAN (prévia para aprovação)

Site de uma única página: `index.html` (tudo dentro dele: estilos, scripts, logo e logos dos clientes).

## Publicar no GitHub Pages (para mandar o link ao Gil)
1. No GitHub, crie um repositório novo (ex.: `gwscan-site`) e envie os arquivos desta pasta (`index.html` e `.nojekyll`).
2. No repositório: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, escolha **main** e a pasta **/ (root)**, e salve.
3. Em 1 a 2 minutos o link aparece na mesma tela: `https://SEU-USUARIO.github.io/gwscan-site/`.

## Imagens e vídeo
- As fotos de campo carregam direto do site atual (gwscan.com.br). Funcionam enquanto o site antigo estiver no ar. Antes de desligá-lo, baixe as fotos e troque os endereços no `index.html`.
- O vídeo do YouTube toca dentro da página quando o site está publicado (https). Aberto direto do computador, o clique abre o YouTube em outra aba.

## Instagram
- Por padrão aparece uma grade de fotos que leva ao perfil @gwscan.
- Para mostrar publicações de verdade, abra o `index.html`, procure `INSTAGRAM_POSTS=[]` e coloque os links dos posts entre aspas, separados por vírgula.

## Topo (foto do drone)
A foto do Mavic 3 é imagem de divulgação da DJI, usada só como prévia. Para o site final, troque por foto ou vídeo da própria GWSCAN.
