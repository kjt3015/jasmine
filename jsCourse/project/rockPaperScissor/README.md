# 가위바위보 프로젝트

이때까지 여러분에게 많은 정보를 던져만 주었고 실제로 그 정보들을 우리는 사용해보지 않았습니다. 배운 것을 이용하지 못한다면 그것은 큰 의미가 없겠죠? 우리는 아주 간단한 가위바위보 게임을 만들어보겠습니다. 모두가 가위바위보에 대한 룰은 알고 있다고 가정을 할게요! (정말로 모르신다면 [위키피디아](https://ko.wikipedia.org/wiki/%EA%B0%80%EC%9C%84%EB%B0%94%EC%9C%84%EB%B3%B4)의 가위바위보를 참고하세요... 그리고 내가 어떤 인생을 살아왔나도 한 번 회고해보시길...)

지금은 화면은 없고 콘솔 창에서만 진행을 할 것 입니다. 그래서 HTML과 CSS는 걱정하지 않으셔도 되지만, 나중에 다시 이 프로젝트로 돌아와 인터페이스를 추가하여 가위바위보를 조금 더 동적으로 할 수 있게 만들게요.

## 과제

1. 가위바위보 프로젝트를 위한 새로운 깃 레포지터리를 생성하세요.

2. 빈 HTML 문서를 script 태그와 함께 생성하여 주세요. 우리는 게임을 콘솔에서만 진행할 것이기 때문에 다른 것은 전혀 신경쓰지 않으셔도 됩니다.

3. 여러분은 컴퓨터랑 게임을 진행 할 것입니다. '가위', '바위', '보', 셋 중에 하나의 값을 반환하여 주는 **computerPlay** 라는 함수를 만들어주세요. 저희는 이 함수를 컴퓨터의 가위바위보 선택으로 사용할 것입니다.

4. 가위바위보를 한 판 진행하는 함수를 선언하여주세요. 여러분의 함수는 두 개의 매개변수를 가집니다. - **playerSelection** 과 **computerSelection** 입니다. 두 개의 매개변수는 유저의 선택과 컴퓨터의 선택을 각각 의미합니다. 그리고, 승자를 선언하는 문자열을 반환하여 주세요. 예를 들어: "컴퓨터에게 졌습니다! 가위는 바위를 이길 수 없어요"
형식의 문자열을 반환하여 주시면 됩니다.

  - 여러분의 함수는 소문자, 대문자 그 어떤 것이 들어와도 실행을 할 수 있어야 합니다. 예를 들어, 'rock', 'RocK', 'ROCK' 모두 바위로 인식하여 결과값을 반환해주어야 합니다.

5. **중요!!** : 위에서 얘기하였듯이, 여러분의 함수는 문자열을 반환하여 주어야 합니다. `console.log` 로 찍으시면 안됩니다!

예를 들어, 이런 식으로 작성하여 주세요.

```javascript
playRound(playerSelection, computerSelection) {
  // 여러분의 코드가 들어갈 곳!
} 

const playerSelection = “rock”; 
const computerSelection = computerPlay();

console.log(playRound(playerSelection, computerSelection)); 
```

6. **game()** 이라는 새로운 함수를 만들어주세요. 이 함수에 위에서 만들어준 **playRound()** 함수를 5번 진행하는데, 누가 많이 이겼는지 기록을 한 다음, 5번 진행 후 승자를 선언하여 줍니다.

  - 여러분은 아직 "반복문"을 배우지는 않았는데요. 반복문을 아신다면 그냥 반복문을 사용하셔도 좋고, 아니라면 그냥 playRound()를 5번 호출해주세요. 반복문은 이 프로젝트 바로 다음에 배울 것입니다.

  - 각각의 판마다, `console.log()` 를 사용하여, 매번의 승자를 출력하여주시고, 마지막의 승자도 출력하여주세요.

  - `prompt()` 를 이용하여 유저로부터 인풋을 입력받아주세요. [prompt 문서](https://developer.mozilla.org/ko/docs/Web/API/Window/prompt)

  - 만약에 여러분이 진행하면서, 게임 진행을 원활하게 해 줄 함수를 더 많이 선언하고 싶으시다면, 더 선언하여 주셔도 됩니다.

## 여러분들의 프로젝트

이 문서를 편집하시고, pull request를 이용하시어 여러분의 프로젝트 레포지터리 링크를 걸어주시면 됩니다.

<!-- 이 밑으로 열 -->

[상학 가위바위보](https://github.com/DaeguDude/rock-paper-scissors) - [라이브로 보기](https://daegudude.github.io/rock-paper-scissors/)

