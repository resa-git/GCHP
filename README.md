# GCHP Repository

This repository contains the implementation of the General Compound Hawkes Process (GCHP), a mathematical model used for predicting price volatility in financial markets.

## Code
The `Code` folder contains the implementation of GCHP. For information about the list of files, please refer to the `ReadMe.md` in the folder.

## Setup Docker
Using a Docker image can simplify the setup process to run the code!

### For Linux Systems
Navigate to the `docker` folder and build the Docker image by running the following command:
```sh
docker build -t [dockerUserName]/hawkes:latest .

### To run on a Linux system:
```sh
sudo docker run --rm -it -p 8888:8888 -v "$(pwd)"/GCHP:/home/jovyan/work [dockerUserName]/hawkes:latest /bin/bash

### To run on a Windows system:
```sh
sudo docker run --rm -it -p 8888:8888 -v %cd%/GCHP:/home/jovyan/work [dockerUserName]/hawkes:latest /bin/bash

## Additional Information
For more details and clarifications, please refer to the respective **ReadMe.md** files within each folder. This repository is intended to provide a clear and concise implementation of GCHP for those interested in financial market predictions and analysis.

### Notes:
- Replace `[dockerUserName]` with your Docker username or the appropriate name you wish to use.
- Ensure that the Docker commands are correct and tested, as they are written based on the provided information.



