# Cloud-Managed Campus Networking for the AI Era

**Cisco dCloud**

**Status:** Published
**Created:** August 25, 2025
**Last Updated:** August 25, 2025
**Creator:** cisco-dcloud@cisco.com

---

## About This Demonstration

Evolving business needs and rapid advancements in technology present organizations with the perfect opportunity to modernize their campus and branch networks. Upgrading network infrastructure is no longer just about replacing aging equipment. It's about embracing innovation, enhancing agility, and positioning your organization for long-term success.

In this demonstration, you'll discover how Cisco Cloud-First Campus empowers organizations to seamlessly manage and monitor their campus and branch environments through the Meraki Dashboard.

With support for Meraki and Catalyst switches, MX appliances, and the latest Wi-Fi 7 technologies, this integrated approach unifies cloud-managed and cloud-monitored devices into a flexible, scalable foundation tailored to your unique requirements.

You'll experience how proactive management ensures smooth transitions during hardware refresh cycles, minimizing disruption and supporting business continuity.

### Included Cisco Products

- Catalyst/Meraki Switching and Wireless
- Meraki Cloud Fabric
- Meraki Access Manager
- Meraki Adaptive Policy
- Workflows
- ThousandEyes (Including Endpoint Mobile Agent)
- Splunk
- Webex

## Access Your Demo

To use Meraki Dashboard, ThousandEyes, and other integrated tools, you must log in to each portal separately from the iDAC dashboard.

NOTE: The links between Meraki Dashboard and ThousandEyes may not be seamless in this demo. Each product requires its own login session.

---

## Use Case 1: Explore the Power of the Meraki Dashboard: Real-Time Network Observability

### Scenario 1: Navigate the Meraki Dashboard: A Day in the Life of an IT Admin

**Persona:** Andrew Moore, Network Administrator

**Demo Scenario:**

> Andrew begins his day by opening Meraki Dashboard, the central platform for managing his organization's network. The dashboard offers a unified, cloud-first view of the entire enterprise, showing an organized hierarchy from global to network to device level. Andrew can easily navigate between branches, campuses, and devices—wired and wireless alike—thanks to Meraki's seamless integration and intuitive interface.
> 
> He explores how the dashboard consolidates management for switches, access points, security appliances, and more, all in one place. Enterprise-grade features such as Access Manager, Assurance, Insights, and alerting are built in, providing real-time visibility and streamlined daily operations.

**Pain Point:**

Managing a large, distributed network with multiple device types has traditionally required Andrew to juggle several tools and platforms, making it difficult to maintain visibility and consistency across the organization. Manual monitoring and configuration eat up time and increase the risk of oversight causing outages.

We use the following Cisco features and products to address this pain point:
• Meraki Dashboard: To unify network management and monitoring for wired, wireless, routing, and security services
• Assurance and Insights: For advanced analytics and operational visibility
• Meraki and Catalyst Switching: Enterprise access layer switching
• Meraki and Catalyst Access Points: Wi-Fi 7 implementation, management, and troubleshooting
• Meraki MX Security Appliances: Secure and provide connectivity to the internet and other branch locations

#### Step 1

**What?**

"We explore the Meraki Dashboard to understand how it provides unified, real-time visibility and management for the entire network. We use the dashboard to view overall network health, analyze connected clients and their activity, examine traffic analytics, and visualize network topology."

**Why?**

In this step, we explore the observability features of the Meraki dashboard. In the Organization Summary dashboard, administrators can see the health status of all networks and devices across the whole organization.

**a)** Let's investigate network-specific details. Click Network at the top of the left navigation. Select Branch2. Navigate to Network-wide > Clients.

Administrators get an at-a-glance overview of every device connected to the network, Branch 2 in this case, whether wired or wireless.

   - Instantly see device names, IP and MAC addresses, and their connection status (online or offline).
   - Track how much bandwidth each client is using, along with the types of applications and services they're accessing.
   - Click into any device for more details, such as its operating system, VLAN assignment, and the specific port or access point it's using.
   - Review a device's usage history and easily search or filter the list to find what you need.
   - Apply or adjust network policies, such as bandwidth limits or access restrictions, right from the same view.

**b)** Navigate to Network-wide > Traffic Analytics.

The Traffic Analytics tab in the Meraki Dashboard gives administrators a clear and detailed look at how network bandwidth is being used across all your networks, Branch 2 in this case.

   - See a breakdown of overall traffic by application category (such as web browsing, streaming, or file sharing) and by specific applications (such as YouTube, Dropbox, or Microsoft 365).
   - Identify which users or devices are generating the most traffic and what services are consuming the most bandwidth.

**c)** Navigate to Network-wide > Topology. This is a visual representation of your network.

#### Step 2

**What?**

"We see how the Meraki Dashboard consolidates management of all major network components: security appliances, switches, and wireless access points into a single, unified interface. We navigate through status and configuration pages for each device type to see how administrators monitor and control the network from one place."

