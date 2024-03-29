# [목차]
 01. 게임명
 02. 컨셉
 03. 관련 이미지
 04. 대표 이미지
 05. 컨셉, 대표 이미지 묘사
 06. 게임 구성 요소
 07. 게임 시스템 디자인<br>
     7-1. 게임 오브젝트 모델<br>
     7-2. 파라미터 분석<br>

# 01. 게임명: 매직마니아
게임명은 매직 마니아입니다. 마법을 뜻하는 매직과 애호가를 뜻하는 마니아를 합한 이름입니다.
다양한 마법을 사용하며 강화하거나 서로 조합하는 게임의 컨셉을 나타냅니다

# 02. 컨셉
## 메인컨셉: 핵앤 슬래쉬
  ○ 몰려오는 적들을 모아서 스킬로 처치하는 재미
### 서브 컨셉 1: 스킬 조합
  ○ 여러 태그들의 조합으로 다양한 효과의 스킬을 조합할 수 있음
### 서브 컨셉 2: 간편한 조작
  ○ 게임을 처음 해본 사람도 쉽게 숙달해 즐길 수 있게함.<br>
  ○ 키보드 (혹은 조이스틱) 로 이동, 마우스 방향으로 스킬 사용.
  
 # 03.관련 이미지
 ![image](./img/ConceptImage.png)
컨셉 예시

# 05. 컨셉, 대표 이미지 묘사
### 대표이미지 기반
키보드로 이동하며 좌,우,스페이스바 키로 스킬을 사용하여 플레이어에게 달려드는 적들을 쓰러트리는 게임
### 컨셉 기반
플레이어는 여러 태그를 조합해서 다양한 스킬을 선택하고 체험하는 재미를 느낄 수 있도록 함.

#  06. 게임 구성 요소
### 메커니즘
몰려오는 적들을 스킬을 사용하여 공격
보스 몹을 쓰러트리면 새로운 스킬 해금
몹들을 쓰러트리면 포션 충전
### 스토리
원인 모를 재앙을 막는 마법사 스토리
스토리보다 게임 플레이 중점

# 07. 게임 시스템 디자인
## 7-1. 게임 오브젝트 모델
### 플레이어 모델
![image](./img/playerModel.png)
### 적 모델
![image](./img/spiderModel.png)
### 기본 스킬
![image](./img/missile.png)
### 방사형 스킬
![image](./img/thower.png)
### 폭발 이펙트
![image](./img/explosion.png)
## 7-2. 파라미터 분석
### 플레이어 파라미터
![image](./img/playerParam.png)

### 적 파라미터
![image](./img/mosterParam.png)

### 기본 스킬 파라미터
![image](./img/skillParam.png)

## 7-4. 오브젝트 상태
### 플레이어 상태
![image](./img/playerState.png)

### 적 상태
![image](./img/monsterState.png)
