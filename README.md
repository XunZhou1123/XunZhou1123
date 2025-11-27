## Hi there 👋

<!--
**XunZhou1123/XunZhou1123** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
/* style.css — common styles for GoodView site */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  color: #333;
}
header {
  background-color: #222;
  color: #fff;
  padding: 1rem 2rem;
}
header h1 {
  margin: 0;
  font-size: 1.8rem;
}
nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}
nav li {
  margin-right: 1.5rem;
}
nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}
nav a:hover {
  text-decoration: underline;
}
main {
  padding: 2rem;
}
.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.5rem;
}
.product-item {
  border: 1px solid #ddd;
  padding: 1rem;
  border-radius: 5px;
}
footer {
  background-color: #f4f4f4;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}

