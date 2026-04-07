<div align="center">
  <h1>🌍 Akyl: Cloud-Powered Quiz Game Application</h1>
  <p><b>A Serverless, Full-Stack Educational Platform for Kyrgyz Culture</b></p>

  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/GoDaddy-00A69C?style=for-the-badge&logo=godaddy&logoColor=white" alt="GoDaddy" />
  <img src="https://img.shields.io/badge/CI/CD-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="CI/CD" />
</div>

<h1>🧠 Cloud-Powered Quiz Game Application</h1>

<p>
A scalable, serverless quiz application built using modern web technologies and AWS cloud services.
This project demonstrates real-world cloud architecture, CI/CD automation, and full-stack development skills.
</p>

<hr>

<h2>🖼️ Architecture Diagram</h2>
<p>High-level system design:</p>
<img src="./image24.png" alt="Architecture Diagram" width="900">

<hr>

<h2>🚀 Tech Stack</h2>
<ul>
  <li><b>Frontend:</b> React</li>
  <li><b>Backend:</b> Node.js, Express</li>
  <li><b>Database:</b> MongoDB Atlas</li>
  <li><b>Cloud:</b> AWS Lambda, S3, API Gateway, CloudFront</li>
  <li><b>CI/CD:</b> AWS CodePipeline, CodeBuild</li>
</ul>

<hr>

<h2>✨ Features</h2>
<ul>
  <li>🎯 Interactive quiz system</li>
  <li>📊 Real-time score tracking</li>
  <li>🔐 Admin authentication (JWT)</li>
  <li>🛠 Admin panel for quiz management</li>
  <li>📱 Fully responsive UI</li>
  <li>⚡ Serverless scalability</li>
</ul>

<hr>

<h2>📡 API Endpoints</h2>

<h3>Quiz</h3>
<ul>
  <li>GET /api/quiz</li>
  <li>GET /api/quiz/:id</li>
  <li>POST /api/quiz (Admin)</li>
  <li>PUT /api/quiz/:id (Admin)</li>
  <li>DELETE /api/quiz/:id (Admin)</li>
</ul>

<h3>Authentication</h3>
<ul>
  <li>POST /api/auth/register</li>
  <li>POST /api/auth/login</li>
</ul>

<hr>

<h2>🧪 Detailed Testing & Implementation</h2>

<h3>Testing React Application Locally (localhost:3000)</h3>

<h4>Main Page</h4>
<p>
The main page welcomes users with an H1 heading: "Welcome to Quiz Game about Kyrgyzstan."<br>
A paragraph prompts users: "Select a category to start learning more about Kyrgyzstan."<br>
Categories are displayed as clickable buttons.
</p>
<img src="image26.png" width="700">

<h4>Quiz by Category</h4>
<p>
A page dynamically renders quiz questions and options based on the selected category.
</p>
<img src="image28.png" width="700">

<h4>Quiz Results</h4>
<p>
The results page displays the user's score (e.g., "You scored 5 out of 9").<br>
Includes buttons to retake the quiz or return to the main page.
</p>
<img src="image27.png" width="700">


<h4>Admin Panel</h4>
<p>
Allows admins to manage quizzes by creating categories, editing questions, and deleting existing entries.
</p>
<img src="image33.png" width="700">

<h4>Edit Quiz</h4>
<p>
Admins can edit quizzes by modifying questions, options, and the correct answer.
</p>
<img src="image31.png" width="700">

<hr>

<h3>Testing APIs Locally (localhost:5000)</h3>

<h4>API Testing with Postman</h4>

<p><b>GET /api/quiz</b>: Fetches all quiz categories.</p>
<img src="image32.png" width="700">

<p><b>GET /api/quiz/:id</b>: Fetches a specific quiz by ID.</p>
<img src="image34.png" width="700">

<p><b>POST /api/quiz</b>: Creates a new quiz (admin-only access).</p>
<img src="image35.png" width="700">

<hr>

<h3>Project Structure in Visual Studio Code</h3>

<h4>Frontend</h4>
<p>The structure of the frontend project highlights components, services, and pages.</p>
<img src="image39.png" width="700">

<h4>Backend</h4>
<p>The backend project includes routes and models.</p>
<img src="image40.png" width="700">

