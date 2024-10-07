<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Cloud Server Website</h1>
		</header>

<!-- Content -->
<h2 id="content">Overview</h2>
<p>The Weather Forecast App is a robust and scalable application developed using Python and Django. This app integrates data from multiple APIs to provide users with accurate and up-to-date weather information. To ensure consistency and reliability, the application is containerized with Docker and hosted on an AWS EC2 instance.</p>

<h2 id="content">Features</h2>
<h3>Python Django Web App</h3>
<ul>
    <li>Developed using the Django framework to handle web requests.</li>
    <li>Renders accurate weather data in a user-friendly format.</li>
</ul>

<h3>Multiple APIs Integration</h3>
    <ul>
        <li>Fetches weather data from various APIs to ensure comprehensive forecasts.</li>
        <li>Combines data sources for improved accuracy.</li>
    </ul>

<h3>Containerization with Docker</h3>
    <ul>
        <li>Containerized using Docker to ensure consistency across different environments.</li>
        <li>Facilitates easy deployment and scalability.</li>
    </ul>

<h3>Hosting on AWS EC2</h3>
    <ul>
        <li>Deployed on an AWS EC2 instance for robust and scalable hosting.</li>
        <li>Ensures high availability and reliability.</li>
    </ul>

<h2>Deployment</h2>

<h3>Automated AWS Deployment with Terraform</h3>
    <ul>
        <li>Utilizes Terraform for Infrastructure as Code (IaC), automating the deployment of AWS resources.</li>
        <li>Simplifies infrastructure management and deployment processes.</li>
    </ul>

<h3>CI/CD Pipeline with GitHub Actions</h3>
    <ul>
        <li>Implements a continuous integration and continuous deployment (CI/CD) pipeline using GitHub Actions.</li>
        <li>Uses OpenID Connect for secure and temporary credentials during the deployment process.</li>
    </ul>

<h3>Terraform State Management</h3>
    <ul>
        <li>Secures the Terraform state file in a versioned S3 backend.</li>
        <li>Manages concurrency and consistency with a DynamoDB table state lock in the CI/CD pipeline.</li>
    </ul>

<h2>Technologies Used</h2>
    <ul>
        <li><strong>Django:</strong> Web framework for Python.</li>
        <li><strong>Docker:</strong> Containerization platform.</li>
        <li><strong>AWS EC2:</strong> Cloud computing service for hosting.</li>
        <li><strong>Terraform:</strong> Infrastructure as Code tool.</li>
        <li><strong>GitHub Actions:</strong> CI/CD automation tool.</li>
        <li><strong>OpenID Connect:</strong> Protocol for secure and temporary credentials.</li>
        <li><strong>S3:</strong> AWS storage service.</li>
        <li><strong>DynamoDB:</strong> AWS NoSQL database service.</li>
    </ul>

<!-- <h4>Fit</h4> -->
<div class="image fit">
<img src="{% link assets/images/Weather-App.png %}" alt="" />
<li><a href="http://ec2-44-214-46-118.compute-1.amazonaws.com" class="button">View Demo</a></li>
</div>

</div>
</section>