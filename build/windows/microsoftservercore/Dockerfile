FROM microsoft/windowsservercore

COPY dist /

VOLUME C:\\ProgramData\\Portainer

WORKDIR /

EXPOSE 9000

ENTRYPOINT ["/portainer.exe"]
