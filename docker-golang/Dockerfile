FROM golang
MAINTAINER perry.tang <perry.tzp@gmail.com>
WORKDIR /go/src/app
COPY . .
# 对外端口
EXPOSE 80
# 运行项目
ENTRYPOINT ["go","run","main.go"]