# adwerx application
## December 10, 2021

### Assignment 1

1. 
SELECT * FROM users
WHERE email = “bob@acmecorp.com”

2. 
SELECT * FROM users u
JOIN partners p ON u.partner_id = p.id
WHERE p.name = “Acme Corporation”

Extra Credit:
Note - it does not seem possible to find this given the columns in database schemas. The closest comparison would be to find the number of users who last signed in on 02/01/2018.

SELECT Count(*) FROM users
WHERE last_sign_in_at = “02/01/2018”


### Assignment 2
1.
{
    "id": "e78f9fdc",
    "email": "jameslaugerman@gmail.com",
    "password": "DesMoines"
}

2.
Tierra Brakus

3. 

const fullNames = contacts.map((a) => a.first_name + " " + a.last_name);
console.log(fullNames);


### Assignment 3
see html file in repository
