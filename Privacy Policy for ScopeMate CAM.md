<h1>Privacy Policy — ScopeMate CAM</h1>

<p><strong>Effective date:</strong> July 18, 2026<br>
<strong>Application:</strong> ScopeMate CAM (Package name: <code>com.hawel.scopematecam</code>)<br>
<strong>Developer:</strong> ScopeMate</p>

<p>This Privacy Policy describes how the ScopeMate CAM mobile application ("the App", "we", "us") handles information when you install and use the App. By downloading, installing, or using the App, you agree to the practices described in this Privacy Policy.</p>

<h2>1. Summary</h2>
<p><strong>The ScopeMate CAM App does NOT collect, store, or transmit any personal data or device data to the developer or to any third-party server.</strong> The App is a companion controller for your ScopeMate camera. All communication performed by the App happens directly between your mobile device and your own camera over your local network (Wi-Fi, USB, Bluetooth, or NFC). The App does not send any data to us or to any external service.</p>

<h2>2. Data We Do NOT Collect</h2>
<p>The App does <strong>not</strong> collect, transmit, or share any of the following:</p>
<ul>
  <li>Personally identifiable information (name, email, phone number, account credentials)</li>
  <li>Device identifiers (IMEI, MEID, Android Advertising ID, serial number, MAC address)</li>
  <li>Precise or coarse location (GPS coordinates, latitude/longitude)</li>
  <li>Contacts, messages, call logs, or browsing history</li>
  <li>Usage analytics, behavioural statistics, or crash reports sent to external servers</li>
  <li>Photos or videos captured by the camera — these are stored only on your phone's local gallery and never uploaded anywhere by the App</li>
</ul>

