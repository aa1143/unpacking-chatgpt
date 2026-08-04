# Project guidance

## Purpose

Maintain the Chinese educational content series “拆开 ChatGPT”. Preserve technical accuracy while keeping every episode understandable to a non-specialist audience.

## Content rules

- Lead with a concrete question or counterintuitive phenomenon.
- Explain one main concept per episode.
- Use “现象 → 原理 → 工程类比 → 实际影响 → 下一期问题”.
- Define technical terms on first use.
- Distinguish ChatGPT, GPT, Transformer, and LLM accurately.
- Prefer “逐 Token 生成” over “逐字生成”.
- Label invented probabilities and simplified tokenization as illustrative.
- Do not claim the model truly understands or thinks unless discussing that question explicitly.
- Keep formulas out of the first explanation; add them only when the episode requires them.

## File conventions

- Episode folders use `NN-中文主题`.
- Use `article.md`, `video-script.md`, `storyboard.md`, `whiteboard-plan.md`, `social-copy.md`, and `publish.md`.
- Preserve high-resolution cover masters; create platform exports as separate files.
- Do not commit raw video, editor caches, or rendered video exports.

## Visual rules

- Article covers use the installed `$engraved-knowledge-cover` workflow.
- Generate high-resolution illustration without text, then typeset Chinese titles separately.
- Vertical video canvas is 1080×1920. The whiteboard region is exactly 1080×810 (4:3), from y=480 to y=1290.
- Keep whiteboard diagrams simple enough to read on a phone.

## Verification

- Check all Chinese titles and punctuation manually.
- Check technical claims against primary sources when accuracy may have changed.
- Preview covers and diagrams at phone-thumbnail size.
- Update the episode progress table after meaningful milestones.

