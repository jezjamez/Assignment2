To Run Docker:

sudo docker run --gpus all -it -p 8888:8888  -it --rm -v /path-to-assignment2-directory:/work --ipc=host --ulimit memlock=-1 --ulimit stack=67108864  nvcr.io/nvidia/pytorch:22.06-py3

Change to Working Directory:

cd /work

For training run train.ipynb
For inference run inference.ipynb

Change test_images_path for giving new test directory

Results are available in results.csv