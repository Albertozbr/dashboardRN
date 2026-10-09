# RN · Dashboard — Design & Serviços

Dashboard principal de um hub de integração de e-commerce da **RN Design & Serviços**.
O lojista visualiza, em um só lugar, dados unificados das suas contas na **Shopee**,
**Mercado Livre** e **TikTok Shop**.

## ✨ Características

- **Dark mode tecnológico** alinhado à identidade visual oficial da RN
  (tipografia *Montserrat* e gradiente-assinatura ciano → azul `#3fd0e9 → #5a9aee`).
- **KPIs** com contadores animados (faturamento, pedidos pendentes, total de pedidos, ticket médio).
- **Gráficos** em SVG puro: barras de faturamento por dia e donut de vendas por canal.
- **Status das integrações** (Shopee, Mercado Livre, TikTok Shop) com indicador "Conectado".
- **Tabela de pedidos recentes** minimalista com badges de status e plataforma.
- **Animações dinâmicas**: scroll-reveal, barra de progresso de rolagem e micro-interações.
- **Responsivo** e **sem frameworks** — HTML + CSS + JavaScript vanilla em um único arquivo.

## 🚀 Como usar

Abra o arquivo `index.html` em qualquer navegador moderno.
Opcionalmente, sirva localmente:

```bash
python -m http.server 8777
# acesse http://localhost:8777/index.html
```

## 📁 Estrutura

```
dashboardRN/
├── index.html   # Dashboard completo (HTML + CSS + JS)
└── README.md
```

> Protótipo de interface (front-end). Os dados são fictícios e os botões são demonstrativos
> (sem backend).
