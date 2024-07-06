
<b>1. Accounts</b>
<ul>
    <li>Registration: http://127.0.0.1:8000/api/account/register/</li> 
        <l1>Pass (Username ,Email <Password,Password2} as Body </l1>
    <li>Login: http://127.0.0.1:8000/api/account/login/</li>
    <li>Logout: http://127.0.0.1:8000/api/account/logout/</li>
</ul>
<br>

<b>2. Stream Platforms</b>
<ul>
    <li>Create Element & Access List: http://127.0.0.1:8000/api/watch/stream/</li>
    <li>Access, Update & Destroy Individual Element: http://127.0.0.1:8000/api/watch/stream/&lt;int:streamplatform_id&gt;/</li>

</ul>
<br>

<b>3. Watch List</b>
<ul>
    <li>Create & Access List: http://127.0.0.1:8000/api/watch/</li>
    <li>Access, Update & Destroy Individual Element: http://127.0.0.1:8000/api/watch/&lt;int:movie_id&gt;/</li>
</ul>
<br>

<b>4. Reviews</b>
<ul>
    <li>Create Review For Specific Movie: http://127.0.0.1:8000/api/watch/&lt;int:movie_id&gt;/reviews/create/</li>
    <li>List Of All Reviews For Specific Movie: http://127.0.0.1:8000/api/watch/&lt;int:movie_id&gt;/reviews/</li>
    <li>Access, Update & Destroy Individual Review: http://127.0.0.1:8000/api/watch/reviews/&lt;int:review_id&gt;/</li>
</ul>
<br>

<b>5. User Review</b>
<ul>
    <li>Access All Reviews For Specific User: http://127.0.0.1:8000/api/watch/user-reviews/?username=example</li>
</ul>
<br>
