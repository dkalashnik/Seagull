FROM platinumthinker/docker-seagull:1.2

RUN    apt update \
    && apt install -y libssl1.0.0 libssl-dev \
    && rm -rf /var/lib/apt/lists/*

ENV LD_LIBRARY_PATH=/usr/local/bin
CMD ["/bin/bash"]
