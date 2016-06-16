FROM microsoft/dotnet:1.0.0-rc2-core

WORKDIR /app

# Copy the app
COPY . .

# Configure the listening port to 80
ENV ASPNETCORE_URLS http://*:5000
EXPOSE 5000

# Start the app
ENTRYPOINT dotnet api-dotnet.dll