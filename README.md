# EatWellthy 🥗
A comprehensive web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) designed to revolutionize healthy eating habits through intelligent meal planning and nutrition tracking.

<p align="center">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
</p>


## 🌐 Live Demo & Deployment
- **Deployed Application**: [EatWellthy](https://eatwellthy.onrender.com)
- This deployed application may be inactive periodically
- It is highly recommended to clone this repository and use localhost

## 👥 Team Members
- [MOHD SHAJIE](https://github.com/mdshajie720/SMART-EATWELTHY-AI)
  [SAAD AHMED]()
  [MOHDMEHRAN]()


## 🌟 Key Features
🍴 Intelligent Meal Planning
Access precise nutritional data via the trusted Nutritionix API.
Create, save, and customize your own recipes effortlessly.
Receive daily meal suggestions tailored to your profile and preferences.
📈 Advanced Nutrition Insights
Track calories and macronutrients in real-time.
Gain detailed insights into macro and micronutrient distribution.
Monitor your progress with visually appealing, interactive charts.
🧑‍💻 Enhanced User Experience
Stay updated with a personalized dashboard summarizing daily stats.
Utilize an easy-to-navigate meal planner with drag-and-drop capabilities.
Get instant help from the responsive AI assistant, Welloh, for queries.
⚙️ Getting Started
1. Repository Setup
Clone the project repository using your preferred method:

GitHub Desktop: Ideal for beginners; offers a user-friendly interface.
Git Command Line: Efficient for advanced users.
     ```bash
     git clone <repository-url>
     ```

### 2. Environment Setup
Open EatWellthy/backend/.env.example, key in your API keys, rename as .env
```
MONGODB_URI=your_mongodb_uri
NUTRITION_API_KEY=your_api_key
```
Open EatWellthy/client/.env.example, key in your API key, rename as .env
```
REACT_APP_GOOGLE_MAPS_API_KEY=your_api_key
```

### 3. Install Dependencies
Under the eatwellthy directory, copy this to your terminal:
```bash
npm install 
npm run install-all
npm run dev
```
##### The web app will automatically open in your default browser.
##### The first local run may take ~45 seconds to install packages.
##### The following takes ~20 seconds.

Alternatively you may key in the command line by line 
```bash
npm install 
cd client 
npm install --legacy-peer-deps
cd ../backend
npm install
cd ..
npm run dev
```

---
## 🔄 Development Workflow
### Regular Updates
Before making changes:
```bash
git fetch origin
git pull origin main
```

### Making Changes
1. Create a new branch for your feature:
```bash
git checkout -b feature/your-feature-name
```
2. Make your changes
3. Commit and push:
```bash
git add .
git commit -m "Description of changes"
git push origin feature/your-feature-name
```

---
## 📦 Troubleshooting
If modules need reinstalling:
```bash
cd EatWellthy or client or backend
For Mac/Linux users: rm -rf node_modules
For Windows users: Remove-Item -Recurse -Force .\node_modules 
npm install --legacy-peer-deps  

---
 ## 🔌 API Integrations
EatWellthy utilizes a range of advanced APIs to deliver an all-encompassing health and nutrition platform:

🥗 Nutritionix API
Offers a rich food database with precise nutritional data and natural language processing capabilities.
🤖 OpenAI Integration
Provides personalized meal suggestions through the AI-powered chatbot, Welloh.
📍 Google Maps API
Easily find nearby grocery stores for convenient shopping.
📅 Google Calendar API
Sync meal plans effortlessly and set reminders directly in your Google Calendar.
✉️ Brevo API
Enables smooth email verification and supports password reset functionality.
🔐 Google OAuth 2.0
Ensures secure login and cross-device profile synchronization for a seamless experience.

---






## 📚 Documentation Structure

- [Documents](/Documents)
  - [Design Diagrams](/Documents/DesignDiagrams)
  - [Lab Deliverables](/Documents/LabDeliverables)
  - [Sequence Diagrams](/Documents/SequenceDiagrams)

## 📋 Project Resources
- [EatWellthy Demo Slides](/Documents/EatWellthy%20Demo%20Slides.pdf)
- [EatWellthy Development Team](/Documents/EatWellthy%20Development%20Team.pdf)
- [EatWellthy Test Cases](/Documents/EatWellthy%20Test%20Cases.pdf)
- [EatWellthy Use Cases](/Documents/EatWellthy%20Use%20Cases.pdf)


## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


## 🤝 Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request


## 📝 Additional Notes
- Regularly pull changes from main to stay updated
- Follow the README.md for operation guidance
- The application uses Nutritionix API for food data
- Deployed on Render's platform


## 🔗 References

Here are the documentation resources used in this project:

- [Nutritionix API Documentation](https://developer.nutritionix.com/docs/v2)  
  V2.0 API Home. (n.d.).
- [BREVO API Documentation](https://developers.brevo.com/)  
  Brevo API. (n.d.).
- [Google API Documentation](https://console.cloud.google.com/apis/library)  
  API Library – APIs & Services – Google Cloud console. (n.d.).
- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference/introduction)  
  OpenAI Platform. (n.d.).
- [IEEE Software Engineering Standards](https://innovate.ieee.org/ieee-software-engineering-standards/)  
  Ieeeinnovate. (2019, December 9). Innovate.
- [Good Practices for Educational Software Engineering Projects](https://ieeexplore.ieee.org/document/4222631)  
  IEEE Conference Publication | IEEE Xplore. (n.d.).
- **Nanyang Technological University, Singapore** - SC2006 Software Engineering, Lecture Notes



Happy coding with **EatWellthy**! 💪
