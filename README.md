# Online SLZ — Site estático

Este pacote contém o site da Online SLZ, com a página inicial e seis páginas de projetos.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub para o site.
2. Envie **o conteúdo deste ZIP** diretamente para a raiz do repositório (não envie a pasta ZIP como uma única pasta).
3. No repositório, abra **Settings > Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**; depois **main** e **/(root)**.
5. Para usar o domínio desejado, configure **Custom domain** como `www.online.slz.br` e siga as instruções de DNS indicadas pelo GitHub. Só mude os registros de DNS quando estiver pronto para migrar o domínio.

**Importante:** este site foi preparado para funcionar na raiz do domínio (`www.online.slz.br`). Links e recursos usam caminhos iniciados por `/`. Portanto, se for visualizado no endereço temporário `usuario.github.io/nome-do-repositorio`, os links podem não funcionar corretamente até o domínio personalizado ser configurado.

## Estrutura

- `index.html`: página principal;
- `projetos/`: listagem dos projetos;
- `diana/`, `notasolidaria/`, `conexaoescola/`, `italianoconstrucoes/`, `carlanutri/`, `apprime/`: páginas individuais;
- `assets/`: logomarcas;
- `style.css`: estilos;
- `site.js`: conteúdo e navegação.

O site é estático e não requer Python, Node.js, PHP ou banco de dados no servidor.
