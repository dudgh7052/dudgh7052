<div align="center">

# JANG YOUNGHO

### Unity Client Programmer

**확장 가능하고 유지보수하기 좋은 게임 시스템을 설계하는 Unity 클라이언트 프로그래머**

`Unity` `C#` `FSM` `EventBus` `ScriptableObject` `Object Pooling`

</div>

---

## 🏆 수상 및 선정

<table>
<tr>
<td width="25%" align="center">
<img src="./assets/awards/indiecraft.png" width="140">
<br>
<b>INDIECRAFT 2026</b>
<br>
<sub>Understander · 챌린저 부문 선정</sub>
</td>

<td width="25%" align="center">
<img src="./assets/awards/bic.png" width="140">
<br>
<b>BIC Festival 2025</b>
<br>
<sub>Understander · 루키부문 선정</sub>
</td>

<td width="25%" align="center">
<img src="./assets/awards/beaverrocks.png" width="140">
<br>
<b>BEAVER ROCKS 2025</b>
<br>
<sub>Understander · 온라인 선정</sub>
</td>

<td width="25%" align="center">
<img src="./assets/awards/ggc-2021.png" width="140">
<br>
<b>Global Game Challenge 2021</b>
<br>
<sub>Lacapium · 동상</sub>
</td>
</tr>
</table>

---

## 🔥 대표 프로젝트

### Understander

<img src="./assets/projects/understander.gif" width="100%">

**Team Project · Client Programmer · 5인 팀**  
`2024.08 ~ Present`

BIC, INDIECRAFT, BEAVER ROCKS 선정 및 입상, 실제 출시까지 경험한 팀 프로젝트입니다.  
**Player 액션과 Enemy / Boss 전투를 중심으로 게임플레이 핵심 시스템을 설계하고 구현했습니다.**

### 주요 개발

- **Player FSM** — State Pattern 기반 FSM으로 `Idle / Run / Jump / Fall / Dash / Skill` 상태의 행동과 전이 책임 분리
- **Generic EventBus** — Player / Enemy / UI 간 직접 참조를 줄이고 이벤트 기반 통신 구조 구현
- **Enemy / Boss Combat** — `BaseEnemy` 기반 공통 로직과 적별 AI, Boss 전투 패턴 구현
- **Object Pooling** — Projectile / Effect 등 반복 생성 오브젝트를 재사용하여 생성·삭제 비용 감소
- **Unity Input System** — `Player / UI / TimingCommand` Action Map 분리 및 Keyboard / Gamepad 입력 통합

### 성과 및 출시

- 🏆 **2026 INDIECRAFT 챌린저 부문 선정**
- 🏆 **BIC Festival 2025 루키부문 선정**
- 🏆 **BEAVER ROCKS 2025 온라인 선정**
- 🎮 **STOVE 출시**
- 🎮 **Steam Demo 출시**

### 링크

