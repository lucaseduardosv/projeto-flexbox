# Projeto Food.exe — Catálogo Delivery

Landing page responsiva de um serviço de delivery inspirado no visual fornecido. Construída com HTML + CSS focando em Flexbox para organizar o layout.

## Tema
- **Categoria:** Catálogo simples de lanches/bebidas.
- **Descrição:** Página única com herói, seção “Sobre”, serviços, categorias, produtos em destaque, avaliações, contato e rodapé corporativo.

## Onde usei Flexbox
1. `header` (`.cabecalho-conteudo` + `.menu-principal`) para alinhar logo e navegação.
2. Seção hero (`.capa-conteudo`) que divide texto e imagem.
3. Cards de serviços, categorias, produtos e avaliações (`.cartoes-servico`, `.grade-categorias`, `.grade-produtos`, `.grade-avaliacoes`) usando `flex-wrap` + `gap`.
4. Seções “Sobre” e “Contato” (`.sobre-conteudo`, `.contato-conteudo`) formando colunas flexíveis.

## Breakpoints
- **900px:** Hero reorganiza para colunas empilhadas, navegação reduz espaçamento.
- **600px:** Cabeçalho e formulários passam a coluna única; hero ganha padding menor.

## Requisitos atendidos
- Header com menu, hero com CTA, seção “Sobre”, cards (6 categorias), seção produtos, avaliações, contato com formulário (nome, e-mail, mensagem) e footer.
- Imagens com `alt`, formulários com `label for=`, cores e tipografia definidas, `max-width` em `.container`, efeitos `:hover` nos botões/links.
