FROM arm64v8/python:3.11.3-bullseye
WORKDIR /app
COPY . .
RUN pip3 install -r requirements.txt
EXPOSE 5001
CMD ["python3", "app.py"]