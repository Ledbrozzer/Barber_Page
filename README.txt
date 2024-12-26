Baixr Extensão -> "Live Sass" | Tem a extensão "Sass (.sass only)" -> caso as VARIAVEIS importadas, não apareçm nas sugests
O Saas que foi baixd - é pré-compilador do CSS (CSS com mais func)
Tem que passar o arqv '.scss' p/ "index.html"-mas, o navg n entende o pré-compilador.. Tem que convert p/ 1 arqv 'CSS'.
Vai ter lá embaix no VSCode-> "Watch Sass", clikng->Vai abrir uma janela(output):
Vai tá "Generated".., e, vai tá informando q tá "Watching"
-> tá watching o CSS.. / clicnd no "Watch Sass"->Abre o "Output" informng qtá "Watching" e cria um arqv convertd = "style.css.map"
-> Se alter oarqv Sass=>Vai re-compilar e jogar no arqv "CSS"

-> dáp/separ-as-partes d códg| Criando past: "partials" - criar aqvs
-> Def VARIAVEIS --> "$x: #Y;" - etc.
-> p/embut-inCODE MAINd'css: -Em cima do 'body'(style.scss)->Put'@import "partials/colors";'

Usar um breakpoint=Responsividade de acord c/ det size de media..

"_layout.scss" -> Put t-Layout da pág
-> Alinhar o "bg-home"-p/ajust de acordo c/maxSize
-> Criar o '.container' p/def o ponto de alinhamento doLayout
bg-home -> usar o '::before' (Pseudo-elemento) = "ants do noss conteúd..
-> vou pass '"content": ""'-vazio(nenhum);
vou passar a img de fund -c/Gradiente p/BAIXO;
--> a img meio que se 'funde' c/ o outro fundo -> o "linear-gradient(to bottom)" ajud niss
por ',' e pass o 'rgba', ',' e a cor. [Vai ter opacidad-quase none-> em cima (p/exib a img)-e-dps a cor solid]
dps.. ',' passa a "url"
vai t "z-index" = "-1" => Vai ficar em baix do conteud
"background-size" vai ser "cover"(pegar wholeSize da Tela)-(sem quebr);
"background-repeat: no-repeat" ->não reptir img

->Criar a part do ABout:
