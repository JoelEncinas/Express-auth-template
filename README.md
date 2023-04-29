# 🔑 Express authentication template
<img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="node" style="max-width: 100%;"> <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="express" style="max-width: 100%;"> <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb" style="max-width: 100%;"> <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="jsonwebtokens" style="max-width: 100%;"> <img src="https://img.shields.io/badge/handlebars-AF4B0C?style=for-the-badge&logo=handlebarsdotjs&logoColor=white" alt="handlebars" style="max-width: 100%;">

Simple login and register form using Express, Handlebars templates, and protected routes with a logout button. Users can register, login, and access the protected route only after successful authentication. The JWT token is used for authentication and is stored as a cookie in the client's browser. When the user logs out, the token is cleared from the cookie. I used this auth method in the [Wyrm's Lair](https://github.com/JoelEncinas/Wyrms-lair) project.

## 💿 Test the app locally

Replace the user, password and secret_key variables at `.env` with yours. In the project directory, you can run:

- `npm install`
- `npm start`

Open http://localhost:5000 to view it in your browser.

## 📷 Screenshots
<img src="https://github.com/JoelEncinas/Express-auth-template/blob/main/demo_img/register.PNG" alt="demo" width="350" height="300"/> <img src="https://github.com/JoelEncinas/Express-auth-template/blob/main/demo_img/login.PNG" alt="demo" width="350" height="300"/> <img src="https://github.com/JoelEncinas/Express-auth-template/blob/main/demo_img/protected.PNG" alt="demo" width="350" height="300"/>

