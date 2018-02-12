# HIFLY-Web-View-One
> [HIFLY Final](https://github.com/HIFLY-CSM/HIFLY-Final) 참조

## 사용 법

1. Web Server는 가볍게 사용하기 위해 Apache를 사용한다.

2. WebContent만 이용한다.

3. index.html의 ```<video src="images/2.mp4" id="player" style="position: absolute; top: 0; left: 0; bottom: 0; height: 100%; width: 100%; border: 0;" autoplay controls></video>``` src에 HIFLY-JAVA-SERVER에서 넘겨주는 ffserver url을 넣어주면 된다.
