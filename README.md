# javsctript

## Day 1
### Fundamental of Git
#### Git version
- [ git --v ] ->  Kiểm tra phiên bản của Git.

#### Git config
- [ git config --g user.name "Dev name" ] -> Set user name
- [ git config --g user.email "Dev email" ] -> Set email
- [ git config --g list ] -> Hiển thị thông tin đã có sẵn trên máy

#### Git init
- [ git init ] -> khi muốn tạo một phiên bản git mới cho một dự án.
#### Git status
- [ git status] -> Kiểm tra trạng thái của kho lưu trữ
- [ git status --short ] 
  +   ?? - Tập tin không bị theo dõi
  +   A - Tệp được thêm vào giai đoạn
  +   M - Tệp đã sửa đổi
  +   D - Các tệp đã xóa

#### Git add
- [ git add . ]
- [ git add --all]
- [ git add index.html]

#### Git commit
- [ git commit -m " thông điệp"] -> Ghi lại các thay đổi vào kho lưu trữ

#### Git push

- [ git push -u origin branch_mane]  -> Đẩy nhánh (brach) vào remote repository
- [ git push] - (Đẩy) tất cả mọi thay đổi (đã commit) lên remote repository.
- [ git push -d origin branch_mane] -> Xóa một branch trên remote repository.
- [ git push -f origin branch_mane] -> Push force sẽ apply toàn bộ log ở local của bạn lên branch ở repo, bất chấp log 2 nơi khác nhau. (Xóa vĩnh viễn branch cũ Push branch mới. Dễ gây conflict cho người khác cẩn trọng trước khi dùng)

## Day 2

