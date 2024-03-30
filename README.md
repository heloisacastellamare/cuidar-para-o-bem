<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>CUIDAR PARA O BEM</title>
  
  <!-- HTML -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <p class="TITULO">CUIDAR PARA O BEM</p>

  <h3>JUNTOS PODEMOS TRANSFORMAR</h3>
  <!-- Project -->

    <p class="texto-1">A diferença entre o lixo reciclável e o lixo comum é muito citada nos meios de comunicações, entretanto, é perseptível que tais informações ainda não estão totalmente claras, visto que parte da população ainda faz o descarte desses resíduos em locais inapropriados, como em vias públicas, próximo a córregos, praças ou até mesmo não fazem a separação e eliminam tudo em lixo comum. </h2>
    <br>
    <br>
    <p class="texto-2">Reduzir, Reutilizar e Reciclar, são os “3R’s” para o avanço na sustentabilidade como um todo.  </p>
    <br>

     <div class="quadrado-reduzir">
      <p class="texto-3">Reduzir o consumo de itens pouco usados ou até mesmo nulo, auxilia no combate de descarte inadequado e promove a conscientização de compra e consumo. </p>
      </div>

     <div class="quadrado-reutilizar">
      <p class="texto-4">Reutilizar. Capaz de aproveitar algo que certamente iria para o lixo. Tal ação promove a sustentabilidade e diminui o consumo exagerado. Alguns exemplos são: um pote de manteiga pode se transformar em um “porta-treco”. </p>
      </div>

     <div class="quadrado-reciclar">
      <p class="texto-5">Reciclar. Muito semelhante a reutilização, que visa utilizar produtos que iriam para o lixo comum, como: reutilizar casca de frutas para gerar novos alimentos. </p>
     </div>

 <!--Separação do lixo-->
  <p class="SUBTITULO">COMO FAZER A SEPARAÇÃO?</p>
  </p>
  <h1>Veja abaixo onde cada item deve ser colocado</h1>
     <div class="box-img-1">
       <div class="papel" style="background-image: url(imagens/papel.png);"></div>
       <div class="plastico" style="background-image: url(imagens/plastico.png);"></div>
       </div>
     <div class="box-img-2">
       <div class="metal" style="background-image: url(imagens/metal.png);"></div>
       <div class="vidro" style="background-image: url(imagens/vidro.png);"></div>
    </div>
    <p class="texto-6">Deslize o cursor sobre a imagem para visualizar</p>

    <!--Mapa-->
  <p class="LOCALIZAÇÃO">ONDE POSSO DESCARTAR MEU LIXO RECICLÁVEL?</p>
  <h2>Esse é o ECOPONTO mais próximo dos moradores do bairro da Cidade A.E. Carvalho</h2>
  <div class="contrainer-form">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3658.324475710072!2d-46.46353064038151!3d-23.52082927744881!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce6131340d0d0b%3A0x1bbbaae39139d689!2sR.%20Manuel%20Alves%20da%20Rocha%2C%20584%20-%20Parque%20Guarani%2C%20S%C3%A3o%20Paulo%20-%20SP%2C%2008235-620!5e0!3m2!1spt-BR!2sbr!4v1710714362337!5m2!1spt-BR!2sbr" width="500" height="350" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </div>

</body>
</html>

body {
    background-color: rgb(255, 255, 255);
    text-align: center;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 20px;
}

p.texto-6 {
     font-size: 10px;
}

p.TITULO {
    font-size: 50px;
    font-family: Impact, fantasy;
    text-align: center;
    text-decoration-line: underline;
}

.quadrado-reduzir {
    width: 280px;
    height: 260px;            
    border-width: 3px;
    border-color: rgb(72, 255, 0);
    border-style: solid;
    display: inline-flex;
    border-radius: 20%;
    position: relative;
    text-align: center;
}

.quadrado-reutilizar {
    width: 280px;
    height: 260px;            
    border-width: 3px;
    border-color: rgb(72, 255, 0);
    border-style: solid;
    display: inline-flex;
    border-radius: 20%;
    position: relative;
    text-align: center;
}

.quadrado-reciclar {
    width: 280px;
    height: 260px;            
    border-width: 3px;
    border-color: rgb(72, 255, 0);
    border-style: solid;
    display: inline-flex;
    border-radius: 20%;
    position: relative;
    text-align: center;
}

p.SUBTITULO {
    font-size: 50px;
    font-family: Impact, fantasy;
    text-align: center;
    text-decoration-line: underline;
}

.box-img-1{
    width: 450px;
    height: 300px;
    position: relative;
    overflow: hidden;
    display: inline-flex;
}

.box-img-2 {
    width: 450px;
    height: 300px;
    position: relative;
    overflow: hidden;
    display:inline-flex;
}

.metal, .vidro{
    width: 100%;
    height: 100%;
    background-size: cover;
    position: absolute;
}

.papel, .plastico{
    width: 100%;
    height: 100%;
    background-size: cover;
    position: absolute;
}

.plastico { 
    left: 100%;
    transition: 1s;
}
.vidro{
    left: 100%;
    transition: 1s;
}

.box-img-1:hover .plastico{
    left: 0%;
}

.box-img-2:hover .vidro{
    left: 0%
}

p.LOCALIZAÇÃO{
    font-size: 50px;
    font-family: Impact, fantasy;
    text-align: center;
    text-decoration-line: underline;
}

