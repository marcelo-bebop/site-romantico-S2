<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <title>Para o amor da minha vida 💗</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Quicksand', sans-serif;
      background-color: #000;
      color: #fff;
      overflow-x: hidden;
    }

    #telaEntrada {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      background: #1a1a1a;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      z-index: 9999;
      text-align: center;
      padding: 20px;
    }

    #telaEntrada h1 {
      font-size: 2em;
      color: #ffcce6;
      margin-bottom: 30px;
    }

    .btnEntrada {
      background: #ffcce6;
      border: none;
      padding: 12px 20px;
      margin: 10px;
      border-radius: 12px;
      font-weight: bold;
      color: #000;
      cursor: pointer;
      font-size: 1em;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: background 0.3s ease;
    }

    .btnEntrada:hover {
      background: #ff99cc;
    }

    #gatinhoTriste {
      display: none;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
      height: 100vh;
    }

    #gatinhoTriste img {
      width: 250px;
      margin-bottom: 20px;
      border-radius: 16px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.5);
    }

    #conteudoSite {
      display: none;
    }

    body.siteativo {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      background-image: url('https://i.pinimg.com/736x/56/e5/4a/56e54a34cf5c4aa97ca1383f844e3285.jpg');
      background-size: contain;
      background-position: center;
      background-repeat: no-repeat;
      backdrop-filter: brightness(0.6) blur(2px);
      justify-content: center;
      align-items: center;
      overflow-y: auto;
      position: relative;
    }

    .mensagem-container {
      margin: 40px auto;
      background-color: rgba(255, 255, 255, 0.15);
      border-radius: 20px;
      padding: 30px;
      max-width: 600px;
      text-align: center;
      color: #fff;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
      animation: aparecer 2s ease-in-out;
      position: relative;
      z-index: 10;
    }

    h1 {
      color: #ffcce6;
      margin-bottom: 20px;
      font-size: 2em;
    }

    p {
      font-size: 1.1em;
      line-height: 1.6;
      color: #ffffff;
      text-shadow: 0 0 2px #000;
      white-space: pre-wrap;
      margin-bottom: 16px;
    }

    @keyframes aparecer {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    #btnMusica {
      position: fixed;
      top: 20px;
      right: 20px;
      background: #ffcce6;
      border: none;
      padding: 10px 16px;
      border-radius: 12px;
      font-weight: bold;
      color: #000;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: background 0.3s ease;
      z-index: 100;
    }

    #btnMusica:hover {
      background: #ff99cc;
    }

    #btnSurpresa {
      display: block;
      margin: 30px auto;
      background: #ffcce6;
      border: none;
      padding: 10px 16px;
      border-radius: 12px;
      font-weight: bold;
      color: #000;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: background 0.3s ease;
    }

    #btnSurpresa:hover {
      background: #ff99cc;
    }

    #cartaSecreta {
      display: none;
      margin-top: 20px;
      background-color: rgba(255, 255, 255, 0.15);
      border-radius: 20px;
      padding: 30px;
      max-width: 600px;
      text-align: center;
      color: #fff;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
      animation: aparecer 1s ease-in-out;
      margin: 0 auto;
    }

    #cartaSecreta img {
      max-width: 100%;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.4);
    }

    #cronometroEuTeAmo, #cronometroPrimeiraConversa {
      margin-top: 20px;
      font-size: 1.2em;
      color: #ffcce6;
      font-weight: bold;
      text-align: center;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
      text-shadow: 0 0 4px #000;
    }

    .mouse-heart {
      position: absolute;
      width: 12px;
      height: 12px;
      background: #ff99cc;
      transform: rotate(-45deg);
      pointer-events: none;
      opacity: 0.8;
      animation: mouse-float 1s ease-out;
      z-index: 999;
    }

    .mouse-heart::before,
    .mouse-heart::after {
      content: "";
      position: absolute;
      width: 12px;
      height: 12px;
      background: #ff99cc;
      border-radius: 50%;
    }

    .mouse-heart::before {
      top: -6px;
      left: 0;
    }

    .mouse-heart::after {
      left: 6px;
      top: 0;
    }

    @keyframes mouse-float {
      0% { transform: translateY(0) scale(1) rotate(-45deg); opacity: 0.8; }
      100% { transform: translateY(-20px) scale(1.5) rotate(-45deg); opacity: 0; }
    }
  </style>
