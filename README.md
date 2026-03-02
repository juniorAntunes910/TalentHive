# 💼 TalentHive — Landing Page Responsiva (Mobile First)

Projeto desenvolvido para a atividade prática de Front-End com foco em **Mobile First**, **HTML5**, **CSS3** e uso de **variáveis CSS**.

O layout replica o design proposto no Figma, simulando uma landing page moderna para um aplicativo de busca de empregos.

---

## 🎯 Objetivo da Atividade

Construir o front-end fiel ao design fornecido, aplicando:

- ✅ Abordagem **Mobile First**
- ✅ Layout Responsivo (Mobile → Tablet → Desktop)
- ✅ Variáveis CSS
- ✅ Estrutura semântica
- ✅ Boas práticas de organização

---

## 🖌 Sobre o Design

O layout representa uma landing page de aplicativo chamada **TalentHive**, contendo:

- Hero Section com destaque principal
- Mockups do aplicativo
- Seção explicativa com vídeo
- Seção de benefícios
- Footer com CTA (Call To Action)

A estrutura foi desenvolvida pensando primeiro na versão mobile e depois expandida para telas maiores.

---

## 🧠 Conceitos Aplicados

### 📱 Mobile First

O projeto foi iniciado pela versão mobile e adaptado para telas maiores utilizando media queries baseadas em `min-width`.

Exemplo:

```css
@media (min-width: 768px) {
  /* ajustes para tablet */
}

@media (min-width: 1024px) {
  /* ajustes para desktop */
}

:root {
  --color-primary: #4f7cff;
  --color-secondary: #f5f5f5;
  --color-dark: #111111;
  --color-light: #ffffff;

  --font-primary: 'Inter', sans-serif;

  --spacing-sm: 0.5rem;
  --spacing-md: 1rem;
  --spacing-lg: 2rem;
}

📁 talenthive
 ├── index.html
 ├── style.css
 ├── 📁 assets
 │     ├── images
 │     └── icons
 └── README.md
