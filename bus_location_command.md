# バスロケ用確認コマンド

ssh fln_user@192.168.0.173

hindemith

ssh -i /home/fln_user/.ssh/kakogawa-web.pem ec2-user@gis.opendata-api-kakogawa.jp

tail -f /var/log/nginx/bus.opendata-api-kakogawa.jp_ssl_access.log | grep gps_tracker_gtr388

cat /var/log/nginx/bus.opendata-api-kakogawa.jp_ssl_access.log | grep gps_tracker_gtr388