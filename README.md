# 💱 Currency Converter

A responsive web application that converts currencies in real time using live exchange rates. The application integrates a public exchange rate API and dynamically updates country flags, providing an intuitive and user-friendly currency conversion experience.


https://github.com/user-attachments/assets/83a8ad63-a4df-47b5-a585-f37ef881731c

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![API](https://img.shields.io/badge/REST-API-green)
![License](https://img.shields.io/badge/License-MIT-blue)
---

## Features

* Real-time currency conversion using live exchange rates.
* Supports a wide range of international currencies.
* Automatic country flag updates based on selected currencies.
* Interactive and responsive user interface.
* Input validation for user-entered amounts.
* Dynamic exchange rate display.
* Lightweight client-side implementation with JavaScript.

---

## Tech Stack

### Frontend

* **HTML5** – Structured the application's layout.
* **CSS3** – Designed a responsive and visually appealing interface.
* **JavaScript (ES6)** – Implemented application logic, DOM manipulation, and asynchronous API requests.

### APIs

* **Currency API** – Retrieves live exchange rates.
* **FlagsAPI** – Displays country flags corresponding to selected currencies.

---

## Project Structure

```text
Currency-Converter
│
├── index.html          # Main application interface
├── style.css           # Styling and responsive design
├── app.js              # Currency conversion logic
├── codes.js            # Currency-country mapping
├── exchange.png        # Exchange icon
└── README.md
```

---

##  Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/currency-converter.git
```

2. Navigate to the project folder

```bash
cd currency-converter
```

3. Open `index.html` in your browser.

No additional dependencies or installation are required.

---

## 📸 Screenshots

<img width="959" height="475" alt="image" src="https://github.com/user-attachments/assets/08f6c72a-a0f7-48f8-b0bc-d6a82f8c84cc" />
<img width="959" height="470" alt="image" src="https://github.com/user-attachments/assets/6c537bbd-6b1e-4148-bee8-d397c16e1e7c" />
<img width="959" height="476" alt="image" src="https://github.com/user-attachments/assets/a5518902-f396-4868-87ef-9f0e9020d20b" />


---

## How It Works

1. Enter the amount to convert.
2. Select the source currency.
3. Select the destination currency.
4. The application fetches the latest exchange rate from the Currency API.
5. The converted amount and current exchange rate are displayed instantly.

---

## Future Enhancements

* Currency swap button.
* Conversion history.
* Favorite currencies.
* Dark mode support.
* Offline caching of exchange rates.
* Exchange rate trend visualization.

---

# 🔐 Password Generator

A modern and responsive password generator built with React and Tailwind CSS that creates secure, customizable passwords instantly. Users can control password length, include numbers and special characters, and copy generated passwords to the clipboard with a single click.



https://github.com/user-attachments/assets/fe999444-3b61-420e-a28c-3b7334e932dd


![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue)
---

## Features

- Generate strong random passwords instantly
- Adjustable password length
- Option to include numbers
- Option to include special characters
- One-click copy to clipboard
- Responsive and modern user interface
- Real-time password regeneration when settings change

---

## Tech Stack

### Frontend

- **React.js** – Built reusable UI components and managed application state.
- **Vite** – Fast development environment and optimized production builds.
- **JavaScript (ES6+)** – Implemented password generation logic and application functionality.
- **Tailwind CSS** – Designed a responsive and modern user interface.
- **HTML5** – Structured the application.
- **CSS3** – Global styling and Tailwind integration.

### React Concepts

- **useState** – Managed password settings and generated password.
- **useEffect** – Automatically regenerated passwords when options changed.
- **useCallback** – Optimized function rendering.
- **useRef** – Enabled copy-to-clipboard functionality.

### Browser APIs

- **Clipboard API** – Copied generated passwords with a single click.

---

## Project Structure

```text
Password-Generator
│
├── node_modules/
├── public/
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── App.css
│   └── index.css
│
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/password-generator.git
```

2. Navigate to the project folder

```bash
cd password-generator
```

3. Install dependencies

```bash
npm install
```

4. Start the development server

```bash
npm run dev
```

5. Open the local development URL displayed in the terminal.

---

## 📸 Screenshots

<img width="521" height="335" alt="image" src="https://github.com/user-attachments/assets/08c4a9a3-c722-461d-aedf-d5e4359e3073" />
<img width="762" height="389" alt="image" src="https://github.com/user-attachments/assets/e1375a1e-8459-4e9a-97e7-daab73d4a241" />

---

## How It Works

1. Select the desired password length.
2. Choose whether to include numbers and special characters.
3. A secure random password is generated automatically.
4. Copy the password instantly using the **Copy** button.

---

## Future Enhancements

- Password strength indicator
- Exclude ambiguous characters (O, 0, l, I)
- Custom character sets
- Password history
- Dark/Light mode
- Password entropy calculation



## Author

**Vedika Gupta**

B.Tech CSE (Artificial Intelligence)

GitHub: https://github.com/vedikagupta890
