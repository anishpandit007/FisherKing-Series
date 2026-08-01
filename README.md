# FisherKing Series

A curated collection of ComfyUI workflows, reference implementations, and productivity tools for image and video generation.

The FisherKing Series focuses on practical, reusable workflow implementations with an emphasis on understandable architecture, efficient local generation, and low-VRAM accessibility where practical.

## Workflow Collection

### Image Generation

| Model / Workflow | Description |
|---|---|
| [**ImageFactory**](workflows/image-generation/imagefactory/) | Model-agnostic text-to-image productivity workflow |
| [**Krea2**](workflows/image-generation/krea2/) | Text-to-image and identity-edit reference workflows |
| [**Flux.2 Klein 9B**](workflows/image-generation/flux2_klein_9B/) | Text-to-image and character utility workflows |
| [**ZiT**](workflows/image-generation/zit/) | Text-to-image and guided image-to-image reference workflows |
| [**Anima**](workflows/image-generation/anima/) | Text-to-image and image-edit reference workflows |
| [**Ideogram 4**](workflows/image-generation/ideogram4/) | Ideogram 4 reference workflow |
| [**NoobAI**](workflows/image-generation/noobai/) | NoobAI text-to-image reference workflow |

### Image Manipulation

| Workflow | Description |
|---|---|
| [**BiRefNet**](workflows/image-manipulation/birefnet/) | Background-removal utility workflow |
| [**CodeFormer**](workflows/image-manipulation/codeformer/) | Face-restoration utility workflow |

### Video Generation

| Model | Description |
|---|---|
| [**LTX 2.3**](workflows/video-generation/ltxv23/) | Local video-generation reference workflows |
| [**WAN 2.2**](workflows/video-generation/wan22/) | Image-to-video and video-generation reference workflows |

## Repository Structure

```text
workflows/
├── image-generation/
│   ├── anima/
│   ├── flux2_klein_9B/
│   ├── ideogram4/
│   ├── imagefactory/
│   ├── krea2/
│   ├── noobai/
│   └── zit/
├── image-manipulation/
│   ├── birefnet/
│   └── codeformer/
└── video-generation/
    ├── ltx23/
    └── wan22/
    
## Design Philosophy

FisherKing workflows are designed around a few practical principles:

- Practical and reusable reference implementations
- Productivity-oriented workflow design
- Modular and understandable architectures
- Low-VRAM accessibility where practical
- Local-first image and video generation
- Useful foundations for experimentation and customization

## Usage

Workflow files are provided as ComfyUI JSON workflows.

Download the required workflow and load it into ComfyUI. Model requirements, custom nodes, configuration, and other implementation details may vary between workflows.

Individual workflows may include additional documentation and guidance directly within the workflow.

## CivitAI

The FisherKing Series workflows are also available on the [FisherKing CivitAI profile](https://civitai.com/user/fisherking786/models).

## Status

The FisherKing Series is actively maintained and expanded as new workflows are developed and existing implementations are updated.