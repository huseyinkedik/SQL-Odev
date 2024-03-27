1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
id INTEGER PRIMARY KEY,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100)
);
```
2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, name, birthday, email) values (1, 'Hortense', '2005-04-27', 'hmacnucator0@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (2, 'Selene', '2013-04-04', 'sdanielsohn1@wsj.com');
insert into employee (id, name, birthday, email) values (3, 'Raphael', '2010-02-24', 'rdanelut2@seesaa.net');
insert into employee (id, name, birthday, email) values (4, 'Kristal', '2017-07-20', 'kburnand3@who.int');
insert into employee (id, name, birthday, email) values (5, 'Pace', '2008-08-02', 'pkesley4@ovh.net');
insert into employee (id, name, birthday, email) values (6, 'Merle', '2021-06-30', 'mclink5@archive.org');
insert into employee (id, name, birthday, email) values (7, 'Mil', '2014-02-16', 'mticksall6@reference.com');
insert into employee (id, name, birthday, email) values (8, 'Ranee', '2023-12-16', 'rlytton7@ca.gov');
insert into employee (id, name, birthday, email) values (9, 'Siffre', '2021-12-11', 'sjennens8@patch.com');
insert into employee (id, name, birthday, email) values (10, 'Dame', '2002-05-21', 'dreston9@dell.com');
insert into employee (id, name, birthday, email) values (11, 'Jill', '2021-12-20', 'jdana@etsy.com');
insert into employee (id, name, birthday, email) values (12, 'Seka', '2008-04-27', 'stimbyb@huffingtonpost.com');
insert into employee (id, name, birthday, email) values (13, 'Gavin', '2022-02-18', 'gfrankishc@icio.us');
insert into employee (id, name, birthday, email) values (14, 'Kennie', '2015-09-11', 'kkonzelmannd@home.pl');
insert into employee (id, name, birthday, email) values (15, 'Susann', '2015-08-07', 'sreye@statcounter.com');
insert into employee (id, name, birthday, email) values (16, 'Tedman', '2014-06-03', 'trandsf@cdc.gov');
insert into employee (id, name, birthday, email) values (17, 'Bowie', '2020-04-21', 'bduddeng@miibeian.gov.cn');
insert into employee (id, name, birthday, email) values (18, 'Ailbert', '2012-12-10', 'abeath@unesco.org');
insert into employee (id, name, birthday, email) values (19, 'Calley', '2021-05-14', 'ckensholei@flickr.com');
insert into employee (id, name, birthday, email) values (20, 'Maureen', '2017-03-31', 'mbusainj@woothemes.com');
insert into employee (id, name, birthday, email) values (21, 'Datha', '2007-01-01', 'dbridgelandk@google.ca');
insert into employee (id, name, birthday, email) values (22, 'Adele', '2016-08-14', 'adingatel@1und1.de');
insert into employee (id, name, birthday, email) values (23, 'Agathe', '2003-03-05', 'aseggiem@pbs.org');
insert into employee (id, name, birthday, email) values (24, 'Gustaf', '2010-12-23', 'gashwelln@alexa.com');
insert into employee (id, name, birthday, email) values (25, 'Zacharie', '2005-12-01', 'zflintofto@desdev.cn');
insert into employee (id, name, birthday, email) values (26, 'Cheslie', '2015-01-08', 'cmollonp@yellowpages.com');
insert into employee (id, name, birthday, email) values (27, 'Erina', '2023-04-29', 'eeuelsq@blinklist.com');
insert into employee (id, name, birthday, email) values (28, 'Celka', '2023-11-13', 'cnormandaler@newyorker.com');
insert into employee (id, name, birthday, email) values (29, 'Karylin', '2019-02-27', 'kwhitleys@icq.com');
insert into employee (id, name, birthday, email) values (30, 'Amandi', '2015-10-18', 'awandrackt@spiegel.de');
insert into employee (id, name, birthday, email) values (31, 'Chris', '2017-11-24', 'cwisdishu@umich.edu');
insert into employee (id, name, birthday, email) values (32, 'Gordan', '2015-04-12', 'gbushbyv@imdb.com');
insert into employee (id, name, birthday, email) values (33, 'Nari', '2005-11-02', 'nkewishw@gizmodo.com');
insert into employee (id, name, birthday, email) values (34, 'Gard', '2021-02-06', 'galvaradox@scribd.com');
insert into employee (id, name, birthday, email) values (35, 'Lelah', '2013-04-23', 'lwolfery@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (36, 'Bobinette', '2003-07-18', 'bcarwardinez@google.fr');
insert into employee (id, name, birthday, email) values (37, 'Randolf', '2022-05-07', 'rlace10@github.io');
insert into employee (id, name, birthday, email) values (38, 'Theda', '2021-01-29', 'tlidster11@biblegateway.com');
insert into employee (id, name, birthday, email) values (39, 'Jory', '2016-12-17', 'jcalbrathe12@hhs.gov');
insert into employee (id, name, birthday, email) values (40, 'Lothaire', '2009-02-03', 'ldougher13@slideshare.net');
insert into employee (id, name, birthday, email) values (41, 'Gordan', '2019-08-10', 'gleivers14@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (42, 'Cameron', '2005-12-15', 'cyouster15@imgur.com');
insert into employee (id, name, birthday, email) values (43, 'Sally', '2002-05-11', 'sgreiswood16@canalblog.com');
insert into employee (id, name, birthday, email) values (44, 'Keslie', '2022-06-29', 'kalliston17@1688.com');
insert into employee (id, name, birthday, email) values (45, 'Doug', '2006-06-16', 'dstanlock18@webmd.com');
insert into employee (id, name, birthday, email) values (46, 'Vaughan', '2003-05-19', 'vlyosik19@shutterfly.com');
insert into employee (id, name, birthday, email) values (47, 'Gaspard', '2005-08-10', 'gglastonbury1a@1688.com');
insert into employee (id, name, birthday, email) values (48, 'Tan', '2010-05-12', 'tbows1b@csmonitor.com');
insert into employee (id, name, birthday, email) values (49, 'Isa', '2001-05-29', 'iwhereat1c@unblog.fr');
insert into employee (id, name, birthday, email) values (50, 'Leonie', '2019-10-12', 'ljenne1d@mediafire.com');
insert into employee (id, name, birthday, email) values (51, 'Courtnay', '2020-01-21', 'cmcarley1e@alexa.com');
insert into employee (id, name, birthday, email) values (52, 'Helsa', '2018-05-31', 'hlarrie1f@fotki.com');
insert into employee (id, name, birthday, email) values (53, 'Costanza', '2005-05-30', 'cyeardsley1g@merriam-webster.com');
insert into employee (id, name, birthday, email) values (54, 'Zollie', '2017-09-02', 'zmedendorp1h@skype.com');
insert into employee (id, name, birthday, email) values (55, 'Clarie', '2020-11-20', 'cpetto1i@dropbox.com');
insert into employee (id, name, birthday, email) values (56, 'Robbie', '2009-05-03', 'rfenkel1j@mysql.com');
insert into employee (id, name, birthday, email) values (57, 'Loren', '2003-12-04', 'lyurkevich1k@columbia.edu');
insert into employee (id, name, birthday, email) values (58, 'Karin', '2003-01-08', 'ksegar1l@theatlantic.com');
insert into employee (id, name, birthday, email) values (59, 'Gwenneth', '2003-10-12', 'gcovolini1m@tripadvisor.com');
insert into employee (id, name, birthday, email) values (60, 'Kate', '2006-04-04', 'kcyples1n@example.com');
insert into employee (id, name, birthday, email) values (61, 'Susan', '2014-03-16', 'sgowler1o@pagesperso-orange.fr');
insert into employee (id, name, birthday, email) values (62, 'Erminie', '2008-06-11', 'egotthard1p@google.co.uk');
insert into employee (id, name, birthday, email) values (63, 'Shelby', '2006-08-24', 'spryer1q@digg.com');
insert into employee (id, name, birthday, email) values (64, 'Evyn', '2018-02-04', 'emiddlemiss1r@cnn.com');
insert into employee (id, name, birthday, email) values (65, 'Patrice', '2021-05-06', 'pfannon1s@eventbrite.com');
insert into employee (id, name, birthday, email) values (66, 'Teressa', '2001-07-11', 'tjeannon1t@wisc.edu');
insert into employee (id, name, birthday, email) values (67, 'Oralla', '2014-05-06', 'osquirrel1u@bravesites.com');
insert into employee (id, name, birthday, email) values (68, 'Ethelbert', '2016-01-06', 'esaunderson1v@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (69, 'Merridie', '2021-10-03', 'mlikely1w@webs.com');
insert into employee (id, name, birthday, email) values (70, 'Randa', '2002-02-11', 'rhammerson1x@taobao.com');
insert into employee (id, name, birthday, email) values (71, 'Zonda', '2012-11-08', 'zlavalle1y@1688.com');
insert into employee (id, name, birthday, email) values (72, 'Concordia', '2000-10-28', 'cguerro1z@bbb.org');
insert into employee (id, name, birthday, email) values (73, 'Corly', '2002-08-15', 'cjablonski20@columbia.edu');
insert into employee (id, name, birthday, email) values (74, 'Noella', '2019-09-05', 'nreffe21@google.co.uk');
insert into employee (id, name, birthday, email) values (75, 'Neill', '2019-01-29', 'ntowse22@yelp.com');
insert into employee (id, name, birthday, email) values (76, 'Carlotta', '2011-04-05', 'cchateau23@dailymail.co.uk');
insert into employee (id, name, birthday, email) values (77, 'Mauricio', '2021-05-17', 'mpaeckmeyer24@nhs.uk');
insert into employee (id, name, birthday, email) values (78, 'Flin', '2013-05-10', 'fstrangward25@surveymonkey.com');
insert into employee (id, name, birthday, email) values (79, 'Leilah', '2018-10-13', 'lmattevi26@discuz.net');
insert into employee (id, name, birthday, email) values (80, 'Mord', '2015-04-05', 'mlafrentz27@ftc.gov');
insert into employee (id, name, birthday, email) values (81, 'Frederica', '2023-06-26', 'fharlett28@4shared.com');
insert into employee (id, name, birthday, email) values (82, 'Kelley', '2015-10-11', 'kmoyers29@networkadvertising.org');
insert into employee (id, name, birthday, email) values (83, 'Faustine', '2023-05-11', 'fheardman2a@blogspot.com');
insert into employee (id, name, birthday, email) values (84, 'Nixie', '2012-07-22', 'ncalleja2b@yelp.com');
insert into employee (id, name, birthday, email) values (85, 'Sisile', '2005-11-09', 'sorigan2c@privacy.gov.au');
insert into employee (id, name, birthday, email) values (86, 'Orlando', '2012-11-01', 'opachmann2d@surveymonkey.com');
insert into employee (id, name, birthday, email) values (87, 'Gus', '2007-12-30', 'giacomelli2e@ucoz.ru');
insert into employee (id, name, birthday, email) values (88, 'Kanya', '2003-09-08', 'kteasdale2f@addtoany.com');
insert into employee (id, name, birthday, email) values (89, 'Domenico', '2014-05-15', 'dharkin2g@marriott.com');
insert into employee (id, name, birthday, email) values (90, 'Gabriel', '2020-10-23', 'glatimer2h@indiegogo.com');
insert into employee (id, name, birthday, email) values (91, 'Nita', '2012-10-23', 'ndongate2i@hexun.com');
insert into employee (id, name, birthday, email) values (92, 'Miof mela', '2013-04-26', 'mramas2j@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (93, 'Alexio', '2016-03-06', 'abalas2k@ibm.com');
insert into employee (id, name, birthday, email) values (94, 'Wileen', '2014-01-12', 'wlombardo2l@macromedia.com');
insert into employee (id, name, birthday, email) values (95, 'Gabriel', '2006-04-27', 'ghallmark2m@statcounter.com');
insert into employee (id, name, birthday, email) values (96, 'Babb', '2010-12-19', 'bpride2n@wisc.edu');
insert into employee (id, name, birthday, email) values (97, 'Torre', '2011-10-10', 'tmemory2o@umich.edu');
insert into employee (id, name, birthday, email) values (98, 'Inna', '2018-10-10', 'ilandeg2p@china.com.cn');
insert into employee (id, name, birthday, email) values (99, 'Bernadette', '2014-02-07', 'bmouth2q@wikispaces.com');
insert into employee (id, name, birthday, email) values (100, 'Winthrop', '2021-07-27', 'wchastand2r@cbslocal.com');
```
3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'Ismet',
birthday = '1998-01-01',
email = 'ismet@ismet.com'
WHERE id = 11 ;

UPDATE employee
SET name = 'Hasan',
birthday = '1996-01-01',
email = 'Hasan@Hasan.com'
WHERE id = 1
RETURNING *;

UPDATE employee
SET name = 'Selin',
birthday = '1991-01-01',
email = 'Selin@Selin.com'
WHERE id = 20 ;

UPDATE employee
SET name = 'Ekrem',
birthday = '1991-01-01',
email = 'Ekrem@Ekrem.com'
WHERE id = 30 ;

UPDATE employee
SET name = 'Ahmet',
birthday = '1991-01-01',
email = 'Ahmet@Ahmet.com'
WHERE id = 25 ;
```
4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.*/
```
DELETE FROM employee
WHERE id = 11 ;

DELETE FROM employee
WHERE id = 1
RETURNING *;

DELETE FROM employee
WHERE id = 20 ;

DELETE FROM employee
WHERE id = 30 ;

DELETE FROM employee
WHERE id = 25 ;
```
