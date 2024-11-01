=== WebTotem Security ===
Contributors: wtsec
Donate Link: https://wtotem.com/
Tags: security, firewall, monitoring, antivirus, protection
Requires at least: 5.0
License: GPLv3
Tested up to: 6.6
Requires PHP: 7.1
Requires at least: 6.0
Stable tag: 2.4.34

WebTotem is a SaaS which provides powerful tools for securing and monitoring your website in one place in easy and flexible way.

== Description ==

**WebTotem: Enhance Your WordPress Website Security**

WebTotem the Ultimate WordPress Security Plugin for Comprehensive Protection
In today's digital landscape, safeguarding your WordPress website against a myriad of threats is paramount. WebTotem emerges as a formidable security solution, offering a suite of powerful features designed to protect your website from the ground up. With antivirus scans, firewall protection, SSL certificate monitoring, and port analysis, WebTotem ensures your web space is meticulously guarded. Pushing the envelope further, it incorporates CVE vulnerability scanning to preemptively identify and mitigate potential risks, fortifying your website's defense mechanism.
WebTotem transforms your website into an impenetrable fortress by integrating additional layers of security such as activity logs, two-factor authentication (2FA), brute force attack prevention, and CAPTCHA functionalities. This not only guarantees uninterrupted operation but also establishes a reliable security framework for your website.

## Core Features: ##
* **Antivirus Protection:** Conducts thorough scans of your files for malicious software, hidden shells, and dubious modifications, marking the first step towards a secure website. It's an intuitive solution for maintaining your site's integrity.
* **Firewall Defense:** Offers real-time safeguarding against SQL injections, XSS, and DOS attacks, ensuring your data remains secure from unwelcome intrusions.
* **SSL Module:** Administers continuous monitoring and management of your site's SSL certificates, protecting data transmission round the clock.
* **Port Scanner:** Employs meticulous analysis to identify open ports, blocking unauthorized access and neutralizing potential threats.
* **Open Path Scanner:** Proactively searches and reviews accessible paths to files and directories, closing off avenues for attacks.
* **Reputation Module:** Vigilantly monitors and alerts you about any blacklisting issues, safeguarding your site's online reputation and visibility.
* **Accessibility Module:** Keeps a close watch on site availability and page response times, ensuring optimal performance and a seamless user experience.
* **Technology Scanner:** Accurately identifies your site's technology stack and its versions, aiding in keeping your systems up-to-date.

## Highlight Features: ##
* **Vulnerability Scanner:** A cornerstone feature that scans for known vulnerabilities within the Common Vulnerabilities and Exposures (CVE) database, enabling swift remediation to boost your site's security.
* **Server Resource Module:** Provides crucial insights into RAM and CPU usage, along with disk space analytics, facilitating efficient resource utilization for enhanced site performance.
* **Activity Log:** An essential tool for monitoring site changes and activities, offering a comprehensive event timeline for enhanced security oversight and swift incident response.

## Enhanced Security Measures: ##
* **Two-Factor Authentication (2FA):** Elevates security by requiring a second form of verification, seamlessly integrated within your CMS to protect administrative access.
* **CAPTCHA Integration:** A versatile tool against spam bots and automated attacks, offering customizable CAPTCHA deployment to safeguard your forms from unwarranted submissions.
* **Brute-Force Protection:** Actively combats password guessing attempts, employing proactive measures to prevent unauthorized access to your accounts.
* **Security Level Assessment (Scoring):** Offers a detailed security evaluation based on an innovative methodology, pinpointing improvement areas with strategic recommendations to fortify your website's security stance.
* **Vulnerability Remediation Advice:** Goes beyond detection by providing actionable, detailed guidance for addressing vulnerabilities, enhancing your website's resilience against threats.

WebTotem stands as a comprehensive security plugin, expertly crafted to enhance your WordPress site's defenses. By adopting WebTotem, you not only protect your site from current threats but also strengthen its overall security architecture, ensuring a safe and robust online presence.

