# [Pet Shop web site](https://pet-shop-frontend-ten.vercel.app/) 
<p align="left">
  <a href="https://github.com/katroienko/pet-shop-frontend/tree/master" target="_blank" style="text-decoration:none;">
    <button style="padding:10px 20px; font-size:16px; cursor:pointer;">Look Front-End code</button>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/katroienko/pet-shop-backend" target="_blank" style="text-decoration:none;">
    <button style="padding:10px 20px; font-size:16px; cursor:pointer;">Look Back-End code</button>
  </a>
  &nbsp;&nbsp;
  <a href="https://pet-shop-frontend-ten.vercel.app/" target="_blank" style="text-decoration:none;">
    <button style="padding:10px 20px; font-size:16px; cursor:pointer;">Look web site</button>
  </a>
</p>
📖 Available in:  
<a href="https://github.com/katroienko/pet-shop-frontend/blob/master/docs/README.ru.md" target="_blank" style="text-decoration:none;">
    <button style="padding:10px 20px; font-size:16px; cursor:pointer;"> [🇷🇺 Русский]</button>
  </a>
 [🇷🇺 Русский](https://github.com/katroienko/pet-shop-frontend/blob/master/docs/README.ru.md) | [🇩🇪 Deutsch](docs/README.de.md)

 
# 🐾 Pet Shop — Online Store  

A modern **full-stack e-commerce project** built from scratch with full **frontend + backend** integration.  
The app features dynamic product filtering, a shopping cart, checkout flow, breadcrumbs for navigation, and optimized performance.  

---

## 🔹 Problem  
Most educational e-commerce projects are limited to static pages or primitive filtering.  
As a result, users cannot quickly find the right product, and employers have difficulty evaluating the developer’s real skill level.  

---

## 🔹 Solution  
I created **Pet Shop** — an online store with a real-world feature set:  
- Dynamic filtering with **URL-synchronized state**  
- Shopping cart and checkout with validation  
- Scalable architecture with **Redux Toolkit + Thunk**  
- Reusable UI components and responsive design  
- Improved **SEO** with breadcrumbs  

---

## 🚀 Key Features  

- 🔎 **URL-synchronized filters (state in URL)** → sharable links, state persists after reload  
- ⚡ **Server-side filtering** → accurate results on large catalogs, less mobile traffic  
- ♿ **Accessible modals (focus trap, aria-*)** → keyboard/screen reader support, no accidental scrolls  
- 📄 **Custom pagination (usePagination)** → predictable navigation, saved scroll position  
- 🗂 **Redux Toolkit + Thunk** → single source of truth, safe against race conditions  
- 🧠 **Memoization (React.memo, useMemo, useCallback)** → fewer re-renders, smoother UI  
- 🧭 **Breadcrumbs** → clear navigation, SEO improvement  
- 🛡 **Request decorator** → cancellation of outdated responses, always fresh UI state  
- 📝 **Form validation & error handling** → clear messages, no lost data, smoother checkout  
- 🔁 **Reusable components (Button, PageLayout, Title)** → consistent UI, less cognitive load  
- 🎨 **MUI + CSS Modules** → responsive, accessible design, stable theming  
- 🐞 **URL logging for debugging** → easier bug reproduction, higher reliability  

---

## 📊 Potential Impact  
- ↓ **Time-to-Product**  
- ↑ **Add-to-Cart rate**  
- ↑ **Checkout completion**  
- ↓ **Bounce rate** during filtering  
- ↑ **Share rate** via URLs  

---

## 🔹 Results  
- ⚡ Fast filtering → products found in 2–3 clicks  
- 🌐 Shareable search results → closer to real e-commerce functionality  
- 📈 Scalable architecture → easy to extend with new categories and filters  
- 🚀 Improved **SEO** and navigation  

---

## 🧑‍💻 Lessons Learned  
- How to structure **Redux + Thunk architecture**  
- How to persist **filter state in URL** (important for SEO & UX)  
- How to **optimize rendering** with memoization  
- How to combine styling approaches (**MUI + CSS Modules**)  
- How to deploy a **full-stack project**  

---

## ⚙️ Tech Stack  
- **Frontend:** React, Redux Toolkit, Redux Thunk, MUI, CSS Modules  
- **Backend:** Node.js, Express, MySQL  
- **Other:** Custom Hooks (useFetch, usePagination), JWT Auth, REST API  

<p align="left">
  <img src="https://github.com/katroienko/pet-shop-frontend/blob/master/petPhoto/1.jpg?raw=true" width="200" title="Pet Shop Screenshot">
  <img src="https://github.com/katroienko/pet-shop-frontend/blob/master/petPhoto/2.jpg?raw=true" width="200" title="Pet Shop Screenshot">
  <img src="https://github.com/katroienko/pet-shop-frontend/blob/master/petPhoto/3.jpg?raw=true" width="200" title="Pet Shop Screenshot">
  <img src="https://github.com/katroienko/pet-shop-frontend/blob/master/petPhoto/4.jpg?raw=true" width="200" title="Pet Shop Screenshot">
  <img src="https://github.com/katroienko/pet-shop-frontend/blob/master/petPhoto/5.jpg?raw=true" width="150" title="Pet Shop Screenshot">
</p>

# [animal-eshop-backend_final_NODE.JS](https://github.com/katroienko/animal-eshop-backend_final_nodeJS/tree/main) 
<p align="left">
   <a href="https://github.com/katroienko/animal-eshop-backend_final_nodeJS/tree/main" target="_blank" style="text-decoration:none;">
    <button style="padding:10px 20px; font-size:16px; cursor:pointer;">Look Back-End code</button>
  </a>
    &nbsp;&nbsp;
  <a href="https://github.com/katroienko/pet-shop-frontend/tree/master" target="_blank" style="text-decoration:none;">
    <button style="padding:10px 20px; font-size:16px; cursor:pointer;">Look Front-End code</button>
  </a>
</p>
## 🚀 Tech Stack

- **Node.js** + **Express.js** — RESTful API
- **MongoDB** + **Mongoose** — remote database
- **WebSocket** — real-time communication
- **jsonwebtoken (JWT)** — token-based authentication
- **bcrypt** — secure password hashing
- **multer** — file/image upload
- **cors** — cross-origin requests
- **dotenv** — environment variable management

---

## 🔐 Authentication & Roles

- JWT-based login and registration
- Role-based access control:
  - `superadmin`
  - `admin`
  - `manager`
  - `user`
- Middlewares:
  - `authenticate` — validates JWT
  - `isSuperadmin` — restricts access to superadmins

  <p align="left">
   <a href="https://github.com/katroienko/animal-eshop-backend_final_nodeJS/blob/main/README.md" target="_blank" style="text-decoration:none;">
    <button style="padding:10px 20px; font-size:16px; cursor:pointer;">CONTINUE TO READ IN FILE README.md</button>
  </a>
  </p>

# [PUMB Online](https://apps.apple.com/ua/app/пумб-online/id1373626840) 
<p align="left"> <a href="https://apps.apple.com/ua/app/пумб-online/id1373626840" download><img src="https://user-images.githubusercontent.com/33416429/180564545-32e7e42c-7ded-4f52-81d6-9989b16cc4a3.png" width="170" ></a>
</p>

* PUMB Online - A native iOS online banking app which helps people to manage their finance
* PUMB Online has more than 1 000 000 users, #5 finance app in Ukrainian AppStore, rating 4.8. Crash free users - 99.89 %

<p align="center">
<img src="https://user-images.githubusercontent.com/33416429/93138739-516e5780-f694-11ea-8578-3f16db1bc263.png" width="930" title="PUMBOnline">

# [Straight Ur Back](https://apps.apple.com/us/app/id1531009911) 
<p align="left"> <a href="https://apps.apple.com/us/app/id1531009911" download><img src="https://user-images.githubusercontent.com/33416429/180564545-32e7e42c-7ded-4f52-81d6-9989b16cc4a3.png" width="170" ></a>
</p>
Straight Ur Back is an application that reminds you to keep your back straight. You can choose a time interval and how often you want to receive notifications. 

* MVP (Model-View-Presenter) architecture
* Firebase Analytics
* UserDefaults
* Local Notifications
* Fully programmatically UI 

<p align="center">
<img src="https://user-images.githubusercontent.com/33416429/92800949-05f13c00-f36a-11ea-8d58-513b0d759c96.jpg" width="230" title="StraightUrBack">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/33416429/92800926-02f64b80-f36a-11ea-9213-904f52359a83.jpg" width="230" title="StraightUrBack">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/33416429/92800943-0558a580-f36a-11ea-94b6-15d054a5e51f.jpg" width="230" title="StraightUrBack">

</p>



## Thanks for stopping by!

# Contact Info:

- Email: roienkokateryna@gmail.com
- LinkedIn: [decodealex](https://www.linkedin.com/in/kateryna-roienko/) 
