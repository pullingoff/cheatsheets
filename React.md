<section style='display:flex'>
  <img width="350px" alt="useReducer for boolean state" src="https://user-images.githubusercontent.com/50111853/190553452-1936b4f3-e8e1-4236-9cc0-64f7b91a83bc.png">
</section>

- 이 reducer는 상태를 true로 바꾸는 한 가지 역할/트랜지션만 하므로 (초기값->최종값) 값이 revert되면 안될때 사용.
- reducer를 사용하면 좋은 점은 **로직을 한군데 캡슐화할 수 있다는 거고, 그 밖에선 메시지를 dispatch하는 것이나 현재 상태를 읽는 것만 가능**하단 것.
- toggle example: `[on, toggle] = useReducer(s => !s, false)`  
