FROM python:3.8-slim
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
EXPOSE $PORT
ENTRYPOINT [ "streamlit","run","app.py","--server.port=$PORT","--server.address=0.0.0.0" ]