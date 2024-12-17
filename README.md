# screenshot: 
   ![WhatsApp Image 2024-12-17 at 7 58 36 PM](https://github.com/user-attachments/assets/e323e17d-b485-496c-81ab-cfbed2461b15)
![WhatsApp Image 2024-12-17 at 8 00 06 PM](https://github.com/user-attachments/assets/da550968-f12f-4aa7-8d34-380fd32b2ac4)

 ![WhatsApp Image 2024-12-17 at 8 00 28 PM](https://github.com/user-attachments/assets/635823eb-b194-47de-ac57-0a91bca57551)

 ##  CVE Management System
# Problem Statement:
         The CVE Management System (Securin) is a platform designed to manage, track, and display data on CVEs (Common Vulnerabilities and Exposures). 
         The system is built to fetch real-time data from the National Vulnerability Database (NVD) and display it in a user-friendly manner. 
         The primary goal of the project was to efficiently manage vulnerability information and allow users to interact with CVE data in a structured way.

# Approach
The project started with the aim of creating a responsive, scalable, and efficient application using the ReactJS framework for the frontend, Node.js and Express for the backend, 
and integrating real-time data from the NVD API. The data includes various details about vulnerabilities, such as descriptions, CVSS scores, exploitability, 
CPE (Common Platform Enumeration), and more.
I used Redux to manage the state of the application across different components. The project required frequent API calls, which I optimized using memoization techniques. 
Additionally, I added unit testing using Jest for critical components of the frontend.

# Tech Stack Used
     # Frontend:
        ReactJS: A JavaScript library for building user interfaces, ideal for creating interactive and dynamic components.
        Redux: For state management, ensuring that the data fetched from the backend is available to all components without excessive re-renders.
        Axios: Used for making HTTP requests to the backend API.
        HTML/CSS: For structuring and styling the frontend UI.

    # Backend:
         Node.js: A JavaScript runtime environment that allows running JavaScript on the server side.
         Express.js: A web framework for Node.js used to build the backend API endpoints.
         Axios: Used in the backend for making requests to the NVD API to fetch CVE data

# Optimization:
Memoization: Used to store results of API calls and prevent fetching the same data repeatedly, improving performance.
Redux: Helps to avoid redundant API calls by storing data globally in the application state, making the app more efficient.

# Testing:
Jest: A JavaScript testing framework used to write unit tests for the frontend components to ensure the functionality of critical sections like fetching and displaying data.

# Challenges Faced and Solutions: 
API Integration: One of the key challenges was integrating with the NVD API, ensuring that the data was parsed correctly, 
and implementing pagination to handle large amounts of CVE data. This was tackled by using pagination query parameters and storing only the relevant data.

State Management: As the project grew in size, managing state across multiple components became challenging. Using Redux simplified this by centralizing the state management and
ensuring that components could access the data easily without prop drilling.

# Conclusion
The CVE Management System project helped me to hone my skills in full-stack development. I worked extensively with ReactJS, Redux, Node.js, Express, and Axios to fetch and display data
from an external API. The project was optimized using memoization and Redux for efficient data handling. Jest was used for unit testing, ensuring the reliability of key components.
The project successfully meets its objective of fetching, displaying, and managing CVE data in a structured and user-friendly manner. 
The application can easily be scaled or modified to include additional features, such as filtering and searching CVEs, making it a robust solution for managing vulnerabilities.
