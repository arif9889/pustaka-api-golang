## TODO

---

1. Ubah yang belum di service handler ✅
2. Do all function in handler (Create ✅, Reads ✅, Update ✅, Delete ✅, ReadByID ✅)
3. Sesuain response dengan schema
4. Error handler di Findbyid dan delete pada resultnya
5. Use environment ✅

## Flow App

---

    server -> repository -> service -> handler

## How to run

---

- `swag init -g server.go`
- `go run server.go`

or

- `swag init -g server.go`
- `go build server.go`
- `./server`

visit

- `http://127.0.0.1:5000/swagger/index.html` to see Doc API

### Tutorial from

---

[YT Agung Setiawan - Tutorial Golang Web API Bahasa Indonesia - Full Course](https://www.youtube.com/watch?v=GjI0GSvmcSU&t=290s)
