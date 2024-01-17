<h1 id="more-tweaks-setedit-android"><span style="font-family: 'comic sans ms', sans-serif;">More Code SetEdit Android</span></h1>
<p><span style="font-family: 'comic sans ms', sans-serif;">Trước Khi Bắt Đầu Tối Ưu, Vui Lòng Bạn Hãy Cài Đặt App SetEdit và Bộ Featurepack dưới đây:</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><a href="https://web1s.info/tmri2GVI0N/"><span style="color: #222222;"><span style="background-color: #e9ebec;">Download_Setedit_And_FeaturePack</span></span></a></span></p>
<ul>
<li><span style="font-family: 'comic sans ms', sans-serif;">Note: Nếu Bạn Xoá Ứng Dụng SetEdit Thì sẽ có thể mất code nha, có máy mất và có máy không mất. Nếu nhập qua adb shell thì không mất code </span></li>
<li><span style="font-family: 'comic sans ms', sans-serif;">My Channel: <a href="https://www.youtube.com/channel/UCqnb_ntxhhG_js7OdiSGs1A"><code>https://www.youtube.com/channel/UC-FKTqZu2tO0-vgAM1S6dfw</code></a> ( Vietnamese )</span></li>
</ul>
<p><span style="font-family: 'comic sans ms', sans-serif;">Mình Ở Đây Là Đi Tổng Hợp Các Code Từ Nguồn Bên Ngoài Về Nhé&lt;3</span><br /><span style="font-family: 'comic sans ms', sans-serif;">Không yêu cầu máy bắt buộc phải root - hầu như máy nào cũng có thể áp dụng được</span><br /><span style="font-family: 'comic sans ms', sans-serif;">Cách áp dụng thì áp dụng theo video trên kênh yt nha. bên dưới mình sẽ cho ra các tweaks</span><br /><span style="font-family: 'comic sans ms', sans-serif;">Các bạn nhớ lựa chọn 'system table' vì chủ yếu tất cả trong vùng này thoi:33</span><br /><span style="font-family: 'comic sans ms', sans-serif;">Sau mỗi cái tweak là giá trị nhé</span></p>
<h2 id="tweaks-c-b-n"><span style="font-family: 'comic sans ms', sans-serif;">Tweaks Cơ Bản</span></h2>
<details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">3 Lệnh Tối Ưu Khởi Động</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.config.hw_quickpoweron - true<br /></em> boot.fps - 25 ( Là tốc độ khung hình khi khởi động máy. để 15 được thì càng tốt )</span><br /><span style="font-family: 'comic sans ms', sans-serif;">* debug.sf.nobootanimation - 1</span></p>
</details>
<p><span style="font-family: 'comic sans ms', sans-serif;"><code>Sau đó khởi động lại máy là tận hưởng thành quả nhé&lt;3</code></span></p>
<h2 id="tweaks-n-ng-cao"><span style="font-family: 'comic sans ms', sans-serif;">Tweaks Nâng Cao</span></h2>
<details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Display density</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* display_density_forced - 209</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Ring without delay</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* ring.delay - 0</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tăng Tốc Độ Khởi Động Máy</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> boot.fps - 25 ( 25 là fps, tốc độ khung hình khi khởi động máy, ví dụ như logo )<br /></em> debug.sf.nobootanimation - 1</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Giảm hết pin nhanh và giảm % cpu</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* wifi.supplicant_scan_interval - 120 ( giúp tăng thời gian giữa các lần quét WiFi, tiết kiệm pin và tốc độ CPU )</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tiết Kiệm Pin</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> pm.sleep_mode - 1<br /></em> power_supply.wakeup - enable</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.mot.eri.losalert.delay - 1000 (có thể tắt chia sẻ kết nối wifi)<br /></em> ro.ril.power_collapse - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;">* ro.ril.disable.power.collapse - 0</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tối Ưu Cho Game, Tăng Hiệu Suất</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">Vâng, Hẳn là vậy rồi. chắc chắn bạn nào cũng cần nhất là cái này.</span><br /><span style="font-family: 'comic sans ms', sans-serif;">việc này giúp cho máy trơn tru hơn ban đầu. tối ưu cho điện thoại của chúng ta :D</span></p>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> debug.enabletr - true<br /></em> debug.qctwa.preservebuf - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> dev.pm.dyn_samplingrate - 1<br /></em> video.accelerate.hw - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> debug.overlayui.enable - 1<br /></em> debug.egl.hw - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> Debug.egl.prifiler - 1<br /></em> debug.sf.hw - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> debug.composition.type - c2d<br /></em> debug.composition.type - gpu</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> debug.performance.tuning - 1<br /></em> Logcat.live - disable</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Điều Hướng Độ Nhạy Tốt Hơn</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* windowsmgr.max_events_per_sec - 100</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt Hoạt Ảnh Khi Dùng Dấu Vân Tay</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* fod_animation_type - 4</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tăng chất lượng đầu ra âm thanh</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> af.resampler.quality - 255<br /></em> mpq.audio.decode - true</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tối Ưu Trình duyệt web và tốc độ download</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> net.tcp.buffersize.default - 4096,87380,256960,4096, 16384,256960<br /></em> net.tcp.buffersize.wifi - 4096,87380,256960,4096,163 84,256960</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.tcp.buffersize.umts - 4096,87380,256960,4096,163 84,256960<br /></em> net.tcp.buffersize.gprs - 4096,87380,256960,4096,163 84,256960</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.tcp.buffersize.edge - 4096,87380,256960,4096,163 84,256960<br /></em> net.tcp.buffersize.hspa - 6144,87380,524288,6144,163 84,262144</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.tcp.buffersize.lte - 524288,1048576,2097152,5242 88,1048576,2097152<br /></em> net.tcp.buffersize.hsdpa - 6144,87380,1048576,6144,8 7380,1048576</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.tcp.buffersize.evdo_b - 6144,87380,1048576,6144, 87380,1048576<br /></em> net.rmnet0.dns1 - 8.8.8.8</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.rmnet0.dns2 - 8.8.4.4<br /></em> net.dns1 - 8.8.8.8</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.dns2 - 8.8.4.4<br /></em> net.ppp0.dns1 - 8.8.8.8</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.ppp0.dns2 - 8.8.4.4<br /></em> net.wlan0.dns1 - 8.8.8.8</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.wlan0.dns2 - 8.8.4.4<br /></em> net.eth0.dns1 - 8.8.8.8</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.eth0.dns2 - 8.8.4.4<br /></em> net.gprs.dns1 - 8.8.8.8</span><br /><span style="font-family: 'comic sans ms', sans-serif;">* net.gprs.dns2 - 8.8.4.4</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tăng Tốc GPU</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> debug.qc.hardware - true<br /></em> debug.qctwa.statusbar - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> debug.qctwa.preservebuf - 1<br /></em> debug.composition.type - gpu</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> hw3d.force - 1<br /></em> hwui.render_dirty_regions - false</span><br /><span style="font-family: 'comic sans ms', sans-serif;">* hwui.disable_vsync - true</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt FeedBack</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* haptic_feedback_enabled - 0 ( muốn bật lại thì chỉnh 0 thành 1 và khởi động lại máy )</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tối Ưu Cho Streaming, chia sẻ màn hình</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> media.stagefright.enable-player - true<br /></em> media.stagefright.enable-meta - true</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> media.stagefright.enable-scan - true<br /></em> media.stagefright.enable-http - true</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> media.stagefright.enable-aac - true<br /></em> media.stagefright.enable-qcp - true</span><br /><span style="font-family: 'comic sans ms', sans-serif;">* media.stagefright.enable-record - true</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tinh chỉnh Wifi Mượt</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> net.ipv4.ip_no_pmtu_disc - 0<br /></em> net.ipv4.route.flush - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.ipv4.tcp_ecn - 0<br /></em> net.ipv4.tcp_fack - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.ipv4.tcp_mem - 187000 187000 187000<br /></em> net.ipv4.tcp_moderate_rcvbuf - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.ipv4.tcp_no_metrics_save - 1<br /></em> net.ipv4.tcp_rfc1337 - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.ipv4.tcp_rmem - 4096 39000 187000<br /></em> net.ipv4.tcp_sack - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> net.ipv4.tcp_timestamps - 1<br /></em> net.ipv4.tcp_window_scaling - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;">* net.ipv4.tcp_wmem - 4096 39000 18700</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tinh chỉnh RAM</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* ro.HOME_APP_ADJ - 1</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt Tự động gửi báo cáo lỗi tới nhà sản xuất</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> profiler.force_disable_err_rpt - 1<br /></em> profiler.force_disable_ulog - 1</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tối Ưu Sóng 3G</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><code>Hiện chưa thấy tweaks cho 4G Nhé :v</code></span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.ril.hep - 0<br /></em> ro.ril.hsxpa - 2</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.ril.gprsclass - 12<br /></em> ro.ril.enable.dtm - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.ril.hsdpa.category - 8<br /></em> ro.ril.enable.a53 - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.ril.enable.3g.prefix - 1<br /></em> ro.ril.htcmaskw1.bitmask - 4294967295</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.ril.htcmaskw1 - 14449<br /></em> ro.ril.hsupa.category - 6</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt sự cố màn hình đen sau cuộc gọi</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.lge.proximity.delay - 25<br /></em> mot.proximity.delay - 25</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Giúp hiển thị chất lượng tốt hơn</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* persist.sys.use_dithering - 1 ( có thể giảm fps và hiệu năng xuống )</span></p>
</details>
<h2 id="t-ng-th-m-tweaks-video-120like-"><span style="font-family: 'comic sans ms', sans-serif;">Tặng Thêm Tweaks ( Video Đủ 120Like )</span></h2>
<details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tăng Hiệu Năng Chơi Game v2</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> persist.sys.NV_FPSLIMIT - 60<br /></em> persist.sys.NV_POWERMODE - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> persist.sys.NV_PROFVER - 15<br /></em> persist.sys.NV_STEREOCTRL - 0</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> persist.sys.NV_STEREOSEPCHG - 0<br /></em> persist.sys.NV_STEREOSEP - 20</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> persist.sys.purgeable_assets - 1<br /></em> ro.vold.umsdirtyratio - 20</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.fb.mode - 1<br /></em> persist.sys.ui.hw - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.sf.compbypass.enable - 1<br /></em> persist.sys.composition.type - c2d</span></p>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.media.dec.jpeg.memcap - 8000000<br /></em> ro.media.enc.hprof.vid.bps - 8000000</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.media.dec.aud.wma.enabled - 1<br /></em> ro.media.dec.vid.wmv.enabled - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.media.cam.preview.fps - 0<br /></em> ro.media.codec_priority_for_thumb - so</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tăng Tốc Dalvik Virtual Machine ( Máy Ảo )</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> dalvik.vm.checkjni - false<br /></em> dalvik.vm.dexopt-data-only - 1</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> dalvik.vm.heapstartsize - 5m<br /></em> dalvik.vm.heapgrowthlimit - 48m</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> dalvik.vm.heapsize - 64m<br /></em> dalvik.vm.verify-bytecode - false</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> dalvik.vm.execution-mode - int:jit<br /></em> dalvik.vm.lockprof.threshold - 250</span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em> dalvik.vm.dexopt-flags - m=v,o=y<br /></em> dalvik.vm.stack-trace-file - /data/anr/traces.txt</span><br /><span style="font-family: 'comic sans ms', sans-serif;">* dalvik.vm.jmiopts - forcecopy</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Loại Bỏ Giới Hạn FPS</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* debug.gr.swapinterval - 0 ( Có thể không ổn định )</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt Hoạt Ảnh Vân Tay</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* fod_animation_type - 4</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tăng Phản Hồi Intensity</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> haptic_feedback_enabled - 1<br /></em> haptic_feedback_intensity - 1</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Bật Tự Động Xoay Cho Điện Thoại</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">Một Số Dòng Máy không được hỗ trợ tính năng này. nhất là các ROM Mod.</span><br /><span style="font-family: 'comic sans ms', sans-serif;">Vậy Lên Tôi Đã Chia Sẻ Tweaks Này</span></p>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> lockscreen.rot_override - true ( Cho Màn Hình Khoá )</em></span></p>
<p><span style="font-family: 'comic sans ms', sans-serif;">Muốn Tắt Tự Động Xoay Thì Chỉnh Giá Trị "true" Thành "false"</span></p>
<p><span style="font-family: 'comic sans ms', sans-serif;">log.tag.launcher_force_rotate - VERBOSE ( Cho Màn Hình Chính )</span></p>
<p><span style="font-family: 'comic sans ms', sans-serif;">Muốn Tắt Tự Động Xoay Thì Xoá "log.tag.launcher_force_rotate" Đi nhé.</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Giữ đèn phím sáng khi màn hình đang bật</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* ro.mot.buttonlight.timeout = 0 ( Muốn Tắt Thì Để Giá Trị Là 1 )</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt Tính Năng Tự Động Kiểm Tra Lỗi</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.kernel.checkjni - 0<br /></em> ro.kernel.android.checkjni - 0</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt Chế Độ Nghiêm Ngặt</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* persist.android.strictmode - 0</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tuỳ Chỉnh DPI Của Máy</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* ro.sf.lcd_density - 420 ( Có Thể Chỉnh 420 là số dpi khác mà bạn muốn )</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Sửa đổi bộ hẹn giờ thử lại MMS APN SMS</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">Nếu không gửi được SMS / MMS, Android sẽ cố gắng gửi lại sau 5 giây.</span><br /><span style="font-family: 'comic sans ms', sans-serif;">Bạn có thể thay đổi số lần lặp lại và khoảng thời gian giữa các lần thử lại đó.</span><br /><span style="font-family: 'comic sans ms', sans-serif;">Đoạn mã sau sẽ buộc 4 lần thử lại sau mỗi 8 giây.</span></p>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.gsm.2nd_data_retry_config - max<br /></em> _retries - 4, 8000, 8000, 8000, 8000</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt định vị</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;"><em> ro.com.google.locationfeatures - 0<br /></em> ro.com.google.networklocation - 0</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt tính năng gửi dữ liệu sử dụng</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* ro.config.nocheckin - 1</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Thay Đổi Màn Hình LCD</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* ro.sf.lcd.density - 240 ( 240 là giá trị tốt nhất thời điểm hiện tại )</span></p>
</details><details>
<summary><span style="font-family: 'comic sans ms', sans-serif;">Tắt Thông Báo Khi Kết Nối ADB</span></summary>
<p><span style="font-family: 'comic sans ms', sans-serif;">* persist.adb.notify - 0</span></p>
</details>
<h2 id="k-t-lu-n"><span style="font-family: 'comic sans ms', sans-serif;">kết luận</span></h2>
<p><span style="font-family: 'comic sans ms', sans-serif;">lấy từ nhiều nơi khác nhau và các web khác nhau.</span><br /><span style="font-family: 'comic sans ms', sans-serif;">sự tổng hợp tất cả các lệnh SetEdit ổn định mà tôi đang sử dụng.</span></p>
<p><span style="font-family: 'comic sans ms', sans-serif;"><code>Cảm Ơn vì Đã Đến Với Trang Osteup Của tôi</code></span></p>
