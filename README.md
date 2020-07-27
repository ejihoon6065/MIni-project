<기본 환경설정 문제>

Java 환경 구현시 오류가 발생가능(컴파일 버젼과 실행 버젼이 맞지 않는 등.)

konlpy 설치 문제 관련


내 컴퓨터 - 우클릭 - 환경변수 설정에서 자바 경로 설정해줘야 함

<jvm.py>

def init_jvm 아래

jvmpath = 'C:/Program Files/Java/jdk1.8.0_261/jre/bin/server/jvm.dll'


<_jvmfinder.py>

def _get_from_java_home : 아래

java_home = "C:/Program Files/Java/jdk-14.0.2"

C:\Program Files\Java\jdk1.8.0_261\jre\bin\server;jvm.dll





<오류 유형 1>

jvm.dll이(가) 없어 프로그램을 시작할 수 없습니다 


R programming 뿐 만 아니라 jvm.dll을 path로 접근하는 모든 프로그램은

jvm.dll로 접근하기 위한 path 환경설정이 제대로 안되어 있을 때,

이러한 에러를 출력합니다.


이런 에러의 이유는 다음 두가지입니다.
1. JAVA를 설치하지 않으셨을 때.
2. JAVA를 설치했지만, PATH 환경변수에 jvm.dll 위치를 등록하지 않으셨을 때.





