<html>
<head>
<title>uno</title>
<link rel="stylesheet" type="text/css" href="ESTILOUNO.css">
</head>
<body>
<img src="logoarduino.png" width="30%">
<nav>
  <ul class="menu">
        <li><a href="index.html">MENU</a></li>
		 <li><a href="arduino.html">ARDUINO</a></li>
		 <li><a href="#"> TIPOS DE ARDUINO</a>
                <ul>
                      <li><a href="uno.html">UNO</a></li>
                      <li><a href="nano.html">NANO</a></li> 
                      <li><a href="lilypad.html">LILYPAD</a></li>   
					  <li><a href="mega.html">MEGA</a></li> 
                </ul>
            </li>           
            <li><a href="###">PROJETOS COM ARDUINO</a>
                <ul>
                      <li><a href="projetouno.html">UNO</a></li>
                      <li><a href="projetonano.html">NANO</a></li> 
                      <li><a href="projetolilypad.html">LILYPAD</a></li>   
					  <li><a href="projetomega.html">MEGA</a></li> 
                </ul>
            </li>                
</ul>
</nav>
<br><br>
<center><h2>ARDUINO UNO</h2></center>
<br>
<table border="1">
<tr>
<td>Sobre</td>
</tr>
<tr>
<td>A placa Arduino UNO já está em sua terceira revisão <br>
e você pode baixar seu esquema elétrico no site Arduino,<br>
ou até mesmo todos os arquivos do projeto para a edição.<br>
Ela tem duas camadas apenas e várias características<br> 
interessantes do projeto.</td>
</tr>
</table>
<center>
<table border="1">
<tr>
<td>Características</td>
</tr>
<tr>
<td>A placa pode ser alimentada pela conexão USB<br>
ou por uma fonte alimentação externa.<br>
A alimentação externa é feita através do<br>
conector Jack com positivo no centro,<br>
onde o valor de tensão da fonte externa deve<br>
estar entre os limites 6v a 20v,porém se alimentada<br>
com uma tensão abaixo de 7v, a tensão de funcionamento<br>
da placa,que no Arduino UNO é 5v,pode ficar instável e <br>
quando alimentada acima de 12v,o regulador de tensão <br>
pode sobreaquecer e danificar a placa.Dessa forma é,<br>
recomendado para tensões de fonte externa valores<br>
de 7v a 12v.
</td>
</tr>
</table>
</center>
<br>
<br>
<table border="1" align="right">
<tr>
<td>Comunicação USB da Placa</td>
</tr>
<tr>
<td>Como a interface USB para comunicação com o computador<br>
há na placa im microcontrolador ATMEL AYMEGA16U2.<br>
Esse microcontrolador é o responsável pela forma<br>
transparente como funciona placa Arduino UNO,possibilitando<br>
o upload do código binário gerado após a compilação do<br>
programa feito pelo usuário.Possui um conector ICSP<br>
para a gravação de firmware através de um programador<br>
ATMEL,para atualizações futuras.Nesse microcontrolador<br>
também estão conectados dois led(TX,RX),controlados<br>
pelos softwares do microcontrolador,que indicam o <br>
envio e recepção de dados da placa para o computador.<br>
Esse microcontrolador possui um cristal externo de 16MHz.<br>
É interessante notar a conexão entre o microcontrolador com <br>
ATMEL ATMEGA328,onde é feita pelo canal serial desses<br>
microcontroladores.Outro ponto interessante que faclita o uso <br>
da placa arduino é a conexão do pino 13 do ATMEGA238,<br>
possibilitandoa entrada no modop bootloader<br>
automaticamente quanado é pressionado o botão<br>
Upload na IDE.Essa características não aconteciam nas<br>
primeiras placas Arduino,onde era necessário<br>
pressionar o botão de RESET antes de fazer o<br>
UPLOAD na IDE.
</td>
</tr>
</table>
<center><img src="uno.jpg" width="40%"></center>
</html>
