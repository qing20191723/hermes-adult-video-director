# AIGC成人短剧导演系统 v11

> AI-powered adult short drama video production pipeline. From script to final AI video prompts.

## What It Does

This skill turns an AI assistant into a complete adult short drama director. Input a story idea or script, and it walks you through a 5-step interactive pipeline:

```
Step 0: Ask aspect ratio (16:9 or 9:16)
Step 1: Script -> structured 4-act screenplay
Step 2: Storyboard -> shot-by-shot shooting script
Step 3: Image Assets -> scene/prop prompts + sex position reference images
Step 4: Video Prompts -> Wan2.7 (adult) or Seedance 2.0 (normal)
```

## Features

- **Self-contained**: 39 emotions with 5-track breakdown (eyes->breath->shoulders->body->voice), 14 sex positions with full posture descriptions, camera vocabulary, lighting library -- no external references needed
- **Dual video routing**: NC-17 content -> Wan2.7 (with timestamps, dialogue capacity checks, A-B-C bridge protocol). Normal content -> Seedance 2.0 (with cinematic style anchors)
- **15-second Sequence system**: A-B-C continuity bridge protocol ensures smooth transitions between Sequences. Dialogue capacity validated per segment (max ~3 short lines per 15s)
- **Image generation ready**: Scene/prop prompts for Seedream 5.0 Pro text-to-image. Sex position prompts for Seedream 5.0 Pro Edit (reference image compositing)
- **Production rules embedded**: No subtitles, no exaggerated expressions, flat-visible descriptive language, bright clean lighting only

## Quick Start

Trigger the skill by mentioning any of these keywords in Hermes Agent:
- `adult video`, `AV分镜`, `成人短剧`, `NC-17 script`

Just describe your story idea and the system guides you through each step.

## Tools Used

| Stage | Tool | Model ID |
|-------|------|----------|
| Scene images | Seedream 5.0 Pro | `bytedance/seedream-v5.0-pro/text-to-image` |
| Prop images | Seedream 5.0 Pro | same as above |
| Position images | Seedream 5.0 Pro Edit | `bytedance/seedream-v5.0-pro/edit` |
| Video (adult) | Wan2.7 | `wan2.7-t2v-2026-06-12` |
| Video (normal) | Seedance 2.0 | Style-prefix format |

## Knowledge Base

**39 emotions** in 10 categories: flirtatious, pleasure, afterglow, teasing, disappointment, grievance, intense, cold, conflicted, special states. Each with 5-track motion sequence (eyes, breath, shoulders, body/hands, voice).

**14 positions**: Penetrative (cowgirl, doggy, standing doggy, edge-standing, missionary, spooning), oral (fellatio, cunnilingus, 69), non-penetrative (titjob, intercrural, French kiss), manual (handjob, fingering).

**9 camera movements** + **8 lighting types** + **6 film style anchors**.

## Repository

- **Skill**: `SKILL.md` -- the complete self-contained system prompt
- **GitHub**: https://github.com/qing20191723/hermes-adult-video-director
- **Hermes skill path**: `creative/adult-video-director`

## License

MIT
