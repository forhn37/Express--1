# Express--1
'눈'이 되어주는 디버거의 힘과 프레임워크와의 관계
훈련생 여러분들께서 가뿐히 적응하고 있는 Express.js는 Node.js에서 웹 서버 프레임워크 경쟁자가 없을만큼 '표준' 처럼 보편화되었습니다. Node.js 오랜 친구처럼 매우 큰 사랑 받고 있기 때문에, 유저들의 관성도 대단합니다. 현재는 Express.js를 '품고' 있는 상위호환 프레임워크들이 강세이지만, 어디까지나 안정적인 '규격화'된 프레임워크를 위함이기 때문에 가볍게 비즈니스모델을 구현하는 것에는 여전히 강력한 유저풀을 거드리고 있습니다. 서비스 프로토타이핑을 할 때 Express.js는 매우 간단히 적용하고, 추후에 방향에 따라 변경하는 등 유연한 선택지를 만들어 주기때문에 간과하기 쉬운 것은,

바로 '어딘가 쓰여져 있을 코드'를 알아채고 원활하게 활용할 수 있어야 합니다. 오랜시간 공들여 다듬어진 프레임워크이기 때문에, '마이크로 프레임워크'를 추구하는 Express.js여도 지원하는 기능이 상당히 많습니다.이럴때 우리는 책을 들여다보거나, GPT를 활용하는 등 여러가지 조치로 학습하고 응용할 수 있게되겠지만, GPT가 생성해주는 똑똑한 답변도 시간, 책보는 시간도 시간이기에, 탐색에 매우 큰 수고가 따릅니다. 요컨데 역시 '디버거'의 사용성은 언제나 변함없이 중요합니다.

본 스크린샷 예제는 간단하게 서버를 제작하는 놀랄만큼 짧게, 직관적으로 처리된 Express.js 프로젝트 초기 모습입니다. '풍부한 이해'를 위해서 거의 '고정되듯' 작성된 몇개의 코드를 주석으로 지우듯 처리하고, express() 라는 이름의 함수를 호출하여 대입한 app 변수를 조회한 모습입니다.

'눈'으로는 함수처럼 보이는 이 코드는 역시나 인스턴스로 판별됩니다. 즉, 객체이므로 여러가지 메서드와 속성들이 가득 들어있는 것을 확인 할 수 있습니다. 브라우저가 따로 없는 이러한 서버'구축'에서는 디버거의 습관화가 매우 중요합니다.

비교를 위해 터미널과 함께 디버거를 사용한 모습을 확인 할 수 있는데, '아래'인 터미널은 console.log()로 일일히 작성해야 하는 반면, 스크롤도 필요하며, 다양한 객체를 조회하는데 매우 제한적입니다. 반대로 왼쪽 활성화된 디버거는 동일한 정보를 확인 할 수 있음에도, 접힌형태(토글)로 '어디에 무엇이' 있는지 훤히 눈이되어 확인 할 수 있게끔 도와줍니다. 

디버거를 적극 활용했을 때 제작 난이도와 작업 소요 시간이 대폭 줄어드는 효과를 한장의 스크린샷으로나마 쉽게 예측 할 수 있습니다.

대표적인 '느린 보상', '빠른 이해'의 항목에 해당하기에 '습관 형성'이 상당히 중요합니다. 복잡한 구조를 다루어 멋진 애플리케이션을 만들 기본기를 탄탄히 진행하시기 바랍니다.