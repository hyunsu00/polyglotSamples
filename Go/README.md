
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
# 주의사항
# go-dlv는 브레이크 포인트 설정시 심볼릭링크경로에는 붙지 않는다.
# 따라서 실제 경로에서 프로젝트에서 열어야만 디버깅이 가능하다.

go install github.com/go-delve/delve/cmd/dlv@latest
which dlv
```
