# CodeIgniter 3 + HMVC + Ion Auth Base

Base project structure and files for CodeIgniter 3 with HMVC extensions and Ion Auth library

## Getting Started

Just follow the instructions below to run this project on your machine.

### Requirements

#### Development environment

* PHP version 5.6 or newer recommended. Older PHP releases might not be compatible.

* MySQL version 5.1 or newer.

### Installation

Installation steps:

* Clone this repository to your webroot

example: 
```
$ cd /path/to/server/root

$ git clone https://github.com/msazzuhair/codeigniter-hmvc-ion_auth.git my-project
```

* Run your web server (Apache) and MySql.

* Open your web browser and access:
>```http://localhost/my-project```

#### Database Setup & Migration

* Create a new database for the project

* Modify the database configuration inside ```database.php``` based on your database configurations.
Example:
```php
    ...
	'hostname' => 'localhost',
	'username' => 'username',
	'password' => 'password',
	'database' => 'my-project',
    'dbdriver' => 'mysqli',
    ...
```

* For migrating database structure, go to ```http://localhost/my-project/migration/migrate```. The database will be updated automatically

#### Ion Auth Default Login
Username: admin@admin.com password: password 

## Built Using

* [Codeigniter 3](https://github.com/bcit-ci/codeigniter)
* [Codeigniter Modular Extensions - HMVC](https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc)
* [Ion Auth](https://github.com/benedmunds/CodeIgniter-Ion-Auth)

## Authors

* **Muhammad Azzuhair** - [@msazzuhair](https://github.com/msazzuhair)

## License

This project uses MIT License - See [LICENSE](LICENSE) for more information.