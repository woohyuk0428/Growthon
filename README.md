# Growthon(프로잭트명 정해지면 변경)
프로그램 언어 및 빌드, 배포 정해지면 README.md 수정하기

## 1. Repository Fork

1. GitHub에서 Project 페이지로 이동합니다.  
   url :  `https://github.com/woohyuk0428/Growthon.com`

2. 페이지 우측 상단의 **Fork** 버튼을 클릭합니다.

3. "Create a new fork" 옵션을 선택하고, **Create Fork** 버튼을 눌러 내 GitHub 계정으로 저장소를 복사합니다.

4. Fork가 완료되면, 내 GitHub 계정에서 Fork된 저장소를 확인할 수 있습니다.  
   예: `https://github.com/내GitHub아이디/Growthon`

---

## 2. Repository Clone

1. 로컬 컴퓨터에서 터미널을 엽니다.  
   - Windows: **CMD**  
   - Mac OS: **Terminal**  

2. 작업할 디렉토리를 만들고 이동합니다:
```bash
mkdir coding
cd coding
git clone https://github.com/내GitHub아이디/Growthon.git
cd Growthon
```

## 3. create Project

1. src 디렉토리 안에 각 파트별 프로젝트 생성
ex)
frontend: 
```bash
react-active-create frontend
cd frontend
```
backend:
src안에 "backend" 로 프로잭트 생성
