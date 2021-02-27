FROM ethereum/client-go
COPY geth /usr/bin/geth
COPY rungeth.docker /usr/bin/rungeth
COPY geth.password /root/password
COPY genesis.json /root/genesis.json
COPY ethereum /root/.ethereum
EXPOSE 8110 8990 
ENTRYPOINT ["/usr/bin/rungeth", "--syncmode \"full\"", "--rpc", "--http", "--http.crossdomain '*'"]