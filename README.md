

<h1>eMart Microservices Architecture</h1>

<p>
<b>eMart</b> is a <strong>microservices-based e-commerce platform</strong>, designed with modular, scalable, and containerized services. Inspired by enterprise platforms like Amazon and Flipkart, it demonstrates <strong>cloud-native architecture principles</strong> and <strong>service isolation</strong>.
</p>

<h2>Architecture Overview</h2>

<ul>
    <li><strong>API Gateway (Nginx):</strong> Entry point for client requests. Implements <strong>reverse proxy, load balancing, routing</strong>, and request management across services.</li>
    <li><strong>Front-End (Angular):</strong> Single-page application interacting via REST APIs with the API gateway.</li>
</ul>

<h2>Backend Microservices</h2>

<ul>
    <li><strong>Mart API (Node.js):</strong> Manages <strong>product catalog, inventory, and user data</strong>. Connects to <strong>MongoDB</strong> for <strong>document-oriented, schema-flexible storage</strong>.</li>
    <li><strong>Books API (Java/Spring Boot):</strong> Handles <strong>book listings, transactions, and metadata</strong>. Connects to <strong>MySQL</strong> for <strong>relational, ACID-compliant storage</strong> with <strong>structured queries</strong>.</li>
</ul>

<h2>Containerization & Deployment</h2>

<ul>
    <li>All components deployed as <strong>Docker containers</strong>, enabling <strong>service isolation</strong> and <strong>scalable deployments</strong>.</li>
    <li>Supports <strong>polyglot microservices</strong> architecture, allowing multiple programming languages and databases within the same ecosystem.</li>
</ul>

<h2>Screenshots</h2>

<p>Below are examples of the Docker Compose configuration and Dockerfiles used to build and deploy the eMart microservices:</p>

<ul>
    <li><strong>docker-compose.yml (First Half)</strong></li>
    <img width="297" height="762" alt="Screenshot 2026-03-03 143050" src="https://github.com/user-attachments/assets/715776fc-b818-4457-9f35-5176512d47ed" />
    <li><strong>docker-compose.yml (Second Half)</strong></li>
    <img width="605" height="603" alt="Screenshot 2026-03-03 143221" src="https://github.com/user-attachments/assets/a05a4653-27ed-4814-bcb9-4586e600661c" />
    <li><strong>Dockerfile.yml (FrontEnd Angular Dockerfile)</strong></li>
    <img width="799" height="359" alt="Screenshot 2026-03-03 143842" src="https://github.com/user-attachments/assets/c2d132dd-f096-41be-83e8-670fcd3228b4" />
    <li><strong>Dockerfile.yml (Books API Dockerfile)</strong></li>
    <img width="996" height="382" alt="image" src="https://github.com/user-attachments/assets/3511a9f6-7298-460a-ab5f-a2287c6b773a" />
    <li><strong>Dockerfile.yml (Mart API Dockerfile)</strong></li>
    <img width="568" height="292" alt="Screenshot 2026-03-03 143649" src="https://github.com/user-attachments/assets/ded885d5-4c1d-498a-a01a-63c3ca64b879" />
    <li><strong>Official Docker images were used for nginx and Databases (MongoDB, MYSQL)</strong></li>
    

    
</ul>

<h2>Database Architecture</h2>

<ul>
    <li><strong>MongoDB (Mart API):</strong> Flexible document-based storage for dynamic e-commerce data such as product info, inventory, and user profiles.</li>
    <li><strong>MySQL (Books API):</strong> Relational storage optimized for transactional data, relationships, and structured queries for book operations.</li>
</ul>

<h2>Key Technical Skills Demonstrated</h2>

<p>
Docker, Nginx, Angular, Node.js, Java (Spring Boot), MongoDB, MySQL, REST APIs, microservices, containerization, API gateway, load balancing, service isolation, polyglot persistence.
</p>

<p>
This architecture demonstrates a <strong>production-ready, scalable microservices ecosystem</strong> suitable for cloud deployment and modular service expansion.
</p>

</body>
</html>
