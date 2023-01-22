## ToDo
- Simple Angular App
- Mock for API
- Playwright E2E test


## Steps
### Create project
1. Create project in PyCharm - pw_angular_mock
2. Create repo om GitHub
3. Telnet:
    ```
    $ git init
    $ git add README.md
    $ git commit -m "first commit"
    $ git branch -M main
    $ git remote add origin https://github.com/vvuri/pw_angular_mock.git
    $ git push -u origin main
    ```    
4. Run venv
   - Open pyCharm --> Go to Settings --> Tools --> Terminal
   - C:\Windows\system32\cmd.exe /K  "venv\Scripts\activate.bat"
   - reopen terminal	
5. Install https://playwright.dev/python/docs/intro

   ``` $ pip install pytest-playwright ```
    > pytest_playwright-0.3.0
    > playwright-1.29.1
    
   ```$ playwright install```    
    > Downloading Chromium 109.0.5414.46 
6. $ pip install flake8
7. $ pip freeze > requirements.txt 	
8. project structure
    > /src - for project
      /tests - for tests
9. first test
    https://playwright.dev/python/docs/writing-tests

### Next

- API mock test
    - Mocking API Response | Playwright Tutorial Part - 81
        https://www.youtube.com/watch?v=c7zCQ8FKih4
    - https://playwright.dev/python/docs/mock

- Playwright + xPath

- VSCode
    https://www.youtube.com/watch?v=6fapvF1uYo0

- PageObject model
    https://www.youtube.com/watch?v=9w6tDpQC4lE

- Work in docker or VM

- Search 
    https://www.bing.com/search?q=Playwright

- Playwright API Testing[CRUD] with Python/PYTEST
    https://www.youtube.com/watch?v=_i-XNZSSa5Q

- Doc
    https://playwright.dev/
    https://learn.microsoft.com/ru-ru/microsoft-edge/playwright/
- 
- PW example
    https://github.com/JoanEsquivel/playwright-python-test-framework

### Angular app
1.  Install
```bash
$ cd src
$ npm install -g @angular/cli
```
for windows:
```
$ Get-ExecutionPolicy -List
$ Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
$ ng help
```

2. Create simple app
```bash
$ ng new angular-app
```
without routing, with CSS
```bash
$ cd .\angular-app\
$ npm start
```
Browser: http://localhost:4200/

3. CLI
- ng generate component xyz
- ng add @angular/material
- ng add @angular/pwa
- ng test
- ng build --prod

### TypeScript wiki

1. Doc
[https://www.typescriptlang.org/docs]

2. Install
```bash
$ npm install -g typescript
$ tsc --version
  Version 3.9.7
```

3. Run
```bash
$ tsc
$ tsc main.ts
$ tsc --sourcemap main.js   // точки останова в TS
```

4. Configure
Конфигурационный файл: tsconfig.json

5. Types
*имя: тип*
```js
var str: string;
let num: nubber;
let big: bigint = 100n;
let isWork: boolean = false;

let list: number[] = [1, 2, 3];
let list: Array<number> = [1, 2, 3];

let x: [string, number];
```

```js
let notSure: unknown = 4;
notSure = "maybe a string instead";
```

```js
enum Color { Red, Green, Blue, }
let c: Color = Color.Green;
```

```js
const chnging: any;

let unusable: void = undefined;

let n: null = null;
```

- В функциях - необязательный параметр *имя?: тип*
- Never
- Object

6. Interface
```js
interface User {
  name: string;
  id: number;
  dop?: any;
}

const user: User = {
  name: "Hayes",
  id: 0,
};
```

7. Function
```js
```

8. Class
```js
```


9. Decorators
@expression
Декораторы представляют функции, которые могут применяться к классам, методам, геттерам и сеттерам, свойствам, параметрам.
Декоратор — это выражение, предваренное символом "@", которое возвращает функцию определенного вида.
```js
function MyDecorator(target, propertyKey, descriptor) {
    // ...
}
class MyClass {
    @MyDecorator
    myMethod() {
    }
}
```
@Component({
  // имя идентификации компонента в DOM
  // свойство шаблона
  // стилевое оформление компонента
})
class HelloWorldComponent({
  // код реализующий логику компонента
})

[Habr | https://habr.com/ru/company/docsvision/blog/310870/]

10. Generic
```js
```


