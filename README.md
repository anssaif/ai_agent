# Ultravox Project

This project uses Express.js to handle incoming calls and integrates with the Ultravox API and Twilio for voice communication.

## Prerequisites

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/anssaif/ai_agent.git
    cd ultravox
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Create a [.env](http://_vscodecontentref_/0) file in the root directory and add your Ultravox API key:
    ```env
    ULTRAVOX_API_KEY=your_ultravox_api_key_here
    ```

## Usage

1. Start the server:
    ```sh
    npm start
    ```

2. The server will run on port 3000. You can change the port in the [server.js](http://_vscodecontentref_/1) file if needed.

## Project Structure

- [server.js](http://_vscodecontentref_/2): Main server file that handles incoming calls and integrates with Ultravox and Twilio.
- [.env](http://_vscodecontentref_/3): Environment variables file (not included in the repository).
- [.gitignore](http://_vscodecontentref_/4): Git ignore file to exclude [node_modules](http://_vscodecontentref_/5) and [.env](http://_vscodecontentref_/6) from the repository.

## Dependencies

- express
- https
- twilio
- dotenv

## License

This project is licensed under the MIT License.