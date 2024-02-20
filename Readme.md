# JAVAScript lecture 3
## temes:Recursion and Closure

**1. Рекурсия-карочи ва я мадуд функсиаи хастаи ки да дрону хдш функсиа хдша фариод мукна.**
*Recursion is a process of calling a function from within itself. In JavaScript, a recursive function must have a condition to stop calling itself, otherwise, the function is called indefinitely. This is called a base condition. Here is an example of a recursive function in JavaScript that counts down from a given number to 1:*

![Recursion](https://i.ytimg.com/vi/NiQ8LP963hg/maxresdefault.jpg) хайкарочи ма амияаша фамидм руй рекурсии зардада икида далшиша бфахмен хдтон


**KArochi to mo limitsh namonem beskanichni kor kardan megira**
````javascript
 function factorial(num) {
     if(num==0) return 1
     return num * factorial(num-1)
    
 }
 console.log(factorial(500));
````
**cHIKHE ?**
![Изображение](https://bigbangpartnership.co.uk/wp-content/uploads/2017/10/4-1024x576.webp)
# карочи ай руи ами сурат мумкин камтар фахмен
![Изображение](https://vuejsdevelopers.com/images/posts/recursive_components.jpg "Логотип QUESTION")

# Closure
**а Closure боша да друни хдш я фнкцияи нав меcаза**

````javascript
function createAdder(num1) {
    return (num2) => {
        return num1+num2
    }
}

const adder = createAdder(5)
console.log(adder(3));
````
![Изображение](https://www.google.com/url?sa=i&url=https%3A%2F%2Fbigbangpartnership.co.uk%2Fthe-creative-power-of-questions%2F&psig=AOvVaw2EVPhXUsspHlBEb2xNqSFr&ust=1708510500103000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCNCn1d7XuYQDFQAAAAAdAAAAABAQ)
*A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function's scope from an inner function. In JavaScript, closures are created every time a function is created, at function creation time*

![Изображение](https://linuxhint.com/wp-content/uploads/2021/12/JavaScript-Function-closures-2.png   "Логотип QUESTION")

*Э хай карочи ма вакти холи надорм чизои аснавнойша фахмондм хдт бков бйов давомш интернетда pray*
*davay*
![Изображение](https://th.bing.com/th/id/OIP.lqU8M7MRsQKCnf-BHguy6AHaEK?rs=1&pid=ImgDetMain   "Логотип QUESTION")
