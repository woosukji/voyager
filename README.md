# 프로젝트 개요
- 시각장애인의 이동권 향상을 위해, 컴퓨터 비전 기술을 통해 전방의 지형지물 및 장애물을 안내하여 안전하게 보행하실 수 있도록 돕는 프로젝트

## 주요기능
- 바닥지형 안내
- - 턱, 경사로, 계단 등 바닥지형 위험요소 안내
- 횡단보도 건너기 보조
- - 횡단보도를 벗어나지 않도록 방향 안내
- 장애물 충돌 위협 감지
- - 케인으로 감지가 힘든 장애물(ex. 난간, 볼라드, 바리케이드, 머리높이 장애물) 감지

## 아키텍처
- AWS EC2 T2.micro + g4.xlarge
- 

# 개발자
- 지우석
- 이동관
- 황주원

<h4>Commit convention rule</h4>

> 1. feat : 새로운 기능 ✨
> 2. fix : 버그 수정 🐛
> 3. build : 빌드 관련 파일 수정 🏗️
> 4. chore : 그 외 자잘한 수정 ✏️
> 5. ci : CI관련 설정 수정 👷
> 6. docs : 문서 수정 📝
> 7. style : 코드 스타일 혹은 포맷 등 💄
> 8. refactor :  코드 리팩토링 ♻️
> 9. test : 테스트 코드 수정 ✅