**Why?**

To demonstrate how unified management simplifies daily operations, improves visibility, and streamlines configuration across the entire network, making it easier to maintain security, performance, and scalability.

The Meraki Dashboard brings all key aspects of enterprise network management into a single, unified interface - making it remarkably easy to monitor and configure everything from security appliances to wireless access points and core switches.

**a)** Navigate to Security & SD-WAN > Appliance Status.

Here, administrators can instantly check the health and activity of their security appliances. This includes real-time status, VPN connections, active threats, and WAN performance metrics. Essential security and traffic controls such as firewall rules, content filtering, and SD-WAN policies are fully accessible and configurable.

**b)** Navigate to Switching > Switches. Select Branch2-9300.

The Switching section offers a comprehensive view of all switches in the network. Administrators can monitor switch health, port status, and traffic flows in real time. Selecting a switch reveals detailed information on each port, including connected devices, PoE power consumption, and configuration options.

VLAN settings, port security, and even firmware upgrades can be managed remotely, streamlining daily operations.

NOTE: Many pages in the Meraki Dashboard allow you to switch between Old Version and New Version. We suggest you always switch to the New Version, if possible.

**c)** Navigate to Wireless > Access Points. Select Branch2-AP2.

In this Wireless section, you see a live inventory of all deployed Access Points across the organization. Each AP's connectivity, usage, client count, and even channel utilization are visible at a glance.

By selecting an individual access point, you can review detailed performance stats, troubleshoot client issues, and manage settings such as SSIDs and radio configurations—all without leaving the dashboard.

#### Step 3

**What?**

"We learn how to use Meraki Access Manager for centralized, cloud-based network access control (NAC). We review how access policies are set up and enforced for users and devices, and how the integration with identity services (such as Microsoft Entra ID) is managed—all from the Meraki Dashboard."

**Why?**

To show how cloud-based NAC enables rapid, scalable, and consistent access policy deployment without the complexity or hardware requirements of traditional solutions, improving security, and operational efficiency.

Meraki Access Manager is changing the game for network access control. Unlike traditional NAC solutions that require on-site appliances and advanced configuration, Access Manager is a fully cloud-based NAC and simple to use right from the Meraki Dashboard.

**a)** Navigate to Access Manager > Users.

What makes Access Manager stand out is how naturally it fits into the rest of the Meraki ecosystem. Security, wireless, and switching all work together under one pane of glass, making it easier to keep things secure and consistent. Here you can get a centralized view into how Access Manager is configured. In this demo, we've integrated Access Manager with Microsoft Entra ID for user identity.

#### Step 4

**What?**

"Meraki Network Visibility provides a suite of powerful tools: Assurance, Insight, and Organization Alerts that give IT administrators a comprehensive view of network health, application performance, and security events. These features allow teams to monitor, troubleshoot, and respond to issues proactively across the entire organization."

**Why?**

Having complete visibility into network operations is essential for maintaining a reliable and high performing network. By leveraging these tools, IT teams can detect problems early, understand their root causes, and respond quickly minimizing downtime, improving user experience, and supporting seamless business operations.

**a)** Navigate to Assurance > Overview.

Review the information found here. Note the overall health score, as well as details about the clients, network devices, and applications.

**b)** Navigate to Insight > Web App Health.

Explore the applications monitored by ThousandEyes Enterprise Agents running on MX appliances in every network. ThousandEyes test results are reported back to Meraki Dashboards, and can be viewed in both the Meraki Dashboard Insight page and in the ThousandEyes portal itself.

NOTE: Insight integrates nicely with ThousandEyes to give detailed path analytics.

**c)** Navigate to Organization > Alerts. Investigate the active alerts in the Organization. Feel free to check alert details, see suggested actions, etc.

Organization Alerts are the network's early warning system. They notify administrators right away about important events, outages, or anything unusual happening anywhere across the organization's network.

### Scenario 2: See Cloud-First Networking in Action: Meraki-Managed Wired and Wireless Solutions

**Persona:** James Deen, Network Operations Engineer at PseudoCo

**Demo Scenario:**

> James' job is to keep PseudoCo's branch networks running smoothly, no matter how the company grows or how many different devices pop up. At Branch 1, he's got Meraki devices everywhere. Managing them is a breeze! He logs into the Meraki Dashboard and can see, configure, and troubleshoot every access point, switch, and SSID in just a few clicks.
> 
> Branch 2 is a bit different, it's built on Cisco Catalyst hardware. But here's where Meraki's true power really comes through. James doesn't have to switch tools or bounce between dashboards. Instead, he gets a single, cloud-based view of everything, Meraki and Catalyst alike.
> 
> At Branch 2, James has set up two Meraki access points and a Meraki Cloud Gateway (MCG) on-site. With L3 roaming using the MCG, roaming issues are gone. The MCG acts like a home base for wireless users.

