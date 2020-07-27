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
