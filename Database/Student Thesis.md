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
	lecturer_id VARCHAR(36) NOT NULL,
	college_student_id VARCHAR(36) NOT NULL,
	PRIMARY KEY (id)
)
```