**Pain Point:**

Before Meraki, James was stuck juggling different management tools, struggling to keep user experience consistent, and worrying about enforcing policies across a mixed network. Users would often get disconnected or have to reconnect every time they moved around the office.

We use the following Cisco features and products to address this pain point:
• Meraki Dashboard: Unified, easy management of both Meraki and Catalyst devices
• Meraki Cloud Gateway: Smooth L3 roaming and keeping users connected as they move

#### Step 1

**What?**

"We explore how the Meraki Dashboard provides centralized, cloud-based management for both Cisco Meraki and Cisco Catalyst switches. You will monitor device and port status, configure settings, and perform troubleshooting tasks for both device types from a single interface."

**Why?**

To showcase how Cisco's unified cloud management streamlines operations, enabling consistent configuration, monitoring, and troubleshooting across the full Cisco switching portfolio.

**a)** Click Network at the top of the left navigation and select Branch1. Navigate to Switching > Switches. Select the Branch1-MS130 switch.

You can view the real-time status of every port, any major device issues, see which devices are connected, and check traffic levels at a glance.

**b)** Go to Branch2. Select the switch Branch2-9300.

You can see that the Catalyst 9300 switch was onboarded as a Meraki managed device right in the dashboard. Configuration Source: Cloud means that this device is fully managed by Meraki Dashboard.

#### Step 2

**What?**

"We utilize the Meraki Dashboard to view and manage wireless access points and SSIDs. We assess real-time AP status, client activity, performance, and easily configure wireless network settings."

**Why?**

To demonstrate how Meraki's management approach simplifies wireless network maintenance, troubleshooting, and optimization.

**a)** Within Branch1, go to Wireless > Access Points and select Branch1-CW9162.

Here, you get a quick snapshot of everything important: AP's current status, location on the network, and basic performance stats. Check out the Ports tab, Device Health section, Timeline tab, Connections, and Performance tab.

**b)** Within the Wireless tab of Branch1, go to SSIDs.

Here you'll find a clear overview of all the wireless networks running in your branch. Each SSID represents a different Wi-Fi network. You can adjust settings like network names, security types, VLAN tags, and access controls.

#### Step 3

**What?**

"See the Meraki Cloud Gateway (MCG) in action, enabling Layer 3 roaming so users can move throughout Branch 2 without session drops or IP address changes."

**Why?**

To highlight how Cisco's cloud-first wireless architecture solves mobility and roaming challenges.

**a)** Go to Branch2. Navigate to Wireless > Campus Gateways.

Here you can see the Meraki Cloud Gateway (MCG) in action. The MCG is a cloud-managed appliance that anchors wireless client traffic for SSIDs that are set up in "tunneled" mode.

**b)** In Branch2, navigate to Wireless > Access Control.

Select any SSID and scroll down to Client IP and VLAN configuration section. Note that all SSIDs in Branch2 are configured to tunnel the user traffic through the MCG cluster.

---

## Use Case 2: Automate Network Deployment(s) Using Cisco Workflows for Cisco Networking

### Scenario 1: Deploy a New Branch with Cisco Workflows and AI Assistant

**Persona:** Emily Tran, Junior Network Engineer at PseudoCo

**Demo Scenario:**

> PseudoCo is in a period of explosive growth, opening new branches across multiple cities every month. The company's IT leadership expects each location to have a secure, standardized network ready on day one, but the experienced network team can't be everywhere at once.
> 
> Emily, a junior engineer, is tasked with deploying the new branch networks. She turns to Cisco Workflows, which allow her to automate and standardize the process with a no-code model.

**Pain Point:**

Manual network deployment is slow, complicated, and prone to inconsistency—especially as branch count rises and IT resources continue to be stretched thin.

We use the following Cisco features and products:
• Cisco Workflows: Workflow Visualization and Editing with drag-and-drop builders
• Cisco AI Assistant: Enables seamless and easy way to interact with Workflows

#### Step 1

**What?**

"Emily initiates a pre-built workflow in the Meraki Dashboard to automatically configure all essential network components such as VLANs, SSIDs, and security policies for the new branch."

**Why?**

This makes branch deployment fast and reliable, allowing even junior engineers to set up secure, consistent networks without advanced configuration skills.

**a)** Log into the Meraki Dashboard and click the AI Assistant icon.

**b)** Type "I'd like to create a new network" and click Next. Select the "Create New PseudoCo Network" workflow.

**c)** AI Assistant provides you with the modules that this workflow will perform. Confirm that you want to use this workflow. Add a branch name and subnets.

**d)** Confirm deployment and click Next. Then navigate to Workflow > Run to see the status.

### Scenario 2: Build No-Code Automation Using Cisco Workflows

**Persona:** Carlos Diaz, IT Support Specialist at PseudoCo

**Demo Scenario:**

