FROM python:3.8-slim AS builder
WORKDIR /app
COPY requirements.txt./
RUN pip install --no-cache-dir -r requirements.txt
COPY..

FROM python:3.8-slim
WORKDIR /app
COPY --from=builder /app /app
EXPOSE 5000
CMD ["python", "app.py"]