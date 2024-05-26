# Midjourney Prompt Examples

## Guidelines
### Prompt Structure
A prompt is a sentence that describes the image you want to generate. It can include the following elements:

- **Image URL(s)**: Image URL(s) to influence the style and content of the result.
- **Description**: A brief description of what image you want to generate
- **Parameters**: Additional parameters to change how an image generates

> Example:
> `https://example.com/image.png A portrait of a cat in a neon-lit cityscape --ar 7:4`

### Image URL(s)
Add Image URLs at the front of a prompt to influence a Job's composition, style, and colors.
Image file should end in `.png`, `.gif`, `.webp`, `.jpg`, or `.jpeg`.

> Example:
> `https://example.com/image.png`

### Description
Focus on what you want and be clear about any context or details by forming a concise sentence including tge following:

- **Subject**: person, animal, character, location, object
- **Medium**: photo, painting, illustration, sculpture, doodle, tapestry
- **Environment**: indoors, outdoors, on the moon, underwater, in the city
- **Lighting**: soft, ambient, overcast, neon, studio lights
- **Color**: vibrant, muted, bright, monochromatic, colorful, black and white, pastel
- **Mood**: sedate, calm, raucous, energetic
- **Composition**: portrait, headshot, closeup, birds-eye view

> Example
> `A portrait of a cat in a neon-lit cityscape`

### Parameters
Add parameters at the end of a prompt to change how an image generates. Some of the common parameters are as follows:

- **--ar**: Aspect Ratio (E.g. `--ar 7:4`)
- **--cref**: Character Reference (E.g. `--cref https://url.com/BlueHairGuy.png`)
- **--sref**: Style Reference (E.g. `--sref https://url.com/BlueHairGuy.png`)
- **--cw**: Character Weight between 0 and 100 (E.g. `--cw 50`)
- **--no**: Remove Background (E.g. `--no fruit`)
- **-q**: Quality among `0.25`, `0.5` or default `1` (E.g. `-q 0.5`)

## Prompt Tips
To maintain a consistent style while using a character reference, you can combine the --sref and --cref parameters.

> illustration of a man sitting in a cafe --cref https://url.com/BlueHairGuy.png --sref https://url.com/BlueHairGuy.png
