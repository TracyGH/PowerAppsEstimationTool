# PowerAppsEstimationTool
Estimate the cost of your Power Apps application and compare costs of the different Microsoft Power Apps licensing models. 

# To Power Apps or to custom dev?

That is often the question. 
While custom development will typically incur more costs up front and take longer to build, Power Apps will incur licensing fees for the life of the application. When deciding the best fit for your solution and organization, it can be helpful to understand the potential Power Apps licensing costs. 

### Power Apps Estimation Tool How-To:
:white_check_mark: The only required value is an estimate of the number of unique monthly visitors your app will receive.  

:white_check_mark: The Dataverse Database, File, and Log usage values can be left blank. The tool will provide the allotted Dataverse capacities for each PowerApps licensing model. Additional Dataverse capacity can be purchased for [Premium and per app models](https://learn.microsoft.com/en-us/power-platform/admin/add-storage#purchase-add-on-storage-capacity) as well as [pay-as-you-go](https://learn.microsoft.com/en-us/power-platform/admin/pay-as-you-go-meters?tabs=image#how-do-meters-work).  

:white_check_mark: If you provide Dataverse usage estimates above the alloted capacities, the tool will automatically calculate the difference and include that in the monthly cost estimates.  

:white_check_mark: The tool will also provide the number of requests allotted to your application per 24 hours.

![license](https://github.com/TracyGH/PowerAppsEstimationTool/assets/38665906/2ee54b83-ec74-40ff-9050-9f2bede6dae0)

> [!NOTE]
> There are additional Microsoft subscriptions beyond Power Platform that grant Dataverse capacity
> entitlements. Please see [this page](https://docs.microsoft.com/en-us/office365/servicedescriptions/project-online-service-description/project-web-service-description#project-for-the-web-and-microsoft-dataverse) for details related to Project for the web, as well as the [Dynamics 365 Licensing Guide](https://go.microsoft.com/fwlink/?LinkId=866544&clcid=0x409) for information related to other entitlements.

Calculations and values were derived from the following resources:  
:thumbsup: [Power Apps and Power Automate Licensing Guide](https://go.microsoft.com/fwlink/?linkid=2085130)  
:thumbsup: [Power Platform Pay-as-you-go meters](https://learn.microsoft.com/en-us/power-platform/admin/pay-as-you-go-meters)  
:thumbsup: [Add Microsoft Dataverse storage capacity](https://learn.microsoft.com/en-us/power-platform/admin/add-storage#purchase-add-on-storage-capacity)  

If you see something I forgot or miscalculated - please open a repo issue!:sun_with_face:
