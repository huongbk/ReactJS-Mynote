# JavaScript

---

- File tóm tắt một số cú pháp cơ bản của JavaScript, dựa trên playlist JavaScript trên trang [CodeX](https://www.youtube.com/c/CodersX/playlists). Anh tác giả của course giảng khá chậm và kỹ nên để  ```speed x1.5``` học sẽ hợp lý hơn.

---

Bài 0 - Chuẩn bị đồ nghề

---

- IDE,...

---

Bài 1. Thuật ngữ (terms) là gì?

---

- TERM: Thuật ngữ là những từ ngữ biểu thị khái niệm khoa học và công nghệ thường được sử dụng trong các văn bản khoa học, công nghệ. Và điều đặc biệt thuật ngữ khác với từ ngữ phổ thông mỗi một thuật ngữ đều sử dụng trong từng lĩnh vực với từng biểu thị một khái niệm khác nhau.
- Biến, Mảng, Kiểu dữ liệu, Hàm,...

---

Bài 2 - Nội dung khoá học lập trình miễn phí Coders.Tokyo

---

- Tổng quan: Frontend & BackEnd
  - Cơ bản: JS + HTML + CSS
  - Nâng cao: JS + CSS
  - CSS Framework: Material + Bootstrap_4 + Other
- Frontend framework:
  - Reactjs --> chuyển sang React Native easy! | Facebook
  - Angular | Google
  - VueJS | Evan you
- Backend framework:
  - ExpressJS - NodeJS
  - Lavavel - PHP
  - Spring - Java
- Other:
  - Git
  - UI Design
  - Apache
  - Docker
  - AWS
  - Heroku
  - Deployment
  - ect.
- Why JS:
  - Nhiều người dùng
  - JS làm được rất nhiều thứ, có thể làm tất nhứ Web, App, Mobile, Server, etc.

---

Bài 3 - Biến (Variable)

---

- Program
  - Ram - CPU - Screen
  - Khai báo biến bằng các quy tắc, keywords: Lưu tạm vào Ram
- Var, Let, Const [tham khảo](https://viblo.asia/p/phan-biet-kieu-bien-var-let-va-const-trong-javascript-ORNZqaOnZ0n)

---

Bài 4. Kiểu dữ liệu (Phần 1)

---

- Null: Null có nghĩa là giá trị rỗng hoặc giá trị không tồn tại, nó có thể được sử dụng để gán cho một biến như là một đại diện không có giá trị.
- Undefined: Undefined có nghĩa là không xác định. Trong javascript, khi bạn khai báo một biến nhưng chưa gán giá trị cho nó, giá trị của biến đó sẽ là undefined.
  var test = undefined;

  - typeof undefined           // undefined
  - typeof null                // object
  
- array
- object

- escape a character: 'Hello, I\'m HuongBK.'

---

Bài 5 - Object trong JavaScript

---

- Khai báo:

    ```javascript
    var ObjectName = {
    key : value
    };

    var myDog = {
    name : 'Dog',
    weight: 5.2,
    isAlive: true
    };
    ```

- Rule: camelCase
  - ex: myBestFriend

- Thay đổi các thuộc tính:

    ```javascript
    console.log(myDog);
    console.log(myDog.weight);
    myDog.weight = 10;
    console.log(myDog.weight);
    ```

- other:

    ```javascript
    myDog.name == myDog['name']
    myDog.isAlive == myDog['isAlive']
    <!-- tương tự như Dictionary trong python -->
    ```

---

Bài 6 - Mảng trong JavaScript (Array)

---

- Array - Element - Index - Length
- Khai báo:

    ```javascript
    var arrName = [1, 2, 3, 5, 'emCoDanhRoiNhipNaoKhong'];
    ```

- Index bắt đầu từ 0
- Mảng arrName có 5 phần tử

- Object bên trong mảng:

    ```javascript
    var dogOne = {
    name = 'cho ta',
    weight = 6.9
    };

    var dogTwo = {
    name = 'cho tay',
    weight = 10.5
    };

    var dogThree = {
    name = 'cho bec de',
    weight = 8.5
    };

    var commonDog = [dogOne, dogTwo, dogThree];
    console.log(commonDog[2]);
    console.log(commonDog[2].name);
    ```

- Thay đổi object trong array:

    ```javascript
    var dogFour = {
    name = 'Husky',
    weight = 4
    };

    commonDog[0] = dogFour;
    console.log(commonDog);
    ```

- In JavaScript, array is a single variable that is used to store different elements. It is often used when we want to store list of elements and access them by a single variable.

    ```javascript
    var myContracts = [
    {  
        name = 'huongBk',
        age = 23
    },
    {  
        name = 'huongNeu',
        age = 24
    },
    {  
        name = 'huongFtu',
        age = 25
    }
    ];
    ```

---

Bài 8 - Các phép tính tăng giảm (++, --)

---

```jsx
++
--
*
/
%
+-
```

```jsx
var a = 5;
a++; 
-------> trả về giá trị trước khi tăng
++a;
-------> tăng luôn và trả về giá trị sau khi tăng
var a = 5;
a++ + ++a;   // ra 12 chứ không phải 11 nhé!
// 5 + ++a; // thời điểm này a = 6
// 5 + 7
// 12

var a = 5;
a++ + ++a - --a + a--;   // output: 12
// 5 + ++a - --a + a--;  // a = 6
// 5 + 7 - --a + a--;    // a = 7
// 5 + 7 - 6 + a--;      // a = 6
// 5 + 7 - 6 + 6;        // a = 5
// 12

var a = 5;
var b = 10;

a++ * b-- + --a * ++b; // output: 100
5 * 10 + --a * ++b;   // a = 6, b = 9
5 * 10 + 5 * 10;   // a = 5, b = 10
// 100
```

---

Bài 7 - Arithmetic operators

---

```jsx
  *  - nhân bình thường
  /  - chia bình thường
  %  - chia lấy phần dư
  +- - cộng trừ bình thường

- Thực hiện từ trái sang phải
- Nhân chia trước, cộng trừ sau
```

---

Bài 9 - Assignment operators

---

```jsx
  =
  +=
  -=
  *=
  /=
```

---

Bài 10 - Function trong JavaScript

---

```jsx
function calculatorDiscSquare(r) {
    output = r * r * 3.14;
    return output;
}
```

---

Bài 11 - Object methods

---

- Phương thức trong Object hay còn gọi là methods
- Khi hàm trong Object thì hiểu là phương thức
- Anonymous function: hàm k truyền tham số

    ```jsx
    var myDog = {
    name : 'Dogger',
    age : 3,
    weight : 5.
    color: 'yellow',
    sound : function() {
        console.log('gau gau gau');
        console.log('Dog\'s name is', this.name);
    },
    eat : function(cc) {
        this.weight += cc.weight;
        return this;
    }
    };

    myDog.sound();
    var cc = { weight : 0.4 };
    console.log(myDog.weight);
    myDog.eat(cc);
    console.log(myDog.weight);
    ```

- ```this``` trong method đại diện cho chính cái Object luôn nhé
- ```biến``` chưa gán thì in ra ```undefine```

    ```jsx
    const person = {
    firstName: "John",
    lastName: "Doe",
    id: 5566,
    fullName: function() {
        return this.firstName + " " + this.lastName;
    }
    };
    ```

---

Bài 12 - Comparison operators

---

```jsx
  >
  <
  >=
  <=
  ===
  !==
  == 
  !=
```

- What is == in JavaScript?
  - Double equals (==) is a comparison operator, which transforms the operands having the same type before comparison.
  - So, when you compare string with a number, JavaScript converts any string to a number. An empty string is always converts to zero. A string with no numeric value is converts to NaN (Not a Number), which returns false.

- What is === in JavaScript?
  - === (Triple equals) is a strict equality comparison operator in JavaScript, which returns false for the values which are not of a similar type. This operator performs type casting for equality. If we compare 2 with “2” using ===, then it will return a false value.

- Why use == in JavaScript?
  - The == operator is an equality operator. It checks whether its two operands are the same or not by changing expression from one data type to others. You can use == operator in order to compare the identity of two operands even though, they are not of a similar type.

- How === Works Exactly?  
  - Strict equality === checks that two values are the same or not.
  - Value are not implicitly converted to some other value before comparison.
  - If the variable values are of different types, then the values are considered as unequal.
  - If the variable are of the same type, are not numeric, and have the same value, they are considered as equal.
  - Lastly, If both variable values are numbers, they are considered equal if both are not NaN (Not a Number) and are the same value.

```jsx
var a = 10 !== 100;
a;
// a = true
```

---

Bài 13 - Vòng lặp for

---

```jsx
  for(init; condition; final-expression){
    statements;
  }
  exit(if condition is false)
```

- ex:

    ```jsx
    for (var i = 0; i < 10; i++) {
    console.log(i);
    }
    ```

- ex:

    ```jsx
    var employees = [
    {  
        name : 'huong',
        age : 23
    },
    {  
        name : 'luong',
        age : 24
    },
    {  
        name : 'van',
        age : 25
    }
    ];

    for (i = 0; i < 3; i++) {
    console.log(employees[i].name);
    }
    ```

---

Bài 14 - for ... of, for ... in

---

- ```for...of``` ví dụ:

    ```jsx
    var employees = [
    {  
        name : 'huong',
        age : 23
    },
    {  
        name : 'luong',
        age : 24
    },
    {  
        name : 'van',
        age : 25
    }
    ];

    for (var index of employees) {
        console.log(index.name, index.age);
    }
    ```

- ```for...in``` ví dụ:

    ```jsx
    var myDogs = {
    name : 'bec de',
    age : 4,
    weight : 12  
    };

    for (var key of myDogs) {
    console.log(key, myDogs[key]);
    }
    ```

---

Bài 15 - Array methods

---

```jsx
var a = [...];
var b = [...];

  a.concat(b);
  
  a.push(b);
  a.pop();
  
  a.shift();
  a.unshift();
  
  a.slice
  a.splice
  ... xem trên docs nhiều lắm...
```

- ```toString()```  : Chuyển một mảng về dạng chuỗi ký tự.
- ```push()```  :  Thêm một phần tử mới vào vị trí cuối mảng, trả về độ dài của mảng mới
- ```pop()``` : Xóa phần tử nằm ở vị trí cuối mảng, trả về độ dài của mảng mới
- ```unshift()```  : Thêm một phần tử mới vào vị trí đầu mảng, trả về độ dài mới của mảng
- ```shift() ```:  Xóa phần tử nằm ở vị trí đầu mảng, trả về giá trị bị đẩy ra
- ```concat()``` :  Ghép các mảng con lại với nhau rồi trả về một mảng mới.
- ```slice()``` :  Trích xuất một phần của mảng ban đầu rồi trả về một mảng mới.
- ```splice()``` :  Thêm hoặc xóa "một hoặc nhiều phần tử" ở vị trí bất kỳ trong mảng.
- ```length``` : Trả về số lượng phần tử của mảng.

<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array>

---

Bài 16 - Dùng function như tham số ()

---

- Truyền hàm vào Method
- Ex:

    ```jsx
    var machineCoffee = {
    name : "machine",
    makeCoffee : maker(callbackFunction) {
        console.log('make a coffee...');
        callbackFunction();
    }
    }

    function otherFunction() {
    console.log('output of callback function');
    }

    machineCoffee.makeCoffee(otherFunction);
    ```

---

Bài 17 - array.map dùng như thế nào

---

```jsx
const array1 = [1, 4, 9, 16];

// pass a function to map
const map1 = array1.map(x => x ** 2);

console.log(map1);
// expected output: Array [2, 8, 18, 32]

// mấy cái này lên thẳng docs đọc cho sướng
```

---

Bài 18 - array.filter dùng để làm gì?

---

```jsx
const words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];

const result = words.filter(word => word.length > 6);

console.log(result);

// expected output: Array ["exuberant", "destruction", "present"]
```

---

Bài 19 - array.find hoạt động ra sao?

---

- The value of the first element in the array that satisfies the provided testing function. Otherwise, undefined is returned.

```jsx
const array1 = [5, 12, 8, 130, 44];

const found = array1.find(element => element > 10);

console.log(found);
// expected output: 12
```

---

Bài 20 - array.reduce tưởng khó mà dễ

---

```jsx
var number = [1, 2, 3 , 4]
number.reduce(function(a, b) { return a + b })
// 1 2 3 4
//   3 3 4
//     6 4 
//       10
```

```jsx
const array1 = [1, 2, 3, 4];
const reducer = (previousValue, currentValue) => previousValue + currentValue;

// 1 + 2 + 3 + 4
console.log(array1.reduce(reducer));
// expected output: 10

// 5 + 1 + 2 + 3 + 4
console.log(array1.reduce(reducer, 5));
// expected output: 15

const array1 = [1, 2, 3, 4];
console.log(array1.reduce((a, b) => a * b, 10));  // init = 10, tính với thằng đầu tiên trước
// expected output: 240
```

---

Bài 21 - Ứng dụng array methods trong thực tế

---

- Combine with HTML

---

Bài 22 - Reduce phần 2

---

- thêm cái init

```jsx
array.reduce(() => a + b, init)
```

---

Bài 23 - Sort an array

---

- Xem docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort>

```jsx
compareFunction(a, b) return value  sort order
  > 0    sort b before a
  < 0    sort a before b
  === 0  keep original order of a and b
```

```jsx
// the array to be sorted
const data = ['delta', 'alpha', 'charlie', 'bravo'];

// temporary array holds objects with position and sort-value
const mapped = data.map((v, i) => {
  return { i, value: someSlowOperation(v) };
})

// sorting the mapped array containing the reduced values
mapped.sort((a, b) => {
  if (a.value > b.value) {
    return 1;
  }
  if (a.value < b.value) {
    return -1;
  }
  return 0;
});

const result = mapped.map(v => data[v.i]);
```

---

Tạo sao mình dạy JavaScript?

---

```text
JS basic
JS advanced
CSS
HTML
Bootstrap
NodeJS
ReactJS
--
ExpressJS
Git
Deployment tools
```

---

Bài 24 - Math object

---

```text
  Math.PI
  Math.ceil()
  Math.floor()
  Math.round()
  Math.max()
  Math.min()
  Math.random()
```

<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math>

---

Bài 25 - The `new` keyword

---

```jsx
function Car(make, model, year) {
  this.make = make;
  this.model = model;
  this.year = year;
}

const car1 = new Car('Eagle', 'Talon TSi', 1993);

console.log(car1.make);
// expected output: "Eagle"
```

- Syntax
  - new constructor[([arguments])]

- Parameters
  - Constructor
    - A class or function that specifies the type of the object instance.

  - Arguments
    - A list of values that the constructor will be called with.

- Constructor function
  - Constructor: A constructor is a function that initializes an object.
  - In JavaScript the constructors are more similar to normal java constructor.
  - Object constructor: In JavaScript, there is a special constructor function known as Object() is used to create and initialize an object.

  ```jsx
  var mouse = {                        
    weight : 0.2,
    getWeight : function() {
      return this.weight;
    }
  };

  function Mouse() {           // constructor function Mouse()
    this.type = 'mouse';
  }

  var mouse1 = new Mouse();
  var mouse2 = { type : 'mouse' };
  var mouse3 = new Mouse();
  ```

- Method chaining

  ```jsx
  var tom = {
    name : 'Tom',
    stomach : [],
    eating : function (mouse) {
      this.stomach.push(mouse);
      return this;
    }
  };

  var mouse = {
    weigh : 2.3
  };

  function Mouse(name) {
    this.type = 'mouse',
    this.name = name
  }

  m1 = new Mouse('m1');
  m2 = new Mouse('m2');
  m3 = new Mouse('m3');

  tom.eating(m1).eating(m2).eating(m3);
  ```

---

Bài 26 - Prototypes in JavaScript

---

- Prototypes
  - Khuôn mẫu được chia sẻ giữa các Object được tạo ra bằng từ khóa New, tránh việc khởi tạo lại method nhiều lần
  - Prototypes giúp tiết kiệm bộ nhớ hơn

- Best practice

  ```jsx
  function Person(first, last, age, eyecolor) {
    this.firstName = first;
    this.lastName = last;
    this.age = age;
    this.eyeColor = eyecolor;
  }

  Person.prototype.nationality = "English";
  ```

  ```jsx
  function Person(first, last, age, eyecolor) {
    this.firstName = first;
    this.lastName = last;
    this.age = age;
    this.eyeColor = eyecolor;
  }

  Person.prototype.name = function() {
    return this.firstName + " " + this.lastName;
  };
  ```

  ```jsx
  var mouse = {
    weight : 3.5,
    getWeight: () => this.weight;
  };

  function Mouse(color, weight) {
    this.type = 'mouse';
    this.color = color;
    this.weight = weight;
  }

  Mouse.prototype.sleep = function=() {
    console.log(this.color + ' ' + 'Sleeping...');
  };

  var jerry = new Mouse('black', 23);
  var mickey = new Mouse('white', 12);
  jerry.sleep();
  mickey.sleep();
  ```

---

Bài 27 - Cài đặt NodeJS + Sublime Text trên Windows

---

- Bỏ qua

---

Bài 28 - Install Node.js on Mac

---

- Bỏ qua, chưa có tiền mua Mac

---

Bài 29 - Node module system

---

- Dùng node module
- Chia nhỏ file to thành nhiều file cho dễ quản lý, làm nhiều sẽ quen

```jsx
// ./mouse.js
function Mouse(color) {
  this.color = color;
  this.dead = false;
}

Mouse.prototype.die = function() {
  this.dead = true;
};

module.export = Mouse;
```

```jsx
// ./cat.js
function Cat() {
  this.stomach = [];
};

Cat.prototype.eat = function(mouse) {
  this.stomach.push(mouse);
  mouse.die();
};

module.export = Cat;
```

```jsx
// ./index.js
var Mouse = require('./mouse');
var Cat = require('./cat');

var jerry = new Mouse('black');
var mickey = new Mouse('red');

console.log(jerry);
console.log(mickey);

var tom = new Cat();
tom.eat(mickey).eat(jerry);

console.log(tom);
```

```bash
# terminal:
  => node index.js
```

---

Bài 30 - Node build-in modules

---

- Dùng build-in modules trong nodejs, cứ đọc và dùng thôi

---

Bài 31 - npm (Node Package Manager)

---

- node -v
- npm -v

```bash
=> npm init
  => enter...
    => yes...enter...

=> package.json

  => npm install name-module --save  (--save để nó lưu lại vào file package!!)

- Dùng bằng => require('name-module');

=> 2 thằng Node và Npm này được cài cùng nhau.
```

---

Bài 32 - JSON methods

---

- stringify: chuyển đổi object thành JSON string
- parse: ngược lại với stringify

  ```jsx
  new_JsonString = JSON.stringify(object);
  object = JSON.parse(new_JsonString);
  ```

- Chuẩn JSON String

---

Bài 33 - If ... else

---

```jsx
if (condition) {
  //  block of code to be executed if the condition is true
} else {
  //  block of code to be executed if the condition is false
}
```

---

Bài 34 - Ternary operator - Condition operator

---

```jsx
var age = 26;
var beverage = (age >= 21) ? "Beer" : "Juice";
console.log(beverage); // "Beer"

function example(…) {
    return condition1 ? value1
         : condition2 ? value2
         : condition3 ? value3
         : value4;
}
```

```jsx
// Equivalent to:

function example(…) {
    if (condition1) { return value1; }
    else if (condition2) { return value2; }
    else if (condition3) { return value3; }
    else { return value4; }
}
```

---

Bài 35 - else if

---

```jsx
if (time < 10) {
  greeting = "Good morning";
} else if (time < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```

---

Bài 36 - switch case

---

```jsx
const action = 'say_hello';
switch (action) {
  case 'say_hello':
    let message = 'hello';
    console.log(message);
    break;
  case 'say_hi':
    let message = 'hi';
    console.log(message);
    break;
  default:
    console.log('Empty action received.');
    break;
}
```

```jsx
var Animal = 'Giraffe';
switch (Animal) {
  case 'Cow':
  case 'Giraffe':
  case 'Dog':
  case 'Pig':
    console.log('This animal is not extinct.');
    break;
  case 'Dinosaur':
  default:
    console.log('This animal is extinct.');
}
```

---

Bài 37 - while, do ... while

---

```jsx
while (condition) {
  //do something
}
```

```jsx
do {
  // do something
} while(condition)
```

```jsx
let result = '';
let i = 0;

do {
  i = i + 1;
  result = result + i;
} while (i < 5);

console.log(result);
// expected result: "12345"
```

```jsx
let str = '';

for (let i = 0; i < 9; i++) {
  str = str + i;
}

console.log(str);
// expected output: "012345678"
```

```jsx
var i = 0;

for (;;) {
  if (i > 3) break;
  console.log(i);
  i++;
}
```

---

Bài 38 - Student manager app (CLI)

---

- Ok

---

Bài 39 - Sync. vs. Async. - đồng bộ và không đồng bộ

---

- In synchronous operations tasks are performed one at a time and only when one is completed, the following is unblocked. In other words, you need to wait for a task to finish to move to the next one.

- In asynchronous operations, on the other hand, you can move to another task before the previous one finishes.

---

Bài 40 - Callback hell

---

- Lồng quá nhiều kiểu if lồng if liên tục hay hàm lồng trong hàm

```jsx
const makeBurger = nextStep => {
  getBeef(function(beef) {
    cookBeef(beef, function(cookedBeef) {
      getBuns(function(buns) {
        putBeefBetweenBuns(buns, beef, function(burger) {
          nextStep(burger);
        });
      });
    });
  });
};

// __Bad!
```

---

Bài 41 - Promise

---

- Giúp thu gọn lại code
- Sinh ra để xử lí bất đồng bộ, giải quyết vấn đề callback hell

  ```jsx
  var fs = require('promise-fs');

  function onDone(song) {
    console.log(song);
  }

  function onError(error) {
    console.log(error);
  }

  function readFile(path) {
    return fs.readFile(path, { encoding: 'utf8' });
  }

  readFile('song1.txt')
    .then(onDone)
    .then(function() {
      return readFile('song2.txt');
    })
    .then(onDone)
    .catch(onError);
  ```

  ```jsx
  let done = true

  const isItDoneYet = new Promise((resolve, reject) => {
    if (done) {
      const workDone = 'Here is the thing I built'
      resolve(workDone)
    } else {
      const why = 'Still working on something else'
      reject(why)
    }
  })


  const fs = require('fs')

  const getFile = (fileName) => {
    return new Promise((resolve, reject) => {
      fs.readFile(fileName, (err, data) => {
        if (err) {
          reject(err)  // calling `reject` will cause the promise to fail with or without the error passed as an argument
          return        // and we don't want to go any further
        }
        resolve(data)
      })
    })
  }

  getFile('/etc/passwd')
  .then(data => console.log(data))
  .catch(err => console.error(err))
  ```

---

Bài 42 - Promise.all

---

```jsx
const p1 = new Promise((resolve, reject) => {
    setTimeout(() => {
        console.log('The first promise has resolved');

        resolve(10);
    }, 1 * 1000);

});
const p2 = new Promise((resolve, reject) => {
    setTimeout(() => {
        console.log('The second promise has resolved');
        resolve(20);
    }, 2 * 1000);
});
const p3 = new Promise((resolve, reject) => {
    setTimeout(() => {
        console.log('The third promise has resolved');
        resolve(30);
    }, 3 * 1000);
});

Promise.all([p1, p2, p3])
    .then(results => {
        const total = results.reduce((p, c) => p + c);

        console.log(`Results: ${results}`);
        console.log(`Total: ${total}`);
    });

===============================
============Output=============
===============================

The first promise has resolved
The second promise has resolved
The third promise has resolved
Results: 10,20,30
Total: 60
===============================
```

<https://www.javascripttutorial.net/es6/javascript-promise-all/>

---

Bài 43 - node co

---

<https://www.npmjs.com/package/co>

```jsx
co(function* () {
  var result = yield Promise.resolve(true);
  return result;
}).then(function (value) {
  console.log(value);
}, function (err) {
  console.error(err.stack);
});
```

---

Bài 44 - async await

---

---

Bài 45 - setTimeout

---

```jsx
  setTimeout(() => {console.log("this is the first message")}, 5000);
  setTimeout(() => {console.log("this is the second message")}, 3000);
  setTimeout(() => {console.log("this is the third message")}, 1000);

setTimeout(function(){ alert("Hello"); }, 3000);

var timeOutID = setTimeout(function done() {}, 1000);
clearTimeout(timeOutID);
```

---

Bài 46 - setInterval

---

- Thuc hien ham sau moi khoang thoi gian

```jsx
var intervalId = setInterval(function () {
  ++i;
  console.log(i===10) {
    clearInterval(intervalId);
  }
}, 1000);
```

---

Bài 47 - Date

---

```jsx
var now = new Date();
var myBirthday = new Date(1998, 10, 30);

console.log(now.getTime());
```

```jsx
var moment = require('moment');
var now = moment('2021-10-25 00:00');
console.log(now.fromNow());
console.log(now.format('YYYY/MM/DD'));
```

---

Bài 48 - scope

---

- local scope _ global scope

- Scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. The two types of scope are ```local``` and ```global```: Global variables are those declared outside of a block. Local variables are those declared inside of a block.

- [linking](https://www.digitalocean.com/community/tutorials/understanding-variables-scope-hoisting-in-javascript#:~:text=Scope%20in%20JavaScript%20refers%20to,declared%20inside%20of%20a%20block)

---

Bài 49 - Database design (Basic)

---

- Google
