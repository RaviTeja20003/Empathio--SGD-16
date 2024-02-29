# Empathio- SGD-16

[Link to UN Page regarding Gaza](https://news.un.org/en/story/2024/02/1146997)

[Link to UNICEF Page regarding GAZA](https://www.unicef.org/emergencies/children-gaza-need-lifesaving-support)

This project harnesses Google's Gemini AI to create multimedia narratives that inspire hope and raise funds for children and individuals affected by conflict, while also prioritizing mental health support. Through partnerships with organizations like UNICEF and potential deployments with NGOs such as the Red Cross, it aims to scale its impact globally. By implementing GAN-inspired architecture and GEMINI Vision, the project ensures safe content generation, safeguarding identities and adhering to UN Child Rights Convention standards, thus fostering resilience in conflict zones.

Problem Statement: In conflict zones, fundraising efforts struggle due to limited resources and awareness, while individuals endure mental stress and trauma without adequate support.

Solution Overview: Our project utilizes AI-generated multimedia narratives to facilitate fundraising without compromising identities and provides digital content to alleviate mental stress among affected populations.

Impact: By safeguarding identities and leveraging advanced AI technologies like Google's Gemini, we create impactful fundraising campaigns while addressing the mental health needs of individuals in conflict zones through tailored digital content, fostering resilience and support.

Our project aligns with SDG 16 by promoting peace and ending violence against children in conflict zones through the dissemination of positive narratives and fundraising efforts.
Target 17.16: The project's fundraising narrative drives global partnerships, fostering collaboration among organizations like UNICEF and the Red Cross to address the needs of children and individuals affected by conflict.

Within SDG 4, our project contributes to Target 4.a by providing a virtual safe space that fosters learning and healing for children in conflict-affected areas, promoting education as a means of empowerment and recovery.
SDG 3: Good Health and Well-being: Under SDG 3, our project addresses Target 3.4 by leveraging hopeful images and multimedia content to promote mental well-being among war-affected children, offering a source of solace and positivity amidst adversity.

Backend:
Utilizes Google Cloud Platform (GCP) services such as Google Cloud Functions, Google Cloud Storage, and Google Cloud Pub/Sub for scalability and reliability.
Frontend (Mobile Application):
Developed using Google's Flutter framework for cross-platform mobile app development, ensuring consistency and efficiency.
Technologies:
Google Firebase for user authentication, real-time database, and cloud messaging, ensuring secure and seamless user experiences.
TensorFlow for AI model training and inference, enabling advanced image and text processing capabilities.
Gemini text to text and text to Image capabilities are also used
Gemini - pro- vision - API for image analysis and recognition, enhancing multimedia content generation and safety checks.
Google Colab for collaborative machine learning model development and experimentation.
Programming Languages:
Backend: Primarily uses Python for its versatility and compatibility with various GCP services.
Frontend: Utilizes Dart programming language for Flutter app development, providing a modern and efficient development environment.

Gemini AI:

Purpose: Advanced AI capabilities for multimedia content generation and analysis.
Why for this project: Enables content safety checks and adherence to UN Child Rights Convention standards, enhancing narrative creation for conflict zone contexts.
Google Colab:

Purpose: Collaborative environment for machine learning and AI model experimentation.
Why for this project: Facilitates rapid prototyping and iteration of AI models, crucial for developing sophisticated features tailored to conflict zone needs.
Google Cloud Platform (GCP):

Purpose: Scalable and reliable cloud services for enterprise-level applications.
Why for this project: Offers scalability and reliability for hosting multimedia content and supporting backend operations essential for the project's functionality.
Google Firebase:

Purpose: Real-time database capabilities and comprehensive features for mobile and web applications.
Why for this project: Provides seamless user authentication, real-time data synchronization, and push notifications critical for enhancing user experiences and engagement.

Flutter:
Purpose: Framework for developing cross-platform mobile application frontends.
Why for this project: Offers a single codebase for Android and iOS platforms, ensuring consistency and efficiency in delivering a visually appealing user experience for conflict zone populations.

Steps Taken to Test the Solution with Real Users:

Discussed pilot deployment with an expert from a leading international organization and explored collaboration with the Red Cross and UN agency country offices.
Explored the solution with UNICEF for potential use in social media fundraising campaigns, though discussions remained verbal.
Planned partnership with the UN for deployment in the Middle East amid government funding suspensions for UNRWA.
Feedback Points Received from Real Users:

Collaboration Opportunities: Users highlighted potential partnerships with international organizations and NGOs for pilot deployments.
Fundraising Campaigns: Users suggested exploring UNICEF collaboration for social media fundraising campaigns.
Strategic Deployment: Users emphasized strategic deployment in regions affected by funding suspensions like the Middle East.
Implemented Improvements Based on User Feedback:

Strengthened efforts for collaboration with international organizations and NGOs for pilot deployments.
Explored formal discussions and agreements with UNICEF for effective fundraising campaigns.
Prioritized strategic deployment plans in regions affected by funding suspensions, aligning with the solution's objectives.

HTTP Timeout with GEMINI Pro:

Detail: Encountered HTTP Timeout issues with GEMINI Pro during content generation.
Solution: Worked extensively through the night to troubleshoot and optimize the code for efficient handling of requests, ensuring seamless interactions with GEMINI Pro.
Uncontrolled Images from Diffusion:

Detail: Diffusion often produced uncontrolled images, posing a challenge to content safety.
Solution: Employed a GAN-inspired approach to introduce safety guardrails, preventing the generation of inappropriate content. Leveraged GEMINI Vision for content quality checks, aligning with UN Child Rights Convention standards and ensuring the safety and appropriateness of generated images.
Change from IMAGEN to Stable Diffusion:

Detail: Initially planned to use IMAGEN, but had to pivot due to availability constraints.
Solution: Adapted the plan and chose stable diffusion, ensuring continuity and stability in the content generation process. The decision considered both the immediate need for a reliable solution and the availability of resources.

Our project stands as a beacon of innovation and hope in addressing the profound challenges faced by children and individuals living in conflict zones and war-torn areas. By harnessing the power of advanced AI technologies like GEMINI Pro and Diffusion, we've created a solution that transcends boundaries, offering solace, empowerment, and practical assistance where it's needed most.
To understand our solution's impact, we've utilized a range of tools and methodologies, including  user feedback sessions, and impact assessments.
our solution is not just a technological marvel; it's a testament to human ingenuity and compassion.

1. Adding Reinforcement learning to improve AI generated multimodal storyline. Fine-tune Google Gemma

2. Use GEMINI to improve customization of the AI generated multimedia to local language and local cultures  

3. Fine tune GAN based model to build more safety guardrails of AI generated content 

4. Deploy on Google cloud to scale the deployment
