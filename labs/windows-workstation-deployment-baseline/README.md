- creating a virtual machine environment
- performing a clean Windows installation
- configuring a local administrator account
- renaming the workstation using a naming convention
- verifying drivers in Device Manager
- validating Windows Update readiness
- confirming  activation status
- testing network connectivity
- enabling Remote Desktop
- validating firewall profiles
- enabling network discovery
- reviewing local security policies
- checking Event Viewer logs
- verifying local users and groups
- confirming hostname configuration

--- 
## Environment

Lab setup:

- Windows 10 Pro (22H2)
- Oracle VirtualBox
- Local administrator account: LabAdmin
- Device name: LAPTOP-TEST01

---

## Deployment Workflow – Step-by-Step Evidence

This section documents the workstation preparation workflow from installation media creation through final validation checks.

---

### Installation media preparation

- 00-media-creation-tool-downloaded
- 01-windows-iso-configuration
- 02-select-iso-option
- 04-windows-iso-created
- 05-windows-iso-file-size

---

### Virtual machine creation

- 06-vm-name-and-iso-selected
- 07-skip-unattended-installation
- 08-vm-hardware-settings
- 09-virtual-disk-size
- 10-vm-created-successfully

---

### Windows installation

- 11-windows-setup-language-screen
- 12-windows-install-now-screen
- 13-windows-product-key-screen
- 14-select-windows-edition
- 15-accept-license-terms
- 16-installation-type-selection
- 17-select-installation-disk
- 18-windows-getting-ready

---

### OOBE configuration

- 22-region-selection
- 23-keyboard-layout-selection
- 24-skip-second-keyboard-layout
- 25-setup-for-personal-use-selection
- 26-microsoft-account-bypass
- 27-local-user-creation
- 28-edge-privacy-settings
- 29-privacy-settings-configured
- 30-windows-desktop-ready

---

### Post-install configuration

- 31-guest-additions-installed
- 32-current-device-name-before-rename
- 33-device-name-renamed
- 34-device-manager-clean
- 35-windows-update-check
- 37-windows-system-specifications
- 38-windows-activation-status
- 39-workgroup-status
- 48-computer-management-console

---

### Network and connectivity validation

- 36-network-connectivity-test
- 41-firewall-network-profile-public
- 42-firewall-network-profile-private
- 43-network-discovery-enabled

---

### Remote access readiness

- 40-remote-desktop-enabled
- 44-rdp-firewall-rule-enabled
- 45-remote-desktop-users-group
- 46-remote-desktop-service-running
- 47-winrm-service-status

---

### Security baseline review

- 50-account-lockout-policy-baseline
- 51-audit-policy-baseline
- 52A-user-rights-assignment-top
- 52B-user-rights-assignment-bottom
- 53A-security-options-top
- 53B-security-options-bottom
- 53C-security-options-bottom
- 53D-security-options-final
- 54A-advanced-audit-policy-root
- 54B-advanced-audit-policy-summary

---

### Final validation checks

- 55-event-viewer-system-log
- 56-local-users-list
- 57-local-groups-list
- 58-local-administrators-group
- 59-hostname-validation

---

## What I learned

Through this lab I practiced documenting a structured workstation preparation workflow and validating that a Windows system is ready before delivery to a user or domain enrollment.

This exercise helped me become more comfortable with:

- workstation deployment preparation steps
- local security baseline inspection
- connectivity validation
- Remote Desktop readiness
- Windows administrative tools used in Help Desk environments
