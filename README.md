<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport"

content="width=device-width,

initial-scale=1.0">

<title>Simple Blog</title>

<link rel="stylesheet"

href="styles.css">

</head>

<body>

<h1>My Blog</h1>

<div class="post-form">

<h2>Create a New Post</h2>

<textarea id="postContent"

placeholder="Write your post

here..."></textarea>

<button

onclick="addPost()">Post</button>

</div>

<div id="posts">

<h2>Posts</h2>

<!-- Posts will be

dynamically added here-->

</div>

<script src="script.js"></

script>

</body>

</html>
