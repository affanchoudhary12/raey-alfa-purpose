<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dear Alfa</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html, body {
      height: 100%;
      overflow: hidden;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(120deg, #fdeff9, #ec38bc, #7303c0);
      background-size: 400% 400%;
      animation: gradientBG 15s ease infinite;
      color: #333;
    }
    @keyframes gradientBG {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }
    header {
      text-align: center;
      padding: 40px 20px;
      background: rgba(255,255,255,0.1);
      color: white;
      font-family: 'Great Vibes', cursive;
    }
    header h1 {
      font-size: 3em;
    }
    section {
      height: 100vh;
      display: none;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
      padding: 40px;
      animation: fadeIn 1s ease;
      background: rgba(255,255,255,0.2);
      border-radius: 16px;
      backdrop-filter: blur(10px);
      margin: 20px;
    }
    section.active {
      display: flex;
    }
    .button {
      margin-top: 40px;
      background: #ec407a;
      color: white;
      border: none;
      padding: 12px 30px;
      font-size: 1em;
      border-radius: 30px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .button:hover {
      background: #d81b60;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0,0,0,0.2);
      color: white;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(20px);}
      to {opacity: 1; transform: translateY(0);}
    }
    .bigLove {
      font-size: 2.5em;
      color: #ff4081;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Dear Alfa ❤️</h1>
    <p>A journey from friendship to forever...</p>
  </header>

  <section id="page1" class="active">
    <h2>1. Welcome Alfa</h2>
    <p>This site isn't just code—it's my soul speaking to yours.</p>
    <button class="button" onclick="nextPage('page2')">Let’s Begin 💫</button>
  </section>

  <section id="page2">
    <h2>2. How We Met</h2>
    <p>Alfa, jab tum mere bagal se nikli thi aur maine bola "Astaghfirullah", tumne sun liya. Fir shuru hua woh raasta jahan hum baat karne lage. Mujhe tum dino se achi lag rahi thi... par baat hui sirf 4 din pehle. Tumne pehchana ki main wahi ladka hoon. Tab se tum ho mere dil mein.</p>
    <button class="button" onclick="nextPage('page3')">Next 🌸</button>
  </section>

  <section id="page3">
    <h2>3. About You</h2>
    <p>Tum meri gali ke end se ho, par mere dil ke centre mein. Tumse baat karne ke baad laga, ab kisi aur se baat karna bekaar hai. Tumne mujhe rubber band diya tha, jo main aaj tak pehne hua hoon... aur hamesha pehnuunga, kyunki main tumhara hoon, Alfa.</p>
    <button class="button" onclick="nextPage('page4')">Next ✨</button>
  </section>

  <section id="page4">
    <h2>4. From Ilma to You</h2>
    <p>Tum jaanti ho meri ex Ilma thi... par yeh website kehte hai ki ab sirf ek naam hai mere dil mein – Alfa. Tum mere liye sab kuch ho. Tum meri rooh ho. Main tumse jism nahi, rooh se pyaar karta hoon.</p>
    <button class="button" onclick="nextPage('page5')">Next 💗</button>
  </section>

  <section id="page5">
    <h2>5. Mirror Talk</h2>
    <p>Alfa, tum khud se ek baar mirror me dekhna... aankhon me aankhon daal ke bolna: <br><br><strong>"Main special hoon, main pyaar ke laayak hoon... Affan mujhe dil se chahta hai."</strong></p>
    <div class="bigLove">I LOVE YOU ❤️</div>
    <button class="button" onclick="nextPage('page6')">Next 🪞</button>
  </section>

  <section id="page6">
    <h2>6. My Soul to Yours</h2>
    <p>Mujhe tumhare jism se nahi, tumhari rooh se mohabbat hai. Tum mere liye ek dua ho, jo mujhe har roz milti hai. Agar tum sirf timepass kar rahi ho to pls "No" kehna... Par agar sach mein saath dena hai to tabhi "Haan" kehna...</p>
    <button class="button" onclick="nextPage('page7')">Next 💬</button>
  </section>

  <section id="page7">
    <h2>7. My Diary</h2>
    <p>Alfa, main tumhe apni har diary me likhta hoon. Tum mere din ka sabse haseen hissa ho. Har raat, tumhare baare me kuch na kuch zarur likhta hoon – tumhare bare me, tumhari baton me, tumhari khamoshi me bhi ek jazba hai jo meri rooh ko chhoo jaata hai.</p>
    <button class="button" onclick="nextPage('page8')">Next 📔</button>
  </section>

  <section id="page8">
    <h2>8. Trust</h2>
    <p>Tum par meri poori zindagi bhar ka bharosa hai. Jab tumne bina maange mujhe apne saari IDs ke passwords de diye... mujhe samajh aaya ki tum mujh par waqai bharosa karti ho. Agar tumhe meri kisi bhi cheez ka password chahiye... just ask.</p>
    <button class="button" onclick="nextPage('page9')">Next 🔐</button>
  </section>

  <section id="page9">
    <h2>9. Fun Game!</h2>
    <p>Chalo thoda smile karte hain!👇<br><br>Guess karo – agar Affan ek pushpa type hero hota, to tumhara naam kya hota? 😜<br><br>Options:<br>1. Alfa Rani 💃<br>2. Gulabo 2.0 🌸<br>3. Dil Ki Dhadkan 💗<br>4. Jaaneman Forever 💞<br><br>(Answer: Har baar tum hi ho 😉)</p>
    <button class="button" onclick="nextPage('page10')">Next 🎮</button>
  </section>

  <section id="page10">
    <h2>10. The Proposal</h2>
    <p>Alfa, will you be mine? 💍<br><br>Agar haan karti ho to mujhe teen baar "I Love You" bolna hoga. Main pehli baar bolne ke baad, tumse fir se puchunga... fir teesri baar. Kyunki main tumhare har lafz ko yaad rakhna chahta hoon.</p>
    <button class="button" onclick="nextPage('page11')">Next 💞</button>
  </section>

  <section id="page11">
    <h2>11. Final Words</h2>
    <p>Alfa, main tumse jhooth nahi bolta. Agar tum mere saath ho, to main zindagi bhar tumhara saath nibhaunga. Main tumhara bracelet pehenta hoon, aur hamesha pehenta rahunga.<br><br>Tum mera band ho, meri dua ho... aur ab bas tum hi ho.</p>
    <div class="bigLove">I LOVE YOU ❤️</div>
  </section>

  <footer>
    Made with 💗 by Affan – For Alfa, Soul to Soul.
  </footer>

  <script>
    function nextPage(id) {
      const current = document.querySelector('section.active');
      const next = document.getElementById(id);
      if (current) current.classList.remove('active');
      if (next) next.classList.add('active');
    }
  </script>
</body>
</html>
