# 🚀 DeepSeek OCR - React + FastAPI

Modern OCR web application powered by DeepSeek-OCR with a stunning React frontend and FastAPI backend.

![DeepSeek OCR in Action](assets/multi-bird.png)

# Hướng dẫn cài đặt

Hướng dẫn cài đặt & chạy trên Windows 10 x64

## Phần 1: cài đặt backend

## Cài đặt CUDA và cuDNN



### Cài đặt Python 

Cài đặt Python 3.10 x64

### Cài đặt virtual environment (tùy chọn)

Vào folder **backend** tạo virtual environment

`virtualenv venv`

Active virtual environment

`venv\Scripts\activate`


### Cài đặt Python package

`pip install -r requirements.txt`

### Cài đặt PyTorch CUDA

pip install torch --index-url https://download.pytorch.org/whl/cu118

## Phần 2: cài đặt frontend

### Cài đặt NodeJS 18.20

### Cài đặt JS packages

Vào folder **frontend** cài đặt JS packages bằng lệnh:

`npm install`


## Phần 3: chạy server

### Chạy backend

Chạy file **start_backend.bat** hoặc chạy lệnh sau trong folder backend

`python -m uvicorn main:app --host 0.0.0.0 --port 8000`

### Chạy frontend

Chạy file **start_frontend.bat** hoặc chạy lệnh sau trong folder frontend

`npm run dev`