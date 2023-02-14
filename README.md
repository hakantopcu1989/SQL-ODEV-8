# SQL-ODEV-8
SQL-ODEV-8


1.	test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
2.	Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
3.	Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
4.	Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
Çözüm : 1  
 CREATE TABLE employee (
	id SERIAL,
	name VARCHAR (50),
	birthday DATE,
	email VARCHAR(100)
)
Çözüm 2 : 
insert into employee (name, birthday, email) values ('Georgia', 'error: invalid date "31/12/2000"', 'gtellwright0@mail.ru');
insert into employee (name, birthday, email) values ('Vivyan', 'error: invalid date "31/12/2000"', 'vabramow1@unicef.org');
insert into employee (name, birthday, email) values ('Margo', null, null);
insert into employee (name, birthday, email) values ('Fayina', 'error: invalid date "31/12/2000"', 'fhartfield3@drupal.org');
insert into employee (name, birthday, email) values ('Merilee', 'error: invalid date "31/12/2000"', 'mdalgetty4@seesaa.net');
insert into employee (name, birthday, email) values ('Ardella', 'error: invalid date "31/12/2000"', 'arollingson5@t-online.de');
insert into employee (name, birthday, email) values ('Averyl', 'error: invalid date "31/12/2000"', 'acrowley6@jugem.jp');
insert into employee (name, birthday, email) values ('Louisa', 'error: invalid date "31/12/2000"', 'llackie7@narod.ru');
insert into employee (name, birthday, email) values ('Emeline', 'error: invalid date "31/12/2000"', 'epylkynyton8@networksolutions.com');
insert into employee (name, birthday, email) values ('Vitia', null, null);
insert into employee (name, birthday, email) values ('Orelee', 'error: invalid date "31/12/2000"', 'olambrooka@google.com.hk');
insert into employee (name, birthday, email) values ('Atlanta', 'error: invalid date "31/12/2000"', 'asonierb@technorati.com');
insert into employee (name, birthday, email) values ('Hermine', 'error: invalid date "31/12/2000"', 'hfallanchec@dagondesign.com');
insert into employee (name, birthday, email) values ('Gae', 'error: invalid date "31/12/2000"', 'grockalld@multiply.com');
insert into employee (name, birthday, email) values ('Bobinette', 'error: invalid date "31/12/2000"', 'bboltone@paypal.com');
insert into employee (name, birthday, email) values ('Klara', 'error: invalid date "31/12/2000"', 'koverellf@tumblr.com');
insert into employee (name, birthday, email) values ('Kynthia', 'error: invalid date "31/12/2000"', 'ktottong@ask.com');
insert into employee (name, birthday, email) values ('Zorana', 'error: invalid date "31/12/2000"', 'zboyntonh@businesswire.com');
insert into employee (name, birthday, email) values ('Jeannie', 'error: invalid date "31/12/2000"', 'jbrignalli@google.nl');
insert into employee (name, birthday, email) values ('Brittani', null, null);
insert into employee (name, birthday, email) values ('Dody', null, null);
insert into employee (name, birthday, email) values ('Brietta', null, null);
insert into employee (name, birthday, email) values ('Alla', 'error: invalid date "31/12/2000"', 'adowdellm@wikispaces.com');
insert into employee (name, birthday, email) values ('Brena', 'error: invalid date "31/12/2000"', 'btabertn@macromedia.com');
insert into employee (name, birthday, email) values ('Katharina', null, null);
insert into employee (name, birthday, email) values ('Lissa', null, null);
insert into employee (name, birthday, email) values ('Phyllys', 'error: invalid date "31/12/2000"', 'pdsouzaq@utexas.edu');
insert into employee (name, birthday, email) values ('Patience', null, null);
insert into employee (name, birthday, email) values ('Bev', 'error: invalid date "31/12/2000"', 'bbraggers@naver.com');
insert into employee (name, birthday, email) values ('Grace', 'error: invalid date "31/12/2000"', 'gweighellt@archive.org');
insert into employee (name, birthday, email) values ('Moria', 'error: invalid date "31/12/2000"', 'mconneelyu@wikimedia.org');
insert into employee (name, birthday, email) values ('Nicolea', 'error: invalid date "31/12/2000"', 'nshimminv@lycos.com');
insert into employee (name, birthday, email) values ('Ddene', 'error: invalid date "31/12/2000"', 'ddimitrescuw@sciencedirect.com');
insert into employee (name, birthday, email) values ('Ursa', null, null);
insert into employee (name, birthday, email) values ('Winnie', 'error: invalid date "31/12/2000"', 'whambrighty@myspace.com');
insert into employee (name, birthday, email) values ('Guillema', 'error: invalid date "31/12/2000"', 'gclipshamz@seesaa.net');
insert into employee (name, birthday, email) values ('Jorry', 'error: invalid date "31/12/2000"', 'jbohlens10@mapy.cz');
insert into employee (name, birthday, email) values ('Madelene', 'error: invalid date "31/12/2000"', 'msandeford11@themeforest.net');
insert into employee (name, birthday, email) values ('Moyra', 'error: invalid date "31/12/2000"', 'mbearne12@vk.com');
insert into employee (name, birthday, email) values ('Tatum', null, null);
insert into employee (name, birthday, email) values ('Cordula', 'error: invalid date "31/12/2000"', 'ckiley14@is.gd');
insert into employee (name, birthday, email) values ('Nerissa', 'error: invalid date "31/12/2000"', 'nglascott15@cargocollective.com');
insert into employee (name, birthday, email) values ('Gabi', 'error: invalid date "31/12/2000"', 'gdevile16@baidu.com');
insert into employee (name, birthday, email) values ('Nerissa', 'error: invalid date "31/12/2000"', 'nyashunin17@accuweather.com');
insert into employee (name, birthday, email) values ('Cori', 'error: invalid date "31/12/2000"', 'cscarf18@ed.gov');
insert into employee (name, birthday, email) values ('Bella', 'error: invaliinsert into employee (name, birthday, email) values ('Jemie', '1901-10-14', 'jhouldey0@miitbeian.gov.cn');
insert into employee (name, birthday, email) values ('Colly', null, null);
insert into employee (name, birthday, email) values ('Willamina', '1953-05-13', 'wsergeant2@wsj.com');
insert into employee (name, birthday, email) values ('Meridith', null, null);
insert into employee (name, birthday, email) values ('Babette', '1953-03-11', 'bvalenta4@sourceforge.net');
insert into employee (name, birthday, email) values ('Jodie', '1971-06-23', 'jkauscher5@elpais.com');
insert into employee (name, birthday, email) values ('Deva', '1944-04-11', 'dfewtrell6@meetup.com');
insert into employee (name, birthday, email) values ('Jocelyn', '1996-08-10', 'jruzek7@phoca.cz');
insert into employee (name, birthday, email) values ('Rubi', null, null);
insert into employee (name, birthday, email) values ('Elita', null, null);
insert into employee (name, birthday, email) values ('Trenna', null, null);
insert into employee (name, birthday, email) values ('Nicolette', '1960-12-08', 'nrimellb@cafepress.com');
insert into employee (name, birthday, email) values ('Perri', '1989-05-22', 'prestieauxc@ucoz.ru');
insert into employee (name, birthday, email) values ('Nicol', '1921-06-25', 'nmarcosd@angelfire.com');
insert into employee (name, birthday, email) values ('Vanda', '1938-02-07', 'vknipee@t.co');
insert into employee (name, birthday, email) values ('Nerta', '1986-06-15', 'ncorraof@bloglovin.com');
insert into employee (name, birthday, email) values ('Gabriell', '1941-01-16', 'grathjeng@spiegel.de');
insert into employee (name, birthday, email) values ('Bambi', '1960-04-29', 'bbigbyh@bloglines.com');
insert into employee (name, birthday, email) values ('Karisa', null, null);
insert into employee (name, birthday, email) values ('Tandy', '1976-03-27', 'tchessellj@a8.net');
insert into employee (name, birthday, email) values ('Elyssa', '1937-07-25', 'enundk@nature.com');
insert into employee (name, birthday, email) values ('Wilma', '1970-12-23', 'wfairbairnl@noaa.gov');
insert into employee (name, birthday, email) values ('Maribelle', '1932-10-04', 'mtaggettm@de.vu');
insert into employee (name, birthday, email) values ('Carol-jean', '1939-05-13', 'cfeehamn@blogger.com');
insert into employee (name, birthday, email) values ('Christiana', '1908-08-23', 'ccrosskello@vkontakte.ru');
insert into employee (name, birthday, email) values ('Bonnie', null, null);
insert into employee (name, birthday, email) values ('Bella', '1945-03-06', 'blubeckq@merriam-webster.com');
insert into employee (name, birthday, email) values ('Loraine', '1925-08-22', 'lyaxleyr@google.com.au');
insert into employee (name, birthday, email) values ('Laura', '1988-06-01', 'ltiplers@newsvine.com');
insert into employee (name, birthday, email) values ('Delia', '1940-06-01', 'djatczakt@hexun.com');
insert into employee (name, birthday, email) values ('Elset', '1961-09-21', 'evilesu@is.gd');
insert into employee (name, birthday, email) values ('Janifer', '1966-03-06', 'jblackshawv@instagram.com');
insert into employee (name, birthday, email) values ('Kala', '1931-12-08', 'kwehnerw@xing.com');
insert into employee (name, birthday, email) values ('Jeanie', '1913-03-17', 'jvaskovx@usgs.gov');
insert into employee (name, birthday, email) values ('Arda', '1906-04-20', 'atollerfieldy@digg.com');
insert into employee (name, birthday, email) values ('Margie', '1937-03-23', 'mscopynz@tamu.edu');
insert into employee (name, birthday, email) values ('Allene', '1947-09-16', 'ajaine10@blogspot.com');
insert into employee (name, birthday, email) values ('Dannie', '1902-06-28', 'dczaple11@netvibes.com');
insert into employee (name, birthday, email) values ('Tiffany', '1961-02-06', 'tbrandreth12@flickr.com');
insert into employee (name, birthday, email) values ('Kimmie', '1901-03-24', 'kcockill13@wunderground.com');
insert into employee (name, birthday, email) values ('Melessa', '1915-11-07', 'mrowden14@bigcartel.com');
insert into employee (name, birthday, email) values ('Dionne', '1978-03-04', 'dtreadgold15@google.de');
insert into employee (name, birthday, email) values ('Kristine', '1966-05-16', 'klegion16@reuters.com');
insert into employee (name, birthday, email) values ('Patti', null, null);
insert into employee (name, birthday, email) values ('Kristine', '1986-03-29', 'kgandrich18@alexa.com');
insert into employee (name, birthday, email) values ('Naoma', '1905-08-05', 'nschoular19@apple.com');
insert into employee (name, birthday, email) values ('Nadean', null, null);
insert into employee (name, birthday, email) values ('Tammara', '1975-09-08', 'tjohnes1b@blogs.com');
insert into employee (name, birthday, email) values ('Mady', '1985-10-16', 'mkonrad1c@tinypic.com');
insert into employee (name, birthday, email) values ('Cristen', null, null);d date "31/12/2000"', 'bschiesterl19@google.pl');
insert into employee (name, birthday, email) values ('Maddalena', null, null);
insert into employee (name, birthday, email) values ('Valentine', null, null);
insert into employee (name, birthday, email) values ('Rhetta', null, null);
insert into employee (name, birthday, email) values ('Rochelle', 'error: invalid date "31/12/2000"', 'rbulteel1d@so-net.ne.jp');

Çözüm 3 :
 UPDATE employee set name='Mahoni' WHERE id=10
UPDATE employee set birthday='1985-10-10' WHERE id=30
UPDATE employee set email='kodlamaci@yahoo.com' WHERE name='Tiffany'
UPDATE employee set name='Suzan' WHERE name='Melessa'
UPDATE employee set email='deneme@mynet' WHERE id=18

Çözüm 4 : 
DELETE FROM employee WHERE name='Delia'
DELETE FROM employee WHERE birthday='1988-06-01'
DELETE FROM employee WHERE id=23
DELETE FROM employee WHERE email='"nrimellb@cafepress.com"'
DELETE FROM employee WHERE id=11
