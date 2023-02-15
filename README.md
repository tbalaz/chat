# chat
@page
@model LoginModel
@{
    ViewData["Title"] = "Login";
}
<h2>@ViewData["Title"]</h2>
<form method="post">
    <div>
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" required />
    </div>
    <div>
        <label for="password">Password:</label>
        <input type="password" name="password" id="password" required />
    </div>
    <button type="submit">Login</button>
</form>
