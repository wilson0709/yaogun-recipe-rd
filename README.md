# 肴滚云菜谱研发演示站

这是一个用于 GitHub Pages 公网展示的脱敏演示版本，展示肴滚智慧大厨云菜谱研发工作台的交互原型。

## 内容

- AI 云菜谱研发输入
- 机器可执行菜谱草稿
- 公有云菜谱排行摘要
- 烹饪规律分析
- 菜谱库与下发流程演示

## 数据说明

`src/data/recipeAnalysis.json` 只保留排行、执行次数、执行时长、统计摘要和规律结论。原始后台接口、完整 V6 程序体、菜谱 GUID 和研发人员字段已移除。

## 本地运行

```bash
npm install
npm run dev
```

## 构建

```bash
npm run build
```
