## Class0430 수업 정리

### 수업내용

<img width="800" src="./img/class.jpg" alt="file system" >
<p>표준 유닉스 파일 시스템은 부트 블록, 슈퍼 블록, i-리스트, 데이터 블록 부분으로 구성된다.</p>
<p>커널 내에 파일 디스크립터 배열, 파일 테이블, 동적 i-노드 테이블등의 자료구조를 사용한다.</p>
<p>디렉터리는 파일을 관리, 파일의 연관된 것들의 집합이다. 파일의 내용이 저장되고 파일의 형식 영역으로 관리한다.</p>
<p>파일은 바이트의 연속이다.</p>
<p>디렉터리는 일련의 디렉터리 엔트리들을 포함하고 각 디렉터리 엔트리는 파일 이름과 그 파일의 i-노드 번호로 구성된다.</p>

<img width="800" src="./img/list1.jpg" alt="file system" >
<p>list1.c 코드</p>
<img width="800" src="./img/list1start.jpg" alt="file system" >
<p>list1.c 실행</p>

<img width="450vw" src="./img/list21.jpg" alt="file system" ><img width="450vw" src="./img/list22.jpg" alt="file system" >
<p>list2.c 코드</p>

<img width="800" src="./img/link.jpg" alt="file system" >
<p>link.c 코드</p>

<img width="800" src="./img/unlink.jpg" alt="file system" >
<p>unlink.c 코드</p>

<img width="800" src="./img/symlink.jpg" alt="file system" >
<p>symlink.c 코드</p>

<img width="800" src="./img/rlink.jpg" alt="file system" >
<p>rlink.c 코드</p>