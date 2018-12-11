# Pothole-Crack-Detection_MRCNN

#Step 1 Clone the repo
```bash
git clone https://github.com/jerofad/Pothole-Crack-Detection_MRCNN
```
#Step 2 Change direcrory to the new repo:
```bash
cd Pothole-Crack-Detection_MRCNN
```

#Step 3 Download the pre-trained MRCNN model
```bash
wget https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5
```
#Step 4: Run the training on the dataset
```bash
python pot_crack.py train --dataset=datasets/pot-crack/ --weights=coco.
```
Goodluck. If you need any help please do contact.
