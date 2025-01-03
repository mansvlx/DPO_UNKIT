### Обучал модель YOLOv3  
### dataset - [https://huggingface.co/datasets/arnavmahapatra/fruit-detection-dataset](https://huggingface.co/datasets/arnavmahapatra/fruit-detection-dataset)  

* Использовал данные всего датасета,разметку делал через Roboflow

* Обучение модели длилось 180 поколений, дальнейшее обучение сочёл не разумным

* Модель умеет определять яблоки, апельсины и бананы
_____________________________________________________________________________________________________________________
**Для обнаружения объектов необходимо ввести в терминал следующие команды:**
1. >***cd ~/IDEProjects/PythonProject/PyTorch-YOLOv3***
2. >***poetry run yolo-detect -m data/fruits.cfg -w data/fruits.pth -c data/classes.names -i detection_input -o detection_result***
 
