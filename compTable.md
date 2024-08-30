# CompTable draft

```sql echo
CREATE college (
    USE ctcdata;

    CREATE TABLE student (
        student_num INT(6),
        program_code VARCHAR(6),
        id_num INT(13),
        PRIMARY KEY (student_num)
    )
    

    CREATE TABLE user (
        user_name VARCHAR(50),
        user_surname VARCHAR (50),
        dot DATE,
        id_num INT(13)
        physical_address VARCHAR(150), 
        postal_address VARCHAR(150),
        email_address VARCHAR(100), 
        nationality VARCHAR(50), --there would be options for this that the applicant can choose from--
        diabilities BOOLEAN
    )
    CREATE TABLE admin (
        admin_id VARCHAR(7), 
        performance_report 
    )

)