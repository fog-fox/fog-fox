<div align="center"><h2> Hi there 👋

I'm Unity Game Developer🎮
</h2>


  
🐣 저는 거대한 육각형 개발자을 목표로 성장해가는 아직은 작은 개발자입니다 🥚
  
🎲 사람과 사람을 연결하고, 즐거운 시간을 남기고, 가끔은 감동을 전할 수 있는 게임을 만들기 위해 노력하고 있습니다. 🎲



<h2> 🛠 Tech Stack 🛠 </h2>
<h3> Game Development Tool
  
![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Photon](https://img.shields.io/badge/photon-%23004480.svg?style=for-the-badge&logo=photon&logoColor=white)

Game Design Tool

![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Drawio](https://img.shields.io/badge/drawio-%23F08705.svg?style=for-the-badge&logo=diagrams.net&logoColor=white)
</h3>
</div>

# Featured Projects

## Project Expedition

[**Project-Expedition-Showcase →**](https://github.com/fog-fox/Project-Expedition-Showcase)

공통 실행 구조와 데이터 조합을 중심으로 설계한 게임 시스템 Showcase입니다.

**Key Features**

- Data-Driven Action / Skill Framework
- ScriptableObject와 Runtime Data 분리
- Skill Upgrade / Status / Trigger System
- Procedural Dungeon Generation
- Condition / Sequence / Step 기반 Monster Attack System
- Save Data Integrity & Recovery
- Photon Fusion 기반 Host-Authoritative Multiplayer

```text
Skill / Action Definition
          ↓
    Runtime Data
          ↓
Upgrade / Equipment / Passive
          ↓
   Final Gameplay Action
```

---

## Project-T

[**Project-T-Showcase →**](https://github.com/fog-fox/Project-T-Showcase)

2D Top-Down Tactical Shooter에서 구현한 시야와 전투 시스템 Showcase입니다.

**Key Features**

- 근거리 원형 + 전방 원뿔형 Fog of War
- Wall / Smoke 기반 Line of Sight
- Unexplored / Explored / Visible 상태 관리
- 변경된 Cell만 갱신하는 Visibility Update
- Fog of War와 Smoke System의 상호작용
- 이동·조준·반동 상태를 반영한 Shooting System

```text
Player Vision
     ↓
Line of Sight
  ├─ Wall
  └─ Smoke
     ↓
Visibility State
```

---

## Travelling

[**Travelling-Showcase →**](https://github.com/fog-fox/Travelling-Showcase)

Grid 기반 가구 이동 및 배치 시스템 Showcase입니다.

**Key Features**

- 크기가 다른 가구의 Grid Placement
- 90° Rotation 및 점유 Cell 재계산
- Grid + Physics 기반 Placement Validation
- 가구 위에 다른 가구를 배치하는 Sub Grid
- 책상과 의자를 자연스럽게 연결하는 Chair Snap
- Parent / Child 구조를 이용한 그룹 이동
- Preview / Commit 분리를 이용한 배치 취소 및 상태 복구

```text
Furniture
├─ Floor Grid
├─ Sub Grid
└─ Chair Point
       ↓
Placement Validation
       ↓
Commit / Restore
```

---

## AdventureGame

[**AdventureGame-Showcase →**](https://github.com/fog-fox/AdventureGame-Showcase)

JSON 기반 대화와 선택지를 실제 게임 상호작용으로 연결한 시스템 Showcase입니다.

**Key Features**

- JSON 기반 Dialogue Data
- Runtime Dialogue / Choice UI 생성
- Typewriter Dialogue
- 반복 상호작용에 따른 Dialogue Progression
- Command Pattern 기반 Choice Result 처리
- 선택 결과와 실제 Game Object 상태 연결

```text
Dialogue JSON
      ↓
DialogueManager
      ↓
ChoiceManager
      ↓
CommandFactory
      ↓
Game Interaction
```

---
