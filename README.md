$ pwd
/c/Users/Ahmed Khaled/Desktop/Docker/frontend


$ docker run -p 3000:3000 df2cd59a67c8


docker run -p 3010:3010 -v /app/node_modules -v "$(pwd):/app" 9305f699e0a1



docker run -p 8080:80 4a78ccf46091