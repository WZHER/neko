# neko-planner · 我的喵配装模拟器

[FUUN.FUN](https://fuun.fun)《我的喵》守站小游戏的第三方工具页。

## 功能

- **配装模拟**：40 只猫全数据（稀有度/等级/点数/装备强化实时联动），每只猫的配置自动保存在浏览器
- **成本分析**：升级、买装备、强化的 FUN 全程统计
- **战报反推器**：直接粘贴对战报告，自动解析伤害（普通/暴击/追打）与胜负，推对手大概属性（攻击/防御/暴伤/生命区间），带点数可行性检查
- **养成攻略**：加点收益、升级 vs 强化成本的数据结论

## 数据来源

- 公开 API：`https://fuun.fun/api/v1/neko/types`、`https://fuun.fun/api/v1/shop/items`
- 守站喵说明手册与前端源码常量（2026-10-29 抓取）

## 本地运行

纯静态单文件（`index.html`），无构建步骤。GitHub Pages 或直接双击打开均可。

相关链接：[我的喵](https://fuun.fun/my-neko) · [守站喵说明](https://fuun.fun/my-neko/guard-manual)
