# Changelog

The **Next** series continues development of the plugin by the original author and focuses on ongoing maintenance, reliability improvements, and compatibility with current Unraid releases.

Development of the plugin will continue with ongoing maintenance, improvements, and enhancements.

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
