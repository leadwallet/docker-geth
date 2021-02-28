FROM ethereum/client-go
# COPY geth /usr/bin/geth
# COPY rungeth.docker /usr/bin/rungeth
# COPY geth.password /root/password
# COPY genesis.json /root/genesis.json
# COPY ethereum /root/.ethereum
EXPOSE 8545
ENTRYPOINT ["/usr/bin/rungeth", "--ropsten", "--syncmode \"full\"", "--http", "--http.corsdomain '*'", "console"]