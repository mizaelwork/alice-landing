# Alice Carvalho Nails — Landing Page

Projeto de landing page premium para a marca Alice Carvalho Nails. Direção visual: "luxo silencioso" — navy + dourado + off-white, tipografia editorial (Cormorant Garamond + Calibri), zero estética de infoproduto.

## Arquivo de produção

[variation-alice-1-luxe-teste-melhoria.html](variation-alice-1-luxe-teste-melhoria.html) — versão adotada como padrão. Auto-contida (HTML + CSS + JS inline). Responsiva mobile/tablet/desktop.

[variation-alice-1-luxe.html](variation-alice-1-luxe.html) — baseline antigo, mantido como referência. **Não modificar.**

## Estrutura atual (ordem das seções)

1. **Hero** — navy deep, foto da Alice em moldura arredondada, 3 stats (+1.500 alunas · +5 anos · 205 conteúdos), CTAs "Falar com Alice" (WhatsApp) e "Conhecer formações" (âncora)
2. **Voz da aluna** — vídeo destaque da Marquiele (off-white bg)
3. **Mais alunas** — 3 quote cards (Rafaela com foto, Victoria com foto, 3ª texto)
4. **Além da técnica** — 6 pilares numerados (navy bg)
5. **Sobre Alice** — foto + narrativa CLT 6x1 → autonomia + frase-âncora dourada
6. **Formações** — 4 cards (Blindagem, Molde F1, Presencial "Além da Técnica", Marca Pessoal em breve)
7. **CTA final** — navy, 2 botões (WhatsApp + Voltar às formações)
8. **Footer**

Lógica: filosofia → prova → profundidade → pessoa → oferta. Oferta fica no fim, depois de toda confiança construída.

## Tokens

- **Cores**: navy `#1E3A5F`, navy-deep `#142A47`, gold `#C9A961`, ice-blue `#F5F8FC`, off-white `#FBF9F4`
- **Tipografia**: Cormorant Garamond (títulos, itálico em frases-chave) + Calibri (corpo, kickers caps gold)

## Links reais (já no HTML)

- WhatsApp: `https://wa.me/message/QMVSU4E7AU76F1`
- Checkout Blindagem (R$37,90 / 9× R$5,04): `https://pay.cakto.com.br/ohoz79b_846247`
- Checkout Molde F1 (R$27,90): `https://pay.cakto.com.br/u7d4knp`
- Instagram: `https://www.instagram.com/alicecarvalho.nails/`

## Mídias em uso ([midias/](midias/))

- `alice-curso-1.png` — hero + sobre
- `unhas-blindagem.jpeg` — card Blindagem
- `aplicacao-molde-f1.jpeg` — card Molde F1
- `atendimento-atelier.jpeg` — card Presencial
- `aluna-victoria.jpeg` — card Marca Pessoal + quote Victoria
- `aluna-rafaela.jpeg` — quote Rafaela
- `feedback-marquiele.mp4` — vídeo destaque

Arquivos com espaços/nomes originais ficaram como backup. Sempre renomear novos arquivos pra kebab-case (espaço quebra path em alguns navegadores).

## Como renderizar/testar

- Abrir direto no navegador: `start "" variation-alice-1-luxe-teste-melhoria.html`
- Preview headless: `"C:/Program Files/Google/Chrome/Application/chrome.exe" --headless=new --disable-gpu --hide-scrollbars --window-size=1440,4200 --screenshot=_preview.png file:///c:/Users/Asus/Documents/CLAUDE%20CODE/Alice/variation-alice-1-luxe-teste-melhoria.html`

## Fontes de verdade do conteúdo

- [Design_System_Alice_Carvalho.md](Design_System_Alice_Carvalho.md) — tokens, paleta, princípios visuais
- [content-alice.md](content-alice.md) — copy aprovado, números reais, links

## Pendências

- Bloco antes/depois (removido temporariamente — voltar quando tiver fotos)
- Textos reais dos depoimentos (Rafaela/Victoria/Marquiele) — hoje são plausíveis
- Política de privacidade real no footer (link `#` placeholder)
