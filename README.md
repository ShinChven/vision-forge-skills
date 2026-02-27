# VisionForge: Image Generation Prompt Suite

VisionForge is a collection of specialized agent skills designed to generate high-fidelity prompts for state-of-the-art image generation models. By reverse-engineering visual components from existing images—such as human anatomy, environmental atmosphere, and composition—VisionForge provides a modular framework for precise prompt engineering across AI agent platforms.

## Overview

VisionForge extracts the "DNA" of an image and translates it into optimized text descriptions. Whether you need to replicate a complex pose or translate a specific lighting setup to a new environment, VisionForge provides the tools to bridge the gap between visual inspiration and generative output. These skills follow the standard `SKILL.md` format, making them compatible with any agent framework that supports structured skill definitions.

## Agent Skills

### 🏃 Pose-to-Prompt
**Location:** `skills/pose-to-prompt`

Generates detailed character pose prompts by analyzing anatomy and posture. It ignores environment or clothing unless they influence the pose, ensuring the generated prompt focus remains on the character's physical presence—perfect for maintaining identity consistency across generations.

- **Key Features**: Dynamic stance analysis, limb breakdown, camera angle identification, and gaze direction.
- **Usage**: Use when you need to replicate or adapt a specific character posture.

### 🌌 Environment-to-Prompt
**Location:** `skills/environment-to-prompt`

Translates environmental backgrounds into optimized prompt descriptions. It preserves lighting, depth, and composition while allowing for thematic shifts (e.g., turning a forest into a cyberpunk city), optimized for complex scene logic and cinematic rendering.

- **Key Features**: Atmospheric mapping, lighting preservation, and compositional translation.
- **Usage**: Use to "re-skin" the environment of a shot while maintaining its original visual balance.

## Usage

To use these skills, provide the relevant `SKILL.md` file and its associated references to your AI agent. 

For agents supporting dynamic skill activation (like the Gemini CLI):
```bash
activate_skill skills/pose-to-prompt
```

## Project Structure

```text
.
├── skills/
│   ├── environment-to-prompt/   # Background translation and analysis
│   └── pose-to-prompt/          # Human pose and anatomy extraction
└── ...
```

## Contributing

These skills are designed to be modular. If you're adding a new skill (e.g., `Lighting-to-Prompt` or `Style-to-Prompt`), ensure it follows the standard `SKILL.md` format and provides a clear workflow for the agent.
