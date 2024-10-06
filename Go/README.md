
# Go 환경

```bash
# 일반적인 설치 경로
$ which go
# Go 설치 경로 확인
$ go env GOROOT
# Go 환경 변수 확인
$ go env
```

## Go 모듈 초기화

`$ go mod init 프로젝트명`

## Go 실행

`$ go run main.go`

## Go 빌드

`$ go build -o hellowolrd`

## 모든 캐쉬 지우기

`go clean -cache -modcache -testcache`

## Go 디버깅

```bash
go install github.com/go-delve/delve/cmd/dlv@latest
which dlv
```
