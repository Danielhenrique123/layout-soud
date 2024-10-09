/*
===========================================================
							FONTE
===========================================================
*/
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap');
/* 
==========================================================
	CSS RESET	
	http://meyerweb.com/eric/tools/css/reset/ 
	v2.0 | 20110126
	License: none (public domain)
==========================================================
*/
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
	display: block;
}
body {
	line-height: 1;
}
ol,
ul {
	list-style: none;
}
blockquote,
q {
	quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
/* ============================================================= 
                    topo

===========================================================*/
header {
	margin: 2vw 4vw 0 4vw;
}
header nav ul {
	display: flex;
	justify-content: right;
}
header a {
	margin: 30px 20px 30px 20px;
	font-weight: bold;
	text-decoration: none;
	/*tira o sublinhado*/
	color: black;
	/*essa tag muda a cor do a */
}
/* ========================================================
                     conteudo                 
=========================================================*/



/*================
		BANNER
===================*/
section.banner {
	display: flex;
	/* o flex deixa os filhos do elemento um ao lado do outro */
	margin: 110px 60px 80px 180px;
}
section.banner h1 {
	font-size: 40px;
	color: black;
}
section.banner div.text {
	margin: 0 0 0 200px
}
section.banner div.text div.tx p {
	margin: 0 0 40px 0;
}
section.banner div.text .xp {
	display: flex;
	justify-content: flex-start;
	/*alinha para posição inicial do div na horizontal*/
	align-items: start;
	width: 100%;
}
section.banner div.text .xp .anderson {
	width: 80px;
	margin: 0;
	margin: 40px 0 40px 0;
}
section.banner .contener {
	display: flex;
}
section.banner .contener .perfil {
	margin: 0 10px 0 10px;
}
.banner .contener .info h2 {
	margin: 4px 0 0 0;
}
.banner .contener .info p {
	margin: 5px 0 0 2px;
	color: #a7acb3;
}
section.brow-class {
	border-top: 2px solid gray;
	margin: 0 5px 50px 100px;
	display: flex;
	gap: 20px;
}
section.brow-class h1 {
	font-weight: bold;
	font-size: 2rem
}
section.brow-class div.esquerda {

	margin: 100px;
}
section.brow-class div.esquerda p {
	margin: 20px 0 0 0
}
section.brow-class div.direita {
	margin:80 ;
}
section.brow-class div.zero {
	margin: 80px;
}
section.brow-class div.zero h2 {
	font-size: 40px;
}
section.brow-class div.zero p {
margin: 40px 0 0 70px;
color: rgb(100, 100, 100);
}
section.brow-class div.zero span {
	margin: 0 40px 0 0;	color: rgb(100, 100, 100);	font-size: 28px;
}
section.brow-class div.dois {
	margin: 80px;
}
section.brow-class div.dois h2 {
font-size: 40px;
}
section.brow-class div.dois p {
	margin: 40px 0 0 70px;
	color: rgb(100, 100, 100);
	}
	section.brow-class div.dois span {
		margin: 0 40px 0 0;
		color: rgb(100, 100, 100);
		font-size: 28px;
	}
	section.brow-class div.tres {
		margin: 80px;
	}
	section.brow-class div.tres h2 {
	font-size: 40px;
	}
	section.brow-class div.tres p {
		margin: 40px 0 0 70px;
		color: rgb(100, 100, 100);
		}
		section.brow-class div.tres span {
			margin: 0 40px 0 0;
			color: rgb(100, 100, 100);
			font-size: 28px;
		}
		section.brow-class div.quatro {
			margin: 80px;
		}
		section.brow-class div.quatro h2 {
		font-size: 40px;
		}
		section.brow-class div.quatro p {
			margin: 40px 0 0 70px;
			color: rgb(100, 100, 100);
			}
			section.brow-class div.quatro span {
				margin: 0 40px 0 0;
				color: rgb(100, 100, 100);
				font-size: 28px;
			}
		
			section.final {
				border-top: 2px solid gray;
				margin: 0 5px 50px 100px;
				display: flex;
				gap: 20px;
			}

			section.final div.fotos img {

               display: flex;

			   justify-content: center;


			   font-size: 30px;



			}

			section.final p {

                   justify-content: center;


			}
	
