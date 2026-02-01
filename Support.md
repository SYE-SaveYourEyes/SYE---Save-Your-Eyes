# SYE - Save Your Eyes Support

Welcome to **SYE (Save Your Eyes)**, your companion app for healthier digital habits and eye care. This support guide will help you get the most out of the app.

## 📱 App Overview

SYE - Save Your Eyes is an iOS app designed to help you:
- **Protect your eyes** with the 20-20-20 Eye Rest rule

Upcoming (not available as of yet) :
- **Manage screen time** with Homework/Focus Mode for parental control
- **Track lifetime phone usage** to understand your digital habits

---

## ✨ Features

### 1. 20-20-20 Eye Rest
Follow the eye care rule: every 20 minutes, take a 20-second break to look at something 20 feet away.

**How to use:**
1. Tap "Start Session" on the 20-20-20 Eye Rest card
2. Select the apps/websites you want to rest from
3. Choose your interval (20, 30, or 40 minutes), rest duration (20, 40, or 60 seconds), and number of cycles
4. Tap "Start Session" to begin
5. The app will notify you when it's time to rest your eyes

**Active Session:**
- A green indicator shows when a session is active
- Cycle progress is displayed (e.g., "Cycle 1/3")
- You can stop the session anytime by starting a new one

### 2. Homework/Focus Mode (Upcoming)
Block all apps and websites except those you allow.

**How to use:**
1. Enable Screen Time permission (required)
2. Tap "Allowed Apps & Websites" to select which apps/websites are permitted
3. Tap "Start Homework Mode"
4. Choose duration (15 min, 30 min, 1 hour, 2 hours, or 3 hours max)
5. Tap "Start Homework Mode"
6. All apps except the allowed ones will be blocked until the session ends

**Features:**
- Maximum session duration: 3 hours
- Automatic blocking via Screen Time APIs
- Notifications when sessions start and end
- Session persists even if the app is closed

### 3. Expected Hours of Phone Use (Upcoming)
See how much of your lifetime you spend on your phone based on your weekly screen time.

**How to use:**
- The app attempts to fetch your weekly screen time automatically
- If unavailable, you can manually enter your weekly hours
- The card displays:
  - Your weekly screen time
  - The percentage of a 73.5-year lifespan spent on your phone

**Example:**
- 10 hours/week = approximately 5.96% of your life

---

## 🔐 Permissions

### Notifications
**Required for:** Eye rest reminders and session alerts

**How to enable:**
1. When prompted, tap "Allow"
2. Or go to Settings > SYE > Notifications > Enable notifications

**Why needed:** To remind you when to rest your eyes and alert you when sessions start/end.

### Screen Time (Family Controls)
**Required for:** Homework/Focus Mode

**How to enable:**
1. Tap "Enable Screen Time" when prompted
2. Follow the on-screen instructions
3. Grant permission in Settings if needed

**Why needed:** To block apps and websites during Homework Mode.

**Note:** This permission can only be granted once. If denied, go to Settings > Screen Time > Family Controls to enable.

---

## 🆘 Troubleshooting

### Notifications Not Working

**Problem:** I'm not receiving notifications for eye rest or sessions.

**Solutions:**
1. Check notification settings:
   - Settings > SYE > Notifications > Enable "Allow Notifications"
   - Ensure "Alerts" and "Sounds" are enabled
2. Check Do Not Disturb:
   - Settings > Focus > Ensure SYE is allowed during Focus modes
3. Restart the app:
   - Close the app completely and reopen it
4. Request permission again:
   - Open SYE > Permissions section > Tap "Enable Notifications"

### Screen Time Permission Issues

**Problem:** I can't enable Screen Time or Homework Mode isn't working.

**Solutions:**
1. Check if Screen Time is enabled:
   - Settings > Screen Time > Ensure Screen Time is turned on
2. Request permission again:
   - Open SYE > Permissions section > Tap "Enable Screen Time"
3. If permission was previously denied:
   - Settings > Screen Time > Family Controls
   - Remove SYE if listed, then grant permission again in the app
4. Restart your device:
   - Sometimes a restart helps refresh permission states

### Homework Mode Not Blocking Apps

**Problem:** Apps aren't being blocked during Homework Mode.

**Solutions:**
1. Ensure Screen Time permission is granted (see above)
2. Verify you've selected allowed apps:
   - Tap "Allowed Apps & Websites" before starting Homework Mode
   - At least one app/website must be selected
3. Check if session is active:
   - Look for the green "Active" indicator on the Homework Mode card
4. Test on a real device:
   - Some features may not work fully in simulator
   - Test on a physical iPhone/iPad

### 20-20-20 Session Not Working

**Problem:** The eye rest session isn't starting or notifications aren't coming.

