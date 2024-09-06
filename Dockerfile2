FROM frooodle/s-pdf:latest



# Use a simple built-in health check
HEALTHCHECK --interval=10s --timeout=10s --start-period=10s --retries=3 \
  CMD wget --spider http://localhost:80 || exit 1
