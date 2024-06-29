<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eu te amo</title>

    <style>
         body{
            background-color: red;
         }
            
            

         .painel{

            background-color: white;
            width: 500px;
            height: 500px;
            border-radius: 20px;
            text-align: center;
            padding-top: 50px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;



         }

        #sim{
          
          height: 40px;
          width: 60px;
          background-color:red ;
          border:2px solid white ;
          border-radius: 10px;
          color: white;
          margin-left: -50px ;
        }
        #nao{
            position: absolute;
            height: 40px;
          width: 60px;
          background-color:red ;
          border:2px solid white ;
          border-radius: 10px;
          color: white;
          margin-left: 10px ;


        } 

    </style>
</head>
<body>
    <div class="painel">
 <h1> Eu te amo 🤍 </h1>
 <img src="https://gifman.net/wp-content/uploads/2019/06/ursinho-fofo-apaixonado.gif" alt="" srcset="">
 
  <a href="https://www.youtube.com/watch?v=W5HYF3zo-CE&pp=ygUVdGUgYW1vIG1pbmhhIHByaW5jZXNh"><button  id="sim " >sim</button></a>
  <button onmouseover="fuja()"  id="nao">Não </button>

    </div>
 <script>
          function fuja(){
             var botaonao = document.getElementById("nao")
            var larguradaJanela = window.innerWidth;
            var alturadaJanla = window.innerHeight;
            var maxX = larguradaJanela - botaonao.offsetWidth;
            var maxY = alturadaJanla - botaonao.offsetHeight;
         

            var aleatorioX = Math.floor(Math.random()  *  maxX );
            var aleatorioY = Math.floor(Math.random() * maxY);

            botaonao.style.left = aleatorioX + "px";
            botaonao.style.top = aleatorioY + "px";


          }


          function Euteamo(){

            alert("Eu te amo muito minha princesa, As ondas do mar se perderiam em teus cachos ");
          }
 </script>

    
</body>

</html>

