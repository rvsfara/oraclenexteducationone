### [Voltar - Neste mesmo curso](../README.md) 
# Curso de Animações e Canvas JavaScript
Canvas
Bandeira
```html
<html>
<meta charset=UTF-8>
<title>Primeiro Teste</title>

</meta>
<body>
    <a href="https://www.linkedin.com/in/rvsfara/">Meu LinkedIn</a>
    <br />
<canvas width="600" height="400"> </canvas>

<script>

    var tela = document.querySelector('canvas');
    var pincel = tela.getContext('2d');

    pincel.fillStyle = 'lightgrey';
    pincel.fillRect(0, 0, 600, 400);

    pincel.fillStyle = 'green';
    pincel.fillRect(0, 0, 200, 400);

    pincel.fillStyle = 'red';
    pincel.fillRect(400, 0, 200, 400);
</script>
</body>
</html>
```

Triangulo e Circulo
```html
<html>
<meta charset=UTF-8>
<title>Primeiro Teste</title>

</meta>
<body>
    <a href="https://www.linkedin.com/in/rvsfara/">Meu LinkedIn</a>
    <br />
<canvas width="600" height="400"> </canvas>

<script>

    var tela = document.querySelector('canvas');
    var pincel = tela.getContext('2d');

    pincel.fillStyle = 'lightgrey';
    pincel.fillRect(0, 0, 600, 400);

    pincel.fillStyle = 'green';
    pincel.fillRect(0, 0, 200, 400);

    pincel.fillStyle = 'red';
    pincel.fillRect(400, 0, 200, 400);

    pincel.fillStyle = 'yellow';
    pincel.beginPath();
    pincel.moveTo(300, 200);
    pincel.lineTo(200, 400);
    pincel.lineTo(400, 400);
    pincel.fill();

    pincel.fillStyle = 'blue';
    pincel.beginPath();
    pincel.arc(300, 200, 50, 0, 2 * 3.14);
    pincel.fill();

</script>
</body>
</html>
```

Desenho de telas

Animações

### [Voltar - Neste mesmo curso](../README.md)