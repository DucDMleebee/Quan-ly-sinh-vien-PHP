Project PHP về Quản lý sinh viên
được thưc hiện bởi Đặng Minh Đức và Nguyễn Cao Huy Hoàng

Hướng dẫn sử dụng:
- Dùng MYSQL tạo các database có tên như sau: class, message, game.
- Trong database "class" có các bảng sau:
+ Student:
+----------+-----------------+------+-----+---------+----------------+
| Field    | Type            | Null | Key | Default | Extra          |
+----------+-----------------+------+-----+---------+----------------+
| id       | int(6) unsigned | NO   | PRI | NULL    | auto_increment |
| username | varchar(30)     | NO   |     | NULL    |                |
| password | varchar(30)     | NO   |     | NULL    |                |
| fullname | varchar(30)     | NO   |     | NULL    |                |
| email    | varchar(30)     | NO   |     | NULL    |                |
| phonenum | varchar(10)     | NO   |     | NULL    |                |
+----------+-----------------+------+-----+---------+----------------+

+ Teacher:
+----------+-------------+------+-----+---------+-------+
| Field    | Type        | Null | Key | Default | Extra |
+----------+-------------+------+-----+---------+-------+
| username | varchar(30) | NO   | PRI | NULL    |       |
| password | varchar(30) | YES  |     | NULL    |       |
+----------+-------------+------+-----+---------+-------+

- Database "message" để trống.
- Trong database "game" có bảng "challenge":
+-----------+--------------+------+-----+---------+----------------+
| Field     | Type         | Null | Key | Default | Extra          |
+-----------+--------------+------+-----+---------+----------------+
| chalID    | int(11)      | NO   | PRI | NULL    | auto_increment |
| challenge | varchar(255) | YES  |     | NULL    |                |
| hints     | varchar(255) | YES  |     | NULL    |                |
+-----------+--------------+------+-----+---------+----------------+

- Ngoài ra trong thư mục gốc này tạo thêm 2 thư mục con là baitap va challenge.

Các chức năng và người thực hiện:

