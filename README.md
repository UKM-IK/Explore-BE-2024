# Explore-BE-2024

# How to Run Project

clone project :

```properties
git clone https://github.com/UKM-IK/Explore-FE-2024.git
```

install dependencies :

```properties
npm install
```

run project

```properties
npm run dev
```

# Exploring Project

**Brief :** <br />
As a Front End Developer you are required to create a blog, you don't need to create a Back End Developer but focus on the Front End Developer.

1. Please create a single page application using ReactJS
2. Please use data from public api https://gorest.co.in/ to generate a blog post.
3. The API's need API Key to access some endpoint. use this API Key : <br />

```javascript
API_KEY=4d932797eb7eba8643df6e4e837bd412a30a4478e0f5fa04f03de9f47967ae27
```

4. It’s up to you how to visualize the data
5. example project : https://blog-q4cvx78m3-yandiaan.vercel.app

## Dian

_Feature to develop :_ **CRUD (Create Read Update Delete) Posts**

Endpoint :
https://gorest.co.in/public/v2/posts

Example Request for __POST/PUT/PATCH__:

```json
{
    "title": "ini judul blog",
    "body": "ini isi dari postingan blog"
},
```

Acceptance Criteria :

- User can view list of posts
- user can view detail of posts
- user can create new post
- user can update post
- user can delete post

## Ridhwan

_Feature to develop :_ **CRUD (Create Read Update Delete) Comments**

Endpoint :
https://gorest.co.in/public/v2/posts/{id_posts}/comments

Example Request for __POST/PUT/PATCH__
```json
{
    "name": "Ridhwan Cahyadi",
    "email": "ridhwancahyadi@utdi.ac.id",
    "body": "Postingannya keren sekali."
},
```

Acceptance Criteria :

- User can view list of comments in post page
- user can create new comment
- user can update comment
- user can delete comment

## Sufardi

_Feature to develop :_ **CRUD (Create Read Update Delete) Users**

Endpoint :
https://gorest.co.in/public/v2/users

Example Request for __POST/PUT/PATCH__
```json
{
    "name": "Sufardi Madoa",
    "email": "sufardi@utdi.ac.id",
    "gender": "male",
    "status": "active"
},
```

Acceptance Criteria :

- User can view list of users
- user can view detail of users
- user can create new users
- user can update users
- user can delete users

## Lintang

_Feature to develop :_ **CRUD (Create Read Update Delete) Todo Lists**

Endpoint :
https://gorest.co.in/public/v2/todos

Example Request for __POST/PUT/PATCH__
```json
{
    "title": "Makan Pagi",
    "due_on": "2024-02-17T00:00:00.000+05:30",
    "status": "pending"
},
```

Acceptance Criteria :

- User can view list of todo
- user can view detail of todo
- user can create new todo
- user can update todo
- user can delete todo
