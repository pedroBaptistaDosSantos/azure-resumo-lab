## Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

O conjunto de dimensionamento é necessário para definir a escalabilidade das máquinas.
O número de instâncias, limite de CPU.<br>
Existe a opção de desconto de spot, na qual você utiliza o espaço e o serviço da VM porém com baixa prioridade, podendo ficar indisponível caso outro cliente necessite utilizar de mais recursos no servidor da azure. Essa opção que serve para reduzir custos e pode ser utilizada para testes de desenvolvimento, por exemplo.<br>
Os tamanhos da VM são dividios em Séries, suas descrições nos dizem o melhor uso indicado para cada uma.<br>
Também é preciso criar o disco do SO, esses disco pode ser movido para outra VM caso ache necessário.<br>
Estão disponíveis opções de backup e a área de regras para monitoramento e notificações.<br>
Algumas extensões também estão disponíveis para serem instaladas junto com a máquina.
