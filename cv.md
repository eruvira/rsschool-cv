<img src="https://img.hhcdn.ru/photo/605981272.jpeg?t=1664359427&h=9_MNCK_E4fQfdfkpfi1d2A" width="200" />
---

# Elvira Darisheva
## Frontend Developer
***
## Contacts
- **phone**: +7 (707) 332 0968
- **telegram**: @eruvira
- **discord**: elvira(@eruvira)
***
## About me:
#### I graduated from the university with a degree in Information Security. While I was studying at the university, I realized that I like web development more. My first job was more related to layout and I wrote small scripts in js and Jquery. After that, I began to study Vue and moved to a new job. Now I want to fill in the gaps in my knowledge, since I learned most of the development myself and in the process.
***
## Skills:
- HTML, CSS, SCSS
- JavaScript
- Vue
- Nuxt, Pinia 
- Figma
- Git
- Linux

***
## Code example
**Valid Palindrome from Leetcode**
<br/>
A phrase is a palindrome if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters include letters and numbers.

Given a string s, return true if it is a palindrome, or false otherwise.

```JavaScript
var isPalindrome = function(s) {
    s = s.toLowerCase()
    s = s.replace(/[^a-z0-9]/g,'')
    for (let [i,j]=[0,s.length-1]; i<j;) {
        if (s[i]!=s[j]) {
            return false
        }
        i++
        j--
    }
    return true
};
```
