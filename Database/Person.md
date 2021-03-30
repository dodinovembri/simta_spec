# Person
A person.
```sql
CREATE TABLE person (
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	updater_id VARCHAR(36) NULL,
    nim VARCHAR(40) NULL,
    nip VARCHAR(40) NULL,
	given_name VARCHAR(128) NULL,
	middle_name VARCHAR(128) NULL,
	surname VARCHAR(128) NULL,
	business_entity_id VARCHAR(36) NULL,
	birth_date DATETIME NULL,
	gender_code INT NULL,
    person_type_code INT NULL,
    academic_lecturer_nip VARCHAR(40) NULL,
    year_of_education_id VARCHAR(36) NULL,
    majors_id VARCHAR(36) NULL,
	PRIMARY KEY (id)
)
```