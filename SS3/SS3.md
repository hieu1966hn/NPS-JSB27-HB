Ôn lại kiến thức buổi 2

- display: flex
- float:
- div: công dụng
- class, id
- Các cách sử dụng CSS

display: Thể hiện sự hiển thị của thẻ trên trang web ntn. Dưới đây là 1 vài thuộc tính đi kèm của display
body{
thuoc_tinh: value;
}

- inline: trong dòng => viết trong cùng 1 dòng.
- block: Dạng khối và có chiều ngang (1 dòng) toàn bộ màn hình website.
- inline-block: ....
- flex;

Các cách style cho 1 thẻ

- inline: viết trong thẻ mở với thuộc tính style
- sử dụng cặp thẻ <stlye></stlye>
- Sử dụng file.css bên ngoài để style.

Lưu ý: Trong các thẻ HTML thường có mặc định thuộc tính display cho từng thẻ.

- Các thẻ inline: span, b, i, u, a(dẫn link sang web khác), mark, strong, img, ...
- Các thẻ block: div, p, h1->6, .....

Box-Model

- Content;
- padding; 4 hướng (lên xuống trái phải)
- border;
- margin; 4 hướng (lên xuống trái phải)

- Các thẻ inline:

* padding: 4 hướng được
* Margin: 2 hướng gồm: trái phải

- Các thẻ block:

* padding: 4 hướng được
* Margin: 4 hướng được.

- Với thẻ có thuộc tính: inline-block; Kết hợp cả 2 thuộc tính.

- class: nhóm các thẻ mong muốn có cùng thuộc tính được khai báo:

* Tính tái sử dụng
* Khá tiện và gọn vì không còn cần phải gọi tên thẻ khi style VD: div{color: red;} => đúng hơn: .red{color: red;}

- id: Sử dụng cho duy nhất 1 thẻ trong dự án.

* Ít sử dụng

Cách style với CSS:
.red{}: class
#blue{}: id

Display: flex;

- flex-direction: chọn chiều trục chính (mặc định là: row)
- justify-content: Căn vị trí nội dung của các phần tử con

* left/right/center: theo vị trí từng hướng (all các item ở vị trí đó)
* space-around: Dàn đều các item. Khoảng cách các item bằng nhau (lề trái + lề phải == khoảng cách các item)
* space-between:Dàn đều các item. Khoảng cách các item bằng nhau (item trái, phải ngoài cùng đều trùng với đường viền thẻ cha).
* space-evenly: Khoảng cách các item bằng nhau và bằng khoảng cách từ item cuối -> lề.

order
