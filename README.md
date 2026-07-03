Este  trabalho  apresenta  uma  abordagem  baseada  em  Inteligência  Artificial  (IA)  para 
apoio  à  tomada  de  decisão  no  mercado  acionário  brasileiro,  utilizando  informações 
contábeis  trimestrais  de  empresas  listadas  na  B3  (Brasil,  Bolsa,  Balcão).  Os  dados 
foram  obtidos  no  portal  fundamentus.com.br,  compreendendo  balanços  patrimoniais 
e  Demonstrações  do  Resultado  do  Exercício  (DRE)  referentes  ao  período  histórico 
de 2012 até o ano de 2023. 
Após  a  aquisição,  os  dados  passaram  por  etapas  de  tratamento,  limpeza, 
integração,  normalização  e  engenharia  de  atributos  utilizando  a  linguagem  Python  e 
bibliotecas  como  Pandas,  NumPy  e  Scikit-learn,  permitindo  a  construção  de  uma 
base  adequada  ao  treinamento  de  modelos  de  aprendizado  de  máquina.  Foram 
avaliados  diferentes  algoritmos  amplamente  empregados  em  aplicações  financeiras, 
incluindo  Árvore  de  Decisão,  Regressão  Logística,  K-Nearest  Neighbors  (KNN), 
Naive  Bayes,  Support  Vector  Machine  (SVM)  e  Random  Forest,  com  o  objetivo  de 
identificar  o  modelo  de  melhor  desempenho  para  classificação  de  ativos  com 
potencial  de  valorização  superior  ao  índice  Ibovespa  (IBOV)  no  trimestre 
subsequente. 
Após  a  comparação  dos  modelos  por  meio  de  métricas  de  desempenho,  o  algoritmo 
Random  Forest  foi  selecionado  e  posteriormente  otimizado  por  ajuste  de 
hiperparâmetros,  obtendo  melhorias  significativas  na  acurácia  e  na  precisão  das 
previsões.  A  validação  prática  foi  realizada  por  meio  da  simulação  de  uma  carteira 
de  investimentos  construída  a  partir  das  recomendações  do  modelo,  cujo 
desempenho  foi  comparado  ao  índice  de  referência  do  mercado.  Os  resultados 
demonstraram  que  a  metodologia  proposta  foi  capaz  de  selecionar  ativos  que 
proporcionam  rentabilidade  superior  ao  Ibovespa  no  período  analisado, 
evidenciando  o  potencial  da  Inteligência  Artificial  como  ferramenta  de  apoio  à 
análise fundamentalista e à tomada de decisão no mercado financeiro. 
