###### Resume
### Melnik Ilya  
## My contacts  
**+375(29)835-35-03** - preferred means of communication  
  iliamelnik@outlook.com - my outlook   
  [Facebook](https://www.facebook.com/profile.php?id=100006719685274)  
  [Linkedin](https://www.linkedin.com/in/ilya-melnik/)  
  Skype - live:iliamelnik  
## About me
I want to start a career Junior front-end developer in Epam and develop as a specialist. I strive for the continuous development of both my professional and personal qualities. I am sociable and try to be as involved as possible in the team work on one thing.  
## Skills and Technology   
* native JS;
* functional programming and OOP, SOLID;
* BEM,Bootstrap, Adaptive layout, LESS, SASS;
* basics Node.js, React.js;
* GIT;
* MySQL, MondoDB; 
## Code examples  
These are my mini-tasks from courses in Itransition: 
* Phyton Game "rpck-paper-scissors":
```
import random
import math
from array import array
import hashlib 
import hmac
import sys
import secrets
myArray =[]
if __name__ == "__main__":
    if(len(sys.argv)) > 3 and len(sys.argv) % 2==0:
        for param in sys.argv:
            myArray.append(param)
        del myArray[0]
    else : exit()
oppChoise = random.randint(1, len(myArray))

while True:
    for j in range(len(myArray)) :
        print(j + 1, ") ", myArray[j])
    print("0) Exit")
    key = secrets.token_bytes(64)
    myHmac = hmac.new(key, bytearray(myArray[oppChoise-1], 'utf-8'), hashlib.sha256) 
    print(myHmac.hexdigest())
    youChoise = int(input("Select number: "))
    if youChoise <= len(myArray) and youChoise >= 0 :
        break
    print("Сhoose the correct option")


if youChoise == 0 :
    exit()  


print("Your choice = ", myArray[youChoise-1], ".\n Opponents  choice= ", myArray[oppChoise-1], ".\n", "Secret key:", key.hex())
if oppChoise == youChoise :
    print("Draw")
elif (oppChoise - youChoise) % (len(myArray)) < len(myArray) / 2 :
    print("You have a win")
else :
    print("Opponent has a win")Начните карьеру младшего фронтенд-разработчика в Epam и развивайтесь как специалист
```
* JS task "code minimization":
```
t=process.argv.slice(2),s=t.reduce((a,b)=>a.length<=b.length?a:b),l=m=s.length;for(;l>0;l--)for(k=0;k<=m-l;k++){u=s.substr(k,l);if(t.every(e=>~e.indexOf(u))){l=0;break}u=''}console.log(u)
```
## Experience
**My projects**  
[Slider](http://wowslider.com/slider-js-utter-blinds-demo.html)  
[JavaScript calculator](https://codepen.io/giana/pen/GJMBEv)  
[SPA](https://meduza.io/)  
## Education
###### Higher education  
Belarusian State University of Informatics and Radioelectronics, Faculty of information technologies and control, Control Systems, Minsk   
Year of ending - 2021. 
Average score - 6.9.  
###### Courses: 
* **It-incubator**(May 2018 - August 2018)     
* **Streamline**(November 2018 - January 2019)   
* **Itransition**(November 2018 - January 2019)  
## Languages  
English — A2 — Elementary.  
German — B2 — Pre-intermediate.  
