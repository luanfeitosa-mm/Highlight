# Highlight Co. — Site Oficial (`highlightco.com.br`)

Site institucional de alta conversão da **Highlight Co.**, construído em arquitetura estática moderna (Dark Mode High-Tech, Tailwind CSS, tipografia `Clash Display` + `Satoshi`, e visualizações interativas em HTML5 Canvas 3D), sem dependência de WordPress/Elementor e pronto para hospedagem direta no **GitHub Pages**.

## Estrutura do Projeto

- `index.html` — Aplicação principal com todas as seções (Hero + Vídeo, Soluções & Posicionamento, Diagnóstico Interativo de Funil, Processo em 5 Etapas, Equação Dinâmica de Growth, Comparativo Sem vs. Com Highlight, Resultados em 90 Dias, Tour Guiada e Seção Founder).
- `assets/favicon.png` — Ícone oficial da marca (`H.`).
- `assets/luan-feitosa.jpg` — Foto do Founder & CEO (Luan Feitosa).
- `assets/hero-video.mp4` — Vídeo de apresentação otimizado para streaming rápido (`fast-start`, 32 MB).
- `CNAME` — Configuração de domínio customizado (`highlightco.com.br`) para o GitHub Pages.

## Como Visualizar Localmente

Basta abrir o arquivo `index.html` no navegador ou rodar um servidor local simples:

```bash
python3 -m http.server 8080
```

E acessar `http://localhost:8080`.

## Como Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `site-highlight` ou `highlightco.com.br`).
2. Conecte este diretório local e envie o código:
   ```bash
   git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   git branch -M main
   git push -u origin main
   ```
3. No GitHub, acesse **Settings → Pages**:
   - Em **Source**, selecione **Deploy from a branch** → branch `main` / `/ (root)`.
   - O arquivo `CNAME` já configurará automaticamente o domínio `highlightco.com.br`.
