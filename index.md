---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: homepage
---

<!-- Main container for homepage content -->
<div style="display: flex; flex-direction: row; align-items: flex-start; justify-content: center; margin-top: 50px;">

    <!-- Left Section: Profile Picture and Social Links -->
    <div style="flex: 1; text-align: center;">
        <!-- Circular Profile Picture -->
        <img src="assets/images/Jacob_profile_pic.jpg" 
             alt="Jacob Delgado Home" 
             style="width: 200px; height: 200px; border-radius: 50%; object-fit: cover;">

        <!-- Name -->
        <h2 style="margin-top: 15px; font-family: Arial, sans-serif;">Jacob Delgado</h2>

        <!-- Social Links -->
        <div style="margin-top: 10px;">
            <a href="https://github.com/yourgithubusername" target="_blank" style="margin-right: 10px;">
                <img src="assets/icons/github-icon.png" alt="GitHub" style="width: 30px; height: 30px;">
            </a>
            <a href="https://www.linkedin.com/in/yourlinkedinprofile" target="_blank">
                <img src="assets/icons/linkedin-icon.png" alt="LinkedIn" style="width: 30px; height: 30px;">
            </a>
        </div>
    </div>

    <!-- Right Section: About Me, Research Interests, and News -->
    <div style="flex: 2; margin-left: 30px;">

        <!-- About Me Section -->
        <section id="about-me" style="margin-bottom: 20px;">
            <h2>About Me</h2>
            <p>I am an <strong>undergraduate senior</strong> in 
               <a href="https://www.uprm.edu/cse/">Computer Science and Engineering</a> 
               at the 
               <a href="https://www.uprm.edu/">University of Puerto Rico at Mayagüez</a>.</p>
            <p>
               My research focuses on deploying Artificial Intelligence (AI) to create meaningful social impact, particularly in resource-constrained environments. 
               I am committed to optimizing AI for embedded devices and exploring approaches like quantization and pruning.
            </p>
            <p>
               My ultimate career goal is to pursue a PhD in Computer Science and Engineering, contribute to the advancement of AI systems, and join academia in Puerto Rico 
               to mentor future generations.
            </p>
        </section>

        <!-- Research Interests Section -->
        <section id="research-interests" style="margin-bottom: 20px;">
            <h2>Research Interests</h2>
            <ul>
                <li><strong>AI for Social Impact:</strong> disease diagnosis, agricultural monitoring, environmental conservation</li>
                <li><strong>Machine Learning:</strong> transfer learning, knowledge distillation</li>
                <li><strong>Biomedical Engineering:</strong> accessible healthtech, disease prevention</li>
            </ul>
        </section>

        <!-- News Section -->
        <section id="news">
            <h2>News</h2>
            <ul>
                <li><strong>[Nov. 2024]</strong> Submitted two research papers to ISICN 2025!</li>
            </ul>
        </section>

    </div>
</div>

<!-- Footer: Contact Information -->
<footer style="margin-top: 30px; text-align: center;">
    <p><strong>Email:</strong> <a href="mailto:jacobdelgado1002@gmail.com">jacobdelgado1002@gmail.com</a></p>
</footer>

