#### Plan for executing the app


- Figma design
- Database diagram
- Back end setup ( Auth, Database )
- UI ( React ) 

DB - PostgreSQL

Tables:

resources
 id PK AI
 user_id FOREIGN KEY - user.id
 description varchar(255)
 tags ENUM[]
 created_at
 updated_at

user
 id PK AI
 username varchar(255)
 email varchar(255)
 password varchar(255)
 created_at timestamp
 updated_at timestamp

company
 id PK AI 
 name varchar(255)
 website_url varchar(255)
 is_startup bool

post
 id PK AI
 text_content varchar(255)
 image_url varchar(255)
 hypes int
 likes int
 tags ENUM[]
 created_at timestamp
 updated_at timestamp


 
Tech considerations:
- API could maybe be built in .NET just to practice .NET skills