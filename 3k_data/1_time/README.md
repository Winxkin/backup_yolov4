Data tranning: store_data(1k) + store_improve_1k7 (1k7) => total = 2k7 data
epoch: 0 -> 6000



Note last log:
    class_id = 0, name = empty, ap = 41.45%   	 (TP = 1072, FP = 1067) 
    class_id = 1, name = object, ap = 61.66%   	 (TP = 51775, FP = 26549) 

    for conf_thresh = 0.25, precision = 0.66, recall = 0.67, F1-score = 0.66 
    for conf_thresh = 0.25, TP = 52847, FP = 27616, FN = 25658, average IoU = 49.37 % 

    IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
    mean average precision (mAP@0.50) = 0.515547, or 51.55 % 

    Set -points flag:
    `-points 101` for MS COCO 
    `-points 11` for PascalVOC 2007 (uncomment `difficult` in voc.data) 
    `-points 0` (AUC) for ImageNet, PascalVOC 2010-2012, your custom dataset

    mean_average_precision (mAP@0.50) = 0.515547 
    If you want to train from the beginning, then use flag in the end of training command: -clear  
