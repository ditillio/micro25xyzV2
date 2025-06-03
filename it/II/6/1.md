<style>
.alfgame td {
  padding: 5px;
  text-align: center;
  font-size: 20px;
</style>









bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla 


<table class="alfgame" style="width:15%; table-layout:auto; border-collapse: collapse">
  <tr>
    <td style="visibility: hidden"> GiocatoreBBBBBB </td>
    <td style="visibility: hidden"> Down </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="4" style="vertical-align:bottom">
    $\text{Giocatore 2}$
    </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="2">
    Left
    </td>
    <td colspan="2">
    Right
    </td>
  </tr>
  <tr>
    <td style="vertical-align:bottom; text-align:center">
    $\text{Giocatore 1}$
    </td>
    <td>
    Up
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        $1$
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        $1$
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        $0$
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        $3$
    </td>
  </tr>
  <tr>
    <td></td>
    <td>
    Down
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        $3$
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        $0$
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        $2$
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        $2$
    </td>
  </tr>
</table>


<br>














bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla 




































<h2 id="SUBSEC_DOM">Strategie dominate</h2>

bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla 


homogeneous good

bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla 
$P=5-Q/1000$ e $MC=2$

Anche se il gioco sembra complicato, osservandolo con un po' di attenzione notiamo che possiamo risolverlo eliminando iterativamente le strategie dominate, seguendo la procedura in tre step qui a lato.
<span class="marginnote">
<input type="radio" name="dom4" id="DOMcheck1game4" onclick="DOMerase4('darkgrey')">
<b>Eliminazione iterata - Step 1</b>
</span>
<span class="marginnote" id="DOMmsg1">
</span>
<span class="marginnote">
<input type="radio" name="dom4" id="DOMcheck2game4" onclick="DOMerase4('darkgrey')">
<b>Eliminazione iterata - Step 2</b>
</span>
<span class="marginnote" id="DOMmsg2">
</span>
<span class="marginnote">
<input type="radio" name="dom4" id="DOMcheck3game4" onclick="DOMerase4('darkgrey')">
<b>Eliminazione iterata - Step 3
</b>
</span>
<span class="marginnote" id="DOMmsg3">
</span>
<span class="marginnote">
<input type="radio" name="dom4" id="DOMcheck0game4" onclick="DOMerase4('darkgrey')" checked>
Reset
</span>



<!-- 4x4 discrete Cournot duopoly (ITERATED DOMINANCE) -->

<table class="alfgame" style="width:20%; table-layout:auto; border-collapse: collapse">
  <tr>
    <td style="visibility: hidden"> ImpresaBB </td>
    <td style="visibility: hidden"> Down </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
  </tr>
  <tr>
    <td>
    </td>
    <td>
    1600
    </td>
    <td id="DOM081game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        2240
    </td>
    <td id="DOM082game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td id="DOM481game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        1600
    </td>
    <td id="DOM482game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        400
    </td>
    <td id="DOM581game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        320
    </td>
    <td id="DOM582game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        240
    </td>
    <td id="DOM881game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        -320
    </td>
    <td id="DOM882game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        -320
    </td>
  </tr>
  <tr>
    <td style="vertical-align:bottom; text-align:center">
    $\text{Impresa B}$
    </td>
    <td>
    1200
    </td>
    <td id="DOM051game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        2160
    </td>
    <td id="DOM052game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td id="DOM451game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        1680
    </td>
    <td id="DOM452game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        560
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        720
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        720
    </td>
    <td id="DOM851game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        240
    </td>
    <td id="DOM852game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        320
    </td>
  </tr>
  <tr>
    <td>
    </td>
    <td>
    400
    </td>
    <td id="DOM041game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        1040
    </td>
    <td id="DOM042game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td id="DOM441game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        880
    </td>
    <td id="DOM442game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        880
    </td>
    <td id="DOM541game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        560
    </td>
    <td id="DOM542game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        1680
    </td>
    <td id="DOM841game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        400
    </td>
    <td id="DOM842game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        1600
    </td>
  </tr>
  <tr>
    <td></td>
    <td>
    0
    </td>
    <td id="DOM001game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td id="DOM002game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td id="DOM401game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td id="DOM402game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        1040
    </td>
    <td id="DOM501game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td id="DOM502game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        2160
    </td>
    <td id="DOM801game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td id="DOM802game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        2240
    </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="2">
    0
    </td>
    <td colspan="2">
    400
    </td>
    <td colspan="2">
    1200
    </td>
    <td colspan="2">
    1600
    </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="8" style="vertical-align:bottom">
    $\text{Impresa A}$
    </td>
  </tr>
</table>

bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla 
bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla 






<script>
function DOMerase4(newColor) {
  var checkBox1 = document.getElementById("DOMcheck1game4");
  var checkBox2 = document.getElementById("DOMcheck2game4");
  var checkBox3 = document.getElementById("DOMcheck3game4");
  var checkBox0 = document.getElementById("DOMcheck0game4");
  const dom081game4 = document.getElementById("DOM081game4");
  const dom082game4 = document.getElementById("DOM082game4");
  const dom051game4 = document.getElementById("DOM051game4");
  const dom052game4 = document.getElementById("DOM052game4");
  const dom041game4 = document.getElementById("DOM041game4");
  const dom042game4 = document.getElementById("DOM042game4");
  const dom001game4 = document.getElementById("DOM001game4");
  const dom002game4 = document.getElementById("DOM002game4");
  const dom401game4 = document.getElementById("DOM401game4");
  const dom402game4 = document.getElementById("DOM402game4");
  const dom501game4 = document.getElementById("DOM501game4");
  const dom502game4 = document.getElementById("DOM502game4");
  const dom801game4 = document.getElementById("DOM801game4");
  const dom802game4 = document.getElementById("DOM802game4");
  const dom481game4 = document.getElementById("DOM481game4");
  const dom482game4 = document.getElementById("DOM482game4");
  const dom581game4 = document.getElementById("DOM581game4");
  const dom582game4 = document.getElementById("DOM582game4");
  const dom881game4 = document.getElementById("DOM881game4");
  const dom882game4 = document.getElementById("DOM882game4");
  const dom851game4 = document.getElementById("DOM851game4");
  const dom852game4 = document.getElementById("DOM852game4");
  const dom841game4 = document.getElementById("DOM841game4");
  const dom842game4 = document.getElementById("DOM842game4");
  const dom451game4 = document.getElementById("DOM451game4");
  const dom452game4 = document.getElementById("DOM452game4");
  const dom441game4 = document.getElementById("DOM441game4");
  const dom442game4 = document.getElementById("DOM442game4");
  const dom541game4 = document.getElementById("DOM541game4");
  const dom542game4 = document.getElementById("DOM542game4");
  if (checkBox1.checked == true){
  document.getElementById("DOMmsg1").innerHTML = 
  " Per ciascuna impresa, non produrre affatto è una strategia dominata (da produrre 400 o 1200 unità). Nel gioco ridotto ottenuto dopo il primo step le strategie rimaste per ciascuna impresa sono quindi produrre 400, 1200 o 16000 unità."
  ;
  document.getElementById("DOMmsg2").innerHTML = "";
  document.getElementById("DOMmsg3").innerHTML = "";
  dom081game4.style.background = newColor;
  dom051game4.style.background = newColor;
  dom041game4.style.background = newColor;
  dom001game4.style.background = newColor;
  dom401game4.style.background = newColor;
  dom501game4.style.background = newColor;
  dom801game4.style.background = newColor;
  dom481game4.style.background = "transparent";
  dom581game4.style.background = "transparent";
  dom881game4.style.background = "transparent";
  dom851game4.style.background = "transparent";
  dom841game4.style.background = "transparent";
  dom451game4.style.background = "transparent";
  dom441game4.style.background = "transparent";
  dom541game4.style.background = "transparent";
  dom082game4.style.background = newColor;
  dom052game4.style.background = newColor;
  dom042game4.style.background = newColor;
  dom002game4.style.background = newColor;
  dom402game4.style.background = newColor;
  dom502game4.style.background = newColor;
  dom802game4.style.background = newColor;
  dom482game4.style.background = "transparent";
  dom582game4.style.background = "transparent";
  dom882game4.style.background = "transparent";
  dom852game4.style.background = "transparent";
  dom842game4.style.background = "transparent";
  dom452game4.style.background = "transparent";
  dom442game4.style.background = "transparent";
  dom542game4.style.background = "transparent";
  } else if (checkBox2.checked == true){
  document.getElementById("DOMmsg1").innerHTML = 
  " Per ciascuna impresa, non produrre affatto è una strategia dominata (da produrre 400 o 1200 unità). Nel gioco ridotto ottenuto dopo il primo step le strategie rimaste per ciascuna impresa sono quindi produrre 400, 1200 o 16000 unità."
  ;
  document.getElementById("DOMmsg2").innerHTML = 
  " Nel gioco ridotto ottenuto dopo il primo step, per ciascuna impresa produrre 1600 unità è una strategia dominata (da produrne 400 o 1200). Eliminata questa, le strategie rimaste per ciascuna impresa sono solo produrre 400 o 1200 unità. <b><i>Nota: questo gioco ridotto è un dilemma del prigioniero!</i></b>"
  ;
  document.getElementById("DOMmsg3").innerHTML = "";
  dom081game4.style.background = newColor;
  dom051game4.style.background = newColor;
  dom041game4.style.background = newColor;
  dom001game4.style.background = newColor;
  dom401game4.style.background = newColor;
  dom501game4.style.background = newColor;
  dom801game4.style.background = newColor;
  dom481game4.style.background = newColor;
  dom581game4.style.background = newColor;
  dom881game4.style.background = newColor;
  dom851game4.style.background = newColor;
  dom841game4.style.background = newColor;
  dom451game4.style.background = "transparent";
  dom441game4.style.background = "transparent";
  dom541game4.style.background = "transparent";
  dom082game4.style.background = newColor;
  dom052game4.style.background = newColor;
  dom042game4.style.background = newColor;
  dom002game4.style.background = newColor;
  dom402game4.style.background = newColor;
  dom502game4.style.background = newColor;
  dom802game4.style.background = newColor;
  dom482game4.style.background = newColor;
  dom582game4.style.background = newColor;
  dom882game4.style.background = newColor;
  dom852game4.style.background = newColor;
  dom842game4.style.background = newColor;
  dom452game4.style.background = "transparent";
  dom442game4.style.background = "transparent";
  dom542game4.style.background = "transparent";
  } else if (checkBox3.checked == true){
  document.getElementById("DOMmsg1").innerHTML = 
  " Per ciascuna impresa, non produrre affatto è una strategia dominata (da produrre 400 o 1200 unità). Nel gioco ridotto ottenuto dopo il primo step le strategie rimaste per ciascuna impresa sono quindi produrre 400, 1200 o 16000 unità."
  ;
  document.getElementById("DOMmsg2").innerHTML = 
  " Nel gioco ridotto ottenuto dopo il primo step, per ciascuna impresa produrre 1600 unità è una strategia dominata (da produrne 400 o 1200). Eliminata questa, le strategie rimaste per ciascuna impresa sono solo produrre 400 o 1200 unità. <b><i>Nota: questo gioco ridotto è un dilemma del prigioniero!</i></b>"
  ;
  document.getElementById("DOMmsg3").innerHTML = 
  " Le imprese producono 1200 unità ciascuna. Il prezzo è quindi 5-(1200+1200)/1000=2.6 e ciascuna impresa ottiene un profitto pari a (2.6-2) × 1200=720. "
  ;
  dom081game4.style.background = newColor;
  dom051game4.style.background = newColor;
  dom041game4.style.background = newColor;
  dom001game4.style.background = newColor;
  dom401game4.style.background = newColor;
  dom501game4.style.background = newColor;
  dom801game4.style.background = newColor;
  dom481game4.style.background = newColor;
  dom581game4.style.background = newColor;
  dom881game4.style.background = newColor;
  dom851game4.style.background = newColor;
  dom841game4.style.background = newColor;
  dom451game4.style.background = newColor;
  dom441game4.style.background = newColor;
  dom541game4.style.background = newColor;
  dom082game4.style.background = newColor;
  dom052game4.style.background = newColor;
  dom042game4.style.background = newColor;
  dom002game4.style.background = newColor;
  dom402game4.style.background = newColor;
  dom502game4.style.background = newColor;
  dom802game4.style.background = newColor;
  dom482game4.style.background = newColor;
  dom582game4.style.background = newColor;
  dom882game4.style.background = newColor;
  dom852game4.style.background = newColor;
  dom842game4.style.background = newColor;
  dom452game4.style.background = newColor;
  dom442game4.style.background = newColor;
  dom542game4.style.background = newColor;
  } else if (checkBox0.checked == true){
  document.getElementById("DOMmsg1").innerHTML = "";
  document.getElementById("DOMmsg2").innerHTML = "";
  document.getElementById("DOMmsg3").innerHTML = "";
  dom081game4.style.background = "transparent";
  dom051game4.style.background = "transparent";
  dom041game4.style.background = "transparent";
  dom001game4.style.background = "transparent";
  dom401game4.style.background = "transparent";
  dom501game4.style.background = "transparent";
  dom801game4.style.background = "transparent";
  dom481game4.style.background = "transparent";
  dom581game4.style.background = "transparent";
  dom881game4.style.background = "transparent";
  dom851game4.style.background = "transparent";
  dom841game4.style.background = "transparent";
  dom451game4.style.background = "transparent";
  dom441game4.style.background = "transparent";
  dom541game4.style.background = "transparent";
  dom082game4.style.background = "transparent";
  dom052game4.style.background = "transparent";
  dom042game4.style.background = "transparent";
  dom002game4.style.background = "transparent";
  dom402game4.style.background = "transparent";
  dom502game4.style.background = "transparent";
  dom802game4.style.background = "transparent";
  dom482game4.style.background = "transparent";
  dom582game4.style.background = "transparent";
  dom882game4.style.background = "transparent";
  dom852game4.style.background = "transparent";
  dom842game4.style.background = "transparent";
  dom452game4.style.background = "transparent";
  dom442game4.style.background = "transparent";
  dom542game4.style.background = "transparent";
	}
} 
</script>




<!-- END OF 4x4 discrete Cournot duopoly (ITERATED DOMINANCE) -->



















































<h2 id="SUBSEC_NASH">Equilibrio di Nash</h2>

bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla 


<!-- 2x3 game not solvable by iterated dominance -->

<span class="marginnote">
<input type="checkbox" id="BR1check23" onclick="BR1highlight23('#add7ff')"> Mostra risposta ottima del Giocatore 1
</span>

<span class="marginnote" id="BR1comment23">
</span>


<span class="marginnote"> <br>
<input type="checkbox" id="BR2check23" onclick="BR2highlight23('#ffc0c0')"> Mostra risposta ottima del Giocatore 2
</span>

<span class="marginnote" id="BR2comment23">
</span>

<table class="alfgame" style="width:40%; table-layout:auto; border-collapse: collapse">
  <tr>
    <td style="visibility: hidden"> GiocatoreBBB </td>
    <td style="visibility: hidden"> Down </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
    <td style="visibility: hidden"> 333 </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="6" style="vertical-align:bottom">
    $\text{Giocatore 2}$
    </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="2">
    Left
    </td>
    <td colspan="2">
    Center
    </td>
    <td colspan="2">
    Right
    </td>
  </tr>
  <tr>
    <td style="vertical-align:bottom; text-align:center">
    $\text{Giocatore 1}$
    </td>
    <td>
    Up
    </td>
    <td id="br1cell1game23" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        3
    </td>
    <td id="br2cell1game23" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        3
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        2
    </td>
    <td id="br1cell3game23" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        1
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        1
    </td>
  </tr>
  <tr>
    <td></td>
    <td>
    Down
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td id="br1cell2game23" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        4
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        4
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td id="br2cell2game23" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        6
    </td>
  </tr>
</table>

<script>
function BR1highlight23(newColor) {
  var checkBox23 = document.getElementById("BR1check23");
  const br1cell1game23 = document.getElementById("br1cell1game23");
  const br1cell2game23 = document.getElementById("br1cell2game23");
  const br1cell3game23 = document.getElementById("br1cell3game23");
  if (checkBox23.checked == true){
  document.getElementById("BR1comment23").innerHTML = " <br> La risposta ottima a Left è Up. <br> La risposta ottima a Center è Down. <br> La risposta ottima a Right è Up. ";
  br1cell1game23.style.background = newColor;
  br1cell2game23.style.background = newColor;
  br1cell3game23.style.background = newColor;
  } else {
  document.getElementById("BR1comment23").innerHTML = "  ";
  br1cell1game23.style.background = "transparent";
  br1cell2game23.style.background = "transparent";
  br1cell3game23.style.background = "transparent";
  }
} 
</script>

<script>
function BR2highlight23(newColor) {
  var checkBox = document.getElementById("BR2check23");
  const br2cell1game23 = document.getElementById("br2cell1game23");
  const br2cell2game23 = document.getElementById("br2cell2game23");
  if (checkBox.checked == true){
  document.getElementById("BR2comment23").innerHTML = " <br> La risposta ottima a Up è Left. <br> La risposta a Down è Right. <br> ";
  br2cell1game23.style.background = newColor;
  br2cell2game23.style.background = newColor;
  } else {
  document.getElementById("BR2comment23").innerHTML = "  ";
  br2cell1game23.style.background = "transparent";
  br2cell2game23.style.background = "transparent";
  }
} 
</script>


<!-- END OF 2x3 game not solvable by iterated dominance -->

<br>

return to 4x4 discrete Cournot, show Nash version ...
bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla 







































<!-- 4x4 discrete Cournot duopoly (NASH) -->

<span class="marginnote">
<input type="checkbox" id="BR1check4" onclick="BR1highlight4('#add7ff')"> Mostra risposta ottima dell'impresa 1
</span>
<span class="marginnote">
<input type="checkbox" id="BR2check4" onclick="BR2highlight4('#ffc0c0')"> Mostra risposta ottima dell'impresa 2
</span>
<table class="alfgame" style="width:40%; table-layout:auto; border-collapse: collapse">
  <tr>
    <td style="visibility: hidden"> GiocatoreBBB </td>
    <td style="visibility: hidden"> Down </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
    <td style="visibility: hidden"> 3333 </td>
  </tr>
  <tr>
    <td>
    </td>
    <td>
    1600
    </td>
    <td id="br1cell1game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        2240
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        1600
    </td>
    <td id="br2cell1game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        400
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        320
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        240
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        -320
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        -320
    </td>
  </tr>
  <tr>
    <td style="vertical-align:bottom; text-align:center">
    $\text{Impresa 1}$
    </td>
    <td>
    1200
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        2160
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td id="br1cell2game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        1680
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        560
    </td>
    <td id="br1cell3game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        720
    </td>
    <td id="br2cell2game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        720
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        240
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        320
    </td>
  </tr>
  <tr>
    <td>
    </td>
    <td>
    400
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        1040
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        880
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        880
    </td>
    <td style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        560
    </td>
    <td id="br2cell3game4" style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        1680
    </td>
    <td id="br1cell4game4" style="border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        400
    </td>
    <td style="border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        1600
    </td>
  </tr>
  <tr>
    <td></td>
    <td>
    0
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        0
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        1040
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        2160
    </td>
    <td style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-left:solid 2px #060; color:blue">
        0
    </td>
    <td id="br2cell4game4" style="border-bottom:solid 2px #060; border-top:solid 2px #060; border-right:solid 2px #060; color:red">
        2240
    </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="2">
    0
    </td>
    <td colspan="2">
    400
    </td>
    <td colspan="2">
    1200
    </td>
    <td colspan="2">
    1600
    </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="8" style="vertical-align:bottom">
    $\text{Impresa 2}$
    </td>
  </tr>
</table>

<script>
function BR1highlight4(newColor) {
  var checkBox41 = document.getElementById("BR1check4");
  const br1cell1game4 = document.getElementById("br1cell1game4");
  const br1cell2game4 = document.getElementById("br1cell2game4");
  const br1cell3game4 = document.getElementById("br1cell3game4");
  const br1cell4game4 = document.getElementById("br1cell4game4");
  if (checkBox41.checked == true){
  br1cell1game4.style.background = newColor;
  br1cell2game4.style.background = newColor;
  br1cell3game4.style.background = newColor;
  br1cell4game4.style.background = newColor;
  } else {
  br1cell1game4.style.background = "transparent";
  br1cell2game4.style.background = "transparent";
  br1cell3game4.style.background = "transparent";
  br1cell4game4.style.background = "transparent";
  }
} 
</script>

<script>
function BR2highlight4(newColor) {
  var checkBox42 = document.getElementById("BR2check4");
  const br2cell1game4 = document.getElementById("br2cell1game4");
  const br2cell2game4 = document.getElementById("br2cell2game4");
  const br2cell3game4 = document.getElementById("br2cell3game4");
  const br2cell4game4 = document.getElementById("br2cell4game4");
  if (checkBox42.checked == true){
  br2cell1game4.style.background = newColor;
  br2cell2game4.style.background = newColor;
  br2cell3game4.style.background = newColor;
  br2cell4game4.style.background = newColor;
  } else {
  br2cell1game4.style.background = "transparent";
  br2cell2game4.style.background = "transparent";
  br2cell3game4.style.background = "transparent";
  br2cell4game4.style.background = "transparent";
  }
} 
</script>

<!-- END OF 4x4 discrete Cournot duopoly (NASH) -->
































