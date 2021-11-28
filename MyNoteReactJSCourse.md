# ReactJS Course

-----------------------------------------------------------------------------
Mynote ReactJS from F8 Official

- Yêu cầu
  - Hiểu biết về mô hình Client-Server
  - Phân biệt rõ ràng được Front-end & Back-end
  - Nắm chắc HTML, CSS, đã có sản phẩm tự tay làm
  - Nắm chắc Javascript cơ bản và nâng cao

-----------------------------------------------------------------------------

## Nội dung khóa học

-----------------------------------------------------------------------------

### Giới thiệu

- [X] Video 01: 10:41 : ReactJS là gì? Tại sao nên học ReactJS?

- [X] Video 02: 22:20 : SPA/MPA là gì?

### Ôn lại ES6

- [X] Video 03: 08:37 : Arrow function trong Javascript ES6

- [X] Video 04: 14:50 : Module trong javascript ES6

- [X] Video 05: 05:15 : Enhanced object literals trong javascript ES6

- [X] Video 06: 13:57 : Spread trong javascript ES6

- [X] Video 07: 13:20 : Destructuring trong javascript ES6

### React, React-Dom

- [X] Video 08: 10:02 : document.createElement() để làm gì?

- [X] Video 09: 14:51 : Thêm React vào Website? Github, NPMJS, UNPKG là gì?

- [X] Video 10: 14:31 : React.createElement() nữa là sao?

- [X] Video 11: 11:09 : React-DOM là gì? Tại sao cần React-DOM?

### JSX, Components, Props

- [X] Video 12: 15:59 : JSX là gì? Tại sao cần JSX?

- [X] Video 13: 13:36 : JSX render Arrays | JSX FQA

- [X] Video 14: 14:13 : React element types | React components

- [X] Video 15: 25:42 : Props là gì? Dùng props khi nào?

- [X] Video 16: 13:58 : DOM events? Làm việc với JSX #1

- [X] Video 17: 26:07 : Tạo Components linh hoạt? Làm việc với JSX #2

- [X] Video 18: 22:05 : Children props & Render props? Làm việc với JSX #3

### Create React App

- [X] Video 19: 11:39 : NodeJS là gì? Tại sao phải sử dụng NodeJS trong khóa ReactJS?

- [X] Video 20: 31:15 : Tạo dự án với React + Webpack

- [X] Video 21: 14:13 : Create React App

- [X] Video 22: 31:31 : NPM, NPX và YARN là gì?

- [X] Video 23: 12:37 : CRA Folder Structure

### Hooks

- [X] Video 24: 12:31 : Hooks là gì? Giới thiệu React Hooks

- [X] Video 25: 19:51 : useState trong React hook | React hook 2021

- [ ] Video 26: 28:07 : Two-way binding | React hooks 2021

- [ ] Video 27: 15:08 : Todolist with useState() | React hooks 2021

- [ ] Video 28: 05:37 : Mounted & Unmounted?

- [ ] Video 29: 24:50 : React useEffect hook chi tiết cho người mới

- [ ] Video 30: 13:03 : useEffect with dependencies | React hooks 2021

- [ ] Video 31: 16:39 : useEffect() with DOM events

- [ ] Video 32: 09:03 : useEffect() with timer functions

- [ ] Video 33: 12:31 : useEffect() with preview avatar

- [ ] Video 34: 18:46 : useEffect() with fake Chat App

- [ ] Video 35: 08:45 : useLayoutEffect() hook? | React hooks 2021

- [ ] Video 36: 17:35 : useRef() hook

- [ ] Video 37: 11:00 : React.memo() HOC

- [ ] Video 38: 10:12 : useCallback() hook

- [ ] Video 39: 11:06 : useMemo() hook

- [ ] Video 40: 15:58 : useReducer() hook

- [ ] Video 41: 21:35 : Todo App with useReducer() hook

- [ ] Video 42: 18:18 : useReducer() recap | React hooks 2021

- [ ] Video 43: 18:52 : React Context & useContext() hook

- [ ] Video 44: 28:54 : Global State with Context + useReducer

- [ ] Video 45: 16:45 : useImperativeHandle() hook

### CSS, SCSS, CSS Modules

- [ ] Video 46: 12:17 : Sử dụng CSS trong dự án ReactJS

- [ ] Video 47: 14:51 : CSS module là gì? Dùng NTN?

- [ ] Video 48: 12:12 : Thư viện clsx và classnames?

- [ ] Video 49: 05:23 : Install SASS để dùng SCSS?

### React Router V6

- [ ] Video 50: 15:07 : React Router V6 | Định tuyến trong ReactJS

-----------------------------------------------------------------------------

### Mynote each video

-----------------------------------------------------------------------------

#### Video 01

ReactJS là gì? Tại sao nên học ReactJS?

-----------------------------------------------------------------------------

- A JavaScript library for building user interfaces
- Open source from Facebook
- SPA : Single-Page Application
- Tại sao nên học?
  - Nhiều dự án yêu cầu phát triển Frontend bằng ReactJS, cộng đồng lớn
  - Thân thiện với SEO
  - Khả năng mở rộng tốt, tái sử dụng cao => Component
  - Hiệu suất cao, phát triển nhanh chóng => bê component từ cộng đồng vào dùng
  - Khả năng tương thích ngược
  - Tương lai phát triển cùng hệ sinh thái của Facebook

-----------------------------------------------------------------------------

#### Video 02

SPA/MPA là gì?

-----------------------------------------------------------------------------

- SPA: Single-Page Application
  - Hiện đại, không yêu cầu tải lại trang
  - Còn gọi là CSR -> Client side redering
  - Tương tác nhanh
  - Phần lớn tài nguyên tải trong lần đầu, nên khá là nặng nếu không tối ưu
  - Phương pháp băm nhỏ code để tải lần đầu cho nhanh
  - Thêm Dom vào rood element mới ra giao diện
  - Source code FE và BE riêng biệt khá gọn gàng
  - Ưu điểm khi phát triển trên thiết bị di động
    - Dễ tái sử dụng code
    - Sử dụng lại phần lớn API
    - Phụ thuộc hoàn toàn vào JS

- MPA: Multi-Page Application
  - Cổ điển, tải lại trang trong quá trình sử dụng
  - Còn gọi là SSR -> Server side redering
  - Mang tiếng chậm hơn nhưng nếu hạ tầng internet tốt thì trải nghiệm khá ok
  - Cả BE và FE đều nằm cùng trong source code luôn và nằm ở phía server, nên 2 bên phối hợp với nhau khá nhiều

