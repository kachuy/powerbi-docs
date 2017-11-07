---
title: Connect to comScore Digital Analytix with Power BI
description: comScore Digital Analytix for Power BI
services: powerbi
documentationcenter: ''
author: joeshoukry
manager: erikre
backup: maggiesMSFT
editor: ''
tags: ''
qualityfocus: no
qualitydate: ''

ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 10/16/2017
ms.author: yshoukry

---
# Connect to comScore Digital Analytix with Power BI
Visual and explore your comScore Digital Analytix data in Power BI with the Power BI content pack. The data will be refreshed automatically once per day.

Connect to the [comScore content pack for Power BI.](https://app.powerbi.com/getdata/services/comscore)

Note: To connect to the content pack you need a comScore DAx user account and have comScore API access. More [details](#Requirements) below.

## How to connect
1. Select Get Data at the bottom of the left navigation pane.
   
   ![](media/powerbi-content-pack-content-pack/getdata.png)
2. In the **Services** box, select **Get**.
   
   ![](media/powerbi-content-pack-content-pack/services.PNG)
3. Select **comScore Digital Analytix** \> **Get**.
   
   ![](media/powerbi-content-pack-content-pack/comscore.png)
4. Provide the datacenter, comScore Client ID and Site you’d like to connect to. For more details on how to find these values, please see [Finding your comScore Parameters](#FindingParams) below.
   
   ![](media/powerbi-content-pack-content-pack/parameters.PNG)
5. Provide your comScore username and password to connect. See details on finding this value below.
   
   ![](media/powerbi-content-pack-content-pack/creds.PNG)
6. The import process will begin automatically. When complete, a new dashboard, report and model will appear in the Navigation Pane. Select the dashboard to view your imported data.

**What Now?**

* Try [asking a question in the Q&A box](powerbi-service-q-and-a.md) at the top of the dashboard
* [Change the tiles](powerbi-service-edit-a-tile-in-a-dashboard.md) in the dashboard.
* [Select a tile](powerbi-service-dashboard-tiles.md) to open the underlying report.
* While your dataset will be schedule to refreshed daily, you can change the refresh schedule or try refreshing it on demand using **Refresh Now**

<a name="Requirements"></a>

## System requirements
A comScore DAx user account and access to the comScore DAx API is required to connect. Please contact your comScore DAx admin to confirm your account.

<a name="FindingParams"></a>

## Finding parameters
Details on how to find each of your comScore parameters is below.

**Data Center**

The data center you connect to is determined by the URL you navigate to in comScore.

If you use https://dax.comscore.com, enter “US”, if you use https://dax.comscore.eu, enter “EU”.

![](media/powerbi-content-pack-content-pack/comscore_URL.png) 

**Client**

The Client is the same one you provide when signing into comScore DAx.

![](media/powerbi-content-pack-content-pack/comscore_signin.PNG) 

**Site**

The comScore site determines which site you’d like to see the data from. You can find the list of sites from your comScore account.

![](media/powerbi-content-pack-content-pack/comscore_sites.PNG)

### See also
[Get started in Power BI](powerbi-service-get-started.md)

[Get data in Power BI](powerbi-service-get-data.md)
