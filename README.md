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

**팀 프로젝트 · 클라이언트 프로그래머 · 5인 팀**  
`2024.08 ~ Present`

BIC Festival, INDIECRAFT, BEAVER ROCKS 선정과 실제 출시를 경험한 팀 프로젝트입니다.  
**Player 액션과 Enemy / Boss 전투를 중심으로 게임플레이 핵심 시스템을 설계하고 구현했습니다.**

### 주요 개발

- **Player FSM** — State Pattern 기반 FSM으로 `Idle / Run / Jump / Fall / Dash / Skill` 상태의 행동과 전이 책임 분리
- **Generic EventBus** — Player / Enemy / UI 간 직접 참조를 줄이고 이벤트 기반 통신 구조 구현
- **Enemy / Boss Combat** — `BaseEnemy` 기반 공통 로직과 적별 AI, Boss 전투 패턴 구현
- **Object Pooling** — Projectile / Effect 등 반복 생성 오브젝트를 재사용하여 생성·삭제 비용 감소
- **Unity Input System** — `Player / UI / TimingCommand` Action Map을 분리하고 Keyboard / Gamepad 입력 통합

### 성과 및 출시

- 🏆 **INDIECRAFT 2026 챌린저 부문 선정**
- 🏆 **BIC Festival 2025 루키부문 선정**
- 🏆 **BEAVER ROCKS 2025 온라인 선정**
- 🎮 **STOVE 출시**
- 🎮 **Steam Demo 출시**

### 링크

[Repository](https://github.com/dudgh7052/Understander) ·
[Gameplay Video](https://youtu.be/NLIcGpjQTtA?si=hyCTPXRmZhicE5su) ·
[STOVE](https://store.onstove.com/ko/games/101948) ·
[Steam](https://store.steampowered.com/app/4519300/Understander_Demo/)

---

## 🎮 주요 프로젝트

### DestinyBoard

<img src="./assets/projects/destinyboard.gif" width="85%">

**졸업작품 · 클라이언트 프로그래머 · 6인 팀**  
`2025.09 ~ Present`

NodeCanvas의 Behavior Tree를 활용해  
**Enemy / Boss AI와 전투 패턴을 중심으로 전투 시스템을 설계하고 구현한 졸업작품입니다.**

### 주요 개발

- **Behavior Tree AI** — NodeCanvas 기반 Behavior Tree로 Enemy / Boss 행동 흐름과 상태 조건 구성
- **Enemy / Boss Combat** — 적 종류별 전투 로직과 Boss 공격 패턴 구현
- **Combat System** — Player와 Enemy 간 공격 / 피격 / 전투 상호작용 구현
- **UI Tween System** — 반복되는 UI 연출을 재사용할 수 있도록 Tween 구조 설계 및 구현

### 링크

[Team Repository](https://github.com/Butterwafle/DestinyBoard)

---

### ColorPop

<img src="./assets/projects/colorpop.gif" width="85%">

**개인 프로젝트 · Modular / Data-Driven Architecture**  
`2026.04 ~ Present`

게임 기능을 독립적으로 확장하고 다른 프로젝트에서도 재사용할 수 있도록  
**Gameplay 로직과 Data, 공통 System의 책임을 분리한 구조를 설계하고 있습니다.**

### 주요 개발

- **Modular Architecture** — Gameplay와 공통 기능을 분리하고 `Pool / Audio / Save / Progress / Scene` 등을 독립적인 System 단위로 구성
- **Data-Driven Ability System** — `AbilityDataSO`와 `AbilityEntity`를 분리하여 Ability 정의 데이터와 런타임 동작을 독립적으로 확장
- **Progression System** — ScriptableObject 기반 강화 노드와 선행 조건을 데이터화하고 영구 진행 저장 및 Stat 강화 구조와 연결
- **Reusable PoolSystem** — Prefab별 Pool 자동 생성과 `PreWarm`, Global / Scene Pool Lifecycle을 지원하는 공통 Pool 구조 구현
- **AudioSystem** — SoundEmitter Pooling과 Builder 구조를 활용해 Sound Data / 재생 / 설정 책임 분리

### 링크

[Repository](https://github.com/dudgh7052/ColorPop)

---

### MazeElf

<img src="./assets/projects/mazeelf.gif" width="85%">

**개인 프로젝트 · 3D 액션**  
`2025.06 ~ 2026.03`

새로운 무기와 공격 방식을 쉽게 추가할 수 있도록  
**ScriptableObject와 다형성을 활용한 확장 가능한 전투 시스템을 설계한 개인 프로젝트입니다.**

### 주요 개발

- **Data-Driven Attack System** — `BaseAttackData`를 기반으로 공격 동작을 추상화하고 `OneShot / Shotgun / ChargeShot` 등 공격 방식을 독립적으로 확장
- **Player Combat FSM** — `Idle / Move / Attack / ChargeAttack / Dodge / Die` 상태로 전투 행동과 상태 전이 책임 분리
- **ScriptableObject Data** — Weapon / Character / Monster / Skill / Stage 데이터를 분리하여 설정 데이터와 런타임 로직의 책임 구분
- **Reusable Object Pool** — Unity ObjectPool 기반으로 Prefab별 Pool을 동적 생성하고 Projectile 등 반복 생성 오브젝트 관리

### 링크

[Repository](https://github.com/dudgh7052/MazeElf)

---

### Lacapium

<img src="./assets/projects/lacapium.gif" width="85%">

**팀 프로젝트 · 클라이언트 프로그래머 · 5인 팀**  
`2021`

팀 단위 개발부터 수상과 모바일 스토어 출시까지 경험한 프로젝트로,  
**게임을 완성하고 실제 플랫폼에 배포하는 전체 개발 과정을 경험한 첫 팀 프로젝트입니다.**

### 주요 개발

- **Game Client Development** — Unity 기반 게임플레이 및 클라이언트 기능 구현
- **Team Development** — 팀원과 기능을 분담하고 프로젝트 통합 및 협업 경험
- **Mobile Release** — Android 빌드 및 모바일 플랫폼 출시 과정 경험

### 성과 및 출시

- 🏆 **Global Game Challenge 2021 동상**
- 🎮 **Google Play 출시**
- 🎮 **ONE store 출시**

### 링크

[Project Video](https://youtu.be/XJTS5xvgCeI?si=fHYrh7iSi9JDA75t)

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
| **ColorCrush** | 2026.02 ~ 2026.04 | ScriptableObject 기반 재사용 가능한 Tween System · Object Pooling · ONE store 출시 |
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
