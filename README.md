<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<p align= "center">Лабораторная работа №2</p><br><br><br><br><br><br><br><br>
<p align= "right">Выполнил: Андреев Д.В.</p><br><br><br><br><br><br><br><br>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p><br><br><br><br><br><br><br><br>
<h2 style="text-align: center">Введение</h2>
<p align="justify">JavaScript ("JS" для краткости) — это полноценный динамический язык программирования, который применяется к HTML документу, и может обеспечить динамическую интерактивность на веб-сайтах. Его разработал Brendan Eich, сооснователь проекта Mozilla, Mozilla Foundation и Mozilla Corporation. JavaScript сам по себе довольно компактный, но очень гибкий. Разработчиками написано большое количество инструментов поверх основного языка JavaScript, которые разблокируют огромное количество дополнительных функций с очень небольшим усилием. JavaScript невероятно универсален и дружелюбен к новичкам. Обладая большим опытом, вы сможете создавать игры, анимированную 2D и 3D графику, полномасштабные приложения с базами данных и многое другое!</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify"> <br>
<h2 align="center">Цели и задачи</h2>
1.Что выведет этот скрипт?

let name = "Ilya";

alert( `hello ${1}` ); // ?

alert( `hello ${"name"}` ); // ?

alert( `hello ${name}` ); // ?
<br>
2. Создайте страницу, которая спрашивает имя у пользователя и выводит его.
<br>
3.Чему будут равны переменные a, b, c и d в примере ниже?

let a = 1, b = 1;
let c = ++a; // ?
let d = b++; // ?
<br>
4. Чему будут равны переменные a и x после исполнения кода в примере ниже?

let a = 2;
let x = 1 + (a *= 2);
<br>
5. Какой результат будет у выражений ниже?

"" + 1 + 0
"" - 1 + 0
true + false
6 / "3"
"2" * "3"
4 + 5 + "px"
"$" + 4 + 5
"4" - 2
"4px" - 2
7 / 0
"  -9  " + 5
"  -9  " - 5
null + 1
undefined + 1
" \t \n" – 2
<br>
6. Ниже приведён код, который запрашивает у пользователя два числа и показывает их сумму. Он работает неправильно. Код в примере выводит 12 (для значения полей по умолчанию). В чём ошибка? Исправьте её. Результат должен быть 3.

let a = prompt("Первое число?", 1);
let b = prompt("Второе число?", 2);
alert(a + b); // 12
<br>
7.  Вывести на экран число Пи с точностью до сотых.
<br>
8. Составить программу вывода на экран числа, вводимого с клавиатуры. Выводимому числу должно предшествовать сообщение "Вы ввели число".
<br>
9. Составить программу вывода на экран числа, вводимого с клавиатуры. После выводимого числа должно следовать сообщение " - вот какое число Вы ввели".
<br>
10. Дана сторона квадрата. Найти его периметр.
<br>
11. Дан радиус окружности. Найти ее диаметр.
<br>
12. Считая, что Земля — идеальная сфера с радиусом
R 6350 км, определить расстояние до линии горизонта от точки с заданной высотой над Землей.
<br>
13. Дана длина ребра куба. Найти объем куба и площадь его боковой поверхности.
<br>
14. Дан радиус окружности. Найти длину окружности и площадь круга.
<br>
15. Поменять местами значения двух переменных без использования дополнительной переменной.
<br>
16. Даны два целых числа. Найти: а) их среднее арифметическое; б) их среднее геометрическое.
<br>
17. Известны объем и масса тела. Определить плотность материала этого тела. 
<br>
18. Известны количество жителей в государстве и площадь его территории. Определить плотность населения в этом государстве.
<br>
19. Даны катеты прямоугольного треугольника. Найти его гипотенузу. 
<br>
20. Найти площадь кольца по заданным внешнему и внутреннему радиусам.
<br>
21. Даны катеты прямоугольного треугольника. Найти его периметр. 
<br>
22. Даны основания и высота равнобедренной трапеции. Найти ее периметр.


    <br>
 <h2>Задание 1</h2>
  <p><script>
    let name = "Ilya";
