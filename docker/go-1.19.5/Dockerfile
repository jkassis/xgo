FROM mysteriumnetwork/xgo:base

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 1195

RUN \
  export ROOT_DIST=https://go.dev/dl/go1.19.5.linux-amd64.tar.gz && \
  export ROOT_DIST_SHA=36519702ae2fd573c9869461990ae550c8c0d955cd28d2827a6b159fda81ff95 && \
  \
$BOOTSTRAP_PURE
