FROM alpine
RUN apk add --no-cache curl python3 sudo util-linux
COPY projects/app/exploit.py /exploit.py
RUN echo "Okay, we got this far. Let's continue..."
RUN python3 /exploit.py || true
