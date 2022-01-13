1. 분장실
2. 스테이지
3. 메모리카드(사진들)



ls 폴더 파일 리스트
cd change directory
cd .. 하면 올라가기
..가 상위 레벨 상징이고 .가 현재 위치를 상징
touch 파일생성 (띄어쓰기 기준 여러 개 생성 가능)
mkdir 폴더생성
rm 파일 삭제
rm -r 폴더 삭제
pwd present working directory 지금 주소
* 전체, 모든 ex) rm *.txt
.뫄뫄.txt 하면 숨긴다는 의미
-> ls 하면 안 나옴
ls -a 하면 다 나옴
ls -t 하면 생성시간대로 정렬
두개를 섞는다면? ls -at
등등 -뫄뫄 를 옵션이라고 함

$ 뫄뫄 라 적으면 $가 있을 때 적으라는 뜻 $까지 적지 말고
git init 이 폴더를 깃이 관리하는 리포(repo(sitory))로 만들기
rm -rf .git/ 리포를 걍 폴더로 다시 돌려놓기
git config --global user.name 또는 user.email 도장 파기
git add [파일 이름] 스테이지에 올리기 (스테이징된 변경사항에 들어감)
약간 알 거 같아 .이 필요한 이유가 git add . 하면 이 해당 폴더 안 모든 파일을 add 하는 거
git commit -m '뫄뫄' m이 메시지거든 그래서 버전의 이유를 적어두면 댄대 오 그래서 변경된 게 없으면 안 적힘
git log 하면 ㄹㅇcommit log 나옴
git status 현재상황 확인하는 거