> PseudoCo's business is booming. As the company launches pop-up offices and shops across the country, the IT helpdesk is overwhelmed with network setup requests.
> 
> Carlos, a newer member of the IT team, explores Meraki's Workflow Automation and sees an opportunity: what if creating a new branch network could be as simple as entering a name and clicking a button?

**Pain Point:**

Manual branch setup is tedious, slow, and inconsistent, especially for less experienced IT staff. Each network must be named, configured, and checked line by line.

We use Cisco Workflows for Networking to enable IT to build simple, guided workflows that automate complex tasks.

#### Step 1

**What?**

"Carlos creates a workflow in the Meraki Dashboard that prompts the user for a branch name, then automatically provisions a new branch network with all default settings."

**Why?**

This reduces human error, speeds up deployment, and empowers even junior IT staff to deliver flawless branch networks.

**a)** In the Meraki Dashboard, navigate to Automation > Workspace and click + Create workflow. Select Blank Custom Workflow and click Continue.

**b)** Write the name that will be used to identify the workflow and click Continue. Then click the Variables tab.

**c)** Select the Data Type (String), change Scope to Input to determine that this block will be used to get data from the user.

**d)** Click the Target tab. Within the Target section, click Execute on this target. Determine the Target Type as Meraki Endpoint.

---

## Use Case 3: Cloud-First Identity-Driven Access and Segmentation with Meraki

### Scenario 1: Secure Your Network by Providing Granular Identity-based Network Access Control

**Persona:** Anna Moore, Network Security Administrator at PseudoCo

**Demo Scenario:**

> As PseudoCo grew and began handling more sensitive client data, Anna quickly realizes that traditional, static network controls aren't enough. She needs to securely separate teams such as Developers and Finance.
> 
> Meraki Access Manager, a new cloud-based Network Access Control (NAC) solution catches her eye. With Access Manager, Anna can centralize and automate how users and devices authenticate.

**Pain Point:**

Anna used to spend hours managing a patchwork of ACLs and manual rules, constantly worrying about misconfigurations or gaps that could put data at risk.

We use the following Cisco features and products:
• Meraki Adaptive Policy: Scalable, group-based segmentation
• Cisco TrustSec: Dynamic SGT assignment and policy enforcement
• Meraki Access Manager: Group assignment and authentication

#### Step 1

**What?**

"Anna reviews how Adaptive Policy and SGTs are mapped and enforced."

**Why?**

So she can be sure that segmentation is working as intended and that the business is truly protected.

**a)** From the Dashboard left-navigation menu, select Access Manager > Users. Browse the Users tab to see users and groups synced with Entra ID.

**b)** Navigate to Access Manager > Access Rules. Select the "Allow HR Users" rule to see VLAN assignment and Adaptive policy SGT value.

#### Step 2

**What?**

"We review the session log in Access Manager to identify failed authentication attempts."

**Why?**

Quickly pinpointing the cause of access problems helps resolve user issues faster.

**a)** Click Access Manager > Session Log to see authentication successes and failures.

**b)** Select the first failure you see. In the Network Access Details pop up, view the Failure/Rejection Info for troubleshooting.

### Scenario 2: Protect the Environment by Providing End-to-End Segmentation

**Persona:** Paul Miller, Senior Network Architect at PseudoCo

**Demo Scenario:**

> As PseudoCo expanded, the complexity of its network skyrocketed. Paul knew that relying on hundreds of static ACLs and firewall rules was no longer sustainable.
> 
> With Cisco Meraki Adaptive Policy and TrustSec, Paul finally has what he needs. He can define access policies based on roles, not just IP addresses.

**Pain Point:**

Paul struggled with time-consuming manual segmentation, out-of-sync ACLs, and the constant risk of accidental access between teams.

We use the following Cisco features and products:
• Meraki Adaptive Policy: Scalable, group-based segmentation
• Cisco TrustSec: Dynamic SGT assignment and policy enforcement

#### Step 1

**What?**

"Paul reviews how the Adaptive Policy is set up to segment communication between different user groups."

**Why?**

To ensure that segmentation rules are applied correctly, preventing Developers from accessing Finance resources.

**a)** Navigate to Organization > Adaptive Policy. Click the Groups tab to view Cisco Trustsec scalable group tags (SGTs).

**b)** Click the Policies tab. Focus on the Developers to Finance policy which prevents users with SGT(18) from communicating with SGT(19).

#### Step 2

**What?**

"Paul verifies the Adaptive Policy is working as intended."

**Why?**

To prove that segmentation is actively protecting the network and sensitive data.

**a)** Navigate to Branch2 > Network-wide > Clients. View the Adaptive Policy Group column to see assigned SGTs.

**b)** Navigate to Branch2 > Switching > Switches. Select Branch2-9300 and click the Tools tab. Run Adaptive Policy Counters to verify packets are being blocked.

---

## Use Case 4: Optimize User Experience with Real-Time Wireless Monitoring

### Scenario 1: Get to Know Your Network and See the Expected Behavior

