# multimedia description
```sql
CREATE TABLE multimedia_description (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
    information_type_code VARCHAR(36) NULL,
    file_name VARCHAR(256) NULL,
    original_file_name VARCHAR(256) NULL,
    file_size INT NULL,
    url VARCHAR(256) NULL,
    description TEXT NULL,
	PRIMARY KEY (id)
)
```