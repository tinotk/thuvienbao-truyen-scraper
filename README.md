# ThuVienBao Truyện Scraper
<strong>ThuVienBao Truyện Scraper v1.2 **BETA**</strong><br>
Tool để lấy text và raw html từ các websites truyện phổ biến.
<h2>Supported sites:</h2>

* `http://truyencv.com/xxxxx/`
* `https://truyenyy.com/truyen/xxxxx/`
* `https://bachngocsach.com/reader/xxxxx`
* `http://truyenfull.vn/xxxxx/`
* `https://truyen.tangthuvien.vn/doc-truyen/xxxxx`
* `http://truyencuatui.net/truyen/xxxxx.html`
* `http://truyendich.com/xxxxx/`
* `http://webtruyen.com/xxxxx/`
* `https://wikidich.com/truyen/xxxxx`
* `https://www.wattpad.com/story/xxxxx`

## Features:
* Tự động check chương đã download và update chương mới.
* Tự động lọc text rác bằng regular expression, có thể lọc được hầu hết text rác trừ những cái mới ra chưa update. Dự tính sẽ làm thêm 1 bộ custom regex để người dùng tự thêm.

## Notes:
* Lưu ý dành cho <strong>wattpad</strong>: Vì site này xài JavaScript &amp; AJAX cho text nên HTTP GET thường không có lấy được nhé, thay vào đó phải xài qua <a href="https://sites.google.com/a/chromium.org/chromedriver/downloads">ChromeDriver</a>. Bạn cần download thêm <strong><a href="https://sites.google.com/a/chromium.org/chromedriver/downloads">ChromeDriver.</a> </strong>Extract <code>chromedriver.exe</code> rồi copy vào <code>C:\Windows</code>. Muốn biết thêm chi tiết về ChromeDriver có thể vào homepage tại https://sites.google.com/a/chromium.org/chromedriver/. Khi chạy chương trình bạn sẽ thấy Chrome mở lên, cứ để cho nó chạy đừng có làm gì hết.<br><br>
* Tool đang còn beta nên sẽ có bug. Nhớ report dùm nhé.
## Project Homepage:
Xin mời chư vị ủng hộ website <a href="https://truyen.thuvienbao.com/">ThuVienBao Audiobooks.</a> Nghe truyện audio tiên hiệp, huyền huyễn, ngôn tình...

https://truyen.thuvienbao.com/
