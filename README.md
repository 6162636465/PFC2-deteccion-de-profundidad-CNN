## PFC2-deteccion-de-profundidad-CNN
en este repositorio se propondra para usar una una tecnica para deteccion de profundidad usando imagenes stereo
para eso se evaluara 2 tecnicas , la tecnica base y la propuesta que en mi caso sera ralft stereo 
## Dataset:
La dataset usada para evaluar y entrenar ambos modelos pertenece a [KITTI](https://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo) 
los datos usados fueron los de tereo 2015 de 2(GB)
## implementación:
se uso una gpu:rtx2060 con 200 epocas de entrenamientos para ambos modelos se uso la carpeta Train del data set para entrenar con las perspectivas de image_0 e image_1 para tomar la perspectiva de ambas camaras y se validara con la carpeta testing.
#como parametros tomaremos:
-tiempo de ejecucion
-End Point Error
-Validation Error
estos parametros fueron sacados de  [unimatch](https://github.com/autonomousvision/unimatch) que compara diversos modelos de deteccion de profundidad con imagenes
![Screenshot_3](https://github.com/6162636465/PFC2-deteccion-de-profundidad-CNN/assets/40539959/0b14fb6f-26b0-46d6-a937-dac67794ffa9)
