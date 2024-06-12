
# FileTransfer

A simple web-based application for transferring files between devices on the same local network. The application uses WebSockets to synchronize file uploads across devices in real-time.

## Features

- Upload files from one device and download them on another device connected to the same local network.
- Real-time synchronization of file uploads using WebSockets.
- Simple and intuitive user interface.

## Prerequisites

- Node.js and npm installed on your machine.
- All devices should be connected to the same local network.

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/bangyizhang/FileTransfer.git
    cd FileTransfer
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

## Usage

1. Start the server:

    ```sh
    node server.js
    ```

2. Open the application in your browser:

    ```sh
    http://<your-local-ip>:3000
    ```

    Replace `<your-local-ip>` with your computer's local IP address.

3. Use the application to upload and download files between devices.

## Directory Structure

```
FileTransfer/
├── uploads/         # Directory to store uploaded files
├── index.html       # The main HTML file for the UI
├── server.js        # Node.js server script
├── package.json     # Project metadata and dependencies
└── README.md        # Project documentation
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any bugs or feature requests.

## License

This project is licensed under the MIT License.
