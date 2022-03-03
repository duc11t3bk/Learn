# Outsystems

## Documents

#### 1. Outsystems 11
Link [https://success.outsystems.com/Documentation/11/New_in_OutSystems_11](https://success.outsystems.com/Documentation/11/New_in_OutSystems_11)

## Question
#### Q1.
 - Trong dự án thực tế thì dùng DB của OS hay liên kết với DB bên ngoài ? AWS RDS,..
#### Q2.
 - Dùng I18n ?
#### Q3.
 - Có quản lý tập trung validation error message ở file ? bằng cách nào ? 
#### Q4.
 - Tạo data Create update với many-many relation
 - Tạo UI động thêm mới item - delete item

Answer 
 > https://www.youtube.com/watch?v=wivOMW-DkKU 

#### Q5.
 - Designing Apps Using an Architecture Framework
   - Naming Conventions for Modules
   - Typical Module Elements

## Memo
#### 1. Joins Agreggates
 > https://www.outsystems.com/forums/discussion/60874/joins-agreggates/ 

Automated is just Only With (if foreign key is a mandatory attribute) and With or Without (if is not mandatory) because they are the obvious choices:

if it is mandatory, I can do a Inner Join because they will match. If it is not mandatory, I keep the relevant table and all the extra info is a bonus.