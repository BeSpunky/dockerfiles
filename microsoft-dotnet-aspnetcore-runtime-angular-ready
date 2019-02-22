FROM microsoft/dotnet:2.2-aspnetcore-runtime
WORKDIR /app
EXPOSE 80
EXPOSE 4200
EXPOSE 443
RUN apt-get update -yq \
 && apt-get install -yq gnupg2 \
 && curl -sL https://deb.nodesource.com/setup_11.x | bash - \
 && apt-get install -yq nodejs
