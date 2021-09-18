## RS-SCHOOL
# Anton Lucev
## Front-end Developer
## About me
I'm a 19 y.o. guy who wants to gain a foothold in the IT field.
I had experience in developing small desktop applications in C#.
I want to study web development from the inside and become a confident middle.

## Contacts
Email: 50we@mail.ru

## Skills
* HTML
* CSS
* JavaScript
* C#
* SQL
## Code example
```javascript              
                    function revrot(str, sz) 
                    {
                       ln = str.length;//длина строки
                       if(sz < 1 || !str || sz > ln) return "";
                    
                       const test = s => Array.prototype.reduce.call(s, (acc, val) => acc + Number(val) ** 3, 0) % 2 === 0;
                       const reverse = s => s.split("").reverse().join("");
                       const rotate = s => s.slice(1) + s.slice(0, 1);
                    
                       let arr = [];
                       for(let i = 0; i < ln; i += sz) arr.push(i+sz <= ln ? str.slice(i, i+sz) : "")
                       return arr.map(x => test(x) ? reverse(x) : rotate(x)).join("");
                    }
```            
            
## Education
* Course HTML & CSS (Andrey Andrievsky) on YouTube
* WEB Developer 2021 (Ivan Petrichenko) on Udemy
## English
A2+/B1