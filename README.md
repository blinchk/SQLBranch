1)
CREATE TABLE users(
	ID int not null PRIMARY KEY,
        phonenumber int,
	admin varchar(50),
	pasword varchar(50)
)

2)
INSERT INTO users(admin, pasword)
VALUES ('admin', 'pasik')

3)
DROP TABLE users
