---
name: ni-haixia-tianji
description: |
  当用户询问《天纪》这本书本身（书名/作者/章节/整书概览/术语），或涉及本书未独立成 Skill 的主题时调用：
  紫微排盘与细分规则（六吉六煞/禄马交驰/格局/六亲宫/身宫）、阳宅凶局化解、面相细则（相术望诊）、
  手相八宫、六神占断、小六壬、发旋定辰、阴宅来龙、四柱命卦旁支（铁板神数/皇极经世）、堪舆学龙穴砂水。
  
  以下意图优先使用同包独立 Skill: tianji-sancai-yiguo(命能不能改/该不该信)、tianji-yangzhai-mingwei(住哪间房)、
  tianji-ziwei-pandu(看命盘)、tianji-mianxiang(看面相十二宫)、tianji-qise-shengsi(看气色)、
  tianji-guanrenshu(识小人)、tianji-xingti-fenlei(形体分类)、tianji-rendao-64gua(该进该退)、tianji-sizhu-minggua(无紫微盘排命卦)。
  
  Triggers: 天纪/倪海厦/紫微斗数/阳宅/人间道/面相/手相/堪舆/四柱/六神
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: router
  cangjie.bundle-id: bundle.ni-haixia-tianji
  cangjie.capability-count: 35
  cangjie.entrypoint-count: 10
