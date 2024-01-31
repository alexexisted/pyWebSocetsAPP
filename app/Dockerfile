FROM python:3.11
LABEL authors="alexa"

#ENTRYPOINT ["top", "-b"]

WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
EXPOSE 8000
#CMD ["pip", "install", "uvicorn", "&&", "uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]