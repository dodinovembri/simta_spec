# Proposal seminar requirement
```sql
CREATE TABLE proposal_seminar_requirement (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
	proposal_seminar_requirement_code VARCHAR(36) NOT NULL,
	proposal_seminar_requirement_name VARCHAR(256) NOT NULL,
	description TEXT NULL,
	PRIMARY KEY (id)
)
```