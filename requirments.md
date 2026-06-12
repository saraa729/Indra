## --Төслийн нэр--
IndraCyber Institute Website

## --Төслийн зорилго--
IndraCyber Institute-ийн сургалтын үйл ажиллагаа, мэргэжлийн хөтөлбөрүүд, ангиудын мэдээлэл, элсэлтийн бүртгэл болон суралцагчдад зориулсан мэдээллийг цахимаар хүргэх веб систем боловсруулах.

## 1.--Сургуулийн мэдээлэл
IndraCyber Institute нь дараах мэргэжлүүдээр сургалт явуулна.
## 1. Software Engineering
3 анги
Веб хөгжүүлэлт
Mobile хөгжүүлэлт
Database & Backend

## 2. Graphic Design
1 анги
Photoshop
Illustrator
UI/UX Design

## 3. Digital Marketing
3 анги
Social Media Marketing
SEO
Content Marketing


## 2. Functional Requirements
Home Page
ID	Requirement
FR-01	Нүүр хуудас байх
FR-02	Сургуулийн танилцуулга харагдах
FR-03	Сургуулийн статистик харуулах
FR-04	Онцлох мэдээ харуулах


## Programs Module
ID	Requirement
FR-05	Software Engineering мэдээлэл харах
FR-06	Graphic Design мэдээлэл харах
FR-07	Digital Marketing мэдээлэл харах
FR-08	Ангиудын мэдээлэл харах
FR-09	Сургалтын төлөвлөгөө харах


## Admission Module
ID	Requirement
FR-10	Элсэлтийн мэдээлэл харах, 
FR-11	Онлайн бүртгэл хийх,
FR-12	Бүртгэлийн мэдээлэл хадгалах,
FR-13	Админ бүртгэлүүдийг харах,
FR-14	Элсэгчийн төлөв шинэчлэх

## News Module
ID	Requirement
FR-15	Мэдээ нийтлэх
FR-16	Мэдээ засах
FR-17	Мэдээ устгах
FR-18	Мэдээ унших

## Teacher Module
ID	Requirement
FR-19	Багш нарын мэдээлэл харах
FR-20	Багш нэмэх
FR-21	Багшийн мэдээлэл засах
FR-22	Багш устгах


## Student Portal
ID	Requirement
FR-23	Student Login
FR-24	Хуваарь харах
FR-25	Зар мэдээлэл харах
FR-26	Профайл харах


## Contact Module
ID	Requirement
FR-27	Холбоо барих форм
FR-28	Google Map харуулах
FR-29	Сошиал хаяг харуулах


## 3. Non-Functional Requirements
--Security
JWT Authentication
Password Encryption
Role Based Authorization

--Performance
Хуудас 3 секундээс бага хугацаанд ачаалагдах
Availability
24/7 ажиллагаатай байх

## 4. Database Tables
🔐 Role тайлбар (System design)

👑 superadmin
Бүх эрхтэй
Admin үүсгэнэ / устгана
System settings удирдана

🧑‍💼 admin
Системийн үндсэн удирдлага
Programs / Teachers / News CRUD
Admissions хянах

🛡 moderator
Content хянагч
News approve/edit
Comments / contacts шалгах

👨‍🏫 teacher
Өөрийн profile
Class мэдээлэл харах
Student list харах (өөрийн class)

🧑‍💻 staff (ажилтан)
Admissions data оруулах
Student бүртгэл хийх
Internal support

🎓 student
Login
Schedule харах
News харах
Profile харах

👤 user (visitor)
Public access only
Login хийхгүй байж болно