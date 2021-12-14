
# ReactJS Course

-----------------------------------------------------------------------------

- Dưới đây là một số ghi chú của mình khi học ReactJS tại F8 Official, đây có lẽ là trang dạy Frontend web hay nhất dành cho người mới bắt đầu mình từng biết.
- Với mong muốn mở rộng chút kiến thức về mảng Frontend, mình thấy khóa này quá đáp ứng mong muốn của mình. Course cung cấp rất kỹ kiến thức về ReactJS, sẽ dễ học hơn nếu nắm chắc về HTML, CSS, JavaScript.

- Yêu cầu
  - Hiểu biết về mô hình Client-Server
  - Phân biệt rõ ràng được Front-end & Back-end
  - Nắm chắc HTML, CSS, đã có sản phẩm tự tay làm
  - Nắm chắc Javascript cơ bản và nâng cao, mình có note khóa JavaScript Cơ bản của [CodeX](https://www.youtube.com/c/CodersX/playlists) tại file [JavaScriptBasic.md](https://github.com/huongbk/ReactJS-Mynote/JavaScriptBasic.md)
  - etc.

-----------------------------------------------------------------------------

## Nội dung khóa học ReactJS 2021 F8 Official

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

- [X] Video 26: 28:07 : Two-way binding | React hooks 2021

- [X] Video 27: 15:08 : Todolist with useState() | React hooks 2021

- [X] Video 28: 05:37 : Mounted & Unmounted?

- [X] Video 29: 24:50 : React useEffect hook chi tiết cho người mới

- [X] Video 30: 13:03 : useEffect with dependencies | React hooks 2021

- [X] Video 31: 16:39 : useEffect() with DOM events

- [X] Video 32: 09:03 : useEffect() with timer functions

- [X] Video 33: 12:31 : useEffect() with preview avatar

- [X] Video 34: 18:46 : useEffect() with fake Chat App

- [X] Video 35: 08:45 : useLayoutEffect() hook? | React hooks 2021

- [X] Video 36: 17:35 : useRef() hook

- [X] Video 37: 11:00 : React.memo() HOC

- [X] Video 38: 10:12 : useCallback() hook

- [X] Video 39: 11:06 : useMemo() hook

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

  - Trong đó:
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

- Children nó cũng là một props, tách ra cho dễ nhìn thôi
- Phân cấp thẻ html lồng nhau bằng html

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
    const postItem = React.createElement(
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
    const postItem = React.createElement(
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

- Homework:

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

    ```bash
      npx create-react-app tiktok
    ```

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
  - Tạo 1 ứng dụng Random gift
  - Two-way Binding
  - Todolist app

- Tạo 1 ứng dụng Random gift

  ```jsx
  import React, { useState } from "react";

  const listGift = ["CPU i9 gen 10", "RAM 32 GB RGB", "RGB Keyboard"];

  function App() {
    const [gift, setGift] = useState("Chưa có phần thưởng");

    const handleGift = () => {
      const index = Math.floor(Math.random() * listGift.length);
      console.log(index);
      setGift(listGift[index]);
    };

    return (
      <div stype={{ padding: 32 }}>
        <h1>{gift}</h1>
        <button onClick={handleGift}>Click random gift</button>
      </div>
    );
  }

  export default App;

  ```

- Two-way Binding
  - Khi sử dụng các Framework JS có 2 khái niệm:
    - ReactJS:
      - One-way Binding là rằng buộc một chiều
      - One-way Data Binding: ReactJS uses one-way data binding. In one-way data binding one of the following conditions can be followed: Component to View: Any change in component data would get reflected in the view. View to Component: Any change in View would get reflected in the component's data.

    - VueJS:
      - Two-way Binding là rằng buộc hai chiều
      - Two-way data binding refers to sharing data between a component class and its template. If you change data in one place, it will automatically reflate at the other end. For example, if you change the value of the input box, then it will also update the value of the attached property in a component class.

  - Phần lớn thời gian sẽ làm việc với Two-way Binding nhiều hơn là One-way Binding
  - Rằng buộc 2 chiều: gõ cái gì thì bên trong nó thể hiện dữ liệu luôn, cứ lấy sẵn state mà xử lý dữ liệu. Ví dụ:
    - One-way Binding in React

      ```jsx
      import React, { useState } from "react";

      function App() {
        const [name, setName] = useState(" ");

        console.log(name);

        return (
          <div stype={{ padding: 32 }}>
            <input onChange={(e) => setName(e.target.value)} />
            <button onClick={() => setName("Luong Van Huong")}>Button</button>
          </div>
        );
      }

      export default App;

      ```

    - Two-way Binding in React, thêm cái ```value={name}``` vào

      ```jsx
      import React, { useState } from "react";

      function App() {
        const [name, setName] = useState(" ");

        console.log(name);

        return (
          <div stype={{ padding: 32 }}>
            <input value={name} onChange={(e) => setName(e.target.value)} />
            // thêm cái value bằng state (name) tạo ra rằng buộc 2 chiều
            <button onClick={() => setName("Luong Van Huong")}>Button</button>
          </div>
        );
      }

      export default App;

      ```

  - Ứng dụng trong thực tế xử lý From Name, Email:

    ```jsx
    import React, { useState } from "react";

    function App() {
      const [name, setName] = useState(" ");
      const [email, setEmail] = useState(" ");

      const handleEmail = () => {
        // CALL API
        console.log({
          name,
          email,
        })
      }

      return (
        <div stype={{ padding: 32 }}>
          <input value={name} onChange={(e) => setName(e.target.value)} />
          <input value={email} onChange={(e) => setEmail(e.target.value)} />
          <button onClick={handleEmail}>Button</button>
        </div>
      );  
    }

    export default App;

    ```

  - Two-way Binding cho Ratio:
    - Trong radio thì đặt trung name thì nó chỉ cho chọn 1 trong các radio thôi, tuy nhiên không dùng cách này do nó chỉ thay đổi giao diện.
    - Nên dùng State để xem nó chọn checkbox nào. Bài toán đặt ra là xem người dùng chọn radio nào rồi trả về cái Id của nó.

      ```jsx
      import React, { useState } from "react";

      // Response from API
      const listCourse = [
        {
          id: 1,
          name: "HTML, CSS"
        },
        {
          id: 2,
          name: "JavaScript"
        },
        {
          id: 3,
          name: "Python for DataScience"
        }
      ];

      function App() {
        const [idCourseChecked, setIdCourseChecked] = useState(); // ban đầu chưa chọn nên để undefine

        const handleClick = () => {
          // handle ID Checked with API
          console.log({
            id: idCourseChecked,
            name: listCourse[idCourseChecked - 1].name
          });
          // console.log(typeof idCourseChecked);
        };

        return (
          <div stype={{ padding: 32 }}>
            {listCourse.map((course) => (
              <div key={course.id}>
                <input
                  type="radio"
                  checked={course.id === idCourseChecked} // boolean
                  onChange={() => setIdCourseChecked(course.id)}
                />
                {course.name}
              </div>
            ))}
            <button onClick={handleClick}>Register</button>
          </div>
        );
      }

      export default App;

      ```

  - Two-way Binding cho list Checkbox (cho chọn nhiều cái):
    - Chọn nhiều cái nên phải tạo một cái mảng để lưu những checkbox đã chọn
    - [Array.prototype.includes()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)

      ```jsx
      import React, { useState } from "react";

      // Response from API
      const listCourse = [
        {
          id: 1,
          name: "HTML, CSS"
        },
        {
          id: 2,
          name: "JavaScript"
        },
        {
          id: 3,
          name: "Python for DataScience"
        }
      ];

      function App() {
        const [idCourseChecked, setIdCourseChecked] = useState([]); // ban đầu chưa chọn nên để undefine

        const handleCheckbox = (course) => {
          if (idCourseChecked.includes(course.id))
            setIdCourseChecked((pre) => pre.filter((item) => item !== course.id));
          else setIdCourseChecked((pre) => [...pre, course.id]);
        };

        const handleClick = () => {
          // handle ID Checked with API
          console.log({
            listIdCourse: idCourseChecked
          });
        };

        return (
          <div stype={{ padding: 32 }}>
            {listCourse.map((course) => (
              <div key={course.id}>
                <input
                  type="checkbox"
                  checked={idCourseChecked.includes(course.id)} // boolean
                  onChange={() => handleCheckbox(course)}
                />
                {course.name}
              </div>
            ))}
            <button onClick={handleClick}>Register</button>
          </div>
        );
      }

      export default App;

      ```

- Todolist app (Video sau)
- Other
  - [The nullish coalescing operator (??)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator) is a logical operator that returns its right-hand side operand when its left-hand side operand is ```null``` or ```undefined```, and otherwise returns its left-hand side operand.

-----------------------------------------------------------------------------

#### Video 27

Todolist with useState() | React hooks 2021

-----------------------------------------------------------------------------

- Content
  - To do list with useState()

    ```jsx
    import React, { useState } from "react";

    function App() {
      const [listTask, setListTask] = useState([
        {
          id: 0,
          name: "Create App TodoList"
        }
      ]);
      const [task, setTask] = useState();
      const description = "Type something...";
      const handleClickAdd = (task) => {
        const newId = listTask[listTask.length - 1].id + 1;
        setListTask((pre) => [...pre, { id: newId, name: task }]);
        document.getElementById("myID").value = "";
        setTask();
      };
      const handleClickReset = () => {
        setListTask((pre) => [pre[0]]);
        document.getElementById("myID").value = "";
      };

      return (
        <div stype={{ padding: 32 }}>
          <h1>To Do List</h1>
          <input
            type="text"
            onChange={(e) => setTask(e.target.value)}
            placeholder={description}
            id="myID"
          />
          <button onClick={() => handleClickAdd(task)}>Add</button>
          <button onClick={() => handleClickReset()}>Reset</button>
          {listTask.map((task) => (
            <div key={task.id}>
              <input type="checkbox" />
              {task.name}
            </div>
          ))}
        </div>
      );
    }

    export default App;

    ```

-----------------------------------------------------------------------------

#### Video 28

Mounted & Unmounted?

-----------------------------------------------------------------------------

- Mounted component: khi component đưa vào được sử dụng
- Unmounted component: khi component đưa vào mà không được sử dụng

  ```jsx
  import React, { useState } from "react";

  function Content() {
    return <h1>This is new Content</h1>;
  }

  function App() {
    const [display, setDisplay] = useState(false);
    const [state, setState] = useState("show");
    const handleClick = () => {
      setDisplay(!display);
      setState(display ? "show" : "hide");
    };
    return (
      <div stype={{ padding: 32 }}>
        <h1>To Do List</h1>
        <button onClick={handleClick}>Click to {state} Content</button>
        {display ? <Content /> : <h1>...</h1>}
      </div>
    );
  }

  export default App;

  ```

-----------------------------------------------------------------------------

#### Video 29

React useEffect hook chi tiết cho người mới

-----------------------------------------------------------------------------

##### Content

- Sử dụng đến khái niệm mounted, unmounted khá nhiều
- Giới thiệu useEffect Hook
  - Hook cơ bản trong ReactJS, The Effect Hook lets you perform side effects in function components
  - Sử dụng nhiều cú pháp nâng cao trong JavaScript nên nếu k chắc kiến thức JS Nâng cao thì tiếp cận khá là khó
  - useEffect() ra đời để làm gì, dùng nó khi nào?
- Một số kiến thức nên nắm chắc trước khi học useEffect hook
  - Event in JavaScript: Add/ Remove event listener,...hiểu tại sao lại phải đi remove event listener
  - Observer pattern advance: Subscribe/ Unsubscribe
  - Closure in JS
  - Biết cách làm việc với webapi dạng timer như setInterval(), setTimeout(), clearInterval(), clearTimeout(). Hiểu tại sao phải dùng? Khi nào phải dùng tới nó?
  - Nắm chắc useState, Mounted, Unmounted ở bài trước
  - Kiến thức cơ bản về toán tử so sánh ===
  - Hiểu cách Call API
- Khi nắm chắc những kiến thức trên thì giải quyết ngon lành các bài toán khó dùng useEffect()

- useEffect() ra đời để làm gì, dùng nó khi nào?
  - Dùng khi bạn muốn thực hiện các Side Effects
    - Side Effects là một thuật ngữ trong lĩnh vực lập trình phần mềm, nói tới một chương trình phần mềm mà khi có tác động xảy ra thì dữ liệu của chương trình bị thay đổi
  - Thường dùng useEffect() để thực hiện:
    - Update DOM
    - Call API
    - Listen DOM Events
      - Scroll
      - Resize
    - Cleanup
      - Remove listener/ Unsubscribe
      - Clear Timer

- [useEffect(callBack, [deps])](https://dmitripavlutin.com/react-useeffect-explanation/#:~:text=useEffect(callback%5B%2C%20dependencies%5D)%3B)
  - ```callBack```: đối số bắt buộc của useEffect, hàm ta tự định nghĩa rồi truyền vào để thực hiện các Side Effect
  - ```[deps]```: đối số không bắt buộc

##### Update DOM

- Một số tính chất của useEffect và ví dụ trong Update DOM:
  - Call back trong useEffect luôn được gọi sau khi Mounted component
    - ```Trường hợp 1: useEfftect(callBack)```
      - Gọi callBack mỗi lần component được re-render
      - Thực thi hàm callBack sau khi Component => tạo Dom Element => thêm vào trong DOM, như ví dụ bên dưới:

        ```jsx
        // Content.js
        import React, { useState, useEffect } from "react";

        function Content() {
          const [title, setTitle] = useState();
          useEffect(() => {
            console.log("Mounted component");
          });

          return (
            <div>
              <input onChange={(e) => setTitle(e.target.value)}></input>
              <h1>This is new Content!</h1>
            </div>
          );
        }

        export default Content;
        ```

        ```jsx
        // App.js
        import React, { useState } from "react";

        import Content from "./Content";

        function App() {
          const [display, setDisplay] = useState(false);

          return (
            <div stype={{ padding: 32 }}>
              <button onClick={() => setDisplay(!display)}>Click me!</button>
              {display && <Content />}
            </div>
          );
        }

        export default App;
        ```

        ```jsx
        //index.js
        import { StrictMode } from "react";
        import ReactDOM from "react-dom";

        import App from "./App";

        const rootElement = document.getElementById("root");
        ReactDOM.render(
          <StrictMode>
            <App />
          </StrictMode>,
          rootElement 
        );
        ```

        ```css
        /* styles.css */
        .App {
          font-family: sans-serif;
          text-align: center;
        }
        ```

      - Trường hợp này ít dùng trong thực tế, còn 2 trường hợp sau dùng liên tục luôn
      - Tại sao không để code ra ngoài mà phải để trong useEffect trường hợp này?
        - Nếu logic trong hàm callBack phức tạp thì nó vẫn render ra giao diện người dùng trước, rồi mới thực thi code trong hàm callBack
        - Còn nếu không sử dụng useEffect() thì nó chạy hết logic trong hàm callBack trước rồi mới render ra giao diện người dùng - [explain](https://youtu.be/hjIxfXKmkjk?t=760)
      - Nên để những cái thay đổi dữ liệu Side Effect vào trong useEffect, cho nó render ra trước rồi tính toán logic phức tạp sau

    - ```Trường hợp 2: useEfftect(callBack, [])```
      - Video sau
    - ```Trường hợp 3: useEfftect(callBack, [deps])```
      - Video sau

##### Call API

- Nên Call API bên ngoài hay bên trong useEffect() ?
  - [JSONPlaceholder](https://jsonplaceholder.typicode.com/) is a free online REST API that you can use whenever you need some fake data. It can be in a README on GitHub, for a demo on CodeSandbox, in code examples on Stack Overflow, ...or simply to test things locally.
  - Ví dụ tạo ra 1 trang list ra 100 bài post hiển thị ra giao diện người dùng
    - Trường hợp code như dưới này tạo ra vòng lặp call api liên tục, cứ mỗi lần setState nó lại call api 1 lần :), do nó thực thi callBack trong useEffect sau mỗi lần re-render (mỗi lần setState)

        ```jsx
        // cái này rơi vào Trường hợp 1: useEfftect(callBack)
        import React, { useState, useEffect } from "react";

        function Content() {
          const [title, setTitle] = useState();
          const [posts, setPosts] = useState([]);

          useEffect(() => {
            fetch("https://jsonplaceholder.typicode.com/posts")
              .then((res) => res.json())
              // .then((data) => console.log(data));
              .then((post) => setPosts(post));
          });

          return (
            <div>
              <input onChange={(e) => setTitle(e.target.value)}></input>
              <h1>This is new Content!</h1>
              <ul>
                {posts.map((post) => (
                  <li key={post.id}>{post.title}</li>
                ))}
              </ul>
            </div>
          );
        }

        export default Content;
        ```

      - Để khắc phục hiện tượng thực thi hàm callBack trong useEffect nhiều lần như trên thì sinh ra thằng dependences bên cạnh Callback (trường hợp 2 và trường hợp 3)

    - ```Trường hợp 2: useEfftect(callBack, [])```
      - Chỉ gọi callBack 1 lần sau khi Mounted Component
      - Nó không gọi lại mỗi khi component re-render như trường hợp 1

        ```jsx
        import React, { useState, useEffect } from "react";

        function Content() {
          const [title, setTitle] = useState();
          const [posts, setPosts] = useState([]);

          useEffect(() => {
            fetch("https://jsonplaceholder.typicode.com/posts")
              .then((res) => res.json())
              // .then((data) => console.log(data));
              .then((post) => setPosts(post));
          }, []);
          // thêm mảng rỗng [] vào thì nó chỉ thực chi callBack một lần sau khi Mounted Component

          return (
            <div>
              <input onChange={(e) => setTitle(e.target.value)}></input>
              <h1>This is new Content!</h1>
              <ul>
                {posts.map((post) => (
                  <li key={post.id}>{post.title}</li>
                ))}
              </ul>
            </div>
          );
        }

        export default Content;
        ```

    - Trường hợp 2 thường áp dụng cho việc gọi API một lần để hiển thị ra màn hình
    - ```Trường hợp 3: useEfftect(callBack, [deps])```
      - Video sau

-----------------------------------------------------------------------------

#### Video 30

useEffect with dependencies | React hooks 2021

-----------------------------------------------------------------------------

- Content
  - ```Trường hợp 3: useEffect(callBack, [deps])```
    - [useEffect(callBack, [deps])](https://dmitripavlutin.com/react-useeffect-explanation/#:~:text=useEffect(callback%5B%2C%20dependencies%5D)%3B)
    - Mỗi khi mounted thì nó gọi luôn hàm call back trước
    - CallBack sẽ được gọi lại mỗi khi Dependences thay đổi
    - Mỗi khi component re-render lại thì useEffect() nó sẽ kiểm tra xem Dependences có bị thay đổi hay không ( so sánh bằng toán tử === ), 
    - Dependences chỉ đơn giản là cái biến chứa dữ liệu, có thể là props truyền từ ngoài vào hoặc state,...
  
      ```jsx
      import React, { useState, useEffect } from "react";

      const tabs = ["posts", "comments", "albums", "photos", "todos", "users"];

      function Content() {
        const [title, setTitle] = useState();
        const [datas, setDatas] = useState([]);
        const [type, setType] = useState("posts");

        useEffect(() => {
          fetch(`https://jsonplaceholder.typicode.com/${type}`)
            .then((res) => res.json())
            .then((data) => setDatas(data));
          // .then((data) => console.log(data));
        }, [type]);

        const handleClickType = (tab) => {
          setType(tab);
          console.log(tab);
        };

        return (
          <div>
            {tabs.map((tab) => (
              <button
                style={
                  type === tab
                    ? {
                        color: "#fff",
                        backgroundColor: "#333"
                      }
                    : {}
                }
                onClick={() => handleClickType(tab)}
                key={tab}
              >
                {tab}
              </button>
            ))}
            <input onChange={(e) => setTitle(e.target.value)}></input>
            <h1>This is new Content!</h1>
            <ul>
              {datas.map((data) => (
                <li key={data.id}>
                  {type === "comments" || type === "users" ? data.name : data.title}
                </li>
              ))}
            </ul>
          </div>
        );
      }

      export default Content;
      ```

-----------------------------------------------------------------------------

#### Video 31

useEffect() with DOM events

-----------------------------------------------------------------------------

##### Listen DOM Events

- Content
  - Cách Listen DOM Events
  - Các vấn đề thường xảy ra
  - Cách khắc phục các vấn đề
  - Kiến thức yêu cầu
    - [DOM Events CheatSheet](https://www.codecademy.com/learn/fecp-building-interactive-websites/modules/fecp-dom-events-with-javascript/cheatsheet)
    - [EventsListener](https://developer.mozilla.org/en-US/docs/Web/API/EventListener#:~:text=Browser%20compatibility-,EventListener,-The%20EventListener%20interface)
    - [Remove DOM Events](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/removeEventListener)
- Trong bài này dùng 2 ví dụ
  - Scroll
  - Resize
- Lưu ý
  - Tránh viết gộp nhiều logic vào trong một cái useEffect()
  - Khi listen ở phạm vi ```windows``` thì nó vẫn listen khi unmounted component, nó chỉ biến mất khi mình tắt tab trình duyệt đi thôi => bị rò rỉ bộ nhớ ```memory leak```
    - Cách giải quyết: ```remove even listener``` khi unmounted component
  - ```Cleanup Function``` luôn được gọi trước khi unmounted component trong cả 3 trường hợp của useEffect()
    - Mục đích của ```Cleanup Function``` sinh ra để dọn dẹp bộ nhớ khi unmounted component

- Listen scroll

  ```jsx
  import React, { useState, useEffect } from "react";

  const tabs = ["posts", "comments", "albums", "photos", "todos", "users"];

  function Content() {
    const [title, setTitle] = useState();
    const [datas, setDatas] = useState([]);
    const [type, setType] = useState("posts");
    const [showGoToTop, setShowGoToTop] = useState(false)

    useEffect(() => {
      fetch(`https://jsonplaceholder.typicode.com/${type}`)
        .then((res) => res.json())
        .then((data) => setDatas(data));
    }, [type]);

    useEffect(() => {
      const handleScroll = () => {
        setShowGoToTop(window.scrollY >= 200)
      }
      window.addEventListener("scroll", handleScroll)
      // console.log("addEventListener")

      // Cleanup function in useEffect() => fixed warning!  
      return(() => {
        window.removeEventListener("scroll", handleScroll)
        // console.log("removeEventListener")
      })
    }, [])

    const handleClickType = (tab) => {
      setType(tab);
      console.log(tab);
    };

    return (
      <div> 
        {tabs.map((tab) => (
          <button
            style={
              type === tab
                ? {
                    color: "#fff",
                    backgroundColor: "#333"
                  }
                : {}
            }
            onClick={() => handleClickType(tab)}
            key={tab}
          >
            {tab}
          </button>
        ))}
        <input onChange={(e) => setTitle(e.target.value)}></input>
        <h1>This is new Content!</h1>
        <ul>
          {datas.map((data) => (
            <li key={data.id}>
              {type === "comments" || type === "users" ? data.name : data.title}
            </li>
          ))}
          {showGoToTop && (
            <button style={{
              position: "fixed",
              right: 20,
              bottom: 20,
            }}>
              Go to top!
            </button>
          )}
        </ul>
      </div>
    );
  }

  export default Content;
  ```

- Resize: Yêu cầu đơn giản là hiện ra kích thước chiều ngang màn hình ra ngoài, khi mình resize thì nó update lại giá trị hiển thị đó.

  ```jsx
  import React, { useState, useEffect } from "react";

  function Content() {
    const [width, setWidth] = useState(window.innerWidth)
    const [height, setHeight] = useState(window.innerHeight)

    useEffect(() => {
      const handleResize = () => {
        // console.log("handleResize");
        setWidth(window.innerWidth)
        setHeight(window.innerHeight)
      }
      window.addEventListener("resize", handleResize)

      // Cleanup function
      return(() => {
        window.removeEventListener("resize", handleResize)
      })
    }, [])
    
    return (
      <div> 
        <h1>Showing width and height windows!</h1>
        <ul>Width: {width}</ul>
        <ul>Width: {height}</ul>
      </div>
    );
  }

  export default Content;
  ```

-----------------------------------------------------------------------------

#### Video 32

useEffect() with timer functions

-----------------------------------------------------------------------------

- Trước khi học cần nắm chắc
  - Closure
  - [setInterval()](https://developer.mozilla.org/en-US/docs/Web/API/setInterval), [setTimeout()](https://developer.mozilla.org/en-US/docs/Web/API/setTimeout), clearInterval(), clearTimeout()

- setInterval() trong bài toán đếm ngược

  ```jsx
  import React, { useState, useEffect } from "react";

  function Content() {
    const [timer, setTimer] = useState(200);
    useEffect(() => {
      const intervalID = setInterval(() => {
        setTimer(prev => prev -1 )
      }, 1000);
    // cleanup function
    return (() => {
      clearInterval(intervalID)
    })
    },[])
    
    return (
      <div> 
        <h1>Clock!</h1>
        <ul>{timer}</ul>
      </div>
    );
  }

  export default Content;
  ```

- setTimeOut() trong bài toán đếm ngược

  ```jsx
  import React, { useState, useEffect } from "react";

  function Content() {
    const [timer, setTimer] = useState(200);
    useEffect(() => {
      const timeoutID = setTimeout(() => {
        setTimer(prev => prev -1)
      }, 1000);
    // cleanup function
    return (() => {
      clearTimeout(timeoutID)
    })
    },[timer])
    return (
      <div> 
        <h1>Clock!</h1>
        <ul>{timer}</ul>
      </div>
    );
  }

  export default Content;
  ```

-----------------------------------------------------------------------------

#### Video 33

useEffect() with preview avatar

-----------------------------------------------------------------------------

- Content
  - Ôn lại chút về cleanup function trong useEffect()
    - Cleanup function luôn được gọi trước khi unmounted component
    - Cleanup function luôn được gọi trước khi hàm callBack được gọi, trừ lần mounted component => trước khi thực hiện 1 lần callBack mói thì nó sẽ đi cleanup cái lần trước đó

      ```jsx
      import React, { useState, useEffect } from "react";

      function Content() {
        const [count, setCount] = useState(0);

        useEffect(() => {
          console.log(`Mounted lần ${count}`)
          //cleanup function
          return (() => {
            console.log(`Cleanup lần ${count}`)})
        },[count])
        
        return (
          <div> 
            <button onClick={() => setCount(preCount => preCount + 1)}>Counter!</button>
            <ul>{count}</ul>
          </div>
        );
      }

      export default Content;
      ```

- Ví dụ useEffect() with preview avatar với hai trường hợp
  - Trường hợp không sử dụng useEffect(): Như code bên dưới vẫn hoạt động đúng chức năng upload ảnh và hiển thị, tuy nhiên khi người dùng chọn file khác, file cũ vẫn lưu trong bộ nhớ (nó chỉ xóa khi người dùng đóng tab) => Memory Leak

    ```jsx
    import React, { useState } from "react";

    function Content() {
      const [avatar, setAvartar] = useState();
      const handleFile = (files) => {
        const file = files[0]
        file.preview = URL.createObjectURL(file)
        setAvartar(file)
      }
      return (
        <div>
          <input type="file" onChange={e => handleFile(e.target.files)} />
          <div>
            <h1>Your Image!</h1>
            {avatar && (<img src={avatar.preview} alt="" width={'50%'} />) }
          </div>    
        </div>
      );}

    export default Content;
    ```

  - Để khắc phục rò rỉ bộ nhớ như trường hợp trên, sử dụng useEffect()

    ```jsx
    import React, { useState } from "react";
    import { useEffect } from "react/cjs/react.development";

    function Content() {
      const [avatar, setAvartar] = useState();

      useEffect(() => {
        // Gọi hàm cleanup trước mỗi lần unmount, mỗi lần thay đổi file
        return (() => {
          avatar && URL.revokeObjectURL(avatar.preview)
        })
      }, [avatar])

      const handleFile = (files) => {
        const file = files[0]
        // if (avatar)
        //   URL.revokeObjectURL(avatar.preview)
        file.preview = URL.createObjectURL(file)
        setAvartar(file)
      }
      
      return (
        <div>
          <input type="file" onChange={e => handleFile(e.target.files)} />
          <div>
            <h1>Your Image!</h1>
            {avatar && (<img src={avatar.preview} alt="" width={'50%'} />) }
          </div>    
        </div>
      );}

    export default Content;
    ```

  - Nhận xét: trong trường hợp 2, có thể đặt lệnh ```URL.revokeObjectURL(avatar.preview)``` trước mỗi lần ```createObjectURL(file)``` vẫn tiết kiệm bộ nhớ mỗi khi người dùng chọn file khác. Tuy nhiên, dùng với useEffect hiệu quả hơn vì nó gọi hàm Cleanup trước mỗi lần Unmounted component => tiết kiệm bộ nhớ hơn.

-----------------------------------------------------------------------------

#### Video 34

useEffect() with fake Chat App

-----------------------------------------------------------------------------

- Content
  - Trong video trước còn trường chọn 2 ảnh giống nhau liên tiếp
    - Trong thực tế trường hợp người dùng chọn ảnh sau giống hệt ảnh trước thì không cần xử lý.
    - Do chọn 2 ảnh giống nhau liên tiếp nên ```e.target.value``` nó không thay đổi => hàm trong ```onChange()``` không được gọi
    - Nếu thích gọi hàm trong ```onChange``` trường hợp này thì có thể set ```e.target.value = null``` sau mỗi lần tải lên ảnh mới.
  - Bài hôm nay sẽ xử lý chức năng thời gian thực như chat, bình luận,... nâng cao hơn chút so với bài trước
    - Cơ chế bọn này thì dựa trên Subcribe và Unsubcribe, tương tự kiểu Listener & RemoveListener
    - What is WebSocket server?
      - A WebSocket server is nothing more than an application listening on any port of a TCP server that follows a specific protocol. ... A WebSocket server can be written in any server-side programming language that is capable of Berkeley sockets, such as C(++), Python, PHP, or server-side JavaScript.Oct 25, 2021
  - Trong bài này sẽ Fake ra 1 WebSocket server
    - Dữ liệu fake là lesson có 3 bài học với id và tên tương ứng
    - Khi phát ra 1 event ở phạm vi windows (```window.dispatchEvent()```)thì bất cứ một file nào trong chương trình cũng có thể lắng nghe được event đó
      - Trong bài này thì tạo 1 event fake comment, cứ 2 giây nó bắn ra 1 even tương ứng mỗi lesson.
      - Nên đọc thêm [CustomEvent()](https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent/CustomEvent)

    ```jsx
    // App.js
    import React, { useState } from "react";

    import Content from "./Content";

    // Fake comment
    function emitComment(id) {
      setInterval(() => {
        window.dispatchEvent(
          new CustomEvent(
            `lesson-${id}`,
            {detail: `Nội dung comment của lesson ${id}`}
          )
        )
      }, 2000)
    }

    emitComment(1)
    emitComment(2)
    emitComment(3)

    function App() {
      const [display, setDisplay] = useState(false);

      return (
        <div stype={{ padding: 32 }}>
          <button onClick={() => setDisplay(!display)}>Click me!</button>
          {display && <Content />}
        </div>
      );
    }

    export default App;
    ```

    ```jsx
    // Content.js
    import React, { useState, useEffect } from "react";

    const lesson = [
      {
        id: 1,
        name: 'RCNN'
      },
      {
        id: 2,
        name: 'Fast-RCNN'
      },
      {
        id: 3,
        name: 'Faster-RCNN'
      },
    ]

    function Content() {
      const [lessonID, setLessonID] = useState(1)

      useEffect(() => {
        const handleListenCustomEvent = ({detail}) => {
          console.log(detail)
        }
        window.addEventListener(`lesson-${lessonID}`, handleListenCustomEvent)
        
        return (() => {
          window.removeEventListener(`lesson-${lessonID}`, handleListenCustomEvent)
        })
      }, [lessonID])
      
      return (
        <div>
          {lesson.map((les) => (
            <li
              key={les.id}
              style={{
                color: lessonID === les.id ? 'red': '#333'
              }}
              onClick={() => setLessonID(les.id)}
            >
              {les.name}
            </li>
          ))}
        </div>
      );}

    export default Content;
    ```

-----------------------------------------------------------------------------

#### Video 35

useLayoutEffect() hook? | React hooks 2021

-----------------------------------------------------------------------------

- useLayoutEffect() gần giống với useEffect(), cả 2 thằng đều dùng để xử lý side effect. Đa phần là dùng useEffect() còn hy hữu lắm mới sử dụng useLayoutEffect()
- Chỉ khác nhau thứ tự thực hiện công việc như bên dưới
  - useEffect()

    ```text
    1. Cập nhật lại State
    2. Cập nhật lại một cái properties ở trong DOM Node (mutated)
    3. Render lại UI
    4. Gọi Cleanup nếu deps thay đổi
    5. Gọi useEffect() callback
    ```

  - useLayoutEffect()

    ```text
    1. Cập nhật lại State
    2. Cập nhật lại một cái properties ở trong DOM Node (mutated)
    3. Gọi Cleanup nếu deps thay đổi (sync)
    4. Gọi useLayoutEffect callback (sync)
    5. Render lại UI
    ```

- Ví dụ sử dụng useEffect() gây ra hiện tượng chớp nhoáng UI trong bài toán đếm số trong khoảng [0, 3]

  ```jsx
  import React, { useState, useEffect } from "react";

  function Content() {
    const [count, setCount] = useState(0)

    useEffect(() => {
      if(count > 3)
        setCount(0)

      return(() => {
        console.log("Cleanup...")
      })
    }, [count])
    
    const handleOnClick = () => {
      setCount(count => count + 1)
    }
    
    return (
      <div>
        <h1>{count}</h1>
        <button onClick={handleOnClick}>Button</button>
      </div>
    );}

  export default Content;

  // trường hợp này thì nó show ra số 4 rất nhanh trong quá trình hiển thị từ số 3 về số 0
  ```

- Để khắc phục hiện tượng chớp nhoáng phần hiểu thị như trên thì dùng useLayoutEffect()

  ```jsx
  import React, { useState, useLayoutEffect } from "react";

  function Content() {
    const [count, setCount] = useState(0)

    useLayoutEffect(() => {
      if(count > 3)
        setCount(0)

      return(() => {
        console.log("Cleanup...")
      })
    }, [count])
    
    const handleOnClick = () => {
      setCount(count => count + 1)
    }
    
    return (
      <div>
        <h1>{count}</h1>
        <button onClick={handleOnClick}>Button</button>
      </div>
    );}

  export default Content;
  ```

-----------------------------------------------------------------------------

#### Video 36

useRef() hook

-----------------------------------------------------------------------------

- useRef() ra đời để lưu lại một giá trị bất kỳ qua một giá trị tham chiếu bên ngoài function component
- Khi khởi tạo thì useRef() luôn trả về 1 đối tượng với properties là current

  ```jsx
    const refObject = useRef(69)
    console.log(refObject)
    // {current: 69}
  ```

- Ví dụ, xây dựng một chương trình đếm ngược với 2 nút start, stop

  ```jsx
  import React, { useState, useRef } from "react";

  function Content() {
    const [count, setCount] = useState(60)
    const [disabedStart, setDisabedStart] = useState(false)
    const refItervalID = useRef()

    const handleStart = () => {
      console.log("start...")
      refItervalID.current= setInterval(() => {
        setCount(preCount => preCount - 1)
      }, 1000);
      setDisabedStart(true)
    }

    const handleStop = () => {
      clearInterval(refItervalID.current)
      console.log("stop...", refItervalID)
      setDisabedStart(false)
    }
    
    return (
      <div style={{ padding: 20 }}>
        <h1>{count}</h1>
        <button onClick={handleStart} disabled={disabedStart}>Start</button>
        <button onClick={handleStop}>Stop</button>
      </div>
    );}

  export default Content;
  ```

- Ví dụ khác, trong thực tế nếu gặp trường hợp cần biết ```giá trị state trước và sau khi re-render```

  ```jsx
  import React, { useState, useRef } from "react";
  import { useEffect } from "react/cjs/react.development";

  function Content() {
    const [count, setCount] = useState(60)
    const [disabedStart, setDisabedStart] = useState(false)
    const refItervalID = useRef()
    const preCount = useRef()

    useEffect(() => {
      preCount.current = count
    }, [count])
    
    const handleStart = () => {
      console.log("start...")
      refItervalID.current= setInterval(() => {
        setCount(preCount => preCount - 1)
      }, 1000);
      setDisabedStart(true)
    }

    const handleStop = () => {
      clearInterval(refItervalID.current)
      console.log("stop...", refItervalID)
      setDisabedStart(false)
    }
    
    console.log(`count: ${count}, preCount.current: ${preCount.current}}`)

    return (
      <div style={{ padding: 20 }}>
        <h1>{count}</h1>
        <button onClick={handleStart} disabled={disabedStart}>Start</button>
        <button onClick={handleStop}>Stop</button>
      </div>
    );}

  export default Content;
  ```

- Thông thường cũng dùng useRef() để lưu cái thằng DOM Element

  ```JSX
  import React, { useState, useRef } from "react";
  import { useEffect } from "react/cjs/react.development";

  function Content() {
    const [count, setCount] = useState(60)
    const [disabedStart, setDisabedStart] = useState(false)
    const refItervalID = useRef()
    const preCount = useRef()
    const h1Ref = useRef()

    useEffect(() => {
      preCount.current = count
    }, [count])
    
    const handleStart = () => {
      console.log("start...")
      refItervalID.current= setInterval(() => {
        setCount(preCount => preCount - 1)
      }, 1000);
      setDisabedStart(true)
    }

    const handleStop = () => {
      clearInterval(refItervalID.current)
      console.log("stop...", refItervalID)
      setDisabedStart(false)
    }
    
    console.log(`count: ${count}, preCount.current: ${preCount.current}}`)
    console.log("h1Ref.current as bellow", h1Ref.current);

    return (
      <div style={{ padding: 20 }}>
        <h1 ref={h1Ref}>{count}</h1>
        <button onClick={handleStart} disabled={disabedStart}>Start</button>
        <button onClick={handleStop}>Stop</button>
      </div>
    );}

  export default Content;
  ```

-----------------------------------------------------------------------------

#### Video 37

React.memo() HOC

-----------------------------------------------------------------------------

- Thằng này nó không phải là Hook, nhưng phải biết sử dụng React.memo() thì bài sau học useCallback() ngon hơn
- ```React.memo()``` là Higher Order Component - **HOC**
- Trong React thì nó chia thành 3 cái, mỗi cái có chức năng và cách sử dụng khác nhau, túm lại là để đóng gói phần logic và tái sử dụng.
  - Hook - bên trong function
  - HOC - thằng này ở bậc cao hơn
  - Render props
- memo() giúp xử lý component để tránh re-render trong những tình huống không cần thiết
  - Ví dụ bên dưới có Component cha App() và Component con Content()
  - Tuy nhiên thằng Content bị re-render lại mỗi khi update state tại component App() => sinh ra thằng memo() để giải quyết vấn đề render thừa

    ```jsx
    // App.js
    import React, { useState } from "react";

    import Content from "./Content";

    function App() {
      const [count, setCount] = useState(0)

      return (
        <div stype={{ padding: 32 }}>
          <button onClick={() => {setCount(preCount => preCount + 1)}}>Button</button>
          <h2>Count: {count}</h2>
          <Content />
        </div>
      );
    }

    export default App;
    ```

    ```jsx
    import React, { useState } from "react";

    import Content from "./Content";

    function App() {
      const [count, setCount] = useState(0)

      return (
        <div stype={{ padding: 32 }}>
          <button onClick={() => {setCount(preCount => preCount + 1)}}>Button</button>
          <h2>Count: {count}</h2>
          <Content />
        </div>
      );
    }

    export default App;
    ```

  - Để tránh re-render lại nhiều lần thì bọc thằng Content() trong React.memo() lúc export

    ```jsx
    // export default Content;
    export default React.memo(Content);
    ```

- Nguyên lý của React.memo()
  - Nó nhận vào 1 Component()
  - Sau đó nó kiểm tra các props của Component() đó xem sau mỗi lần re-render có bị thay đổi hay không?
    - Chỉ cần ít nhất 1 props trong Component() thay đổi giá trị thôi thì nó sẽ re-render lại
    - Nếu không có props nào thay đổi thì nó không re-render lại
  - Toán tử nó sử dụng để so sánh sự thay đổi của props là toán tử 3 dấu bằng huyền thoại ```===```
  - [Cú pháp trong Docs:](https://reactjs.org/docs/react-api.html#reactmemo)

    ```jsx
    const MyComponent = React.memo(function MyComponent(props) {
      /* render using props */
    });
    ```

    ```jsx
    function MyComponent(props) {
      /* render using props */
    }
    function areEqual(prevProps, nextProps) {
      /*
      return true if passing nextProps to render would return
      the same result as passing prevProps to render,
      otherwise return false
      */
    }
    export default React.memo(MyComponent, areEqual);
    ```

- Khi nào nên sử dụng React.memo()
  - Khi mà component của bạn sử dụng nhiều props
  - Tự đánh giá, nếu component cha mà nó chứa nhiều component con bên trong, thì nên dùng memo() cho những cái component con đó
  - Không nên lạm dụng memo() quá, nhất là mấy component con đơn giản, dùng hết props của component cha thì chả cần memo() làm gì
  - Video sau sẽ xem vấn đề của memo() là gì, tại sao cần useCallback()

-----------------------------------------------------------------------------

#### Video 38

useCallback() hook

-----------------------------------------------------------------------------

- The useCallback hook is used when you have a component in which the child is rerendering again and again without need. Pass an inline callback and an array of dependencies. useCallback will return a memoized version of the callback that only changes if one of the dependencies has changed.
- Kiến thức yêu cầu
  - Reference Types trong JS, [Link này giảng khá chi tiết](https://www.educative.io/courses/step-up-your-js-a-comprehensive-guide-to-intermediate-javascript/7nAZrnYW9rG)
    - [Array , Function , and Object](https://viblo.asia/p/value-vs-reference-in-javascript-ByEZkW22ZQ0)

      ```jsx
      // exam
      function changeAgeImpure(person) {
          person.age = 25;
          return person;
      }

      const alex = {
          name: 'Alex',
          age: 30
      };   

      const changedAlex = changeAgeImpure(alex);

      console.log(alex); // -> { name: 'Alex', age: 25 }
      console.log(changedAlex); // -> { name: 'Alex', age: 25 }
      console.log(alex === changedAlex); // -> true
      ```

  - React.memo(), kiến thức bài trước

- useCallback() sinh ra để tránh tạo những function component không cần thiết, xem thử ví dụ bên dưới để thấy sự khác biệt so với thằng memo()
  - Trường hợp dùng memo() thì mỗi lần click button thì nó re-render lại thằng component con 1 lần

    ```jsx
    // App.js
    import React, { useState } from "react";

    import Content from "./Content";

    function App() {
      const [count, setCount] = useState(0)

      const handleClickButton = () => {
        setCount(preCount => preCount + 1)
      }

      // lưu ý toán tử so sánh === khi so sánh các tham chiếu thì nó chỉ so sánh cái địa chỉ bộ nhớ chứa function tham chiếu thôi

      return (
        <div stype={{ padding: 32 }}>
          <h2>Count: {count}</h2>
          <Content onIncrease = {handleClickButton} />
        </div>
      );
    }

    export default App;
    ```

    ```jsx
    // Content.js
    import React from "react";

    function Content({ onIncrease }) {
      console.log("re-render nè!")
      return (
        <div style={{ padding: 20 }}>
          <h2>Đây là Component con! Mỗi lần ấn Button Content() lại phải re-render 1 lần</h2>
          <button onClick= { onIncrease }>Button!</button>
        </div>
      );}

    export default React.memo(Content);
    ```

  - Để khắc phục hiện tượng trên thì sử dụng ```useCallback()```, thằng này có 2 tham số, 1 là function và thứ hai là ```[deps]``` tương tự như thằng ```useEffect()```

    ```jsx
    // App.js
    import React, { useState, useCallback } from "react";

    import Content from "./Content";

    function App() {
      const [count, setCount] = useState(0)

      const handleClickButton = useCallback(() => {
        setCount(preCount => preCount + 1)
      }, [])

      // useCallback() nó trả lại giá trị tham thiếu nên handleClickButton không thay đổi giá trị tham chiếu sau mỗi lần click
      // do đó memo() nó không re-render lại thằng con vì nó so sánh giá trị tham chiếu 2 lần === nhau

      // ngoài ra nếu trong hàm có biến nào đấy thì đút biến đó vào [deps], dùng tương tự thằng useEffect()

      return (
        <div stype={{ padding: 32 }}>
          <h2>Count: {count}</h2>
          <Content onIncrease = {handleClickButton} />
        </div>
      );
    }

    export default App;
    ```

    ```jsx
    // Content.js 
    import React from "react";

    function Content({ onIncrease }) {
      console.log("re-render nè!")
      return (
        <div style={{ padding: 20 }}>
          <h2>Đây là Component con! Mỗi lần ấn Button Content() lại phải re-render 1 lần</h2>
          <button onClick= { onIncrease }>Button!</button>
        </div>
      );}

    export default React.memo(Content);
    ```

- Túm lại
  - Một component có thể nhận rất nhiều Props
  - Props có thể là kiểu dữ liệu nguyên thủy hoặc kiểu dữ liệu tham chiếu (hàm, object, array)
    - Nếu props là kiểu dữ liệu tham chiếu thì nên dùng useCallback()
  - Nếu không sử dụng memo() cho Component con thì không cần phải dùng useCallback(), không nên làm dụng
    - Nếu thằng component con mà không dùng memo() thì bê useCallback() vào vô nghĩa

-----------------------------------------------------------------------------

#### Video 39

useMemo() hook

-----------------------------------------------------------------------------

- useMemo() là Hooks còn React.memo() là một HOG nên chức năng và cách sử dụng của hai thằng là khác nhau
  - useMemo() là Hooks nên dùng bên trong Component(), dùng để tránh lặp lại các logic trong component
  - React.memo() là HOG dùng để tránh re-render lại Component không cần thiết

- Ví dụ, cho người dùng nhập tên sản phẩm, giá sản phẩm. Khi ấn nút Add thì show ra bên dưới Tên : Giá sản phẩm

  ```jsx
  // App.js
  import React, { useState } from "react";

  function App() {
    const [name, setName] = useState("")
    const [price, setPrice] = useState("")
    // const [total, setTotal] = useState([])
    const [product, setProduct] = useState([])

    const handleAdd = () => {
      setProduct(pre => [...pre, {name: name, price: +price}])
    }
    // đoạn này bị tính toán lại khá nhiều lần
    const total = product.reduce((result, curProduct) => (result + curProduct.price), 0)
    console.log(total)

    return (
      <div stype={{ padding: 32 }}>
          <br />
            <input
              value={name}
              onChange={e => setName(e.target.value)}
              placeholder="Enter name..." 
            />        
          <br />
            <input
              value={price}
              onChange={e => setPrice(e.target.value)} 
              placeholder="Enter price..."
            />        
          <br />
            <button onClick={handleAdd}>Add!</button> 
          <br />
          <br />
            <h1>Total: {total}</h1>
          <br />
            <h2>List product:</h2>
            {product.map((product) => (
              <li key={product.name}>Name: {product.name}, price: {product.price}</li>
            ))}
      </div>
    )
  }

  export default App;
  ```

- Nhận xét: đoạn code trên thực hiện tính toán lại Total quá nhiều lần gây lãng phí, thực tế chỉ cần tính toán lại total mỗi khi người dùng ấn Add làm ```product``` thay đổi
- Khắc phục với ```useMemo()```, thằng này thì có 2 tham số là Callback function và ```[deps]```, nó chỉ thực hiện tính toán trong callback funtion khi Dependences thay đổi, các trường hợp của Dependences tương tự kiểu useEffect hay useCallback()

  ```jsx
  const total = useMemo(() => {
    return product.reduce((result, curProduct) => (result + curProduct.price), 0)
  }, [product])
  ```

- useMemo() giúp hiệu năng tốt hơn khá nhiều, code bài trên sau khi dùng useMemo() và thêm mấy cái linh tinh thành như sau

  ```jsx
  // App.js
  import React, { useMemo, useState, useRef } from "react";

  function App() {
    const [name, setName] = useState("")
    const [price, setPrice] = useState("")
    const [product, setProduct] = useState([])
    const nameRef = useRef()

    const handleAdd = () => {
      setProduct(pre => [...pre, {name: name, price: +price}])
      setName("")
      setPrice("")
      nameRef.current.focus()
    }

    const total = useMemo(() => {
      return product.reduce((result, curProduct) => (result + curProduct.price), 0)
    }, [product])

    return (
      <div stype={{ padding: 32 }}>
          <br />
            <input
              ref={nameRef}
              value={name}
              onChange={e => setName(e.target.value)}
              placeholder="Enter name..." 
            />        
          <br />
            <input
              value={price}
              onChange={e => setPrice(e.target.value)} 
              placeholder="Enter price..."
            />        
          <br />
            <button onClick={handleAdd}>Add!</button> 
          <br />
          <br />
            <h1>Total: {total}</h1>
          <br />
            <h2>List product:</h2>
            {product.map((product) => (
              <li key={product.name}>Name: {product.name}, price: {product.price}</li>
            ))}
      </div>
    )
  }

  export default App;
  ```

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
