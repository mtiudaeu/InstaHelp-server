# CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o main .
# sudo docker build -t to_delete .
# sudo docker run -p 8080:8080 -t to_delete 

FROM scratch
ADD main /
ADD view.html /
add edit.html /
CMD ["/main"]
