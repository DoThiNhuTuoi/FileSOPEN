# Hướng dẫn cập nhật tài liệu sử dụng phần mềm quản trị - Ban CNTT

Repository này được tạo ra với mục đích xây dựng tài liệu hướng dẫn sử dụng phần mềm. Giúp người dùng dễ dàng tiếp cận các sản phẩm của Ban CNTT. Dưới đây là các lưu ý khi cập nhật hướng dẫn sử dụng phần mềm.

## Cấu trúc project 

    mkdocs.yml    # File cấu hình.
    docs/
        index.md  # Trang chủ giới thiệu.
        hrm       # Thư mục theo từng phân hệ (Nhân sự, Kế toán, SaaS Portal, Digital Workplace, Văn phòng...)
            introduction.md             # Giới thiệu chung về phân hệ
            initialization.md           # Thiết lập và khai báo ban đầu
            abbreviations.md            # Thuật ngữ và từ viết tắt
            master-datas.md             # Khai báo danh mục 
            log-histories.md            # Lịch sử phát triển phân hệ
            employee.md,recruitment.md  # Mô tả các module trong phân hệ
            images/                     # Lưu trữ hình ảnh đính kèm

## Cấu trúc Menu một phân hệ

File cấu hình: mkdocs.yml

    - 'Nhân sự': 
            - 'Giới thiệu về phân hệ Quản lý nhân sự': 'hrm/introduction.md'
            - 'Thiết lập và khai báo ban đầu': 'hrm/initialization.md'
            - 'Các thuật ngữ và từ viết tắt': 'hrm/abbreviations.md'
            - 'Hướng dẫn sử dụng chức năng':
                - 'Khai báo danh mục': 'hrm/master-datas.md'
                - 'Tuyển dụng': 'hrm/recruitment.md'
                - 'Nhân viên': 'hrm/employee.md'
           	- 'Lịch sử phát triển sản phẩm': 'hrm/log-histories.md'
## 3. Sử dụng công cụ Typora 

Trang chủ: [https://typora.io/](https://typora.io/)

Hướng dẫn sử dụng Markdown cơ bản: [https://support.typora.io/Markdown-Reference/](https://support.typora.io/Markdown-Reference/)

Một số thao tác với hình ảnh với Typora: [https://support.typora.io/Images/](https://support.typora.io/Images/)

### Một số lưu ý

1. Các đầu mục lớn phải đặt format Headings, bắt đầu từ h1 -> h6
2. Các đầu mục lớn không cần đánh số chỉ mục như 1,1.1,... Chỉ phân cấp qua Headings. Recommend sử dụng tab **Outline** trên **Sidebar** của Typora để quản trị tốt hơn. 

### Cấu hình upload  hình ảnh  đính kèm

> **Cấu hình cho phép end user chỉ cần paste hoặc Drag & Drop 1 ảnh bất kỳ, Typora sẽ tự copy ảnh vào phân vùng lưu trữ & gắn path đến phân vùng đó.**
>
> **Tất cả các đường dẫn hình ảnh đính kèm bắt buộc cấu hình ở dạng tương đối (relative path).**

Chọn: Format → Image → When Insert Local Images → Global Image Settings.

Cấu hình như hình dưới.

![image-20210914093218818](images/image-20210914093218818.png)

Sau khi cấu hình xong, test lại đường dẫn relative path như hình dưới là OK.

![image-20210914093759081](images/image-20210914093759081.png)



### 



