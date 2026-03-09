# SyntaxWear - E-commerce de Tênis e Sneakers

## Descrição

SyntaxWear é um site de e-commerce dedicado à venda de tênis e sneakers online. O projeto apresenta um design moderno e responsivo, focado em oferecer uma experiência de compra intuitiva e atrativa. O site inclui seções como hero banner, categorias de produtos, grid de produtos em destaque e footer com navegação e newsletter.

Este é um projeto front-end estático, desenvolvido com HTML e CSS modular, sem dependências de JavaScript ou frameworks externos.

## Funcionalidades

- **Header Responsivo**: Navegação principal com menu mobile, links para categorias (Masculino, Feminino, Outlet) e ícones de acesso rápido (conta, ajuda, carrinho).
- **Seção Hero**: Banner promocional com chamada para ação para visualizar modelos e comprar.
- **Categorias de Produtos**: Seções para estilos Casual, Esporte, Moderno e Futurista.
- **Grid de Produtos**: Destaque de produtos com títulos, subtítulos e links para gêneros.
- **Footer**: Formulário de newsletter, links para redes sociais e navegação organizada por categorias.

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica do site.
- **CSS3**: Estilos modulares organizados em arquivos separados para melhor manutenção.
  - `reset.css`: Reset de estilos padrão.
  - `variables.css`: Definição de variáveis CSS para cores, fontes, etc.
  - `base.css`: Estilos base.
  - `layout.css`: Layout geral.
  - Componentes: `header.css`, `hero.css`, `product-category.css`, `product-grid.css`, `footer.css`.

## Estrutura do Projeto

```
ecommerce-syntaxwear/
├── index.html                 # Arquivo principal do site
├── README.md                  # Este arquivo
├── css/
│   ├── reset.css              # Reset de estilos
│   ├── variables.css          # Variáveis CSS
│   ├── base.css               # Estilos base
│   ├── layout.css             # Layout geral
│   └── componetents/          # Estilos de componentes
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       ├── product-grid.css
│       └── footer.css
└── images/
    ├── banners/               # Imagens de banners
    ├── favicons/              # Favicons
    ├── icons/                 # Ícones (menu, redes sociais, etc.)
    ├── logo/                  # Logo do site
    └── products/              # Imagens de produtos
```

## Como Executar o Projeto

Como este é um site estático, não há necessidade de instalação de dependências ou servidor. Basta abrir o arquivo `index.html` em qualquer navegador web moderno.

1. Clone ou baixe o repositório.
2. Navegue até a pasta do projeto.
3. Abra o arquivo `index.html` no seu navegador preferido.

Para desenvolvimento, você pode usar um servidor local simples, como o Live Server do VS Code, para recarregar automaticamente as mudanças.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## Autor

Desenvolvido por Samuel como parte do projeto DevQuest 2.0.