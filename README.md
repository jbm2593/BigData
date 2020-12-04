>공공데이터포털에서 제공하는 농수축산물 데이터를 이용하여 전국의 농수축산물 가격을 조사하여 시각화 하였습니다.

## 1. Environment

- VirtualBox(Master Server, Slave Server)
- Ubuntu
- Notepad++
- Putty
- Hadoop Framework
- Apache Spark
- Apache Zepplin

## 2. 실행 순서

#### 1. 하둡 시작: start-all.sh
#### 2. 스파크 시작: $SPARK_HOME/sbin/start-all.sh
#### 3. 스파크 셀 시작: $SPARK_HOME/bin/spark-shell --master yarn
#### 4. 제플린 서버 시작: $ZEPPELIN_HOME/bin/zeppelin-daemon.sh start
#### 5. 제플린 종료: $ZEPPELIN_HOME/bin/zeppelin-daemon.sh stop
#### 6. 스파크 종료: $SPARK_HOME/sbin/stop-all.sh
#### 7. 하둡 종료: stop-all.sh

## 3. 전국의 농수축산물 가격조사비교

<img src="https://user-images.githubusercontent.com/54352373/101183277-a7024100-3692-11eb-9e8b-88abb7ec7b26.PNG" width="700" height="370">
<img src="https://user-images.githubusercontent.com/54352373/101183302-af5a7c00-3692-11eb-8895-110fb82ec788.PNG" width="700" height="370">
