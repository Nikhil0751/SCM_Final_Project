URL of the repository : https://github.com/Nikhil0751/SCM_Final_Project.git

### Description ### 

This project, titled "The Replica of Google", aims to create a simplified version of the renowned Google search engine. The objective is to replicate core functionalities such as the search interface, query processing, and displaying search results, albeit on a much smaller scale. This educational project helps understand the basic workings of search engines and web indexing.

### Features ###

1. Search Functionality
   Keyword Search: Users can enter keywords or phrases to search for relevant web pages.
   Autocomplete Suggestions: As users type, the search bar provides real-time suggestions based on popular queries and the user's search history.
   Search Filters: Users can filter search results by various categories such as Web, Images, News, and Videos.
   Advanced Search Options: Provides options for refining searches with additional parameters such as date range, exact match, and excluding specific terms.
2. Search Results Page
   Relevance Ranking: Results are displayed based on their relevance to the search query using a custom ranking algorithm.
   Snippet Generation: Each result includes a snippet of text that gives a preview of the content on the web page.
   Pagination: Results are divided into multiple pages to improve navigation and readability.
   Related Searches: Suggests additional related search queries at the bottom of the results page.
3. Image Search
   Thumbnail Display: Search results for images are displayed as thumbnails.
   Image Filters: Users can filter images by size, color, type, and usage rights.
   Image Preview: Clicking on a thumbnail opens a larger preview of the image with additional information.
4. News Search
   Latest News: Displays the most recent news articles related to the search query.
   Source Filtering: Users can filter news results by source or publication date.
   Topic Categorization: News results are categorized into topics such as Politics, Technology, Sports, etc.
5. Video Search
   Video Thumbnails: Video search results are displayed with thumbnails and brief descriptions.
   Source Integration: Results include videos from various sources like YouTube, Vimeo, and other popular video platforms.
   Playback: Users can watch videos directly within the search results page without navigating to a different site.
6. User Interface
   Responsive Design: The site is designed to be responsive and works well on desktops, tablets, and mobile devices.
   Clean Layout: The interface is minimalist and user-friendly, similar to Google's clean and simple design philosophy.
   Dark Mode: Provides an option to switch to dark mode for a better user experience in low-light environments.
7. Backend and Performance
   Efficient Crawling: Implements an efficient web crawler that indexes web pages and stores relevant information for quick retrieval.
   Database Management: Uses a robust database system to manage indexed data and user queries efficiently.
   Scalability: Designed to handle a large number of simultaneous search queries with low latency.
8. Security and Privacy
   Data Encryption: Ensures that all user data and search queries are encrypted and transmitted securely.
   Privacy Policy: Clearly states the handling of user data and ensures user privacy is respected.
   Spam Filtering: Includes mechanisms to detect and filter out spam or malicious websites from search results.
9. Additional Tools
   Language Translation: Provides translation of search results and web pages in multiple languages.
   Voice Search: Allows users to perform searches using voice commands.
   Location-Based Search: Offers search results tailored to the user's location for more relevant information.
10. Analytics and Feedback
   Search Analytics: Tracks search trends and popular queries to improve the search algorithm.
   User Feedback: Provides options for users to give feedback on search results to continually improve the service.

### Dependencies ###

### Frontend
- HTML5: Markup language for structuring and presenting content.
- CSS3: Styling language for describing the presentation of the HTML.
- JavaScript: Programming language to create dynamic and interactive web content.
- Bootstrap: CSS framework for responsive design and pre-built components.
- jQuery: JavaScript library for simplifying HTML DOM tree traversal and manipulation.

### Backend
- Node.js: JavaScript runtime built on Chrome's V8 JavaScript engine.
- Express.js: Web application framework for Node.js.
- MongoDB: NoSQL database for storing search results and user data (if applicable).
- Mongoose: Object Data Modeling (ODM) library for MongoDB and Node.js.
- Body-Parser: Node.js middleware for parsing incoming request bodies.
- Axios: Promise-based HTTP client for the browser and Node.js, used for making API requests.

### Additional Tools
- Git: Version control system for tracking changes in the source code.
- npm (Node Package Manager): Package manager for JavaScript, included with Node.js.
- Webpack: Module bundler for JavaScript.
- Babel: JavaScript compiler for using next-generation JavaScript today.
- ESLint: Linting tool for identifying and fixing JavaScript code issues.

### Testing ###

### 1. Search Functionality
#### Test Case 1: Basic Search
- **Description:** Verify that entering a query in the search bar returns relevant results.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "OpenAI".
  3. Press the search button.
- **Expected Result:** A list of search results related to "OpenAI" should be displayed.

#### Test Case 2: No Results Found
- **Description:** Verify the system's response when no results are found for a query.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "qwertyuiopasdfghjklzxcvbnm".
  3. Press the search button.
- **Expected Result:** A message stating "No results found" should be displayed.

### 2. Advanced Search Options
#### Test Case 3: Search with Filters
- **Description:** Verify that applying filters narrows down the search results.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "Python programming".
  3. Apply filter for "Last year".
  4. Press the search button.
- **Expected Result:** Only results from the last year related to "Python programming" should be displayed.

#### Test Case 4: Search by File Type
- **Description:** Verify that searching for a specific file type returns the correct results.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "machine learning filetype:pdf".
  3. Press the search button.
- **Expected Result:** Only PDF files related to "machine learning" should be displayed.

### 3. Autocomplete Feature
#### Test Case 5: Autocomplete Suggestions
- **Description:** Verify that autocomplete suggestions appear as the user types a query.
- **Steps:**
  1. Open the homepage.
  2. Start typing "artificial intelligence".
