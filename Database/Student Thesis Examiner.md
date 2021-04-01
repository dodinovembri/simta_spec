# Student thesis examiner
```sql
CREATE TABLE student_thesis_examiner (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
	college_student_id VARCHAR(36) NULL,
	lecturer_id VARCHAR(36) NULL,
    lecture_type INT NULL,
	description TEXT NULL,
	PRIMARY KEY (id)
)
```
## Lecturer Type
| Code | Name |
| ---- | ---- |
| 1 | Examiner Lead |
| 2 | Examiner |