# real-problems

给编码 agent 用的 skill：对已经在磁盘上的 skill、给 agent 看的说明、或给人看的手册，多角度找出真问题，两道闸门后再改文件。

运行时排错、产品取舍、从零新建、代码拆模块，不要走这套。

## 安装

```text
npx skills add Shengjingwa/real-problems-skill
```

也可以把 `skills/real-problems/` 整目录拷到本机：

- Cursor / Codex：`~/.agents/skills/real-problems/` 和 `~/.cursor/skills/real-problems/`

目录名必须是 `real-problems`，和 `SKILL.md` 里的 `name` 一致。拷完后在该目录放 `source-root`，一行，填本仓库在磁盘上的绝对路径。每次跑留下的清单写在本仓 `docs/`，不进 git。

新开一聊后敲 `/real-problems`。

## 许可证

MIT。见 [LICENSE](LICENSE)。
