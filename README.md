# shells
脚本|说明|示例
---|---|---
nginx2goaccess.sh|将nginx日志格式格式化为goaccess能识别的日志格式|sh nginx2goaccess.sh '$remote_addr - $remote_user [$time_local] "$http_host$request_uri" $status $request_time $body_bytes_sent "$http_referer" "$http_user_agent" "$http_x_forwarded_for"'
