## 10월19일 스터디 
* 머신러닝 파워드 애플리케이션 ml-powered-app

*프로젝트 폴더 만들고 가상환경도 만들어 실행 
1. 폴더 생성 
   C:\mkdir ml-powered-app
2. 해당 폴더로 이동한 뒤 가상환경 생성(가상환경 이름= ml_editor)
   C:\ml-powered-app>python -m venv ml_editor
 혹은 C:\ml-powered-app>virtualenv ml_editor -->'virtualenv'은(는) 내부 또는 외부 명령, 실행할 수 있는 프로그램, 또는 배치 파일이 아닙니다. cmd에서 치니 오류 뜸. why
3. 가상환경 활성화 : 가상환경 폴더에 들어간 후 
   C:\ml-powered-app>source ml_editor/bin/activate -->'source'은(는) 내부 또는 외부 명령, 실행할 수 있는 프로그램, 또는 배치 파일이 아닙니다.
 혹은 (Scripts\activate.bat)

 
1. 가상환경 만든 후 가상환경 실행 창에서 (Scripts\activate.bat)
2. 깃허브 클론 git clone https://github.com/rickiepark/ml-powered-applications.git
=> 가상환경을 실행한 상태에서 git clone 했어도 가상환경 폴더 밖에 cloned 폴더가 생김. 맞나? 
3. nltk 설치(pip install nltk)
*nltk 내 자료 다운로드하기 
4.(파이썬 세션 오픈) python
5. import nltk
6. nltk.download('punkt') 
결과 
[nltk_data] Downloading package punkt to
[nltk_data]     C:\Users\hjkim\AppData\Roaming\nltk_data...
[nltk_data]   Unzipping tokenizers\punkt.zip.

질문1 질문1 질문1 
*가상환경 내 python 세션에서 jupyter lab 실행하는 방법 
python -m ipykernel install --user --name ml-powered-app => invalid syntax, ipykernel라고 함. 
혹은 No module named ipykernel

===> ipykernel을 install해야 함

안 되서 아나콘다 프롬프트로 주피터랩 실행했는데, 새로 만든 가상환경이 리스트에 없음.  

---> 주피터랩이나 주피터 노트북은 항상 커널 연결하는 프로세스를 진행해야 하지만 vs-code에서는 필요 없는 것인지? vs-code에서 ml-powered-app 폴더 찾아 연 뒤 새 노트북 만들고 노트북 이름 지정. -> 실행됨 
 

2. 깃허브 클론 git clone https://github.com/rickiepark/ml-powered-applications.git
=> 가상환경을 실행한 상태에서 git clone 했어도 가상환경 폴더 밖에 cloned 폴더가 생김. 맞나? 


2. 해당 폴더로 이동한 뒤 가상환경 생성(가상환경 이름= ml_editor)
   C:\ml-powered-app>python -m venv ml_editor
 혹은 C:\ml-powered-app>virtualenv ml_editor -->'virtualenv'은(는) 내부 또는 외부 명령, 실행할 수 있는 프로그램, 또는 배치 파일이 아닙니다. cmd에서 치니 오류 뜸. why

3. 가상환경 활성화 
   C:\ml-powered-app>source ml_editor/bin/activate -->'source'은(는) 내부 또는 외부 명령, 실행할 수 있는 프로그램, 또는 배치 파일이 아닙니다.

1. cmd 창에서 가상환경 실행 
2. 1이 된 상태에서 vs 코드 실행
3. open folder하고 주로 사용할 폴더를 열음
4. new file 누르고 제목 쓴 뒤 뒤에 .py를 붙임 
 - ch3_ml_editor.py 


=====
10월19일
'new' 버튼
repository name

*계정 연결 
소스트리 켜고 +(뉴탭)
remote
계정추가 
호스팅 서비스 - 깃허브 선택
aught token 새로고침 => 소스트리와 깃허브를 연결
확인(계정 연동 확인)

*repository 연결 
소스트리 
원격 
추가 
remote account == > 설정 
 
깃허브의 repository 주소를 복붙
원격:  repository이름 쓰고 
확인

*파일 올리기 
push 

*repository 삭제하기 
-setting 에서 repository 삭제
