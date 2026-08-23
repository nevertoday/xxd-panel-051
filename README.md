<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 051 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 051

### 让可辨识主体成为一件轻盈可触的微缩纸艺装置

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D5898C?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-6FA4B7?style=flat-square)](#)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 微缩纸艺 · 横向悬浮景观带 · 真实手工材质 · 空气蓝 · 大量留白

把源图中最有辨识度的主体与叙事关系，转化为一件手工微缩纸艺装置：一个可辨识核心主体、一条狭长轻盈的横向景观带、少量有依据的陪衬模型、真实纸纤维和大面积浅色纸面。

## 为什么需要这套 Skill

```text
锁定主体、轮廓、姿态与叙事关系 → 保留三个专属线索 → 重构一个可辨识手工微缩主体 → 只提炼必要陪衬模型 → 组织于一条狭长横向悬浮景观带 → 显示纸纤维、折边、切口、层叠厚度与微小误差 → 用柔和微距光建立体积 → 保留大面积浅色纸面 → 让文字像作品签名融入
```

如果换成无关照片后，主体辨识、模型构造、材质选择、景观带节奏、配色关系和文字都不发生实质变化，结果就不属于这套 Panel。

## 视觉契约

- 至少保留三个源图专属线索，让核心手工微缩主体一眼可辨。
- 只建立一个核心主体与一条狭长横向悬浮景观带；少量陪衬模型必须有源图依据且保持低权重。
- 通过尺度变化、层叠遮挡与小型前后景建立纵深；整体可居中但不过度对称，基座不得厚重。
- 纸纤维、折边、切口、层叠厚度、轻微毛边与细小制作误差必须可见；柔和漫射光和接触阴影提供微距摄影般体积。
- 使用空气蓝、象牙白、奶油白、浅米色、柔和灰绿、鼠尾草绿和建筑中性色；灰粉只作少量点缀。
- 拒绝塑料 CG、玩具展示、儿童手工感、通用微景观、复杂堆积、过度可爱、电商陈列、平面矢量替代和灰脏泛黄。

完整规格见 [SKILL.md](SKILL.md) 与 [生产提示词](references/xxd-panel-051-prompt.zh-CN.md)。它们保留原始审美动机，但不会把历史 3:4 画布变成隐藏默认值。

## 样张 · 待补充

051 的正式样张来源尚未提供，因此这里不借用其他风格的图片作为占位。收到小小东发布的 `VOL.051` X 原文后，会将核验过的图片保存到 `assets/examples/`，并逐张链接回原文。未来样张只展示审美动机，不会成为生成参考或默认值。

## 四种可组合输出模式

可以用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 张 PNG。

| 模式 | 未指定尺寸 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 `W×2H` | 上方完整原图＋下方变化设计，严格 50/50 |
| `left-right` | 源图自适应 `2W×H` | 左侧完整原图＋右侧变化设计，严格 50/50 |
| `design-only` | 源图自适应 `W×H` | 只显示变化设计，不出现原照片 |
| `wallpaper-pack` | 设备分别标注尺寸 | 手机、iPad、电脑、儿童手表四张独立 PNG |

壁纸可选连贯或独立。连贯套装让所有设备共同参考原图和同一张批准定调图，绝不裁切或串联衍生图；独立套装每张只参考原图。

## 文案、位图与可信边界

正式生成前确认自动文案、准确自定义文案或无文字；语言跟随目标受众，准确文案逐字保留。自动文案从地点、主体身份、主题、情绪、深意或隐藏关系中提炼一个短标题，不限定城市名。历史原稿提到英文，但生产时服从目标语言，不把英文设为默认。小型、精致、略带手写感的文字优先进入景观带下方留白，像作品签名而不是商业标题。

普通模式未指定尺寸时按源图自适应；双联严格 50/50，全部交付为 PNG。每次调用都在 `~/Desktop/xxd/xxd-panel-051/` 下创建新任务。位图路线只输出脱敏状态；SVG、HTML、Canvas 和程序绘图不能代替最终作品。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-051.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-051" ~/.codex/skills/xxd-panel-051
```

Claude Code 用户可把同一文件夹链接到 `~/.claude/skills/xxd-panel-051`。安装后请重启 Agent 会话。

```text
$xxd-panel-051
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完整规格：[Skill 工作流](SKILL.md) · [原始风格档案](references/051-source.md) · [英文生产提示词](references/xxd-panel-051-prompt.en.md) · [中文生产提示词](references/xxd-panel-051-prompt.zh-CN.md)

## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。

## 支持与会员

- 深度咨询：299 元／小时，通过[微信](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)预约。
- 小小东 Skills 用户交流群：99 元，一次付费入群；不含一对一咨询。
- 知识星球＋成员提示词库：699 元／年，一次年费同时开通两项权益。若从[知识星球](https://wx.zsxq.com/group/15554814142882)开通，请微信联系小小东领取[成员提示词库](https://vip.xiaoxiaodong.ai/)兑换码；若在成员提示词库自助开通，请微信联系小小东邀请进入知识星球。

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>不是把照片做成玩具，而是把它的真实关系折进纸里。</strong></div>

---

<div align="center">

## ☕ 支持这个开源项目

算力赞助请使用小小东自己的微信或支付宝赞赏码；赞助完全自愿，不改变开源项目的访问权限。

<table><tr><td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD WeChat reward" width="180"></a><br><strong>WeChat</strong></td><td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD Alipay reward" width="180"></a><br><strong>Alipay</strong></td></tr></table>

</div>
