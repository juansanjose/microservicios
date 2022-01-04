FROM python:3.6.9

ENV GROUP_NUMBER=02

WORKDIR /home/juansj2000/practica_creativa2/bookinfo/src/productpage


COPY requirements.txt requirements.txt

RUN pip3 install -r /home/juansj2000/practica_creativa2/bookinfo/src/productpage/requirements.txt 



COPY . .

CMD ["python3","productpage.py","9080"]
