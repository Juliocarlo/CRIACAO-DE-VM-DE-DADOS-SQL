# CRIACAO-DE-VM-DE-DADOS-SQL
Descreve a criação de uma VM de serviço de banco de dados.

Criando uma máquina virtual de banco de dados no Azure

1- Ao entrar através do portal do Azure, digitar no campo de busca “pesquisa de recursos e documentos “, por banco de dados sql. 
Realizando este procedimento, a opção de máquina virtual do sql Azure irá aparecer nas opções, 
e será possível escolher esta opção pra a criação da máquina virtual de serviços de banco de dados.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/VM%20DE%20BANCO%20DE%20DADOS%20SQL%20FIGURA%201.png

2- Selecionar a opção de SQL DO AZURE e depois escolher a opção de criar máquina virtual.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/SELECIONANDO%20CRIAR%20MAQUNA%20VIRTUAL%20FIGURA%202.png

3- Na etapa seguinte, poderá escolher qual é o serviço de banco de dados ser criado, e que atenderá a demanda necessária para o atendimento ao serviço.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/SELECIONAR%20O%20SERVI%C3%87O%20DESEJADO%20FIGURA%203.png

4- Após escolhido o serviço, a etapa será a criação da configuração dos parâmetros normais de uma VM básica, 
com a escolha de nome do servidor, qual será a autenticação a ser utilizada.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/CONFIGURA%C3%87%C3%83O%20DO%20NOME%20DO%20SERVIDOR%20E%20FORMA%20DE%20AUTENTICA%C3%87%C3%83O%20FIGURA%204.png
https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/CONFIGURA%C3%87%C3%83O%20DO%20NOME%20DO%20SERVIDOR%20E%20FORMA%20DE%20AUTENTICA%C3%87%C3%83O%20FIGURA%204-A.png

5- Configurar a rede a ser utilizada, se deseja ou não regras de Firewall.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/SELECIONANDO%20A%20REDE%20FIGURA%205.png

6- Na aba segurança, definir as credenciais de identidade e de encriptação  da segurança.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/CONFIGURAR%20A%20SEGURAN%C3%87A%20DA%20VM%20DO%20BANCO%20DE%20DADOS%20FIGURA%206.png

7 – Na aba de configurações adicionais definir se deseja utilizar o Microsoft Defender para SQL.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/CONFIGURA%C3%87%C3%95ES%20ADICIONAIS%20DE%20SEGURAN%C3%87A%20FIGURA%207.png

8- Na aba rótulos, criar os rótulos.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/CONFIGURA%C3%87%C3%83O%20DOS%20R%C3%93TULOS%20FIGURA%208.png

9- Na aba revisar e criar, se alguma configuração não estiver de acordo e faltando dados a serem definidos, irá apresentar falha de validação, 
e qual o módulo da criação está a falha, então será necessário ir até este módulo para definir as configurações que não foram realizadas, conforme mostra a figura abaixo.
Basta realizar as configurações que estiverem faltando ou erradas e solicitar nova revisão , se esta revisão estiver tudo corrigido, a VM será criada. 
É importante sempre, ir observando o custo da VM durante a criação, e também o dimensionamento ou utilização de recursos que não serão utilizados, 
pois cada recurso adicionado acarretará um aumento no valor de utilizador da VM. Deve-se atentar para que a utilização seja contido dentro do orçamento designado.

https://github.com/Juliocarlo/CRIACAO-DE-VM-DE-DADOS-SQL/blob/main/REVIS%C3%83O%20E%20CRIA%C3%87%C3%83O%20DA%20VM%20FIGURA%209.png
