# dolphin-staking-website
海豚链上赚币官方网站

> ⚠️ **重要提示**: 所有新功能都在 `copilot/add-community-vip-features` 分支上！  
> 📖 详细说明请查看 [BRANCH_INFO.md](BRANCH_INFO.md)  
> 🔗 GitHub链接: https://github.com/aosima858588-boop/dolphin-staking-website/tree/copilot/add-community-vip-features

## 📁 项目结构

本项目采用模块化组织，各功能独立存放：

```
dolphin-staking-website/
├── index.html              # 主入口页面（门户导航）
├── staking/                # 返款查询系统模块
│   └── index.html         # USDT/INJ认购信息及返款计划查询
├── vip-membership/        # VIP会员中心模块
│   ├── vip.html          # VIP会员主页
│   ├── chat.html         # 社区群聊
│   ├── resources.html    # 专属资料库
│   ├── calculator.html   # 收益计算器
│   ├── entertainment.html # 娱乐中心
│   ├── lottery.html      # 幸运抽奖
│   └── checkin.html      # 每日签到
└── apps/                  # 其他独立应用
    └── todo.html         # 待办事项管理
```

## 🚀 功能模块

### 1. 返款查询系统
- 实时返款状态查询
- 多产品支持（USDT三期一返、每日返、INJ到期返本）
- 详细的认购记录统计

### 2. VIP会员中心
- **社区群聊** - 实时交流分享
- **专属资料** - 市场分析报告
- **收益计算** - 精准投资规划
- **娱乐中心** - 休闲小游戏
- **幸运抽奖** - 每日惊喜奖品
- **每日签到** - 连续签到奖励

### 3. 待办事项
- 快速创建待办任务
- 任务分类管理
- 本地存储

## 🛠️ 技术栈

- 纯HTML + CSS + JavaScript
- 无需后端服务器
- LocalStorage数据持久化
- 响应式设计

## 📖 使用说明

1. 打开 `index.html` 作为主入口
2. 选择需要的功能模块
3. 所有数据自动保存在浏览器本地存储

## 📝 更新日志

### 2026-02-07
- 重构项目结构，模块化组织
- 创建统一的门户导航页面
- 各功能模块独立存放，便于维护和扩展

