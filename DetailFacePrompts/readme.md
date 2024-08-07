# Flux - Usage of Detailed Prompting in Facial Variation Testing

## Description

For this test I utilized random combinations of facial features against a prompt that specified an exact age and ethnicity for the model.  Overall I found that doing this resulted in very little facial variation.  My cheekbones test showed that there can be some variation achieved with a loose prompt with only cheekbones, but overall in this test I see less variation of the cheekbones.  Facial shape and lip shape seem to have little to no impact, and eye shape only changed with a couple of the prompts.  This leaves us still facing the issue that Flux seems to have only a few face variations.  Hopefully further tests such as using names will help in creating different variations.  It would also be interesting to see if adding hair style would help.

## Testing Details

- **Image Resolution:** 512x768
- **Model:** Flux1-dev-fp8
- **Hardware:** 4060 TI 16GB
- **Software:** SwarmUI + ComfyUI

## Helpful Links

- `index.html` - HTML Index Grid showcasing a comparative view of generated images. [View HTML Index Grid](./index.html)
- `FullGrid.jpg` - A composite image displaying all generated images in a single grid. [View Full Grid Image](./FullGrid.jpg)

