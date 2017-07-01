## docker-lemp-test

This is a LEMP server on Ubuntu 16.04

The following technologies were used:

- Nginx
- MySQL
- PHP 7.0
- Test database
- Test php application

The query is "select last_name, first_name, gender, birth_date, hire_date  
from employees E where E.birth_date = '1965-02-01' AND E.gender = 'M' AND  
E.hire_date > '1990-01-01' order by last_name, first_name"  

### Run this container
``` bash
# docker run -p 8080:80 hpierce/docker-lemp-test
```

### View results
Open your web browser to http://localhost:8080  

