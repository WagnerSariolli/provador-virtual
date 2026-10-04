# Provador Sob Medida

Loja de moda feminina com provador virtual. A cliente informa suas medidas, e um manequim de costureira assume essas proporções. Ao escolher peça, cor e tamanho, a roupa aparece vestida no manequim, mostrando:

- onde aperta, onde fica justinha, onde está ideal e onde sobra tecido (com os centímetros de cada região);
- onde a barra termina (joelho, midi, tornozelo) ou se a calça vai precisar de barra;
- o tamanho sugerido para as medidas informadas;
- uma nota de compatibilidade com o perfil (biotipo, altura, caimento e subtom de pele).

## Como usar

É um único arquivo HTML, sem dependências nem build. Abra `index.html` no navegador.

## Observações

- Tabelas de medidas, preços e regras de estilo são dados de exemplo; troque o array `PRODUCTS` pelas tabelas reais de cada peça.
- O desenho é uma vista frontal em 2D que converte circunferência em largura com proporções fixas. Serve para comparar caimento, não é uma simulação física do tecido.
- A sacola é demonstrativa: nenhum pagamento é processado.
