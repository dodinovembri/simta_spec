# Majors
```sql
CREATE TABLE majors (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
	majors_code VARCHAR(36) NOT NULL,
	majors_name VARCHAR(256) NOT NULL,
	description TEXT NULL,
	PRIMARY KEY (id)
)
```