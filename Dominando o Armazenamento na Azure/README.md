## Dominando o Armazenamento na Azure

A conta de armazenamento inclui os blobs, arquivos filas e tabelas. Deve ter um nome exclusivo que permite que seja acessado por http ou https. <br>
Conta possui modelo standard ou premium. A opção premium oferece melhor performance e cobra o espaço total de armazenamento, não somente o utilizado.<br>
A zona de redundância da conta de armazenamento também pode ser configurada, definindo em quais datacenters ficará disponível.<br> 
Também é possível configurar a retenção dos objetos(tempo que vai ficar disponível para restauração após a exclusão).<br>
Para migrações, o azure disponibiliza algumas ferramentas como azcopy , storage explorer ou em casos com mais arquivos databox e databox heavy.