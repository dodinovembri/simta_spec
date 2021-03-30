# Person Asset
```sql
CREATE TABLE person_asset (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
    person_id VARCHAR(36) NULL,
    information_type_code VARCHAR(36) NULL,
    file_name VARCHAR(256) NULL,
    original_file_name VARCHAR(256) NULL,
    file_size INT NULL,
    url VARCHAR(256) NULL,
    description TEXT NULL,
	PRIMARY KEY (id)
)
```
## Information Type Code
| Code | Name |
| ---- | ---- |
| 1 | KRS File |
| 2 | KP File |
| 3 | Transkrip Nilai |
| 4 | Consultation File |
| 5 | Consultation File for Extend Proposal Seminar |
