#led를 이용한 푸시알림 기능

#개발목적
 생활하면서 문자메세지, 카카오톡, 전화 등 핸드폰 알림이나 집안에서 일어나는 비상 사태에 대해서 인지 하지 못하는 경우가 종종 있다.

필자의 경우 꽤나 심하다 이를 해결 하기 위한 방법으로 보려고 의식 하지않아도 자연스럽게 인식할 수 있는것을 고민하던 중

led전구의 빛은 인식하지 않아도 눈에 보이기 때문에 이를 이용하여 각종 푸시메세지를 led로 표현하면 되겠다고 생각하였다.

#순서

필립스 휴의 스마트 led의 경우 다양한 색상의 빛을 낼 수 있고 hue library를 통해 직접 개발할 수 있다.


1.안드로이드 푸시메세지 분석

2.푸시메세지 활용

3. 브릿지 연결 구현

4. led제어 구현

5. 푸시메세지를 통해 led 제어

6. 어플 보완


#진행상황

현재 전화, 문자 등의 핸드폰 내부에서 오는 신호에 대해서는 led제어가 가능하다.
hue led 색상변화는 1600만가지정도 이지만 현재 어플에서는 실제로 500만 가지정도 표현가능하다.


#앞으로 해결해야할 것들

어플을 설치하여 외부에서 들어오는 푸시 메세지에 대해서는 아직 제어가 불가능하다.
led 제어색상을 1600가지가 가능하도록 한다.
라즈베리파이를 서버로 활용하여 외부ip에서 접속 할수 있도록한다.
라즈베리파이에 센서를 달아서 집안에서 일어날 수 있는 각종 상황에 대해서 알림 기능을한다.
ex) 온도센서를 통해 집안의 온도가 비정상적으로 높아지면 led색이 변한다.







