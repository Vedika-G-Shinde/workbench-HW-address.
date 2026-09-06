# workbench-HW-address.
create table address( 
 address_id int, house_no varchar(20),
 city varchar(10), state varchar(40), 
 pincode varchar(30), country varchar(45));
 INSERT INTO address VALUES(
(101, 'FC road', 'Pune', 'Maharashtra', '411004', 'India'),
(102, 'MG road', 'Pune', 'Maharashtra', '411002', 'India'),
(103, 'JM road', 'Pune', 'Maharashtra', '411005', 'India'),
(104, 'Karve road', 'Pune', 'Maharashtra', '411045', 'India'),
(105, 'Baner road', 'Pune', 'Maharashtra', '411038', 'India'),
(106, 'Hinjewadi road', 'Pune', 'Maharashtra', '411057', 'India'),
(107, 'Wakad road', 'Pune', 'Maharashtra', '411048', 'India'),
(108, 'Viman nagar road', 'Pune', 'Maharashtra', '411014', 'India'),
(109, 'Kothrud road', 'Pune', 'Maharashtra', '411033', 'India'),
(110, 'Sinhagad road', 'Pune', 'Maharashtra', '411030', 'India'));
select* from address;
select*from address
where pincode='411038';
