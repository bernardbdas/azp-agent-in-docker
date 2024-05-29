FROM mcr.microsoft.com/windows/servercore:ltsc2022-amd64 as azp-agent-win
# Fetch available tags from here : https://mcr.microsoft.com/v2/windows/servercore/tags/list

WORKDIR /azp/

COPY ./start.ps1 ./

CMD powershell .\start.ps1