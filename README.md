# Growthon(프로잭트명 정해지면 변경)
프로그램 언어 및 빌드, 배포 정해지면 README.md 수정하기

## 1. Repository Fork

1. GitHub에서 Project 페이지로 이동합니다.  
   url :  `https://github.com/woohyuk0428/Growthon.git`

2. 페이지 우측 상단의 **Fork** 버튼을 클릭합니다.

3. "Create a new fork" 옵션을 선택하고, **Create Fork** 버튼을 눌러 내 GitHub 계정으로 저장소를 복사합니다.

4. Fork가 완료되면, 내 GitHub 계정에서 Fork된 저장소를 확인할 수 있습니다.  
   예: `https://github.com/내GitHub아이디/Growthon.git`

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

## 3. Create Project

1. src 디렉토리 안에 각 파트별 프로젝트 생성

frontend: 
```bash
react-active-create frontend
cd frontend
```
backend:
src안에 "backend" 로 프로잭트 생성

## 4. Project Structure

### 디렉토리 및 파일 설명

#### `src/`
- **소스 코드**가 위치하는 디렉토리입니다. 프로젝트의 모든 기능적인 부분은 여기에서 작성됩니다.
- 일반적으로 서버 코드, API 엔드포인트, UI 컴포넌트 등의 핵심 코드가 이 디렉토리에 포함됩니다.

#### `docs/`
- 프로젝트에 대한 **문서화** 파일들이 포함되는 디렉토리입니다.
- 사용법, API 문서, 설계 문서, 기여 방법 등 프로젝트에 필요한 모든 문서가 이 디렉토리 안에 위치할 수 있습니다.

#### `tests/`
- **테스트 코드**가 위치하는 디렉토리입니다.
- 유닛 테스트, 통합 테스트 등 프로젝트가 올바르게 동작하는지 확인할 수 있는 테스트 코드들이 이 디렉토리에 포함됩니다.

#### `.gitignore`
- Git에서 **무시할 파일 목록**을 정의하는 파일입니다.
- 일반적으로 빌드 파일, 의존성 파일, IDE 설정 파일 등을 포함하여 Git에 추적되면 안 되는 파일을 나열합니다.

#### `README.md`
- 프로젝트에 대한 **설명**을 포함하는 파일입니다.
- 이 파일은 프로젝트를 소개하고, 설치 방법, 사용법, 기여 방법 등을 설명하는 데 사용됩니다.

#### `LICENSE`
- 프로젝트의 **라이선스** 정보를 담고 있는 파일입니다.
- 프로젝트를 사용하거나 기여하려는 사람들이 준수해야 할 라이선스 규정을 명시합니다.


## 5. Commit Convention

깃 프로젝트에서 커밋 메시지는 매우 중요합니다. 명확하고 일관된 커밋 메시지를 사용하는 것이 좋습니다.

feat: 새로운 기능 추가

fix: 버그 수정

docs: 문서 수정

style: 코드 스타일 수정 (로직에 영향 없음)

refactor: 코드 리팩토링 (기능 변경 없음)

test: 테스트 추가/수정

chore: 기타 수정 (빌드 도구, 패키지 관리 등)