</head>
<body>
  <!-- ENTRADA -->
  <div id="telaEntrada">
    <h1>Você quer ver o nosso eterno cantinho do amor q eu fiz pra gente?</h1>
    <button class="btnEntrada" onclick="entrarSite()">Sim, meu amor.</button>
    <button class="btnEntrada" onclick="mostrarGatinho()">Não 🥺</button>
  </div>

  <!-- GATINHO TRISTE -->
  <div id="gatinhoTriste">
    <img src="https://i.pinimg.com/736x/7f/02/c2/7f02c2ef556012fff6550ea9346497ac.jpg" alt="Gatinho triste">
    <p style="color: #ffcce6; font-size: 1.2em;">Poxa... eu só queria te mostrar o quanto te amo 😿</p>
    <button class="btnEntrada" onclick="voltarParaEntrada()">Voltar 😢</button>
  </div>

  <!-- CONTEÚDO PRINCIPAL -->
  <div id="conteudoSite">
    <div class="mensagem-container">
      <h1>Para o amor da minha vida 💗</h1>
    
         <p>oii amor, td bem? entao meio q oq vc esta vendo ai foi tudo feito por mim, com as minhas mãos eu fiz isso pra vc e vc pode até achar q tudo isso foi so copia e cola mas eu tive a opção de fazer isso e mostrar pra vc e vc ficar super feliz com isso mas eu nao ia sentir q eu tava fazendo isso de verdade sabe, a sua felicidade nao ia ser por um esforço meu e sim por um copia e cola que eu ia ter q guardar pelo resto da minha vida porque vc ia ficar chateada se eu contasse então eu coloquei minha mão na massa e mesmo com meu conhecimento praticamente nulo sobre programação eu fiz isso pra vc, com a ajuda do chatgpt eu fiz isso pra vc e talvez vc pense "nossa mas com o chatgpt até eu, queria ver sozinho" entao meio q eu nao ia conseguir fazer isso sozinho pq nao sei de nada e acho q ele é o único q poderia me ajudar, ele me achou a baixar e a programar e eu so escrevia o que ele mandava, eu nao sei se vai ficar perfeito, na vdd a única coisa q eu sei é q nao vai ficar perfeito, no mínimo um meia boca, mas vai ser um meia boca com um esforço enorme meu, e eu gostaria q vc apreciasse o que eu fiz pra vc e pudesse curtir o que eu criei pra vc, nao vai estar o melhor mas lembra que foi de coração.</p>

        <p>desde antes da gente brigar eu já pensava nisso ai prova oq vc fala q eu so penso e nao faço mas na minha cabeça ia ser algo impossível tipo q eu ia passar horas fazendo isso e na vdd é super tranquilo pelo menos é o que eu to achando sabe entao mesmo a gente estando brigados eu quero fazer isso pra vc, sei q isso nao vai ajudar mas sabe aquela sensação q se eu fizer ela vai gostar e uma das coisas q eu mais amo em vc é o seu sorriso, vc sempre fala q ele é feio e eu nunca entendi pq eu sempre achei ele tao lindo e tao único q se eu pudesse eu so olhava pra ele o dia inteiro, e até hj eu acho uma bobagem vc fazer aquela cirurgia na sua gengiva sabe pq eu acho ele tao lindo e espero q com isso q eu fiz eu possa soltar mais um riso de vc ou até um sorriso sincero q eu estou morrendo de sdds de ver.</p>

        <p>desde q a gente brigou meus dias viraram cinzas, sabe a nuvem da família adams que onde eles andam essa nuvem persegue eles, entao era meio q isso q eu sentia meu dias nao eram mais os meus sem os seus te amo e por isso q quando vc fala eu fico mt feliz com isso eu sei q a culpa é minha e sei q eu estraguei com tudo mas eu sinto q vamos resolver isso e vamos ter mais uma história pra contar pros nossos filhos ou nosso casalzinho de crianças ou duas filhas linda, Deus me livre dois meninos, brincadeiras a parte como eu falei em uma mensagem passada eu sinto sdds das nossas conversas e eu to louco pra ter elas de volta, meu sonho é vc estar virada pra frente ai eu te chamo e começo a te explicar super animado oq é frutiguear aero q eu to louco pra explicar pra vc oq é e vc fazendo aquela cara de quem ta tentando entender alguma coisa ou vc tentando contar uma das quelas fofocas q eu nao entendo nada mas eu odeio várias pessoas so pq vc odeia ou vc brigar comigo por coisinhas bobas ou implicando comigo como fazia e virava pra frente e ficava rindo escondido pra eu nao ver ou das vezes q eu fazia vc morrer de rir por besteiras q eu disse.</p>

        <p>se chegasse um cara e falasse "o seu perdão ou ser rico e nunca mais precisar trabalhar" eu sem êxito escolheria o seu perdão, uma coisa q eu também amava mt era te deixar tímida por coisas fofas q eu fazia, teve uma vez onde a gente tava abracadinhos e o jv tava junto ai eu falei q ia pra minha mesa e te dei um beijo na bochecha super aleatório sabe e vc fez uma cara tao de surpresa e de timidez q talvez vc nao lembre mas pra mim foi algo tao simples mas q me marcou tanto q eu lembro até hj, e além de tudo isso sdds dos nossos abraços e ainda pior oq me mata mais é nao poder te abraçar quando a gente voltava do lanche, mds como eu amava aquilo todo dia era uma surpresa diferente como o narducci correndo pra me abraçar ou vc pulando e me abraçando super feliz, esses momentos eu tenho mt sdds e com isso eu nao quero na vdd eu quero mas nao é o intuito principal q vc me desculpe por tudo q eu fiz isso é so uma coisa q eu queria q vc olhasse e apreciasse oq eu fiz, olhando e dizendo o quanto vc gostou do q eu fiz, e dps de vc ler essa mensagem claro q vai ser uma opção sua e eu até prefiro sinceramente q vc mande uma mensagem falando sobre oq vc achou, oq vc mais gostou e sobre oq vc sentiu lendo isso, meu intuito nao é forçar vc respondeu o meu eu te amo mas sim fazer vc sentir q eu ainda te amo com todas as minhas forças e se vc quiser ai já é uma opção sua responder meu eu te amo acho q essa seria a melhor hora mas ai é uma questão sua.</p>

        <p>espero q vc consiga sentir oq eu quis trazer com essa mensagem e te falar q isso tudo foi feito por mim e foi feito com mt esforço e com mt amor e eu já tô escrevendo essa mensagem a mt tempo tipo meus dedos já estão até cansados e eu so quero q vc ainda se sinta amada nao com os meus eu te amo mas sim com esse ato de amor q eu to fazendo pra vc e com os meus eu te amo sim ta kkkkkkkkkkkkk e eu espero q vc nao comente isso com ninguém, se vc gostar mt e achar q eu me superei e q foi super fofo eu deixo vc mostrar pra sua mãe, deixo nao ne vc pode mostrar pra quem vc quiser mas acho q se for pra sua mãe so eu ficaria mais tranquilo sabe pq eu imagino q se for pras suas amigas elas vao falar tipo "ai miga isso tudo foi copia e cola até as mensagens dele, ele te machucou tanto e vc vai cair nesse papinho, vc é mt idiota ne" nao sei pq eu penso q elas falariam isso sabe kkkkkkkkkkkkk, brincadeira a parte se vc gostar mt e quiser claro eu ficaria lisonjeado se vc mostrasse pra sua mãe e junto com sua resposta a isso mande a opinião da sua mãe sobre isso q eu fiz pra vc e lembra q isso nao foi so um ato de vc me desculpar por tudo q eu fiz pra vc e sim eu abrindo meu peito pra vc, de todas as vezes q eu me abri com vc essa foi a q eu mais me abri q quis q vc sentisse oq eu estou sentido por vc e eu nao quero q vc já me responda como respondia antes me chamando de amor e tudo mais e sim uma mensagem do jeito q vc quiser me chamando de amor ou nao ou  respondendo meu eu te amo ou nao e so peco q vc escreva tudo q sentiu e achou sobre isso sabe, enfim já to escrevendo isso a mt tempo sem parar e tudo q começa acaba entao esse vai ser o meu encerramento, lembra q eu te amo mt mt mt e trocaria todos os meus amigos pra ficar contigo ou faria loucuras de amor por vc e que pra mim é a maior mostra de amor que alguém pode falar, eu falo a vc agora eu mato e morro por vc  enfim eu te amo mt mt mt amor vc nao sabe o quanto e espero q vc ame essa mensagem o quanto q eu amo vc, tchau amor</p>
      
        <p><strong>EU TE AMO MUITO MUITO MUITO, INCONDICIONALMENTE E INFINITAMENTE, AMOR DA MINHA VIDA TODINHA</strong></p>
    </div>

    <p style="margin-top: 40px; font-size: 1.1em; text-align: center; color: #ffcce6;">
      — Do seu eterno bobo apaixonado, <strong>Marcelo</strong> 💌
    </p>

    <button id="btnSurpresa" onclick="mostrarCarta()">💌 Clique para uma surpresa</button>

    <div id="cartaSecreta" style="display: none;">
      <img src="47d9fa34-c912-4097-9619-e5c4d233b240.jpg" alt="Foto surpresa" style="max-width: 100%; border-radius: 20px; box-shadow: 0 8px 20px rgba(0,0,0,0.4);">
    </div>

    <p id="cronometroEuTeAmo"></p>
    <p id="cronometroPrimeiraConversa"></p>

    <button id="btnMusica" onclick="TocarMusica()">💗 Tocar Musica</button>
  </div>

  <audio id="audio" loop>
    <source src="lovers-rock.mp3" type="audio/mpeg" />
    Seu navegador não suporta áudio.
  </audio>

  <script>
    function entrarSite() {
      document.getElementById('telaEntrada').style.display = 'none';
      document.getElementById('conteudoSite').style.display = 'block';
      document.body.classList.add('siteativo');
    }

    function mostrarGatinho() {
      document.getElementById('telaEntrada').style.display = 'none';
      document.getElementById('gatinhoTriste').style.display = 'flex';
    }

    function voltarParaEntrada() {
      document.getElementById('gatinhoTriste').style.display = 'none';
      document.getElementById('telaEntrada').style.display = 'flex';
    }

    const audio = document.getElementById('audio');
    function TocarMusica() {
      audio.play();
      document.getElementById('btnMusica').style.display = 'none';
    }

    function mostrarCarta() {
      const carta = document.getElementById('cartaSecreta');
      carta.style.display = carta.style.display === 'none' ? 'block' : 'none';
      document.getElementById('btnSurpresa').textContent = carta.style.display === 'block'
        ? '💌 Esconder surpresa' : '💌 Clique para uma surpresa';
    }

    const dataEuTeAmo = new Date(2024, 4, 18);
    const dataPrimeiraConversa = new Date(2024, 3, 19);

    function diferencaDias(dataInicial, dataFinal) {
      const inicio = new Date(dataInicial.getFullYear(), dataInicial.getMonth(), dataInicial.getDate());
      const fim = new Date(dataFinal.getFullYear(), dataFinal.getMonth(), dataFinal.getDate());
      const diffTime = fim - inicio;
      return Math.floor(diffTime / (1000 * 60 * 60 * 24));
    }

    function atualizarCronometro() {
      const agora = new Date();
      const diasEuTeAmo = diferencaDias(dataEuTeAmo, agora);
      const diasPrimeiraConversa = diferencaDias(dataPrimeiraConversa, agora);
      document.getElementById('cronometroEuTeAmo').textContent = `Já faz ${diasEuTeAmo} dias que eu disse "Eu te amo" pra você (que na vdd é te amo mas o amor é o mesmo ta kkkkkkkkkkkk) 💗`;
      document.getElementById('cronometroPrimeiraConversa').textContent = `Já faz ${diasPrimeiraConversa} dias desde nossa primeira conversa 💬`;
    }

    setInterval(atualizarCronometro, 60000);
    atualizarCronometro();

   let ultimoHeart;

let timeoutUltimoHeart;

let removerUltimosTimeout;

document.addEventListener("mousemove", function(e) {
  const heart = document.createElement("div");
  heart.classList.add("mouse-heart");
  heart.style.left = (e.pageX + (Math.random() * 30 - 15)) + "px";
  heart.style.top = (e.pageY + (Math.random() * 30 - 30)) + "px";
  document.body.appendChild(heart);

  // Remove cada coração após 1s normalmente
  setTimeout(() => {
    heart.remove();
  }, 1000);

  // Limpa o timeout anterior para remover corações travados
  clearTimeout(removerUltimosTimeout);

  // Quando o mouse para, remove todos os corações restantes após 100ms
  removerUltimosTimeout = setTimeout(() => {
    document.querySelectorAll('.mouse-heart').forEach(el => el.remove());
  }, 400);
});
  </script>
</body>
</html>
