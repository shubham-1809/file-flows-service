<h2>File Flows Service</h2>

<h3>Table of Contents</h3>
<ul>
  <li>Introduction</li>
  <li>Features</li>
  <li>Getting Started</li>
    <ul>
      <li>Prerequisites</li>
      <li>Installation</li>
    </ul>
  <li>Usage</li>
  <li>Endpoints</li>
  <li>License</li>
</ul>

<h3>Introduction</h3>
<p>File Flows is a simple file link sharing web app built using Node.js, Express and MongoDB. The application allows users to upload and share files with others through generated links. The frontend is developed using HTML, CSS, and JavaScript.This app mainly focuses on college students so that they can share their project files with faculty members.</p>

<h3>Features</h3>
<ul>
  <li>File upload and link generation.</li>
  <li>User-friendly interface with responsive design.</li>
  <li>MongoDB integration for data storage.</li>
  <li>Built in 'send file via email' feature for college students.</li>
  <li>24 hour file link expiration to optimize database space.</li>
</ul>

<h3>Getting Started</h3>
<h4>Prerequisites</h4>
<p>Before you begin, ensure you have the following installed:</p>
<ul>
  <li>Node.js</li>
  <li>MongoDB</li>
</ul>
<h5>Installation</h5>
<ol>
  <li>Clone the repository: git clone https://github.com/shubham-1809/file-flows-service.git</li>
  <li>Navigate to the project directory:cd file-flows-service</li>
  <li>Install dependencies: npm install</li>
  <li>Set up your MongoDB database and update the configuration in config/config.js.</li>
  <li>Start the application: npm start</li>
</ol>
The app will be running at http://localhost:3000.

<h3>Usage</h3>
<ol>
  <li>Open your web browser and navigate to http://localhost:3000.</li>
  <li>Upload files through the provided interface.</li>
  <li>Obtain the generated link and share it with others.</li>
  <li>Or fill the provided form and send the mail if you are a college student</li>
</ol>

<h3>API Endpoints</h3>
<ul>
  <li>POST /api/files: Uploads file to the server.</li>
  <li>GET /files/:uuid: Redirects to the download link page.</li>
  <li>GET /files/download/:uuid: Downloads file from the server.</li>
</ul>

<h3>Contributing</h3>
<p>Contributions are welcome! Fork the repository, create a branch, make your changes, and submit a pull request.</p>

<h3>License</h3>
<p>This project is licensed under the MIT License.</p>
