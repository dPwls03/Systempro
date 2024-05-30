## 명령어 코드 구현하기

### cat

#### cat - 파일의 내용을 화면에 출력

<img width="800" src="./img/cat1.png" alt="cat" >

#### cat -n - 모든 라인 앞에 라인 번호를 출력

<img width="800" src="./img/cat2.png" alt="cat" >

#### cat -b - 비어있지 않은 라인 앞에만 라인번호를 출력

<img width="800" src="./img/cat3.png" alt="cat" >

#### cat -E - 라인의 마지막과 비어있는 라인에 '$' 기호를 출력

<img width="800" src="./img/cat4.png" alt="cat" >

#### cat -T - 탭 문자를 '^I' 표시로 바꿔서 출력

<img width="800" src="./img/cat5.png" alt="cat" >

#### cat -A - 라인의 마지막과 비어있는 라인에 '$' 기호 출력, 탭 문자는 '^l' 로 바꿔서 출력

<img width="800" src="./img/cat6.png" alt="cat" >

#### cat -s - 두 번 이상 연속된 빈 라인은 출력하지 않음

<img width="800" src="./img/cat7.png" alt="cat" >

<hr>

### head

#### head - 파일의 앞 10줄을 출력

<img width="800" src="./img/head1.png" alt="head" >

#### head -v - 파일명을 출력하고  파일 내용의 앞 10줄을 출력

<img width="800" src="./img/head2.png" alt="head" >

#### head -q - 파일명을 출력하지 않고 파일 내용의 앞 10줄을 출력

<img width="800" src="./img/head3.png" alt="head" >

#### head -n 숫자 - 지정한 숫자 만큼의 행을 출력

<img width="800" src="./img/head4.png" alt="head" >

<hr>

### chmod

#### chmod - 파일의 권한을 설정

<img width="800" src="./img/chmod.png" alt="chmod" >

<hr>

### cp

#### cp - 파일을 복사

<img width="800" src="./img/cp.png" alt="cp" >

<hr>

### pwd

#### pwd - 현재 위치한 경로를 절대 경로로 출력

<img width="800" src="./img/pwd.png" alt="pwd" >

<hr>

### mkdir

#### mkdir - 디렉토리를 생성

<img width="800" src="./img/mkdir1.png" alt="mkdir" >

#### mkdir -v - 디렉토리를 생성하고 생성된 디렉토리에 대한 메시지 출력

<img width="800" src="./img/mkdir2.png" alt="mkdir" >

<hr>

### nl

#### nl - 텍스트 파일의 각 줄에 줄 번호를 붙여 출력

<img width="800" src="./img/nl.png" alt="nl" >

<hr>

### rm

#### rm - 파일을 제거

<img width="800" src="./img/rm1.png" alt="rm" >

#### rm -d - 비어있는 디렉토리를 제거

<img width="800" src="./img/rm2.png" alt="rm" >

<hr>

### rmdir

#### rmdir - 빈 디렉토리 삭제

<img width="800" src="./img/rmdir1.png" alt="rmdir" >

#### rmdir -v - 빈 디렉토리 제거 후 삭제 되었다는 메시지를 출력

<img width="800" src="./img/rmdir2.png" alt="rmdir" >

<hr>

### tail

#### tail - 파일의 마지막 10줄을 출력

<img width="800" src="./img/tail1.png" alt="tail" >

#### tail -v - 파일명을 출력하고 파일의 마지막 10줄을 출력

<img width="800" src="./img/tail2.png" alt="tail" >

#### tail -q - 파일명을 출력하고 파일의 마지막 10줄을 출력

<img width="800" src="./img/tail3.png" alt="tail" >

#### tail -n 숫자 - 입력받은 라인 수 만큼 파일의 마지막 부분에서 출력

<img width="800" src="./img/tail4.png" alt="tail" >

<hr>

### touch

#### touch - 파일의 접근시간과 수정 시간을 현재 시간으로 업데이트

<img width="800" src="./img/touch1.png" alt="touch" >

#### touch -a - 파일의 접근시간을 현재 시간으로 업데이트

<img width="800" src="./img/touch2.png" alt="touch" >

#### touch -m - 파일의 수정시간을 현재 시간으로 업데이트

<img width="800" src="./img/touch3.png" alt="touch" >

#### touch -d - 지정한 시간으로 접근시간과 수정시간을 업데이트(string으로 data를 입력받는다.)

<img width="800" src="./img/touch4.png" alt="touch" >

#### touch -c - 존재하지 않는 파일을 수정하려해도 새로운 파일을 생성하지 않는다.

<img width="800" src="./img/touch5.png" alt="touch" >
