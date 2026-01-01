# Project Discontinued

# OtakuJin RPC App

This is the background application for **OtakuJin**, a companion app that allows users to interact with the OtakuJin website and use Discord RPC features to enhance their anime-watching experience. This app provides integration with Discord, enabling users to share their current activity on OtakuJin directly on their Discord profile.

## Features

- **Discord RPC Integration**: Displays what you're currently browsing on OtakuJin directly on your Discord profile.
- **Cross-Platform Support**: Available for **Linux**, **Windows**, and **macOS**.
- **Easy Setup**: Simple to install and run, no complex setup required.
- **Local Server Communication**: The app communicates with a local Go server running on your machine.


> The app requires a local server running on **port 8080** to function properly. You can confirm the server is running by pinging the `/ping` route.

### Installation


1. Download the `.zip` release for your system.
2. Extract the contents to a folder of your choice.
3. Run the application: Just a click.

#### How It Works
- Local Server: The app connects to a local Go server running on port 8080. You can confirm the server is up by pinging http://localhost:8080/ping.
- Discord RPC: Once the app is running and the local server is connected, it will update your Discord profile to show the current activity you're browsing on OtakuJin.

#### Troubleshooting
1. If the app isn't running:
The Go server needs to be running on port 8080. Ensure the server is active by pinging http://localhost:8080/ping.
2. If RPC is not displaying the activity:
Check the inspect tab in your browser's developer tools to see if the request to the RPC server is being blocked.
If blocked, disable any ad blockers or exclude the OtakuJin site from being blocked by them.
