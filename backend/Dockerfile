FROM nvidia/cuda:12.4.0-runtime-ubuntu22.04

WORKDIR /usr/src/app

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 7861

CMD ["python", "app.py"]
