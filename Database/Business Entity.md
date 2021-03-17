# Business Entity
A Business Entity.
```sql
CREATE TABLE business_entity (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
	PRIMARY KEY (id)
)
```