# Design System · Alice Carvalho

**Conceito:** Azul chique delicado — marinho profundo + dourado champagne, com tipografia clássica em itálico para o toque sofisticado.

---

## Paleta de cores

| Token | HEX | Uso |
|---|---|---|
| Navy | `#1E3A5F` | Cor primária. Fundos de divisores de capítulo, blocos de destaque, títulos. |
| Blue | `#4A6FA5` | Azul médio. Acentos em listas e textos secundários sobre fundo claro. |
| Soft Blue | `#7BA3C9` | Azul suave. Subtítulos sobre navy, bordas finas em cards. |
| Pale Blue | `#EAF0F7` | Azul pálido. Watermarks gigantes, textos sutis sobre navy. |
| Ice Blue | `#F5F8FC` | Azul quase branco. Fundos de cards, painéis laterais. |
| Gold | `#C9A961` | Dourado champagne. Acento principal — kickers, linhas decorativas, números, ovais. |
| Gold Soft | `#E0CFA0` | Dourado claro. Labels secundárias sobre navy. |
| Dark | `#2C3E50` | Texto corpo principal sobre fundo claro. |
| Muted | `#6B7C93` | Texto descritivo, legendas, rodapés. |
| White | `#FFFFFF` | Fundo dos slides de conteúdo. Texto sobre navy. |

**Regra de dominância:** Navy + branco dominam (60-70%). Soft blue + ice blue como suporte (20-25%). Dourado é acento (5-10%) — usado em linhas finas, marcadores, kickers. **Nunca** use dourado para blocos grandes.

---

## Tipografia

| Família | Função |
|---|---|
| **Georgia** | Headers. Sempre em itálico nos títulos principais para o ar chique. |
| **Calibri** | Corpo, listas, labels em caixa alta. |
| **Calibri Light** | Subtítulos, descrições secundárias, legendas. |

### Escala

| Elemento | Tamanho | Peso | Cor |
|---|---|---|---|
| Título da capa | 48pt | Georgia itálico | White |
| Subtítulo da capa | 32pt | Georgia | Soft Blue |
| Número de capítulo (divisor) | 90pt | Georgia itálico | Gold |
| Título de divisor | 38pt | Georgia | White |
| Título de slide | 28pt | Georgia | Navy |
| Destaques em itálico | 18-22pt | Georgia itálico | Navy |
| Watermark de passo | 150pt | Georgia itálico | Pale Blue |
| Corpo | 13pt | Calibri | Dark |
| Lista | 12-14pt | Calibri | Dark |
| Kicker (caixa alta) | 9-11pt | Calibri bold | Gold |
| Rodapé / paginação | 9pt | Calibri Light | Muted |

**Char spacing:** Para labels em caixa alta (kickers, footers), aplicar `charSpacing: 4 a 8` para o ar editorial.

---

## Motivos visuais (repetir em todo o deck)

1. **Marca dourada no canto superior direito** — dois círculos pequenos (gold + soft blue) em todos os slides claros. Funciona como assinatura silenciosa.
2. **Linha curta dourada** — 0.5" de largura, 0.025" de altura, abaixo de títulos e dentro de cards. **Nunca** linha que atravessa o slide inteiro.
3. **Faixa lateral dourada** nos divisores de capítulo — 0.08" de largura, altura total.
4. **Itálico Georgia** para títulos e frases-chave — assina o tom chique.
5. **Aspas tipográficas grandes** (60-90pt) em dourado para citações dentro de cards navy.

---

## Layouts (templates)

### 1. Slide de divisor de capítulo
Fundo navy, faixa dourada lateral, número grande em itálico dourado, label em caixa alta soft blue, título grande em branco, subtítulo opcional em pale blue. Assinatura "Alice Carvalho" no rodapé em gold soft.

### 2. Slide de conteúdo padrão
Fundo branco, barra superior fina navy (0.04"), marca dourada no canto, kicker dourado + título navy + linha curta dourada. Conteúdo abaixo de y=1.95".

### 3. Slide de duas colunas (comparação)
Coluna ice blue à esquerda + coluna navy à direita. Mesma altura (3.0"). Conteúdo da esquerda em tom suave; conteúdo da direita em branco/dourado.

### 4. Slide de grid de cards (3, 4 ou 5 itens)
Cards brancos com borda fina soft blue. Pequeno acento dourado no topo. Número em Georgia itálico dourado, depois título em navy bold.

### 5. Slide de passo com watermark
Número gigante itálico em pale blue à esquerda (150pt). Título e bullets à direita.

### 6. Capa e encerramento
Fundo navy com formas ovais translúcidas decorativas (blue + gold com 70-85% transparência). Hierarquia centralizada com nome em dourado itálico.

---

## Espaçamento

- Margem mínima das bordas: **0.5"**
- Margem padrão lateral: **0.6"–0.7"**
- Gap entre blocos: **0.3"–0.5"**
- Altura padrão de card de conteúdo: **3.0"**
- Conteúdo principal começa em y = **1.95"–2.0"**
- Rodapé / paginação em y = **5.25"**

---

## Acentos e formas

| Elemento | Especificação |
|---|---|
| Card padrão | `RECTANGLE`, fill ice blue ou white, borda 0.5pt soft blue |
| Card de destaque | `RECTANGLE`, fill navy, sem borda |
| Pílula | `ROUNDED_RECTANGLE`, `rectRadius: 0.08` |
| Bolinha decorativa | `OVAL` 0.12–0.18" — sempre em dourado |
| Linha de acento | `RECTANGLE` 0.5×0.025" em dourado |

---

## Princípios

1. **Whitespace é luxo.** Nunca preencher cada centímetro — o vazio comunica sofisticação.
2. **Dourado em microdoses.** Sempre como acento (linha, ponto, kicker), nunca em bloco.
3. **Itálico = elegância.** Reserve para títulos e frases-chave, nunca para corpo.
4. **Cantos arredondados raros.** Use `ROUNDED_RECTANGLE` apenas em pílulas; o restante é retangular limpo.
5. **Navy carrega autoridade.** Slides escuros para abertura, fechamento e citações. Slides claros para o conteúdo "respirar".
6. **Repita o motivo.** As bolinhas no canto e a linha dourada curta aparecem em todos os slides — é o que faz o conjunto parecer um sistema, não um amontoado.

---

*Material complementar — Curso Molde F1 · Alice Carvalho*
