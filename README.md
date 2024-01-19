# 3D Human Avatar Generation

![render_color (5)](https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/114cc68e-f409-4f9a-a343-787391157c54)

![render_color (7)](https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/076c7e20-38cb-4f47-9a17-abd36d8e140b)


<table class="center">
      <tr >
      <td  style="border: none; text-align: center">Video</td>
      <td  style="border: none; text-align: center">Video</td>
      <td  style="border: none; text-align: center">Video</td>
      <td  style="border: none; text-align: center">Video</td>
      </tr>
      <tr>
      <td style="border: none"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/3690e2bf-154f-4991-831d-577d6636d949.gif"></td>
      <td style="border: none"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/6705a629-5a3b-46b1-a62e-d325e2199e2e.gif"></td>
      <td style="border: none"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/acceaac4-71e1-40e9-9529-733fbc11c0b8.gif"></td>
      <td style="border: none"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/114cc68e-f409-4f9a-a343-787391157c54.gif"></td>    
      </tr>
      <tr >
      <td  style="border: none; text-align: center"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/34ea0ec7-3ff2-4b9c-bbf3-bb399ed37be5.gif"></td>
      <td  style="border: none; text-align: center"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/b97b834e-f7c3-4b38-b480-c0d637ac41a5.gif"></td>
      <td  style="border: none; text-align: center"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/8ab1e3e2-a578-4283-a41d-ef346880d717.gif"></td>
      <td  style="border: none; text-align: center"><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/076c7e20-38cb-4f47-9a17-abd36d8e140b.gif"></td>
      </tr>
      <tr >
      <td  style="border: none; text-align: center">Mesh </td>
      <td  style="border: none; text-align: center">Mesh </td>
      <td  style="border: none; text-align: center">Mesh </td>
      <td  style="border: none; text-align: center">Mesh </td>
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




