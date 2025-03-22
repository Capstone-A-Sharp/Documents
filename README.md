
# Capstone Design Documents
2024 가을학기 - 2025 봄학기 임베디드시스템공학과 캡스턴 디자인 발표 자료 및 보고서용 레포지토리
<br>
## 🔸 주제
### 🔹 메인 기능
- 사람이 걷는 속도에 맞춰서 한 걸음 내딛을 때마다 함께 움직이는 보행기
- 핸들에 부착된 압력센서를 통해 저항값을 기준으로 모터 제어
    - 각 핸들에 압력센서를 8개 정도 달아서 미는 것과 꽉 잡는 것, 당기는 것을 판별
- 영상처리를 통해서 핸들 압력과 이동속도 간의 상관관계 파악
    - 핸들 압력을 통한 모터 구동의 보정용도로 영상처리를 활용
    - 상시 동작 X , 보행기 충전 시 녹화된 영상을 통해 영상처리 진행 -> 전력 최소화
### 🔹 서브 기능
- 보폭 분석 후 이상 징후, 보폭 속도 및 걸음 습관 데이터 집계해서 시각화하기
- 손잡이 길이를 마음대로 정할 수 있도록 변경
- 브레이크 및 비상 정지 버튼 추가
- 야간을 대비하는 라이트 추가
<br>

## 🔸 Git Convention
## 🔹 Commit Message 컨벤션
Gitmoji [type] :comment

### ✔ Type
- ✨ Add : REAME.md, 파일(발표자료, 보고서) 업로드
- ♻️ Refactor : 레포지토리 구조 및 내용 수정  
- 💡 Chore : 그 외 기타 작업    

Ex) ✨[Add] : 240913 발표자료 업로드

## 🔹 Branch 컨벤션
- branch 이름 : type/이슈번호
    - ex) Add/1
- branch 생성 후 Issue 연동 필수
- branch 생성 후 local에서 해당 브랜치로 checkout 후 작업 진행

## 🔹 PR 컨벤션
- PR 제목 : [branch이름] 제목
    - ex) [Add/1] 24년도 9월 2주차 발표자료 업로드
- PR description은 특별한 경우가 아닐 경우 간단하게 작성
- Reviewers에 전 팀원 지정 
- Assigness에 본인 지정
- Development에 Issue 연동
- PR Merge는 모든 팀원의 리뷰가 끝났을 경우 팀장이 진행

<br>

## 🔸 Directory 구조
```
└── 📂발표자료
    ├── 📂00년00월00주차 
    │   └── 💾A#_YYMMDD_발표자료.pptx
    ├── 📂...  
    └── 📂00년00월00주차 
└── 📂보고서
    ├── 📂00년00월00주차 
    │   └── 💾A#_YYMMDD_보고서.pdf
    ├── 📂...  
    └── 📂00년00월00주차 
└── ...
```
<br>

## 🔸 참여자
|<img src="https://avatars.githubusercontent.com/u/132703437?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/105117441?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/91868155?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/141633727?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|:-:|
|김준범<br/>[@doodoodi](https://github.com/doodoodi)|이진성<br/>[@Bina-Lee](https://github.com/Bina-Lee)|이효림<br/>[@rimi3226](https://github.com/rimi3226)|박소윤<br/>[@psy1218](https://github.com/psy1218)|
<br/>