**Persona:** Jordan Lee, Wireless Network Administrator at PseudoCo

**Demo Scenario:**

> It's the start of a busy week at PseudoCo, and Jordan Lee is eager to see how the company's latest investment in Wi-Fi 7 is paying off. With a growing number of employees using new laptops and phones equipped for Wi-Fi 7, expectations are high.
> 
> Jordan logs into the Meraki Dashboard, intent on making sure these next-gen clients are getting the experience they were promised.

**Pain Point:**

As PseudoCo rolls out Wi-Fi 7, there is high pressure to ensure these new devices deliver on their promise. Without clear visibility into how Wi-Fi 7 clients are actually performing on the network, it's difficult to verify improvements.

Cisco solutions:
• Cisco Meraki Dashboard: Centralized network and client monitoring
• Meraki Assurance: Real-time client health and performance insights
• Cisco Meraki Wi-Fi 7 Access Points

#### Step 1

**What?**

"Jordan reviews the summary of wireless clients in Branch4, paying close attention to Wi-Fi 7 capable devices."

**Why?**

To confirm that Wi-Fi 7 clients are connecting as expected and performing at peak efficiency.

**a)** Select Branch4. Navigate to Assurance > Clients. Select device with MAC: 24:eb:16:35:50:89, identified as a Wi-Fi 7 client.

**b)** Note the device capable Wi-Fi standards, you should see 6 GHz band, which is synonymous with Wi-Fi 7 support.

**c)** Go to Performance tab, to see how this device is performing on the 2.4 GHz, 5 GHz, and 6 GHz bands.

#### Step 2

**What?**

"Jordan accesses the Client summary page to see general trends and traffic patterns."

**Why?**

Quick access to summarized client health helps identify usage patterns and potential congestion.

**a)** In Branch2, navigate to Assurance > Clients. Explore the page. Notice the client information and general trends.

**b)** Click Settings (the Gear icon). Notice the other information you can display in the table.

**c)** Click to expand the Application Details list under the pie chart diagram to review common applications.

### Scenario 2: Identify and Troubleshoot Client Connectivity Issues

**Persona:** Carol Freeman, Network Administrator at PseudoCo

**Demo Scenario:**

> Carol receives complaints of slow Wi-Fi connections. Users are reporting trouble in video calls and slow file downloads.

**Pain Point:**

A poor Wi-Fi experience can be caused due to many reasons, such as access points operating in a congested channel or a client connecting to a far away AP.

Cisco solutions:
• Meraki Dashboard with Wireless Assurance
• Meraki AI-Enhanced Radio Resource Management (AI-RRM)

#### Step 1

**What?**

"Carol uses Cisco Meraki Wireless Access Points performance view."

**Why?**

Since we know users complain of slow Wi-Fi, we will first check the Wi-Fi performance metrics view for live real-time insights.

**a)** From the Network drop-down, choose Branch2. Navigate to Wireless > Access points. Click Packet Loss for details.

**b)** Identify access points exhibiting high packet loss. View the Average packet loss by SSID and time series view.

#### Step 2

**What?**

"Identify and analyze sources of wireless interference affecting the Meraki access points."

**Why?**

Checking the RF spectrum helps us find out if interference or channel congestion is causing packet loss.

**a)** Navigate to Wireless > Overview > RF Spectrum. Click the affected Branch2-AP1 to open AP Neighbors view.

**b)** Select the 5 Ghz band. Multiple APs operating on the same channel 149 may be causing high utilization.

#### Step 3

**What?**

"AI-Enhanced Radio Resource Management (AI-RRM) is enabled in the Meraki Dashboard."

**Why?**

Enabling AI-RRM allows the network to proactively detect and resolve RF interference and congestion.

**a)** Navigate to Wireless > Configure > Radio Settings. Click the RRM tab. Toggle on AI-RRM to Enable.

**b)** Scroll down to the Busy hour section. Meraki automatically calculates busy hours to avoid RRM changes during peak times.

### Scenario 3: Detect and Neutralize Rogue Access Points in Your Network

**Persona:** Sarah Brown, Sr. Wireless Architect at PseudoCo

**Demo Scenario:**

> One Monday morning, Sarah Brown is alerted by several helpdesk tickets: users are complaining about unreliable Wi-Fi and suspicious new networks showing up. A rogue access point can open the door to data breaches.

**Pain Point:**

Rogue access points can silently undermine security, allowing unauthorized devices onto the network.

Cisco solutions:
• Meraki Dashboard with Wireless Assurance
• Meraki Air Marshal

#### Step 1

**What?**

"Sarah reviews Meraki Air Marshal and determines there are rogue access points."

**Why?**

Rogue access points allow unintended access to the corporate network and resources.

**a)** Select Branch1. Navigate to Wireless > Air Marshal. From the dashboard, view SSIDs operating within the wireless spectrum.

