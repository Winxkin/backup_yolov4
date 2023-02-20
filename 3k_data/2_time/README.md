epoch : 6000 -> 10000

last log:

    class_id = 0, name = empty, ap = 43.91%   	 (TP = 1107, FP = 1031) 
    class_id = 1, name = object, ap = 63.24%   	 (TP = 52255, FP = 25060) 

    for conf_thresh = 0.25, precision = 0.67, recall = 0.68, F1-score = 0.68 
    for conf_thresh = 0.25, TP = 53362, FP = 26091, FN = 25143, average IoU = 50.70 % 

    IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
    mean average precision (mAP@0.50) = 0.535772, or 53.58 % 

    Set -points flag:
    `-points 101` for MS COCO 
    `-points 11` for PascalVOC 2007 (uncomment `difficult` in voc.data) 
    `-points 0` (AUC) for ImageNet, PascalVOC 2010-2012, your custom dataset

    mean_average_precision (mAP@0.50) = 0.535772 
    If you want to train from the beginning, then use flag in the end of training command: -clear 