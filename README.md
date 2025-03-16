<h1 align="center">📖 Blog Application</h1>

<h3>🌟 Overview</h3>
<p>
This Blog Application is a full-featured platform where users can create and manage blog posts, categorize them, and interact through comments. It implements robust security with JWT authentication and provides role-specific access for admins and users.
</p>

<hr>

<h3>🚀 Features</h3>
<ul>
  <li>👤 <b>User Management:</b> Users can register, log in, and manage their accounts securely.</li>
  <li>✍️ <b>Post Management:</b> Create, update, delete, and view posts with category assignments.</li>
  <li>💬 <b>Comment System:</b> Add, update, delete comments, and view all comments on a post.</li>
  <li>🔍 <b>Advanced Filtering:</b> Implemented pagination, searching, and sorting for better user experience.</li>
  <li>🔐 <b>Role-Based APIs:</b> Admin and normal users have separate API access levels.</li>
  <li>🛡️ <b>Secure Authentication:</b> JWT authentication and Spring Security integration.</li>
</ul>

<hr>

<h3>🛠 Tech Stack</h3>
<ul>
  <li>☕ <b>Backend:</b> Java, Spring Boot, Spring Security, Hibernate</li>
  <li>🗄️ <b>Database:</b> MySQL</li>
  <li>🧪 <b>API Testing:</b> Postman</li>
  <li>🔗 <b>Version Control:</b> GitHub</li>
</ul>

<hr>

<h3>⚙️ Installation & Setup</h3>
<ol>
  <li>📥 <b>Clone the repository:</b>
    <pre><code>git clone https://github.com/your-username/blog-application.git
cd blog-application</code></pre>
  </li>
  <li>🛠 <b>Configure MySQL Database:</b>
    <p>Update <code>application.properties</code> with your MySQL credentials.</p>
  </li>
  <li>🏗 <b>Build & Run the Project:</b>
    <pre><code>mvn clean install
mvn spring-boot:run</code></pre>
  </li>
  <li>📝 <b>Test APIs</b> using Postman or any API client.</li>
</ol>

<hr>

<h3>🔐 Authentication & Authorization</h3>
<ul>
  <li>🔑 <b>JWT-based authentication</b> for secure API access.</li>
  <li>🏛 <b>Admin has access</b> to all user and post management actions.</li>
  <li>✏️ <b>Normal users can create, edit, and manage</b> their own posts.</li>
</ul>

<hr>

<h3>📂 API Endpoints</h3>

<h4>🔹 User APIs</h4>
<ul>
  <li><code>POST /api/auth/register</code> - 📝 Register a new user</li>
  <li><code>POST /api/auth/login</code> - 🔑 Authenticate and get a token</li>
</ul>

<h4>🔹 Post APIs</h4>
<ul>
  <li><code>POST /api/posts</code> - ✍️ Create a new post</li>
  <li><code>GET /api/posts</code> - 📜 Retrieve all posts with pagination & sorting</li>
  <li><code>GET /api/posts/{id}</code> - 🔍 Get post by ID</li>
  <li><code>PUT /api/posts/{id}</code> - ✏️ Update post (Owner/Admin only)</li>
  <li><code>DELETE /api/posts/{id}</code> - 🗑 Delete post (Owner/Admin only)</li>
</ul>

<h4>🔹 Comment APIs</h4>
<ul>
  <li><code>POST /api/posts/{id}/comments</code> - 💬 Add a comment</li>
  <li><code>PUT /api/comments/{id}</code> - ✏️ Edit a comment</li>
  <li><code>DELETE /api/comments/{id}</code> - 🗑 Delete a comment</li>
</ul>

<hr>

<h3>🎯 Future Enhancements</h3>
<ul>
  <li>🖼 Add support for image uploads in posts.</li>
  <li>📩 Implement email notifications for post interactions.</li>
  <li>🖥 Enhance UI with a frontend framework like React.</li>
</ul>

<hr>

<h3>🤝 Contributing</h3>
<p>Feel free to submit pull requests or issues to improve this project! 🚀</p>

<hr>

<h3>📜 License</h3>
<p>This project is licensed under the MIT License.</p>