**b)** Click the Rogue SSIDs tab. There is one Rogue SSID called hacker_ap1. Click it to view details.

**c)** Click Edit, select Contain and click Confirm. The AP will send de-authentication packets to prevent clients from connecting.

#### Step 2

**What?**

"Sarah physically locates and blocks the rogue access point."

**Why?**

Containing the SSID is only step one. The next step is to block it across the network.

**a)** Note the MAC address 2c:cf:67:42:c4:1f. Navigate to Network-wide > Clients and find matching MAC.

**b)** Select wlanpi-41f. In the client dashboard, view which switch it's connected to and change device policy to Block Access.

### Scenario 4: Identify and Resolve a Client's Network Access Issues

**Persona:** Alex Chen, Wireless Support Specialist at PseudoCo

**Demo Scenario:**

> A user logs a ticket: "I can connect to the IOT Wi-Fi, but I can't open any websites or access company resources." For Alex, this is a classic case of a connection that looks successful but fails in practice.

**Pain Point:**

A client can associate with the wireless network but still be left stranded if it doesn't receive a valid IP address from DHCP.

Cisco solution:
• Meraki Dashboard with Assurance: Immediate insights into client connection steps and failures

#### Step 1

**What?**

"Alex reviews wireless client connection logs to identify a DHCP failure."

**Why?**

To quickly determine that the root cause of the client's issue is a missing DHCP response.

**a)** Select Branch1. Navigate to Wireless > Access Points. In the Overview page, clients have a 0% DHCP success rate. Click DHCP Success.

**b)** Navigate to Assurance > Clients. Select client with MAC: 74:19:f8:16:14:16. The client is using an APIPA address.

**c)** Click the Connections tab. It clearly indicates a DHCP failure in the connection process.

### Scenario 5: Troubleshoot Why a Client Cannot Connect to the Network

**Persona:** Sam Patel, IT Support Specialist at PseudoCo

**Demo Scenario:**

> Kristi Holland from the Finance department reports that she can't connect to the corporate Wi-Fi in Branch1. Every connection attempt fails and payroll submissions are due within the hour.

**Pain Point:**

Authentication errors like wrong passwords are common and disruptive, but without clear diagnostics, IT can waste valuable time.

Cisco solutions:
• Meraki Dashboard with Assurance
• Meraki Access Manager: Detailed session logs

#### Step 1

**What?**

"Sam reviews Kristi's recent connection attempts and authentication logs."

**Why?**

To identify the issue and provide a fast resolution, minimizing downtime.

**a)** Select Branch1. Navigate to Assurance > Clients. Search for MAC address 74:19:f8:16:25:c1. The device fails to authenticate.

**b)** Go to the Connections tab. The Primary failure stage is Authentication.

**c)** Navigate to Access Manager > Session Log. Search for kholland@pseudoco.com. The reason is incorrect username and password.

### Scenario 6: Identify Connection Problems for One Specific Client

**Persona:** Emily Johnson, IT Support Engineer at PseudoCo

**Demo Scenario:**

> Alice, an employee, is unable to connect her laptop to the corporate wireless network. Her device just won't join the network despite several attempts.

**Pain Point:**

Troubleshooting individual client connection failures is challenging when everything on the network side is correctly configured.

Cisco solutions:
• Meraki Dashboard with Assurance
• Meraki Access Manager: Per-session logs

#### Step 1

**What?**

"Emily reviews Alice's connection attempts and authentication logs."

**Why?**

To quickly confirm that the issue is not due to a network or IT misconfiguration.

**a)** Select Branch1. Navigate to Assurance > Clients. Search for MAC address: 74:19:f8:16:22:c7.

**b)** Navigate to Wireless > Access points > Connection log to review connection attempts.

**c)** Navigate to Access Manager > Session Log. Alice's device is using MSCHAPv2, not supported by Meraki. Guide her to switch to PEAP or EAP-TLS.

---

## Use Case 5: Maintain Wired Network Uptime and Reliability Using Monitoring and Assurance Tools

### Scenario 1: Prevent Network Slowdowns: Get Alerts for Wired Network Problems

**Persona:** Harper Simmons, Network Specialist at PseudoCo

**Demo Scenario:**

> At PseudoCo, the wired network is the backbone of daily operations. Harper knows that if a switch or port experiences issues, the ripple effect can be immediate.

**Pain Point:**

Wired client issues can develop silently and go unnoticed until they disrupt business critical functions.

Cisco solutions:
• Meraki Dashboard: Real-time monitoring and proactive alerts
• Meraki Managed Catalyst and MS Switches

#### Step 1

**What?**

"Harper monitors for critical network alerts, such as STP root guard activations."

**Why?**

To quickly detect and neutralize threats like STP loops before they disrupt the business.

**a)** Select Branch1. Navigate to Assurance > Alerts. Click the "Root guard activated, STP discarding packets" alert.

**b)** View the AI-generated explanation of what triggered the alert and recommended actions.

