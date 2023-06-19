# Final stage
FROM scratch

# Copy the compiled binary from the build stage
COPY rustybgpd* /usr/local/bin/

# Set the entry point or CMD as needed
ENTRYPOINT ["/usr/local/bin/rustybgpd"]
