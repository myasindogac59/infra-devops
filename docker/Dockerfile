FROM nginx:alpine
HEALTHCHECK  --interval=30s --timeout=3s \
CMD wget -q0- http://localhost || exit 1
