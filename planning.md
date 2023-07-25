#### Plan for executing the app


- Figma design
- Database diagram
- Back end setup ( Auth, Database )
- UI ( React ) 

DB - PostgreSQL

Tables:

resources
 id PK AI
 description varchar(255)
 tags ENUM
 created_at
 updated_at

user
 id PK AI
 email varchar(255)
 password varchar(255)
 
