# Lower Sideband Support

Lower Sideband is a native Reticulum and LXMF messaging client for iPhone, iPad, and Mac. It requires iOS or iPadOS 17 or later, or macOS 14 or later.

## Getting connected

Lower Sideband uses automatic connection discovery by default:

1. It tries a specifically configured gateway when the user has selected one.
2. It discovers compatible gateways on the local network.
3. It falls back to public Internet Reticulum gateways when no local route is available.

Connection attempts happen in the background. Open **Network Status** in the app to see the active gateway, route state, reconnect history, and privacy-safe diagnostics.

## Messaging checklist

- Confirm the status indicator shows **Ready** or **Route available**.
- Verify the recipient's full LXMF destination address.
- Leave automatic connection enabled unless diagnosing a specific gateway.
- If a message remains queued, keep the app open briefly while it discovers a path or propagation node.
- Use **Retry failed messages** after changing networks.
- For attachments and voice calls, wait for an authenticated direct link.

Reticulum is delay tolerant. Delivery can take longer when a destination is offline, a path has expired, or a public gateway is congested.

## Identity and safety

The LXMF ID shown at the top of the main screen is the address to share with contacts. Compare identity fingerprints over a separate trusted channel before marking a contact as verified.

Use **Block Contact** to reject future inbound content from a destination. Use **Report Contact** or **Report Message** in the conversation actions to prepare a safety report. The report is shown as an email draft for review before you send it. Lower Sideband does not automatically include message text, attachments, telemetry, display names, contact notes, or cryptographic keys.

Lower Sideband is not an emergency service and should not be relied on for urgent, life-safety, medical, or emergency communications.

## Privacy and permissions

Camera, microphone, location, local-network, notification, iCloud, and device-authentication features are optional and controlled by the user. See the [Lower Sideband Privacy Policy](PRIVACY.md) for details.

## Contact support

When reporting a problem, include the app version, device model, operating-system version, what Network Status shows, and the privacy-safe diagnostics copied from the app. Do not send private identity keys or confidential message content.

Support and safety email: sepus@hotmail.com
