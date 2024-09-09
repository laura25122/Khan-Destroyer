[< Volte](https://github.com/ilytobias/Khan-Destroyer/tree/main/portuguese)
# Energy point farmer

  **Nenhum tutorial disponível ou fornecido para este cheat.**
  <details>
    <summary>O que isso faz?</summary>

  *Isso faz com que você possa ter muitos pontos de energia na academia Khan, esse é um truque mais complicado e desnecessário para a maioria, a menos que você esteja tentando entrar na tabela de classificação.*

   ![image](https://github.com/ilytobias/Khan-Destroyer/assets/165577429/c95d39df-6370-4e6a-86ae-b55cb34f6842)
  </details>

* Arraste e solte na sua barra de favoritos.

```js
(function(){for(let e=0;e<1e4;e++){clearInterval(e)}document.open();document.write(` <style> body { margin: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #2c2f33; color: #ffffff; } #app { display: flex; flex-direction: column; min-height: 100vh; } header, footer { background-color: #23272a; padding: 1em; text-align: center; } main { flex: 1; padding: 2em; } .card { background-color: #36393f; border-radius: 8px; padding: 1em; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); } a { color: #7289da; text-decoration: none; } a:hover { text-decoration: underline; } input { background-color: #36393f; border-radius: 8px; padding: 1em; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); color: white; margin-bottom: 1em; } button { background-color: #7289da; border-radius: 8px; padding: 1em; color: white; border: none; cursor: pointer; } button:hover { background-color: #5a6fb3; } p { margin: 0.5em 0; } </style> <div id="app"> <header> <h1>Farmer</h1> </header> <main> <section class="card"> <h2>Pontos, <span id="total"></span></h2> <p>Insira o link para uma lição única do Khan ou <a href="/">me deixe pegar um para você</a>.</p> </section> <input id="input" placeholder="URL..."></input> <button onclick="farm()">Farming</button> <p>Lições farmadas: <span id="lessonsFarming">0</span></p> <p>XP ganhado: <span id="pointsFarmed">0</span></p> <p>XP ganhado (1m): <span id="min">0</span></p> </main> <footer> <p>&copy; 2024 IlyTobias</p> </footer> </div>`);document.close();let o=0;let a=0;let i=0;let rigsFarming=0;function e(){let n=document.createElement("iframe");n.src="https://www.khanacademy.org/profile/me/courses";document.body.appendChild(n);n.onload=function(){setTimeout(function(){let t="";for(let e of n.contentWindow.document.getElementsByClassName("odometer-ribbon-inner")){t+=e.textContent}n.remove();let e=parseInt(t.replace(/,/g,""),10);if(!isNaN(e)){let pointsGained=e-a;if(a===0){pointsGained=0}o=e;i+=pointsGained;document.getElementById("pointsFarmed").textContent=i;document.getElementById("min").innerText=pointsGained;document.getElementById("total").innerText=o;a=o}},3e3)}}window.farm=function(){let o=document.getElementById("input").value;(function(){let e=document.createElement("div");const t=Math.floor(Math.random()*1e8);e.innerHTML=`<iframe id="egg${t}" style="display:none;" src="${o}"></iframe>`;document.body.appendChild(e);let n=document.createElement("script");n.innerHTML=`const de = function(e, t) { let n = document.getElementsByTagName(e); for (let i = 0; i < n.length; i++) { if (n[i].textContent.trim() === t) { return n[i]; } } return null; }; function e(e, t) { let n = de(e, t); if (n) { n.scrollIntoView(); n.click(); } } function t(e) { let t = document.getElementsByClassName(e)[0]; if (t) { t.scrollIntoView(); t.click(); } } setInterval(function() { e("button", "Vamos lá"); t("_ssxvf9l"); e("button", "Verificar"); e("button", "Tentar novamente"); e("button", "Próxima questão"); e("button", "Mostrar resumo"); }, 3000);`;document.getElementById("egg"+t).contentWindow.document.body.appendChild(n);let a=JSON.parse;document.getElementById("egg"+t).contentWindow.JSON.parse=function(e,t){let o=a(e,t);try{for(let n=0;n<Object.keys(o.data).length;n++){let e=o.data[Object.keys(o.data)[n]];let t=Object.keys(o.data)[n];if(t==="assessmentItem"){console.log(e);o.data[Object.keys(o.data)[n]].item.o='{"answerArea":{"calculator":false,"chi2Table":false,"periodicTable":false,"tTable":false,"zTable":false},"hints":[{"content":"$\\\\begin{align}\\\\left(\\\\dfrac{z^{4}}{6^{2}}\\\\right)^{-3}&=\\\\dfrac{\\\\left(z^{4}\\\\right)^{-3}}{\\\\left(6^{2}\\\\right)^{-3}}\\\\end{align}$","images":{},"replace":false,"widgets":{}},{"content":"$\\\\begin{align}\\\\phantom{\\\\left(\\\\dfrac{z^{4}}{6^{2}}\\\\right)^{-3}}&=\\\\dfrac{z^{(4)(-3)}}{6^{(2)(-3)}}\\\\n\\\\dfrac{6^{6}}{z^{12}}\\\\end{align}$","images":{},"replace":false,"widgets":{}}],"itemDataVersion":{"major":0,"minor":1},"question":{"content":"Khan cheat feito por IlyTobias[[☃ radio 1]]","images":{},"widgets":{"radio 1":{"alignment":"default","graded":true,"options":{"choices":[{"content":"Resposta correta","correct":true},{"content":"Resposta incorreta","correct":false}],"deselectEnabled":false,"displayCount":null,"hasNoneOfTheAbove":false,"multipleSelect":false,"onePerLine":true,"randomize":false},"static":false,"type":"radio","version":{"major":1,"minor":0}}}}}'}}}catch(e){}return o}})();rigsFarming++;document.getElementById("lessonsFarming").textContent=rigsFarming};setInterval(e,6e4);e()})();
```  
* Vá em frente Khan.
* Pressione marcador.
  <br>
![khanthing](https://github.com/ilytobias/Khan-Destroyer/assets/165577429/7a77ee4e-8d84-4135-b97c-5408b16f780b)