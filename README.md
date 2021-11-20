#ÁREAS DENTRO DO GIT

<b>Diretório de trabalho/arquivos (pasta):</b>

- Modificados
- Excluídos
- Adicionados 

Os arquivos presentes nessa etapa ainda não estão garantidos pelo GIT, ou seja, em caso de exclusão ou qualquer alteração que modifique seu estado atual não será preservado pelo GIT.

<b>Preparação:   git add</b>

- Arquivos adicionados e preparados para receber uma “versão”.

Nessa etapa o arquivo ainda não está no repositório, porém já está pronto para receber uma versão e ser inserido.

<b>Repositório: git commit</b>

- Arquivos salvos

Uma vez que o arquivo está no repositório é possível consultar todas as alterações feitas nos arquivos, seja ele exclusão ou modificação de arquivos. O mesmo nos permite fazer regressões em versões anteriores ou adiantar versões que já foram feitas. 

#COMANDOS GIT 

<b>git clone (endereço do repositório remoto)</b>  ex: https://github.com/caduamorim/audicaoamiga.git 

Comando pra clonar o repositório do GitHub

<b>git status</b> 

Informas todas as atualizações feitas na pasta

<b>git add  nome do arquivo</b>

Adiciona o arquivo na área de preparação de forma individual 

<b>git add .<b>

Adiciona todos os arquivos da pasta na área de preparação 

<b>git commit -m “escrever aqui o que foi feito no commit”</b>

Envia todos os arquivos da área de preparação no repositório 

<b>git log</b>

Histórico do commit informando o código do commit, autor, data e o local onde o commit foi inserido. 

<b>git push origin main</b> (nessa parte temos que informar para qual branch os arquivos serão enviados)

Empurra todos os arquivos da pasta para a nuvem 

<b>git pull origin main</b> (nessa parte temos que informar de qual branch o arquivos será extraído)

Puxa todos os arquivos da nuvem para pasta

<b>git branch nome da branch</b> 

Criando uma nova branch 

<b>git branch </b>

Confirma se a branch foi criada e a alteração está sendo feita nessa ramificação (o nome da branch que deseja acessar deve estar verde) 

<b>git checkout nome da branch</b>

Permite o acesso a ramificação (branch) criada GitHub 

<b>git merge nome da branch que deseja mesclar</b>

Mescla uma ramificação no branch em que estiver sendo acessada.

Ex: Estou na branch main e quero trazer as alteração feitas na branch 01 é só utilizar este código. 




#CONCEITOS

Branch é uma ramificação do nosso projeto, onde nos permite fazer alteração sem modificar o branch main (branch principal do projeto).


