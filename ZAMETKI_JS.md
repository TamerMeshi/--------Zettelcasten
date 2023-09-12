# МАССИВЫ И ИХ МЕТОДЫ
const cars = ['bmw','mercedes', 'lada']

console.log(cars)

console.log(cars[0]) //index первой машины т.е. BMW

cars[0]= 'ford'

console.log(cars)

## [[переприсваивание индекса в массиве]]

cars[3]= 'BMW' // создали еще один масcив добавили индекс 3

console.log(cars)

cars[cars.length] = 'mazda'
console.log(cars)

## [[добавление элементов]]


/ let c = ['anna',1,1,31]

  

// let man = ['ivan','male',34,178,'ivanov']

  

// let a = [1,2,3,4] // переставить 4,2,3,1

// let t = a[0]

// a[0] = a[a.length -1]

// a[a.length -1] = t

// console.log(a)

 [[перестановка элементов в массиве]] 

// for( let i = 0; i<a.length; i++){

// document.querySelector('.out-1').innerHTML += a[i]; 

// }

## [[вывод массива на экран]]

// let out = ''

// for(let i = 0; i<a.length; i++){

// if(a[i]% 2 === 0){

// out+= a[i] +' _' // ВЫВОД НА ЭКРАН 4 _2 см. let a =, // ВАЖНО метода push нету так как out это строчная переменная

// }

// }

// document.querySelector('.out-1').innerHTML = out; // вывели строку массив в строку через out,

  
  
  

// let b = [4,8,5,55,10,14,44,23]// 

// let max = b[0]//4

// for(let i = 0; i<b.length; i++){ // пробежали по массиву измерив длину -length а также перебирая числа [i]

// if(b[i]>max){ // берем то что в [b] и пока то что в ней больше чем в max =4,

// max= b[i] //

// }

// }

// console.log('max: '+max)

## [[ВЫВОД МАКСИМАЛЬНОГО ЧИСЛА]]
  
  
// let b = [4,8,5,55,10,14,44,23]// 
// let sum= 0

// for(let i = 0; i<b.length; i++){

// sum+= b[i] // 

// }

// console.log('sum: '+sum)//

  
  [[складываем сумму в массиве ]]



  

// let a = [

// [1,2,3],

// [4,5,6],

// [7,8,9]

// ]

// let out = ''

// for(let i = 0; i<a.length; i++){

  

// for(let p=0; p<a[i].length;p++){

// out += a[i][p]+' ' //

// console.log(a[i][p])

// }

// }

  

// out = ''

// for(let i = 0; i<a.length; i++){

// for(let p=0; p<a[i].length;p++){

// if(a[i][p]>4){

// out += a[i][p]+' '

// }

// }

// // out+= '<br>'

  

// // }

   ## [[ДВУМЕРНЫЙ МАССИВ]]

// let a = [1,0,0,0,0] //перебор еденицы в конец

// document.querySelector('.out-1').innerHTML = a

// let k = 0

// document.querySelector('button').onclick = ()=>{

// if(k+1<5){

// a[k] = 0

// a[k+1] = 1

// k++

// }

// document.querySelector('.out-1').innerHTML = a

// }
## [[ПЕРЕБОР ЦИФРЫ в конец с помощью кнопки ]]