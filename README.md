#  Real-Time Chat Application with Node.js and Socket.IO

This project is a simple yet powerful demonstration of a **real-time, multi-user chat application**. It utilizes the power of **WebSockets** via the **Socket.IO** library to establish a persistent, bidirectional connection between the client and the server, enabling instant message delivery.

-----

##  Features

  * **Real-Time Messaging:** Instantaneous message transmission and receipt for all connected users.
  * **Multi-User Support:** Easily handles multiple simultaneous connections.
  * **Join/Leave Notifications:** Alerts all active users when someone joins or leaves the chat.
  * **Bidirectional Communication:** Server and client can send (emit) or listen (on) for events at any time.
  * **Event-Driven:** Uses custom events like `send`, `receive`, and `new-user-joined` for clean, scalable logic.
  * **Client Interface:** Clean and responsive frontend design using HTML and CSS.
  * **Message Alert:** Plays a sound notification for incoming messages.

-----

##  Technologies Used

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Backend** | **Node.js** | JavaScript Runtime Environment for the server. |
| **Real-Time** | **Socket.IO** | Library for low-latency, two-way communication (WebSockets). |
| **Frontend** | **HTML5** | Structure and content of the chat interface. |
| **Styling** | **CSS3** | Styling and layout of the application. |
| **Logic** | **JavaScript** | Client-side logic and DOM manipulation. |

-----

## Prerequisites

Before running this project, ensure you have the following installed on your machine:

  * **Node.js** (LTS recommended)
  * **npm** (Node Package Manager)

-----

## Installation & Setup

Follow these steps to get the chat application running locally:

### 1\. Clone the Repository


### 2\. Install Dependencies

Navigate into the server folder and install the required packages (primarily **Socket.IO**):

```bash
npm install
```

### 3\. Start the Server

Run the main server file (`index.js`). The server will typically run on port `8000`.

```bash
node index.js
# OR, if you have nodemon installed:
nodemon index.js
```

The server is now running and waiting for client connections.

-----

## Usage

To use the chat application:

1.  **Open the Client:** Open the `index.html` file in your web browser.
2.  **Enter Name:** You will be prompted to enter a name. Use a unique name to join the chat.
3.  **Multi-User Simulation:** Open multiple browser tabs, windows, or even different browsers, and enter a different name in each to simulate several users chatting.
4.  **Chat:** Type a message in the input box and click **Send** or hit `Enter`.
      * Your sent messages will appear on the **right** side of your chat window.
      * Messages received from other users will appear on the **left** side of your chat window, accompanied by a notification sound.