<h2>3. Data Flow — Device to Camera Only</h2>
<p>The App communicates exclusively with the camera you own and have connected to:</p>
<ul>
  <li><strong>Control commands</strong> (e.g. take photo, start/stop recording, change settings) are sent from your phone to the camera over local Wi-Fi / USB / Bluetooth / NFC.</li>
  <li><strong>Media</strong> (photos, videos, live preview stream) is received from the camera and saved into your phone's local gallery, or displayed on your screen.</li>
  <li><strong>Wi-Fi credentials</strong> that you enter to pair with the camera (the camera's Wi-Fi hotspot password) are stored locally on your phone only and are never transmitted anywhere except to the camera during pairing.</li>
</ul>
<p>None of this data leaves your device other than to your own camera over your local network.</p>

<h2>4. Permissions Used by the App</h2>
<p>The App requests the following permissions to provide its core functionality. Each permission is used only for the purpose described below.</p>
<table>
  <tr><th>Permission</th><th>Purpose</th><th>Required?</th></tr>
  <tr><td>Internet / Network &amp; Wi-Fi state</td><td>Communicate with your camera over the local Wi-Fi network</td><td>Required (core function)</td></tr>
  <tr><td>Change Wi-Fi / network state</td><td>Connect your phone to the camera's Wi-Fi hotspot</td><td>Required</td></tr>
  <tr><td>Location (coarse &amp; fine)</td><td><strong>Read the connected Wi-Fi network name (SSID) only</strong>, so the App can recognise when your phone is connected to the camera. <strong>No GPS coordinates are read; no location is tracked.</strong> Android requires location permission to return the real SSID since version 8.1.</td><td>Required (Android 8.1+)</td></tr>
  <tr><td>Camera</td><td>Scan the QR code printed on the camera body during pairing (optional — manual entry also available). The App does not record or save any imagery.</td><td>Optional</td></tr>
  <tr><td>Bluetooth (connect / scan)</td><td>Pair with the camera over Bluetooth during initial Wi-Fi setup. Bluetooth scan results are not used for location.</td><td>Required for Bluetooth pairing</td></tr>
  <tr><td>NFC</td><td>Tap-to-pair with the camera. Only reads the Wi-Fi credentials encoded in the camera's NFC tag.</td><td>Optional</td></tr>
  <tr><td>Photos &amp; Videos (Media access)</td><td>Save photos/videos downloaded from the camera into your gallery, and browse locally stored media for playback</td><td>Required</td></tr>
  <tr><td>Microphone / Audio</td><td>Play audio from the camera's live preview and recordings through your phone's speaker</td><td>Required for audio playback</td></tr>
  <tr><td>Wake lock / Vibrate</td><td>Keep the screen on during preview; provide touch feedback</td><td>Required</td></tr>
</table>

<h2>5. Third-Party SDKs</h2>
<p>The App does <strong>not</strong> integrate any advertising, analytics, crash-reporting, or tracking SDK that collects or transmits user data to external servers. Specifically:</p>
<ul>
  <li><strong>No advertising SDKs</strong> (no AdMob, Facebook Audience Network, etc.)</li>
  <li><strong>No analytics SDKs</strong> (no Firebase Analytics, Google Analytics, or equivalent)</li>
  <li><strong>No crash-reporting SDKs</strong> (the previously integrated Tencent Bugly SDK has been removed from this release)</li>
  <li><strong>No login / authentication SDKs</strong> (the previously integrated Google Sign-In and Facebook Login SDKs have been removed)</li>
  <li>The libraries that remain in the App (image loading, HTTP transport, UI widgets) operate entirely locally and do not transmit any data off the device.</li>
  <li><strong>Camera SDK (iCatchtek):</strong> The App integrates the iCatchtek camera SDK to communicate with and control your camera. iCatchtek supplies the camera's chipset and SDK and acts as a technology provider only — it is <strong>not</strong> the developer or data controller of this App. The SDK operates strictly locally: it exchanges data only between your phone and your own camera over the local network (Wi-Fi/USB/Bluetooth/NFC) and does not transmit any data to iCatchtek or any external server.</li>
</ul>

<h2>6. Data Storage on Your Device</h2>
<ul>
  <li><strong>Downloaded media</strong> (photos, videos from the camera) are saved into your phone's public gallery under <code>DCIM/ScopemateCam/</code>.</li>
  <li><strong>Camera pairing information</strong> (the camera's Wi-Fi SSID and password) is stored in the App's private local storage and is never shared.</li>
  <li><strong>Diagnostic logging</strong> is disabled by default. When manually enabled by the user, logs are written to the phone's local storage only and are never transmitted anywhere.</li>
  <li>The App opts out of Android's cloud backup — no App data is backed up to Google Drive or transferred between devices.</li>
</ul>

<h2>7. Children's Privacy</h2>
<p>The App is a hardware-companion tool intended for general audiences. It is not directed at children under 13, does not collect any personal information from anyone, and does not offer any in-app purchase, advertising, or user-generated content. The App is tagged as "not targeted at children" in the Google Play Store.</p>

<h2>8. Data Security</h2>
<p>Because the App does not collect or transmit any personal data off your device, there is no external data store to protect. Communication between your phone and your camera uses the camera vendor's protocol over your local network; when the camera's protocol uses unencrypted transport, this traffic stays within your local network and does not traverse the public internet.</p>

<h2>9. Your Rights</h2>
<p>Since the App collects no personal data and shares nothing with external parties, there is no personal data held by us to access, correct, export, or delete. The camera media and pairing information stored on your phone remain under your full control — you can delete them at any time through the App or your phone's standard gallery and App settings, and uninstalling the App removes all locally stored App data.</p>

<h2>10. Changes to This Privacy Policy</h2>
<p>We may update this Privacy Policy from time to time. Any changes will be posted to this page with an updated effective date. Continued use of the App after changes constitutes acceptance of the revised policy.</p>

<h2>11. Contact Us</h2>
<p>If you have any questions about this Privacy Policy or the App's data practices, please contact:</p>
<p>
  Developer: ScopeMate<br>
  Email: <code>823864766@qq.com</code>
</p>

<p><em>
  © 2026 ScopeMate. This Privacy Policy is provided for the ScopeMate CAM application.
</em></p>
