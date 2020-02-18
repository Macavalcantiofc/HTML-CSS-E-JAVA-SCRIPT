# HTML-CSS-E-JAVA-SCRIPT
@charset"utf-8";
@import url ('https://fonts.googleapis.com/css?family= Saira + Semi + Condensado & display = swap');
@font-face{
 src: url("../_fonts/bubblegum-sans-regular.otf");
 font-family: 'FonteLogo';
 
}


body {
                  background-color: #dddddd;
                  color:        rgba(0,0,0,1);
         }

         p {
             text-align: justify;
             text-indent: 50px;
         }

/* FOMATAÇAO DE INTERFACE*/
         div#interface{
             width:1100px;
             background-color: #ffffff;
             margin: -20px auto 0 auto;
             box-shadow: 0 0 10px rgba(0,0,0,.5);
             padding: 10px 10px 10px 10px ;

         }



/* FOMATAÇAO DO OCULOS NA INTERFACE*/

         header#cabecalho img#icone{
             position: absolute;
             left: 80%;
             top: 75px;
         }

/* CABEÇALHO NO INICIO DO SITE com imagem*/

         header#cabecalho{
            border-bottom:  1px #606060 solid;
             height: 150px;
             background: url("../_imagens/glass-logo-peq.jpg") no-repeat 0 80px;


         }

/* CABEÇALHO OS 2 PRIMEIROS TITULOS*/

         header#cabecalho h1{
             font-family: 'FonteLogo', sans-serif;
             font-size: 30pt;
             color: rgba(0,0,0,.5);
             text-shadow: 1px 1px 1px rgba(0,0,0,.6);
             padding: 0;
             margin-bottom: 0;
         }

         header#cabecalho h2{
             font-family: 'FonteLogo2', sans-serif;
             color: #888888;
             font-size: 15pt;
             padding: 0;
             margin-top: 0;

         }



 /* FOMATAÇAO DE IMAGENS COM LEGENDAS*/
/*_imagens/glass-quadro-homem-mulher.jpg"*/

        figure.foto-legenda{
            position: relative;
            border: 3px solid white;
            box-shadow: 1px 1px 4px black;
        }

        figure.foto-legenda img{
          width: 100%;
          height: 100%;
        }

         figure.foto-legenda figcaption{
           opacity: 0;
           position: absolute;
           top: 0;
           width: 20%;
           height:10%;
           padding: 5px;
           transition: opacity 1s;
         }

          figure.foto-legenda:hover figcaption{
              opacity: 1;
          }

/* FOMATAÇAO DE IMAGENS TERMINA LEGENDAS*/
/*_imagens/glass-quadro-homem-mulher.jpg"*/





/* fazer o menu ficar na posicao correta */
   nav#menu {
       display: block;

   }


/* FOMATACÃO DO MENU caxinhas de clicar*/

   nav#menu ul {
       list-style: none;
       text-transform: uppercase;
       position: absolute;
       top: -20px;
       left: 380px;

   }


/* FOMATACÃO DO MENU para ficar em cima do site na horizontal*/

   nav#menu li {
       display: inline-block;
       background-color: #dddddd;
       padding: 10px;
       margin: 2px;
       transition: backgroud-color 1s;

   }


/* ESCONDER O H1 DO MENU*/

   nav#menu h1{
    display: none;

   }


/* fazer efeito de 1s  H1 DO MENU*/

   nav#menu a:hover {
    color: #ffffff;
    transition: color 2s;
       text-decoration: underline;
   }
/* fazer efeito de mudar a cor quando passar o mouse */

   nav#menu li:hover{
       background-color: #606060;
   }

/* FOMATAR OS LINKS*/

   nav#menu a{
       color: black;
       text-decoration: none;
   }

/* CONFIGURAÇAO DA SECTION PRINCIPAL CORPO*/

   section#corpo{
       display: block;
       width: 600px;
       float: left;
       border-right: 1px solid grey;
       padding-right: 25px;
   }

/* CONFIGURAÇAO DA ASIDE LATERAL CORPO*/

   aside#lateral{
       display: block;
       width: 450px;
       float: right;

   }
/* CONFIGURAÇAO DA footer rodape CORPO*/

   footer#rodape{
       clear: both;
       border-top: 1px solid grey;


   }

   footer#rodape h3 {

   	text-align: center; 
   }
