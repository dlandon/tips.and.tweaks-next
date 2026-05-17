# Changelog

The **Next** series continues development of the plugin by the original author and focuses on ongoing maintenance, reliability improvements, and compatibility with current Unraid releases.

Development of the plugin will continue with ongoing maintenance, improvements, and enhancements.

## 2026.05.17

### Improvements
- Updated CPU scaling and power management handling for improved compatibility with modern Linux CPU frequency drivers
- Simplified CPU power management controls with a more user-friendly and generic policy-based approach
- Improved Tweaks page layout, responsiveness, and UI behavior

### Fixes
- Updated CPU scaling and boost handling for newer Intel and AMD CPU frequency drivers
- Reworked help text and UI descriptions for improved clarity and consistency
- Fixed several UI logic and scheduling issues related to CPU Boost and Power Saving settings
- Corrected various Tweaks page layout and rendering issues

### Enhancements
- Added improved dynamic UI handling for CPU scheduling and power management controls
- Improved compatibility with modern CPU power management features and driver behavior

### Notes
- CPU scaling settings have been redesigned using a simplified policy-based model
- Existing CPU scaling settings are not automatically converted to the new policy modes
- After upgrading, review the CPU scaling settings on the Tweaks page and click Apply to save the updated configuration

## 2026.05.15

### Fixes
- Fix misspelling of balanced AMD Pstate EPP governors.

## 2026.03.27

Initial release of the **Next** series maintained by the original author.

The focus of this release is reliability, stability, and improved operational behavior...

Additional enhancements include expanded CPU governor options for AMD systems and improved visibility of network tuning settings by displaying Rx/Tx ring buffers, flow control, and TSO settings for each network interface.

### Improvements
- Updated user interface for improved compatibility with Unraid 7.x responsive design
- Modernized layout and visual separators on the Tweaks page
- Improved validation and usability of numeric configuration inputs

### Fixes
- Updated help text for **Balanced Performance** and **Balanced Power** CPU profiles
- Corrected several UI layout issues introduced by recent Unraid UI changes
- Limited Rx and Tx ring buffer configuration values to supported ranges

### Enhancements
- Added additional CPU governor options (**On Demand** and **Conservative**) for AMD Pstate
- Improved network tuning controls by displaying Rx/Tx ring buffers, flow control, and TSO settings per NIC
- Updated settings icons and UI controls for improved clarity

### Notes
- Minimum supported Unraid version is now **6.12**
- This release resumes active development of the plugin
- Detailed technical changes are documented in the GitHub release notes