== Installation  ==
Installing the WebTotem security plugin is very simple. Detailed description of the process with screenshots is available [here](https://docs.wtotem.com/plugin-for-wordpress) , however below we give a short instruction.

To install WebTotem Security:

1. Go to the "Plugins" page and then select "Add New",
2. Search for our plugin using the name "WebTotem Security",
3. Once you have installed the plugin, you need to activate it. Go to the "Installed Plugins" page and click on the "Activate" button,
4. Go to the [WebTotem](https://wtotem.com/cabinet/profile/keys) and Generate an API-key on the "API-keys" page,
5. Use the API-key to activate plugin in the Wordpress admin panel on the "WebTotem Security" page.

Visit the [Support Forum](https://wordpress.org/support/plugin/wt-security/) to ask questions, report bugs or suggest new features.

== Frequently Asked Questions ==

More information on the WebTotem Security plugin can be found in our [Help Center](https://docs.wtotem.com/plugin-for-wordpress).

= SETUP =
**Why can’t I activate Wordpress plugin with API-Keys?**
It is required to copy API-Key immediately after it has been generated. Since we don't store API-Keys with authentic namings for the sake of security issues. If you did not copy it from generation window, we recommend you to delete it, generate a new one again and copy it with original naming.

= FIREWALL =
**Why doesn’t firewall block the attacks?**
After installation the firewall is undergoing training for two weeks, analyzing the operation of the system and all requests. Upon completion of the training, the firewall will start to block attacks. If after two weeks after installation the firewall does not block attacks, then contact support.

**Does GDN send my data to other WebTotem clients?**
Thanks for the question. You don't have to worry about your personal data. GDN option shares data collected between your websites and does not share it with other WebTotem clients.

= ANTIVIRUS =
**How does antivirus work?**
Our antivirus scans every 6 hours and scans automatically each time the filesystem changes. In other words, if you upload a new file to your website our antivirus scans it immediately. There is also an option to start manual scanning by clicking the rescan button in the right top of the module.  Manual scanning shows the same results if no changes to filesystem has occured since the last automatic scanning.

**How do I delete an infected file?**
It is impossible to completely delete a file marked as infected by an antivirus using our service. This can be a vital file for your website. You can quarantine this file. To do this, select the site you need in your personal account. Go to the antivirus module, click the "SHOW MORE" button, configure the filter for infected files and click the "trash bin" icon next to the file name.

== Screenshots ==
1. Dashboard - Shows statistics for all modules.
2. Firewall - Shows firewall activity, attacks map.
3. Antivirus - Shows antivirus and quarantine logs.
4. Settings - Offers multiple settings to configure the functionality of the plugin.
4. Reports - Offers multiple tools to create reports.

== Changelog ==
= 2.4.34 =
* Fixed twig conflict
* Fixed the output of the details of the WAF attacks
* Front improvements

= 2.4.33 =
* Fixed auth method

= 2.4.32 =
* Fixed the issue of our API address being blocked by adding a site mirror

= 2.4.31 =
* Internal improvements

= 2.4.30 =
* Fixed link scanning on the WP scan page
* Internal improvements

= 2.4.29 =
* Added Plugin Checks for CVEs
* Added anti-user enumeration
* Internal improvements

= 2.4.28 =
* Fixed the issue that occurred when adding a site.
* Internal improvements

= 2.4.27 =
* Fixed login attempts issue
* Internal improvements

= 2.4.26 =
* Feedback user issue has been fixed
* Internal improvements

= 2.4.25 =
* The api-key entry page has been fixed
* Internal improvements

= 2.4.24 =
* Added forceCheck buttons
* Fixed AV data request
* Internal improvements

= 2.4.23 =
* Fixed some errors WP scan
* Added user feedback popup

= 2.4.22 =
* The Open Path Scanner module has been added
* The Port Scanner and SSL modules have been changed
* Availability and deface modules have been removed

= 2.4.21 =
* The logic has been changed, now when the plugin is removed, the AV and WAF agents are not deleted
* Fixed styles for mobile devices

= 2.4.20 =
* Fixed an issue with blocking custom administrator roles
* WP scan improvements

= 2.4.19 =
* Fixed some errors in multisite
* Internal improvements

= 2.4.18 =
* Added the Confidential files section on the WP scan page
* Added support for different domains in multisite mode
* Added the rescan button to the WP scan page
* Fixed errors caused by the absence of the wtotem_audit_logs table in the database
* Changed the maximum value to 10000 for the DOS limits parameter
* Internal improvements

= 2.4.17 =
* Added the setting blocking countries
* Added WP scan page: Log of user actions. Logs on found links, scripts and iframes

= 2.4.16 =
* Added pop-up notification
* Added 2FA to all users
* Fixed an error saving settings without installed agents

= 2.4.15 =
* Fixed the cause of php warnings
* Fixed conflict with Google Authenticator
* Fixed errors in styles
* Internal improvements

= 2.4.14 =
* Added firewall log report
* Added login attempts
* Added password reset attempts
* Added Determining the environment by the API-key

= 2.4.13 =
* Fixed ajax error

= 2.4.12 =
* Added Two-factor authorization
* Added reCAPTCHA for authorization
* Added the option to Hide the WP version
* Added API Data Caching
* Fixed a bug when switching to a multisite

= 2.4.11 =
* Fixed the problem of reinstalling agents when updating.

= 2.4.10 =
* Fixed a bug when upgrading from older versions.

= 2.4.9 =
* Fixed issues with switching to a multisite

= 2.4.8 =
* Session data storage has been changed

= 2.4.7 =
* Fixed an issue related to using the function str_contains

= 2.4.6 =
* Internal improvements

= 2.4.5 =
* Fixed session errors

= 2.4.4 =
* Internal improvements

= 2.4.3 =
* Fixed styles issue

= 2.4.2 =
* Fixed multisite page view

= 2.4.1 =
* Added multisite support
* All settings have been moved to the settings page
* Internal improvements

= 2.3.47 =
* Change title for request counter on WAF blocks
* Fixed adding domains

= 2.3.46 =
* Fixed adding IDN domains

= 2.3.45 =
* Fixed page reload issue

= 2.3.44 =
* Fixed a problem with viewing AV logs

= 2.3.43 =
* Added URL white list
* Fixed the issue of time zone

= 2.3.42 =
* Added port ignore list
* Added the ability to send IP addresses by list
* Added notifications settings

= 2.3.41 =
* Fixed the issue of reinstalling agents

= 2.3.40 =
* Fixed styles

= 2.3.39 =
* Added antivirus last scan time

= 2.3.38 =
* Fixed an issue with API key authorization

= 2.3.37 =
* Fixed the issue of deleting agent files

= 2.3.36 =
* Fixed redirects issue

= 2.3.35 =
* Fixed the authorization issue

= 2.3.34 =
* Changed the translation algorithm
* Added ru-Ru language

= 2.3.33 =
* Fixed logout bug

= 2.3.32 =
* Fixed waf training period

= 2.3.31 =
* Changed display of data

= 2.3.30 =
* Fixed file filter by status
* Updated agents statuses

= 2.3.29 =
* Fixed styles dark mode
* Logic changed, agents are removed when logout

= 2.3.28 =
* Updated plugin information
* Updated screenshots

= 2.3.27 =
* Fixed the issue of deactivating the plugin

= 2.3.26 =
* Fixed the issue of adding a file to the quarantine

= 2.3.25 =
* Added analytics system

= 2.3.24 =
* Added Firewall advanced options allow/deny list

= 2.3.23 =
* Fixed conflict with some plugins
* Fixed session errors in the "site health" section

= 2.3.1-22 =
* Added antivirus permission changed filter
* Added download antivirus log
* Added antivirus rescan
* Fixed plugin deactivation bug
* Fixed the issue of adding sites with www

= 2.3 =
* Added report page
* Limit login attempt option
* Added file quarantine
* Added Server resources module

= 2.2 =
* Added settings page
* Fixed data display error
* Added dark mode
* Added attacks map view

= 1.1 =
* Disable waf in admin page

== Upgrade Notice ==
= 1.0 =
Publishing the plugin
