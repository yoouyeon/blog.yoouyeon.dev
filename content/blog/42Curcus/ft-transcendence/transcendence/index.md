---
title: "트센 회고"
date: 2023-04-29 22:31:44
category: 42Curcus/ft-transcendence
description: "우당탕탕 트센 돌아보기"
---

## 🙃 intro

과제를 끝낸 지 무려 2달이나 지나고서 쓰는 42 마지막 과제 회고... 그래도 다행인건 끝나자마자 이 생각은 기록해놔야 해!! 하고 끄적여놨던 메모가 있었다는 것이다. 사실 내가 경험한 첫 (나름?) 규모가 큰 프로젝트였기에 아쉬운 부분이 많았어서 뒤늦게라도 기록을 해놔야 겠다는 생각이 있었다..

👍✨👍✨👍 프로젝트 레포 ✨👍✨👍✨

https://github.com/Jay13Jeong/PinguPong

✨👍✨👍✨👍✨👍✨👍✨👍✨👍✨

그리고 ... 반성의 시간 시작

## 😊 의미있었던 것

그냥 이론적으로 공부만 하던 React에 처음으로 Backend를 붙여볼 수 있었다. 혼자서 공부만 할 때에는 그냥 이론적으로... 이론서에 나오는 내용들만 얕게 알고 있었는데 실제로 프로젝트에 적용해보니 내가 생각보다도 더 모르는 내용이 많았구나... 하는 생각이 들었고 어떤 방향으로 더 공부를 해야 할지 몸과 마음으로 느낄 수 있었던 계기가 되었던 것 같다.

그리고 목표했던 기간 안에 기능 구현을 완료해서 평가 까지 통과했다는 점도 의미있었다. 팀원 한분이 2월 이후에는 작업이 어려우셔서 절대로 2월 안에 통과를 했어야 했는데 어떻게든 기한을 맞춰서 통과를 했다는 점? 빡빡한 계획은 세우지 않았지만 널찍하게 세웠던 계획에 모두 맞춰서 끝냈다는 점도 의미있었던 것 같다.

마지막으로는 혼자서 공부해서는 생각해보지 않았을 많은 내용들에 대한 고민을 할 수 있었다는 점이다. 웹 소켓을 사용해보는 경험이라던가, 실시간 핑퐁게임을 구현하는 로직에 대한 고민, 등등은 평범한 웹 프로젝트에서는 접해보지 못했을 (아닐수도.. 내가 그냥 경험이 부족한 것일수도...) 내용이라 이 과제를 하면서 고민했던 내용들이 나중에도 큰 도움이 되지 않을까.. 하는 생각이 든다.

## 🥲 아쉬웠던 것

> 미리 찔려서 고백하자면 아쉬운 점이 좀 많은데,,, 처음 경험하는 장기간의 프로젝트라 더 그랬을 것이라고 변명 아닌 변명을 해 봅니다.......... 🥲🥲

일단 제대로 된 문서를 작성하지 않았다. 변명하자면 우리 팀은 3명이라는 매우 적은 인원에 워크타임이 모두 동일한 시간이었기 때문에 바로바로 피드백이 가능했고, 각자가 담당하는 분야가 겹치지 않았기에 서로 소통만 잘 되면 되었어서 문서는 요구사항 명세서와 화면 설계 정도면 충분하긴 했었다. 하지만 API 명세 같은 것들은 필요할 때 마다 물어보고 받은 답변들을 slack에 고정시켜두고 썼었는데 미리 명시적으로 정리해뒀더라면 불필요한 커뮤니케이션을 좀 줄일 수 있지 않았을까... 하는 생각이 든다.

그리고 제대로 된 코드리뷰가 없었고 팀원을 전적으로 믿었다는 점도 아쉬웠다. 팀원이 나 (FE 100%), 팀원 A (FE 20%, BE 80%), 팀원 B (BE 100%)이었다. 백엔드 팀원들은 오프라인에서 코드리뷰를 종종 했었는데 나는 사실상 프론트엔드를 혼자서 해야 하는 상황이었기에 (프론트엔드 로그인, 프로필 관리 부분을 도와준 팀원 A는 백엔드 중심의 지식과 경험을 가지고 있었다.) 기술적으로는 그냥 내가 단독으로 진행시키는 감이 없지않아 있었다. 게다가 팀원 셋 다 담당 분야에 대한 기술들을 익히는 데 벅찼기 때문에 더 '일단 되게 하자' 라는 기조가 있었던 것 같다. 각자의 브랜치에서 작업을 하고 PR을 남기기도 했는데 리뷰보다는 각자의 작업 사항이 겹치지 않게 하기 위한 목적이 더 컸던 것 같아서 굉장히 아쉽다고 생각한다... 각자 잘 모르는 분야기는 하지만 그래도 논리적인 흐름 정도는 리뷰를 해 주는 편이 좋지 않았을까? 하는 생각이 들기도 하면서도 한정적 인원과 짧은 수행 기간 때문에 불가피한 것이었던 것 같아서 더 아쉽다.

