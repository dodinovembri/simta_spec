# Field Of Study
```sql
CREATE TABLE field_of_study (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
	field_of_study_code VARCHAR(36) NOT NULL,
	field_of_study_name VARCHAR(256) NOT NULL,
	description TEXT NULL,
	PRIMARY KEY (id)
)
```