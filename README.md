# SQL-Odev8

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (
   id INTEGER PRIMARY KEY
   name VARCHAR(50)
   email VARCHAR(100)
   birthday DATE);

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into MOCK_DATA (email, name, birthday) values ('thamshar0@blinklist.com', 'Thatch Hamshar', '1989-08-22');
insert into MOCK_DATA (email, name, birthday) values ('jsmowton1@biblegateway.com', 'Jeanine Smowton', '1980-06-19');
insert into MOCK_DATA (email, name, birthday) values ('cfitton2@arstechnica.com', 'Cacilia Fitton', '1980-05-31');
insert into MOCK_DATA (email, name, birthday) values ('vvan3@1und1.de', 'Vinnie Van Dalen', '1942-10-30');
insert into MOCK_DATA (email, name, birthday) values ('tboyse4@reuters.com', 'Tanya Boyse', '1989-02-13');
insert into MOCK_DATA (email, name, birthday) values ('bliddiard5@typepad.com', 'Brody Liddiard', '1991-12-08');
insert into MOCK_DATA (email, name, birthday) values ('ccasperri6@behance.net', 'Cozmo Casperri', '1926-09-05');
insert into MOCK_DATA (email, name, birthday) values ('pdreinan7@163.com', 'Pansie Dreinan', '1961-09-24');
insert into MOCK_DATA (email, name, birthday) values ('fgommery8@sphinn.com', 'Flossi Gommery', '1983-08-12');
insert into MOCK_DATA (email, name, birthday) values ('jshillitoe9@histats.com', 'Jordan Shillitoe', '1921-01-14');
insert into MOCK_DATA (email, name, birthday) values ('ttrevera@twitter.com', 'Towney Trever', '1996-12-08');
insert into MOCK_DATA (email, name, birthday) values ('jstandidgeb@admin.ch', 'Jocko Standidge', '1947-06-19');
insert into MOCK_DATA (email, name, birthday) values ('ckarolewskic@dell.com', 'Cyndy Karolewski', '1950-04-03');
insert into MOCK_DATA (email, name, birthday) values ('hlonginad@360.cn', 'Harlen Longina', '1978-10-10');
insert into MOCK_DATA (email, name, birthday) values ('istaniforde@com.com', 'Isaiah Staniford', '1944-11-07');
insert into MOCK_DATA (email, name, birthday) values ('gingreyf@thetimes.co.uk', 'Ginni Ingrey', '1909-02-23');
insert into MOCK_DATA (email, name, birthday) values ('bcastledineg@about.me', 'Bron Castledine', '1973-10-05');
insert into MOCK_DATA (email, name, birthday) values ('cgoveh@nih.gov', 'Cory Gove', '1948-11-29');
insert into MOCK_DATA (email, name, birthday) values ('jcollecki@myspace.com', 'Joella Colleck', '1965-11-12');
insert into MOCK_DATA (email, name, birthday) values ('dharremaj@macromedia.com', 'Deborah Harrema', '1943-06-16');
insert into MOCK_DATA (email, name, birthday) values ('eceschinik@youtu.be', 'Eugenie Ceschini', '1998-05-10');
insert into MOCK_DATA (email, name, birthday) values ('jgodballl@tiny.cc', 'Jasper Godball', '1947-01-02');
insert into MOCK_DATA (email, name, birthday) values ('mingreem@fc2.com', 'Mylo Ingree', '1920-08-29');
insert into MOCK_DATA (email, name, birthday) values ('dohoolahann@yahoo.co.jp', 'Deborah O''Hoolahan', '1938-09-06');
insert into MOCK_DATA (email, name, birthday) values ('ddmitrichenkoo@jugem.jp', 'Dov Dmitrichenko', '1935-06-19');
insert into MOCK_DATA (email, name, birthday) values ('earmandp@japanpost.jp', 'Emmey Armand', '1929-04-28');
insert into MOCK_DATA (email, name, birthday) values ('rashcroftq@amazon.co.jp', 'Ronica Ashcroft', '1946-05-05');
insert into MOCK_DATA (email, name, birthday) values ('sscuffhamr@admin.ch', 'Sherlocke Scuffham', '1956-02-12');
insert into MOCK_DATA (email, name, birthday) values ('mmaclises@is.gd', 'Melloney MacLise', '1938-09-20');
insert into MOCK_DATA (email, name, birthday) values ('sbriatt@deliciousdays.com', 'Sally Briat', '1943-02-10');
insert into MOCK_DATA (email, name, birthday) values ('descheu@reuters.com', 'Davon Esche', '1904-08-10');
insert into MOCK_DATA (email, name, birthday) values ('sbraynv@hao123.com', 'Shirleen Brayn', '1940-04-06');
insert into MOCK_DATA (email, name, birthday) values ('fgleadhallw@ucoz.ru', 'Farris Gleadhall', '1916-08-03');
insert into MOCK_DATA (email, name, birthday) values ('ecockingx@livejournal.com', 'Elga Cocking', '1910-04-03');
insert into MOCK_DATA (email, name, birthday) values ('bcollingtony@t.co', 'Bekki Collington', '1991-01-22');
insert into MOCK_DATA (email, name, birthday) values ('amugridgez@wufoo.com', 'Alexandr Mugridge', '1998-03-13');
insert into MOCK_DATA (email, name, birthday) values ('rtowner10@hugedomains.com', 'Raleigh Towner', '1917-05-16');
insert into MOCK_DATA (email, name, birthday) values ('bculp11@drupal.org', 'Boothe Culp', '1932-07-17');
insert into MOCK_DATA (email, name, birthday) values ('cbalsdone12@skyrock.com', 'Cathrine Balsdone', '1983-01-17');
insert into MOCK_DATA (email, name, birthday) values ('tstoite13@illinois.edu', 'Tybie Stoite', '1937-02-18');
insert into MOCK_DATA (email, name, birthday) values ('srome14@webeden.co.uk', 'Shell Rome', '1966-05-18');
insert into MOCK_DATA (email, name, birthday) values ('lreightley15@seesaa.net', 'Lizabeth Reightley', '1969-01-17');
insert into MOCK_DATA (email, name, birthday) values ('cfrancesch16@nymag.com', 'Caryl Francesch', '1980-02-15');
insert into MOCK_DATA (email, name, birthday) values ('coggers17@redcross.org', 'Carver Oggers', '1944-01-15');
insert into MOCK_DATA (email, name, birthday) values ('mdeval18@yolasite.com', 'Marcelline Deval', '1949-04-26');
insert into MOCK_DATA (email, name, birthday) values ('dtrosdall19@thetimes.co.uk', 'Daniela Trosdall', '1969-01-10');
insert into MOCK_DATA (email, name, birthday) values ('tphette1a@theatlantic.com', 'Tobie Phette', '1995-05-14');
insert into MOCK_DATA (email, name, birthday) values ('jchriston1b@ovh.net', 'Jobie Christon', '1985-07-31');
insert into MOCK_DATA (email, name, birthday) values ('tadacot1c@amazon.co.uk', 'Theodore Adacot', '1970-06-21');
insert into MOCK_DATA (email, name, birthday) values ('hgofforth1d@nbcnews.com', 'Harry Gofforth', '1936-02-06');

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
	SET name = 'ahuha aa',
	email = 'asd.com',
	birthday = '1983-01-01'
WHERE id = 10;

UPDATE employee
	SET name = 'aaa bb',
	email = 'fgh.com',
	birthday = '1963-09-04'
WHERE id = 11;

UPDATE employee
	SET name = 'ccc dd',
	email = 'jkl.com',
	birthday = '1976-02-15'
WHERE id = 18;

UPDATE employee
	SET name = 'ddd eeee',
	email = 'cvbn.com',
	birthday = '1991-04-07'
WHERE id = 22;

UPDATE employee
	SET name = 'eeee fff',
	email = 'zxcv.com',
	birthday = '1974-03-02'
WHERE id = 25;

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE id = 7;
RETURNING *;

DELETE FROM employee
WHERE name = 'Jasper Godball';
RETURNING *;

DELETE FROM employee
WHERE birthday = '1938-09-06';
RETURNING *;

DELETE FROM employee
WHERE email = 'ddmitrichenkoo@jugem.jp';
RETURNING *;

DELETE FROM employee
WHERE id = 19;
RETURNING *;