### Scenario 2: Protect Network Uptime by Quickly Finding and Resolving Issues on Switch Ports

**Persona:** Ethan Kim, Network Support Lead at PseudoCo

**Demo Scenario:**

> During peak production hours, Ethan gets a frantic call: the main label printer in the warehouse is offline. With Meraki's monitoring tools, Ethan immediately pinpoints the root cause.

**Pain Point:**

A single misconfigured port can put the brakes on critical business functions.

Cisco solutions:
• Meraki Dashboard: Real-time monitoring
• Meraki Managed Catalyst and MS Switches

#### Step 1

**What?**

"Ethan investigates port forwarding issues caused by an access policy."

**Why?**

To restore critical device connectivity and ensure business operations aren't interrupted.

**a)** Select Branch1. Navigate to Switches > Branch1-MS130 and select port 14.

**b)** The port is not forwarding due to a MAC Allow List. Click Edit Port Configuration to update allowed MAC addresses.

### Scenario 3: Detect Device Connectivity Issues to Maintain Stability

**Persona:** Riley Morgan, Network Operations Center Analyst at PseudoCo

**Demo Scenario:**

> It's the middle of quarter end rush, and Riley notices several workstations in Branch3 are dropping offline every few minutes.

**Pain Point:**

Intermittent connectivity issues can silently erode productivity and trust in IT.

Cisco solutions:
• Meraki Dashboard
• Meraki-Managed Catalyst and MS Switches

#### Step 1

**What?**

"Riley diagnoses unstable connection affecting user connectivity."

**Why?**

Identify the root cause for intermittent issues with switch connectivity.

**a)** Select Branch3. Navigate to Switching > Switches. Click Branch3-C9300X-1. Review historical connectivity data and event logs.

### Scenario 4: Find Connection Failures: Identify Wired Client Problems

**Persona:** Jenna Patel, IT Service Desk Specialist at PseudoCo

**Demo Scenario:**

> Jenna's support phone rings: Dawn from Accounting can't connect to the wired network, and payroll submissions are due within the hour.

**Pain Point:**

Complex, misapplied policies can block users at the worst possible moment.

Cisco solutions:
• Meraki Dashboard
• Meraki Access Manager
• Meraki-Managed Catalyst and MS Switches

#### Step 1

**What?**

"Jenna troubleshoots a wired client connection issue reported by user Dawn Turner."

**Why?**

To resolve user frustration quickly and ensure network access policies are correctly enforced.

**a)** Select Branch1. Navigate to Assurance > Clients. Select device with MAC: f4:4d:ad:05:6e:ee. Port is connected but blocked due to access policy.

**b)** Navigate to Access Manager > Session Log. User dturner@pseudoco.com was rejected due to "Reject Too Many Groups" rule.

**c)** Navigate to Access Manager > Users and search for Dawn Turner. She is a member of all 3 groups, causing rejection.

### Scenario 5: Stay in Control: Beware of All Configuration Changes

**Persona:** Carol Freeman, Network Administrator at PseudoCo

**Demo Scenario:**

> Just after lunch, printers stop working across Branch3. Carol quickly suspects a recent network change. Using the Meraki Dashboard, she reviews the configuration history.

**Pain Point:**

Undocumented or accidental network changes can cripple shared resources.

Cisco solution:
• Meraki Dashboard: Complete visibility of the catalyst infrastructure

#### Step 1

**What?**

"We navigate to the Meraki Dashboard to troubleshoot by investigating the config history."

**Why?**

Track configuration changes over time, providing a clear audit trail.

**a)** Choose Branch3. Navigate to Switching > Switches. Click a Switch, then click Config History.

**b)** The dashboard highlights a recent edition of an access control list preventing user subnet from accessing printers.

---

## Use Case 6: Improve Time to Resolution with Comprehensive Network Monitoring via Meraki and ThousandEyes Integration

### Scenario 1: Accelerate Troubleshooting with Meraki and ThousandEyes: Application Performance Degradation

**Persona:** Carol Freeman, Network Administrator at PseudoCo

**Demo Scenario:**

> Carol receives a call from a user reporting painfully slow speeds when trying to download files from Box, their cloud-based collaboration platform. The problem could be anywhere—local Wi-Fi, the office switch, the WAN, the ISP, or even the Box app itself.

**Pain Point:**

Without end-to-end visibility, Carol would be left scrambling to identify which segment is causing the issue.

Cisco solutions:
• Meraki Dashboard with ThousandEyes Integration
• ThousandEyes Enterprise Agents
• ThousandEyes Endpoint Agents

#### Step 1

**What?**

"We start in Cisco Meraki Dashboard with ThousandEyes integration. We know Box.com is slow to load so we need to address it quickly."

**Why?**

Initiating troubleshooting in Cisco Meraki with ThousandEyes integration will quickly pinpoint the issue.

