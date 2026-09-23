# Identificação Motor-Gerador (trabalho anterior)

Material exploratório anterior ao plano de IC "Identificação e Controle Clássico Linear e Baseado
em Dados de Conversores CC-CC Buck, Boost e Buck-Boost" (ver [Plano](../Plano/PlanoIC02.qmd)):
coleta de sinais PRBS e identificação por mínimos quadrados de uma bancada motor-gerador,
conduzida por Luiz Felipe Souza e Davi.

- `ColetaPRBS.py` — coleta de sinais PRBS via porta serial.
- `conversãocsv.py` — conversão dos dados coletados para CSV.
- `Motor Gerador Indentificação.ipynb` — identificação ARX por mínimos quadrados.
- `Intro.py`, `Intro2.ipynb` — exploração inicial dos dados.
- `Dadosteste1MG.npy`, `PNG_teste1.png` — dados e figura de um teste de coleta.

Mantido como referência; o foco atual do plano de IC é a identificação e o controle dos
conversores Buck, Boost e Buck-Boost (ver [Identificacao](../Identificacao/) e [Controle](../Controle/)).
