What You're Aiming For
You’ve received a broken web component: a pricing card layout with layout issues and unresponsive buttons. Your task is to fix, refactor, and prepare it for reuse using AI.


Instructions
Copy this broken snippet into Cursor:

 

<!DOCTYPE html>
<html>
<head>
<style>
.pricing {
width: 300px;
margin: auto;
background-color: #fff;
box-shdow: 0 0 10px #ccc;
padding: 10px;
text-align: left;
}

.title {
font-size: 22px;
font-weight: bold;
}

.price {
font-size: 18px;
color: green;
}

.features {
list-style: none;
padding-left: 0;
}

.features li {
padding: 4px;
border-bottom: 1px solid #eee;
}

.btn {
background: blue;
color: white;
padding: 10px 20px;
border: none;
margin-top: 10px;
}

.btn:hover {
background: darkblue;
}
</style>
</head>
<body>

<div class="pricing">
<h2 class="title">Basic Plan<h2>
<p class="price">$9.99 /month</p>

<ul class="features">
<li>1 GB Storage</li>
<li>Basic Support</li>
<li>All Core Features</li>
</ul>

<button class="btn">Start Trial</button>
</div>

</body>
</html>

 

Use Cursor AI chat to identify and fix layout bugs.

 
Refactor it into a reusable component (e.g., Card(title, price, features)).

 
Paste the updated code into a new file and test it.

 
Submit before and after code, and your AI prompt used.
