# Lab 1: Node.js and Express Server

**Name:** E. Sriharsha

**Registration Number:** YOUR REGISTRATION NUMBER

**Section:** S-14

## Live Link

Not deployed yet. Running through GitHub Codespaces.

## Objective

To create a basic HTTP server using Node.js and develop a web server using Express.js.

## How to Run

1. Install Node.js.
2. Open the lab-01 folder.
3. Install dependencies:

```bash
npm install
```

4. Start the server:

```bash
node server.js
```

5. Open port 3000 in the browser.

## Endpoints

| Method | Path | Description |
|---|---|---|
| GET | / | Displays welcome message |
| GET | /about | Displays name and section in JSON |
| GET | /time | Displays current date and time |
| GET | /test | Displays 404 error message |

## Screenshots

### Home Route
![Home](screenshots/home.png)

### About Route
![About](screenshots/about.png)

### Time Route
![Time](screenshots/time.png)

### 404 Route
![404](screenshots/404.png)

## Notes

- Created a Node.js project using npm.
- Installed Express.js.
- Created a basic HTTP server.
- Developed an Express server.
- Implemented GET routes.
- Tested successful responses and 404 errors.

## Viva Questions

**1. Difference between package.json and node_modules?**

package.json stores project information and dependencies. node_modules contains installed packages.

**2. What does app.listen do?**

It starts the Express server on a specified port.
## Deployment link
https://lab1-mbwi.onrender.com/

**3. What are request and response?**

Request contains information sent by the client. Response contains information sent back by the server.
