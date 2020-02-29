# Diray

## 'Diary'는 왜 만드는가?
- 크리스찬으로서 생활하는 하루 하루를 기록하기 위하여 만든다.

## 어떤 기능이 있는가?

### 유저
 - 회원가입
 - 프로필
 - local 로그인
 - google 로그인
 - github 로그인

### 바이블
 - 역본별 성경
 - 검색
 - 음성 (tts)

### 커스텀 노트
 - 자유로운 필드 사용으로 필드에 대한 set을 만들어서 등록하면 다른 사용자도 그 양식으로 활용하여 노트를 작성할 수 있는 형식으로 구현
 - 개인이 만든 양식을 공개 비공개 설정 가능
 - CSS와 같은 디자인 요소에 대한 세팅도 고려중
 - 추후 개인의 양식을 특정인에게만 줄 수 있음
 - 양식을 수정시마다 버젼이 새로 셍성하는 방식으로 기존에 양식을 받은 사용자가 양식이 갑자기 변경되는 상황을 겪지 않도록 한다

### 스케줄러, 투두 리스트
 - 일간, 월간, 연간 스케줄러를 제공하고
 - 작성된 TODO들을 일간, 월간, 연간으로 제공하며
    어제 마무리 하지 못한 TODO 도 미완료된 TODO로 제공

### 북마크
 - URL 기반으로 북마크를 저장하며 이름과 대표 이미지를 수정할 수 있도록 제공
 - 북마크 저장시 해당 페이지를 크롤링하여 해당 페이지 내의 컨텐츠를 저장
 - 북마크된 크롤링 컨텐츠의 내용을 기반으로 검색이 가능하도록 제공

### 녹음기
 - 녹음 기능을 제공하고
 - 파일관리 시스템을 적용
 - 음성파일을 들을 수 있는 Custom Player 구현
 - 음성 녹음시 Speach to Text로 음성을 텍스트로 변환하여 저장 관리
 - STT를 자막으로 활용하여 제공 (다국어 변환 기능 추가)
 - 폴더 별로 안에 있는 음성 파일들을 플레이이 리스트로 제공