- **Expected Result:** A dropdown with autocomplete suggestions related to "artificial intelligence" should appear.

### 4. User Interface
#### Test Case 6: Responsive Design
- **Description:** Verify that the website layout is responsive and adjusts to different screen sizes.
- **Steps:**
  1. Open the homepage on a desktop browser.
  2. Resize the browser window to various dimensions.
  3. Open the homepage on a mobile browser.
- **Expected Result:** The layout should adjust appropriately, maintaining usability and readability on all screen sizes.

#### Test Case 7: Search Button Functionality
- **Description:** Verify that the search button is clickable and initiates a search.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "blockchain".
  3. Click the search button.
- **Expected Result:** A list of search results related to "blockchain" should be displayed.

### 5. Performance
#### Test Case 8: Load Time
- **Description:** Verify that the search results page loads within an acceptable time frame.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "climate change".
  3. Press the search button.
- **Expected Result:** The search results page should load within 2 seconds.

### 6. Error Handling
#### Test Case 9: Network Error
- **Description:** Verify the application's response to a network error.
- **Steps:**
  1. Disable the internet connection.
  2. Open the homepage.
  3. Enter any query and press the search button.
- **Expected Result:** An error message indicating network issues should be displayed.

#### Test Case 10: Invalid Input
- **Description:** Verify the application's response to invalid input.
- **Steps:**
  1. Open the homepage.
  2. Enter special characters as a query (e.g., "!!!@@@###").
  3. Press the search button.
- **Expected Result:** A relevant error message or no results should be displayed, and the application should handle the input gracefully.

### Troubleshooting ### 

## Testing Cases

### 1. Search Functionality
#### Test Case 1: Basic Search
- **Description:** Verify that entering a query in the search bar returns relevant results.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "OpenAI".
  3. Press the search button.
- **Expected Result:** A list of search results related to "OpenAI" should be displayed.

#### Test Case 2: No Results Found
- **Description:** Verify the system's response when no results are found for a query.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "qwertyuiopasdfghjklzxcvbnm".
  3. Press the search button.
- **Expected Result:** A message stating "No results found" should be displayed.

### 2. Advanced Search Options
#### Test Case 3: Search with Filters
- **Description:** Verify that applying filters narrows down the search results.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "Python programming".
  3. Apply filter for "Last year".
  4. Press the search button.
- **Expected Result:** Only results from the last year related to "Python programming" should be displayed.

#### Test Case 4: Search by File Type
- **Description:** Verify that searching for a specific file type returns the correct results.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "machine learning filetype:pdf".
  3. Press the search button.
- **Expected Result:** Only PDF files related to "machine learning" should be displayed.

### 3. Autocomplete Feature
#### Test Case 5: Autocomplete Suggestions
- **Description:** Verify that autocomplete suggestions appear as the user types a query.
- **Steps:**
  1. Open the homepage.
  2. Start typing "artificial intelligence".
- **Expected Result:** A dropdown with autocomplete suggestions related to "artificial intelligence" should appear.

### 4. User Interface
#### Test Case 6: Responsive Design
- **Description:** Verify that the website layout is responsive and adjusts to different screen sizes.
- **Steps:**
  1. Open the homepage on a desktop browser.
  2. Resize the browser window to various dimensions.
  3. Open the homepage on a mobile browser.
- **Expected Result:** The layout should adjust appropriately, maintaining usability and readability on all screen sizes.

#### Test Case 7: Search Button Functionality
- **Description:** Verify that the search button is clickable and initiates a search.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "blockchain".
  3. Click the search button.
- **Expected Result:** A list of search results related to "blockchain" should be displayed.

### 5. Performance
#### Test Case 8: Load Time
- **Description:** Verify that the search results page loads within an acceptable time frame.
- **Steps:**
  1. Open the homepage.
  2. Enter the query "climate change".
  3. Press the search button.
- **Expected Result:** The search results page should load within 2 seconds.

### 6. Error Handling
#### Test Case 9: Network Error
- **Description:** Verify the application's response to a network error.
- **Steps:**
  1. Disable the internet connection.
  2. Open the homepage.
  3. Enter any query and press the search button.
- **Expected Result:** An error message indicating network issues should be displayed.

#### Test Case 10: Invalid Input
- **Description:** Verify the application's response to invalid input.
- **Steps:**
  1. Open the homepage.
  2. Enter special characters as a query (e.g., "!!!@@@###").
  3. Press the search button.
- **Expected Result:** A relevant error message or no results should be displayed, and the application should handle the input gracefully.

### Contributors ###

1. Nikhil Goyal - 2310990751 (nikhil0751.be23@chitkara.edu.in)
2. Nimarjot Kaur - 2310990752 (nimarjot0752.be23@chitkara.edu.in)
3. Nazuk -2310990750 (nazuk0750.be23@chitkara.edu.in)

We would like to extend our heartfelt gratitude to Chitkara University for providing us with the opportunity to work on this exciting project, "The Replica of Google." The resources, guidance, and support offered by the university have been instrumental in bringing this project to fruition.
We are particularly grateful to our professors and mentors, whose valuable insights and encouragement have been a driving force throughout this project. Their expertise and willingness to help us navigate through challenges have been invaluable.

Additionally, we appreciate the collaborative environment and the spirit of innovation fostered at Chitkara University, which has greatly contributed to our learning and development. This project has not only enhanced our technical skills but also our understanding of real-world applications and problem-solving.
Thank you, Chitkara University, for this incredible opportunity and for believing in our potential.

