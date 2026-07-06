# TEF6686 WebBLE Remote Controller

A sleek, responsive, zero-noise Web Bluetooth (WebBLE) controller for standalone TEF6686 DSP Receivers.

## 🚀 Quick Start
Once hosted on GitHub Pages (which provides the required **HTTPS** context for WebBluetooth to work on mobile browsers), you can access the remote controller by opening the hosted URL on any Android phone running Chrome or Edge.

1. Click **Connect**.
2. Select your **TEF6686_Radio** device from the bluetooth dialog.
3. Use the haptic-enabled jog-wheel dial, volume slider, preset buttons, and advanced DSP settings panel to control the radio wirelessly.

## 🔧 GitHub Pages Deployment
1. Create a repository named `tef6686-web-control` on GitHub.
2. Link this local repo and push:
   ```bash
   git remote add origin https://github.com/<YOUR-USERNAME>/tef6686-web-control.git
   git push -u origin main
   ```
3. In your repository on GitHub, navigate to **Settings** → **Pages**.
4. Select **Deploy from a branch** under Source.
5. Choose the **main** branch and `/ (root)` folder, then click **Save**.
6. The site will be live securely at `https://<YOUR-USERNAME>.github.io/tef6686-web-control/`!
