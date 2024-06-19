# TinyML course
 Code written while learning TinyML using [this book](https://tinymlbook.com/). Example code from the book can be found [here](https://github.com/tensorflow/tflite-micro/tree/main/tensorflow/lite/micro/examples).

## Setup
To run TensorFlow you need Linux OS. I recommend using Ubuntu or Debian. If you don't have a Linux PC you can install Ubuntu on Windows using WSL - just go to the Microsoft Store and search for Ubuntu. You should also be able to use Raspberry Pi with Raspberry Pi OS, but I haven't tested that.

### Install required tools
``` bash
sudo apt install python3 python3-pip python3-venv git
```

### Create Python virtual environment and activate it
``` bash
python3 -m venv tinyml
source tinyml/bin/activate
```

### Clone repository
``` bash
git clone https://github.com/szajakubiak/TinyML-course.git
```

### Install requirements
``` bash
cd TinyML-course
pip install -r requirements.txt
```

### Run Jupyter Lab
``` bash
jupyter lab --no-browser
```
You can skip *--no-browser* if you are using PC with Linux installed as a main OS. In such case web browser will be opened with Jupyter Lab tab. If you are on a virtual Linux machine it's better to start web browser on your main system (Windows in my case) and paste in the adress bar link which you will get in the terminal window starting with *localhost:8888/lab* or *127.0.0.1:8888/lab*. Remember to copy the full link with the access token.
