import { initializeApp } from "firebase/app";
import { getFirestore, collection } from "firebase/firestore";

const firebaseConfig = {
    apiKey: "AIzaSyBocJ9h3a8iee3sN55NeBmDWso5LUtk-TA",
    authDomain: "react-n-c69fe.firebaseapp.com",
    projectId: "react-n-c69fe",
    storageBucket: "react-n-c69fe.appspot.com",
    messagingSenderId: "251776740412",
    appId: "1:251776740412:web:5a79db5498c6d10dc32739"
};

const app = initializeApp(firebaseConfig);
export const db = getFirestore(app)
export const notesCollection = collection(db, "notes")