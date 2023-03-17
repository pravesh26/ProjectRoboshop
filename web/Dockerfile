FROM nginx
# Logic command to delete the file in container that is present by default
RUN rm -rf /usr/share/nginx/html/index.html
# Logc command to add our own HTML files from local system to container   
ADD static /usr/share/nginx/html/
# Command to run the container infinitely
# CMD ["nginx","-g","daemon-off;"]
 