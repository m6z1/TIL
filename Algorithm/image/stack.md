# STACK

### 개념

![스택이미지](image/stack.png)

스택(stack)은 '쌓이다' 라는 의미를 가지고 있으며, 데이터를 차곡차곡 쌓은 형태의 자료구조이다.

한 쪽 끝에서만 자료를 넣거나 뺄 수 있어서 끝먼저내기 목록(Pushdown list)라고도 하며, **후입선출 (LIFO - Last In First Out) 선형구조** 이다.

위 사진과 같이 자료를 넣는 것을 **'push'** 라고 하며, 자료를 빼내는 것은 **'pop'** 이라고 한다. 이때, 후입선출 구조이기 때문에 pop을 통해 꺼내지는 자료는 가장 최근에 push한 자료부터 나오게 된다.

<br>

### 연산
stack.push(item) : item 을 stack의 가장 윗 부분에 추가

stack.pop() : stack의 가장 윗 부분 자료 제거

peek() : 스택의 가장 위에 있는 자료 반환 (peek: 훔쳐보다)

isEmpty() : 스택이 비어있는지 확인 (비어있으면 true / 비어있지 않으면 false)

search(item) : item 이 스택에 있으면 몇 번째로 나갈 수 있는지 반환


```
만약, peek() or pop()을 사용했을 때 비어있는 상태일 경우 EmptyStackException 발생
```

<br>

### 활용예시
- 웹 브라우저 방문 기록
- 안드로이드 액티비티 
- 실행취소


<br>

### 참고자료 <br>
https://ko.wikipedia.org/wiki/%EC%8A%A4%ED%83%9D
<br>
https://tildacoderecorder.tistory.com/101
