# GG Harvest - Website 1 Page

Bo giao dien gom:

- `index.html`: noi dung trang chu GG Harvest.
- `styles.css`: mau sac, bo cuc responsive va animation.
- `script.js`: menu mobile, header khi cuon trang va hieu ung hien noi dung.
- `subtitles.vtt`: phu de mau cho video gioi thieu 30 giay.

## Cach dung

Mo truc tiep file `index.html` bang trinh duyet.

## Thay anh

Tim cac the `<img src="...">` trong `index.html` va thay bang duong dan anh moi.

## Thay video 30 giay

Trong section `Video gioi thieu`, thay:

```html
<source src="" type="video/mp4" />
```

bang:

```html
<source src="ten-file-video.mp4" type="video/mp4" />
```

File `subtitles.vtt` da duoc gan san vao video. Neu co phu de rieng, thay ten file tai dong:

```html
<track src="subtitles.vtt" kind="subtitles" srclang="vi" label="Tieng Viet" default />
```