개인적으로는 기획 단계에서 집중해서 참여하지 못했다는 점도 아쉽다. 다른 팀원들은 이미 앞선 과제들을 끝낸 상태였고, 나는 과제가 두개나 남아있었기 때문에 기획단계에선 그냥 참여하는데 의의를 두는 수준이었고, 과제 2개를 마저 끝내고 왔더니 기획이 끝나 바로 개발에 돌입하면 되는 상황이었던 것이 조금 아쉽다는 생각이 들긴 했다.

기술적으로 아쉬웠던 부분은 ... 한두개가 아니지만 좀 추려보면

- 전역상태를 불필요하게 사용한 것 같다. : Recoil을 너무 남발한게 아닌가 하는 느낌. 특히 Game 데이터는 그냥 props로 넘겨주는 것이 좀 더 깔끔하지 않았을까? 하는 생각이다.
- Private Route 방식이 체계적이지 않음 : 사실 로그인 부분에는 관여를 잘 안해서 (위의 아쉬운 내용 참고 ㅜㅜ) 간단히 확인해보았는데 매 컴포넌트마다 useCheckLogin 함수를 써서 확인하는 것 같았다. 로그인 처리에 대해서 좀 공부를 한 지금 다시 생각해보니 PrivateRouteLayout을 하나 더 만들어주는 편이 더 깔끔하고 괜찮은 방법이었을 것 같다는 생각이 든다.
- 에러 처리를 그냥 구멍 메꾸듯 함 : '일단 에러가 안나니 되었다!' 식으로 처리한 부분이 너무너무너무 많다. 특히 api 호출 부분을 너무 복잡하게 짰는데 좀 더 전체적으로 보고 구조 자체를 잘 짰으면 에러도 잡고 구조도 잡고 할 수 있지 않았을까 하는 생각이 든다.

## 🙂 마무리

아쉬웠던 것 내용이 의미있었던 것 내용의 두배...

처음부터 잘하는 사람은 드물 거라고 생각한다. 당연히 이 프로젝트도 다른 팀원들에게도, 나에게도 거의 첫 웹 프로젝트이기 때문에 아쉬운 부분이 없을 수는 없을 것이다. 그래도 좀 더 다른 프로젝트들이 어떻게 진행되는지 같은 좋은 사례들을 보고 우리 팀에 적용할 수 있는 시간적 여유가 있었으면 좋지 않았을까 하는 생각이 계속 들어서 아쉽다는 말을 계속 하고 있는 것 같다.

진행 부분에서는 아쉬운 부분이 많았지만, 그래도 어떻게든 문제 없이 마감 기한을 맞췄다는 것, 그리고 한달 반이라는 시간 동안 내가 배울 수 있었던 많은 것들 (그냥 기분탓이 아니고 정말 트센 전의 나와 트센 이후의 내가 기술적으로나 마음가짐으로나 정말 달라졌는데, 이 내용은 나중에 다른 글에서 풀어볼 기회가 있을 것 같다.)이 있기에 마냥 부끄럽거나 숨기고 싶은 프로젝트는 아니다. 그리고 무려 아무나 통과 못하는 42 본과정의 마지막 과제인걸 음하하 (하지만 프로젝트 첫 단계의 단추를 꿰어보지 못했던 게 아쉬워서 (또 아쉬움...) 다른 팀과 트센을 한번 더 할까? 했었는데 더 좋은 기회가 와서 그러진 못햇다.)

그래도 아쉬운건 아쉬운거라 보완하고 싶은 것들, 개선하고 싶은 것들을 정리해두었다가 당장 바쁜 것 끝나면 팀원들에게 다시 연락해볼까.. 하고 있긴 하다.

- 개인 저장소 → 팀 저장소로 옮기기
- 배포
- 로그인 부분 로직 리뷰해보기
- 땜질해놨던 코드들 더 좋은 방법 있을지 생각해보기

그래도 웹서브때부터 맘 맞는 좋은 팀원들을 만나서 큰 갈등 없이 (정말.. 놀랍게도 큰 갈등이 없었다 정말) 무사히 마지막 과제까지 완료할 수 있어서 다행이라고 생각한다. 줄줄이 적어둔 아쉬웠던 경험들은 분명히 다음 프로젝트때 큰 도움이 될 것이라 생각한다..ㅎㅎ