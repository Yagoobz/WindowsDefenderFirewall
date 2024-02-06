<h1>Windows Defender Firewall</h1>

<h2>About This Lab</h2>
Windows Defender Firewall is essential for protecting your system against network threats. In this lab, I'll show you how I configured firewall rules using both Windows Defender Firewall and its Advanced Security features.

<h2>Exercise 1: Configure Firewall Rules Using Windows Defender Firewall</h2>

<h3>Objectives</h3>
- Get familiar with configuring Firewall Rules Using Windows Defender Firewall.
<br />
- Explore the nuances of Firewall Rules Using Windows Defender Firewall with Advanced Security.

<h3>Step 1: Verify Firewall Status for Each Network Profile</h3>
First, I clicked on the Windows Start button and navigated to Windows Security. Once there, I located and click on 'Firewall & network protection.'
Then I made sure to click on each network profile - Domain, Private, and Public - and I ensured that the Windows Defender Firewall was toggled to 'On' for each one.

<h3>Step 2: Allow Firefox through Firewall</h3>
Let's make an exception for Mozilla Firefox. I clicked on 'Allow an app through firewall' and locate Firefox in the list. I noticed that it's allowed on the Private network but blocked on the Public network. To rectify this, I simply checked the box next to 'Public' for Firefox. Once done, I hit 'OK' to return to the Firewall & network protection screen.
<img src="https://github.com/Yagoobz/WindowsDefenderFirewall/assets/145611184/0e2a2c11-7339-48b0-a8ae-5d8f55af9c16" height="30%" width="70%" alt="Disk Sanitization Steps"/>

<h2>Exercise 2: Configuring Firewall Rules Using Windows Defender Firewall with Advanced Security</h2>

<h3>Objectives</h3>
- Allow the connection for Key Management Service on the Domain and Private network.
<br />
- Deny the connection for Key Management Service on the Public network.

<h3>Step 1: Accessing Advanced Settings & Understanding Rule Types</h3>
First I navigated to the Firewall & network protection screen and select Advanced settings. Then I took note of the Inbound and Outbound rules.

<h3>Step 2: Reviewing Key Management Service Rule & Modify The Rule</h3>
I located the Key Management Service inbound rule and noted the current status and action of the rule. Then I double-click the Key Management Service inbound rule to open its properties, and in the Advanced tab deselect the Public profile to restrict communication to the Domain and Private networks.




