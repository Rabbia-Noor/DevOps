FROM ubuntu
LABEL maintainer="rabbianoor01@gmail.com"
RUN apt-get update && apt-get install -y python3
ENV PAGE_TITLE="Hello from DevOps"
WORKDIR /app
RUN echo "<title>$PAGE_TITLE</title><h1>I am a DevOps engineer</h1>" > index.html
EXPOSE 3000
CMD ["python3", "-m", "http.server", "3000", "--bind", "0.0.0.0"]
