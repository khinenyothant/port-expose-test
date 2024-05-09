FROM nginx

#fix listen port default 80 to 444
RUN sed -i 's/80/444/' /etc/nginx/conf.d/default.conf

# Create a simple HTML file
RUN echo '<!DOCTYPE html> \
<html> \
<head> \
<style> \
body { \
    background-color: lightpink; \
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
<div class="header">This is web server for port 444.</div> \
</body> \
</html>' > /usr/share/nginx/html/index.html
