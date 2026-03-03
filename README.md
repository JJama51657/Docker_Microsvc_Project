
<body>

<h1>eMart Microservices Architecture</h1>

<p><strong>eMart</strong> is a cloud-native e-commerce platform designed using a <strong>microservices architecture</strong>, built for scalability, flexibility, and independent service deployment. The platform demonstrates modern <strong>DevOps practices</strong>, <strong>containerization</strong>, and efficient API-based communication between services.</p>

<h2>Key Components</h2>
<ul>
    <li><strong>API Gateway:</strong> Nginx-based gateway managing <strong>request routing</strong>, <strong>authentication</strong>, and <strong>load balancing</strong> across services. Supports multiple endpoints including <code>/</code>, <code>/api</code>, and <code>/webapi</code>.</li>
    <li><strong>Front-End Application:</strong> Angular client application integrated with the API gateway for a seamless <strong>user experience</strong> and responsive UI interactions.</li>
    <li><strong>Backend Services:</strong>
        <ul>
            <li><strong>Mart API:</strong> Node.js service connected to MongoDB for dynamic product, user, and inventory management.</li>
            <li><strong>Books API:</strong> Java-based service integrated with MySQL for structured book data, transactions, and metadata management.</li>
        </ul>
    </li>
    <li><strong>Containerization:</strong> All services (Nginx, Angular, Node.js, Java, MongoDB, MySQL) run in Docker containers for <strong>CI/CD pipelines</strong>, <strong>scalability</strong>, and <strong>microservice isolation</strong>.</li>
</ul>

<h2>Databases</h2>
<ul>
    <li><strong>MongoDB (Mart API):</strong> Flexible, schema-less database handling dynamic e-commerce data such as products, inventory, and user profiles.</li>
    <li><strong>MySQL (Books API):</strong> Relational database enforcing structured data relationships for book listings, transactions, and metadata.</li>
</ul>

<h2>DevOps & Scalability Highlights</h2>
<ul>
    <li>Supports <strong>horizontal scaling</strong> of services for high availability.</li>
    <li>Facilitates <strong>CI/CD automation</strong> with containerized microservices.</li>
    <li>Enables easy integration of additional services like <strong>payment gateways</strong> or <strong>shopping cart features</strong>.</li>
</ul>

<p><strong>Summary:</strong> eMart exemplifies a modern <strong>microservices-based, cloud-ready architecture</strong> optimized for <strong>DevOps pipelines</strong>, <strong>containerization</strong>, and <strong>API-first design</strong>, making it a scalable, flexible, and maintainable e-commerce solution.</p>

</body>
</html>
