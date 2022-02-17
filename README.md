***NPM***
- npm cache clean --force
- set http_proxy=
- set https_proxy=
- Yarn config delete proxy
- Npm config rm https-proxy
- Npm config rm proxy
- Restart your terminal
- yarn
- Yarn –network-timeout 100000
- Restart your terminal

***GIT & TERMINAL***
export ALL_PROXY=192.168.120.83:44355
git config --global http.proxy http://192.168.120.83:44355
git config --global https.proxy https://192.168.120.83:44355


***MAC****
- network preferences -> advanced -> proxies
- web proxy
- secure web proxy
