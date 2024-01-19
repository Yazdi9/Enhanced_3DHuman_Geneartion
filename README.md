# 3D Human Avatar Generation

<img  src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/3690e2bf-154f-4991-831d-577d6636d949.gif" >
<img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/acceaac4-71e1-40e9-9529-733fbc11c0b8.gif">
<img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/34ea0ec7-3ff2-4b9c-bbf3-bb399ed37be5.gif">

<table class="center">
      <tr >
      <td  style="border: none; text-align: center">Video/Prompt(word base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(word base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(word base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(word base)</td>
      </tr>
      <tr>
      <td style="border: none"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/3690e2bf-154f-4991-831d-577d6636d949.gif"></td>
      <td style="border: none"><img src="Results/2-cut-tusuncub-walking-in-the-snow,-blurry,-looking-at-viewer,.gif"></td>
      <td style="border: none"><img src="Results/3-character-design,-cyberpunk-tusun-kitten-wearing-astronaut-suit,-sci-fic,-realistic.gif"></td>
      <td style="border: none"><img src="Results/2-best-quality,-masterpiece,-photorealistic,-1girl,-light-smile,-shirt-with-collars,.gif"></td>    
      </tr>
      <tr >
      <td  style="border: none; text-align: center">girl,-offshoulder,-light-smile,-shiny-skin-best-quality,-masterpiece,-photorealistic </td>
      <td  style="border: none; text-align: center">cut-tusuncub-walking-in-the-snow,-blurry,-looking-at-viewer</td>
      <td  style="border: none; text-align: center">character-design,-cyberpunk-tusun-kitten-wearing-astronaut-suit,-sci-fic,-realistic</td>
      <td  style="border: none; text-align: center">best-quality,-masterpiece,-photorealistic,-1girl,-light-smile,-shirt-with-collars</td>
      </tr>
      <tr >
      <td  style="border: none; text-align: center">Video/Prompt(Sentence base) </td>
      <td  style="border: none; text-align: center">Video/Prompt(Sentence base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(Sentence base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(Sentence base)</td>
      </tr>
       <td style="border: none"><img src="Results/ezgif.com-video-to-gif.gif"></td>
      <td style="border: none"><img src="Results/ezgif.com-video-to-gif (3).gif"></td>
      <td style="border: none"><img src="Results/ezgif.com-video-to-gif (1).gif"></td>
      <td style="border: none"><img src="Results/ezgif.com-video-to-gif (2).gif"></td>
      </tr>
       <tr >
      <td  style="border: none; text-align: center">The_astronaut_dances_in_futuristic..</td>
      <td  style="border: none; text-align: center">A_daring_man_performing_gravity-defying</td>
      <td  style="border: none; text-align: center">A_daring_man_is_scaling_a_treacherous..</td>
      <td  style="border: none; text-align: center">A_mighty_elephant_marches_steadily.</td>
      </tr>
</table>

## Installation
```bash
conda create -n en3d python=3.8
conda activate en3d
pip install -r requirements.txt
```

## Quick Start

```bash
python app.py
```

### Synthetic avatar library

We released a Rigged & Animated 3D Human library (3DHuman-Syn), containing ~1000 characters produced by En3D, and 1000+ actions are provided for animation.

- Avatar download and rendering
```bash
python render.py
```

- Avatar animation
```bash
python animation.py
```


- AR application <img src="https://img.shields.io/badge/Open in-iphone-blue" alt="google colab logo"></a> 


Convert the generated animation file (.glb) to .usdz format using Sketchfab (upload glb and download usdz) or other tools, and insert the animated avatar to web with [model-viewer](https://modelviewer.dev/).

AR function is only supported with iPhone, try the [AR example](https://3d-studio123.github.io/) in the phone browser and click the right-down icon for AR experience.




