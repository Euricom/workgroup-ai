# Demo Prompts

## DeepSeek privacy Policy

```
Kan je nakijken of er privicy problemen zijn met volgende policy
https://chat.deepseek.com/downloads/DeepSeek%20Privacy%20Policy.html
```

## Reasoning challange

```
A train leaves New York at 8:00 AM traveling west at 60 mph. Another train leaves Los Angeles at 6:00 AM traveling east at 70 mph on the same track. If the distance between New York and Los Angeles is 2,800 miles, at what time will the two trains meet?
```

```
If all wibbles are wobbles, and all wobbles are wubbles, can we conclude that all wibbles are wubbles? Explain your reasoning.
```

## Using AI in the workplace

```
What are the potential risks and disadvantages of blocking AI usage within a company? Provide a detailed analysis of how restricting AI access could negatively impact productivity, innovation, and competitiveness. Additionally, offer a structured argument with key points and strategies to help convince company management to invest in AI and implement controlled access rather than an outright ban. Keep your response concise and focused on the most critical aspects.
```

Alternative add 

```
Include real-world examples, case studies, or data-driven insights to strengthen the argument. Provide references or citations where possible.
```

## Helper prompts

```
Generate a cheat sheet for JavaScript array methods.

Can you create a cheat sheet for SQL commands?

Create a cheat sheet for JavaScript regular expressions with common patterns and syntax.

I need a cheat sheet for React component lifecycle methods and their usage.

Give me a list of essential commands for managing a Kubernetes cluster

Give me the frequently used queries for querying a PostgreSQL database with Prisma

What are the most common CSS grid commands?
```

## Sorting package

```
Write a TS function to sort a array of objects. I want to use a string expression to specify the property & it should allow nested objects. Finally create all the supporting files so its a full package that I can publish to npm. Add unit tests with vitest. Add a readme that explains the usages. Add a changelog system based on changeset to release it. Present everything in a canvas (ChatGPT only)
```

## Rest API (Simple)

```
Within express (v4.x), create an endpoint for users and add the default CRUD methods. Make the endpoint handlers async and user express-async-errors to handle error globally, add Zod input validation for body and params. Use mock data for demonstration. 
```

## Rest API (Advanced)

```
ROLE: You are a backend developer specializing in Node.js and Express.

CONTEXT: You are building a REST API using Express.js. Your task is to create an endpoint for managing users, implementing full CRUD (Create, Read, Update, Delete) functionality. To ensure reliability and maintainability, you will:
- Use **async/await** in all route handlers.
- Handle errors globally using **express-async-errors**.
- Validate request parameters and body data using **Zod**.

REQUEST:  
1. **Create an Express route for users (`/users`).**  
2. **Implement CRUD operations** (`GET`, `POST`, `PUT`, `DELETE`) with async handlers:
   - `GET /users` → Fetch all users  
   - `GET /users/:id` → Fetch a single user by ID  
   - `POST /users` → Create a new user  
   - `PUT /users/:id` → Update an existing user  
   - `DELETE /users/:id` → Delete a user  
3. **Apply input validation with Zod:**  
   - Validate request **body** for `POST` and `PUT` requests.  
   - Validate request **params** (e.g., `id` should be a valid UUID or number).  
4. **Ensure proper error handling:**  
   - Use `express-async-errors` to catch and handle errors globally.  
   - Return appropriate HTTP status codes and error messages.  

LIMITATIONS:  
- Do not use any database; mock data can be used for demonstration.  
- Use TypeScript only.  
- Ensure code is modular and well-structured.  

OUTPUT FORMAT OF THE RESPONSE:  
Provide a **fully functional Express.js code snippet** implementing the requested features. The code should be properly structured, commented, and easy to understand.
```

## Build a ChatGPT-style Local Ollama Chat Website using HTML, CSS, and JavaScript

```
# Build a ChatGPT-style Local Ollama Chat Website using HTML, CSS, and JavaScript

## Core Requirements

### 1. **Model Selector**
- **Dropdown Menu (top-left):**
  - **Live Model Fetch:** Automatically populate the dropdown by making a **real API request** to the proxy endpoint at `http://localhost:3000/api/tags`. This is critical because our proxy forwards requests to the Ollama API (running on port 11434) while injecting the required CORS headers.
  - **Display Details:** For each model, display its name along with available details such as version or size.
  - **Refresh Functionality:** Include a refresh button that calls the model endpoint again to update the model list in real time.
  - **Visual Feedback:** Show a loading indicator during the API call and while switching between models.
  - **User-Friendly Messaging:** If no models are available, display a clear message.

### 2. **Chat Interface**
- **Message Display:**
  - **User Messages:** Display user messages right-aligned with a light background.
  - **Bot Responses:** Display bot responses left-aligned with a dark background.
  - **Markdown & Syntax Highlighting:** Render messages using Markdown and apply syntax highlighting to code snippets.
  - **Streaming Responses:** Stream bot responses word-by-word with a smooth animation. **All API requests should be directed to `http://localhost:3000`**, where the proxy will forward the request to the Ollama API.
  - **Hover Actions:** Implement hover actions on messages for options such as “Copy” or “Regenerate” (which triggers a new API call).

- **Input System:**
  - **Text Input:** Provide a centered, bottom-aligned textarea that expands from 1 to 6 lines as needed.
  - **Sending Options:** Allow sending messages via Enter or Ctrl+Enter (based on a toggle).
  - **Stop Generation:** Display a “Stop” button while the bot is generating a response to allow immediate cancellation.

- **New Chat Button:**
  - **Purpose:** Include a dedicated "New Chat" button that, when clicked, will clear the current chat conversation. This allows the user to start a fresh conversation without any previous message history crowding the chat area.
  - **Behavior:** Clicking the "New Chat" button should reset the state of the chat interface (e.g. clear the message display and reset any conversation-specific state variables) and optionally archive or save the current conversation if needed.

### 3. **Chat History**
- **Sidebar Organization:**
  - **Collapsible Panel:** Include a collapsible left sidebar to organize conversations chronologically.
  - **Conversation List:** Display a list of past conversations with options to search/filter them.
  - **Chat Actions:** Allow renaming, deleting, or archiving of conversations.
  - **New Chat Integration:** The "New Chat" button in the chat interface should allow users to begin a new conversation while keeping the previous conversations saved in this sidebar.

- **Data Persistence:**
  - **LocalStorage & IndexedDB:** Use LocalStorage for recent history and IndexedDB for larger datasets.
  - **Auto-Save:** Automatically save the current conversation every 15 seconds.
  - **Export/Import:** Provide functionality to export chat history as a JSON file and import it back.

## Important Notes

- **Proxy Setup:**  
  The proxy is already built and running on port 3000. Because the Ollama API does not include the required CORS headers, all API calls must be directed to this proxy. The proxy forwards these requests to the Ollama API instance running on port 11434, ensuring cross-origin requests are properly allowed by your browser.

- **API Endpoints:**  
  For example:
  - Fetching models should use: `http://localhost:3000/api/tags`
  - Chat interactions should be conducted through endpoints like `http://localhost:3000/api/chat`

By following these instructions, you'll be using the already built proxy to seamlessly handle CORS issues while communicating with your local Ollama API, and users will be able to create new chats easily using the dedicated "New Chat" button.
```