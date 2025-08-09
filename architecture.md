# Little Guardian for Kids - Architecture

## App Overview
A comprehensive parental control app that protects children from digital threats including malicious messages, harmful websites, and cyberbullying through AI-powered content analysis.

## Core Features
1. **Real-time Message Scanning** - AI analysis for threats and bullying detection
2. **Website Protection** - URL filtering with VirusTotal-style security checks  
3. **Audio Warning System** - Immediate alerts when threats are detected
4. **Parent Notification System** - Instant alerts to parents about incidents
5. **Activity Monitoring** - Comprehensive logging of all security events
6. **Child-Safe Interface** - Colorful, engaging UI designed for children

## Technical Implementation
- **Local Storage**: SharedPreferences for settings and activity logs
- **State Management**: Provider pattern for app state management
- **Security Engine**: Keyword-based threat detection simulating AI capabilities
- **Audio System**: Built-in Flutter audio for warning sounds
- **Parent Alerts**: Local notification simulation system

## File Structure
- `models/` - Data models for threats, messages, activities
- `services/` - Core business logic (security, notifications, storage)
- `screens/` - Main UI screens (dashboard, settings, logs)
- `widgets/` - Reusable UI components
- `theme.dart` - Child-friendly color scheme and styling

## Security Features
- Message content analysis for inappropriate language
- URL reputation checking (simulated VirusTotal integration)
- Real-time threat blocking with user feedback
- Comprehensive activity logging for parent review
- Automatic parent notification system