**a)** Select Branch1. Navigate to Insights > Web App Health. Click the Box application.

**b)** Click VIEW TRENDS for Branch2. ThousandEyes Enterprise Agents provide continuous testing from MX firewalls.

**c)** Navigate to Assurance > Analytics > Overview. From the Time drop-down, choose Last Day.

**d)** Scroll down to Applications tile. Click Box for the alert flyout window. Click Internet to focus on connectivity.

**e)** Click the first Packet Loss alert. Click "Investigate further in ThousandEyes" to see correlated metrics.

**f)** Click Agent to Server. View the path visualization to see nodes between network and Box application server with packet loss.

### Scenario 2: Eliminating Blind Spots: Proactive Monitoring for Mobile Devices

**Persona:** Marcus, IT Operations Manager at PseudoCo

**Demo Scenario:**

> PseudoCo's warehouse and retail teams rely on Android-based portable barcode scanners to track inventory. Recently, users have been complaining that their scanners frequently lose connection.

**Pain Point:**

Troubleshooting mobile device connectivity is notoriously difficult. Issues can be caused by Wi-Fi handoffs, dead zones, or unpredictable application behavior.

Cisco solutions:
• ThousandEyes Mobile Agents: Installed directly on barcode scanners
• ThousandEyes Dashboard: Centralizes monitoring of all mobile agents

#### Step 1

**What?**

"Marcus deploys ThousandEyes Mobile Agents to Android barcode scanners and uses the ThousandEyes Dashboard to monitor live connectivity."

**Why?**

This approach enables Marcus to pinpoint exactly where and when connectivity drops happen.

**a)** In ThousandEyes Dashboard, navigate to Endpoint Experience > Agent Views. Search for "Barcode-Scanner-1".

**b)** Navigate to Segment Visualization tab and click Applications. View unhealthy status for applications used by PseudoCo's teams.

### Scenario 3: Troubleshoot Webex Calling Issues with Control Hub, ThousandEyes, and Meraki Integrations

**Persona:** Sarah Jennings, Help Desk Administrator at PseudoCo

**Demo Scenario:**

> Sarah received a call from Anita, one of the company's employees. Anita explained that she was experiencing intermittent issues with her Cisco 9861 desk phone—calls were dropping, and the audio quality was poor.

**Pain Point:**

Without integration of Webex Control Hub, Cisco ThousandEyes, and Cisco Meraki, troubleshooting would be much more time-consuming.

Cisco solutions:
• Webex Control Hub
• ThousandEyes
• Meraki Dashboard

#### Step 1

**What?**

"Sarah logs into Webex Control Hub so she can view the calls made by Anita."

**Why?**

Control Hub is the single place of information for all Webex Calls.

**a)** Log into Webex Control Hub. Click Troubleshooting. Search for Anita's calls using: pseudococampus+anitacooper@gmail.com

**b)** Find a call listed as Poor and select it. Scroll down to End-to-cloud network path card.

**c)** Click one of the red paths for Anita. Click Launch ThousandEyes dashboard to see where packet loss is happening.

**d)** Go back to Control Hub. Under Anita Cooper, click Check Meraki dashboard to view the phone information and packet captures.

---

## Use Case 7: Use Splunk Enterprise to Search, Analyze, and Visualize Your Meraki and ThousandEyes Data

### Scenario 1: Explore and Interact with Splunk Enterprise

**Persona:** Cindy Cross, Network Wireless Administrator at PseudoCo

**Demo Scenario:**

> Cindy is responsible for conducting regular network audits. She initiates this process by logging into Meraki Dashboard and ThousandEyes. During her review, she identifies connectivity issues in both applications but struggles to establish correlation.

**Pain Point:**

Without an end-to-end data and correlation engine, Cindy would spend considerable manual work to identify if what she sees in ThousandEyes is a result of what she sees on the Meraki network side.

Cisco solutions:
• Splunk Enterprise
• Meraki Dashboard
• ThousandEyes

#### Step 1

**What?**

"We start in Splunk Enterprise to understand how data is collected, visualized and correlated across various data sources."

**Why?**

The Splunk Dashboard provides administrators with a comprehensive overview of network health across Meraki and ThousandEyes organizations.

**a)** In the Splunk Enterprise Web UI, click the Dashboard tab. The custom PseudoCo Campus Health dashboard displays by default.

**b)** Investigate the first tab, Global & Wired. This shows organization-wide network health from Meraki Dashboard.

**c)** Switch to the Wireless Health tab. View wireless network statistics and most commonly seen issues.

**d)** Switch to the ThousandEyes Monitoring tab. View popular tests and most commonly seen failure reasons.

**e)** Scroll down to check ThousandEyes Network Test results, including latency, jitter, and loss metrics.

**f)** (OPTIONAL) Click the magnifying glass icon on any widget to see how they were built with SPL queries.

---

*© 2025 Cisco and/or its affiliates. All rights reserved.*
