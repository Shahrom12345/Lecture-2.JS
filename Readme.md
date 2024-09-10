# Что такое Sample и Loop?
### Что делать, если мне понадобился, например, звук колокольчика? 
### Если у меня есть определенный навык, то я могу попытаться имитировать этот звук на синтезаторе.
### Он может быть похожим на настоящий, но всё равно будет далёк от идеала. 
### В таком случае, нет ничего лучше, чем записанный звук реального колокольчика.
 ### Такой записанный звук называется сэмпл (sample - "фрагмент").
---
* Ресемплинг (Resample). При таком типе воспроизведения, высота звука будет изменяться за счет изменения скорости воспроизведения сэмпла.
* Стретчинг (Stretch). Это переводится как "растягиваться", но здесь всё совсем наоборот. 
---
# Функция
### Функция — это блок из различных команд. С ней легко создавать порядок в коде программы, избавляясь от ненужных повторений и запутанных частей.

## Обычно имя функции пишут стилем camelCase и используют в начале глагол. Например
1. createBearCounter
2. getBearCalculator
3. sendBearPolice
---
### В JavaScript есть два типа функций по признаку имени. В примере ниже функция называется именованной, потому что у неё есть имя.
### const numberFour = 4

### function five() {
  ### const numberFive = numberFour + 1
  ### return numberFive
### }

### console.log(numberFour)
### // 4
### console.log(five())
### // 5
### console.log(numberFive)
### // numberFive is not defined
---
# condition
## the particular state that something or someone is in:
* Mum's still got our pram - it's very old, but it's in perfect condition.
* They left the flat in a terrible condition - there was mess everywhere.
* The hospital say her condition (= state of health) is improving slowly.
* He's in no condition (= he is too sick or too drunk) to drive home.
---
## the situation that someone lives or works in, or that someone or something is affected by:
* The unions are trying hard to improve pay and conditions for their members.
* business/economic/market conditions The timing of the merger depended on market conditions.
* difficult/favourable conditions This year has seen some very difficult trading conditions.
* in/under good, poor, etc. conditions Many of the goods are produced by child workers working in appalling conditions.
* working/living conditions
---
# There are 3 ways of creating a function in JavaScript
1. Function Declaration
2. Function Expression
3 (IIFE) Immediately Invoked Function Expression
( Arrow - function , Anonymous - function )
3. (IIFE) Immediately Invoked Function Expression
---
# Function Declaration
### Классическое» объявление функции, о котором мы говорили до этого, вида function имя(параметры) {...}, называется в спецификации языка «Function Declaration».
* Function Declaration – функция, объявленная в основном потоке кода.
* Function Expression – объявление функции в контексте какого-либо выражения, например присваивания.
### Несмотря на немного разный вид, по сути две эти записи делают одно и то же:

![alt text](<Снимок экрана 2024-09-10 095014-1.png>)
---
# Function Expression
### The function keyword can be used to define a function inside an expression.
### You can also define functions using the function declaration or the arrow syntax.
### Function expressions in JavaScript are not hoisted, unlike function declarations. You can't use function expressions before you create them:
---
# Syntax
![alt text](<Снимок экрана 2024-09-10 095553.png>)
### Note: An expression statement cannot begin with the keyword function to avoid ambiguity with a function declaration
### The function keyword only begins an expression when it appears in a context that cannot accept statements.
---

# Description
### A function expression is very similar to, and has almost the same syntax as, a function declaration.
### The main difference between a function expression and a function declaration is the function name, which can be omitted in function expressions to create anonymous functions.
### A function expression can be used as an IIFE (Immediately Invoked Function Expression) which runs as soon as it is defined
### See also the chapter about functions for more information.
---
# IIFE
### IIFE (Immediately Invoked Function Expression) это JavaScript функция, которая выполняется сразу же после того, как она была определена.
### Это тип выражений, также известный как Self-Executing Anonymous Function, который состоит из двух основных частей.
### Первая - это сама анонимная функция с лексической областью видимости, заключённым внутри Оператора группировки ().
### Благодаря этому переменные IIFE замыкаются в его пределах, и глобальная область видимости ими не засоряется.

### Вторая часть создаёт мгновенно выполняющееся функциональное выражение () , благодаря которому JavaScript-движок выполняет функцию напрямую.
---
# Примеры
### Функция становится мгновенно выполняющимся функциональным выражением.
### Переменные внутри функции не могут быть использованы за пределами её области видимости.
![alt text](<Снимок экрана 2024-09-10 100326-1.png>)
### Переменная, которой присвоено IIFE, хранит в себе результат выполнения функции, но не саму функцию.
![alt text](<Снимок экрана 2024-09-10 100454-1.png>)
---
# Узнать больше
### Материалы
* Ben Alman's blog post defining IIFEs
* Quick example (в конце абзаца "Functions", сразу после "Custom objects")
---
![alt text](AIM-Blog-Why-Thank-You-Matters-More-Than-Money-New-1.jpg)