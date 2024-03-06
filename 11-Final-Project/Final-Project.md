### Final Project

## Final project sẽ gồm các kiến thức sau: 
1. Kiểu dữ liệu
2. Struct
3. Trait ( trait bound, associated type, )
4. Generic Type 
5. Viết unit tests (cách sử dụng `assert_eq!` để so sánh kết quả thực tế và kết quả mong muốn) (Phần này mặc dù ko có trong chương trình nhưng mọi người có thể hiểu đơn giản là viết các trường hợp test cho logic của mình có đúng hay không)

Ví dụ :
+ Định nghĩa viết test case 
```rust
// định nghĩa viết test case 
#[cfg(test)]
mod tests {
    // unit test 
    #[test]
	fn one_greater_than_zero() {
        assert!(1>0, "1 lớn hơn 0");
    }
    #[test]
	fn one_equal_one() {
        assert_eq!(1, 1);
    }
}
```

+ Chạy test bằng `cargo test`

6. Cấu trúc file cơ bản : `lib.rs`, các module khác ví dụ như `energy.rs` ( Phần thảo luận)
7. Macro trong Rust (Phần thảo luận)

## Implementation
+ Đọc hiểu nội dung của logic 
+ Hoàn thành `todo!()`


## Run test

```bash
cargo test 
```

## Cách thức nộp bài 
Submit kết quả trên nền tảng `OpenEdu101 - Rust Bootcamp 2024`
https://www.openedu101.com/bootcamp/5gp9y3a3oze654s

Gồm có: 
+ Final Project Github Link 
+ A screenshot of your terminal after running `cargo test`
