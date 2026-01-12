![I Love You As A Service](src/main/resources/assets/skunk.png)

# I Love You As A Service 💕

An API that returns unconditional love - a SaaS (Software as a Service) that generates random, beautiful ways to say "I love you".

## 📖 About

**I Love You As A Service** is a Spring Boot REST API that provides over 250 unique and heartfelt ways to express love. Whether you need inspiration for a love letter, a sweet message for someone special, or just want to spread some love, this service has you covered.

From poetic expressions like *"You feel like home in every lifetime"* to simple declarations like *"I love you"*, each message is carefully crafted to convey genuine emotion and affection.

## ✨ Features

- 🎲 **Random Love Messages**: Get a randomly selected expression of love from a curated collection
- 💝 **250+ Unique Phrases**: A diverse collection ranging from poetic to heartfelt to simple expressions
- 🚀 **RESTful API**: Easy-to-use HTTP endpoints
- ⚡ **Fast & Lightweight**: Built with Spring Boot for optimal performance
- 🌍 **Always Available**: Stateless service ready to spread love 24/7

## 🛠️ Technology Stack

- **Java 21** - Modern Java platform
- **Spring Boot 4.0.1** - Application framework
- **Maven** - Dependency management and build tool

## 📋 Prerequisites

Before running this application, ensure you have:

- Java 21 or higher installed
- Maven 3.6+ installed (or use the included Maven wrapper)

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Lorieta/i-love-you-as-a-service.git
cd i-love-you-as-a-service
```

2. Build the project:
```bash
./mvnw clean install
```

3. Run the application:
```bash
./mvnw spring-boot:run
```

The application will start on `http://localhost:8080`

## 📚 API Usage

### Get a Random Love Message

```bash
curl http://localhost:8080/api/love
```

**Response Example:**
```json
{
  "message": "You are the warmth in my becoming"
}
```

## 💡 Example Messages

Here are some examples of the beautiful messages you might receive:

- *"You feel like home in every lifetime"*
- *"My soul recognizes yours"*
- *"You are where my heart rests"*
- *"My heart learned your name before I did"*
- *"You exist in every future I imagine"*
- *"You are the poetry I never learned to write"*
- *"I love you beyond words"*
- *"You're my favorite person"*
- *"My heart belongs to you"*

## 🏗️ Project Structure

```
i-love-you-as-a-service/
├── src/
│   ├── main/
│   │   ├── java/com/saas/iloveyouasaservice/
│   │   │   ├── ILoveYouAsAServiceApplication.java
│   │   │   └── api/
│   │   │       └── ways.json (250+ love messages)
│   │   └── resources/
│   │       ├── assets/
│   │       │   └── skunk.png (banner image)
│   │       └── application.properties
│   └── test/
├── pom.xml
└── README.md
```

## 🤝 Contributing

Contributions are welcome! If you have beautiful ways to express love that you'd like to add, feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/add-new-messages`)
3. Add your messages to `src/main/java/com/saas/iloveyouasaservice/api/ways.json`
4. Commit your changes (`git commit -m 'Add new love messages'`)
5. Push to the branch (`git push origin feature/add-new-messages`)
6. Open a Pull Request

## 📄 License

This project is open source and available for spreading love freely.

## 💌 Why This Exists

Sometimes we struggle to find the right words to express how we feel. This service exists to help you find those words - whether it's for a partner, family member, friend, or anyone who deserves to know they're loved.

Love is universal, and everyone deserves to hear it expressed beautifully.

---

Made with ❤️ by people who believe love should be easy to share
