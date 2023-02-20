<h1>HTML</h1>
são linguagens fundamentais para entender as páginas web, e com o os navegadores web são capazes de mostrar essas páginas. 

![image](https://user-images.githubusercontent.com/124601476/220167747-df6e42c6-02d5-40d2-982b-62e751afe610.png)

HTML: *Linguagem de marcação de hipertexto* - usamos para descrever a estrutura da página web (botões, textos, formulários). 
TAG HTML <>, end </>

  head - informamos o título da página web <title> 
  body - inserimos tudo o que deve conter no corpo da página

  <h2>DOM</h2>
página web possui um modelo de árvore, que chamamos de modelo de objeto de documento - ou DOM 
nesse modelo conseguimos visualizar o que está dentro de qual etapa - titulo, está dentro de head, por exemplo

![image](https://user-images.githubusercontent.com/124601476/220169718-d6ac24de-ca6c-4671-8acf-f7ff8b9ba183.png)

  <h2>HEADINGS</h2>
Cabeçalhos mais utilizados:
  h1 h representa a direção e 1 representa a maior direção possível (títulos) 
  h2 cabeçalho menor (subtítulo) 
  h6 cabeçalho menor (define seções e subseções diferentes) 
  
  <h2>LISTS</h2>
HTML tem 2 tipos de listas: ordenadas e não ordenadas
  - Ordenadas: irá listar por números (1, 2, 3..)
    utilizamos a tag: ol
    para listar os itens da lista utilizamos a tag: li
  - Não ordenadas são apenas marcadores de informações, irão listar por bullets
    utilizamos a tag: ul 
    para listar os itens da lista utilizamos a tag: li

  <h2>IMAGE</h2> - como linkar imagens no HTML
*tag de imagem não precisa ser fechada*
  dentro da tag img precisamos informar src (nome do arquivo, cat.jpeg) e alt (texto alternativo que irá constar caso a imagem não abra) width (tamanho da imagem em     pixels) 

  <h2>LINKS</h2> - como fazer com que a nossa página anexe links que possam redirecionar para outra página web
 utlizamos a tag: a e dentro dela informamos o href (vai especificar a qual página eu gostaria de vincular), fechando a tag, informamos qual texto queremos que a página mostre (exemplo: clique aqui)
com a tag do link *a* podemos também vincular a outro doc HTML, o href irá puxar pelo nome do arquivo. 
  
  <h2>TABELAS</h2>
 para criar tabelas utilizamos a tag: *table*
 dentro da tabela, colocamos o título (1° linha): *thead*
 dentro do título, criamos uma linha: *tr* e dentro da linha definimos os cabeçalhos (heado): *th*
 para o corpo da tabela utilizamos: *tbody*
 para criar linhas (rows) usamos: *tr* 
 e cada dado dentro da linha (data) usamos: *td*
 
  <h2>FORMULÁRIO</h2>
dentro do formulário, precisamos inputar os campos que desejamos visualizar: *input* (essa tag não precisa ser fechada)
  e dentro de input definimos o *type* (text-caixa de texto) *placeholder* (o "campo" que irá aparecer na pág web) e *name* (apenas nós visualizamos esse nome) 
com Phyton conseguimos pegar as infos que forem enviadas através de um formulário e salvar em algum banco de dados.   

  form1 - *type* password (quando preencher a caixa de texto aparecerão pontos ao invés do que está sendo digitado)
  *type* radio (botão de opção onde o usuário pod escolher uma das opções) 
  *list* nos permite criar uma listagem onde o usuário escolhe uma das opções
  utilizamos: *datalist* e damos um *id* para a lista.
  dentro do datalist, previsamos informar as opções através do *option* 
  e dentro de option, informamos o valor que o usuário irá visualizar *value* 
Obs: a cada opção dentro do nosso formulário abrimos um *div* (linha) 
  
  <h1>CSS</h1>
![image](https://user-images.githubusercontent.com/124601476/220181091-c6d6b5fd-ead9-400d-9d3e-e126609d6c25.png)

