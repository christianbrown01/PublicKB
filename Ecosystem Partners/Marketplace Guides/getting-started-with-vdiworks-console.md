{{{
  "title": "Getting Started With VDIworks Console Server",
  "date": "08-10-2015",
  "author": "VDIworks",
  "attachments": [],
  "contentIsHTML": false
}}}

![VDIworks logo](../../images/VDIworkls_color_logo_smallerl.png)

### Technology Profile
VDP is an end to end VDI management system. It combines connection brokering, VM management, health, alerting, inventory, physical management, and remote protocols.


### Description
This CenturyLink Blueprint provides a click-through solution to install and configure VDIworks VDP Management Console on the Windows Server platform.

For more information, please visit [http://www.vdiworks.com/](http://www.vdiworks.com)

### Audience
CenturyLink Cloud Users

### Impact
After reading this article, the user should feel comfortable installing the Host Agent on a CenturyLink Cloud server.

### Prerequisite
*  Access to the CenturyLink Cloud platform as an authorized user.
*  A SQL Server machine in your Centurylink Cloud account, along with it's IP address and credentials.

### Postrequisite
*  If you want to access your application over the internet, please perform the following tasks after you receive an email notifying you that the Blueprint completed successfully:

1. If you need to connect to your server via the Internet, [Add a Public IP](../../Network/how-to-add-public-ip-to-virtual-machine.md) to your server through Control Portal.

2. [Allow incoming traffic](../../Network/how-to-add-public-ip-to-virtual-machine.md) for desired ports by clicking on the Servers Public IP through Control Portal and configuring appropriately.
  * Ports needed for Public Access: RDP 3389, TCP&UDP 8004, 6502

- Alternatively, you can use the CenturyLink Cloud VPN that is available through the Control portal.  

### Deploying VDIworks VDP Console Server
VDP Console is available as a Blueprint for deployment on a new server.

#### Steps to deploy VDIworks Console Server
1. Locate and Select the VDIworks VDP CS Blueprint and Deploy
  1. Starting from the CenturyLink Control Panel, navigate to the Blueprints Library.
  2. Search for 'VDIworks VDP' in the keyword search on the right side of the page.
  3. Locate the 'VDIworks VDP Concole Server' Blueprint

2. Choose and Deploy the Blueprint. Click the 'Install VDIworks VDP Console Server' Blueprint.

3. Configure the Blueprint.   Complete the information below:

  1. Enter a Password for the Server and repeat to confirm.
  2. Select a Group for your server, e.g. Default Group
  3. Select a Network
  4. Select a Primary DNS, e.g. Manually Specify
  5. Select a Secondary DNS, e.g. Manually Specify
  6. Select a Server Type, e.g. Standard
  7. Select a Service Level
  8. Create a Server Name.
  9. Create an SQL System Administrator Password and repeat to confirm.
  10. Select an SQL Version, e.g. 2008 r2 Standard
  11. Select SQL Features to be included
     * Database Engine Services
     * Full Text Search
     * Analysis Services
     * Reporting Services
     * Management Tools
     * Documentation Components
     * Integration Services
     * Connectivity Components
  12. Select Database Engine Collation, e.g. SQL_Latin1_General_CP1_CI_AS
  13. Choose Analysis Service Mode, e.g. MultiDimensional
  14. Create an SQL Instance Name
  15. Enter SQL SA Password

Proceed to Step 2.

4. **Review Blueprint and Deploy**

### Access VDIworks VDP Console Server
 After your Blueprint Deploys successfully, please follow these instructions to access your server:

  1. Watch email for notification of the deployment completion.
  2. Log in to your server.
  3. Start the VDIworks VDP Console and login using your Server Account.

### Pricing
For pricing information please contact us through [http://www.vdiworks.com/contact-vdiworks/](http://www.vdiworks.com/contact-vdiworks/)

### About VDIWorks
 Headquartered in Austin, Texas and founded in 2007, VDIworks is a leading provider of Virtual Desktop enablement and management software. Our solution is built on 10 years of pioneering work in the fields of centralized computing and virtualization. Our innovation has been recognized with 6 awarded and over 12 pending patents thus far. We offer the ultimate flexibility and preserves customer choice by giving customers the ability to deploy the right solution for the right user type, utilize any back-end hardware, end-point user access device or virtualization technology for desktop virtualization.  One of the industry's most reputable benchmarks of segment leadership, Computer Reseller News (CRN) has included VDIworks in their Top 100 Virtualization Vendors for several consecutive years and again most recently in the top 50 in 2013.

### Frequently Asked Questions

#### Who should I contact for support?
* For issues related to deploying the VDIworks Blueprint on CenturyLink Cloud, Licensing or Accessing the deployed software, please visit the [VDIworks website](http://www.vdiworks.com/) or email [support@vdiworks.com](mailto:support@vdiworks.com)
* For issues related to cloud infrastructure (VM's, network, etc), or is you experience a problem deploying the Blueprint or Script Package, please open a CenturyLink Cloud Support ticket by emailing [noc@ctl.io](mailto:noc@ctl.io) or [through the CenturyLink Cloud Support website](https://t3n.zendesk.com/tickets/new).
