FROM nginx:1.21.1

# 更新安装源
# RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.ustc.edu.cn/g' /etc/apk/repositories

# 设置时区为上海
# RUN apk update && apk add --upgrade \
    # && apk add tzdata \
    # && cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    # && echo "Asia/Shanghai" > /etc/timezone \
    # && apk del tzdata
EXPOSE 80 8001 8002 8003
