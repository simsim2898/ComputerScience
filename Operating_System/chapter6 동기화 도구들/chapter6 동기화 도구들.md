협력적 프로세스는 시스템 내에서 실행 중인 다른 프로세스의 실행에 영향을 주거나 영향을 받는 프로세스이다. 
협력적 프로세스는 논리 주소 공간（즉, 코드 및 데이터) 을 직접 공유하거나 공유 메모리 또는 메시지 전달을 통해서만 데이터를 공유할 수 있다. 그러나 공유 데이터를 동시에 접근하면 데이터의 일관성을 망칠 수 있다. 
이 장에서는 논리 주소 공간을 공유하는 협력적 프로세스의 질서 있는 실행을 보장하여, 이를 통해 데이터의 일관성을 유지하는 다양한 메커니즘을 논의한다.





[[6.1 배경]]
[[6.2 임계구역 문제]]
[[6.3 Peterson의 해결안]]
[[6.4 동기화를 위한 하드웨어 지원]]