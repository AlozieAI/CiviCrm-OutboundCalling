# AI-Driven Outbound Campaign Automation with CiviCRM and VAPI

**AI-Driven Outbound Campaign Automation with CiviCRM and VAPI**

This project demonstrates the integration of an open-source CRM with complex api documention, CiviCRM, with an AI phone agent solution, VAPI, to automate outbound calling campaigns. Utilizing the no-code platform Make, we orchestrate workflows that extract contacts from specific CiviCRM groups, initiate AI-driven phone calls, and update contact group memberships based on call outcomes. This setup effectively simulates an AI-powered dialer for automated outbound campaigns.

**Project Overview**

The automation process involves the following steps:

Retrieve Contact Groups: Utilize CiviCRM's API to fetch all contact groups within the CRM.

Select Target Group: Identify and select a specific group designated for outbound campaigns.

Extract Contacts: Pull all contacts from the chosen group, ensuring each contact has valid phone numbers.

Initiate AI Calls: Employ VAPI to place calls to each contact, leveraging AI agents equipped with predefined prompts and voices.

Monitor Call Status: After each call, retrieve call details to determine if the contact was successfully reached.

Update Contact Groups: Based on the call outcome, remove the contact from the outbound campaign group and optionally add them to a different group for further actions, such as follow-ups or appointment scheduling.

**Technical Implementation**

CiviCRM API Integration

The integration with CiviCRM is facilitated through its RESTful API (APIv4). This API allows for efficient data retrieval and manipulation, including fetching contact groups and updating contact memberships. 

Detailed documentation on APIv4 REST can be found here: [CiviCrm API Documention](https://docs.civicrm.org/dev/en/latest/api/v4/rest/)

**CIVICRM DOCUMENTATION**

AI Phone Agent with VAPI

VAPI is utilized to automate phone calls to contacts. By integrating VAPI with CiviCRM, we can programmatically initiate calls and handle responses, enabling seamless communication workflows.

Workflow Automation with Make

The no-code platform Make is employed to design and execute the automation workflows. Make allows for the orchestration of various services, including CiviCRM and VAPI, without the need for extensive coding.

**Prerequisites**

CiviCRM: Ensure you have access to a CiviCRM instance with APIv4 enabled.

VAPI Account: Set up an account with VAPI to obtain the necessary credentials for API access.

Make Account: Create an account on Make to design and manage your automation workflows.

**Setup Instructions**

Configure CiviCRM API Access: Follow the CiviCRM APIv4 REST documentation to set up API access: 

**CIVICRM DOCUMENTATION**

Design Workflows in Make: Utilize Make's interface to create workflows that connect CiviCRM and VAPI, implementing the steps outlined in the project overview.

Test the Automation: Run the workflows with test data to ensure proper functionality, including successful API calls and correct handling of call outcomes.

Deploy the Automation: Once testing is complete, deploy the workflows to operate on live data, automating your outbound calling campaigns.

**Additional Resources **


CiviCRM APIv4 REST Documentation: Provides comprehensive guidance on using CiviCRM's APIv4 REST interface - https://docs.civicrm.org/dev/en/latest/api/v4/rest/
CIVICRM DOCUMENTATION

CiviCRM JavaScript Standards: Offers best practices for JavaScript development within the CiviCRM ecosystem - [CiviCrm Best Standards](https://docs.civicrm.org/dev/en/latest/standards/javascript/)

CIVICRM DOCUMENTATION

By following this guide, you can effectively automate outbound calling campaigns using AI-driven phone agents, enhancing your organization's outreach capabilities.
