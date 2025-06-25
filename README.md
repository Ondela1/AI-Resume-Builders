AI Resume Builder – Smart, Simple & ATS-Friendly

Consider adding a screenshot of your live application here once deployed.

🚀 Introduction
In today's competitive digital job market, job seekers face significant challenges in creating resumes that are both professional and optimized to pass through Applicant Tracking Systems (ATS). Our AI Resume Builder is designed to address these challenges by providing an intelligent, user-friendly, and ATS-compatible solution.

✨ Features
Our AI Resume Builder offers a robust set of features to streamline the resume creation process:

User Input Section: Intuitive and easy-to-use forms for collecting essential personal, educational, and professional data.

AI Resume Generation & Refinement: Leverages the Gemini API to auto-generate structured resume content and offer intelligent suggestions for summaries, experience descriptions, and skills, helping users craft impactful narratives.

ATS Compatibility Checker: Analyzes the generated resume content against common ATS standards, providing real-time feedback, a compatibility score, and actionable recommendations for improvement.

Visual Templates: Choose from 3 distinct visual templates (Modern, Classic, Creative) to present your resume with a professional and aesthetically pleasing design.

Feedback Loop: A unique feature that allows users to provide feedback on AI-generated suggestions, enabling a continuous improvement cycle for future AI outputs.

PDF Download: Converts the fully structured and optimized resume into a high-quality, downloadable PDF format, ready for job applications.

🛠️ Technologies Used
The AI Resume Builder is built using a modern static site stack:

Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling Framework: Tailwind CSS CDN for rapid and responsive UI development.

PDF Generation: jsPDF Library for client-side PDF document creation.

AI Integration: Google's Gemini API for intelligent content generation, refinement, and ATS analysis.

Storage: Browser's localStorage for temporary data persistence within the user's browser.

Hosting: Designed for easy deployment on static site hosting services like GitHub Pages or Netlify.

🏃 How to Run Locally
To get a copy of this project up and running on your local machine for development and testing purposes:

Clone the repository:

git clone https://github.com/Ondela1/Ai-Resume-Builders.git
cd Ai-Resume-Builders

Open index.html:
Simply open the index.html file in your preferred web browser. All CSS and JavaScript are linked relatively within the HTML.

Note: For AI features to work, ensure you are running this within an environment that provides the Gemini API key (like the Canvas environment where this was developed) or manually insert your API key into script.js for local testing (not recommended for production environments).

🚀 Deployment
This project is designed as a static website and can be easily deployed to various hosting services.

Deploying to GitHub Pages (Recommended)
Push your code to a GitHub repository. If you haven't already, follow the steps to create a new GitHub repository and push your index.html, style.css, and script.js files to the main branch.

Enable GitHub Pages:

Navigate to your repository on GitHub.

Go to Settings > Pages.

Under "Build and deployment", set "Source" to Deploy from a branch.

Select your primary branch (e.g., main) and the /(root) folder.

Click Save.

Your site will be deployed within a few minutes, and you'll find the public access link in the same "Pages" section (e.g., https://Ondela1.github.io/Ai-Resume-Builders/).

👥 Group Members
Mthunzi Malebadi (Group Leader)

Sinesipho Sibulo

Ondela Citywayo

Vhuvhwavho Mawela Maselesa

Segai Bryton Mampshika

💡 Future Enhancements
Job Description Matching (FR7): Implement AI capabilities to compare the generated resume with a user-provided job description and suggest tailored optimizations.

DOCX/HTML Export: Expand export options to include Microsoft Word (.docx) and plain HTML formats for broader compatibility.

Advanced Customization: Offer more granular control over template aesthetics (e.g., custom colors, font choices beyond predefined templates).

Rich Text Editor: Implement a rich text editor for sections like "Experience Description" to allow users more control over formatting (bold, italics, bullet points).

User Authentication: Secure user data with authentication (e.g., Firebase Authentication).# AI-Resume-Builders
