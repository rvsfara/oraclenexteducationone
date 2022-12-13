### [Voltar - Neste mesmo curso](../README.md)
# JavaScript e HTML

```html
<html>
    <meta charset="UTF-8">
        <title>Primeiro Teste</title>
    </meta>
    <body>
        <h1>Texto Grande h1</h1>
        <h1>Texto h2</h1>
        Frase 1
        <br />
        Frase 2
        <a href="https://www.linkedin.com/in/rvsfara/">Meu LinkedIn</a>
        <script type="text/javascript">
            alert("Exemplo de alerta");
        </script>
    </body>
</html>

```


```html
<html>
<meta charset=UTF-8>
<title>Primeiro Teste</title>

</meta>
<body>
    <a href="https://www.linkedin.com/in/rvsfara/">Meu LinkedIn</a>
    <br />
    <h3>Calculadora Tabuada While</h3>
<script>
    function pulaLinha() {

        //document.write("<br>");
        document.write("<br />");
    }
    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }
    var tabuada = parseInt(prompt("Digite numero de 1 a 10"));
    var multiplicador = 1;
    function condicao(){
        while( isNaN(tabuada)) {
            tabuada = parseInt(prompt("Digite numero de 1 a 10"));
        }
        if(tabuada <= 10 && tabuada >= 1){
            exibetabuada();
        }else{
            tabuada = parseInt(prompt("Digite numero de 1 a 10"));
            condicao();
        }

    }
    function exibetabuada(){
        while(multiplicador <= 10) {
            mostra(tabuada * multiplicador);
            multiplicador = multiplicador + 1
        }
    }
    condicao();
    mostra("FIM");
</script>

</script>
</body>
</html>
```

### [Voltar - Neste mesmo curso](../README.md)
