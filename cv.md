
+ 1: Sergey Suleimanov

---

+ 2: Contacts:
   + Phone: +7 (775) 945-35-37
   + Email: ssuleimanov.94@gmail.com
   
---

+ 3: The goal is to become competitively capable to work in frontend development, creating a product that will be
 useful for people and in demand among employers. Strengths: I like working in teams with experts, learning and
 sharing knowledge. I realize that my knowledge is not enough and strive to get more information about the topic I
 am interested in. Until I get it, I compensate with diligence) I take criticism of my work calmly.
 Experience: prior to this course, was self-trained in website layout, as well as studied the methodology of BEM, studied the basic skills of working with JS.

---

+ 4: HTML5, CSS3, JavaScript, BEM

---

+ 5 :
```javascript
   'use strict';
   
   (function (){
       
       window.addPins = function () {
   
           if (MAP_PINS.querySelectorAll('.map__pin--item').length > 1) {
               [].forEach.call(MAP_PINS.querySelectorAll('.map__pin--item'), function (i) {
                   i.parentNode.removeChild(i);
               })
           }
   
           const PINS_ITEM_BUTTON = document.querySelector('#pin').content.querySelector('button');
   
           for (let i = 1; i <= 8; i++) {
               let newPin = PINS_ITEM_BUTTON.cloneNode(true)
               fragment.appendChild(newPin)
               MAP_PINS.appendChild(fragment)
               newPin.classList.add('map__pin--item')
               newPin.style = 'left:' + UTILS.offer.location.x() + 'px; top:' + UTILS.offer.location.y() + 'px';
               newPin.querySelector("img").src = UTILS.author.avatar(i);
               newPin.querySelector("img").alt = UTILS.offer.title();
           }
       }
   }())
```
---

+ 6: 

---

+ 7: Html Academy Professional Online Course HTML and CSS, Level 1,2.


+ 8: Beginner.

