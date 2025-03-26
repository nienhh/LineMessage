# 使用官方 Python 映像檔
FROM python:3.10

# 設定工作目錄
WORKDIR /app

# 複製檔案進容器
COPY . /app

# 安裝依賴
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

# 設定執行指令
CMD ["python", "webhook_server.py"]
