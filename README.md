# Statement of Work - Automation for Snow melting machine

A document prepared by 
Ashtam Singh on 24st August 2020

## Table of Content

* Executive Summary
* Delivery Scope
* Device APIs
* Maintenance
* Exclusions
* Deliverables
* Customer Responsibilities
* Acceptance Criteria
* Assumptions



## Executive Summary
This documentation is to serve as a 'Statement of Work' or SOW for controlling snow melting machine to enhance and empower Administration. The advancement in the field of IoT, Networks, Computing and Data Science has made possible Integrated systems that can help business. Such a system would include a means to capture, catalogue and analyze data, along with tools to enforce 'business logic'.

Ashtam Singh will work with IdeaUsher to:

* Designing the architecture for connecting and controlling the device to cloud.
* Designing the BLE API for WiFi Provisioning.
* Designing the automatic unique ID generation for devices. 
* Setting up the Mqtt Broker on client server.
* Develop nodejs application bridge.
* Develop and Engineer the system.
* Provide documentation of the new system.
* Knowledge Transfer/Integrate with IdeaUsher.

Ashtam Singh proposes to design, develop and provide installation of v1.0 of the proposed system to IdeaUsher.
This activity will require 2 weeks.

The Value Proposition of using Ashtam Singh for this project are:
* Proven engineering techniques for making Integrated systems.
* Leveraging his experience in working with IoT toolkit (ESP) to bootstrap your effort. 
* Using subject matter experts to complete the project quickly. Rapid project completion minimizes disruptions and allows organizations to realize cost-saving quickly.

## Delivery Scope

* Project Definition
    - A review of the current system which helps in the firmware developing of the devices.
    - A project kickoff meeting to discuss and document the complete scope of Snow Melting Machine and the goals and requirements of this project.

## Device APIs

* Admin SDK / APIs for Devices Native packages to interact with the devices:-
    - Controlling manual mode
    - Provisioning device wifi
    - Check if wifi is connected or not
    - Device uptime
    - Set/Get state of the Heating mode
    - Set/Get state of Snowing mode
    - Set/Get state of Temp Limit mode
    - Set/Get state of Ground Limit mode


## Maintenance (if required)
The period after the development for maintaining the product to be discussed with the Client as it incurred extra charges.

## Exclusions
The followings are excluded from the project scope
* The packages used and maintained by Ashtam Singh for interfacing with IoT Devices.

## Deliverables
The deliverables are listed below.

* Wifi provisioning is provided on the end-user device so that end-user can easily connect their router to the system. Below is the step-wise guide. 
![WiFi Flow](https://github.com/ashtam55/Sow_brewing_automation/raw/master/Wifi%20provisioning%20flow.png)
* Wifi provisioning can also be done via BLE APIs of the device and can be integrated with the Client proprietary application.

* Snowmatic Devices Proposed Architecture
![Snowmatic-flow](https://github.com/ashtam55/SOW_SnowMelting_Machine/blob/master/Snowmatic-flow.png)
* Every device is configured with its Unique ID derived from their MAC address. These ID's is used by the End-User for adding devices in the Client mobile app.
Now every request which is coming to the Cloud is processed according to this ID and forward to devices accordingly. This Solution is scalable, fast and cost effective.

* Mqtt broker.

* Nodejs script for pushing and retriving device data from firebase.

* Software
Access top-level Git repositories for the hardware SDKs and APIs.

* Documentation for the proposed changes in the system.


## Customer Responsibilities
* The nature of this engagement dictates that Ashtam Singh receive a frequent and enthusiastic response from the appropriate personnel.
* A weekly review between the Ashtam Singh and the IdeaUsher or his designate will ensure that the expectations of this engagement are met.
* Client will assign a key contact who will be responsible for providing Ashtam Singh with information, access to personnel, and facility access if required.
* Client will provide a work area space with desk, chair, Internet access for use by Ashtam Singh to conduct project business while working on-site.


## Acceptance Criteria
After this evaluation, all deliverables for this phase will be presented to IdeaUsher for review.

IdeaUsher or his representative will have Seven business days from the date of delivery of any document that is a deliverable to review it and request any changes.  If Ashtam Singh does not receive notification of any required changes within this period, the document will be deemed to have been accepted without modification and will be reissued as a final copy.

If Ashtam Singh is notified by IdeaUsher, within the above time frame, of any changes required, Ashtam Singh will within two business days of such notification implement those changes as have been agreed between the parties.  A final copy of the document will then be submitted to IdeaUsher.

## Assumptions
* General
    * All documentation created for this project will be available in hard copy and electronic format.
    * Any modifications to the scope of work will be handled through a change control process and will be agreed to by both parties.

* Commercial
    * Additional costs may be incurred where any delay not under the control of Ashtam Singh that causes his personnel to not fulfil their scheduled tasks.
    * IdeaUsher will be available at the time of completion of the build phase so that all documentation can be accepted and signed.
    * Additional costs may be incurred where any work scheduled to be undertaken by Ashtam Singh is postponed by IdeaUsher after 24 hours of its commencement.
    * All changes to the schedule or technical requirements must be provided to Ashtam Singh in written format. Email is included as written format. Receipt of all correspondence should be confirmed by phone wherever possible.
    * IdeaUsher has accepted the costs/times estimate as detailed in this document
    * IdeaUsher has accepted the Ashtam singh standard terms and conditions mentioned above.


## Approved by
Name:   
Date:   
Position:   
