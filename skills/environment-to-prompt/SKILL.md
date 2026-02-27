---
name: environment-to-prompt
description: Analyzes the background environment of an image and translates it into a different setting, style, or atmosphere. Use when a user wants to "move" a subject from one environment to another in a generated prompt.
---

# Environment Analysis & Translation

Analyze the background and atmosphere of an image to translate it into a new context. This skill helps preserve the *lighting*, *depth*, and *composition* of the original background while changing its *thematic elements*.

## Workflow

1.  **Current Analysis**: Identify the key elements of the existing environment (lighting, terrain, weather, architecture, depth of field).
2.  **Target Translation**: Map the user's requested environment to specific visual descriptors that maintain the original's compositional balance.
3.  **Atmospheric Synergy**: Define how the new environment interacts with the subject (e.g., reflections, cast shadows, environmental lighting).

## Output Format

Always output the result in a markdown code block using the following structure:

```markdown
- [Environment Title]: [Natural Language Description of the new environment]
```

```markdown
[Comma-Separated Environmental Prompt Tags]
```

## Example

**- Neon Cyberpunk Alleyway: The background is a narrow, rain-slicked urban alley at night. Dark, damp pavement reflects the vibrant pink and cyan glow of overhead neon signs. Steam rises from sewer grates, catching the colorful light. Dilapidated brick walls are covered in digital graffiti and tangled wires. The depth of field is shallow, keeping the focus sharp on the foreground while the neon lights in the distance blur into soft bokeh circles.**

**Prompt: narrow alleyway, cyberpunk city, night time, rain-slicked pavement, neon lights, pink and cyan lighting, wet reflections, rising steam, brick walls, digital graffiti, tangled power lines, cinematic lighting, shallow depth of field, bokeh background.**

