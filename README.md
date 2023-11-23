# Aplica-o-Node-Chat
O iframe também serve para fazer sites de terceiros funcionarem no seu próprio.
se você quiser com que o site do seu amigo, ou do youtube funcione basta pegar a url.
no youtube você precisa clicar em compartilhar e incorporar, e pegar a url que aparece depois da tag ''src'' do vídeo que você deseja.
se quiser com que o site do seu amigo rode, basta pegar o ip da máquina dele pelo prompt de comando, e fazer da seguinte forma




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat - Minha Nova Página</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
        }

        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <!-- Adicione o código do vídeo aqui -->
    <iframe src="http://(IP DA PESSOA QUE VC QUER QUE O SITE FIQUE)/" frameborder="0" allowfullscreen></iframe>
</body>
</html>
