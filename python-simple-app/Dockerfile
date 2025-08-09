FROM python:3.10-slim

# Set working directory
WORKDIR /app

# Install pytest once and for all
RUN pip install -r requirements.txt --no-cache-dir

# (Optional) Set a non-root user if you want to improve security
# RUN useradd -m jenkins
# USER jenkins

CMD ["pytest", "--version"]
