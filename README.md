# traffic-light-detector
This project is developed based on mmdetection. Please refer to the tutorial: https://github.com/open-mmlab/mmdetection

Only a simple installation reference is provided here.

conda create -n openmmlab python=3.7 pytorch==1.6.0 cudatoolkit=10.1 torchvision -c pytorch -y

conda activate openmmlab

pip install openmim

mim install mmcv-full

git clone https://github.com/open-mmlab/mmdetection.git

cd mmdetection

pip install -r requirements/build.txt

pip install -v -e .

git clone https://github.com/ljyw17/traffic-light-detector.git
