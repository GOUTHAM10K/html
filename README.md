<!DOCTYPE html>
<html>
<head>
<title>my sriapthid</title>
<h1>fajkfaskjladfsl;fslfdslj</h1>
</head>
</html>

FROM nginx:alpine
COPY index.html/usr/share/nginx/html/
EXPOSE 80
CMD ["nginx","-g","daemon off;"]
