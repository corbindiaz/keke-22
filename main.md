---
layout: default
title: Home
---

<style>
body {
  background-color: pink;
  font-family: Arial, sans-serif;
  text-align: left1;
}

/* Button styling */
.heart-button {
  padding: 14px 28px;
  font-size: 18px;
  background-color: hotpink;
  color: white;
  border: none;
  border-radius: 10px;
  cursor: pointer;
}

.heart-button:hover {
  background-color: deeppink;
}

.heart {
  width: 30px;
  height: auto;
  position: fixed;
  animation: floatUp 1.5s ease-out forwards;
  pointer-events: none;
}

/* Animation */
@keyframes floatUp {
  0% {
    transform: translateY(0) scale(1);
    opacity: 1;
  }
  100% {
    transform: translateY(-150px) scale(1.5);
    opacity: 0;
  }
}
</style>


<button class="heart-button" onclick="shootHearts()">WHOOOOOOOOOOO</button>

hi baby

<p align="center">
  <video autoplay loop muted playsinline width="600">
    <source src="images/me_and_baby.mp4" type="video/mp4">
  </video>
</p>


Oh baby, my baby<br>
How are you doing today?<br>
I hope its the sweetest<br>
You know im sincere - est<br>
When I wish you love from far away.

<img src="images/IMG_6181.jpeg" width="500">

Twenty two years of age you are<br>
Wow you must really be so wise<br>
And throughout her days,<br>
she still has the prettiest gaze<br>
And is beautiful from her head knees toes and thighs!

<img src="images/IMG_5902.JPG" width="500">

You truly make me feel so special baby<br>
I really hope you know that well.<br>
Because If I was there right now, I cook you a dish<br>
It would taste so delish<br>
It may even be better than Taco Bell.

<img src="images/lp_image(1).jpeg" width="500">

I really can't wait until we're together<br>
And hug you so tightly, it be a charm!<br>
Because even if we are always late<br>
I'm telling you there is nothing more great<br>
Than just laying and cuddling in each others arms.

I loved every second I've spent with you<br>
these past several months, wow its really flew by!<br>
From the dream that was Tampa, To the night in Boston,<br>
And the heaven of Cape Cod, and then again out in Boston,<br>
It couldn't get any better, I could cry

<img src="images/IMG_9015.JPG" width="500">

And it wasn't so long ago, we hadn't talked at all<br>
(Except for all those desperate texts to you)<br>
And then you reached out<br>
On my birthday, whats this about?<br>
We're nearly full circle, now it's you're twenty-two!

Oh baby, my baby, me sweet dearest, my one dearest<br>
How are you doing today, oh yes?<br>
It's my favorite question to ask<br>
It will always be my task,<br>
Because you mean the world to me, my princess.

<img src="images/IMG_6009.JPG" width="500">


HAPPY BIRTHDAY MY PRETTY BABY GIRLLLLLLLL!!!!!!!!!!!!!<br>
You're so funny and sweet and pretty and beautiful and hot and sexy and cute baby I love you so so so much!!!!! I know it's been a ruff week and I know you'll likely spend a lot of today studying, but I hope you have such a wonderful day regardless. You're twenty two!!!!! That's so exciting my baby!!! You're almost there babe, on the final stretch, your exam will be over, and then you'll be done! And then I'll come and visit and we'll have so much fun my baby <333

Just know that no matter how rough it gets, no matter how much it seems like life just keeps happening and its hard to keep track, just know that I'm here, you're here, your siblings are here, your family and friends are here, Boston is here, and everything is gonna be okay. We'll all get through it together my sweet love.

Also, soon its going to be the anniversary of when I reached out a little after your 21st because I desparately wanted to talk. And now here we are! It's been such a wild, fanstastic, and amazing ride with you, and heres to many more years and birthdays and poems and love messages and flowers and gifts and calls and kind words and kisses and smiles my baby <3 No one I'd rather do it with than you.

Now, what are you doing!! Go have fun!! Go party!! Even if partying means learning about your lungs!! You got this baby, this day is yours, the world is yours!!

Sending so so much love mi amor, te quiero,
Corbin Stone Diaz

<script>
function shootHearts() {
  for (let i = 0; i < 10; i++) {
    const heart = document.createElement("img");
    heart.src = "images/balloons.png";
    heart.className = "heart";

    // random position
    heart.style.left = (window.innerWidth / 2) + 1000*(Math.random() * 2 - 1) + "px";
    heart.style.top = (window.innerHeight / 2) + 1000*(Math.random() * 2 - 1) + "px";

    document.body.appendChild(heart);

    // remove after animation
    setTimeout(() => {
      heart.remove();
    }, 1500);
  }
}
</script>