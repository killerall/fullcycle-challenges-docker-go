FROM golang as build
COPY /src/ /src/
WORKDIR /src
RUN go build -o /output/fullcycle
FROM scratch
COPY --from=build /output/fullcycle /bin/fullcycle
ENTRYPOINT ["/bin/fullcycle"]