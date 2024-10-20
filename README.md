# README for Improved Security HTML Script

## Overview
This HTML file provides a mechanism to prevent users from accessing the source code, copying content, or inspecting elements on the page. It restricts various actions like right-clicking, keyboard shortcuts for developer tools, and content copying to ensure a secure viewing experience.

## Features
- **Text Selection Prevention**: Disables text selection across the entire webpage, making it impossible for users to copy the content.
- **Right-Click Context Menu Block**: Disables the context menu that appears on right-click, which typically allows users to view the source code or copy content.
- **Keyboard Shortcut Restrictions**: Blocks common shortcuts such as:
  - `F12` key for opening developer tools
  - `Ctrl+Shift+I` and `Ctrl+Shift+J` for inspecting elements and accessing the JavaScript console
  - `Ctrl+U` to view the page source
  - `Ctrl+C` to copy content
- **Warning Notification**: If the user tries to perform any restricted action, a warning message is displayed at the top of the screen for 2 seconds to inform them that the action is not allowed.

## Update - 20/10/2024
- A new feature has been added to show a warning message when a restricted action is attempted. This enhances the user experience by informing the user about blocked actions instead of failing silently.

## Usage
To use this script, simply include the HTML file in your project. It will automatically add the necessary content protection and warning notifications. No additional libraries or dependencies are required.

## Notes
- This protection mechanism works well for basic content protection; however, determined users with advanced skills may still find ways to bypass these client-side restrictions.
- Consider server-side solutions for more robust security requirements.

## License
This script is free to use and modify for non-commercial purposes.

