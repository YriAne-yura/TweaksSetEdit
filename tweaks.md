
# More Tweaks SetEdit Android
Trước Khi Bắt Đầu Tối Ưu, Vui Lòng Bạn Hãy Cài Đặt App SetEdit Trên CH Play:
`https://play.google.com/store/apps/details?id=by4a.setedit22`
* Note: Nếu Bạn Xoá Ứng Dụng SetEdit Thì Đồng Nghĩa Với Việc Bạn Sẽ Mất Hết Các Tweaks Đã Cài Vào
* My Channel: `https://www.youtube.com/channel/UC-FKTqZu2tO0-vgAM1S6dfw` ( Vietnamese ) 

Mình Ở Đây Là Đi Tổng Hợp Các Code Từ Nguồn Bên Ngoài Về Nhé<3
Không yêu cầu máy bắt buộc phải root - hầu như máy nào cũng có thể áp dụng được
Cách áp dụng thì áp dụng theo video trên kênh yt nha. bên dưới mình sẽ cho ra các tweaks
Các bạn nhớ lựa chọn 'system table' vì chủ yếu tất cả trong vùng này thoi:33
Sau mỗi cái tweak là giá trị nhé

## Tweaks Cơ Bản

<details><summary>3 Lệnh Tối Ưu Khởi Động</summary><p>

* ro.config.hw_quickpoweron - true 
* boot.fps - 25 ( Là tốc độ khung hình khi khởi động máy. để 15 được thì càng tốt )
* debug.sf.nobootanimation - 1

Sau đó khởi động lại máy là tận hưởng thành quả nhé<3

</p></details>

## Tweaks Nâng Cao

<details><summary>Display density</summary><p>

* display_density_forced - 209

</p></details>

<details><summary>Ring without delay</summary><p>

* ring.delay - 0

</p></details>

<details><summary>Tăng Tốc Độ Khởi Động Máy</summary><p>

* boot.fps - 25 ( 25 là fps, tốc độ khung hình khi khởi động máy, ví dụ như logo )
* debug.sf.nobootanimation - 1

</p></details>

<details><summary>Giảm hết pin nhanh và giảm % cpu</summary><p>

* wifi.supplicant_scan_interval - 120 ( giúp tăng thời gian giữa các lần quét WiFi, tiết kiệm pin và tốc độ CPU )

</p></details>

<details><summary>Tiết Kiệm Pin</summary><p>

* pm.sleep_mode - 1
* power_supply.wakeup - enable
* ro.mot.eri.losalert.delay - 1000 (có thể tắt chia sẻ kết nối wifi)
* ro.ril.power_collapse - 1
* ro.ril.disable.power.collapse - 0

</p></details>


<details><summary>Tối Ưu Cho Game, Tăng Hiệu Suất</summary><p>

Vâng, Hẳn là vậy rồi. chắc chắn bạn nào cũng cần nhất là cái này.
việc này giúp cho máy trơn tru hơn ban đầu. tối ưu cho điện thoại của chúng ta :D

* debug.enabletr - true
* debug.qctwa.preservebuf - 1
* dev.pm.dyn_samplingrate - 1
* video.accelerate.hw - 1
* debug.overlayui.enable - 1
* debug.egl.hw - 1
* Debug.egl.prifiler - 1
* debug.sf.hw - 1 
* debug.composition.type - c2d
* debug.composition.type - gpu
* debug.performance.tuning - 1
* Logcat.live - disable

</p></details>


<details><summary>Điều Hướng Độ Nhạy Tốt Hơn</summary><p>

* windowsmgr.max_events_per_sec - 100

</p></details>


<details><summary>Tắt Hoạt Ảnh Khi Dùng Dấu Vân Tay</summary><p>

* fod_animation_type - 4

</p></details>


<details><summary>Tăng chất lượng đầu ra âm thanh</summary><p>

* af.resampler.quality - 255
* mpq.audio.decode - true

</p></details>


<details><summary>Tối Ưu Trình duyệt web và tốc độ download</summary><p>

