# **sentiment-eval-frontend**

A modern frontend application for evaluating sentiment (Positive, Neutral, Negative) using a machine-learning or API-based sentiment analysis backend.
This project provides a clean UI for users to input text, view sentiment results, and visualize confidence scores.

---

## **🚀 Features**

* 📩 **User text input** for sentiment evaluation
* 🤖 **Integration with Sentiment Analysis API**
* 📊 **Confidence score visualization**
* ⚡ **Fast, responsive UI**
* 🎨 **Modern design (React/Tailwind recommended)**

---

## **📁 Project Structure (example)**

```
sentiment-eval-frontend/
│── public/
│── src/
│   ├── components/
│   ├── pages/
│   ├── api/
│   ├── App.js
│   ├── index.js
│── package.json
│── README.md
```

---

## **🛠️ Installation**

1. Clone the repository:

```bash
git clone https://github.com/yourusername/sentiment-eval-frontend.git
```

2. Navigate to project directory:

```bash
cd sentiment-eval-frontend
```

3. Install dependencies:

```bash
npm install
```

---

## **▶️ Running the Project**

For development:

```bash
npm start
```

The app will run on:

```
http://localhost:3000
```

For production build:

```bash
npm run build
```

---

## **🔌 API Configuration**

Create a `.env` file in the root directory:

```
REACT_APP_API_URL=http://localhost:5000/predict
```

The frontend will send POST requests like:

```json
{
  "text": "I love this product!"
}
```

---

## **📦 Example Expected API Response**

```json
{
  "sentiment": "Positive",
  "confidence": {
    "positive": 0.92,
    "neutral": 0.05,
    "negative": 0.03
  }
}
```

---

## **🧪 Running Tests (if added)**

```bash
npm test
```

---

## **🤝 Contributing**

Pull requests are welcome!
Please open an issue for suggestions or bug reports.

---

## **📄 License**

MIT License.

---