[Repository](https://github.com/dudgh7052/Understander) ·
[STOVE](https://store.onstove.com/ko/games/101948) ·
[Steam](https://store.steampowered.com/app/4519300/Understander_Demo/)

---

## 🎮 주요 프로젝트

### DestinyBoard

<img src="./assets/projects/destinyboard.gif" width="85%">
</div>

**Graduation Project · Client Programmer · 6인 팀**  
`2025.09 ~ Present`

NodeCanvas의 Behavior Tree를 활용해 **Enemy / Boss AI와 전투 시스템을 설계하고 구현한 졸업작품**입니다.

### 주요 개발

- NodeCanvas Behavior Tree 기반 Enemy / Boss AI 구현
- Enemy 및 Boss별 전투 로직과 공격 패턴 구현
- Player와 Enemy 간 Combat System 구현
- 반복적으로 활용할 수 있는 UI Tween 구조 설계 및 구현

`Behavior Tree` `Enemy AI` `Combat System` `UI Tween`

### 링크

[Team Repository](https://github.com/Butterwafle/DestinyBoard)

---

### MazeElf

<img src="./assets/projects/mazeelf.gif" width="85%">
</div>

**Personal Project · 3D Action**  
`2025.06 ~ 2026.03`

새로운 무기와 공격 방식을 쉽게 추가할 수 있는 **확장 가능한 전투 시스템 설계**를 목표로 제작한 개인 프로젝트입니다.

### 주요 개발

- Player / Enemy FSM 기반 상태 및 행동 관리
- ScriptableObject 기반 Weapon / Attack 데이터 구조 설계
- OneShot / Shotgun / ChargeShot 등 다양한 공격 방식 확장
- Object Pooling 기반 Projectile 생성 및 반환 관리
- Stage / Sound / Save 등 게임 진행 시스템 구현

`FSM` `ScriptableObject` `Object Pooling` `Unity Input System`

### 링크

[Repository](https://github.com/dudgh7052/MazeElf)

---

### ColorPop

<img src="./assets/projects/colorpop.gif" width="85%">
</div>

**Personal Project · Modular / Data-Driven Architecture**  
`2026.04 ~ Present`

게임 기능을 독립적으로 관리하고 재사용할 수 있도록  
**공통 시스템을 모듈화하고 ScriptableObject 기반의 Data-Driven 구조를 적용한 프로젝트입니다.**

### 주요 개발

- Character / Ability / Monster / Stage 데이터를 ScriptableObject로 구조화
- Gameplay / Stage / UI / Data 영역을 역할과 책임에 따라 분리
- Ability / Progression 시스템을 데이터 기반으로 확장 가능하게 설계
- PoolSystem을 분리한 재사용 가능한 Object Pooling 구조 구현
- Audio 재생 / 설정 / Sound Data의 책임을 분리한 AudioSystem 모듈화

`Modular Architecture` `ScriptableObject` `Data-Driven Design` `Object Pooling`

### 링크

[Repository](https://github.com/dudgh7052/ColorPop)

---

### Lacapium

<img src="./assets/projects/lacapium.gif" width="85%">
</div>

**Team Project · Client Programmer · 5인 팀**  
`2021`

팀 단위 개발부터 수상과 모바일 스토어 출시까지 경험한 프로젝트로,  
**게임을 실제 완성하고 배포하는 전체 개발 과정을 경험한 첫 팀 프로젝트입니다.**

### 주요 개발

- Unity 기반 게임 클라이언트 기능 개발
- 팀원과의 기능 개발 및 프로젝트 통합
- 모바일 플랫폼 빌드 및 출시 경험

### 성과 및 출시

- 🏆 **Global Game Challenge 2021 동상**
- 🎮 **Google Play 출시**
- 🎮 **ONE store 출시**

### 링크

[Project](https://youtu.be/XJTS5xvgCeI?si=fHYrh7iSi9JDA75t)

---

## 🛠 기술 스택

| Category | Skills |
|---|---|
| **Engine / Language** | Unity · C# |
| **Architecture / Patterns** | FSM · EventBus · Behavior Tree · Data-Driven Design · Object Pooling |
| **Unity Systems** | ScriptableObject · Input System · Cinemachine · Timeline · Localization · AudioMixer |
| **Libraries** | DOTween · NodeCanvas |
| **Version Control** | Git · GitHub |

---

## 📂 기타 프로젝트

| Project | Period | Main Focus |
|---|---|---|
| **ColorCrush** | 2026.02 ~ 2026.04 | ScriptableObject 기반 재사용 가능한 Tween 시스템 · Object Pooling · ONE store 출시 |
| **ArcherProject** | 2024.08 ~ 2025.07 | Swipe / Touch Input · Player FSM · Skill System · Object Pooling |

---

## 🎓 학력

**동양대학교 게임학부**  
`2021.03 ~ 2027.02 졸업예정`

---

## 📜 자격증

**정보처리기능사**  
`2019.11.07`

---

## 📫 연락처

**장영호 · JANG YOUNGHO**  
Unity Client Programmer

Email · `wkd7052@gmail.com`  
GitHub · [github.com/dudgh7052](https://github.com/dudgh7052)
