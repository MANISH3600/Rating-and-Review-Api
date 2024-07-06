<b>1. Accounts</b>
<ul>
    <li>
        Registration: 
        <a href="http://127.0.0.1:8000/api/account/register/">http://127.0.0.1:8000/api/account/register/</a>
        <br>
        <i>Pass the following JSON body:</i>
        <pre>
{
    "username": "your_username",
    "email": "your_email@example.com",
    "password": "your_password",
    "password2": "your_password"
}
        </pre>
    </li>
    <li>
        Login: 
        <a href="http://127.0.0.1:8000/api/account/login/">http://127.0.0.1:8000/api/account/login/</a>
        <br>
        <i>Pass the following JSON body:</i>
        <pre>
{
    "email": "your_email@example.com",
    "password": "your_password"
}
        </pre>
    </li>
    <li>
        Logout: 
        <a href="http://127.0.0.1:8000/api/account/logout/">http://127.0.0.1:8000/api/account/logout/</a>
    </li>
</ul>
<br>

<b>2. Stream Platforms</b>
<ul>
    <li>
        Create Element & Access List: 
        <a href="http://127.0.0.1:8000/api/watch/stream/">http://127.0.0.1:8000/api/watch/stream/</a>
    </li>
    <li>
        Access, Update & Destroy Individual Element: 
        <a href="http://127.0.0.1:8000/api/watch/stream/&lt;int:streamplatform_id&gt;">http://127.0.0.1:8000/api/watch/stream/&lt;int:streamplatform_id&gt;/</a>
    </li>
</ul>
<br>

<b>3. Watch List</b>
<ul>
    <li>
        Create & Access List: 
        <a href="http://127.0.0.1:8000/api/watch/">http://127.0.0.1:8000/api/watch/</a>
    </li>
    <li>
        Access, Update & Destroy Individual Element: 
        <a href="http://127.0.0.1:8000/api/watch/&lt;int:movie_id&gt;">http://127.0.0.1:8000/api/watch/&lt;int:movie_id&gt;/</a>
    </li>
</ul>
<br>

<b>4. Reviews</b>
<ul>
    <li>
        Create Review For Specific Movie: 
        <a href="http://127.0.0.1:8000/api/watch/&lt;int:movie_id&gt;/reviews/create/">http://127.0.0.1:8000/api/watch/&lt;int:movie_id&gt;/reviews/create/</a>
    </li>
    <li>
        List Of
