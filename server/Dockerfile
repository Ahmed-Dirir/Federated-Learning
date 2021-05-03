From python

WORKDIR .

RUN pip install flask
RUN pip install --no-cache-dir numpy


COPY . .

EXPOSE 5000

CMD ["python", "server.py"]
