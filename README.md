# Mobile-Chatbot-System
Advanced Mobile Product Analysis and Interactive Chatbot System


## Project Overview:
In this project, students will undertake a comprehensive project that involves sophisticated web
scraping of mobile products from daraz.pk, data storage, and the development of an advanced
chatbot. The project will focus on extracting detailed information about mobile products, creating
an intelligent chatbot for user interaction, and presenting the data through an insightful and
interactive dashboard.

### Key Tasks:

### ● Web Scraping:

○ Objective: Extract mobile product data from daraz.pk, from the first five pages.
○ Example: Using Selenium or BeautifulSoup, you would write a script to navigate
to the mobile phone section of daraz.pk. Your script would then parse through
the HTML of each page, extracting product details like name, price, brand, and
reviews. For instance, if a product is named "Samsung Galaxy S21," your script
would extract its price, specifications, and user reviews.
○ Extract essential information such as product ID, name, price, and company.
○ Extract reviews for each product, including review ID, score, and content.
○ Store product details and reviews in separate files (excel or csv), uniquely
identifying with an id
○ Key Focus: Filtering out irrelevant products. You could achieve this by setting
conditions to exclude listings that contain keywords like "case," "cover," or
"charger."

### ● Database Integration:

○ Objective: Create a structured storage system for the scraped data.
○ Example: If using MySQL, you would design tables such as Products (storing ID,
name, price, brand) and Reviews (storing review text, rating, associated product
ID). This allows for efficient querying and analysis of data.
○ Key Focus: Ensure the database schema is robust enough to handle various
types of data and queries, such as retrieving all products within a certain price
range or the average rating of a brand.

### ● 3. Chatbot Development:

○ Objective: Develop a chatbot that can handle user queries based on the scraped
data.
○ Example: If a user asks, "What is the best phone under $300?" your chatbot,
using the stored data, should be able to analyze and respond with options like
"Based on user ratings and price, the best phones under $300 are [Product A],
[Product B]."
○ Key Focus: Implement natural language processing (NLP) capabilities for the
chatbot to understand and accurately respond to complex queries.