---
# 《天纪》（天机道·人间道·地脉道·紫微斗数） — 来源路由入口（compact pack）

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 现代医学诊断、用药与治疗建议（涉及健康务必先就医）
- 法律、投资、保险等专业决策的最终意见
- 以命理结论替代专业咨询或做出重大人生决策的唯一依据
- 对具体个人的确定性预言（生老病死、婚姻成败的断言）

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 三才各占1/3：天命（紫微）+地理（阳宅）+人事（人间道），地理+人事>天命——命可化解。
2. 以果决行：先由命盘/卦象知道结果，再决定当下行动方向，而非从原因推结果。
3. 四化大于星辰：科权禄忌是变化的驱动力，先看四化再看星曜。
4. 庙旺落陷定吉凶：同一颗星庙旺为吉、落陷为凶；吉处藏凶必凶，凶处藏吉平安。
5. 名位相等：阳宅中家庭成员卧室方位与八卦身份对应则吉，不对应则凶。
6. 化解不靠符咒：改地理位置 + 改行为意念，不靠画符念咒或买风水物品。
7. 戒之初与戒之盛：事情开始时要戒惧，运势巅峰时更要戒惧。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 命能不能改；算命有没有用；该不该信命理；如何化解凶运；以果决行 | references/capabilities/tianji-sancai-yiguo.md | 已晋级为独立 Skill `tianji-sancai-yiguo`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 住哪个房间好；卧室方位；父母住哪间；要不要换房间；阳宅吉凶 | references/capabilities/tianji-yangzhai-mingwei.md | 已晋级为独立 Skill `tianji-yangzhai-mingwei`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 看命盘；帮我看看紫微；事业怎么样；财运怎么样；宫位解读 | references/capabilities/tianji-ziwei-pandu.md | 已晋级为独立 Skill `tianji-ziwei-pandu`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 帮我看看面相；这颗痣在哪个宫；眼角纹代表什么；印堂怎么样；面相吉凶 | references/capabilities/tianji-mianxiang.md | 已晋级为独立 Skill `tianji-mianxiang`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 我气色怎么样；最近脸色不好；印堂发黑；气色预示什么；有没有灾 | references/capabilities/tianji-qise-shengsi.md | 已晋级为独立 Skill `tianji-qise-shengsi`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 怎么看出一个人靠不靠谱；同事是不是小人；这人能不能深交；怎么看人；识人 | references/capabilities/tianji-guanrenshu.md | 已晋级为独立 Skill `tianji-guanrenshu`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 我是什么形；五形人怎么看；三停是什么；面型分类；形体命运 | references/capabilities/tianji-xingti-fenlei.md | 已晋级为独立 Skill `tianji-xingti-fenlei`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 我现在该进还是该退；这个处境怎么办；用易经看我的事；卦象怎么解；时机对不对 | references/capabilities/tianji-rendao-64gua.md | 已晋级为独立 Skill `tianji-rendao-64gua`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 没有紫微盘怎么算；帮我排四柱命卦；八字转卦；先天卦后天卦；用易经算流年 | references/capabilities/tianji-sizhu-minggua.md | 已晋级为独立 Skill `tianji-sizhu-minggua`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 家里有凶卦怎么办；以卦化解；凶宅化解 | references/capabilities/tianji-yangzhai-xiongju.md | references/capabilities/tianji-yangzhai-mingwei.md |
| 怎么排命盘；润月怎么算；子时算哪天；排盘规则 | references/capabilities/tianji-ziwei-paipan.md | references/capabilities/tianji-ziwei-pandu.md、references/capabilities/tianji-sizhu-minggua.md |
| 四化怎么看；化忌在哪；化禄什么意思 | references/capabilities/tianji-sihua.md | references/capabilities/tianji-ziwei-pandu.md、references/capabilities/tianji-shengong-huajie.md |
| 紫微星什么意思；贪狼是什么星；主星星性 | references/capabilities/tianji-shisi-zhuxing.md | references/capabilities/tianji-miaowang-luoxian.md、references/capabilities/tianji-ziwei-pandu.md |
| 左辅右弼是什么；文昌文曲怎么看；六吉星 | references/capabilities/tianji-liujixing.md | references/capabilities/tianji-shisi-zhuxing.md |
| 擎羊陀罗怎么看；火星铃星；六煞星 | references/capabilities/tianji-liushaxing.md | references/capabilities/tianji-shisi-zhuxing.md、references/capabilities/tianji-miaowang-luoxian.md |
| 庙旺落陷怎么看；星亮度；吉处藏凶 | references/capabilities/tianji-miaowang-luoxian.md | references/capabilities/tianji-shisi-zhuxing.md |
| 大运怎么样；流年运势；今年运势；大限 | references/capabilities/tianji-dayun-liunian.md | references/capabilities/tianji-ziwei-pandu.md |
| 禄马交驰是什么；禄存怎么看；巨富格局 | references/capabilities/tianji-lumajiaochi.md | references/capabilities/tianji-ziwei-geju.md |
| 半空折翅是什么；日月反背；格局怎么看 | references/capabilities/tianji-ziwei-geju.md | references/capabilities/tianji-ziwei-pandu.md、references/capabilities/tianji-jiehun-zeou.md |
| 兄弟关系怎么样；子女宫怎么看；和父母缘分 | references/capabilities/tianji-liuqin-gong.md | references/capabilities/tianji-mianxiang.md、references/capabilities/tianji-jiehun-zeou.md |
| 身宫是什么；化忌怎么化解；后天运势 | references/capabilities/tianji-shengong-huajie.md | references/capabilities/tianji-sihua.md、references/capabilities/tianji-sancai-yiguo.md |
| 手相怎么看；掌纹解读；天柱纹是什么 | references/capabilities/tianji-shouxiang-bagong.md | references/capabilities/tianji-mianxiang.md |
| 测字怎么看；六神是什么；灵机取象 | references/capabilities/tianji-liushen-zhanguan.md | references/capabilities/tianji-liushen-yingyong.md、references/capabilities/tianji-rendao-64gua.md |
| 什么时候能结婚；和谁结婚好；婚姻怎么样；八字合婚 | references/capabilities/tianji-jiehun-zeou.md | references/capabilities/tianji-ziwei-geju.md、references/capabilities/tianji-liuqin-gong.md |
| 日月反背案例；命例参考 | references/capabilities/tianji-mingli-riyue.md | references/capabilities/tianji-ziwei-geju.md、references/capabilities/tianji-mianxiang.md |
| 吉格案例；命例参考 | references/capabilities/tianji-mingli-jige.md | references/capabilities/tianji-ziwei-geju.md、references/capabilities/tianji-lumajiaochi.md |
| 凶格案例；六亲推算 | references/capabilities/tianji-mingli-xiongge.md | references/capabilities/tianji-liuqin-gong.md、references/capabilities/tianji-shengong-huajie.md |
| 小六壬怎么算；快速占卜 | references/capabilities/tianji-xiaoliuren.md | references/capabilities/tianji-jinqian-gua.md |
| 不知道出生时辰；发旋看时辰 | references/capabilities/tianji-faxuan-dingshchen.md | references/capabilities/tianji-ziwei-paipan.md |
| 祖坟风水；阴宅怎么看；来龙朝向 | references/capabilities/tianji-yinzhai-lailong.md | references/capabilities/tianji-kanyu-longxue.md、references/capabilities/tianji-yangzhai-mingwei.md |
| 金钱卦怎么起；怎么摇卦；起课 | references/capabilities/tianji-jinqian-gua.md | references/capabilities/tianji-rendao-64gua.md、references/capabilities/tianji-liushen-zhanguan.md |
| 六神怎么用；面部六神；占断口诀 | references/capabilities/tianji-liushen-yingyong.md | references/capabilities/tianji-liushen-zhanguan.md |
| 怎么看风水；寻龙点穴；阴宅选址；八煞黄泉 | references/capabilities/tianji-kanyu-longxue.md | references/capabilities/tianji-yangzhai-mingwei.md、references/capabilities/tianji-yinzhai-lailong.md |
| 望诊细则；面色对应什么病；疾厄宫怎么看 | references/capabilities/tianji-xiangshu-wangzhen.md | references/capabilities/tianji-qise-shengsi.md、references/capabilities/tianji-mianxiang.md |
| 四化面相；颧骨代表什么；犀牛骨 | references/capabilities/tianji-sihua-mianxiang.md | references/capabilities/tianji-sihua.md、references/capabilities/tianji-mianxiang.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 涉及身体健康/生死 → 停止命理推演，明确建议就医，不输出确定性死亡预判。
- 涉及法律/人身安全 → 停止套用书中方法，建议求助专业人士。
- 用户意图在路由表与能力索引中均无法命中 → 明确告知超出本书范围，不硬套。
- 用户要求预测他人隐私或用于欺诈/操控他人 → 拒绝。
