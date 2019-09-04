To run this repository,

Fulfill the requirements mentioned in requirements.txt file

Download the pre-trained weight from https://drive.google.com/file/d/1OmCKlUEYmTjg_jaaN-IQm81eHROU-Gyl/view?usp=sharing

To run the system with pre trained weight run after cloning the repo,
 
python3 test_frcnn.py -p test_images 

To train the system yourself run from project directory,

python3 train_frcnn.py -o simple -p annotate.txt

Mentions: This repository has been created from the following blogs and repos,

https://www.analyticsvidhya.com/blog/2018/11/implementation-faster-r-cnn-python-object-detection/

https://github.com/Shenggan/BCCD_Dataset

https://github.com/kbardool/keras-frcnn