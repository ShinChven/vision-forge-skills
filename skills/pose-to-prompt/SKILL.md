---
name: pose-to-prompt
description: Translates physical poses of human characters from images into detailed, generation-ready text prompts for image models like Stable Diffusion or Midjourney.
---

# Pose Analysis & Prompt Generation

Analyze human character poses from images to generate precise text descriptions. Focus exclusively on anatomy and posture, ignoring environment or clothing unless they influence the pose.

## Workflow

1.  **Pose Title**: Assign a short, descriptive name to the pose (e.g., "Dynamic Heroic Stance").
2.  **Camera Angle & Framing**: Identify framing (e.g., full body) and angle (e.g., low angle).
3.  **Core Posture**: Determine stance, weight distribution, and torso alignment.
4.  **Head & Gaze**: Note head tilt and gaze direction.
5.  **Limbs Breakdown**: Detail the position of arms, hands, legs, and feet.

## Output Format

Always output the result in a markdown code block using the following structure for easy copying:

```markdown
- [Pose Title]: [Natural Language Description]
```

```markdown
[Comma-Separated Prompt Tags]
```

## Example

**- Dynamic Confident Standing: The camera captures a full-body, low-angle shot of a female character from a 3/4 front view. She is standing with her weight shifted to her right leg. Her torso is slightly twisted to the right, but her head is turned to look directly over her left shoulder at the viewer. Her left arm is raised with the hand gently resting on the back of her neck, elbow pointing outward. Her right arm rests at her side with her hand resting firmly on her hip. Her left knee is slightly bent with the heel lifted off the ground.**

**Prompt: full body shot, low angle, 3/4 view, female character, standing, dynamic pose, weight on right leg, contrapposto, twisting torso, looking over left shoulder, eye contact, left hand touching back of neck, raised left elbow, right hand on hip, left knee slightly bent, tip-toes on left foot.**
