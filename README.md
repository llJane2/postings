--------------------------------------------
 # models
--------------------------------------------
1. Users
    - Relationships
        has_many : postings
        has_many : comments
    - Elements
        emails / password
2. Postings
    - Relationships
        belongs_to : User
        has_many : comments
    - Elements
        title, body, user_id
3. Comments
    - Relationships
        belongs_to : Users
        belongs_to : Postings
    - Elements
        content, user_id, posting_id
        
--------------------------------------------
# controllers / Views
posting controller
Comment controller

User => divise gemfile
--------------------------------------------

# CSS / JS : Bootstrap CDN
