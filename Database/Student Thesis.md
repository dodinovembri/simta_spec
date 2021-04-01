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
    thesis_status_code TINYINT NULL,
    total_sks_now INT NULL,
    total_sks_transkrip INT NULL,
    is_kkt_file_set TINYINT NULL,
    thesis_topic_id VARCHAR(36) NULL,
    title_of_thesis TEXT NULL,
    date_agree DATE NULL,
	PRIMARY KEY (id)
)
```
## Thesis Status
| Code | Name |
| ---- | ---- |
| 1 | KKT File Uploaded |
| 2 | KKT File Rejected |
| 4 | KKT File Accepted|
| 5 | Submission of Topic |
| 6 | Topic Accepted |
| 7 | Topic Rejected |
| 8 | Extend Proposal Seminar Uploaded |
| 9 | Extend Proposal Seminar Uploaded Accepted |
| 10 | Extend Proposal Seminar Uploaded Rejected |
| 11 | Register for Proposal Seminar |
| 12 | Proposal Seminar Requirement Rejected |
| 13 | Proposal Seminar Requirement Accepted |
| 14 | Examiner already set |