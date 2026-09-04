# 🌱 EcoTrend

Site institucional/e-commerce fictício desenvolvido como trabalho acadêmico (FIAP), com foco em **HTML semântico**, **grid CSS** e **acessibilidade**. O EcoTrend apresenta produtos sustentáveis organizados por categoria, com páginas de listagem, detalhe de produto e contato.

## 📄 Sobre o projeto

O EcoTrend é um site estático de vitrine para produtos sustentáveis (roupas, beleza, casa e tecnologia). O projeto foi construído priorizando:

- **HTML5 semântico** — uso correto de `header`, `nav`, `main`, `section`, `article`, `aside`, `figure` e `footer`;
- **Acessibilidade (a11y)** — atributos `aria-label`, `aria-labelledby`, `aria-current` e classes como `visually-hidden`;
- **Layout em grid** — grades responsivas de categorias e produtos construídas com CSS Grid;
- **Responsividade** — breakpoints para telas médias e pequenas.

## 🗂️ Páginas

| Arquivo           | Descrição                                                                 |
|--------------------|----------------------------------------------------------------------------|
| `index.html`       | Página inicial com hero, banner de frete grátis, categorias e produtos em destaque |
| `categoria.html`   | Listagem das categorias de produtos (Roupas, Beleza, Casa, Tecnologia)      |
| `produto.html`     | Página de detalhe de cada produto, com imagem, preço e descrição           |
| `contato.html`     | Formulário de contato e informações institucionais                         |

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3** (grid customizado em `css/style.css`)
- **[Bootstrap 5.3.3](https://getbootstrap.com/)** — via CDN, para utilitários e componentes de formulário
- **[Font Awesome 6.5.2](https://fontawesome.com/)** — via CDN, para ícones

## 📁 Estrutura de pastas

```
ecotrend_grid_semantico/
├── index.html
├── categoria.html
├── produto.html
├── contato.html
├── css/
│   └── style.css
├── LICENSE
└── README.md
```

## 🚀 Como executar

Este é um projeto estático, sem dependências de build ou instalação. Basta:

1. Clonar ou baixar o repositório;
2. Abrir o arquivo `index.html` diretamente no navegador;

ou, para uma experiência mais próxima de um servidor real, servir a pasta localmente:

```bash
# usando Python
python3 -m http.server 8000

# usando Node.js (npx)
npx serve .
```

Depois, acesse `http://localhost:8000` no navegador.

## 📱 Responsividade

O layout em grid se adapta a diferentes tamanhos de tela:

- **Acima de 900px**: grid de 4 colunas para categorias e produtos;
- **Até 900px**: grid de 2 colunas;
- **Até 600px**: grid de 1 coluna e menu de navegação empilhado.

## ⚠️ Observações

- Este é um projeto **acadêmico/demonstrativo**; os produtos, preços e dados de contato são fictícios.
- As imagens dos produtos são carregadas a partir de links externos (Amazon, Bing Images, Karousell) apenas para fins ilustrativos.
- O formulário de contato não possui backend — o atributo `action="#"` é um placeholder.

## 👥 Autores

| Nome                                        |   RM    |
|---------------------------------------------|---------|
| Ryan Romagnoli Santos                       | 568845  |
| Lucas Zarantonelli Lourenço                 | 569164  |
| Felipe Romano de Paula Souza                | 571653  |
| Nicole Barbosa Oliveira de Lima             | 569505  |
| Vinicius Di Tulio Gomes Silva               | 573019  |

## 📜 Licença

Este projeto está licenciado sob a licença [MIT](LICENSE) — © 2026 DiTulio.