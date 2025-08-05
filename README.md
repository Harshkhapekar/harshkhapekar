<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Profile</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(120deg, #e0eafc, #cfdef3);
      color: #333;
      padding: 40px 20px;
      animation: fadeIn 1.5s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .container {
      max-width: 900px;
      margin: auto;
      background: white;
      border-radius: 15px;
      box-shadow: 0 12px 24px rgba(0, 0, 0, 0.1);
      padding: 40px;
      animation: slideUp 1.2s ease;
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    h1 {
      font-size: 36px;
      text-align: center;
      background: linear-gradient(45deg, #1a73e8, #673ab7);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 30px;
      font-weight: 800;
    }

    .section {
      margin-bottom: 25px;
      padding: 20px;
      border-left: 5px solid #1a73e8;
      border-radius: 10px;
      background: #f5faff;
      transition: all 0.3s ease;
    }

    .section:hover {
      transform: scale(1.02);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.07);
    }

    .section h2 {
      font-size: 22px;
      margin-bottom: 10px;
      color: #1a237e;
    }

    .section p {
      font-size: 16px;
      line-height: 1.6;
    }

    .icon {
      color: #1a73e8;
      margin-right: 10px;
    }

    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }

      h1 {
        font-size: 28px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1><i class="fas fa-user icon"></i>My Profile</h1>

    <div class="section">
      <h2><i class="fas fa-user-graduate icon"></i>Objective</h2>
      <p>To gain knowledge and experience in the field of Computer Science and Software Development while contributing to the organization's success.</p>
    </div>

    <div class="section">
      <h2><i class="fas fa-id-card icon"></i>Personal Information</h2>
      <p><strong>Name:</strong> Harsh Khapekar<br>
         <strong>Date of Birth:</strong> 13/12/2003<br>
         <strong>Gender:</strong> Male<br>
         <strong>Languages Known:</strong> English, Hindi, Marathi<br>
         <strong>Nationality:</strong> Indian
      </p>
    </div>

    <div class="section">
      <h2><i class="fas fa-book icon"></i>Academic Qualification</h2>
      <p><strong>Bachelor of Technology (B.Tech)</strong><br>
         G.H. Raisoni Institute of Engineering and Technology, Nagpur<br>
         RTMNU | Year: 2025 | CGPA: 6.9
      </p>
      <p><strong>12th (HSC)</strong><br>
         Prerna Junior College, Nagpur | Year: 2021 | Percentage: 55.69%
      </p>
      <p><strong>10th (SSC)</strong><br>
         NMC School, Nagpur | Year: 2019 | Percentage: 65.40%
      </p>
    </div>

    <div class="section">
      <h2><i class="fas fa-laptop-code icon"></i>Technical Skills</h2>
      <p><strong>Languages:</strong> C, C++, Python, Java, HTML, CSS, JavaScript, SQL<br>
         <strong>Operating Systems:</strong> Windows, Linux<br>
         <strong>Tools & Technologies:</strong> Git, GitHub, VS Code, MySQL, ServiceNow
      </p>
    </div>

    <div class="section">
      <h2><i class="fas fa-certificate icon"></i>Certifications</h2>
      <p>1. ServiceNow Certified System Administrator – ServiceNow<br>
         2. Salesforce AI Associate – Salesforce
      </p>
    </div>

    <div class="section">
      <h2><i class="fas fa-project-diagram icon"></i>Project</h2>
      <p><strong>Title:</strong> Beggar-Free India Awareness<br>
         <strong>Description:</strong> Created and published a solo awareness video on “Beggar-Free India” to promote social consciousness through the NGO Avbodh Foundation, Nagpur.
      </p>
    </div>

    <div class="section">
      <h2><i class="fas fa-hands-helping icon"></i>Extra Curricular Activities</h2>
      <p>Active participation in blood donation camps, street plays, and other social awareness programs organized by the Avbodh Foundation NGO, Nagpur.</p>
    </div>

    <div class="section">
      <h2><i class="fas fa-thumbs-up icon"></i>Strengths</h2>
      <p>Self-motivated, quick learner, leadership skills, strong communication, and time management abilities.</p>
    </div>

    <div class="section">
      <h2><i class="fas fa-bolt icon"></i>Hobbies</h2>
      <p>Playing cricket, reading books, participating in social events, creating awareness videos, and contributing to social initiatives.</p>
    </div>
  </div>
</body>
</html>