- SEO: SPA không thân thiện bằng MPA
- Tùy hoàn cảnh sẽ dùng MPA hoặc SPA:
- MPA có chi phí phát triển thường thấp hơn, chậm hơn so với SPA
- Perform:
  - Nhiều người dùng thì SPA sẽ giảm tải cho phía server

-----------------------------------------------------------------------------

#### Video 03

Arrow function trong Javascript ES6

-----------------------------------------------------------------------------

- Hàm mũi tên
- Giúp code gọn hơn
- Arow function
  - Không có context của nó - không có this.phương thức
  - Không thể dùng làm Contructor function

```JavaScript
  // arow function
  const sum = (a, b) => a+b;
  const sum = (a, b) => { return a+b };

  // return object
  const sum = (a, b) => ({ a:a, b:b });
  const logger = log => console.log(log);
```

- JavaScript constructor function

```JavaScript
  // constructor function
  function Person () {
      this.name = 'John',
      this.age = 23
  }

  // create an object
  const person = new Person();
```

-----------------------------------------------------------------------------

#### Video 04

Module trong javascript ES6

-----------------------------------------------------------------------------

- A module is nothing more than a chunk of JavaScript code written in a file. By default, variables and functions of a module are not available for use.
- Bóc tách ra hàng chục module trong các file khác nhau để dễ quản lý và xây dựng
- Import / Export
  - File này Export ra cái gì thì file kia Import được cái đó

  ```JavaScript
    import logger from './logger.js';

    function logger(log, type='log') {
    console[type](log);
    }
    export defaul function 
  ```

  ```JavaScript
    // - Nếu mấy thằng export bình thường kiểu 
    export const TYPE_LOG = 'log'
    // thì
    import { TYPE_LOG } from './file.js';
  ```

  - Import hết tất cả các thể loại export:

  ```JavaScript
    import * as someThing from './file.js';
  ```

- Rất nhiều thể loại import export như [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)

-----------------------------------------------------------------------------

#### Video 05

Enhanced object literals trong javascript ES6

-----------------------------------------------------------------------------

- Định nghĩa key: value cho Object
- Định nghĩa method cho Object

```javascript
  var name = "lol";
  var age = 22;
  var student = {
    name, 
    age
  };

  console.log(student);
  //{name: "lol", age: 22}
```

- Định nghĩa key cho Object dưới dạng biến

  ```javascript
    var fieldName = 'name';
    var fieldPrice = 'price';

    const courseJS = {
      [fieldName]: 'Java',
      [fieldPrice]: 1000
    };

    console.log(courseJS)
  ```

- Xem trang chủ khá đầy đủ: [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer)

-----------------------------------------------------------------------------

#### Video 06

Spread trong javascript ES6

-----------------------------------------------------------------------------

