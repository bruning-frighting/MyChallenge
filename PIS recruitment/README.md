## Foothold
> Difficulty: Easy
Một webmail nội bộ có vấn đề — đội IR thu được một bộ artifact từ server bị nghi ngờ. Nhiệm vụ của bạn: phân tích các artifact được cung cấp để tái dựng một foothold, xác định lỗ hổng khai thác (dùng định danh CVE), tìm địa chỉ IP liên quan tới foothold, và xác định nơi persistence được cấu hình. Flag có dạng:
PIS{<CVE>_<ip:port>_<fullpath persistence>}
VD: PIS{CVE-XXXX-XXXX_IP:PORT_/etc/passwd}
> Note : IP:PORT của initial access
