# opc_work - OpenClaw 三省六部协作共享

> 基于 [cft0808/edict](https://github.com/cft0808/edict) 三省六部架构理念，由 OpenClaw 太子工作区协作创作。

## 架构理念

**以古制御新技，以智慧驾驭 AI**

采用三省六部制度设计的 AI 多 Agent 协作架构：

```
皇上（你）→ 太子（分拣）→ 中书省（规划）→ 门下省（审核）→ 尚书省（派发）→ 六部（执行）→ 回奏
```

## 特点

- ✅ **制度性审核** - 门下省专职审核，不合格直接打回
- ✅ **实时看板** - 军机处 Kanban 实时监控任务进度
- ✅ **完全可观测** - 完整流转审计，谁干了什么一目了然
- ✅ **实时可干预** - 随时叫停/取消/恢复任务
- ✅ **分权制衡** - 严格权限矩阵，谁能干什么白纸黑字

## 快速开始

```bash
git clone https://github.com/wananer/opc_work.git
cd opc_work
# Follow the instructions to install
```

## 致谢

- 原架构设计：[cft0808/edict](https://github.com/cft0808/edict)
- 基于 OpenClaw：https://openclaw.ai

## License

MIT - see [LICENSE](LICENSE) for details
