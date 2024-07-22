Version: 1.4.5
- Fixed Anthem protocols to be less dependent on website layout
- Removed download timeout from BCBS protocols
- Increased timeout for CareSource

Version: 1.4.4
- Updated BCBS logins to account for new MFA page

Version: 1.4.3
- Removed debug break from UHC Login
- Improved UHC and UHCR MFA prompts

Version: 1.4.2
- Program now automatically restarts after an update
- More intelligent error message
- Program now saves screenshots of driver on Web Error

Version: 1.4.1
- Added confirmation before window closes due to PIP
- Added How-To section to README file
- Added more detailed messages to MFA verification code prompts
- Made Cigna protocols less dependent on window size

Version: 1.4
- Added Oscar Protocols
- Added BlueCross BlueShield protocols
  - for Texas
  - for Oklahoma
  - for Illinois
  - for Montana
- Added CareSource protocols
- Added UHC Readiness Protocol (stored separately from rest of UHC for reasons beyond my control)
- Fixed GUI bug where SmartScrolledPanels would reset themselves when updated
- SmartScrolledPanel now automatically determines its default size
  - SmartScrolledPanel default size now leaves space for scroll bar
- Changed wording of Verification Filter to MFA filter for conciseness
- Fixed bug where Login page wouldn't scroll till a dropdown was clicked
- File Manager now detects when it can't write to file and prompts user accordingly
- PullTargets can now opt out of clearing windows after login (required for some providers)

Version: 1.3.4
- Added UHC Book of Business protocol
- Stabilized UHC protocols
- Added button to Settings screen to view Save Directory
- Changed how GUI supervisor handles arbitrary exceptions

Version: 1.3.3
- Completed UHC Commissions protocol
- Added Verification Filter to command line usage
- Made Anthem requests more consistent

Version: 1.3.2
- More intelligent patch notes
- Small GUI changes

Version: 1.3.1
- More informative terminal output concerning live service
- Program now responds to request timeouts when checking for updates
- More intelligent version checking
- Request Targets can now be filtered based on whether they
  require a verification code
- Added skeleton for UHC Request Target (not implemented yet)

Version: 1.3
- Added live service
- More to come soon
