# 마우스 오버되면 나타나는 툴팁

- index.html

- style.css

기능먼저 구현

- 가로배치 1번
  .container {
  text-align: center;
  }
  .icon {
  display: inline-block;
  }

- 가로배치 2번 flex
  .container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  }
  .icon {
  }

  - 어떤 요소든
    position: absolute;
    를 주면 inline-block으로 변경

display none은
트랜지션을 줄수 없기 때문에

opacity를 사용했는데
그렇게 되면 마우스가 img태그가 아닌
icon클래스 위치에만 닿아도 툴팁이 나오게됨

visibility: hidden; 속성 추가
자리 값은 유지, 존재 자체는 사라짐

diplay none은
자리 값, 존재 자체가 사라짐



![image](https://user-images.githubusercontent.com/54789601/113504365-998e9200-9572-11eb-9736-39f94e23851a.png)

