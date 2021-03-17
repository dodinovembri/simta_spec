# Student thesis
```sql
CREATE TABLE student_thesis (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
	lecturer_id VARCHAR(36) NULL,
	college_student_id VARCHAR(36) NULL,
    total_sks_now INT NULL,
    total_sks_transkrip INT NULL,
    is_kkt_file_set TINYINT NULL,
	PRIMARY KEY (id)
)
```

