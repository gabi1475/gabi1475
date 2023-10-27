
@@ -0,0 +1,90 @@
* {
	box-sizing: border-box;
}

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}

article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

a {
	color: inherit;
	text-decoration: none;
}

img {
	width: inherit;
}

button {
	font-family: inherit;
	font-size: inherit;
	color: inherit;
	font-weight: inherit;
	padding: 0;
	border: none;
	background-color: unset;
}

input {
	border: none;
	color: inherit;
	font-size: inherit;
	font-weight: inherit;
	font-family: inherit;
}

textarea {
	border: none;
	color: inherit;
	font-size: inherit;
	font-weight: inherit;
	font-family: inherit;
}

select {
	border: none;
	color: inherit;
	font-size: inherit;
	font-weight: inherit;
	font-family: inherit;
}
![image](https://github.com/gabi1475/gabi1475/assets/142610317/0f4bb6ee-3294-4b2a-9fbe-6fa9fa182a00)
@@ -0,0 +1,48 @@
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Alura MIDI</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;600&display=swap" rel="stylesheet">

    <link rel="icon" type="image/png" href="images/bateria.png">
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="css/estilos.css">

</head>
<body>

    <h1>Alura Midi</h1>

    <section class="teclado">
        <button class="tecla tecla_pom">Pom</button>
        <button class="tecla tecla_clap">Clap</button>
        <button class="tecla tecla_tim">Tim</button>

        <button class="tecla tecla_puff">Puff</button>
        <button class="tecla tecla_splash">Splash</button>
        <button class="tecla tecla_toim">Toim</button>

        <button class="tecla tecla_psh">Psh</button>
        <button class="tecla tecla_tic">Tic</button>
        <button class="tecla tecla_tom">Tom</button>
    </section>

    <audio src="sounds/keyq.wav" id="som_tecla_pom"></audio>
    <audio src="sounds/keyw.wav" id="som_tecla_clap"></audio>
    <audio src="sounds/keye.wav" id="som_tecla_tim"></audio>
    <audio src="sounds/keya.wav" id="som_tecla_puff"></audio>
    <audio src="sounds/keys.wav" id="som_tecla_splash"></audio>
    <audio src="sounds/keyd.wav" id="som_tecla_toim"></audio>
    <audio src="sounds/keyz.wav" id="som_tecla_psh"></audio>
    <audio src="sounds/keyx.wav" id="som_tecla_tic"></audio>
    <audio src="sounds/keyc.wav" id="som_tecla_tom"></audio>

</body>
</html>
