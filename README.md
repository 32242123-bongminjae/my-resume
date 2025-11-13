> # 자기소개서

## 🙋‍♂️ About Me 

* **이름:** [봉민재]
* **소속:** [단국대학교(죽전) SW 융합대학]
* **전공:** [컴퓨터 공학과]
* **학번:** [32242123]
* **Email:** [bongminga@dankook.ac.kr](mailto:bongminga@dankook.ac.kr)
* **GitHub:** [github.com/32242123-bongminjae](https://github.com/32242123-bongminjae)

<br>

## 자기 소개
 * 코딩 과정 자체에서 즐거움을 느끼며, 문제 해결을 위해 몰입하는 것을 좋아하는 개발자입니다.
 * 현재 게임 제작에 큰 흥미를 느끼고 있으며, 다양한 팬게임 및 인디게임 제작 프로젝트에 참여하며 경험을 쌓고 있습니다.
 * 프로젝트의 전반적인 과정을 계획하고, 주도적으로 팀을 이끌어 나가는 역할에 관심이 많습니다.
 * 팀원들과의 원활한 소통을 중요하게 생각하며, 긍정적인 분위기에서 협업하는 것을 선호합니다.

<br>

##  🛠️ 기술 스택
| Category | Skills |
| :---: | :---: |
| Backend | `Java`, `Django` |
| Programming Languages | `C`, `C++`, `Python` |
| Database | `MySQL` |
| DevOps & Tools | `Docker`, `Git`, `Unity` |

<br>

## 프로젝트 경험
### 1. [PyketMon] (2024.03 ~ 2024.06)

* **[Pygame 라이브러리를 활용하여 2D로 구현한 포켓몬 게임]**
* **개발 인원: 1인**
* **프로젝트 시연:** [링크](https://youtu.be/WwdN-Gt5KyE)
* **주요 기능:**
    * Pygame을 이용한 플레이어 조작 및 프레임별 애니메이션 구현
    * 텍스트 파일을 활용한 맵 충돌(Blocking) 및 포켓몬 스폰 필드 구현
    * 포켓몬의 종족값, 현재 HP, 몬스터볼 종류를 반영한 포획 확률 시스템 구현
    * SkillData(별도 데이터) 연동을 통한 레벨별 스킬 습득 기능
    * 포켓몬 타입(Type) 상성을 적용한 데미지 계산 (0.25배 ~ 4배)
    * Quest 진행도에 따른 이벤트 관리 시스템 구현
    * 스위칭, 아이템, 공격, 도망 기능이 포함된 턴제 배틀 시스템 구현
* **사용 기술 (Tech Stack):**
    * `Python`, `Pygame`
* **성과 및 배운 점:**
    * `Pygame` 라이브러리를 이용한 2D 게임 개발 전체 프로세스 학습
    * 확장성을 고려한 플레이어, 포켓몬, 맵 데이터 등을 객체화하여 관리하는 방식 시도
    * 텍스트 파일을 읽어와 게임 환경을 구성하는 데이터 기반 설계 경험
* **저장소 (Repository):**
    * **GitHub:** [링크](https://github.com/32242123-bongminjae/PoketMon_Python)

### 2. [Django 프로젝트 평점 및 랭킹 웹사이트] (2024.09 ~ 2024.12)

* **[Django와 Docker를 활용한 프로젝트 평점 및 랭킹 시스템 구축]**
* **개발 인원:** 1인
* **프로젝트 시연:** [링크](https://youtu.be/u4lNGH20zSM)
* **주요 기능:**
    * Django `models.py`를 통한 'Project' 및 'Rating' 데이터베이스 모델링
    * Django 기본 User 모델을 연동한 사용자 로그인/회원가입 기능 (`@login_required` 적용)
    * `views.py`에서 POST 요청을 처리하여 사용자의 프로젝트 평점(score) 제출 기능 구현
    * `models.py` 내 `average_rating` 메서드를 통한 프로젝트별 평균 평점 계산
    * `admin.py` 커스터마이징을 통해 관리자 페이지에서 프로젝트 랭킹 확인 기능
    * `Dockerfile` 및 `docker-compose.yml`을 이용한 Django 애플리케이션 컨테이너화
* **사용 기술 (Tech Stack):**
    * `Django`, `Docker`, `Python`, `SQLite`
* **성과 및 배운 점:**
    * Django를 활용하여 '평점' 및 '랭킹' 같은 복합적인 비즈니스 로직을 직접 설계하고 구현한 경험
    * Docker를 통해 Django 프로젝트를 컨테이너화하여 개발 환경을 격리하고, 배포 과정을 표준화하는 방법 학습
    * Django의 ORM을 사용해 Python 코드로 데이터베이스를 정의하고 관리하는 능력 습득
    * 사용자 인증과 POST 폼 처리를 통한 풀스택 웹 애플리케이션 개발 프로세스 경험
* **저장소 (Repository):**
    * **GitHub:** [링크](https://github.com/32242123-bongminjae/Django)

### 3. [SW 3D FPS Game] (2025.03 ~ 2025.06)

* **[Unity와 Opensource를 통해 개발한 3D FPS RogueLike 게임]**
* **개발 인원:** 3인
* **프로젝트 시연:** [링크](https://youtu.be/I2ObJfuQAIA)
* **주요 역할 (My Role):**
    * 플레이어 캐릭터 컨트롤러 (이동, 점프) 및 애니메이션 연동
    * 몬스터 AI 기믹 구현 (사망 시 독가스 생성 패턴)
    * Unity 물리 엔진 기반 충돌(Collider) 설정 및 버그 디버깅
    * **Git & GitHub를 활용한 팀 협업 및 버전 관리 (충돌 해결)**
    * 프로젝트 초기 기획 및 개발 일정 관리
    * **Unity Particle System**을 활용한 인게임 이펙트(VFX) 제작 (독가스, 수류탄, 피격)
    * 최종 결과물 발표
* **사용 기술 (Tech Stack):**
    * `Unity`, `C#`, `Git`, `GitHub`
* **성과 및 배운 점:**
    * Git/GitHub 기반의 3인 팀 협업 프로세스(버전 관리, 충돌 해결)를 처음으로 경험
    * Unity Particle System 및 Fog를 이용한 3D 환경 및 VFX 제작 기술 습득
    * Opensource 라이센스에 대한 공부 및 활용 방법을 경험
* **저장소 (Repository):**
    * **GitHub:** [링크](https://github.com/32242123-bongminjae/SWOpenSource)
<br>
