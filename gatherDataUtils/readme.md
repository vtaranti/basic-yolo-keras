## Gather COCO data and convert annotations to pascal format  

  
    + Download COCO detection data from http://cocodataset.org/#download  
        + http://images.cocodataset.org/zips/train2014.zip <= train images  
        + http://images.cocodataset.org/zips/val2014.zip <= validation images  
        + http://images.cocodataset.org/annotations/annotations_trainval2014.zip <= train and validation annotations  
    + Run this script to convert annotations in COCO format to VOC format  
        + https://gist.github.com/chicham/6ed3842d0d2014987186#file-coco2pascal-py  


wget http://images.cocodataset.org/zips/train2014.zip    
wget http://images.cocodataset.org/zips/val2014.zip   
wget http://images.cocodataset.org/annotations/annotations_trainval2014.zip  
wget https://gist.github.com/chicham/6ed3842d0d2014987186#file-coco2pascal-py  


using the script:
>>  ./coco2pascal.py create_annotations ./ train ./pascalAnno/train2014/  
>>  ./coco2pascal.py create_annotations ./ val ./pascalAnno/val2014/  


