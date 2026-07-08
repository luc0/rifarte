// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBh4dvUzq7JyYV3dozcr-2W_FkJGJYCMIc",
  authDomain: "rifarte-69a3c.firebaseapp.com",
  projectId: "rifarte-69a3c",
  storageBucket: "rifarte-69a3c.firebasestorage.app",
  messagingSenderId: "796793970576",
  appId: "1:796793970576:web:fc8ee8cf7e2405d8429d15",
  measurementId: "G-YS2JLGXLJG"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
