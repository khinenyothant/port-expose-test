FROM nginx

# Create a simple HTML file
RUN echo '<!DOCTYPE html> \
<html> \
<head> \
<style> \
body { \
    background-color: lightblue; \
    margin: 0; \
    padding: 0; \
    font-family: Arial, sans-serif; \
} \
.header { \
    color: black; \
    text-align: center; \
} \
</style> \
</head> \
<body> \
<div class="header">This is web server for port 80.</div> \
</body> \
</html>' > /usr/share/nginx/html/index.html
