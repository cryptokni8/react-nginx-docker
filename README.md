docker build --rm -f Dockerfile -t helldocker:latest .

docker run --rm -d -p 80:80 helldocker:latest