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