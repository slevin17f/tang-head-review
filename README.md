# tang-head-review

用于历史 K 线复盘的中文 Codex Skill。十二张能力卡涵盖高位 K 线组合、价量与均线交叉、反弹、分批退出，以及逐日核对大盘预测。每次判断标明观察截止时间、当时已知的证据和下一步验证条件。

## 安装

克隆仓库后，在仓库根目录运行以下命令，为当前用户安装。若已安装过同名技能，先检查原有版本及本地修改。

```sh
mkdir -p ~/.agents/skills
cp -R skills/tang-head-review ~/.agents/skills/
```

也可将同一目录放到项目的 `.agents/skills/` 下供该项目使用。完整保留 `SKILL.md` 和同级 `references/`。技能仅使用 Markdown，无需行情接口或额外软件包。

## 示例

> 用 $tang-head-review 复盘这张历史日线图。先只看截至周三收盘的三根线，比较品字头与墓碑夹两种判断，再打开周四的数据检验。

[技能入口](skills/tang-head-review/SKILL.md) · [能力索引](skills/tang-head-review/references/capability-index.md)

## 来源

方法依据唐能通著《短线是银（之五）——头部不再套》，四川人民出版社，2007 年 12 月第 2 版，2008 年 3 月第 2 次印刷，ISBN 9787220074882。能力卡以独立整理的步骤、算例和复盘问题讲解原书方法。卡中 PDF 页码以封面为第 1 页，正文印刷页 1 对应 PDF 第 31 页。
