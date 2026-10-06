# SyntaxWear

Uma landing page de e-commerce focada em sneakers e tênis urbanos, com visual moderno, responsivo e voltado para uma experiência premium no varejo digital.

## Sobre o projeto

O SyntaxWear é uma loja fictícia de calçados esportivos e casuais, com foco em:

- apresentação de banner principal com proposta de marca
- categorias de produtos em destaque
- grid de itens em destaque e campanhas promocionais
- navegação responsiva com menu mobile
- rodapé com newsletter, links institucionais e redes sociais

O projeto foi construído com HTML e CSS puros, mantendo uma estrutura simples e fácil de personalizar para estudos, protótipos e apresentação de portfólio.

## Stack utilizada

- HTML5
- CSS3
- Design responsivo
- Imagens estáticas em SVG e JPG
- Arquitetura modular de estilos por componentes

## Estrutura do projeto

```text
ecommerce-syntaxwear/
├── css/
│   ├── base.css
│   ├── reset.css
│   ├── variables.css
│   └── components/
│       ├── footer.css
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       └── product-grid.css
├── images/
│   ├── banners/
│   ├── icons/
│   ├── logo/
│   └── products/
├── index.html
├── README.md
```

## Funcionalidades

- Cabeçalho fixo com logo, categorias e ícones de navegação
- Hero section com destaque para a coleção principal
- Cards de categorias: Casual, Esporte, Moderno e Futurista
- Grid de produtos com estilo editorial e visual premium
- Menu responsivo para telas menores
- Rodapé com formulário de newsletter e navegação por seções
- Visual consistente com identidade de marca orientada para tecnologia e estilo urbano

## Como executar

### Opção 1: abrir diretamente no navegador

Basta abrir o arquivo `index.html` em qualquer navegador moderno.

### Opção 2: rodar um servidor local

No terminal, na pasta do projeto, execute:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

Se preferir, também pode usar a extensão "Live Server" do VS Code para visualizar o projeto em tempo real.

## Personalização

### Alterar cores e tipografia

Os principais ajustes visuais estão em:

- `css/variables.css` — tokens de marca e fontes
- `css/base.css` — estilos gerais do layout
- `css/components/` — estilos específicos de cada seção

### Trocar imagens

As imagens da marca, hero e produtos estão em:

- `images/banners/`
- `images/products/`
- `images/logo/`
- `images/icons/`

### Ajustar textos e marcas

Os textos principais estão no arquivo `index.html`, incluindo:

- nome da loja
- categorias
- chamadas de promoção
- textos de rodapé
- formulários e links

## Melhorias futuras

- adicionar página de produto individual
- implementar carrinho de compras
- criar filtro por categoria e preço
- integrar com backend e banco de dados
- incluir interações em JavaScript para melhor experiência do usuário

## Licença

Este projeto é destinado a fins de estudo e demonstração. O uso comercial depende de autorização explícita do autor ou do time responsável pela criação do design.

## Autor

Projeto desenvolvido como estudo de front-end com foco em e-commerce moderno e landing page premium.
