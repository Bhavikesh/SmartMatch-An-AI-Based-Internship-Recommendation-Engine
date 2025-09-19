# SmartMatch-An-AI-Based-Internship-Recommendation-Engine

**Project Overview:**
<br> 
SmartMatch is a lightweight, AI-based recommendation engine designed to help first-generation learners and youth from underserved communities find relevant internships. It addresses the challenge of navigating the vast PM Internship Scheme portal by providing a small, curated list of personalized recommendations, making the process simple and accessible.

**Problem Statement:**
<br>
The PM Internship Scheme receives applications from youth across India, many of whom have limited digital exposure and no prior internship experience. With hundreds of internships available, it's difficult for them to identify opportunities that match their skills and interests, leading to misaligned applications and missed opportunities.

**Our Solution:**
<br>
We have developed a functional prototype of a simple, mobile-first AI tool that takes basic candidate inputs and uses a hybrid rule-based and ML-light model to suggest the top 3-5 most relevant internships. Our focus is on user-friendliness, accessibility, and minimal resource usage, ensuring the tool can be easily integrated with the existing portal.

**Key Features:**
<br>
<ul>
<li><b>Personalized Recommendations:</b> Provides a curated list of internships based on user profiles.</li>
<li><b>Simple & Intuitive UI:</b> Designed for users with low digital literacy, featuring minimal text and visual cues.</li>
<li><b>Mobile Compatibility:</b> A single codebase for both Android and iOS ensures widespread access.</li>
<li><b>Lightweight & Efficient:</b> Uses a rule-based and ML-light model, avoiding resource-intensive deployment.</li>
</ul>


**Technical Stack:**
<br>
<ul>
<li><b>Frontend:</b> React Native or Flutter</li>
<li><b>Backend:</b> Python with Django or Flask</li>
<li><b>Recommendation Model:</b> Hybrid Rule-Based + Collaborative Filtering (ML-light)</li>
<li><b>Database:</b> PostgreSQL</li>
</ul>


**The Recommendation Engine:**
<br>
Our "ML-Light" approach is designed for simplicity and efficiency:
<ol>
<li><b>Rule-Based Matching:</b> The engine first filters internships based on a set of rules (e.g., matching a candidate's location and preferred sector).</li>
<li><b>ML-Light Refinement:</b> It then uses a lightweight machine learning model to further refine the recommendations based on historical data of successful matches and user behavior.</li>
</ol>
This hybrid approach ensures high-quality recommendations from day one, even with limited initial data.
<br><br>

**Workflow & User Journey:**
<ol>
  <li><b>User Onboarding:</b> User clicks "Get Recommendations" on the portal.</li>
  <li><b>Profile Input:</b> Fills out a simple form with basic details (education, skills, interests).</li>
  <li><b>Data Processing:</b> Our backend API receives the data and runs the recommendation algorithm.</li>
  <li><b>Recommendation Display:</b>   User sees 3-5 personalized internship cards on their screen.</li>
  <li><b>Application:</b> User can then proceed to apply for the internships they're interested in.</li>




</ol>

**Contributors:**
<br>
Bhavikesh Hedau
<br>
Harshal Ramteke
<br>
Chaitanya Hapse
<br>
Apurva Deshmukh
<br>

**License**
<br>
This project is licensed under the <b>MIT License </b>- see the LICENSE file for details.
