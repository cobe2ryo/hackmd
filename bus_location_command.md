# バスロケ用確認コマンド

ssh fln_user@192.168.0.173

hindemith

ssh -i /home/fln_user/.ssh/kakogawa-web.pem ec2-user@gis.opendata-api-kakogawa.jp

cat -n2000 /var/log/nginx/bus.opendata-api-kakogawa.jp_ssl_access.log | grep gps_tracker_gtr388