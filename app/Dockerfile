FROM python:3.9-slim

WORKDIR /code 

COPY ./requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple

# COPY ./main.py /code

EXPOSE 5050

CMD ["python", "main.py"]


