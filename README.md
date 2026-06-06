# iPhone 17 (Vite + React + Tailwind)

Projeto front-end feito com Vite + React e Tailwind CSS.

## Preview

<p>
  <img src="./public/img/hero.jpg" alt="Hero" width="100%" />
</p>

<p>
  <img src="./public/img/iphone-blue.jpg" alt="iPhone azul" width="32%" />
  <img src="./public/img/titanium-design.jpg" alt="Design em titânio" width="32%" />
  <img src="./public/img/chip-a18-pro.jpg" alt="Chip A18 Pro" width="32%" />
  <img width="1377" height="953" alt="Captura de Tela 2026-06-06 às 14 33 54" src="https://github.com/user-attachments/assets/0d2553eb-09cd-4d1e-b11d-b2dfc73db54c" />
</p>

## Requisitos

- Node.js: 20.19+ ou 22.12+
- npm: 9+ (recomendado usar npm neste repositório por causa do `package-lock.json`)


## Como rodar localmente

Instalar dependências:

```bash
npm ci
```

Rodar em modo desenvolvimento:

```bash
npm run dev
```

Abrir o endereço que o terminal mostrar (normalmente `http://localhost:5173`).


## Estrutura de pastas

- `src/main.jsx`: ponto de entrada (monta o React no DOM)
- `src/App.jsx`: componente raiz
- `src/components/*`: componentes de UI
- `src/index.css`: estilos globais + Tailwind
- `public/img/*`: assets estáticos (imagens)


