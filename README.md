# MotionShop: Zero-Shot Motion Transfer in Video Diffusion Models with Mixture of Score Guidance
[Hidir Yesiltepe](https://sites.google.com/view/hidir-yesiltepe), [Tuna Han Salih Meral](https://tunahansalih.github.io/), [Connor Dunlop](https://sanghani.cs.vt.edu/person/connor-dunlop/), [Pinar Yanardag](https://pinguar.org/)

<a href='#'><img src='https://img.shields.io/badge/ArXiv-1234-red'></a>
<a href='https://motionshop-diffusion.github.io/'><img src='https://img.shields.io/badge/Project-Page-green'></a>
<a href='https://motionshop-diffusion.github.io/supp.html'><img src='https://img.shields.io/badge/Supplementary-Page-yellow'></a>

![teaser](assets/teaser.gif)

## Abstract
> In this work, we propose the first motion transfer approach in diffusion transformer through Mixture of Score Guidance (MSG), a theoretically-grounded framework for motion transfer in diffusion models. Our key theoretical contribution lies in reformulating conditional score to decompose motion score and content score in diffusion models. By formulating motion transfer as a mixture of potential energies, MSG naturally preserves scene composition and enables creative scene transformations while maintaining the integrity of transferred motion patterns. This novel sampling operates directly on pre-trained video diffusion models without additional training or fine-tuning. Through extensive experiments, MSG demonstrates successful handling of diverse scenarios including single object, multiple objects, and cross-object motion transfer as well as complex camera motion transfer. Additionally, we introduce MotionBench, the first motion transfer dataset consisting of 200 source videos and 1000 transferred sequences, covering single/multi-object transfers, and complex camera motions.
