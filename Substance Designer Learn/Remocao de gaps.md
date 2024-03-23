# Remoção de gaps
Eu particularmente tenho uma certa dificuldade em, remover os gaps deixados no gráfico por nodes como o Edge Detect.
Esse setup simples funcionar em boa parte dos cenários, consiste em :
preencher as linhas com floodFill > flood to randon grayscale > distance.
onde no node Distance, a primeira entrada fica com as linhas antes do flood e a segunda entrada recebe o flood to randon grayscale.

![[./removegaps.png|removegaps.png]]