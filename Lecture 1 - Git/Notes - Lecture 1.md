<h1>GIT</h1>

![image](https://user-images.githubusercontent.com/124601476/227392901-2f444e1b-7d09-421e-8923-3d55d37066b5.png)

É uma ferramenta de linha de comando que nos permitirá acompanhar as alterações que fazemos no código. 
Nos permite acompanhar as alterações que fazemos no nosso código, então toda vez que adicionamos ou removemos coisas à ele, podemos salvar instantâneamente as partes do nosso código de modo que possamos referenciar as alterações feitas. 

GIT vai nos ajudar a *sincronizar códigos* com pessoas diferentes - Coworking 
Quando o trabalho está sendo feito em conjunto, ambos poderão ter acesso ao mesmo respositório, os mesmos arquivos. 
E caso sejam feitas alterações, basta realizar o update no servidor e a versão atualizada estará no repositório. 

GIT também nos permite realizar testes no código, sem perder o original. 
Podemos fazer alterações no código em um "branch" separado. 

Por fim, GIT nos permite resgatar versões antigas do nosso código. 

<h2>Comandos</h2>
git clone -> Um comando que utilizamos para pegar um repositório na internet e baixá-lo em nosso próprio computador. 
git clone + url que queremos adicionar

ls -> lista todos os arquivos dentro de um diretório ou pasta

cd -> para mudar para um diretório ou pasta 

touch hello.html -> irá criar um arquivo chamado hello

code . -> abrir o arquivo dentro de um editor de código

savepoints: chamados de commits 
git add -> usamos para rastrear o arquivo, usando esse comando na próxima fez que fizermos um commit será salvo

git commit -m "message" -> comando utilizando para salvar as alterações feitas no arquivo
git commit -am -> comando para salvar TODOS as arquivos alterados 

git status -> status do repositório - irá nos mostrar a diferença do repositório local para o online 

git push -> enviar os comandos que foram utilizados localmente (na máquina) para o repositório online 
git pull -> baixar os comandos do repositório online para a nossa versão local (máquina)

Guia prático -> https://rogerdudler.github.io/git-guide/index.pt_BR.html
