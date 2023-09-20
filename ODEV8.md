## Q1

``` sql

CREATE  TABLE employee (
id INTEGER,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100)
);

```

## Q2

``` sql

insert into employee (name, email, birthday) values ('Hilda', 'hjennison0@tinypic.com', '2021-06-09');
insert into employee (name, email, birthday) values ('Elissa', 'emaccolm1@hibu.com', '2021-06-18');
insert into employee (name, email, birthday) values ('Frederica', 'fparrish2@springer.com', '2014-09-05');
insert into employee (name, email, birthday) values ('Christopher', 'chesey3@flavors.me', '2015-08-02');
insert into employee (name, email, birthday) values ('Arleyne', 'aworms4@mysql.com', '2022-04-26');
insert into employee (name, email, birthday) values ('Britt', 'blocard5@devhub.com', '2015-06-14');
insert into employee (name, email, birthday) values ('Miranda', 'mbeedom6@redcross.org', '2007-03-20');
insert into employee (name, email, birthday) values ('Lisette', 'lmullaney7@eventbrite.com', '2022-08-24');
insert into employee (name, email, birthday) values ('Amalita', 'awinks8@nifty.com', '2011-11-20');
insert into employee (name, email, birthday) values ('Korry', 'kdinis9@netscape.com', '2003-11-15');
insert into employee (name, email, birthday) values ('Torre', 'tbeddowsa@flickr.com', '2001-07-19');
insert into employee (name, email, birthday) values ('Eustace', 'eaudenb@forbes.com', '2005-01-25');
insert into employee (name, email, birthday) values ('Adrienne', 'agewerc@hud.gov', '2016-12-18');
insert into employee (name, email, birthday) values ('Kennith', 'kadaod@smugmug.com', '2012-01-26');
insert into employee (name, email, birthday) values ('Sioux', 'svonderemptene@nyu.edu', '2013-07-19');
insert into employee (name, email, birthday) values ('Ceil', 'cdavydochkinf@multiply.com', '2017-07-03');
insert into employee (name, email, birthday) values ('Binnie', 'bleindeckerg@wikimedia.org', '2006-01-01');
insert into employee (name, email, birthday) values ('Nissie', 'ntrulockh@google.pl', '2002-03-13');
insert into employee (name, email, birthday) values ('Ashly', 'agradlyi@behance.net', '2005-12-02');
insert into employee (name, email, birthday) values ('Bennett', 'bportchmouthj@com.com', '2012-02-07');
insert into employee (name, email, birthday) values ('Jeffie', 'jwegenerk@a8.net', '2008-01-11');
insert into employee (name, email, birthday) values ('Quintilla', 'qniblol@joomla.org', '2021-09-20');
insert into employee (name, email, birthday) values ('Ric', 'rramalhetem@netscape.com', '2020-11-03');
insert into employee (name, email, birthday) values ('Yvor', 'yduerdenn@weather.com', '2018-05-19');
insert into employee (name, email, birthday) values ('Bryan', 'bwardo@walmart.com', '2018-06-01');
insert into employee (name, email, birthday) values ('Rori', 'rdunkp@etsy.com', '2018-03-23');
insert into employee (name, email, birthday) values ('Robbie', 'rscogganq@marketwatch.com', '2006-12-17');
insert into employee (name, email, birthday) values ('Pancho', 'pflockhartr@tripadvisor.com', '2007-09-01');
insert into employee (name, email, birthday) values ('Rennie', 'rbalmes@netscape.com', '2001-02-20');
insert into employee (name, email, birthday) values ('Prudence', 'plippiellot@bigcartel.com', '2006-11-13');
insert into employee (name, email, birthday) values ('Tiffy', 'twaslingu@gizmodo.com', '2008-01-25');
insert into employee (name, email, birthday) values ('Estrellita', 'ecorraganv@google.fr', '2020-10-09');
insert into employee (name, email, birthday) values ('Gilles', 'gsivillsw@examiner.com', '2012-06-04');
insert into employee (name, email, birthday) values ('Kathlin', 'klauksx@networkadvertising.org', '2019-03-22');
insert into employee (name, email, birthday) values ('Monte', 'mmenichelliy@tmall.com', '2014-12-09');
insert into employee (name, email, birthday) values ('Andrei', 'akesbyz@usgs.gov', '2023-06-24');
insert into employee (name, email, birthday) values ('Glenda', 'gayton10@wiley.com', '2007-07-12');
insert into employee (name, email, birthday) values ('Angeli', 'aduxbury11@tuttocitta.it', '2008-11-17');
insert into employee (name, email, birthday) values ('Leicester', 'lbellelli12@patch.com', '2012-04-24');
insert into employee (name, email, birthday) values ('Dyanna', 'dmerriton13@tripadvisor.com', '2001-03-21');
insert into employee (name, email, birthday) values ('Wrennie', 'wgrinham14@sciencedaily.com', '2003-05-11');
insert into employee (name, email, birthday) values ('Neill', 'nconaghy15@home.pl', '2017-07-03');
insert into employee (name, email, birthday) values ('Analise', 'adella16@dion.ne.jp', '2004-03-25');
insert into employee (name, email, birthday) values ('Christean', 'cgratrex17@list-manage.com', '2004-07-12');
insert into employee (name, email, birthday) values ('Danya', 'dbarwood18@myspace.com', '2017-10-19');
insert into employee (name, email, birthday) values ('Raf', 'rtabbernor19@parallels.com', '2009-11-20');
insert into employee (name, email, birthday) values ('Rem', 'rridgley1a@washington.edu', '2006-12-29');
insert into employee (name, email, birthday) values ('Barny', 'bchilton1b@java.com', '2002-09-22');
insert into employee (name, email, birthday) values ('Boyd', 'bhedger1c@buzzfeed.com', '2019-12-10');
insert into employee (name, email, birthday) values ('Briant', 'bsculpher1d@fda.gov', '2004-08-08');

```

## Q3

``` sql

UPDATE employee
SET name = 'Cansu'
Where id = 10;



UPDATE employee
SET birthday = '1992-08-10'
Where name  = 'Kennith';



UPDATE employee
SET email = 'xxxx@yyyy.com'
Where name LIKE 'B%';



UPDATE employee
SET email = 'xxxx@yyyy.com',
 birthday = '1900-01-01'
WHERE name LIKE 'A%e';



UPDATE employee
SET email = 'aaa@ccc.com',
 birthday = '1000-01-01',
 name = 'mahmut'
WHERE id > 20 AND id < 32;

```

## Q4

``` sql

DELETE FROM  employee
Where id = 10;



DELETE FROM  employee
Where name  = 'Kennith';



DELETE FROM  employee
Where name LIKE 'B%';



DELETE FROM  employee
WHERE name LIKE 'A%e';



DELETE FROM  employee
WHERE id > 20 AND id < 32;
```
