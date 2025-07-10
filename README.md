# LawEase (Ongoing)

A huge percentage of rural residents in India face a significant, often overlooked challenge: dealing with legal issues in their daily lives, professional spheres, and communities. Often, they lack awareness of the legal solutions available. To address this, we've created a user-friendly platform to help them navigate these complexities.

## Project Overview
LawEase is designed to make legal information and solutions accessible to everyone, especially those in rural areas. Our platform categorizes legal problems into clear sections and subcategories, making information easy to find. We present relevant laws and legal firms in simple language, including regional languages, and provide video summaries for further clarity. Additionally, we connect users with lawyers for personalized advice and recommendations.

## Features
- **Categorized Legal Problems:** Legal issues are organized into clear sections and subcategories for easy navigation.
- **Simple Language:** All information is presented in easy-to-understand language, with support for regional languages.
- **Video Summaries:** Key legal topics and solutions are explained through short, informative videos.
- **Lawyer Connect:** Users can connect with lawyers for personalized advice and recommendations.
- **Legal Firm Listings:** Find and contact legal firms relevant to your needs.

## Tech Stack
LawEase is built using the MERN stack:
- **MongoDB:** Database for storing user, lawyer, and legal information.
- **Express.js:** Backend framework for building RESTful APIs.
- **React.js:** Frontend library for building a responsive and interactive user interface.
- **Node.js:** Runtime environment for the backend server.

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/echoAbhinav/LawEase.git
   ```
2. **Install dependencies:**
   - For frontend:
     ```bash
     cd frontend
     npm install
     ```
   - For backend:
     ```bash
     cd backend
     npm install
     ```
3. **Run the project:**
   - Start frontend:
     ```bash
     npm start
     ```
   - Start backend:
     ```bash
     npm start
     ```

## Web Flow

```mermaid
flowchart TD
    A[1. Terms & Conditions / Agree & Continue] --> M[1(a). Landing Page]
    M --> B[2. Login / Register]
    B --> C[3. Home / Main Page]
    C --> D[3(a). Search Major Category Issue]
    D --> D1[Subcategories]
    D1 --> D2[i. Multi-Regional Language Solutions]
    D1 --> D3[ii. Video Content]
    D1 --> D4[iii. Find a Lawyer]
    D4 --> D5[Payment Gateway]
    C --> E[3(b). Chat-Bot]
    C --> F[3(c). FAQ]
    C --> G[3(d). About Us / Contact Us]
    C --> H[3(e). Newsletter]
    C --> I[3(f). User Dashboard]
    I --> J[Profile Management]
    I --> K[Saved Solutions]
    I --> L[Support / Helpdesk]
```

### Flow Description
1. **Terms & Conditions:** Users must agree before accessing the website.
2. **Landing Page:** The first page users see, introducing the platform and its benefits.
3. **Login/Register:** Secure authentication for new and returning users.
4. **Home/Main Page:** Central hub for all features.
   - **Search Major Category Issue:** Find legal topics, explore subcategories.
     - Solutions in multiple regional languages
     - Video content for clarity
     - Find and connect with lawyers (with payment gateway)
   - **Chat-Bot:** Get instant answers and guidance.
   - **FAQ:** Common questions answered.
   - **About Us/Contact Us:** Learn about the platform and reach out for support.
   - **Newsletter:** Stay updated with legal news and platform updates.
   - **User Dashboard:** Manage profile, saved solutions, and access support/helpdesk.

<img width="1918" height="864" alt="image" src="https://github.com/user-attachments/assets/bb085ac9-6703-4641-828a-50802130b2b3" />


## Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.

## Contact
For questions or support, please contact the project maintainer via GitHub Issues.