<hr>

<h3>AWS Lambda Deployment</h3>

<h4>Uploading the Backend</h4>
<p>The backend was packaged and uploaded to AWS Lambda.</p>
<img src="image41.png" width="700">

<h4>Testing Lambda Function</h4>
<p>Lambda function tested successfully (200 OK).</p>
<img src="image12.png" width="700">

<h4>API Gateway Trigger</h4>
<p>Configured API Gateway with Lambda integration.</p>
<img src="image14.png" width="700">

<hr>

<h3>Testing Deployed API</h3>

<p><b>Production Invoke URL</b></p>
<img src="image15.png" width="700">

<p><b>GET /api/quiz</b></p>
<img src="image16.png" width="700">

<p><b>GET /api/quiz/:id</b></p>
<img src="image17.png" width="700">

<hr>

<h3>Frontend Integration</h3>

<p><b>Updating API Endpoint</b></p>
<img src="image18.png" width="700">

<p><b>Verification</b></p>
<img src="image19.png" width="700">
<img src="image20.png" width="700">

<hr>

<h3>Hosting the React Application</h3>

<p><b>S3 Upload</b></p>
<img src="image21.png" width="700">

<p><b>S3 Test</b></p>
<img src="image2.png" width="700">

<hr>

<h3>CloudFront Integration</h3>

<p><b>Setup</b></p>
<img src="image3.png" width="700">

<p><b>HTTPS Access</b></p>
<img src="image4.png" width="700">

<hr>

<h3>ACM & Domain</h3>

<p><b>Certificate</b></p>
<img src="image5.png" width="700">

<p><b>DNS Config</b></p>
<img src="image6.png" width="700">

<p><b>Custom Domain</b></p>
<img src="image7.png" width="700">

<hr>

<h3>CI/CD Pipeline</h3>
<p>
The CI/CD pipeline is integrated with <b>GitHub</b>. Every new commit or push to the repository automatically triggers the pipeline.
This ensures continuous integration and continuous deployment without manual intervention.
</p>
<ul>
  <li><b>Trigger:</b> GitHub (on every commit/push)</li>
  <li><b>Automation:</b> AWS CodePipeline detects changes</li>
  <li><b>Build:</b> AWS CodeBuild installs dependencies and builds the project</li>
  <li><b>Deploy:</b> Automatic deployment to S3 (frontend) and Lambda (backend)</li>
</ul>

<p><b>Source Stage</b></p>
<img src="image8.png" width="700">

<p><b>Build Stage</b></p>
<pre>
version: 0.2
phases:
  install:
    commands:
      - echo Installing dependencies...
      - npm install
  build:
    commands:
      - echo Building the React app...
      - npm run build
artifacts:
  files:
    - '**/*'
    base-directory: build
</pre>
<img src="image9.png" width="700">

<p><b>Deploy Stage</b></p>
<img src="image10.png" width="700">

<p><b>Pipeline Overview</b></p>
<img src="image11.png" width="900">

<hr>

<h2>📚 What I Learned</h2>
<ul>
  <li>Designed and implemented a <b>serverless architecture</b> using AWS Lambda and API Gateway</li>
  <li>Deployed and optimized a <b>React application</b> using S3 and CloudFront for global delivery</li>
  <li>Built scalable backend APIs with <b>Node.js and Express</b></li>
  <li>Integrated a cloud database using <b>MongoDB Atlas</b></li>
  <li>Implemented <b>JWT authentication</b> for secure admin access</li>
  <li>Configured <b>CI/CD pipelines</b> using AWS CodePipeline and CodeBuild</li>
  <li>Tested APIs and application workflows using <b>Postman</b></li>
  <li>Understood <b>end-to-end cloud deployment</b> from local development to production</li>
  <li>Improved skills in <b>debugging, system design, and troubleshooting</b></li>
</ul>

<hr>

<h2>👨‍💻 Akylbek's Project</h2>
<p>
This project was fully designed, developed, and deployed by <b>Akylbek Muratbek uulu</b> as part of hands-on learning in cloud computing, DevOps, and full-stack development.
It reflects practical experience in building real-world scalable applications using modern technologies and cloud infrastructure.
</p>









