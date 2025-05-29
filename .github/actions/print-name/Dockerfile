FROM ubuntu:20.04

# Install basic tools
RUN apt-get update && apt-get install -y curl

# Copy the entrypoint script
COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

# Set the entrypoint
ENTRYPOINT ["/entrypoint.sh"]
