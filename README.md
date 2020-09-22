# resilience_detection

Most code from this Pytorch tutorial. Refer to it for more information:
https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html

A customized dataloader is implemented in `Pytorch_custom_dataloader.py` as class `Image_list_dataloader`.

`Image_list_dataloader` received an csv file and a image directory. In the csv file, the first column is the image name, and the second column is the class_id (from 0 - N).
