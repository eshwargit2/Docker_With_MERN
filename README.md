<h1>Simple MERN Project Using Docker</h1>

<img src="https://img.icons8.com/?size=100&id=cdYUlRaag9G9&format=png&color=000000" alt="Docker Img">

<hr/>

<div class={{display:'flex',flexDirection: 'row',marginTop:'50px',justifyContent:'center'}}>

<img width="48" height="48" src="https://img.icons8.com/color/48/mongodb.png" alt="mongodb"/>

<img width="48" height="48" src="https://img.icons8.com/officel/80/express-js.png" alt="express-js"/>

<img width="48" height="48" src="https://img.icons8.com/color/48/react-native.png" alt="react-native"/>

<img width="50" height="50" src="https://img.icons8.com/fluency/50/node-js.png" alt="node-js"/>
</div>

<h1>🚀 Dockerized MERN Stack App (Frontend + Backend Separate Images)</h1>

<p>This project contains a MERN (MongoDB, Express.js, React.js, Node.js) Stack app with Dockerized <strong>frontend</strong> and <strong>backend</strong> components.</p>

<h2>📦 Docker Images</h2>

<p>Both images are hosted on Docker Hub:</p>

<ul>
  <li><strong>Frontend Image:</strong> <code>eshwarelectrotech/mern-frontend</code></li>
  <li><strong>Backend Image:</strong> <code>eshwarelectrotech/mern-backend</code></li>
</ul>

<h2>🔽 Pull Docker Images</h2>

<pre>
<code>docker pull eshwarelectrotech/mern-frontend
docker pull eshwarelectrotech/mern-backend</code>
</pre>

<h2>▶️ Run Docker Containers</h2>

<h3>🖥️ Run Backend</h3>

<pre>
<code>docker run -d -p 5000:5000 --name backend eshwarelectrotech/mern-backend</code>
</pre>

<p>Now your backend server will run on:</p>
<pre><code>http://localhost:5000</code></pre>

<h3>🌐 Run Frontend</h3>

<pre>
<code>docker run -d -p 3000:3000 --name frontend eshwarelectrotech/mern-frontend</code>
</pre>

<p>Now your frontend app will be available at:</p>
<pre><code>http://localhost:3000</code></pre>

<h2>⚙️ Notes</h2>
<ul>
  <li>Make sure your backend and frontend are properly configured to communicate (CORS, API endpoints).</li>
  <li>If you're using MongoDB, make sure it's either running locally or via Docker volume/container.</li>
</ul>

<h2>📁 Source Code</h2>

<p>GitHub Repository: 
<a href="https://github.com/eshwargit2/Docker_With_MERN" target="_blank">
https://github.com/eshwargit2/Docker_With_MERN
</a>
</p>

<hr>

<p>✅ Built with ❤️ by Eshwar Electro Tech</p>
