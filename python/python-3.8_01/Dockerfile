FROM python:3.8
ADD . /app
#RUN apt update -y && apt install libgl1-mesa-glx -y
RUN apt update -y && \
    apt install libgl1-mesa-glx wkhtmltopdf -y && \
    pip install future && \
    pip install six && \
    pip install numpy
RUN pip install -r /app/requirements.txt
#https://pypi.tuna.tsinghua.edu.cn/simple
