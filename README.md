\\# DevOps Hackathon - Đề 004: Quản lý kho hang (Inventory)







\\## 1. Thông tin sinh viên







| Họ và tên | Mã sinh viên | Lớp | Tài khoản Linux | GitHub | Cổng Nginx |



|---|---|---|---|---|---|



| Hà Thị Minh Trang | STU-PTIT-HN-061-RE | HN-KS24-CNTT2 | htmtrang-k24cntt2 | mtrangcp | 8080 |







\\## 2. Môi trường triển khai







\\- Hệ điều hành: Ubuntu 24.04 LTS



\\- Web server: Nginx



\\- Công cụ quản lý mã nguồn: Git



\\- Firewall: UFW



\\- Môi trường triển khai: VPS



\\- Server IP: 221.121.4.114



\\- Cổng website: 8080







\\## 3. Cấu trúc dự án







```text



devops-hackathon-de004-hathiminhtrang/



├── src/



│   └── index.html



├── nginx/



│   └── htmtrang-k24cntt2.conf



├── screenshots/



├── .gitignore



└── README.md

```

\## 4. Cấu hình Nginx



| Tham số | Giá trị |

|---|---|

| PORT | 8080 |

| SERVER\_NAME | 221.121.4.114 |

| WEB\_ROOT | /var/www/devops-hackathon-de004-hathiminhtrang/src |

| INDEX\_FILE | index.html |

| TEN\_TAI\_KHOAN | htmtrang-k24cntt2 |

| ALLOW\_DIRECTIVE | allow all; |



\## 5. Website



http://221.121.4.114:8080



\## 6. Cấu hình UFW



\- Cho phép SSH: 22/tcp

\- Cho phép website cá nhân: 8080/tcp

\- UFW đang ở trạng thái active.



\## 7. Minh chứng

screenshots







