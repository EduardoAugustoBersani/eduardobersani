# Portfólio — Eduardo Bersani

Landing page pessoal apresentando meus projetos de **sistemas embarcados, automação industrial e software full-stack**. Do firmware em C++ ao dashboard em TypeScript.

🔗 **Site:** https://eduardoaugustobersani.github.io

## Sobre

Página estática de arquivo único (`index.html`), sem build e sem dependências além das fontes do Google. Tema de painel de instrumento — traço de osciloscópio animado no topo, seções numeradas como endereços de registrador e stack organizada como mapa de registradores.

Construída com HTML, CSS e JavaScript puro (canvas para a animação, IntersectionObserver para os reveals). Responsiva, com foco de teclado visível e `prefers-reduced-motion` respeitado.

## Projetos em destaque

| Projeto | Stack | Repositório |
|---|---|---|
| GATA — Gestão de Atividades do Time de Automação | Next.js · React · TypeScript · Supabase | [gata.v2](https://github.com/EduardoAugustoBersani/gata.v2) |
| Data Logger ESP32 — Sinal Celular | C++ · FreeRTOS · UART · SD/SPI | [datalogger_esp](https://github.com/EduardoAugustoBersani/datalogger_esp) |
| Forest Plot Builder | Next.js · TypeScript · SVG | [Forest-plot-app](https://github.com/EduardoAugustoBersani/Forest-plot-app) |
| Leitor de Sinal — Processador de Tramas | Python · Requests · Regex | [leitordesinalde_internet](https://github.com/EduardoAugustoBersani/leitordesinalde_internet) |
| Calculadora Hídrica | HTML · CSS · JavaScript | [calculadorahidrica](https://github.com/EduardoAugustoBersani/calculadorahidrica) |
| Análise de Dados de Imóveis | Python · Pandas · Matplotlib | [repositório](https://github.com/EduardoAugustoBersani/An-lise-de-dados-de-im-veis-utilizando-a-biblioteca-Pandas) |

## Rodar localmente

Como é uma página estática, basta abrir o arquivo:

```bash
git clone https://github.com/EduardoAugustoBersani/EduardoAugustoBersani.github.io.git
cd EduardoAugustoBersani.github.io
```

Depois é só abrir o `index.html` no navegador. Se preferir servir por HTTP local:

```bash
python -m http.server 8000
# acesse http://localhost:8000
```

## Publicação

Hospedado no **GitHub Pages** a partir do branch `main` (pasta raiz). Qualquer commit no `index.html` atualiza o site publicado automaticamente.

## Contato

- 📧 eng.eduardo.bersani@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/eduardo-bersani/)
- 💬 [WhatsApp](https://wa.me/5518991467813)