- Dải tham số, tham khảo [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax#rest_syntax_parameters)

- rest:

  ```javascript
  function f(a, b, ...theArgs) {
    // ...
  }

  function myFun(a,  b, ...manyMoreArgs) {
    console.log("a", a)
    console.log("b", b)
    console.log("manyMoreArgs", manyMoreArgs)
  }

  myFun("one", "two", "three", "four", "five", "six")

  // Console Output:
  // a, one
  // b, two
  // manyMoreArgs, ["three", "four", "five", "six"]
  ```

- spread: [programiz](https://www.programiz.com/javascript/spread-operator)

  ```javascript
  function sum(x, y, z) {
    return x + y + z;
  }

  const numbers = [1, 2, 3];

  console.log(sum(...numbers));
  // expected output: 6

  console.log(sum.apply(null, numbers));
  // expected output: 6
  ```

  ```javascript
  let arr1 = [0, 1, 2];
  let arr2 = [3, 4, 5];

  arr1 = [...arr1, ...arr2];
  //  arr1 is now [0, 1, 2, 3, 4, 5]
  ```

  ```javascript
  function sum(x, y ,z) {
      console.log(x + y + z);
  }

  const num1 = [1, 3, 4, 5];

  sum(...num1); // 8
  ```

  ```javascript
  const obj1 = { x : 1, y : 2 };
  const obj2 = { z : 3 };

  // add members obj1 and obj2  to obj3
  const obj3 = {...obj1, ...obj2};

  console.log(obj3); // {x: 1, y: 2, z: 3}
  ```

-----------------------------------------------------------------------------

#### Video 07

Destructuring trong javascript ES6

-----------------------------------------------------------------------------

- The destructuring assignment syntax is a JavaScript expression that makes it possible to unpack values from arrays, or properties from objects, into distinct variables.

  ```javascript
  let a, b, rest;
  [a, b] = [10, 20];

  console.log(a);
  // expected output: 10

  console.log(b);
  // expected output: 20

  [a, b, ...rest] = [10, 20, 30, 40, 50];

  console.log(rest);
  // expected output: Array [30,40,50]
  ```

  ```javascript
  let a = 1;
  let b = 3;

  [a, b] = [b, a];
  console.log(a); // 3
  console.log(b); // 1
  ```

- Giải thích dễ hiểu hơn tại [JavaScript Destructuring](https://www.programiz.com/javascript/destructuring-assignment#:~:text=help%20of%20examples.-,JavaScript%20Destructuring,-The%20destructuring%20assignment)

  ```javascript
  // assigning object attributes to variables
  const person = {
      name: 'Sara',
      age: 25,
      gender: 'female'    
  }

  // destructuring assignment
  let { name, age, gender } = person;

  console.log(name); // Sara
  console.log(age); // 25
  console.log(gender); // female
  ```

-----------------------------------------------------------------------------

#### Video 08

document.createElement() để làm gì?

-----------------------------------------------------------------------------

- Tại sao phải biết phương thức này trong khóa ReactJS?
  - Hiểu được lý do tại sao thư viện ReactJS nó có thể render ra giao diện người dùng
  - Để tạo ra 1 element => thêm element vào trong DOM => tạo ra giao diện cho người dùng

- In this tutorial, you will learn how to use the JavaScript document.createElement() to create a new HTML element and attach it to the DOM tree.
  - [JavaScript CreateElement](https://www.javascripttutorial.net/javascript-dom/javascript-createelement/)

  ```html
  <!DOCTYPE html>
  <html>
  <head>
      <meta charset="utf-8">
      <title>JS CreateElement Demo</title>
  </head>
  <body>
      <script>
          let div = document.createElement('div');
          div.id = 'content';
          div.innerHTML = '<p>CreateElement example</p>';
          document.body.appendChild(div);
      </script>
  </body>
  </html>
  ```

  - Summary
    - The document.createElement() creates a new HTML element.
    - The element.appendChild() appends an HTML element to an existing element.

-----------------------------------------------------------------------------

#### Video 09

Thêm React vào Website? Github, NPMJS, UNPKG là gì?

-----------------------------------------------------------------------------

- các opensorce:
  - Github lưu source, quản lý source code
  - NPMJS-quản lí gói cho node
  - UNPKG - giúp tải nhanh

- Thêm react vào dự án: [Add React in One Minute](https://reactjs.org/docs/add-react-to-a-website.html)
  - Add xong có cái biến global là "React" thêm vào website để sử dụng
  - Thật sự thì thư viện React sẽ không chứa phần render UI, React nó cung cấp những objects/functions chính để chúng ta làm việc, nó cung cấp những khái niệm như: state, props, hooks, react-element và các functions mang tính tiện ích. Để render ra web UI chúng ta sẽ sử dụng thư viện React-dom

-----------------------------------------------------------------------------

#### Video 10

React.createElement() nữa là sao?

-----------------------------------------------------------------------------

- React.createElement() => React element => Thành phần nhỏ nhất của react
- DOM: thành phần nhỏ nhất của Dom là Node, thêm Element vào cái thẻ có sẵn trong Dom thì auto hiện ra giao diện
- Bản thân thằng react không tự render, phải render qua React Dom
- ex:

  ```jsx
  const h1React = React.createElement('h1', { title: 'Hello', className: 'heading'}, 'Hello guys!')
  ```

  - trong đó:
    - type: h1
    - props: { title: 'Hello', className: 'heading'},
    - children: Tất cả những cái còn lại

  ```jsx
  React.createElement(
    type,
    [props],
    [...children]
  )
  ```

- children nó cũng là một props, tách ra cho dễ nhìn thôi
- phân cấp thẻ html lồng nhau bằng html

  ```jsx
  const ulReact = React.createElement(
    'ul',
    null,
    React.createElement('li', null, 'JavaScript'),
    React.createElement('li', null, 'ReactJS'),
  )

  console.log(ulReact);
  ```

-----------------------------------------------------------------------------

#### Video 11

React-DOM là gì? Tại sao cần React-DOM?

-----------------------------------------------------------------------------

- React-DOM là 1 thư viện, cầu nối giữa React và Dom, giúp đưa các React element hiển thị trên Dom
- React-Native là cầu nối giữa React và IOS, Android
- Nhờ sự ra đời của React native nên bóc tách React ra riêng thành React-DOM / React-Native
- Dùng React DOM để render UI:

  ```jsx
  <script>
    const ulReact = React.createElement(
      'ul',
      null,
      React.createElement('li', null, 'JavaScript'),
      React.createElement('li', null, 'ReactJS'),
    )
    const root = document.getElementById('root')

    ReactDom.render(postItem, root)
  </script>
  ```

  - Hoặc

  ```jsx
  <script>
    const ulReact = React.createElement(
      'ul',
      null,
      React.createElement('li', null, 'JavaScript'),
      React.createElement('li', null, 'ReactJS'),
    )

    ReactDom.render(postItem, document.getElementById('root'))
  </script>
  ```

-----------------------------------------------------------------------------

#### Video 12

JSX là gì? Tại sao cần JSX?

-----------------------------------------------------------------------------

- JSX stands for JavaScript XML. It is simply a syntax extension of JavaScript. It allows us to directly write HTML in React (within JavaScript code). It is easy to create a template using JSX in React, but it is not a simple template language instead it comes with the full power of JavaScript.
- Thằng JSX sinh ra để có thể viết XML, HTML trong file JavaScript hoặc trong thẻ ```<Script></Script>```
- JSX không thể truyền thẳng vào ReactDom được, do nó chỉ nhận React Element => cần có thằng trung gian là Babel
  - [Babel](https://reactjs.org/docs/introducing-jsx.html#:~:text=Babel%20compiles%20JSX%20down%20to%20React.createElement()%20calls) là 1 thư viện JS chuyên dùng để chuyển đổi các cú pháp (JSX to JS)(ES6 to ES5)
  - Bản chất là chuyển đổi cú pháp, [link demo](https://babeljs.io/repl/#?browsers=defaults%2C%20not%20ie%2011%2C%20not%20ie_mob%2011&build=&builtIns=false&corejs=3.6&spec=false&loose=false&code_lz=DwVwNgfAUABDxgJYQBIFMxgPYwEIEMAjDAQmAHoloLwIg&debug=false&forceAllTransforms=false&shippedProposals=false&circleciRepo=&evaluate=false&fileSize=false&timeTravel=false&sourceType=module&lineWrap=true&presets=env%2Creact%2Cstage-2&prettier=false&targets=&version=7.16.4&externalPlugins=&assumptions=%7B%7D)
- Lưu ý
  - Khi dùng JSX mà muốn xen lẫn JavaScript vào thì phải có dấu ngoặc { } bọc bên ngoài.
  - Hay nhầm: truyền Object thì cần 2 cái { }, 1 cái dùng để chứa code JS và 1 cái là Object

  ```jsx
  function formatName(user) {
    return user.firstName + ' ' + user.lastName;
  }

  const user = {
    firstName: 'Harper',
    lastName: 'Perez'
  };

  const element = (
    <h1>
      Hello, {formatName(user)}!
    </h1>
  );

  ReactDOM.render(
    element,
    document.getElementById('root')
  );
  ```

- [Introduce JSX](https://reactjs.org/docs/introducing-jsx.html)

-----------------------------------------------------------------------------

#### Video 13

JSX render Arrays | JSX FQA

-----------------------------------------------------------------------------

- homework:

  ```jsx
  <script type='text/babel'>
    const course = [
      {
        name : 'abc',
      },
      {
        name : 'def',
      },
      {
        name : 'ghk',
      }
    ]
    
    const jsx = (
      <ul>
        {courses.map( (course, index) => <li key={index}>{course.name}</li> )}
      </ul>
    )
  </script>
  ```

  ```jsx
  function ReptileListItems() {
    const reptiles = ["alligator", "snake", "lizard"];

    return reptiles.map((reptile) => <li>{reptile}</li>);
  }
  ```

  ```jsx
  function NumberList(props) {
    const numbers = props.numbers;
    const listItems = numbers.map((number) =>
      <li key={number.toString()}>
        {number}
      </li>
    );
    return (
      <ul>{listItems}</ul>
    );
  }

  const numbers = [1, 2, 3, 4, 5];
  ReactDOM.render(
    <NumberList numbers={numbers} />,
    document.getElementById('root')
  );
  ```

- Render 2 cái element 1 lúc => bug => cần một thằng wrap lại => dùng <React.Fragment/>

-----------------------------------------------------------------------------

#### Video 14

React element types | React components

-----------------------------------------------------------------------------

- Đối số đầu tiên là Type: string - function / class
  - Function / Class : để tạo ra các component  
  ==> Function component / Class component
  - Trước sự ra đời của Hook thì chỉ Class component xây dựng được các component đầy đủ tính năng
  => Hook hỗ trợ Function component đầy đủ tính năng không thua kém Class
  - Hầu như toàn dùng hook xây dựng hiện tại
- Đối số thứ hai là Props
- Đối số thứ ba là Child

- React component
  - Tên phải viết hoa chữ cài đầu
  - Dùng Component như cái thẻ tag trong html

  ```jsx
  function Welcome(props) {
    return <h1>Hello, {props.name}</h1>;
  }

  const element = <Welcome name="Sara" />;
  ReactDOM.render(
    element,
    document.getElementById('root')
  );
  ```

- Class:

  ```jsx
  class Welcome extends React.Component {
    render() {
      return <h1>Hello, {this.props.name}</h1>;
    }
  }
  ```

-----------------------------------------------------------------------------

#### Video 15

Props là gì? Dùng props khi nào?

-----------------------------------------------------------------------------

- Nội dung
  - Chữa bài tập
  - React elements & React components
  - Props với React elements
  - Props với React components
  - Prop "key" là prop đặc biệt
  - Props có thể là bất cứ kiểu dữ liệu gì
  - Destructuring với props

- Chữa bài tập
  - Tạo component và render ra component đấy
  - Tuy nhiên để tránh hardcode, để nội dung các component render ra ứng biến hơn
  => Sinh ra thằng Props - tham số truyền vào component

- React elements & React components
  - Phân biệt rõ react elements và react components(thường là cả cái hàm luôn)

- Props với React elements
  - Sử dụng props giống atributes của thẻ HTML
  - 2 props class, for => className, htmlFor
  - Phải tuân theo quy ước có sẵn

- Props với React components
  - Cái thằng React components bản chất là cái hàm thôi
  - Hiểu đơn giản là truyền Props như truyền tham số cho Function thoai
  - Sau console.log(props) mà ra undefify thì khả năng cao là bạn quên không truyền nhé
  - Tự do đặt tên cho Props, đặt tên theo camelCase, có thể bao gồm dấu gạch ngang nhá

  ```jsx
  function Welcome(props) {
    return <h1>Hello, {props.name}</h1>;
  }

  function App() {
    return (
      <div>
        <Welcome name="Sara" />
        <Welcome name="Cahal" />
        <Welcome name="Edite" />
      </div>
    );
  }

  ReactDOM.render(
    <App />,
    document.getElementById('root')
  );
  ```

  ```jsx
  function Comment(props) {
    return (
      <div className="Comment">
        <div className="UserInfo">
          <img className="Avatar"
            src={props.author.avatarUrl}
            alt={props.author.name}
          />
          <div className="UserInfo-name">
            {props.author.name}
          </div>
        </div>
        <div className="Comment-text">
          {props.text}
        </div>
        <div className="Comment-date">
          {formatDate(props.date)}
        </div>
      </div>
    );
  }
  ```

- Prop "key" là prop đặc biệt
  - Lưu ý thằng Props "key" nhá: là prop đặc biệt, được dùng để đưa react element hoặc react component vào trong array để render ra
  - Không sài bừa bãi, nếu k nó trả về undefine

- Props có thể là bất cứ kiểu dữ liệu gì
  - Do là đối số của component thôi nên có có thể là bất kể dữ liệu gì
  - Callback: bản chất là truyền 1 hàm thông qua đối số của 1 hàm khác, nên truyền hàm trong props bản chất là callback đấy nhé
  - Học callback thật chắc ==> callback qua props đơn giản như đan giỏ

- Callback nó hoạt động khá đơn giản
  => dùng để lắng ngh các DOM even như click,... vài bài tới sẽ có ví dụ

- Destructuring với props
  - Thay vì dùng props.title, props.image,... thì chỉ cần gọi thuộc tính thôi bằng cách dùng Destructuring
  - Destructuring rất là hay, bạn có thể đặt được các giá trị default để truyền vào
  - Phần xử lí Destructuring truyền vào cho tiện: <https://youtu.be/TvE2FuYiuXo?t=1185>
  - Json viewer extension: fomat data api trả về cho ngon

- BTVN: <https://youtu.be/TvE2FuYiuXo?t=1475>
- Editor trên này khá là hay: <https://codesandbox.io/s/>

- Props là cách viết ngắn gọn của Properties, dùng để truyền các thuộc tính vào cho component thôi.

-----------------------------------------------------------------------------

#### Video 16

DOM events? Làm việc với JSX #1

-----------------------------------------------------------------------------

- Chữa bài
  - Bất kì function nào cũng có thể tạo ra được function component nhá
  - Tùy hoàn cảnh, cứ dễ hiểu thì dùng function bình thường hoặc arows function

- Xử lý dữ liệu:
  - Thực tế dữ liệu nhận được từ API, còn init các đối tượng trong mảng như sau:
  - Dự án nhỏ thì lấy hẳn từng props rất mất thời gian --> tuyền hẳn cái object cho nhanh, xong dùng map
  - Dự án lớn: tọa ra 1 cái tranformer để xử lý dữ liệu api trả về

- Exam:

  ```jsx
  const courses = [
  {
    "id": 1,
    "name": 'huonglv1'
  },
  {
    "id": 2,
    "name": 'huonglv2'
  },
    {
    "id": 3,
    "name": 'huonglv3'
  },
  ]

  const CourseItem = ({course}) => {
  <div>
    <h2>{course.name}</h2>            // lưu ý nhìn dữ liệu mà truyền cho nó đúng
  </div>
  }

  function App() {
  return (
    <div">
      {courses.map(course => (
      <CourseItem
        key={course.id}
        course={course}
      >
      ))}
    </div>
  )
  }
  ```

  => Link lưu ý: <https://youtu.be/7jQrn1KjcEw?t=433>

- DOM Evens
  - Trong react thì onclick --> onClick

    ```jsx
    <button onClick={ () => console.log( Math.random() ) } Click me! </button>
    ```

- Lưu ý:

  ```jsx
  <button onClick={ (event) => console.log( event.target ) }> Click me!</button>
  // output
  // <button> Click me!</button>  // lấy ra cái target thật trong event hiện tại
  ```

-----------------------------------------------------------------------------

#### Video 17

Tạo Components linh hoạt? Làm việc với JSX #2

-----------------------------------------------------------------------------

- Logic:
  - UI Component: bản chất nó chỉ là nhận dữ liệu và hiển thị thôi
  - HandleClick: <https://youtu.be/5SU6P-cqoJw?t=276>

- Xử lý DOM Events

  ```jsx
  <script type="text/babel">

  const Form = {
  Input() {
    return <input/>
  },
  Checkbox() {
    return <input type="checkbox" />
  }
  }

  function App() {
  return (
    <div id="wrapper">
    <Form.Checkbox>
    <Form.Input>
    </div>
  )
  }

  ReactDom.render(<App/>, document.getElementById('root'))

  </script>
  ```

- Trường hợp muốn render component theo ý mình => Tạo ra các Component tùy biến, linh động hơn

```jsx
<script type="text/babel">

const Form = {
 Input() {
  return <input/>
 },
 Checkbox() {
  return <input type="checkbox" />
 }
}

function App() {
 const type = "Input"    // or "Checkbox"
 const Component = Form[type]
 return (
  <div id="wrapper">
   < Component />
  </div>
 )
}

ReactDom.render(<App/>, document.getElementById('root'))

</script>
```

- Trường hợp muốn click in ra số random và chuyển link khác => Thường dùng để đếm số lần click vào link

```jsx
<script type="text/babel">

function Button({ title, href, onClick }) {
 let Component = "button"
 const props = {}
 
 if (href) {
  Component = 'a'
  props.href = href
 }
 if (onClick) {
  props.onClick = onClick
 }
 
 return (
  <Component {...props}>{title}</Component>
 )
}

function App() {
 return (
  <div id="wrapper">
   < Button
     title="Click me!"
     href = "https://google.com"
     onClick = { () => { console.log(Math.random() ) } }   // truyền 1 callback vào trong onClick
   />
  </div>
 )
}

ReactDom.render(<App/>, document.getElementById('root'))

</script>
```

- Lưu ý:
  - Booland, Null, Undefine không được render ra màn hình

- Other

  ```jsx
  <script type="text/babel">

  function App() {
  let firstAccess = True
  return (
    <div id="wrapper">
    { firstAccess && <div>Hello world!!</div> }
    </div>
  )
  }
  ReactDom.render(<App/>, document.getElementById('root'))
  </script>
  ```

  => Kết hợp toán tử Logic để Render có điều kiện

-----------------------------------------------------------------------------

#### Video 18

Children props & Render props? Làm việc với JSX #3

-----------------------------------------------------------------------------

- Content
  - Khái niệm 2 cách truyền props
  - Props default to "true"
  - Rest/Spread props
  - Children props
  - Render props

  ```jsx
  function HuongBK({ title, primary }) {
    console.log(primary);
    return <button type="primary">{title}</button>;
  }

  export default function App() {
    const title = "Xin chao Vietnam!!";
    return (
      <div className="App">
        {/* <HuongBK primary={true} title={title} /> */}
        <HuongBK primary title={title} />
        {/* default = true */}
      </div>
    );
  }
  ```

  ```jsx
  import "./styles.css";

  function HuongBK({ title, ...inputProps }) {
    return (
      <div>
        <button>{title}</button>
        <inputProps.type>other</inputProps.type>
      </div>
    );
  }

  export default function App() {
    const title = "Xin chao Vietnam!!";
    return (
      <div className="App">
        <HuongBK title={title} label="Somethings" type={"button"} />
      </div>
    );
  }
  ```

- Truyền props cho nhanh

  ```jsx
  function HuongBK({ title, ...inputProps }) {
    return (
      <div>
        <div>{title}</div>
        <input {...inputProps} />
      </div>
    );
  }

  export default function App() {
    const title = "Xin chao Vietnam!!";
    return (
      <div className="App">
        <HuongBK
          title={title}
          placeholder="Enter somethings..."
          titleButton="This is input"
          onFocus={() => {
            console.log(Math.random());
          }}
        />
      </div>
    );
  }
  ```

  ```jsx
  function HuongBK(props) {
    return (
      <div>
        <h1>{props.title}</h1>
        <div>{props.children}</div>
      </div>
    );
  }

  export default function App() {
    const title = "Xin chao Vietnam!!";
    return (
      <div className="App">
        <HuongBK title={title} children="This is children" />
      </div>
    );
  }
  ```

  ```jsx
  function HuongBK({ title, children }) {
    return (
      <div>
        <h1>{title}</h1>
        <div>{children}</div>
      </div>
    );
  }
  export default function App() {
    const title = "Xin chao Vietnam!!";
    return (
      <div className="App">
        <HuongBK title={title} children="This is children" />
      </div>
    );
  }
  ```

- Children prop:
  - ```<Component>String literals</Component>```
  - ```<Component>{expression}</Component>```

- Render props
  - Là truyền một cái function qua props: thường truyền qua children props:

  ```jsx
  function RenderListCar({ data }) {
    return (
      <ul>
        {data.map((item) => (                 // truyền 1 expression và props children
          <li>{item}</li>
        ))}
      </ul>
    );
  }

  export default function App() {
    const car = ["BMV", "AUDI", "HONDA", "MISHUBISHI"];

    return (
      <div>
        <RenderListCar data={car} />
      </div>
    );
  }
  ```

- Bản chất cái thằng children này là cái hàm

  ```jsx
  function RenderListCar({ data, children }) {
    console.log(data);
    console.log({ children });
    return <div>{data.map(children)}</div>;
  }

  export default function App() {
    const car = ["BMV", "AUDI", "HONDA", "MISHUBISHI"];
    return (
      <div>
        <RenderListCar data={car}>{(item) => <li>{item}</li>}</RenderListCar>
      </div>
    );
  }
  ```

- Nên viết như trong cái comment cho ae dễ đọc

  ```jsx
  function RenderListCar({ data, children }) {
    console.log(data);
    console.log({ children });
    return <ul>{data.map(children)}</ul>;
    // return <ul>{data.map((item) => children(item))}</ul>;
  }

  export default function App() {
    const car = ["BMV", "AUDI", "HONDA", "MISHUBISHI"];
    return (
      <div>
        <RenderListCar data={car}>{(item) => <li>{item}</li>}</RenderListCar>
      </div>
    );
  }
  ```

-----------------------------------------------------------------------------

#### Video 19

NodeJS là gì? Tại sao phải sử dụng NodeJS trong khóa ReactJS?

-----------------------------------------------------------------------------

- NodeJS là gì & Tại sao cần sử dụng NodeJS?
  - Là JavaSctipt Runtime, là môi trường để thực thi code JS
  - Nó dùng "chrome v8 javascript engine" để thực thi code JS - engine cũng đang dùng trên chrome luôn.
    - Node.js is an open-source and cross-platform JavaScript runtime environment. It is a popular tool for almost any kind of project!
    - Node.js runs the V8 JavaScript engine, the core of Google Chrome, outside of the browser. This allows Node.js to be very performant.
- Tại sao FE dùng NodeJS => để tạo ra cái máy chủ có thể chạy code trên máy cá nhân
- Để chuyên nghiệp hơn thì dùng NodeJS
- Npm cài đồng thời cùng với NodeJS => dùng các thư viện build sẵn ngon lành
  - install => import ra dùng luôn
  - create-react-app được build sẵn để nhanh chóng tạo project
- webpack: <https://webpack.js.org/> => Làm tối thiểu các file, cài rất nhiều publin trong đó, thay đổi tên biến về 1 kí tự => giảm dung lượng file, nhanh hơn,...

- Cài NodeJS cho Windows đơn giản
- Cài NodeJS cho MacOS, đơn giản

-----------------------------------------------------------------------------

#### Video 20

Tạo dự án với React + Webpack

-----------------------------------------------------------------------------

- Chỉ cần biết Webpack có thể làm gì :
  - Đơn giản là nó giúp module hóa dự án Frontend
  - Tăng trải nghiệm người dùng do gộp nhiều file thành 1 file, tránh request nhiều lần
- Làm theo link này nhé:
  - <https://fullstack.edu.vn/blog/phan-1-tao-du-an-reactjs-voi-webpack-va-babel.html>

- node -v
- npm -v

- npm init
  => package.json

- Cài đặt thư viện webpack
  - npm install webpack webpack-cli --save-dev
  - run `npm fund` for details

- Tạo ra thư mục node_modules, chứa các thư viện ta cài
  - Do 1 thư viện phụ thuộc nhiều thư viện khác nên sinh ra nhiều thư mục

- Cài React và ReactDom
  - --save-dev: lưu vào "devDependencies"
  - --save: lưu vào "dependencies"
  - Khác nhau:
    - devDependencies chỉ dùng lúc dev thôi
    - dependencies dùng cả lúc dev và lúc đưa lên production

- Cài Babel
  - npm install @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev

  - babel-core: Chuyển đổi ES6 về ES5
  - babel-loader: Cho phép chuyển các files Javascript sử dụng Babel & Webpack
  - babel-preset-env: Cài đặt sẵn giúp bạn sử dụng Javascript mới nhất trên nhiều môi trường khác nhau (nhiều trình duyệt khác nhau). Gói này đơn giản là support truyển đổi ES6, ES7, ES8, ES… về ES5.
  - babel-preset-react: Hỗ trợ chuyển đổi JSX về Javascript

- Tạo file public/index.html
  - ! --> template
  - Thêm 'root' vào
- Tạo file src/index.js
  - create App() đơn giản
- Cấu hình webpack
  - 1. Cài đặt CSS-Loader và Style-Loader
    - npm install css-loader style-loader --save-dev
  - 2. Tạo webpack.config.js
    - ok
  - 3. Tạo file .babelrc
    - Một số module trên npm phải cấu hình thêm cho thằng babel nó hiểu
  - 4. Thêm scripts cho dự án
    - Cái này để chạy lệnh cho tiện, ví dụ npm start, npm run build,...(trừ thằng start, mấy thằng khác phải thêm run vào)

      ```jsx
        "scripts": {
          "test": "echo \"Error: no test specified\" && exit 1",
          "start": "webpack --mode development --watch",
          "build": "webpack --mode production"
        },
      ```

- Lưu ý file json phải đủ dấu phẩy 
  - --watch cái này để lắng nghe update cái file và build lại
  => Cái file được build ra bundle.js là kết quả của webpack + thư mục dự án --> ES6->ES5, JSX->JavaScript
- Khi làm việc éo quan tâm file bundle.js lắm, chỉ quan tâm mấy file js thôi
- Chạy dự án
  - 1. Biên dịch code với Webpack
    - ok
  - 2. Chạy dự án với Live Server (VSCode)
    - Phải thêm ```<script src="../build/bundle.js"></script>``` trong body và dùng live server mới chạy được.

- Okie, tới đây các bạn hình dung flow chạy nó như này:
  - Webpack khi được chạy sẽ lắng nghe thay đổi của file
  - Khi file thay đổi Webpack sẽ biên dịch và update vào build/bundle.js
  - Website được chạy sẽ link file script từ build/bundle.js
  - Live Server chạy web và lắng nghe thay đổi của build/bundle.js để F5 lại trang

- Cài đặt html-webpack-plugin
  - npm install html-webpack-plugin --save-dev
- Cấu hình thêm mấy cái linh tinh
  - build ra file html mới và có thêm dòng ```<script defer src="bundle.js"></script></head>``` đằng trước root, do có defer nên nó không gặp lỗi
  - defer: có thằng này thì web tải file js về rồi khi nào gặp root nó mới load ra
- Cài đặt webpack-dev-server
  - npm install webpack-dev-server --save-dev
- Cấu hình

  ```jsx
  "scripts": {
      ...
      "start": "webpack-dev-server --mode development --open --hot",
      ...
  }
  ```

- Sau khi cài html-webpack-plugin, webpack-dev-server và cấu hình như trên thì tạo localhost:8080 luôn!
  - Done!

- Có thằng react-create-app xịn xò hơn, video 20 giúp hiểu bản chất của video 21

-----------------------------------------------------------------------------

#### Video 21

Create React App

-----------------------------------------------------------------------------

- Giúp đơn giản hóa quá trình sử dụng Webpack và ReactJS để tạo ra dự án
- Chạy 1 dòng duy nhất, config sẵn cho luôn
  - npx: thằng này giúp mình dùng thư viện mà không nhất thiết phải install thư viện npm về
  - yarn: nó cũng là trình quản lí gói của nodejs thôi

  ```bash
    yarn start
      Starts the development server.

    yarn build
      Bundles the app into static files for production.

    yarn test
      Starts the test runner.

    yarn eject  --> thằng này để bung ra config của thằng webpack thôi, tuy nhiên nên sử dụng thư viện để thay đổi webpank thay vì dùng trực tiếp eject nhá
      Removes this tool and copies build dependencies, configuration files
      and scripts into the app directory. If you do this, you can’t go back!
  ```

- Other

  ```bash
  - yarn start
          Local:            http://localhost:3000
          On Your Network:  http://192.168.1.170:3000    --> ae trong cùng mạng Lan mà muốn truy cập 
  ```

-----------------------------------------------------------------------------

#### Video 22

NPM, NPX và YARN là gì?

-----------------------------------------------------------------------------

- Yarn vs NPM: <https://www.sitepoint.com/yarn-vs-npm/>

- NPM

- Project scope
  - npm install react react-dom --save // từ bản 5.0 trở đi thì npm không cần thêm đuôi --save
    - npm i react react-dom
    - npm install webpack webpack-cli --save-dev
    - npm i -D webpack webpack-cli
  - Bản chất khi install nó tải thư viện về vào thư mục node_modules
    - npm uninstall react react-dom   // uninstall thư viện
  - Bản chất khi uninstall nó xóa thư viện trong thư mục node_modules

- Global scope
  - npm i --global create-react-app    // thằng global này nó tải về vào 1 thư mục trong máy tính cá nhân
  - npm i -g create-react-app    // linux thì thêm lệnh sudo nhá
  - npm uninstall -g create-react-app    // linux thì thêm lệnh sudo để uninstall nhá
- Bin:
  - Là file kịch bản thôi, giúp mình thực thi dòng lệnh JS

- NPX
  - Khi cài NodeJS thì tự động cài thêm npm và npx
  - Đơn giản là giúp thực thi các file bin như bên trên -> thực thi kịch bản có sẵn của các thư viện

  ```bash
    - npx create-react-app 
    // khi chạy lệnh này thì nó quét xem có thư mục node_modules không, nếu có thì nó vào tiếp thư mục .bin bên trong và tìm file bin trùng tên với create-react-app
    // nếu k thấy ở local scope thì nhảy tới global scope 
    // nếu k thấy ở global scope thì nó lên npm install về 
    => install về thực thi xong nó lại xóa luôn nhá :)) 
  => dùng npx ưu điểm khá ngon, đỡ phải cài lưu lại mà vẫn thực thi được 

  - dùng local scope thì phải đi qua thằng npx trong terminal nhé 
  - một số thằng gặp lỗi do đặt tên user là tiếng việt có dấu 
  => để khắc phục thì cài global thôi 
  ```

- NPM
  - npm actually involves three things:
  - A website for managing various aspects of your npm experience
  - A registry for accessing an extensive public database of JavaScript packages
  - A command-line interface (CLI) for interacting with npm via the terminal

- Yarn
  - Yarn stands for Yet Another Resource Negotiator. The Yarn package manager is an alternative to npm, released by Facebook in October 2016.
  - The original goal of Yarn was to deal with npm drawbacks, such as PERFORMENT and SECURITY issues.
  - Yarn was quickly positioned as a safe, fast, and reliable JavaScript dependency management tool.

- Hiện tại thì npm và yarn tương đối ngang cơ nhau
  - Để mà quản lí tất cả sự phụ thuộc các thư viện,... cần có file package-lock.json hoặc file yarn.lock

- Khi xóa node_modules đi thì --> npm install để kéo hết đống module lại
- Nó đọc file lock và cứ thế install...kk, file .lock tối ưu để cài ít nhất có thể

- Cơ chế:
  - npm cài lần lượt
  - yarn cài song song
  - Cơ chế cake thằng yarn tốt hơn thằng npm
  - Thằng yarn nó dành 1 phân vùng lưu tạm 1 tí của thư viện, khi install nó sẽ tìm xem có trong thư mục cake không, nếu có trong cake thì nó lôi ra luôn, không có thì nó install về 

-----------------------------------------------------------------------------

#### Video 23

CRA Folder Structure

-----------------------------------------------------------------------------

- create react app folder structure
  -npx create-react-app tiktok

- ./public
  - Thư mục này công khai nên có thể truy cập mọi cái trong folder từ trình duyệt
  - Muốn truy cập 1 file thì thêm /fileName: <http://localhost:3000/logo192.png> | <http://localhost:3000/manifest.json>
  - Thư mục public đóng vai trò là thư mục root, mấy file ngoài thư mục này k truy cập được từ trình duyệt
  - <http://localhost:3000> = ./public => Mặc định cấu hình sẽ tải ra file .html trong ./public
- Có nhập sai url thì vẫn mặc định sẽ hiển thị file index.html trong ./public, do là sigle page app
- Cho /node_modules vào file .gitignore nhé
  - Khi đó nguời khác cần gõ npm -i hoặc yarn 1 cái để kéo các package nodejs về
- yarn.lock quan trọng -> yarn để kéo package về
- yarn build --> build ra thư mục ./build để deploy lên cho khách hàng
- Chạy serve người dùng cuối bằng serve > chạy đúng cái source code production trong folder ./build

  ```bash
    yarn global add serve
    sudo npx i --global serve
    serve -s build

      http://localhost:5000
      On Your Network:  http://192.168.1.5:5000  
  --> mini file rất gọn và nhỏ
  ```

- ./src
  - src/index.js: file được webpack trỏ vào
  - Còn mấy file mặc định .css có thể bỏ đi để dựng theo dự án riêng của mình
  - src/reportWebVitals.js: dùng để report => phân tích => giúp tối ưu trải nghiệm người dùng
    - Gửi báo cáo thống kê lên google analytic được
- src/setupTests.js: file này học sau => đại loại giúp viết test để xem component có chạy đúng yêu cầu của mình không
- src/App.test.js: file này để viết test case thôi
  - yarn test => Test: 1 passed, 1 total

- What the Hooks?
  - useState
  - useEffect
  - useContext
  - useReducer
  - useCallback
  - useMemo
  - useRef
  - useImperativeHandle
  - useLayoutEffect
  - useDebugValue

-----------------------------------------------------------------------------

#### Video 24

Hooks là gì? Giới thiệu React Hooks

-----------------------------------------------------------------------------

- Trước muốn làm UI phức tạp cần Class component và function component chỉ làm những hiển thị đơn giản
- Giờ đã có Hooks
- Hooks
  - Là methods, hàm được viết sẵn bởi reactjs, mỗi Hooks có tính năng cụ thể
  - Bản chất khi dùng thằng nào thì gắn Function từ hook vào nên gọi là Hook - nghĩa đen là gắn
- Để dùng được Hooks:
  - Phải hiểu các Hàm bao gồm:
    - Chức năng gì?
    - Dùng khi nào?
    - Dùng ra làm sao?
- import mỗi hàm ra từ 'react'
  - Đầu tiên: dùng sẵn Hooks
  - Sau đó: custom Hooks --> your Hooks
- Thử f12 xem, sẽ thấy các Hooks dạng Function trong đó
- Lưu ý khi học Hooks:
  - Cần hiểu ý nghĩa tên của hàm
  - Xem đối số của nó là gì
  - Xem nó có trả ra cái gì hay không, cái trả ra thì mình làm việc như thế nào
  - Học theo đúng trình tự 10 cái hàm trên đầu luôn :)
- Ghi nhớ:
  - Hooks chỉ dùng cho Function component thôi
  - Vì đi làm đa phần làm Hooks nên tập trung vào Hooks luôn
  - Hooks giúp tạo component đơn giản hơn Class - do Class cần hiểu OOP
- Lifecycle
  - Lifecycle là 1 khái niệm rất quan trọng
  - Đánh dấu thời điểm khi sử dụng các sự kiện
  - Từ lúc hooks được gọi, thay đổi dữ liệu đến lúc bị xóa khỏi DOM
  - Trong class component thì nó tạo nhiều methods, mỗi methods đánh dấu 1 thời điểm của sự kiện nào đó. -> xử lý logic khá phức tạp
  - Trong function component thì nó giúp xử lý logic tại thời điểm khác nhau cùng nhau luôn, không phải sử dụng this như trong class component
- Khi nào dùng Hooks
  - Dự án mới => Hooks
  - Dự án cũ:
    - New component --> dùng luôn Hooks
    - Old component --> giữ nguyên class
  - Một số nghiệp vụ cần các tính năng của OOP --> dùng Class viết cho clean, hơn nữa Facebook chưa có kế hoặc từ bỏ Class component

-----------------------------------------------------------------------------

#### Video 25

useState trong React hook | React hook 2021

-----------------------------------------------------------------------------

- useState
  - Trạng thái của dữ liệu
  - Dữ liệu thay đổi gì thì UI thay đổi theo đó -> tránh phải làm thủ công như code thuần

- Dùng khi nào?
  - Khi muốn dữ liệu thay đổi thì giao diện tự động cập nhật theo - Render lại theo dữ liệu  
- Cách dùng?
  - Lấy nó ra và gắn nó vào function component --> nên gọi nó là hooks

```jsx
import { useState } from 'react';

function Example() {
  const [state, setState] = useState(initState);
 ...
}
```

- Explain: <https://youtu.be/rIaFc5MLCcs?t=281>
  - Mỗi lần gọi thằng setState thì nó lại gọi lại cái function component, chỉ khác chỗ là state không còn nhận init nữa
- Component re-render sau khi setState
- initState chỉ dùng cho lần đầu
- setState với callBack  
  - Lưu ý khi gọi setState nhiều lần trong cùng 1 handleFucntion thì state nó không update lại ngay, nó chỉ re-render lại 1 lần mỗi khi gọi handleFunction

- Trường hợp như này thì nó count chỉ tăng 1 do cơ chế của React

  ```jsx
    const handleOnclick = () => {
      setCount(count+1)
      setCount(count+1)
      setCount(count+1)
    };
  ```

- Trường hợp như này thì nó count tăng 3 mà vẫn re-render 1 lần

  ```jsx
    const handleOnclick = () => {
      setCount(preCount => preCount+1)
      setCount(preCount => preCount+1)
      setCount(preCount => preCount+1)
    };
  ```

- initState với callBack  
- initState có thể đặt là bất kì kiểu dữ liệu gì
- initState có thể đặt là callBack, và nó nhận giá trị trả về của callBack thôi
- Viết như dưới để tránh tính toán lại nhiều lần

  ```jsx
  const [count, setCount] = useState(() => { 
    const total = order.reduce((a, b) => a+b);
    return total 
  });
  ```

- Nếu đưa giá trị tính toán làm giá trị khởi tạo thì nhớ đút thẳng callback - return vào useState()

-----------------------------------------------------------------------------

#### Video 26

Two-way binding | React hooks 2021

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 27

Todolist with useState() | React hooks 2021

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 28

Mounted & Unmounted?

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 29

React useEffect hook chi tiết cho người mới

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 30

useEffect with dependencies | React hooks 2021

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 31

useEffect() with DOM events

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 32

useEffect() with timer functions

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 33

useEffect() with preview avatar

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 34

useEffect() with fake Chat App

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 35

useLayoutEffect() hook? | React hooks 2021

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 36

useRef() hook

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 37

React.memo() HOC

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 38

useCallback() hook

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 39

useMemo() hook

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 40

useReducer() hook

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 41

Todo App with useReducer() hook

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 42

useReducer() recap | React hooks 2021

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 43

React Context & useContext() hook

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 44

Global State with Context + useReducer

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 45

useImperativeHandle() hook

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 46

Sử dụng CSS trong dự án ReactJS

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 47

CSS module là gì? Dùng NTN?

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 48

Thư viện clsx và classnames?

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 49

Install SASS để dùng SCSS?

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------

#### Video 50

React Router V6 | Định tuyến trong ReactJS

-----------------------------------------------------------------------------

- Content

-----------------------------------------------------------------------------
