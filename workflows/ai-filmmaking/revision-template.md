# Local revision request / 局部修改模板

Copy the template and fill in one block per change. Use sequence timecodes for the edited film and label source timecodes separately.
复制模板，每项修改填写一段。成片位置用时间线时间码，原素材位置请另行标明。

```markdown
## Baseline version / 基准版本
- Approved version and project file / 已确认版本及工程文件：
- Target version / 本轮目标版本：
- Timebase and frame rate / 时间码基准及帧率：

## Timecode / 时间码
- Timeline in–out, preferably HH:MM:SS:FF / 成片起止，优先使用 HH:MM:SS:FF：
- Source timecode or asset ID, if relevant / 来源时间码或素材编号（如适用）：

## Current issue / 当前问题
- What happens, and where can it be reproduced? / 现象是什么？在哪里可以复现？

## Expected result / 预期效果
- What should the viewer see or hear after the change? / 改完后观众应看到或听到什么？

## Implementation requirements / 实施要求
- Affected tracks, assets, and constraints / 受影响的轨道、素材与限制：
- Review required before final render / 是否需先审阅局部试样：

## Protected content / 必须保留的内容
- Approved cuts, timecodes, dialogue, subtitles, visuals, and mix to leave in place / 应保留的切点、时间码、对白、字幕、画面与混音：

## Acceptance criteria / 验收标准
- Observable result / 可观察的结果：
- Exact boundaries or tolerance, if applicable / 精确边界或容差（如适用）：

## Regression testing / 回归测试
- Check both edit boundaries, adjacent content, timecodes, captions, and sync where relevant / 按需检查修改区间两端、相邻内容、时间码、字幕和音画同步：
- List automated checks, playback checks, and any items still pending / 记录自动检测、人工播放检查及待核对事项：

## Deliverables / 交付成果
- Separate revision, review clip, updated project files, and change summary as needed / 按需交付独立版本、审阅片段、更新工程及修改说明：

## Rollback / 回撤方式
- Previous version path and dependencies needed to reopen it / 上版路径及重新打开所需依赖：
- Restore by reopening the baseline / 通过重新打开基准版本回撤：
```
