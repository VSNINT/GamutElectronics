# Use the official Grafana image as the base
FROM grafana/grafana:latest

# Expose Grafana's default port
EXPOSE 3000

# If you want to add custom configuration, copy it to the appropriate Grafana directory
# COPY ./grafana.ini /etc/grafana/grafana.ini

# Start Grafana when the container launches
CMD ["grafana-server", "--homepath=/usr/share/grafana"]