document.writeln( `hello ${1}`+ "<br>" ); // hello 1
document.writeln( `hello ${"name"}` + "<br>"); // hello name
document.writeln( `hello ${name}`+ "<br>" ); // hello Ilya
</script></p>


<h2>Задание 2</h2>
  <p> <script>
    let names = prompt("Ваше имя?", "");
    document.writeln(names);
  </script></p>



<h2>Задание 3</h2>
  <p> <script>
    let a = 1, b = 1;
let c = ++a; 
let d = b++; 
document.writeln(a+","+b+","+c+","+d);
  </script></p>

<h2>Задание 4</h2>
<p> <script>
let aa = 2;
let x = 1 + (aa *= 2);
document.writeln(aa+","+x);
</script></p>


<h2>Задание 5</h2>
<p> <script>
document.writeln("" + 1 + 0)
document.writeln("" - 1 + 0)
document.writeln(true + false)
document.writeln(6 / "3")
document.writeln("2" * "3")
document.writeln(4 + 5 + "px")
document.writeln("$" + 4 + 5)
document.writeln("4" - 2)
document.writeln("4px" - 2)
document.writeln(7 / 0)
document.writeln("  -9  " + 5)
document.writeln("  -9  " - 5)
document.writeln(null + 1)
document.writeln(undefined + 1)
document.writeln(" \t \n" - 2)
</script></p>

<h2>Задание 6</h2>
<p> <script>
let aaa = ("Первое число?", 1);
let bbb = ("Второе число?", 2);
document.writeln(aaa + bbb);
</script></p>


<h2>Задание 7</h2>
<p> <script>
var pi = Math.PI.toFixed(2);
document.writeln(pi); 
</script></p>


<h2>Задание 8</h2>
<p> <script>
var number = ("Введите число:",2); //prompt("Введите число:");
document.writeln("Вы ввели число: " + number);
</script></p>

<h2>Задание 9</h2>
<p> <script>
var numbers = ("Введите число:",32);
document.writeln("- вот какое число Вы ввели: " + numbers);
</script></p>

<h2>Задание 10</h2>
<p> <script>
var hislo = ("сторона квадрата:",3);
document.writeln("периметр:"+hislo*4);
</script></p>

<h2>Задание 11</h2>
<p> <script>
var hisslo = ("сторона квадрата:",3);
document.writeln("диаметр:"+hisslo*2);
</script></p>

<h2>Задание 12</h2>
<p> <script>
let radius = 6350; // радиус Земли в километрах
let height = 10; // высота над Землей в километрах
let rast = Math.sqrt((2 * radius * height) + (height * height));
document.writeln("Расстояние до линии горизонта:", rast, "километров");
</script></p>

<h2>Задание 13</h2>
<p> <script>
function vihislitCube(length) {
  let obiem = length ** 3; // объем куба
  let ploshad = 6 * (length ** 2); // площадь его боковой поверхности
  return {
    obiem: obiem,
    ploshad: ploshad
  };
}
let length = 5; // длина ребра куба
let cube = vihislitCube(length);
document.writeln("Объем куба:", cube.obiem);
document.writeln("Площадь его боковой поверхности:", cube.ploshad);
</script></p>

<h2>Задание 14</h2>
<p> <script>

let rradius = ("Введите радиус окружности:", 3);

// длина окружностb
let dlina = 2 * Math.PI * rradius;

// Вычисление площади круга
let area = Math.PI * Math.pow(rradius, 2);

// Вывод результатов
document.writeln("Длина окружности:", dlina.toFixed(2));
document.writeln("Площадь круга:", area.toFixed(2));
</script></p>


<h2>Задание 15</h2>
<p> <script>
var hislo1 = ("Число 1",4);
    var hislo2 = (" 2 число",33);
    hislo1 = hislo1+hislo2;
    hislo2 = hislo1-hislo2;
    hislo1 = hislo1-hislo2;
  document.writeln(hislo1,hislo2)
