<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Hola Yvana</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel="shortcut icon" href="https://scontent.fvvi1-2.fna.fbcdn.net/v/t1.0-9/120369444_1294868640905468_8985364759391161386_o.jpg?_nc_cat=105&ccb=1-3&_nc_sid=09cbfe&_nc_ohc=3sa2QD3F89IAX-Jla_7&_nc_ht=scontent.fvvi1-2.fna&oh=6726bcdd8bafd2987f4ddc2d48fb518f&oe=60793D3F" type="image/x-icon">
    <style>
        body {
            background-color: pink;
        }
    </style>
    <script>
        function accionParaCuandoEllaDigaQueSi(){
            alert('Bien asi me gusta, siempre con una sonrisa..Puedes contar conmigo para lo que sea <3');
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";
            

        }
    </script>
</head>

<body>
    <a href="paginas/mensaje.html"> Se que cuando le das a Si no te sale el mensaje asi que dale click aqui para ver el mensaje jeje :)</a>
    <h3> Hola Yvana como estas? que paso?.. no hemos hablado en varios días y nose, tengo miedo, nose si estas enojada o estas mal o estas bien y...estoy preocupado  :( estas bien? 
        puedes contar conmigo para lo que sea, yo te voy apoyar y ayudarte  :( </h3>
    <input type="button" onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi" value="Estoy Bien " />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="No" />
    <img src="http://2.bp.blogspot.com/-q0-MIdACALk/T6IUEle5SxI/AAAAAAAAEiU/AqzC3VH8-qs/s1600/piolin%252Btriste.jpg" width="200">
    <p>dale a play para escuchar la musiquita</p>
    <audio controls>
        <source  src="https://mus6.djxd.tk/mp3/7725ea1c-f9ae-44d3-acd0-755f6b0fbd4f.mp3" autoplay="true" loop="true" type="audio/mpeg"></audio>
    </audio>
    <p>yo viendo como ya no me hablas :(</p>
    <img src="https://4.bp.blogspot.com/-ttoQny5QJ7g/VAtOhNC1mQI/AAAAAAAA3lY/b6WPqbOQrXo/s1600/hombre%2Bque%2Bllora%2B(3).gif"  width="200">
    <img src="https://media.tenor.com/images/097d93c00e81371b1d206e98df61b8a3/tenor.gif"  width="200" height="160">
    
</body>
</html>
