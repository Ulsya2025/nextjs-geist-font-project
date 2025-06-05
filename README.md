# Project Setup and Running Instructions

## Prerequisites
- Node.js (version 18 or later)
- npm (comes with Node.js)

## Running the Project Locally

1. Open a terminal and navigate to the project root directory (where `package.json` is located).

2. Install dependencies:
```
npm install
```

3. Start the development server:
```
npm run dev
```

4. Open your browser and go to:
```
http://localhost:8000
```

5. To access the server from other devices on your local network, start the server binding to all interfaces:
```
HOST=0.0.0.0 npm run dev
```
Then access the site via your machine's local IP address, e.g., `http://192.168.x.x:8000`.

## Notes
- Make sure you run the commands inside the project root folder where `package.json` is located.
- If you encounter errors related to missing files, verify that you have cloned or copied the entire project folder including `package.json`.

Feel free to reach out if you need further assistance.
