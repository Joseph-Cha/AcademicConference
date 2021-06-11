# 5장 테스트 주도 개발

> TDD는 잘 돌아간다는 점이고, 이를 받아들여야 한다.

여러가지 핑계를 대며 TDD를 못하는 상태라고 하거나, TDD를 왜 해야하는지 모르겠다고 한는 사람들이 있다.

그동안 여러 책을 읽고, 여러 사람들과 이야기해보고 의견을 들어본 결과 TDD는 당연히 해야하는 것이며, 핑계는 자신이 만든 코드의 불확신에 대한 변명이라는 것을 깨달았다.

사실 내가 TDD를 하겠어!라고 해서 TDD를 할 수 있는 환경이 많을 것 같지는 않다.

최소한 TDD를 왜 해야해?라는 생각만 하지 않아도 충분할 것 같다는 생각이 든다.


## 거의 확신

그동안 일이 완료되었다는 말을 했던 기준을 생각해보았다. 그 기준은 굉장히 주관적었다.

그냥 내가 끝났다 싶을 때 완료되었다고 했다. 나는 내 코드에 대해 어떠한 검증도, 확신도 없는 상태에서 완료되었다고 한 것, 내 업무를 기준이라 책에서 말하는 부분과는 조금 다를 수 있지만 책에서 말하고자 하는 의미는 같다고 생각한다.  즉 주관적이 아닌 객관적인 확신이 필요하다는 것, 그 확신은 결국 TDD를 통해야만 가능하다는 것을

말하는 것 같다.


## 용기

아직 TDD가 되어있는 환경에서 코드를 수정해본 경험이 없어서, 정말 두렵지 않을지는 잘 모르겠다. 

하지만 확실한 것은 TDD가 없는 코드들은 정말 수정하기 무섭다. 그 코드를 수정하는데 얼마나 걸릴지 일정도 불확실하다. 만약 TDD가 되어있는 환경에서 두려움이 사라진다면, 코드를 수정하는데 걸리는 일정도 명확해질 수 있지않을까?라고 생각도 해보았다.


## 문서화

문서화가 얼마나 중요한지는 이제 너무 당연하다.

여기서 앨리스 레스토랑의 컬러광택사진이 뭔지 궁금해졌다.

[https://m.blog.daum.net/kkss1/15605808](https://m.blog.daum.net/kkss1/15605808) 이 블로그에 가면 가사를 자세히 해석해주고 있는데,

이 친구들이 어떤 이유로 쓰레기를 버렸는데, 그 이유와 설명은 사람들이 궁금해하지도 보려고 하지도 않고

오로지 사진 한 장으로 이 친구들에 대한 잘못된 판단을 하고있다는 내용 같다?

처음엔 왜 로버트 마틴이 이 앨리스 레스토랑에 대해 언급한지 궁금했는데 결국 예쁜 이미지보다는 숨겨진 내용이 중요하다? 뭐 이런 내용 같다. (노래가 길긴 하지만 생각보다 재밌고 좋다)


## 설계

설계가 얼마나 중요한지는 이제 너무 당연하다 2.

TDD를 하는데 설계가 없다는 것은 말이 안되고, 설계가 있다고 하더라도 설계가 올바르지 않으면 제대로 된 TDD도 나올 수 없다.

> ‘근데 나는 테스트를 나중에 만들 수 있어요.’라는 말은 들렸다.

그렇다면 어느날 갑자기 설계도 제대로 되지 않은 팀에서 우리 TDD합시다! 라고 한다면 TDD를 안하는게 맞는 것일까, 이미 만들어진 프로젝트의 설계를 다시 구성하여 TDD를 진행하는게 맞을까?


## TDD와 관련 없는 사실

> 테스트를 먼저 만들어도 형편없는 코드가 나오기 도 한다.

TDD만 하면 개쩌는 코드를 만들 수 있어! 라고 생각할 수도 있을 것 같다.

온 매체에서 TDD하세요! TDD를 해야 완벽한 코드가 나옵니다! 라고 말 할뿐 TDD를 해도 형편없는 코드가 나올 수 있어요 라고 말하는 매체는 본 적 없는 것 같다.

그런면에서 이 책은 정말 여러번 읽어도 충분한 가치가 있는 것 같다.

중요한 것은 다들 좋다고 해서 따라하는게 아니라 그 목적과 의미를 정확하게 알고 쓸줄 알아야 한다는 점 같다.