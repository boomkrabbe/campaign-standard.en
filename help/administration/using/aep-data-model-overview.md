---
title: Experience Data Model overview
description: Experience Data Model (XDM) is a standard set of data schemas into which data might be ingested for use with Adobe Experience Platform solutions and products.
page-status-flag: never-activated
uuid: 867b1c4b-4c79-4c52-9d0a-ef71993e50a2
contentOwner: sauviat
products: SG_CAMPAIGN/STANDARD
audience: administration
content-type: reference
topic-tags: configuring-channels
discoiquuid: 406c955a-b2d2-4099-9918-95f5fa966067

internal: n
snippet: y
---

# Experience Data Model overview {#experience-data-model-overview}

>[!IMPORTANT]
>
>Campaign Standard Data service is currently in beta, which may be subject to frequent updates without notice. Customers are required to be hosted on Azure (currently in beta for North America only) to access these capabilities. Please reach out to Adobe Customer Care if you would like access.

Experience Data Model (XDM) is a standard set of data schemas into which data might be ingested for use with Adobe Experience Platform solutions and products.

The creation and management of XDM schemas is available with a dedicated API or with the XDM user interface.

## XDM workspace {#xdm-workspace}

XDM Workspace affords the ability to view, create, and extend data schemas.

To access the XDM user interface, open Adobe Experience Platform. Navigate to the Data Model window to create or extend an XDM schema.

Consult the full [XDM Workspace documentation](https://www.adobe.io/apis/experienceplatform/home/xdm/xdmservices.html#!api-specification/markdown/narrative/technical_overview/schema_registry/xdm_system/xdm_system_in_experience_platform.md).

![](assets/aep_xdmworkspace.png)

## XDM API {#xdm-api}

You can perform the following actions via the XDM Schema API:

* View a list of existing schemas
* View a specific schema Extend an existing schema
* Add fields to an extension
* Create and update a new schema
* View schema descriptors
* Create, update, and delete schema descriptors

All the details to manipulate API calls are available in the [Developer Guide](https://www.adobe.io/apis/experienceplatform/home/xdm/xdmservices.html#!api-specification/markdown/narrative/technical_overview/schema_registry/schema_registry_developer_guide.md).
