# Ilustrações do site institucional

Ferramenta: `image_gen` integrada, sem CLI. Referências: `evidencia-temporal.png` e `mapa-estabelecimentos.png`.

Arquivos finais:
- `visao-regional-compacta.png`: versão aplicada ao topo com 60 pixels de espaço vazio removidos entre os indicadores e o cabeçalho territorial, sem redimensionar o conteúdo.
- `evidencia-temporal-ilustracao.png`: ilustração da linha do tempo. Os valores inteiros correspondem aos valores originais, cujos centavos são zero.
- `mapa-cabecalho-ia.png`: composição quadrada do cabeçalho com a área cartográfica original, preservando os créditos do mapa.

## Indicadores regionais — geração integrada

Resultado aplicado em `visao-regional-compacta.png`. Os seis indicadores foram redesenhados com os mesmos rótulos e valores. A composição final preserva o cabeçalho aprovado e a área cartográfica anterior.

Use case: ui-mockup. Generate ONLY a high-resolution horizontal dashboard METRICS PANEL, aspect ratio 2.5:1 (about 2048x820), no map or page title. This will replace the six dark-blue cards at the very top of reference image 1; reference image 2 is the APPROVED visual style to match. Full bleed flat white canvas, not a screenshot of a device. Match the pale grey and pale mint cards, bold navy #14213D typography, deep green #0B3D2E accents, Inter-like sans-serif from reference 2. No dark-blue filled cards. Exactly SIX equal rounded rectangular cards in a precise THREE COLUMNS by TWO ROWS grid, about 40px outer padding and 26px gutters. All cards pale mint or pale grey with subtle thin grey-green borders, no shadows. Large readable labels and large bold numbers. The whole panel must be readable when reduced to 500px wide, so use large clear text, not tiny metadata. Preserve these real numbers EXACTLY, Brazilian thousands periods and decimal comma:
TOP LEFT label "Estabelecimentos ativos", value "270.411".
TOP MIDDLE label "Empresas distintas", value "261.687".
TOP RIGHT label "Municípios com presença", value "35".
BOTTOM LEFT label "Matrizes · filiais", value "257.979 · 12.432" (may wrap between the two values to avoid small text).
BOTTOM MIDDLE label "MEI · Simples · demais", with THREE legible stacked rows: "MEI 134.666", "Simples 72.724", "Demais 26.377". These values must not be merged or repeated elsewhere.
BOTTOM RIGHT label "Cobertura geográfica", value "95,18%".
Labels should be at least 48px at a 2048px wide canvas, headline values about 100px; grouped values can use about 65px so they fit. Use line breaks in long labels. No extra labels, numbers, charts, icons, totals, dates, buttons, logos or decorations. Fill panel efficiently and align typography precisely. Recreate only this metrics strip, not the remaining map or the distribution header in reference 1.

## Linha do tempo — prompt de criação

Use case: ui-mockup. Create a high-resolution SQUARE 2048x2048 PNG illustration for a Brazilian enterprise-history product called Rastro PJ. The attached image is a fidelity reference for style and real event values, not a target to preserve pixel for pixel. Recompose as a beautiful flat front-facing product interface, edge-to-edge white canvas, no outer frame, no perspective, no device, no shadows, no empty letterboxing. Navy #14213D typography, deep green #0B3D2E timeline, pale green #E5F3EC after-cards, pale grey before-cards. Crisp Inter-like sans serif. This image is displayed at about 550 CSS pixels wide: make all text large and legible. Only TWO stacked event sections filling the square, with thin vertical green timeline at left and circular event markers. Generous but efficient padding of about 90 px. Top eyebrow exact text "EVIDÊNCIA TEMPORAL". Large title exact "Linha do tempo". Short subtitle exact "Veja o que mudou, mês a mês." First event date "07/2026 → 08/2026", bold heading "Aumento de capital social", then two equal side-by-side boxes connected by a right arrow: left label "Antes", value EXACT "R$ 5.609.845.717,00"; right label "Depois", value EXACT "R$ 9.507.625.217,00". Second event date "06/2026 → 07/2026", bold heading "Saída de sócio", then two equal side-by-side boxes connected by arrow: left label "Antes", text "Participação registrada"; right label "Depois", text "Participação não consta mais". Use line wrapping within boxes to make all values readable. The second wording illustrates the real exit event in the source without inventing a name. All accents, date intervals and numbers must be verbatim. Keep the top header around upper fifth, first event middle upper section, second event lower section. Do not invent extra metrics, buttons, charts, logos, people, or tiny fine print. Fill entire square with this clear interface illustration.

## Linha do tempo — ajuste final dos valores

Edit this square illustration. ONLY modify the text inside the two monetary value cards. Delete the trailing ".00" from BOTH amounts. Use Brazilian formatting without cents. Exact left amount must read "R$ 5.609.845.717". Exact right amount must read "R$ 9.507.625.217". Do not append decimals or cents, because all cents are zero and must be OMITTED. Maintain all other text, dates, layout, colors, shapes and image proportions. High resolution crisp UI illustration.

## Cabeçalho do mapa — prompt final

Generate ONLY a full-bleed flat white map UI HEADER, exactly a wide rectangle with aspect ratio 2.5:1, high resolution about 2048x820. Reference supplies palette and terminology but RECOMPOSE to make the legend much larger. This header is displayed only 550px wide, so text MUST be readable there. Use navy #14213D, green #0B3D2E, Inter-like sans-serif. 70px padding maximum; no huge empty area above or below. Top small eyebrow at font size 48px exact "INTELIGÊNCIA TERRITORIAL". Title at font size 110px bold exact "Distribuição espacial". Below title thin divider. Lower area divided into two columns: left 40% width, title at font size 62px bold exact "Concentração" and large horizontal light-green to dark-green gradient with labels "Menor" and "Maior" at font size 56px. Right 56% width, exactly THREE VERTICALLY STACKED legend rows, NOT in one horizontal line. Each legend row must have at least 62px font size and a 45px circular dot: green dot "Endereço CNEFE"; golden dot "Aproximação por CEP"; navy dot "Agrupamento por CEP". Use about 90px row height. Large, bold, exceptionally legible labels, accents correct. Fill the rectangle efficiently. No map, no extra text, no totals, no icons other than circles, no perspective, no borders, no device. Style matches source but prioritize larger type over faithful original spacing.
