# 📚 Book Recommendation Chatbot using IBM Watson Assistant

This is a smart and interactive chatbot built using **IBM Watson Assistant** that recommends books to users based on their preferred genre.

---

## 🔍 Features

- Understands user queries for book recommendations  
- Supports multiple genres (mystery, romance, horror, sci-fi, fiction, and more)  
- Provides curated book suggestions for each genre  
- Friendly conversational flow using intents, entities, and dialog nodes  
- Easy to extend with more books or genres  

---

## 🛠️ Tech Stack

- IBM Watson Assistant (Dialog Skill)  
- Intents, Entities, and Dialog Nodes  
- Optional: Integration with website or messaging platforms  

---

## 🎯 Intents

| Intent Name           | Purpose                             |
|-----------------------|-------------------------------------|
| `#greet`              | Greetings like "hi", "hello"        |
| `#book_recommendation`| Asking for book suggestions         |
| `#thanks`             | User says thank you                 |
| `#goodbye`            | User ends the conversation          |

---

## 🧠 Entities

**Entity Name**: `@genre`  
**Example Values**: mystery, romance, horror, sci-fi, fiction, etc.

**Sample `@genre` value: `mystery`**  
- Synonyms: detective, suspense, whodunit, crime fiction

---

## 💬 Dialog Flow

1. Bot greets the user  
2. User asks for a book (Intent: `#book_recommendation`)  
3. Bot asks for preferred genre if not mentioned  
4. User provides a genre (Entity: `@genre`)  
5. Bot recommends 5–10 books based on the genre  
6. Bot thanks or ends chat based on user input  

---

## 📚 Example Genres & Book Lists

### 🔍 Mystery
- *Gone Girl* – Gillian Flynn  
- *The Girl with the Dragon Tattoo* – Stieg Larsson

### 💕 Romance
- *The Notebook* – Nicholas Sparks  
- *It Ends With Us* – Colleen Hoover

### 🚀 Sci-Fi
- *Dune* – Frank Herbert  
- *The Martian* – Andy Weir

### 👻 Horror
- *It* – Stephen King  
- *Dracula* – Bram Stoker

### 🧠 Fiction
- *The Midnight Library* – Matt Haig  
- *The Kite Runner* – Khaled Hosseini

---

## 👨‍💻 Developed By

**Akshat Singh**  
Student Intern  
Book Recommendation Chatbot Project using IBM Watson Assistant  
📧 Email: akshatsingh26072005@gmail.com
