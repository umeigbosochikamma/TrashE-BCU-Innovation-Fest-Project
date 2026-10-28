# TrashE: AI-Powered Smart Recycling Bin

🏆 **2nd Place, BCU Innovation Project Awards 2026**

TrashE is a smart bin that sorts waste for you. A camera spots your item and the bin opens the right lid. Students scan a QR code, earn points for recycling correctly, and swap them for rewards.

Built for the Steamhouse at Birmingham City University by a team of 5.

**Live website:** https://trashe.netlify.app

## How it works

1. Scan the QR code on the bin to link your account.
2. Put your item in front of the camera.
3. The bin opens the right lid: general, recycling or compost.
4. Earn points and track your impact on the website.

If the camera cannot identify an item, a barcode scanner is the backup.

## Features

- YOLOv8 computer vision to identify waste
- Three lids that open automatically
- Ultrasonic sensors to track how full the bin is
- Automatic bag sealing with a winch
- 10-inch touchscreen showing points and recycling tips
- QR-linked accounts, live bin monitor and rewards with four tiers
- Mobile friendly website

## AI model

Trained on 30+ types of waste, with multiple angles of each item and 10+ photos per angle. Accuracy: 86%.

## Tech stack

- **AI:** YOLOv8, Python
- **Hardware:** Raspberry Pi 5, Arduino Mega
- **Website:** HTML, CSS, JavaScript
- **Login and database:** Supabase
- **Hosting:** Netlify

## Team

The Plastics (D09), Birmingham City University
