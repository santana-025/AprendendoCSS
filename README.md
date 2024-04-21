# AprendendoCSS
 Curso de CSS do Programação web

	          CSS
	    Estiliza o HTML

-> Exite 3 Formas de introduzir no site.

		IN LINE
	(NIVEL 1 DE PRIORIDADE)

Diretamente na tag que você pretende estilizar.
 ex>

<h1 style="color:Blue ; font-size 88px" ></h1>

Na Abertuda da tag, sempre se ultiliza ; para separar as propriedades do css. Pórem so funciona na tag criada

		
		CSS INTERNO 
	   (NIVEL 2 DE PRIORIDADE)
 
Quando damos instruções para todas as tag que quisermos Porem so funciona na mesma pagina. abre uma tag style antes do fechamento do head e dentro passa as propriedades do css 

<style>
	h1 {color:Blue ; font-size:88px;}
</style>
</head>
 
Ou seja dentro dessa pagina todos os proximos <H1> Criados Teram os efeitos dos valores passado !

		
	CSS EXTERNO (Mais ultilizado)
	   (NIVEL 1 DE PRIORIDADE)

Vamos criar uma nova pasta CSS com um documento style.css para todos os documentos e chamar ela dentro da pagina html. sendo assim funciona em todas as paginas que foram incorporado.

CSS/style.css

Na Pág HTML antes do fechamento do </head> insira

<link rel="stylesheet" href="CaminhodoArquivo"> Não tem Tag de Fechamento

Além disso pode ter varios arquivos de css
style.css : é o mais usados
master.css
main.css   

		SELETORES EM CSS

Seletor universal = * {} -> Todos os elementos recem os comportamentos passados

Para não repetir codigo podemos agrupar seletores
h1, p {} ou seja os dois receberam esses comportamentos

1 Seletor -> seria das tags semanticas ou tags originais do HTML ex : body,p,div...
body {
    font-sixe:25px; 	
}

2 Seletor -> Class comportamentos já prontos e basta chamar ela nas tags que eu quero.
(não podem comerçar com numeros )
no css usase . nome da class    ex:

style.css - >
.vermelho{ color:Red;}

index.html - >
<div class="vermelho"> </div>

3 Seletor -> ID ussase o indentificador pois é basicamente unico cad um tem o seu. (não podem comerçar com numeros )
no css usase # nome do id 

style.css - >
#vermelho{ color:Red;}

index.html - >
<div id="vermelho"> </div>

		Cores em css


Colour picker > painel de cores no google


		    3 Tipos
color:nomedacor	:	RED
      HEX		:   #ff0000
      RGB		:   255, 0, 0

	  Backgroud no CSS

backgroud-color = cor
backgroud-image = imagem
backgroud-size = tem 2 
contain = não se ajusta			 
backgroud-repete = norepet
				   repeat-x
				   repeat-y 
couver  = se ajusta
backgroud-position = center,top,right,left,baixo

atalho 

backgroud: cor url("pasta/arquivo") no-repeat center ; 

(Somente o size que teria que colocar)

backgoud: url("pasta/arquivo")


		Bordas 

no css 	     3 parametros
border: tamanho em px tipo cor 
ex:
border: 5px solid black ;

tipos de bordas :

solid = solida
dotted = pontilhada
deshed = traçejada
double = dupla
groove = 3d
inset = por dentro 
outset = por forar
ridge = 
hiden = oculta 
none = nenhuma

border-top 
border-left
border-right
border-bottom

	arrendondado
border = 5px solide black
border-radius = % ou px




