# Cafeteria Verde


Este repositório contém o projeto do curso de Ánalise e Desenvolvimento de Sistemas, tema: **Cafeteria Verde**, com foco em CSS3, design system e responsividade.


## 📁 Estrutura de Pastas
```
meu-projeto-cafeteria/
├── index.html
├── about.html
├── contato.html
├── css/
│ ├── variables.css # Variáveis de cores, tipografia e espaçamento
│ ├── layout.css # Grid, Flexbox e responsividade
│ ├── components.css # Botões, cards, formulários, badges, modais
│ ├── utilities.css # Classes utilitárias e helpers
│ └── style.css # Arquivo principal que importa todos os módulos
└── imagens/ # Logos, hero, placeholders de produtos
```


## 🎨 Design System
- **Paleta de cores:** tons de cinza e verde (8 cores definidas)
- **Tipografia:** 5 tamanhos hierárquicos de fonte
- **Espaçamento modular:** 8px, 16px, 24px, 32px, 48px, 64px


## 🧱 Layout Responsivo
- Grid principal com 12 colunas
- Flexbox para alinhamento interno dos componentes
- 5 breakpoints: 1200px, 992px, 768px, 576px, 400px
- Layouts específicos para hero, cards, formulários e seções de contato


## 🧭 Navegação Interativa
- Menu principal com submenu dropdown
- Menu mobile com botão hambúrguer
- Acessibilidade com `aria` e foco visível


## 💳 Componentes de Interface
- Cards de produtos responsivos
- Botões com estados (hover, focus, active, disabled)
- Formulários estilizados com validação visual
- Feedback visual: alerts, toasts e modais
- Sistema de badges/tags para categorias de produtos
