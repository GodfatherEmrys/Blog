# (논리)

## 출력에 관하여

### 문제

> 다음 콘솔 로그 6개의 결과를 출력하는 순서대로 적어주세요.

```js
var selectMenu = 'Coffee';

function printMenu() {
  console.log(selectMenu);
  var selectMenu = 'Latte';
  console.log(selectMenu);
  
  function innerPrint() {
    console.log(selectMenu);
    
    function deeperPrint() {
      console.log(selectMenu);
      selectMenu = 'Iced Coffee';
      console.log(selectMenu);
      
      var selectMenu = 'Cold brew';
      console.log(selectMenu);
    }
    
    deeperPrint();
  }
  
  innerPrint();
}

printMenu();
```