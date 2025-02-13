# Building a Course Platform

## Overview
What we are building

- Courses:
    - Title
    - Description
    - Thumbnail/Image
    - Access:
       - Anyone
       - Email required
       - Purchase required
       - User required(n/a)
    - Status:
       - Published
       - Coming soon
       - Draft
    - Lessons  
        - Title
        - Description
        - Video
        - Status: published,coming soon,Draft 


    - Email verification for short-lived access
        - Views:
            - collect user email
            - verify user email
                 - Activate session
        - Models:
            - Email
            - EmailVerificationToken             