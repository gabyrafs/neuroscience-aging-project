# Hub de Estudos Interativos em Neurociência

Repositório de materiais didáticos em **HTML autônomo** (single-file por página, sem build e sem dependências externas além de Google Fonts) para estudo e ensino na graduação de Medicina.

## Como usar

1. Abra o arquivo `index.html` (ou `./index.html`) diretamente no navegador.
2. Clique em um card para entrar no módulo.
3. Navegue pelas abas internas (Fundamento/Neurobiologia, Mecanismo, Aplicação clínica, Caso/Quiz interativo).

> Os conteúdos têm finalidade didática e **não substituem diretrizes clínicas**, protocolos institucionais ou supervisão docente/preceptoria.

## Estrutura

- `index.html` — hub inicial com cards e links para os módulos.
- `modulos/`
  - `neuroanatomia-funcional.html`
  - `neuronio-e-sinapse.html`
  - `sistemas-de-neurotransmissores.html`
  - `neurociencia-cognitiva.html`
  - `desenvolvimento-e-envelhecimento.html`
  - `introducao-doencas-neurologicas.html`
- `README.md`
- `.gitignore`

## Módulos

1. **Neuroanatomia funcional** — organização do SNC, lobos, vias e sistema límbico.
2. **Neurônio e sinapse** — potencial de ação, neurotransmissão e plasticidade.
3. **Sistemas de neurotransmissores** — colinérgico, dopaminérgico, serotoninérgico, GABA/glutamato.
4. **Neurociência cognitiva** — memória, atenção, linguagem e funções executivas.
5. **Neurociência do desenvolvimento e do envelhecimento** — neuroplasticidade ao longo da vida.
6. **Introdução às doenças neurológicas** — princípios de neuropatologia.

## Observações de design e acessibilidade

- Tema escuro consistente (`#0a0e1a`, `#111827`, `#1a2235`).
- Tipografia: Playfair Display (títulos), DM Sans (texto), DM Mono (rótulos).
- Layout responsivo com cards, tabelas, alertas e quizzes com feedback comentado.
- Cada módulo possui header sticky, barra de progresso e interação em JavaScript puro.
