# Introduction

service-service yang digunakan sistem reservasi medis online medpoint untuk mengambil data ke database

## technology

Raiden dan Go

### Project Structure 
medpoint-BE
- **├── cmd**
- **│   ├── apply**
- **│   │   └── main.go**
- **│   ├── import**
- **│   │   └── main.go**
- **│   └── mirror-medpoint**
- **│       └── mirror_medpoint.go**
- **├── configs**
- **│   └── app.yaml**
- **└── internal**
- **    ├── bootstrap**
- **    │   ├── models.go**
- **    │   ├── roles.go**
- **    │   ├── route.go**
- **    │   └── storages.go**
- **    ├── controllers**
- **    │   └── hello.go**
- **    ├── models**
- **    ├── roles**
- **    └── storages**
