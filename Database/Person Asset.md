# Person Asset
```sql
CREATE TABLE person_asset (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	modified_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	modifier_id VARCHAR(36) NULL,
    person_id VARCHAR(36) NULL,
    multimedie_description_id VARCHAR(36) NULL,
	PRIMARY KEY (id)
)
```