FROM google/cloud-sdk

RUN curl -O https://dl.google.com/go/go1.8.5.linux-amd64.tar.gz && \
    tar -C /usr/local -xzf go1.8.5.linux-amd64.tar.gz && \
    rm -f go1.8.5.linux-amd64.tar.gz

ENV PATH $PATH:/usr/local/go/bin:/root/go/bin

RUN go get -u github.com/golang/dep/cmd/dep
