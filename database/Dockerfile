FROM mongo:latest

# Install MongoDB client tools
RUN apt-get update && apt-get install -y \
    mongodb-clients \
    && rm -rf /var/lib/apt/lists/*

CMD ["sleep", "infinity"]
