

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


[![Material for MkDocs](https://seadufrb.github.io/sited-anais/ii-sited-anais/imagens/capa-anais.png)](https://seadufrb.github.io/sited-anais/ii-sited-anais/imagens/capa-anais.png)







