FROM php:8.2-cli

# Install utilities
RUN apt-get update && apt-get install -y \
    unzip \
    libzip-dev \
    && docker-php-ext-install zip

# Set working directory
WORKDIR /workspace

# Expose port for dev server
EXPOSE 8000
