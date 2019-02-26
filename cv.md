# Maryna Petrenko
____________________
mobile: +375(33) 337-16-28

email: m.petrenko2807@gmail.com

[Linkedin](https://www.linkedin.com/in/марина-петренко-35985a73/)

______________________
# Summary 

I believe that I can be right person for your company, because I have basic skills, required for this job. This job is interesting for me because of its opportunity to keep the brain in tone, to see the results of the work, be useful for society by developing the best solutions. I want to improve my skills in web developing  and I also have a great desire to learn and ability to do it quickly.

____________
# Skills

- HTML
- CSS
- JavaScript
- Git
- Photoshop
_____________
# Code examples

1. Function, that takes one integer and returns true or false, depending on if the integer is prime.

```
function isPrime(num) {
  for(let i = 2; i < num; i++) {
    if(num % i === 0) {
      return false;
    }
  }
  return num > 1;
}
```
2. Tribonacci Sequence

```
function tribonacci(signature,n){
  let a = signature[0];
  let b = signature[1];
  let c = signature[2];
  n = Math.max(0,n);
  let res = [];
  res.push(a, b, c);
  if (n == 0) {
    res.splice(0,3);
  } else if (n > 0 && n < 3){
    res.splice(n, 3-n);
  }
  for (let i = 4; i <= n; i++) {
    if (n > 0) {
    var d = a + b + c;
    a = b;
    b = c;
    c = d;
    } 
    res.push(d);
  }
  return res;
}
```
_________________

# Experience

Small project while studying at Myfreedom.

Helped to rewrite the game from Java to JavaScript for Facebook games.
________________

# Education

Kherson State University (Kherson, Ukraine): 2007-2012

Faculty: English language 

IT-school Myfreedom (Minsk, Belarus) : January 2018 - April 2018

Course: Front-End Developer 
________________

# English level 
 
English level: B1. 

I learned English while sudying at University, now practice it on lingvaleo.com
