# CADU DISCOS — protótipo de e-commerce

Site responsivo em HTML, CSS e JavaScript puro, sem dependências de build.

## Como abrir

1. Extraia o arquivo ZIP.
2. Abra `index.html` em um navegador moderno. Para testes mais consistentes, use um servidor local: `python -m http.server 8000` dentro da pasta e acesse `http://localhost:8000`.

## O que funciona

- Home responsiva, categorias, vitrines, área institucional, benefícios, avaliações ilustrativas e FAQ.
- Busca por título, artista ou gênero, filtros de catálogo, ordenação e favoritos.
- Página de produto, com ficha técnica e seleção de faixas reais do álbum.
- Carrinho lateral com adição, alteração de quantidade e remoção.
- Checkout demonstrativo em três etapas com validação de campos, sem processar pagamentos.
- Persistência local do carrinho e favoritos via `localStorage`.
- Capas reais dos álbuns buscadas pela iTunes Search API quando houver rede e correspondência; caso indisponíveis, o site exibe capas tipográficas **explicitamente ilustrativas**, não capas oficiais.

## Observações

- Todos os preços, condições comerciais, estoque, frete e depoimentos são demonstrativos.
- O projeto não realiza cobranças, não envia pedidos, não salva dados pessoais em servidor e não tem autenticação.
- Imagem externa da seção institucional usa Unsplash; as capas dos álbuns dependem de serviço de terceiros e de acesso à internet.
- Para operar comercialmente: integrar API de produtos/estoque, pagamentos, frete, autenticação, políticas legais e hospedagem de imagens com licença adequada.

## Arquivos

- `index.html`: estrutura e conteúdo.
- `styles.css`: identidade visual e estilos responsivos.
- `app.js`: catálogo, renderização e interações.
