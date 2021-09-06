---
title: "#1 Exemplo de post"
date: 2021-08-31T19:45:41-03:00
draft: true
---

# Aqui está um exemplo de post
Você coloca títulos como o de cima (que é meio desnecessário pois o `title` da configuração já aparece do mesmo tamanho)

Textos funcionam normais, **em negrito**, *em italico* ou até __assim em negrito__ ou _assim em italico_. Você pode inclusive colocar coisas **_em negrito-italico_**. Ou então ~~riscadas~~!

Se quiser pode encher de [Links com títulos bonitos](https://lmgtfy.app/?q=Como+escrever+textos+usando+Markdown)
Coisas que você quer chamar a atenção ou são "códigos/palavras chave" podem ficar na `caixinha amarela`.
## Ou até subtítulos
- Listas são simples
- Itens não numerados
  - tem sublistas

1. Numerados
1. Também funcionam

* Asterisco
  * sublistas
* Também serve

### Sub-subtítulos
#### Ou até mais
##### Sem limites

Você pode formatar código usando:

```python
# isso aqui fica formatado como código

# E pode ter até syntax highlight
# Se for alguma linguagem conhecida
def tipo_python():
    return "oi"
```

Pode até colocar "markdown"

```markdown
# isso é um markdown
* com listas
  * e sublistas
* bem legais
```

Também pode colocar imagens

![exemplo](/img/froot_loops.jpeg)

Desse jeito também serve _que da pra controlar melhor_:

{{< figure src="/img/froot_loops.jpeg" title="Froot Loops" height="100px" >}}

E até embeddings de video

* Do youtube
{{< youtube dQw4w9WgXcQ >}}

Ou então de posts do instagram (nem o embed nem esse jeito aqui funcionam direito - colocando a imagem aqui msm, acho que insta ta frescurento):

{{< instagram CR4OtTrl5f2 >}}

Até tweets:

{{< tweet 1401646054353903620 >}}

Você pode até meter o louco e colocar coisas em HTML direto!

<button>Aperte aqui!</button>

Até coisas malucas:
<!-- Início da coisa maluca -->
<hr>

<p>Test your Response time!</p>
Click on "Start" first, and wait until the background color changes. As soon as it changes, hit "stop!"

<script language="JavaScript">
<!--

//Reflext Tester- By Andy Scott (based on script by Jasper van Zandbeek)
//http://www.geocities.com/SiliconValley/Station/4320/
//Submitted to Dynamic Drive for inclusion
//Visit http://www.dynamicdrive.com for this script

var startTime=new Date();
var endTime=new Date();
var startPressed=false;
var bgChangeStarted=false;
var maxWait=20;
var timerID;


var colors=new Array("tomato","chocolate","limegreen","crimson","darkslategray",
"aliceblue","mediumslateblue","cornflowerblue","darkorchid","darkkhaki","coral",
"darkolivegreen","cadetblue")

if (document.all||document.getElementById)
document.write('<div id="reflex" style="width:135px;height:135px;border:1px solid black" onClick="stopTest()"></div>')

function startTest()
{
        if (document.all)
        document.all.reflex.style.backgroundColor=colors[Math.floor(Math.random()*colors.length)];
        else if (document.getElementById)
	document.getElementById("reflex").style.backgroundColor=colors[Math.floor(Math.random()*colors.length)];
        else if (document.layers)
        document.reflexns.document.reflexns_sub.document.bgColor=colors[Math.floor(Math.random()*colors.length)];
	bgChangeStarted=true;
	startTime=new Date();
}

function remark(responseTime)
{
	var responseString="";
	if (responseTime < 0.10)
		responseString="Well done!";
	if (responseTime >= 0.10 && responseTime < 0.20)
		responseString="Nice!";
	if (responseTime >=0.20 && responseTime < 0.30)
		responseString="Could be better...";
	if (responseTime >=0.30 && responseTime < 0.60)
		responseString="Keep practising!";
	if (responseTime >=0.60 && responseTime < 1)
		responseString="Have you been drinking?";
	if (responseTime >=1)
		responseString="Did you fall asleep?";

	return responseString;
}

function stopTest()
{
	if(bgChangeStarted)
	{
		endTime=new Date();
		var responseTime=(endTime.getTime()-startTime.getTime())/1000;
                if (document.all)
		document.all.reflex.style.backgroundColor="white";
                else if (document.getElementById)
		document.getElementById("reflex").style.backgroundColor="white";
                else if (document.layers)
                document.reflexns.document.reflexns_sub.document.bgColor="white";      
		alert("Your response time is: " + responseTime + " seconds " + "\n" + remark(responseTime));
		startPressed=false;
		bgChangeStarted=false;
	}
	else
	{
		if (!startPressed)
		{
			alert("press start first to start test");
		}
		else
		{       
			clearTimeout(timerID);
			startPressed=false;             
			alert("cheater! you pressed too early!");
		}               
	}
}

var randMULTIPLIER=0x015a4e35;
var randINCREMENT=1;
var today=new Date();
var randSeed=today.getSeconds();
function randNumber()
{
	randSeed = (randMULTIPLIER * randSeed + randINCREMENT) % (1 << 31);
	return((randSeed >> 15) & 0x7fff) / 32767;
}

function startit()
{
	if(startPressed)
	{
		alert("Already started. Press stop to stop");
		return;
	}
	else
	{
		startPressed=true; 
		timerID=setTimeout('startTest()', 6000*randNumber());
	}
}
// --> 
</script>
<br>


<ilayer id="reflexns" width=135; height=135;><layer id="reflexns_sub" width=135; height=135; left=0 top=0 bgColor=yellow></layer></ilayer>

<form name="response">

<input type="button" value="  start  " onClick="startit()" style="font-weight:bold">
<input type="button" value="  stop  " onClick="stopTest()" style="font-weight:bold">
</form>

<p align="center"><font face="Arial" size="-2">Free DHTML scripts provided by<br>
<a href="http://www.dynamicdrive.com">Dynamic Drive</a></font></p>
<!-- Fim da coisa maluca -->