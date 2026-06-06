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

## Scripts

```bash
npm run dev       # servidor de desenvolvimento (HMR)
npm run build     # build de produção
npm run preview   # preview do build localmente
npm run lint      # eslint
```

## Estrutura de pastas

- `src/main.jsx`: ponto de entrada (monta o React no DOM)
- `src/App.jsx`: componente raiz
- `src/components/*`: componentes de UI
- `src/index.css`: estilos globais + Tailwind
- `public/img/*`: assets estáticos (imagens)

## Subindo para o GitHub/GitLab

Se você ainda não inicializou o git neste projeto:

```bash
git init
git add .
git commit -m "chore: initial commit"
```

Depois, crie o repositório remoto e aponte o `origin`:

```bash
git remote add origin <URL_DO_REPOSITORIO>
git branch -M main
git push -u origin main
```

## Observações

- Se você usar outro gerenciador (pnpm/yarn), remova lockfiles conflitantes e mantenha apenas um. Aqui o padrão é npm (`package-lock.json`).
