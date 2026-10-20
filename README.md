# Android Security Assessment Using Metasploit

**Project Overview**

This project documents a hands-on Android security lab using Kali Linux, Metasploit, Apache2, and an Android-x86 virtual machine. The purpose was to learn how Android application delivery and remote-session behavior work in a controlled testing environment and to understand the security and privacy risks that can result from unauthorized access.

**Objectives**

- Set up and test an Android-x86 virtual machine using VirtualBox.
- Prepare Kali Linux with Metasploit and an Apache2 web server.
- Explore Android application delivery in the lab environment.
- Configure a Metasploit handler and observe a successful Meterpreter session.
- Review Android system information and post-exploitation capabilities.
- Identify security risks and discuss ways to protect Android devices.

**Tools and Technologies**

- **Kali Linux** — Linux environment used for security testing.
- **Oracle VM VirtualBox** — Used to run the virtual machines.
- **Android-x86 9.0** — Android test environment.
- **Metasploit Framework** — Used to examine payload and handler behavior in the lab.
- **Apache2** — Used to host the Android application file.
- **Meterpreter** — Used to review the established test session and available commands.

**Lab Summary**

**Step 1: Set Up the Android Virtual Machine**

Downloaded the Android-x86 virtual machine image, extracted the OVA file, imported it into VirtualBox, and confirmed that the virtual machine started successfully. Tested the Android browser by loading YouTube.

**Step 2: Prepare the Kali Linux Environment**

Installed Metasploit and Apache2, verified that the web server was running, and created a directory for the Android application file. Reviewed the Kali Linux IP address and the Metasploit handler configuration.

**Step 3: Conduct the Android Security Assessment**

Accessed the hosted application file from the Android virtual machine and installed the application. Started the Metasploit handler and confirmed that a Meterpreter session was established. Reviewed the Android system information and examined commands related to contact retrieval and screen sharing.

**Key Findings**

- Successfully prepared the Android-x86 virtual machine and Kali Linux testing environment.
- Verified that the Apache2 web server was running and hosting the application file.
- Observed a successful Meterpreter session and retrieved Android system information.
- Examined how post-exploitation capabilities could create privacy risks if misused.
- Identified the importance of application permissions, trusted software sources, and monitoring suspicious network activity.

**Security Recommendations**

- **Control application permissions:** Review requested permissions and limit access to contacts and other sensitive information when unnecessary.
- **Monitor network activity:**  Investigate unexpected connections, unfamiliar destinations, and suspicious traffic.
- **Scan suspicious applications:** Use reputable security tools to examine application files before installation.
- **Use trusted sources:** Avoid installing applications from unverified websites.
- **Keep devices updated:** Install operating system and application security updates.

**What I Learned**

Through this project, I developed hands-on experience with several cybersecurity tools and techniques:

- **Virtual Lab Configuration:** Set up Kali Linux and Android-x86 virtual machines in VirtualBox and verified network connectivity between the lab systems.
- **Web Server Configuration:** Used Apache2 to host an Android application file and verified that the file was accessible through the web server.
- **Metasploit Framework:** Explored Metasploit payload and handler configuration, including the role of the listener IP address and port.
- **Remote Session Analysis:** Confirmed a Meterpreter session and used system information output to identify the Android operating system, kernel, and architecture.
- **Post-Exploitation Awareness:** Examined commands related to contact retrieval and screen sharing to understand how unauthorized access could put personal information at risk.
- **Security Risk Assessment:** Connected the lab results to defensive practices such as reviewing application permissions, monitoring network connections, scanning suspicious files, and limiting unauthorized access.

This project helped me build a foundation in Android security testing, network configuration, web server basics, and the use of security tools. It also helped me understand how defenders can use knowledge of attack techniques to recognize risks and improve device security.

**Scope and Safety**

This assessment was conducted for educational purposes in a controlled virtual lab using systems configured for testing. The techniques were examined to understand security risks and defensive practices. Testing should only be performed on devices and systems for which authorization has been granted.

**Screenshots and Documentation**

Selected screenshots and the project report will be added to this repository to document the lab setup, tool configuration, and observed results.
