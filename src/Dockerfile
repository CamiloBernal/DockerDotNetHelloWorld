FROM microsoft/dotnet:1.0-sdk-projectjson
COPY *.cs /app/
COPY project.json /app/
WORKDIR /app
RUN dotnet restore
CMD dotnet run