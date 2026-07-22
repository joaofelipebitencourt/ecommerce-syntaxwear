# 👟 SyntaxWear - E-commerce de Tênis e Sneakers

O **SyntaxWear** é uma landing page moderna e responsiva desenvolvida para um e-commerce de tênis e calçados urbanos. O projeto utiliza HTML5 e CSS3 moderno com foco em modularização de estilos, CSS Grid, Flexbox e variáveis CSS para garantir uma manutenção limpa e excelente experiência visual.

---

## 🚀 Funcionalidades e Seções

- **Cabeçalho Responsivo (Header):**
  - Logo vetorial da marca SyntaxWear.
  - Menu de navegação por categorias (*Masculino*, *Feminino*, *Outlet*).
  - Links de acesso rápido (*Nossas Lojas*, *Sobre*, *Minha Conta*, *Ajuda* e *Carrinho*).
  - Menu hambúrguer interativo adaptado para telas menores.

- **Seção Banner Principal (Hero):**
  - Destaque principal do produto *Krypton One*.
  - Botões de chamada para ação (CTAs: "Ver modelos" e "Comprar").
  - Suporte a imagens otimizadas para desktop e mobile.

- **Seção de Categorias em Destaque (Highlights):**
  - Cards com efeito visual para as coleções: *Casual*, *Esporte*, *Moderno* e *Futurista*.

- **Seção de Produtos (Products Section):**
  - Layout em grid organizando produtos e destaques com direcionamento para moda feminina e masculina.

- **Rodapé (Footer):**
  - Seção de inscrição em Newsletter com formulário de e-mail.
  - Links direcionais para redes sociais (*Instagram*, *WhatsApp*, *TikTok*, *Facebook*).
  - Mapa de navegação em colunas para suporte e categorias.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica e acessível.
- **CSS3:**
  - **Variáveis CSS (`variables.css`):** Centralização de cores, espaçamentos e tipografia.
  - **CSS Grid & Flexbox:** Construção e alinhamento dos layouts e grids de produtos.
  - **Modularização de CSS:** Estilos organizados por componentes dentro da pasta `css/components/`.
  - **Design Responsivo (`responsive.css`):** Media queries adaptando a visualização para dispositivos móveis, tablets e desktops.
- **SVG / Mídia:** Ícones vetoriais leves e imagens de alta resolução otimizadas para a web.

---

## 📁 Estrutura de Pastas e Arquivos

```
ecommerce-syntaxwear/
├── css/
│   ├── components/
│   │   ├── footer.css              # Estilização do rodapé e formulário de newsletter
│   │   ├── header.css              # Estilização do cabeçalho e navegação principal
│   │   ├── hero.css                # Estilização do banner principal (hero)
│   │   ├── highlights-section.css  # Estilização dos cards de categorias em destaque
│   │   └── products-section.css    # Estilização do grid de produtos
│   ├── global.css                  # Estilos globais e utilitários
│   ├── reset.css                   # Reset de estilos CSS padrões do navegador
│   ├── responsive.css              # Media queries e ajustes para telas responsivas
│   └── variables.css               # Definição de variáveis CSS (cores, fontes, etc.)
├── images/
│   ├── banners/                    # Imagens de fundo do banner (desktop e mobile)
│   ├── icons/                      # Ícones vetoriais SVG (redes sociais, ações do usuário)
│   ├── logo/                       # Logotipo oficial em SVG
│   └── products/                   # Imagens dos tênis e coleções do catálogo
├── index.html                      # Página principal do projeto
└── README.md                       # Documentação do repositório
```

---

## 💻 Como Executar o Projeto

1. **Baixar ou clonar o repositório:**
   ```bash
   git clone https://github.com/joaofelipebitencourt/ecommerce-syntaxwear.git
   ```

2. **Abrir a aplicação:**
   - Navegue até a pasta do projeto e abra o arquivo `index.html` em qualquer navegador (Chrome, Firefox, Edge, etc.).
   - Alternativamente, utilize a extensão **Live Server** do VS Code para executar com servidor local e recarregamento automático.

---

## 📱 Responsividade

O projeto foi desenvolvido com uma abordagem responsiva adaptando-se a diferentes tamanhos de tela (Smartphones, Tablets e Desktops), ajustando desde a disposição das seções até as imagens exibidas no banner principal.

---

## 📝 Licença

Projeto desenvolvido para fins educacionais e portfólio.