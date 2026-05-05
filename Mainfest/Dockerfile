FROM nginx:alpine

# remove default nginx content
RUN rm -rf /usr/share/nginx/html/*

# copy already-built frontend files
COPY build/ /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
