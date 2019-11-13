

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css">
<link rel="stylesheet" href="css/style.css">

<style>


* {
  box-sizing: border-box;
}


/* Float four columns side by side */
.column {
  float: left;
  width: 50%;
  padding: 0 10px;
}

img {
  border-radius: 5px 5px 0 0;
}

/* Remove extra left and right margins, due to padding */
.row {margin: 0 -5px;}

/* Clear floats after the columns */
.row:after {
  display: table;
  clear: both;
}

/* Responsive columns */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}

/* Style the counter cards */
.card {
  box-shadow: 0 10px 10px 0 rgba(0, 0, 0, 0.2);
  padding: 0px;
  text-align: center;
  background-color: #f1f1f1;
  border-radius: 5px;
}

.button {
  border-radius: 4px;
  background-color: #f4511e;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}


#example3 {
  border-radius: 6px;
  padding: 25px;
  background-color: white;
  background-repeat: no-repeat;
  background-origin: content-box;
  background-position: center;
}


</style>



<div id="example3">

  <h1> II Simpósio Internacional de Tecnologias e Educação Digital - Anais</h1>


<center> 
  <div class="column">
     <div class="card">
     <a href="https://seadufrb.github.io/ebooks/leitura-de-ambientes-da-mineracao/capa/"><img src="https://seadufrb.github.io/ebooks/img/capa.jpg" alt="Avatar" style="width:100%"></a>
     </div>
  </div>

<div class="column">
    <div class="card">
     <a href="https://seadufrb.github.io/ebooks/o-papel-do-fiscal-na-administracao-publica/capa/"><img src="https://seadufrb.github.io/ebooks/img/capafrente.jpg" alt="Avatar" style="width:100%"></a>
    </div>
</div>

<br>
<p style="color:white;">.</p>

  <div class="column">
     <div class="card">
     <a href="https://seadufrb.github.io/ebooks/guia-de-producao-de-material-didatico/capa/"><img src="https://seadufrb.github.io/ebooks/img/capa-guia.jpg" alt="Avatar" style="width:100%"></a>
     </div>
  </div>

<div class="column">
    <div class="card">
     <a href="https://seadufrb.github.io/ebooks/tecnologias-educacao-digital/capa/"><img src="https://seadufrb.github.io/ebooks/img/capa-tecnologias.jpg" alt="Avatar" style="width:100%"></a>
    </div>
</div>

<p style="color:white;"> .</p>
</center>

</div>




<!--

<div class="card">
  <a href="https://seadufrb.github.io/ebooks/Leitura%20de%20Ambientes%20da%20Minera%C3%A7%C3%A3o/capa/"><img src="https://seadufrb.github.io/ebooks/img/capa.jpg" alt="Avatar" style="width:100%"></a>
  <div class="container">
    <h4><b>Jane Doe</b></h4> 
    <p>Interior Designer</p> 
  </div>
</div>

<div class="card">
  <a href="https://seadufrb.github.io/ebooks/Leitura%20de%20Ambientes%20da%20Minera%C3%A7%C3%A3o/capa/"><img src="https://seadufrb.github.io/ebooks/img/capa.jpg" alt="Avatar" style="width:100%"></a>
  <div class="container">
    <h4><b>Jane Doe</b></h4> 
    <p>Interior Designer</p> 
  </div>
</div>

-->



<!--
!!! info "Informações de Contato"

  


!!! warning "MkDocs 1.0 compatibility"

    While MkDocs 1.0 supports prebuilding the search index, Material currently
    doesn't support this setting as the default search behavior of the original
    theme was heavily modified for the sake of a better UX. Integration is
    possible, but a small subset of the features Material provides will not be
    portable to the prebuilt index mainly due to missing localization.

!!! info "Call for Contributions: Add languages/translations to Material"

    Help translate Material into more languages - it's just **one click** and
    takes approximately **2 minutes**: [click here](http://bit.ly/2EbzFc8)


## [Hitting](/hitting/avg/)

Common baseball [hitting statistics](/hitting/avg/) with formulas, definitions, and factoids.

## [Pitching](/pitching/era/)

Common baseball [pitching statistics](/pitching/era/) with formulas, definitions, and factoids.

## [Baserunning](/baserunning/sbp/)

Common baseball [baserunning statistics](/baserunning/sbp/) with formulas, definitions, and factoids.

## Quotes

!!! quote "Mickey Mantle"
    "It's unbelievable how much you don't know about the game you've been playing all your life."

!!! quote "Jacques Barzun"
    "Whoever wants to know the heart and mind of America had better learn baseball."

!!! quote "Moneyball"
    "It's hard not to be romantic about baseball."
-->