**Solutions:**
1. Ensure you've selected apps/websites to rest from
2. Check notification permissions (see above)
3. Keep the app running or allow background app refresh:
   - Settings > General > Background App Refresh > Enable for SYE
4. Start a new session:
   - Stop any active session and start fresh

### App Crashes or Freezes

**Problem:** The app crashes or freezes.

**Solutions:**
1. Force close and restart:
   - Swipe up to close the app completely, then reopen
2. Restart your device
3. Update iOS:
   - Settings > General > Software Update
4. Reinstall the app:
   - Delete and reinstall from the App Store

### Screen Time Data Not Loading

**Problem:** Weekly screen time shows "Loading..." or manual input.

**Solutions:**
1. Wait a moment for data to load
2. Enter weekly hours manually:
   - The manual input will appear automatically if data isn't available
3. Check Screen Time settings:
   - Settings > Screen Time > Ensure "Share Across Devices" is enabled if using multiple devices
4. Grant Screen Time permission (required for automatic data)

---

## ❓ Frequently Asked Questions

### Q: Does the app work offline?
**A:** Yes! SYE works completely offline. No internet connection is required for any features.

### Q: Can I use both 20-20-20 Eye Rest and Homework Mode at the same time?
**A:** No. Starting one session will prompt you to end the other if one is already active. This prevents conflicts.

### Q: Why does Homework Mode require Screen Time permission?
**A:** Homework Mode uses Apple's Screen Time APIs to block apps at the system level. This requires Family Controls permission, which is part of Screen Time.

### Q: Will SYE block itself?
**A:** No. The app automatically excludes itself from blocking, so you can always access SYE.

### Q: What happens if I close the app during a session?
**A:** Sessions persist! Both 20-20-20 Eye Rest and Homework Mode continue running even if you close the app. Notifications will still fire, and sessions will end automatically.

### Q: Can I customize the notification sounds?
**A:** Notifications use the system default sound. You can change your device's notification sounds in Settings > Sounds & Haptics.

### Q: What iOS version is required?
**A:** SYE requires iOS 16.0 or later for full functionality. Some features require iOS 17.0+.

### Q: Is my data stored securely?
**A:** Yes. All data is stored locally on your device using iOS's secure storage. No data is sent to external servers.

### Q: Can parents use this for multiple children?
**A:** Currently, SYE manages one device at a time. For multiple children, you would need separate installations or device profiles.

### Q: What's the maximum Homework Mode session duration?
**A:** The maximum is 3 hours. This limit helps ensure healthy breaks and prevents excessive device restriction.

---

## 📋 System Requirements

- **iOS Version:** 18 or later
- **Device:** iPhone or iPad
- **Storage:** Minimal storage required (under 50 MB)
- **Internet:** Not required (works offline)

---

## 🆘 Getting Help

### Contact Support

If you're experiencing issues not covered in this guide, please contact us:

**Email:** [syecontact.app@gmail.com](mailto:syecontact.app@gmail.com)

When contacting support, please include:
- Description of the issue
- Steps to reproduce the problem
- Device model and iOS version
- Screenshots (if applicable)
- Whether the issue occurs consistently or intermittently

We aim to respond within 24-48 hours.

---

## 📝 Privacy & Data

SYE respects your privacy:
- **No data collection:** All data stays on your device
- **No tracking:** We don't track your usage or behavior
- **No ads:** The app is ad-free
- **Local storage only:** All settings and sessions are stored locally

For more details, see our Privacy Policy (if available) or contact us.

---

## 🔄 Updates & Improvements

We're constantly working to improve SYE. If you have feature suggestions or feedback, please email us at [syecontact.app@gmail.com](mailto:syecontact.app@gmail.com).

**Current Version:** 1.0.0

**What's New:**
- Initial release with 20-20-20 Eye Rest
- Offline-first architecture

---

## 📚 Tips for Best Experience

1. **Enable Notifications:** Keep notifications enabled for the best experience
2. **Select Apps Carefully:** For 20-20-20, select apps you frequently use for best impact
3. **Test on Device:** Some features work best on a physical device, not simulator
4. **Regular Sessions:** Use the 20-20-20 feature regularly for maximum eye health benefits
5. **Set Expectations:** When using Homework Mode with children, explain why certain apps are blocked

---

## ⚖ Terms & Legal

By using SYE - Save Your Eyes, you agree to use the app responsibly. The app is provided as-is for your personal use. We are not responsible for any misuse of blocking features or any consequences arising from app usage.

---

**Last Updated:** February 2026

**Support Email:** [syecontact.app@gmail.com](mailto:syecontact.app@gmail.com)

Thank you for using SYE - Save Your Eyes! 👁✨

