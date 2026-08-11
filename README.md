


## ⭐Features
- **📦400+ AI Models**: Rich, high-quality AI models, including CV, NLP, Speech, Video and Cross-Modal. 
- **🧒Easy to Use**: 3 lines of code to predict 400+ AI models.
- **💁Model As Service**: Easy to serve model with only one line of command.
- **💻Cross-platform**: Support Linux, Windows and MacOS.

### 💥Recent Updates
- **🔥2022.08.19:** The v2.3.0 version is released 🎉
  -  Supports [**ERNIE-ViLG**](./modules/image/text_to_image/ernie_vilg)([HuggingFace Space Demo](https://huggingface.co/spaces/PaddlePaddle/ERNIE-ViLG))
  -  Supports [**Disco Diffusion (DD)**](./modules/image/text_to_image/disco_diffusion_clip_vitb32) and [**Stable Diffusion (SD)**](./modules/image/text_to_image/stable_diffusion)

- **2022.02.18:** Release models to HuggingFace [PaddlePaddle Space](https://huggingface.co/PaddlePaddle)

- For more previous release please refer to [**PaddleHub Release Note**](./docs/docs_en/release.md)


<a name="demos"></a>
## 🌈Visualization Demo


#### 🏜️ [Text-to-Image Models](https://github.com/PaddlePaddle/PaddleHub/tree/develop/modules/image/text_to_image)
<div align="center">
<table>
    <tr>
        <td><img src="https://user-images.githubusercontent.com/59186797/200235049-fefa7642-6c4c-4f93-bd84-3b36a8a80595.gif"  width = "100%"></td>
        <td><img src="https://user-images.githubusercontent.com/59186797/200244625-77310db8-c9b2-4293-8fe9-c9aae27ee462.gif" width = "80%"></td>
        <td><img src="https://user-images.githubusercontent.com/59186797/200245387-daaf576d-8224-4937-82b8-27e31ee2df16.gif" width = "100%"></td>
    <tr>
    <tr>
        <td align="center"><a href="https://github.com/PaddlePaddle/PaddleHub/tree/develop/modules/image/text_to_image/ernie_vilg">Wenxin Big Models</a></td>
        <td align="center"><a href="https://github.com/PaddlePaddle/PaddleHub/tree/develop/modules/image/text_to_image/stable_diffusion">Stable_Diffusion series</a></td>
        <td align="center"><a href="https://github.com/PaddlePaddle/PaddleHub/tree/develop/modules/image/text_to_image/disco_diffusion_ernievil_base">Disco Diffusion series</a></td>
        
<tr>

<tr>
        <td align="center">Include ERNIE-ViLG, ERNIE-ViL, ERNIE 3.0 Zeus, supports applications such as text-to-image, writing essays, summarization, couplets, question answering, writing novels and completing text。</td>
        <td align="center">Supports functions such as text_to_image, image_to_image, inpainting, ACGN external service, etc.</td>
        <td align="center">Support Chinese and English input</td>
        
<tr>

</table>
</div>




#### 👓 [Computer Vision Models](./modules#Image)
<div align="center">
<img src="./docs/imgs/Readme_Related/Image_all.gif"  width = "530" height = "400" />
</div>


- Many thanks to CopyRight@[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR), [PaddleDetection](https://github.com/PaddlePaddle/PaddleDetection)、[PaddleGAN](https://github.com/PaddlePaddle/PaddleGAN), [AnimeGAN](https://github.com/TachibanaYoshino/AnimeGANv2)、[openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)、[PaddleSeg](https://github.com/PaddlePaddle/PaddleSeg), [Zhengxia Zou](https://github.com/jiupinjia/SkyAR)、[PaddleClas](https://github.com/PaddlePaddle/PaddleClas) for the pre-trained models, you can try to train your models with them.


#### 🎤 [Natural Language Processing Models](./modules#Text)
<div align="center">
<img src="./docs/imgs/Readme_Related/Text_all.gif"  width = "640" height = "240" />
</div>

- Many thanks to CopyRight@[ERNIE](https://github.com/PaddlePaddle/ERNIE)、[LAC](https://github.com/baidu/LAC)、[DDParser](https://github.com/baidu/DDParser)for the pre-trained models, you can try to train your models with them.



#### 🎧 [Speech Models](./modules#Audio)
<div align="center">
<table>
    <thead>
        <tr>
            <th width=250> Input Audio  </th>
            <th width=550> Recognition Result  </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align = "center">
            <a href="https://Multimodalspeech.bj.bcebos.com/MultimodalAudio/en.wav" rel="nofollow">
                    <img align="center" src="./docs/imgs/Readme_Related/audio_icon.png" width=250 ></a><br>
            </td>
            <td >I knocked at the door on the ancient side of the building.</td>
            </tr>
            <tr>
            <td align = "center">
            <a href="https://Multimodalspeech.bj.bcebos.com/MultimodalAudio/zh.wav" rel="nofollow">
                    <img align="center" src="./docs/imgs/Readme_Related/audio_icon.png" width=250></a><br>
            </td>
           
        </tr>
    </tbody>
</table>
</div>
<div align="center">
<table>
    <thead>
    </thead>
    <tbody>
        <tr>
            <th>Input Text </th>
            <th>Output Audio </th>
        </tr>
        <tr>
            <th>Life was like a box of chocolates, you never know what you're gonna get.</th>
            <th>
            <a href="https://paddlehub.bj.bcebos.com/resources/fastspeech_ljspeech-0.wav">
            <img src="./docs/imgs/Readme_Related/audio_icon.png" width=250 /></a><br>
            </th>
        </tr>
    </tbody>
</table>
</div>

- Many thanks to CopyRight@[PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech) for the pre-trained models, you can try to train your models with PaddleSpeech.



## ✈️QuickStart

#### 🚁The installation of required components.
```python
# install paddlepaddle with gpu
# !pip install --upgrade paddlepaddle-gpu

# or install paddlepaddle with cpu
!pip install --upgrade paddlepaddle

# install paddlehub
!pip install --upgrade paddlehub
```


<a name="License"></a>
## 📚License
The release of this project is certified by the <a href="./LICENSE">Apache 2.0 license</a>.


