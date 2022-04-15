# Coco Manager


* Reads the annotations from a JSON file (i.e. `"instances_train2017.json"`)


* Reads the images either from the disk (i.e. from `"COCO/train2017/"` folder), or by downloading them from `coco_urls` provided in annotations JSON file


* Selects all of the Coco classes (`81` classes total), or produces a subset to scale according to the project (i.e. if `classes = ['person']`, it will find all of the images with a person, and delete all other bounding boxes and masks from them)


* Pads the images so their shapes are a multiple of some number (i.e. a multiple of `32` for a `VGG-FCN` architecture)


* Shows the image alongside the semantic masks of the objects


* Fits easily into a `pytorch` DataLoader (see [Usage_Coco_Manager.ipynb](https://github.com/McCastles/Coco_Manager/blob/master/Usage_Coco_Manager.ipynb))



## Files


[Coco_Manager.ipynb](https://github.com/McCastles/Coco_Manager/blob/master/Coco_Manager.ipynb): for being imported in a project


[Usage_Coco_Manager.ipynb](https://github.com/McCastles/Coco_Manager/blob/master/Usage_Coco_Manager.ipynb): use case and functionality explanation




![img](https://sun9-43.userapi.com/impf/ikNqTFqmSI4wBvPikUebIoaqEygPvJqhV__gNA/FDAIs_3dSHE.jpg?size=1218x851&quality=95&sign=6d9a71b3081a84bc0fba9645856e3e63&type=album)