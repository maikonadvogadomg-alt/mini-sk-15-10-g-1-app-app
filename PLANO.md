# 📋 Plano do projeto: mini-sk-15-10-g-1-app

_Gerado em 15/10/2026, 17:14:00 — sem IA, lendo os arquivos._

## 📊 Visão geral
| Item | Valor |
|---|---|
| Arquivos | 72 |
| Linhas | 11.413 |
| Telas/páginas | 2 |
| Rotas do backend | 0 |
| Chamadas do app | 0 |
| Tabelas do banco | 0 |
| Variáveis de ambiente | 3 |

**Linguagens:** JavaScript (42), Imagem (15), JSON (3), YAML (2), Outros (2), HTML (2), Imagem SVG (2), Markdown (2), CSS (1), Ícone (1)

## 💡 O que fazer (em ordem)
1. 🧹 Tirar a Replit de 13 arquivo(s) (🏗️ Preparar → Fazer tudo)
2. 🔐 Criar um .env.example com: BASE_PATH, GITHUB_STEP_SUMMARY, TESTE_SAIR (os valores você coloca no servidor, nunca no código)
3. 📝 Criar um README.md explicando como rodar

## 🚀 Por onde começa
- `index.html`

## ⌨️ Comandos (package.json)
| Pasta | Comando | O que roda |
|---|---|---|
| . | `npm run desktop` | `electron .` |
| . | `npm run exe` | `electron-builder --win portable --publish never` |

## 📱 Telas e páginas
| Endereço | Arquivo |
|---|---|
| `hub.html` | hub.html |
| `index.html` | index.html |

## 🖥️ Rotas do backend
_Nenhum encontrado._

## 📡 O que o app pede ao servidor
_Nenhum encontrado._

## 🔌 O que falta no backend
✅ Tudo que o app chama tem rota no projeto (ou o app não usa servidor).

## 🗄️ Banco de dados
_Nenhuma tabela encontrada._

## 🔐 Variáveis de ambiente (configurar no servidor)
- `BASE_PATH`
- `GITHUB_STEP_SUMMARY`
- `TESTE_SAIR`

_Só os nomes. Os valores (chaves, senhas) nunca vão no código nem no GitHub._

## 🤖 IA usada
- api.groq.com
- console.groq.com
- generativelanguage.googleapis.com
- openrouter.ai
- api.anthropic.com
- console.anthropic.com
- api.openai.com
- platform.openai.com

## 🌐 Serviços de fora que ele acessa
- aistudio.google.com
- api.anthropic.com
- api.exemplo.com
- api.expo.dev
- api.github.com
- api.groq.com
- api.npms.io
- api.openai.com
- api.perplexity.ai
- api.x.ai
- appassets.androidplatform.net
- cdn.jsdelivr.net
- cdn.tailwindcss.com
- console.anthropic.com
- console.groq.com
- console.x.ai
- esm.sh
- expo.dev
- generativelanguage.googleapis.com
- github.com
- mail.google.com
- ollama.com
- openapi.monica.im
- openrouter.ai
- platform.monica.im
- platform.openai.com
- registry.npmjs.org
- seu-usuario.github.io
- u.expo.dev
- unpkg.com
- www.google.com
- www.npmjs.com
- www.perplexity.ai
- xxxx.supabase.co

## 🧹 Arquivos com coisa da Replit
- js/70-search.js
- js/80-ai.js
- js/86-terminal.js
- js/86c-termux.js
- js/88-inventario.js
- js/90-github.js
- js/95-pwa.js
- js/96b-eas.js
- js/96c-preparar.js
- js/97-analise.js
- js/lib/expo-core.js
- js/lib/plano-core.js
- service-worker.js

## 🔁 Roteiro para recriar fora da Replit
1. Importar o projeto no Mini SK e tocar em 🏗️ Preparar → ✅ Fazer tudo (tira a Replit, cria os arquivos que faltam).
2. Não tem backend: o site sozinho basta (Netlify ou GitHub Pages).
3. Variáveis: cadastrar 3 variável(is) no servidor (lista acima).
4. Testar a prévia; se der erro, 🤖 Mandar os erros para a IA.
5. App: 📲 Instalável (PWA), 📦 APK ou 🖥️ Desktop (.exe) pelo 🏗️ Preparar.

## 🌳 Árvore de arquivos
```
├─ 📁 .github/
│  └─ 📁 workflows/
│     ├─ apk.yml
│     └─ desktop-exe.yml
├─ 📁 css/
│  └─ app.css
├─ 📁 electron/
│  ├─ main.cjs
│  └─ preload.cjs
├─ 📁 icons/
│  ├─ apple-touch-icon.png
│  ├─ icon-128.png
│  ├─ icon-144.png
│  ├─ icon-152.png
│  ├─ icon-16.png
│  ├─ icon-180.png
│  ├─ icon-192.png
│  ├─ icon-32.png
│  ├─ icon-384.png
│  ├─ icon-48.png
│  ├─ icon-512.png
│  ├─ icon-72.png
│  ├─ icon-96.png
│  ├─ icon.svg
│  ├─ maskable-192.png
│  ├─ maskable-512.png
│  └─ maskable.svg
├─ 📁 js/
│  ├─ 📁 lib/
│  │  ├─ expo-core.js
│  │  ├─ nacl-fast.min.js
│  │  ├─ plano-core.js
│  │  └─ selar.js
│  ├─ 00-core.js
│  ├─ 04-conta.js
│  ├─ 10-fs.js
│  ├─ 20-zip.js
│  ├─ 30-highlight.js
│  ├─ 40-editor.js
│  ├─ 50-tree.js
│  ├─ 60-preview.js
│  ├─ 61-tsx.js
│  ├─ 70-search.js
│  ├─ 80-ai.js
│  ├─ 81-gasto.js
│  ├─ 83-voz.js
│  ├─ 84-ponte.js
│  ├─ 85-checkpoints.js
│  ├─ 86-terminal.js
│  ├─ 86b-node.js
│  ├─ 86c-termux.js
│  ├─ 86e-atalhos.js
│  ├─ 87-links.js
│  ├─ 88-inventario.js
│  ├─ 89-config.js
│  ├─ 90-github.js
│  ├─ 91-acoes.js
│  ├─ 92-playground.js
│  ├─ 93-conversa.js
│  ├─ 94-fatiador.js
│  ├─ 95-pwa.js
│  ├─ 96-apk.js
│  ├─ 96b-eas.js
│  ├─ 96c-preparar.js
│  ├─ 97-analise.js
│  ├─ 98-api.js
│  └─ 99-app.js
├─ .gitignore
├─ apk.config.json
├─ favicon.ico
├─ hub.html
├─ hub.webmanifest
├─ index.html
├─ LEIA-ME.md
├─ manifest.json
├─ package.json
├─ PLANO.md
├─ service-worker.js
└─ sw.js
```
