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

![image](https://user-images.githubusercontent.com/124601476/220181988-7cd99cea-7a36-4a06-9e2b-51c487679af0.png)
  
Cascading style sheets - define o design da nossa página 
Nos permite pegar o página em HTML e alterar o seu visual 

  <h2>STYLE</h2>
  Podemos designar propriedades ao nossos atributos do código HTML
  
  tag style dentro de TITLE no nosso código nos permite definir um estilo para uma tag específica 
  dessa forma, não precisamos atribuir o style dentro de cada uma das tags que desejamos 
  dentro de *style* definimos qual o elemento que será estilizado e dentro de {} informamos as alterações como *color* e *text-align*
  
  podemos utilizar o mesmo STYLE, para mais de um código (página) - melhoria: mover para um novo arquivo o nosso código CSS
  criamos um código .css e vinculamos ao código .html através da tag *link* 
  dentro de link, definimos *rel* que define o relacionamento do documento e o *href* onde puxamos o nome do arquivo .css
  
  *background - color* define uma cor de fundo para o texto que definimos 
  *width* e *height* - elementos que definem TAMANHO do background
  *padding* - preenchimento (borda) do texto dentro do background que definimos - DENTRO do elemento
  *margin* - margem do background dentro da página web - FORA do elemento
  
  <h2>FONT</h2>
  
  *font-family* - define a fonte (arial, sans-serif) 1, 2 onde 1 é a princial e 2 é a backup caso o navegador não suporte a 1
  *font-size* - define o tamanho da fonte em px
  *font-weight* - define se será sublinhado, negrito ou outro atributo 
  *border* - define a borda no div que estamos estilizando (tamanho, solido, cor)
  *border-collapse* - junta as bordas em uma para que se pareça de fato com uma tabela
  
  *ID*
  para alterarmos apenas alguns elementos em específico de acordo com o style que desejamos, devemos atribuir um ID ao elemento HTML
  no cód HTML utilizamos id = ""
  e no código CSS utilizamos #
  
  *CLASS*
  uma forma de dar um nome a um elemento HTML que não é exclusivo
  no cód HTML utilizamos class = ""
  e no código CSS utilizamos .
  
  <h2>ESPECIFICIDADE</h2>
  elementos que seguem uma ordem particular 
  1. inline
  2. id
  3. class
  4. type
  
  se dentro do código, definimos uma tag onde o div deve ser azul, e um id (como #foo) onde o div deve ser vermelho, o id sobrepõe a regra da tag e o id é vermelho. 
  o id é mais específico que a tag
  
  <h2>CSS SELECTORS</h2>
  
  ![image](https://user-images.githubusercontent.com/124601476/220190152-1c33121e-d895-45e2-890b-2af448c873e4.png)
  
  ul > li color blue - isso significa que apenas os itens li que estejam dentro de ul, serão azuis 
  os li fora, permanecem 
  
  <h2>ATRIBUTO</h2>
  quando inserimos um atributo como [] podemos criar uma regra específica para ele. 
  Exemplo: definimos que todos os elementos dentro de "a" serão azul porém apenas um elemento específico HTML será vermelho. 
  para esse "específico" utilizamos []
  
  <h2>PSEUDOCLASSE</h2>
  exemplo: modificamos o elemento quando o cliente passa o cursor em cima de alguma informação específica
  para isso usamos o *hover*, onde definimos uma condição para quando estivermos com o cursor do mouse em cima daquela informação (no nosso exemplo, o botão)
 
  <h1>RESPONSIVE DESIGN</h1>
  Projetamos as páginas web de formas responsivas - onde se adaptam em qualquer dispositivo (celular, PC, tablet..)
  
  <h2>Viewport</h2>
  Janela de visualização - parte visual da nossa tela que o usuário pode ver. 
  para ter certeza de que em um dispositivo móvel podemos visualizar a página assim como via web, utilizamos o código: 
    meta name="viewport" content="width=device-width, initial-scale=1.0"
  dessa forma a largura da visualização terá o tamanho do próprio dispositivo, ela se adapta sozinha. 
  ![image](https://user-images.githubusercontent.com/124601476/222608879-f364e29c-f380-43fd-a838-7f5d68b24da7.png)

  <h2>Media Queries</h2>
  Media Types: print, screen, ...
  Media Features: height, width, orientation, ...
  -> trata-se de controlar a aparência da nossa página dependendo de como renderizamos ela, define o tamanho da tela dependendo da renderização. 
  para utilizar essa sintaxe utilizamos @media e dentro de () definimos as especificidades - exemplo: tamanho; e depois mais especificidades {} em body 
  essa tecnologia nos permite escolher como a nossa página irá ser exibida em vários tipos diferentes de dispositivos. 
  podemos controlar qualquer propriedade CSS. 
  
  <h2>Flexbox</h2>
   é útil quando temos vários elementos á serem exibidos em uma única página web, em diferentes dispositivos.
   evita que, ao acessar uma pág web programada para pc, em um celular por exemplo, os itens sejam encolhidos ou permaneçam exatamente do mesmo tamanho e usuário precise arrastar. 
  o Flexbox de forma automática, irá reordenar os elementos de acordo com o tamanho da página. 
  ![image](https://user-images.githubusercontent.com/124601476/222609764-f712017f-b41e-429b-bd07-2eb8b17a1ca9.png)
  para isso utilizamos:
  display: flex
  flex-wrap: wrap
  
  para grid 
  display: grid
  e determinamos também grid-column-gap, grid-row-gap e grid-template-columns (definido em pixels, podemos definir que será auto)
  
  Basicamente, o uso do responsive design garante que as páginas tenham uma boa aparência independente do tipo de navegador ou dispositivo que está sendo utilizado. 
  
  
