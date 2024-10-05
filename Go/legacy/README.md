
## Go 환경
```bash
# 일반적인 설치 경로
$ which go
# Go 설치 경로 확인
$ go env GOROOT
# Go 환경 변수 확인
$ go env
```

## Go 모듈 초기화
`$ go mod init legacy`

## Go 실행
`$ go run main.go`

## Go 빌드
`$ go build -o hellowolrd`

## Go 디버깅
```bash
$ go install github.com/go-delve/delve/cmd/dlv@latest
$ which dlv
```