# 希望学院课件脚本1.0

把已有课件、内训资料或岗位问题整理为可制作的讲解视频脚本。这个 Skill 完成选题、依据、故事链、逐句旁白和逐镜分镜，并把脚本包交给独立的视频制作流程。

## 适用场景

- 有课件：提取论点、案例和限制，按学员的工作判断重组讲解，而非逐页朗读。
- 无课件：从岗位任务、常见错误和判断标准建课；缺少的公司口径列为待业务确认。
- 旁白作为一堂独立的新课直接讲论点和案例。资料出处保留在依据表及分镜中。

## 交付内容

完整脚本包通常包含 `brief.md`、`evidence.md`、`story-arc.md`、`narration.json`、`storyboard.md` 和 `handoff.md`。逐句稿使用稳定的 `L` ID，分镜使用 `S` ID，依据使用 `E` ID，方便审核与后续制作。字段说明见 [交接约定](references/handoff-contract.md)。

脚本阶段给出预计时长与画面意图；正式配音、时间码、字幕、动画、剪辑和成片验收由制作流程完成。

## 安装与使用

把本仓库复制到 Codex 的 `~/.codex/skills/xiwangxueyuan-course-script-v1/`，保留 `SKILL.md`、`agents/` 和 `references/` 的相对位置。之后可在新对话中使用 `$xiwangxueyuan-course-script-v1` 调用。

示例请求：

> 使用 `$xiwangxueyuan-course-script-v1`，把这份达人培训课件改成一条给 PR 学习的讲解视频脚本。请完成选题、依据表、故事链、逐句旁白和分镜；语速按常规讲解的 1.5 倍设计。

本仓库不包含原始内训课件、真实业务数据或视频成片。
