# filhote-em-casa

O site no ar é [https://filhoteemcasa.com.br](https://filhoteemcasa.com.br), publicado no Cloudflare Pages (projeto `filhote-em-casa`). A fonte dessa página de vendas está em [`site/`](site/).

Os HTML na raiz (`index.html`, `privacidade.html` e `terms.html`) são redirecionamentos da URL antiga do GitHub Pages (`https://hercullysp.github.io/filhote-em-casa/`). Cada um manda o visitante para o mesmo caminho em filhoteemcasa.com.br, preservando a query string (UTMs, `fbclid`) e o hash. Os arquivos em `/ads/` e `/assets/` continuam servidos por este repositório.

O workflow de GitHub Pages tira a pasta `site/` do artefato publicado, para essa cópia da página de vendas não aparecer em um segundo endereço.