* net.tcp.buffersize.default - 4096,87380,256960,4096, 16384,256960
* net.tcp.buffersize.wifi - 4096,87380,256960,4096,163 84,256960
* net.tcp.buffersize.umts - 4096,87380,256960,4096,163 84,256960
* net.tcp.buffersize.gprs - 4096,87380,256960,4096,163 84,256960
* net.tcp.buffersize.edge - 4096,87380,256960,4096,163 84,256960
* net.tcp.buffersize.hspa - 6144,87380,524288,6144,163 84,262144
* net.tcp.buffersize.lte - 524288,1048576,2097152,5242 88,1048576,2097152
* net.tcp.buffersize.hsdpa - 6144,87380,1048576,6144,8 7380,1048576
* net.tcp.buffersize.evdo_b - 6144,87380,1048576,6144, 87380,1048576
* net.rmnet0.dns1 - 8.8.8.8
* net.rmnet0.dns2 - 8.8.4.4
* net.dns1 - 8.8.8.8
* net.dns2 - 8.8.4.4
* net.ppp0.dns1 - 8.8.8.8
* net.ppp0.dns2 - 8.8.4.4
* net.wlan0.dns1 - 8.8.8.8
* net.wlan0.dns2 - 8.8.4.4
* net.eth0.dns1 - 8.8.8.8
* net.eth0.dns2 - 8.8.4.4
* net.gprs.dns1 - 8.8.8.8
* net.gprs.dns2 - 8.8.4.4

</p></details>


<details><summary>Tăng Tốc GPU</summary><p>

* debug.qc.hardware - true
* debug.qctwa.statusbar - 1
* debug.qctwa.preservebuf - 1
* debug.composition.type - gpu
* hw3d.force - 1
* hwui.render_dirty_regions - false
* hwui.disable_vsync - true

</p></details>


<details><summary>Tắt FeedBack</summary><p>

* haptic_feedback_enabled - 0 ( muốn bật lại thì chỉnh 0 thành 1 và khởi động lại máy )

</p></details>


<details><summary>Tối Ưu Cho Streaming, chia sẻ màn hình</summary><p>

* media.stagefright.enable-player - true
* media.stagefright.enable-meta - true
* media.stagefright.enable-scan - true
* media.stagefright.enable-http - true
* media.stagefright.enable-aac - true
* media.stagefright.enable-qcp - true
* media.stagefright.enable-record - true

</p></details>


<details><summary>Tinh chỉnh Wifi Mượt</summary><p>

* net.ipv4.ip_no_pmtu_disc - 0
* net.ipv4.route.flush - 1
* net.ipv4.tcp_ecn - 0
* net.ipv4.tcp_fack - 1
* net.ipv4.tcp_mem - 187000 187000 187000
* net.ipv4.tcp_moderate_rcvbuf - 1
* net.ipv4.tcp_no_metrics_save - 1
* net.ipv4.tcp_rfc1337 - 1
* net.ipv4.tcp_rmem - 4096 39000 187000
* net.ipv4.tcp_sack - 1
* net.ipv4.tcp_timestamps - 1
* net.ipv4.tcp_window_scaling - 1
* net.ipv4.tcp_wmem - 4096 39000 18700

</p></details>


<details><summary>Tinh chỉnh RAM</summary><p>

* ro.HOME_APP_ADJ - 1

</p></details>


<details><summary>Tắt Tự động gửi báo cáo lỗi tới nhà sản xuất</summary><p>

* profiler.force_disable_err_rpt - 1
* profiler.force_disable_ulog - 1

</p></details>


<details><summary>Tối Ưu Sóng 3G</summary><p>

`Hiện chưa thấy tweaks cho 4G Nhé :v`
* ro.ril.hep - 0
* ro.ril.hsxpa - 2
* ro.ril.gprsclass - 12
* ro.ril.enable.dtm - 1
* ro.ril.hsdpa.category - 8
* ro.ril.enable.a53 - 1
* ro.ril.enable.3g.prefix - 1
* ro.ril.htcmaskw1.bitmask - 4294967295
* ro.ril.htcmaskw1 - 14449
* ro.ril.hsupa.category - 6

</p></details>


<details><summary>Tắt sự cố màn hình đen sau cuộc gọi</summary><p>

* ro.lge.proximity.delay - 25
* mot.proximity.delay - 25

</p></details>


<details><summary>Giúp hiển thị chất lượng tốt hơn</summary><p>

* persist.sys.use_dithering - 1 ( có thể giảm fps và hiệu năng xuống )

</p></details>

## kết luận

lấy từ nhiều nơi khác nhau và các web khác nhau.
sự tổng hợp tất cả các lệnh SetEdit ổn định mà tôi đang sử dụng.

`Cảm Ơn vì Đã Đến Với ProFile Của tôi`
