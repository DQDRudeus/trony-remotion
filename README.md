# Trony 的 Remotion 视频动效 Skill

**Trony’s Remotion Video Motion Skill** · [中文流程](SKILL.md) · [English workflow](workflow.en.md)

用一句视频想法、一张参考图或一段口播开始。这个 Codex 技能先检查本地 Remotion 环境，和你确定镜头、造型、动作和节奏，再制作可编辑的 Studio 合成。可用于独立片头、动态标题、流程图、转场和透明 B-roll。默认在 Studio 预览，需要交付时再导出。

Start with a video idea, a reference or a script. The skill checks the local Remotion project, works out the storyboard and visual direction with you, and builds an editable Studio composition. Use it for standalone titles, animated diagrams, transitions or overlays. Preview by default and render on request.

## 动效示例 / Watch the examples

点击动图查看完整 MP4。Select a preview to watch the full video.

| 动效合集 · Motion showcase | 纸张展开 · Paper unfold | 黄毛小偷 · Code flow |
|:---:|:---:|:---:|
| [![动效合集](xiaolin-pack.gif)](xiaolin-pack.mp4) | [![纸张展开](trony-paper.gif)](trony-paper.mp4) | [![黄毛小偷](thief-code.gif)](thief-code.mp4) |
| [35.5 秒 · 完整视频](xiaolin-pack.mp4) | [8 秒 · 完整视频](trony-paper.mp4) | [12 秒 · 完整视频](thief-code.mp4) |
| 叠化入场、侧视黑板、路线与逐句高亮 | 纸面弯折飞入、铺平、荧光笔划亮 | 角色分层漂浮、双向代码流、按节拍强调 |

[下载可编辑 Remotion 工程 / Download example source](remotion-examples-source.zip) · [MIT License](LICENSE)

解压源码后运行 `npm ci`、`npm run studio:thief`，在 Studio 中选择 `XiaolinPack`、`PaperInsert` 或 `ThiefCode`。The source ZIP includes the TypeScript compositions, media, lockfile and rendering instructions. Original code and documentation use MIT. Third-party dependencies, fonts and media content retain their respective terms.

## 安装 / Install

[下载完整技能包 / Download the skill ZIP](trony-remotion.zip)

解压后将其中的 `trony-remotion` 文件夹复制到技能目录。 Extract the ZIP and install the enclosed `trony-remotion` folder.

将本技能目录复制到个人 Codex 技能目录下，命名为 `trony-remotion`。确认 `~/.codex/skills/trony-remotion/SKILL.md` 存在，然后在新聊天中调用。如果自定义了 `CODEX_HOME`，使用其中的 `skills` 目录。

Copy this skill directory to `~/.codex/skills/trony-remotion` (or the skills directory under your configured `CODEX_HOME`). Start a new chat and invoke `$trony-remotion`. The skill contains production instructions. Remotion runs in your video project.

## 调用示例 / Try it

> 用 $trony-remotion 做一个 5 秒无声片头。书页卷开后标题逐字出现。先给我看分镜，确定造型后在 Studio 里预览。

> Use $trony-remotion to animate a route map. Reveal each stop on successive beats, then hold the final map for two seconds. Show me the storyboard before building the animation.
