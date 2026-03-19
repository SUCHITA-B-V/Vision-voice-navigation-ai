# Vision-voice-navigation-ai
AI-powered real-time mobility assistant for visually impaired users using voice commands, computer vision, and multi-sensor fusion to detect obstacles, provide navigation guidance, and trigger emergency alerts.

# 🚀 Key Features
1. Real-Time Mobility Detection
30 FPS Continuous Scanning: High-frequency environment monitoring.
Ultrasonic Distance Precision: Accurate proximity sensing between 0.2m – 3m.
Proximity Alerts: * 🛑 Danger: < 0.8m
⚠️ Caution: 0.8m – 1.5m
Walking Mode Detection: Integrated Accelerometer and Pedometer to track gait and motion.

# 2. Computer Vision AI
GPT-4 Vision Integration: High-level scene understanding and analysis.
"Quick Scan" Environment Analysis: Instant feedback on the immediate surroundings.
Object Detection: Identifies obstacles, vehicles, and clear pathways.
Base64 Processing: Production-ready photo capture and optimized image transmission.

# 3. Advanced Voice Interface
Always-Listening Commands: Hands-free operation for seamless use.
Premium TTS: Powered by Murf AI with a local device TTS fallback.
Dynamic Voice Profiles: * Normal: Standard navigation.
Urgent: Nearby obstacles.
Emergency: Immediate hazards.
Real-time Feedback: Visual and audio cues for voice listening status.

# 4. Emergency & Multi-Sensor Fusion
SOS System: Dedicated Red Emergency UI with an instant SOS button.
Auto-Emergency: Triggers on critical proximity detection.
Haptic Feedback: Specific vibration patterns for iOS and Android (3s for Danger, 1s for Caution).
GPS Tracking: Real-time location locking and coordinates included in emergency alerts.
🗣️ Voice Commands
Simply speak these commands to interact with the assistant:
| Command             | Function          |
| ------------------- | ----------------- |
| "status"            | Get system status |
| "scan"              | Scan surroundings |
| "emergency" / "sos" | Trigger emergency |
| "stop"              | Pause scanning    |
| "resume"            | Resume scanning   |

# Demo video 
https://go.screenpal.com/watch/cOeqi3nZWhK

# 🛠️ Technical Specifications
Production Features
Cross-Platform: Full support for iOS and Android.
Optimized Performance: 30 FPS scanning with smart battery optimization.
Offline Capable: Local TTS fallback ensures functionality without a data connection.
Storage: Async AsyncStorage ready for persistent user settings.
Compliance: App Store compliant and Accessibility Certified.
Alert Priority System
Level 1 (< 0.8m): 🚨 DANGER! STOP! (3s Continuous Vibration)
Level 2 (0.8m - 1.5m): ⚠️ CAUTION (1s Pulsed Vibration)
Level 3 (> 1.5m): ✅ SAFE (No Vibration)

# 📦 Deployment
This app is designed for rapid deployment:
Single File Architecture: App.js is 100% complete.
5-Second Setup: Simple copy-paste deployment.
Zero Dependency Issues: No external configuration headaches.

# 🧪 Testing the App
Voice Check: Say "status" to hear the full system report.
Proximity Check: Walk toward a wall to trigger the DANGER haptic alerts.
Vision Check: Say "scan" to receive an AI-generated description of the room.
Safety Check: Press the SOS button to verify emergency UI and GPS locking.
