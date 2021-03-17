# Business Entity Document
A Business Entity Document.
```sql
CREATE TABLE business_entity_document (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
    business_entity_id VARCHAR(36) NOT NULL,
    document_id VARCHAR(36) NOT NULL,
	PRIMARY KEY (id)
)
```