# 3D Human Avatar Generation


 
<table class="center">
<tr>
  <td style="text-align:center;"><b>Mesh Video</b></td>
  <td style="text-align:center;" colspan="2"><b>Output Video</b></td>
</tr>
  
<tr>
  <td><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/c43338fd-11b2-495f-806f-8dc4cd2f5fe0.gif"></td>

  <td><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/e0df201a-4d95-4d4c-853d-4580a4b933a1.gif"></td>
  <td><img src="https://github.com/saba99/Enhanced_3DHuman_Geneartion/assets/33378412/c43338fd-11b2-495f-806f-8dc4cd2f5fe0.gif"></td>
  

 
</tr>

<tr>
  <td width=25% style="text-align:center;color:gray;">"A man is skiing"</td>
  <td width=25% style="text-align:center;">"Wonder Woman, is skiing"</td>
  <td width=25% style="text-align:center;">"A little girl is skiing "</td>
</tr>
     
<tr>
  <td><img src=".gif"></td>
  <td><img src=".gif"></td>
  <td><img src=""></td>              
 
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A rabbit is eating a watermelon"</td>
  <td width=25% style="text-align:center;">"A cat is eating a watermelon on the table"</td>
  <td width=25% style="text-align:center;">"A puppy is eating a cheeseburger on the table, comic style"</td>
 </tr>

<tr>
  <td><img src=".gif"></td>
  <td><img src=".gif"></td>              
  <td><img src=".gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A jeep car is moving on the road"</td>
  <td width=25% style="text-align:center;">"A car is moving on the road, cartoon style"</td>
  <td width=25% style="text-align:center;">"A car is moving on the snow"</td>

 
</tr>


<!-- <tr>
  <td><img src=".gif"></td>
  <td><img src=".gif"></td>
  <td><img src=".gif"></td>              
  <td><img src=".gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A lion is roaring"</td>
  <td width=25% style="text-align:center;">"A tiger is roaring"</td>
  <td width=25% style="text-align:center;">"A lion is roaring, Van Gogh style"</td>
  <td width=25% style="text-align:center;">"A wolf is roaring in New York City"</td>
</tr> -->

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




