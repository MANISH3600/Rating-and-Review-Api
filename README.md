
Registration: http://127.0.0.1:8000/api/account/register/
header POST pass username email passwrord password2 as body

Login: http://127.0.0.1:8000/api/account/login/
Header POST pass username and password as body 

Logout: http://127.0.0.1:8000/api/account/logout/



Stream Platforms

Create Element & Access List: http://127.0.0.1:8000/api/watch/stream/
Access, Update & Destroy Individual Element: http://127.0.0.1:8000/api/watch/stream/<int:streamplatform_id>/


Watch List

Create & Access List: http://127.0.0.1:8000/api/watch/
Access, Update & Destroy Individual Element: http://127.0.0.1:8000/api/watch/<int:movie_id>/



Reviews

Create Review For Specific Movie: http://127.0.0.1:8000/api/watch/<int:movie_id>/reviews/create/
eg : curl -X POST http://127.0.0.1:8000/api/watch/1/reviews/create/ \
-H "Content-Type: application/json" \
-H "Authorization: Token d9a3884730abb7c4e3821a6f961ba76717e937c2" \
-d '{"rating": 4, "description": "Great movie!"}'


List Of All Reviews For Specific Movie: http://127.0.0.1:8000/api/watch/<int:movie_id>/reviews/
Access, Update & Destroy Individual Review: http://127.0.0.1:8000/api/watch/reviews/<int:review_id>/


User Review

Access All Reviews For Specific User: http://127.0.0.1:8000/api/watch/user-reviews/?username=example
