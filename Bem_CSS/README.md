# BEM
- BEM là viết tắt của Block, Element, Modifier.
- Block có thể hiểu là thẻ cha và trong thẻ cha bao gồm những
Elements trong đó.
- Modifier là bổ sung ý nghĩa cho Block hoặc Elements

# Cú Pháp
- .block
- .block__element

- .block--modifier
- .block__element--modifier


# Những thuộc tính mới tiếp thu
- cursor: pointer; -> tạo ra con trỏ chuột có thể click khi trỏ vào
- background-color: transparent; -> làm trong suốt 
- ouline: none; -> outline là đường viền khi trỏ chuột vào ( none là loại bỏ )
- TRICK -> sử dụng selector để CSS những class đứng cạnh nhau nhanh hơn 
    ví dụ: .btn + .btn{
        padding:...;
        margin:...;
    }

- line-height: (nen xai so thap phan);

- @keyframes
Bắt đầu bằng cách tạo một quy tắc @keyframes, đặt cho nó một tên duy nhất để xác định hoạt hình.
Bên trong quy tắc, bạn chỉ định một hoặc nhiều khung hình chính, giống như ảnh chụp nhanh của hoạt hình tại các thời điểm khác nhau.
   ví dụ: ta ghi @keyframes ra xong đặt 1 tên cho nó
          trong mỗi khung hình chính, bạn xác định các thuộc tính CSS (ví dụ: transform, opacity) muốn hoạt hình hóa

          Sau khi bạn xác định quy tắc @keyframes, bạn có thể áp dụng hoạt hình cho một phần tử HTML bằng cách sử dụng thuộc tính animation.
Thuộc tính này lấy một số giá trị, bao gồm:
animation-name: Tham chiếu tên bạn đã đặt cho quy tắc @keyframes.
animation-duration: Xác định tổng thời gian hoạt hình sẽ hoàn thành (ví dụ: 1s, 2s).
Các thuộc tính tùy chọn khác như animation-timing-function, animation-delay, animation-iteration-count và animation-direction có thể tùy chỉnh thêm thời gian phát lại và hành vi của hoạt hình.