</script></p>

<h2>Задание 16</h2>
<p> <script>
let hisslo1 = ("Число 1",4);
let hisslo2 = (" 2 число",33);
  let  sa=(hisslo1*hisslo1+hisslo2*hisslo2)/2; //среднее арифметич 
  let  sg=Math.sqrt(Math.abs(hisslo1)*Math.abs(hisslo2)); //средн. геометрич
  document.writeln("среднее арифметич"+sa+"<br>"+"среднее геометр"+sg)
</script></p>

<h2>Задание 17</h2>
<p> <script>
let obem = ("Введите объем тела:",10);
let mass = ("Введите массу тела:",4);
// плотности 
let density = mass / obem;
document.writeln("Плотность материала тела: " + density);
</script></p>


<h2>Задание 18</h2>
<p> <script>
// Функция для определения плотности населения
function populacia(population, ploshadi) {
return population / ploshadi;
}

let population = 100; // количество жителей
let ploshadi = 5; // площадь
let hh = populacia(population, ploshadi);
document.writeln("Плотность населения составляет  " + hh  + "чел/км²");
</script></p>


<h2>Задание 19</h2>
<p> <script>
let cathetus1 = ("Введите длину первого катета: ",3);
let cathetus2 = ("Введите длину второго катета: ",6);
//  гипотенузf
let hypotenuse = Math.sqrt(cathetus1 ** 2 + cathetus2 ** 2);
document.writeln("Гипотенуза треугольника равна " + hypotenuse);
</script></p>


<h2>Задание 20</h2>
<p> <script>
function calculateRingArea(vnehRadius, vnutrRadius) {


  //  площади кругов
  let vneshPloshad = Math.PI * Math.pow(vnehRadius, 2);
 let vnutrPoshad = Math.PI * Math.pow(vnutrRadius, 2);

  //  площадь кольца
  let ploshadcolca = vneshPloshad - vnutrPoshad;

  return ploshadcolca;
}
let vnehRadius = 8;
let vnutrRadius = 5;
let zz = calculateRingArea(vnehRadius, vnutrRadius)
document.writeln('Площадь кольца:', zz);
</script></p>


<h2>Задание 21</h2>
<p> <script>
    function findPerimeter(cathet1, cathet2) {
//  гипотенузу 
let hypotenus = Math.sqrt(cathetus1 ** 2 + cathetus2 ** 2);

// периметр
let perimeter = cathet1 + cathet2 + hypotenus;
return perimeter;
    }
let cathet1 = 31; 
let cathet2 = 4; 

let j = findPerimeter(cathet1, cathet2);
document.writeln("Периметр треугольника:", j);
</script></p>


<h2>Задание 22</h2>
<p> <script>
  function calculatePerimeter(osn1, osn2, visota) {
  //  сторона боковой стороны трапеции
  let X = Math.sqrt(Math.pow((osn1 - osn2) / 2, 2) + Math.pow(visota, 2));
  //  периметр трапеции
  let perimeter = osn1 + osn2 + (2 * X);
  
  return perimeter;
}
let osn1 = 10; //  основания
let osn2 = 8; //  основания
let visota = 5; // высота
let result = calculatePerimeter(osn1, osn2, visota);
document.writeln("Периметр равнобедренной трапеции:", result);

</script></p>


 <div class="heading">
 
</div>


   <h2 style="text-align: center">ВЫВОД</h2>
  JavaScript – это язык программирования, который добавляет интерактивность на ваш веб-сайт (например: игры, отклик при нажатии кнопок или при вводе данных в формы, динамические стили, анимация). Эта статья поможет вам начать работать с этим захватывающим языком и даст вам представление о том, на что он способен.

Хотя PHP, главным образом, предназначен для работы в среде веб-серверов, область его применения не ограничивается только этим. Читайте дальше и не пропустите главу Возможности PHP либо, начните непосредственно с Вводного руководства, если вас интересует исключительно веб-программирование.
