FROM nginx:alpine

EXPOSE 8080

HEALTHCHECK --interval=10s --timeout=2s \
  CMD wget -qO- http://localhost:8080 || exit 1

