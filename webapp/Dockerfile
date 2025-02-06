# Use the official Python 3.12 image (non-slim to ensure compatibility)
FROM python:3.12

# Set working directory
WORKDIR /app

# Install dependencies, including an updated SQLite version
RUN apt-get update && apt-get install -y sqlite3 libsqlite3-dev && rm -rf /var/lib/apt/lists/*

# Copy and install Python dependencies
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy application files
COPY . .

# Expose port (adjust if needed)
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]
