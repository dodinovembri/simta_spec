# Users
A unique user in the system.
```sql
CREATE TABLE users (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
    person_id VARCHAR(36) NULL,
	username VARCHAR(256) NULL,
	password VARCHAR(256) NOT NULL,
	remember_token VARCHAR(256) NULL,
    user_type_code TINYINT NOT NULL,
	PRIMARY KEY (id)
)
```
## Transaction Type
| User Type Code | Name |
| ---- | ---- |
| 1 | Administrator |
| 2 | Pengelola |
| 3 | Dosen |
| 4 | Mahasiswa |