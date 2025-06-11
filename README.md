# smarketing-frontend

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```


### 프로젝트 구조
ai-marketing-frontend/
├── public/
│   ├── images/
│   │   ├── logo192.png
│   │   ├── millie.png
│   │   ├── netflix.png
│   │   ├── liker.png
│   │   ├── collector.png
│   │   └── addict.png
│   ├── index.html
│   ├── manifest.json
│   └── runtime-env.js
├── src/
│   ├── components/
│   │   ├── common/
│   │   │   ├── Header.js
│   │   │   ├── Layout.js
│   │   │   └── LoadingSpinner.js
│   │   ├── auth/
│   │   │   ├── LoginForm.js
│   │   │   └── RegisterForm.js
│   │   ├── dashboard/
│   │   │   ├── Dashboard.js
│   │   │   ├── SalesChart.js
│   │   │   └── ActivityList.js
│   │   ├── store/
│   │   │   ├── StoreInfo.js
│   │   │   └── MenuList.js
│   │   ├── content/
│   │   │   ├── ContentCreate.js
│   │   │   ├── ContentList.js
│   │   │   └── ContentDetail.js
│   │   └── recommendation/
│   │       └── AIRecommendation.js
│   ├── pages/
│   │   ├── LoginPage.js
│   │   ├── RegisterPage.js
│   │   ├── DashboardPage.js
│   │   ├── StoreManagePage.js
│   │   ├── MenuManagePage.js
│   │   ├── ContentCreatePage.js
│   │   ├── ContentListPage.js
│   │   └── AIRecommendationPage.js
│   ├── services/
│   │   ├── api.js
│   │   ├── authService.js
│   │   ├── storeService.js
│   │   ├── contentService.js
│   │   └── recommendationService.js
│   ├── hooks/
│   │   ├── useAuth.js
│   │   └── useApi.js
│   ├── utils/
│   │   ├── formatters.js
│   │   └── validators.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
├── .gitignore
└── README.md
