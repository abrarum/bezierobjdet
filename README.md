# bezierobjdet

Important files/folders:

1. TESTS - entry point
    - dataset_maker -> To produce dataset and xmls
    - scripts -> from pre-processing to training and evaluation
    - infer -> takes in model, and infer features
    
2. TESTS/workspace
    - models tested with
    
3. TESTS/workspace/*
    - annotations -> tfrecords and xmls
    - exported-models -> generated custom model
    - images -> all the custom images in train/test folder
    - models -> all the generated checkpoints during training
    - pre-trained-models -> all tested models used as a placeholder

Related papers:

1.https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_ABCNet_Real-Time_Scene_Text_Spotting_With_Adaptive_Bezier-Curve_Network_CVPR_2020_paper.pdf
2.https://arxiv.org/abs/1901.03781
3.Line Segment Detection Using Transformers without Edge [https://arxiv.org/pdf/2101.01909v1.pdf]

Dataset (./datasets)
1. (1242 images / 500x500 / ../DATA)
https://openaccess.thecvf.com/content/ACCV2020/html/Abdelfattah_TTPLA_An_Aerial-Image_Dataset_for_Detection_and_Segmentation_of_Transmission_ACCV_2020_paper.html

2. Wood stems