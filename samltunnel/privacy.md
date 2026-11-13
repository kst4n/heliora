# SAMLTunnel Privacy Policy

Effective date: [13 November 2026]

SAMLTunnel ("the app") is developed by Heliora ("we", "us"). This policy explains what happens to your information when you use the app.

## Summary
SAMLTunnel does not collect, store, sell or share any personal data. There are no ads, no analytics, no tracking and no user accounts. We do not operate any servers that the app connects to.

## What the app stores on your device
- VPN profiles you import (.ovpn files), including server addresses, certificates and keys, and the names you give them.
- A connection log used for troubleshooting.
- App settings.

This information stays in the app's private storage on your device. It is never sent to us. You can delete it by removing a profile in the app, clearing the app's data, or uninstalling the app.

## Network connections
- **VPN traffic:** When you connect, your traffic is sent through an encrypted tunnel directly to the AWS Client VPN endpoint configured in your profile. That endpoint is run by your organisation, not by us. Your organisation's own policies govern what it logs.
- **Single sign-on:** Sign-in happens in your browser with your organisation's identity provider (for example Microsoft Entra ID or Okta). The app receives the sign-in result through a temporary connection on your own device (127.0.0.1). We never see your username, password or sign-in tokens.
- **Device information sent to the VPN endpoint:** As part of the standard OpenVPN protocol, the app tells your organisation's VPN endpoint its name and version and your Android version, and may send a device identifier. This is sent only to your organisation's endpoint, never to us.

## Sharing logs
The app never sends logs automatically. If you choose to share the connection log (for example with your IT team), you pick the app and recipient. The log may contain server addresses, IP addresses and your username, so review it before sending.

## Permissions
- **VPN (VpnService):** to create the VPN tunnel. Android asks you to approve this the first time you connect.
- **Internet and network state:** to connect to your VPN endpoint and to reconnect when your network changes.
- **Notifications and foreground service:** to show the ongoing VPN connection status, as Android requires.

## Children
The app is intended for adults using their organisation's network. It is not directed at children under 13.

## Changes to this policy
If this policy changes, we will update this page and the effective date above.

## Contact
Heliora – kst4n.apps@gmail.com
