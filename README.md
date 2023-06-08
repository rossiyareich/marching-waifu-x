# marching-waifu-x

<p>
    <a href="https://github.com/rossiyareich/marching-waifu-x/blob/main/LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/rossiyareich/marching-waifu-x">
    </a>
</p>

Complete 3D character + animation generation based on ControlVideo, Grounding DINO, Segment Anything, InstantNGP, and T2M-GPT

- End-To-End
<br>[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rossiyareich/marching-waifu-x/blob/main/ipynb/end2end_colab.ipynb)

## Related resources:
- [huggingface/diffusers](https://github.com/huggingface/diffusers)
    - [rossiyareich/aniflatmixAnimeFlatColorStyle_v20-fp16](https://huggingface.co/rossiyareich/aniflatmixAnimeFlatColorStyle_v20-fp16)
    - [rossiyareich/anything-v4.0-vae](https://huggingface.co/rossiyareich/anything-v4.0-vae)
    - [AsciiP/badhandv4](https://huggingface.co/AsciiP/badhandv4)
    - [gsdf/EasyNegative](https://huggingface.co/datasets/gsdf/EasyNegative)
- [YBYBZhang/ControlVideo](https://github.com/YBYBZhang/ControlVideo)
- [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
- [IDEA-Research/Grounded-Segment-Anything](https://github.com/IDEA-Research/Grounded-Segment-Anything)
- [NVlabs/instant-ngp](https://github.com/NVlabs/instant-ngp)
- [camenduru/instant-ngp-colab](https://github.com/camenduru/instant-ngp-colab)
- [Mael-zys/T2M-GPT](https://github.com/Mael-zys/T2M-GPT.git)
- [softcat477/SMPL-to-FBX](https://github.com/softcat477/SMPL-to-FBX)
- [rossiyareich/ldm-ckpt-conversion](https://github.com/rossiyareich/ldm-ckpt-conversion.git)
- [veryBadImageNegative](https://civitai.com/models/11772/verybadimagenegative)
- [OpenPoseBones_v9](https://toyxyz.gumroad.com/l/ciojz)
- [genshin-style-anime-female-base-mesh-for-blender](https://sketchfab.com/3d-models/genshin-style-anime-female-base-mesh-for-blender-c2d6727e8c9742feb9a4a3bccac6e0e0)

## To-do:
- [x] ControlVideo + RealESRGAN pipeline
- [x] 1st-order MultistepDPM++ Karras
- [x] 2nd-order MultistepDPM++ Karras
- [x] New generation scheme + format
- [x] MultiControlNet
- [x] Multiprompt
- [x] Upscaled preview video
- [x] Grounding DINO + Segment Anything
- [x] Render new blender views
- [x] Update inference parameters
- [x] Add more embeddings, increase resolution
- [x] Switch out main checkpoint
- [x] Fix setup scripts, separate notebooks into local windows, local linux, colab
- [x] Fix conditioning images
- [x] InstantNGP
- [ ] Prepare `base_cam.json` for InstantNGP
- [ ] T2M-GPT + SMPL-to-FBX
- [ ] bpy processing + rigging + retargeting
- [ ] Evaluation
- [ ] Deployment on Replicate/Gradio
- [ ] Medium article
