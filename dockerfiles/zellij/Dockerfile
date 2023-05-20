FROM pellepedro/binpot:zellij as zellij

FROM alpine:latest
COPY --from=zellij /zellij /user/local/bin/zellij
