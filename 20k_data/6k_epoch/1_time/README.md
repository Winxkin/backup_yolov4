
20k data training with 6k epoch

output:
    class_id = 0, name = empty, ap = 19.41%   	 (TP = 2198, FP = 2909) 
    class_id = 1, name = object, ap = 51.93%   	 (TP = 220799, FP = 178765) 

    for conf_thresh = 0.25, precision = 0.55, recall = 0.65, F1-score = 0.60 
    for conf_thresh = 0.25, TP = 222997, FP = 181674, FN = 120627, average IoU = 41.53 % 

    IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
    mean average precision (mAP@0.50) = 0.356693, or 35.67 % 

    Set -points flag:
    `-points 101` for MS COCO 
    `-points 11` for PascalVOC 2007 (uncomment `difficult` in voc.data) 
    `-points 0` (AUC) for ImageNet, PascalVOC 2010-2012, your custom dataset

    mean_average_precision (mAP@0.50) = 0.356693 
    New best mAP!
    If you want to train from the beginning, then use flag in the end of training command: -clear 