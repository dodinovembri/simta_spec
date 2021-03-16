# Year of education
```sql
CREATE TABLE year_of_education (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
	year_of_education_code VARCHAR(36) NOT NULL,
	year_of_education_name VARCHAR(256) NOT NULL,
	description TEXT NULL,
	PRIMARY KEY (id)
)
```