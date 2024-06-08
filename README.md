## PFC2-deteccion-de-profundidad-CNN
en este repositorio se propondra para usar una una tecnica para deteccion de profundidad usando imagenes stereo
para eso se evaluara 2 tecnicas , la tecnica base y la propuesta que en mi caso sera ralft stereo 
## Arquitectura de Raft stereo:
![RAFTStereo](https://github.com/6162636465/PFC2-deteccion-de-profundidad-CNN/assets/40539959/1a0ce4b9-643c-467d-975b-6ab72310905c)
## Arquitectura de Base stereo:
![OpenStereo](https://github.com/6162636465/PFC2-deteccion-de-profundidad-CNN/assets/40539959/a8384ddc-3824-4915-b41e-f528fd683795)
## Dataset:
La dataset usada para evaluar y entrenar ambos modelos pertenece a [KITTI](https://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo) 
los datos usados fueron los de tereo 2015 de 2(GB)
## implementación:
![Screenshot_2](https://github.com/6162636465/PFC2-deteccion-de-profundidad-CNN/assets/40539959/26d2da07-a6a5-4296-8a19-2ca710b7cdfe)
se uso una gpu:rtx2060 con 200 epocas de entrenamientos para ambos modelos se uso la carpeta Train del data set para entrenar con las perspectivas de image_0 e image_1 para tomar la perspectiva de ambas camaras y se validara con la carpeta testing.
## como parametros tomaremos:
-tiempo de ejecucion
-End Point Error
-Validation Error
estos parametros fueron sacados de  [unimatch](https://github.com/autonomousvision/unimatch) que compara diversos modelos de deteccion de profundidad con imagenes
![Screenshot_3](https://github.com/6162636465/PFC2-deteccion-de-profundidad-CNN/assets/40539959/0b14fb6f-26b0-46d6-a937-dac67794ffa9)
## grafica de parametros:
![Figure_1](https://github.com/6162636465/PFC2-deteccion-de-profundidad-CNN/assets/40539959/47b4f419-fdcc-48eb-944e-948b2124683a)
![Figure_2](https://github.com/6162636465/PFC2-deteccion-de-profundidad-CNN/assets/40539959/4e64433c-4335-4c8d-8914-c8921f6b46d5)
esto nos da la conclusion que el modelo raft stereo es mejor que el base
