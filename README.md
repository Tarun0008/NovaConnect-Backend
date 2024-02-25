**BACKEND SERVER**
https://tb-1.onrender.com/

**TESTING END POINTS**


**TO GET ALL USERS**
https://tb-1.onrender.com/users


**TO GET ALL POSTS**
https://tb-1.onrender.com/postss

**TO SEARCH BY NAME**

https://tb-1.onrender.com/user/:name

**List all posts by particular user name**

https://tb-1.onrender.com/users/:name/posts


**NO SQL DATABASE SO NO REALTIONAL DATABASE**
**USERS ATTRIBUTES**

1. `_id`: A unique identifier for the user.
2. `firstName`: The first name of the user.
3. `lastName`: The last name of the user.
4. `email`: The email address of the user.
5. `password`: The hashed password of the user.
6. `picturePath`: The path or URL to the user's profile picture.
7. `friends`: An array containing information about the user's friends.
8. `location`: The location or city where the user resides.
9. `occupation`: The occupation or job of the user.
10. `viewedProfile`: The ID of the profile that the user has viewed.
11. `impressions`: A numeric value representing impressions or interactions.
12. `createdAt`: The timestamp indicating when the user's account was created.
13. `updatedAt`: The timestamp indicating when the user's account was last updated.
14. `__v`: A version key typically used by MongoDB to track document versions.

**POSTS ATTRIBUTES**


1. `id`: The unique identifier for the post.
2. `userId`: The ID of the user who created the post.
3. `firstName`: The first name of the user who created the post.
4. `lastName`: The last name of the user who created the post.
5. `location`: The location associated with the post.
6. `description`: A description or caption for the post.
7. `picturePath`: The path or URL to the main picture associated with the post.
8. `userPicturePath`: The path or URL to the profile picture of the user who created the post.
9. `likes`: An object containing information about likes received by the post.
10. `comments`: An array containing information about comments made on the post.
11. `createdAt`: The timestamp indicating when the post was created.
12. `updatedAt`: The timestamp indicating when the post was last updated.
13. `__v`: A version key, which might be used by the database to track document versions.

![Uploading Screenshot 2024-02-25 162020.png…]()![Screenshot 2024-02-25 162032](https://github.com/Tarun0008/NovaConnect-Backend/assets/143323486/d70fc443-211f-462e-86d1-2b47f7688155)

![Uploading Screenshot 2024-02-25 162032.png…]()
![Screenshot 2024-02-25 162042](https://github.com/Tarun0008/NovaConnect-Backend/assets/143323486/9245c56a-bba7-4d09-b995-b0f528c78166)
![Screenshot 2024-02-25 162057](https://github.com/Tarun0008/NovaConnect-Backend/assets/143323486/a80c1b55-1297-4b63-a614-6763b6852305)
