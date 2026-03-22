# MINDHIVE — Pesquisa Recursiva Aplicada

Dashboard interativo para a pesquisa "Sistemas que se observam enquanto operam produzem formas de conhecimento inacessíveis à análise linear".

## O que é

Ferramenta de pesquisa com três camadas:

- **Rizoma** — Grafo force-directed com 38 conceitos e 89 conexões. Nós arrastáveis, editáveis, com detecção de emergência em tempo real.
- **Paper** — Editor estruturado com 10 seções, notas recursivas por seção, e tags de nós do rizoma mobilizados.
- **Memória** — Mapa de decisões, hipóteses, calibrações e tensões acumuladas ao longo da pesquisa.

## Como usar

Abra `index.html` em qualquer navegador moderno. Não precisa de servidor, build, ou dependência local — tudo carrega via CDN.

**Persistência:** Edições (nós, conexões, textos do paper) são salvas automaticamente no `localStorage` do navegador. Se quiser recomeçar do estado original, use o botão `reset` no canto superior direito.

## Deploy (GitHub Pages)

1. Crie um repositório no GitHub (ex: `mindhive-dashboard`)
2. Faça push desta pasta como raiz do repositório
3. Em Settings → Pages, selecione a branch `main` e pasta `/ (root)`
4. Acesse em `https://seu-usuario.github.io/mindhive-dashboard/`

## Stack

- React 18 (CDN)
- D3.js 7 (CDN)
- Tailwind CSS (CDN)
- Babel Standalone (JSX → JS no browser)
- Zero dependências locais

## Contexto

Este dashboard é parte do sistema Mindhive — um ambiente cognitivo modular para pesquisa recursiva aplicada, com foco na plataforma T4P (Tools for Perception) como artefato-tese.

Tradição: Intelligence Amplification (Engelbart → Ashby → Licklider → Clark → Hutchins → 4E Cognition)

---

*Pesquisa em andamento. Open Science.*
