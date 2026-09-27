# Mestre do Excel — versão estática para Vercel

Projeto convertido do JSON exportado do Elementor para HTML/CSS/JS estático.

## Publicar
1. Envie todos os arquivos deste diretório para um repositório no GitHub.
2. Na Vercel, escolha **Add New > Project** e importe o repositório.
3. Framework Preset: **Other**. Não é necessário Build Command.
4. Publique.

## IMPORTANTE — checkout
O JSON original não contém URL nos botões de compra. Antes de publicar, abra `index.html`, localize `data-empty-checkout` e substitua `href="#"` pelo seu link real de checkout.

## Imagens
As imagens continuam apontando para o domínio original `plrprofissional.com`, porque fazem parte das referências do export do Elementor. Para independência total do WordPress, baixe essas imagens para uma pasta local e troque as URLs no HTML/JS/CSS.
