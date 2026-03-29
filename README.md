# MoCKA Runtime — Core Execution Engine

<p align="center">
  <img src="https://raw.githubusercontent.com/m-sirius-k/MoCKA/main/docs/images/mocka_overview.svg" width="800">
</p>

> **This is not a task scheduler. Not a cron job. Not a workflow engine.**
> It is the engine that keeps the civilization loop running —
> observation, record, incident, decision, action, audit — continuously.
>
> One entry point. Deterministic execution. Every action recorded.

---

## Position in mocka_Movement

<p align="center">
  <img src="https://raw.githubusercontent.com/m-sirius-k/MoCKA/main/docs/images/mocka_architecture_v2.svg" width="720">
</p>
```
MoCKA (core · heart)
      ↓
mocka-knowledge-gate       ② Record
      ↓
mocka-transparency         ③ Incident · ④ Recurrence
      ↓
mocka-external-brain       ⑥ Decision
      ↓
[ mocka-runtime ]          ← ⑦ Action — YOU ARE HERE
      ↓
mocka-civilization         ⑧ Institutionalize
```

**Loop step: ⑦ Action**
Upstream: mocka-external-brain → sends decisions
Downstream: MoCKA core → ledger records the execution

---

## What this repository does

<p align="center">
  <img src="https://raw.githubusercontent.com/m-sirius-k/MoCKA/main/docs/images/mocka_loop_v2.svg" width="720">
</p>

mocka-runtime drives the entire civilization loop
from a single deterministic entry point.

### Five Engine Architecture

| Engine | Role |
|---|---|
| Runtime | Drives the execution loop |
| Observatory | Monitors system state |
| Knowledge Core | Manages knowledge accumulation |
| Storage | Persists all events |
| Audit | Verifies every execution |

### Civilization Stage Progression
```
Primitive → Organized → Mature → Advanced → AGI-Aligned
```

The runtime tracks which stage the civilization has reached.
Every loop cycle advances the stage.

### Single Entry Point
```
All operations enter through one gate
      ↓
No side effects
No hidden execution paths
No unrecorded actions
      ↓
Every execution is reproducible and verifiable
```

---

## Quick Start
```powershell
# Step 1 — Verify the runtime is intact
mocka-check
# → LEDGER OK + ALL CHECKS PASSED

# Step 2 — Run one civilization loop cycle
mocka-loop
# → Observation → Record → Incident → ... → Audit
# → 1 event sealed into ledger.json

# Step 3 — Seal the execution
mocka-seal "runtime execution complete"
# → ALL CHECKS PASSED
```

---

## Status

**Active Development**
Part of the MoCKA deterministic governance architecture.
Loop position: ⑦ Action

---

## 日本語

### MoCKA Runtimeとは何か

タスクスケジューラーではありません。cronジョブでもありません。
文明ループを継続的に動かし続けるエンジンです——
観測・記録・インシデント・決定・行動・監査を継続的に。

単一エントリポイント。決定論的実行。すべての行動が記録される。

### mocka_Movementにおける位置づけ
```
MoCKA（コア・心臓部）
      ↓
mocka-knowledge-gate       ② Record
      ↓
mocka-transparency         ③ Incident · ④ Recurrence
      ↓
mocka-external-brain       ⑥ Decision
      ↓
[ mocka-runtime ]          ← ⑦ Action — ここです
      ↓
mocka-civilization         ⑧ 制度化
```

**ループステップ：⑦ Action（行動）**
上流：mocka-external-brain → 決定を送信
下流：MoCKAコア → 実行を台帳に記録

### 5エンジンアーキテクチャ

| エンジン | 役割 |
|---|---|
| Runtime | 実行ループを駆動 |
| Observatory | システム状態を監視 |
| Knowledge Core | 知識蓄積を管理 |
| Storage | 全イベントを永続化 |
| Audit | 全実行を検証 |

### 文明ステージ進行
```
Primitive → Organized → Mature → Advanced → AGI-Aligned
```

runtimeは文明がどのステージに達したかを追跡します。
ループ一回転ごとにステージが進行します。

### 単一エントリポイント

すべての操作は1つのゲートを通ります。
副作用なし。隠れた実行経路なし。記録されない行動なし。
すべての実行が再現可能で検証可能です。

---

Part of the [MoCKA Deterministic Governance Architecture](https://github.com/m-sirius-k/MoCKA).
