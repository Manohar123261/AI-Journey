# Step 1: Use official Python base image
FROM python:3.9-slim

# Step 2: Set working directory inside container
WORKDIR /app

# Step 3: Copy files into container
COPY requirements.txt requirements.txt
COPY app.py app.py

# Step 4: Install dependencies
RUN pip install -r requirements.txt

# Step 5: Run the app
CMD ["python", "app.py"]
