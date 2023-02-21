class_id = 0, name = empty, ap = 48.89%   	 (TP = 6508, FP = 5068) 

 for conf_thresh = 0.25, precision = 0.56, recall = 0.48, F1-score = 0.52 
 for conf_thresh = 0.25, TP = 6508, FP = 5068, FN = 7010, average IoU = 40.21 % 

 IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
 mean average precision (mAP@0.50) = 0.488903, or 48.89 % 

Set -points flag:
 `-points 101` for MS COCO 
 `-points 11` for PascalVOC 2007 (uncomment `difficult` in voc.data) 
 `-points 0` (AUC) for ImageNet, PascalVOC 2010-2012, your custom dataset

 mean_average_precision (mAP@0.50) = 0.488903 
New best mAP!
If you want to train from the beginning, then use flag in the end of training command: -clear 