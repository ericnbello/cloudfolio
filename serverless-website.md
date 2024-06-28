<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Serverless Website</h1>
		</header>

<!-- Content -->
<h2>Overview</h2>
    <p>Following my AWS Certified Cloud Practitioner certification, I eagerly undertook the Cloud Resume Challenge to apply and expand my AWS skills. This project encompassed a series of tasks leveraging various AWS services to customize and deploy my portfolio site. Below, I detail the steps taken to integrate these services and successfully complete the challenge.</p>

<h2>Steps</h2>

<h3>1. Deploying as an Amazon S3 Static Website</h3>
    <ul>
        <li>Created a publicly accessible S3 bucket to host the site.</li>
        <li>Configured the website endpoint for the default region (us-east-1).</li>
    </ul>

<h3>2. AWS CloudFront for HTTPS</h3>
    <ul>
        <li>Used CloudFront CDN to enable HTTPS traffic.</li>
        <li>Linked the S3 endpoint as the origin to the CloudFront distribution for a secure domain name.</li>
    </ul>

<h3>3. Custom Domain with DNS</h3>
    <ul>
        <li>Edited DNS entries with my domain provider (Google) to point to the CloudFront distribution.</li>
        <li>Verified ownership and obtained a custom SSL certificate from CloudFront.</li>
    </ul>

<h3>4. Visitor Counter - JavaScript</h3>
    <ul>
        <li>Created a simple VisitorCounter component in Next.js.</li>
        <li>Rendered the counter in the footer of each page.</li>
    </ul>

<h3>5. DynamoDB Database for Count Value</h3>
    <ul>
        <li>Used DynamoDB to store and update the visitor count.</li>
        <li>Opted for on-demand pricing to utilize the AWS Free Tier.</li>
    </ul>

<h3>6. Python Lambda Function and API Gateway</h3>
    <ul>
        <li>Created a Lambda function with Python and boto3 to interact with DynamoDB.</li>
        <li>Set up API Gateway to handle requests from the web app.</li>
    </ul>

<h3>7. Infrastructure as Code (IaC) with CloudFormation and SAM CLI</h3>
    <ul>
        <li>Defined resources using an AWS Serverless Application Model (SAM) template.</li>
        <li>Deployed resources with CloudFormation via the SAM CLI.</li>
    </ul>

<h3>8. Source Control with Git</h3>
    <ul>
        <li>Managed the code for both the back-end API and front-end website in a GitHub repository.</li>
    </ul>

<h3>9. CI/CD with GitHub Actions</h3>
    <ul>
        <li>Set up CI/CD pipelines for consistent deployment.</li>
        <li>Configured GitHub Actions to automatically run on code updates.</li>
        <li>Ensured CloudFront cache invalidation for the latest changes.</li>
    </ul>

<h2>Final Thoughts</h2>
    <p>Completing the Cloud Resume Challenge was an enriching experience that demonstrated my skills in AWS and expanded my knowledge in cloud services, automation, and infrastructure as code. This project showcased my ability to deliver professional-grade solutions using cutting-edge technologies.</p>

<div class="image fit">
<img src="{% link assets/images/Eric-Bello-Portfolio.png %}" alt="" />
</div>

</div>
</section>