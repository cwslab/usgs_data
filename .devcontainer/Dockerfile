# Use the official Microsoft Python image (optimized for Codespaces)
FROM mcr.microsoft.com/devcontainers/python:3.10

# Install system-level spatial dependencies
RUN apt-get update && apt-get install -y \
    libgdal-dev \
    libproj-dev \
    && rm -rf /var/lib/apt/lists/*

# Install your Python packages
COPY environment.yml /tmp/environment.yml
RUN pip install --no-cache-dir \
    pandas numpy matplotlib shapely geopandas folium dataretrieval \
    jupyter ipykernel
