## 한글 - 영어 오타 변환기
- 문서 작업시 한영 설정이 반대로 된 경우, 잘못입력된 텍스트를 수정하지 않고 자동으로 변환하기 위한 프로그램 (최대 약 5000자)

### 1. 동작

![한영변환기](https://github.com/user-attachments/assets/c52253de-5f9c-451d-accd-67f32d13cea1)

### 2. 사용법
- 실행파일을 원하는 곳에 저장한다.
- 바탕화면에서 실행파일의 바로가기를 생성하고, 파일의 속성에서 단축키를 설정해 사용한다.
- 단축키 입력후, 변환할 텍스트를 선택하면 약간의 딜레이 후 텍스트가 변환된다.
  
### 3. 개선점
- 변환시 딜레이가 있다.
- 변환할 텍스트 입력을 포커스된 창을 통해서가 아닌 클립보드를 통해 받아오므로 비효율적이다.
  - 단축키를 입력 후 텍스트를 선택해야한다.(타이밍이 맞지 않으면 변환이 일어나지 않을수 있다.) 

### 4. 개발
- c++
- Visual Studio
