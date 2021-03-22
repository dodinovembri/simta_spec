# Student thesis history
```sql
CREATE TABLE student_thesis_history (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
	lecturer_id VARCHAR(36) NULL,
	student_thesis_id VARCHAR(36) NULL,
	college_student_id VARCHAR(36) NULL,
    history_code TINYINT NULL,
    total_sks_now INT NULL,
    total_sks_transkrip INT NULL,
    description VARCHAR(36) NULL,
	PRIMARY KEY (id)
)
```
## Thesis Status
| Code | Name |
| ---- | ---- |
| 1 | KKT File Uploaded |
| 2 | KKT File Rejected |