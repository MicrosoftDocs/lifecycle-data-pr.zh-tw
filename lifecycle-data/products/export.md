---
title: 生命週期資料匯出
description: 匯出產品生命週期資訊
ms.date: 09/02/2020
ms.openlocfilehash: ea84b31ae6fc22a46b93c8824e60a8a0bd84f34d
ms.sourcegitcommit: adca90be401b37b1ccfe6a6ce3fe265bd2e1f0de
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/02/2020
ms.locfileid: "943098"
---
# <a name="lifecycle-data-export"></a><span data-ttu-id="785bc-103">生命週期資料匯出</span><span class="sxs-lookup"><span data-stu-id="785bc-103">Lifecycle data export</span></span>

> [!IMPORTANT]
> <span data-ttu-id="785bc-104">此頁面正在開發中。</span><span class="sxs-lookup"><span data-stu-id="785bc-104">This page is under development.</span></span>

## <a name="export-all-products"></a><span data-ttu-id="785bc-105">匯出所有產品</span><span class="sxs-lookup"><span data-stu-id="785bc-105">Export all products</span></span>
<span data-ttu-id="785bc-106">按一下下列專案，以匯出所有產品的生命週期資料：</span><span class="sxs-lookup"><span data-stu-id="785bc-106">Export lifecycle data for all products by clicking below:</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="785bc-107">匯出所有產品</span><span class="sxs-lookup"><span data-stu-id="785bc-107">Export All Products</span></span>](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a><span data-ttu-id="785bc-108">依系列和群組匯出產品</span><span class="sxs-lookup"><span data-stu-id="785bc-108">Export products by Family and Group</span></span>
<span data-ttu-id="785bc-109">選取系列，然後選取要匯出的群組。</span><span class="sxs-lookup"><span data-stu-id="785bc-109">Select a Family and then a Group to export.</span></span> <span data-ttu-id="785bc-110">附注：選取 [群組值時，就會開始匯出]。</span><span class="sxs-lookup"><span data-stu-id="785bc-110">Note: Export will begin when Group value is selected.</span></span> 

> [!div class="op_multi_selector" title1="家庭" title2="Group"]
> - [ ( .NET |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET')
> - [ ( .NET | .NET) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET'%20and%20parent/parent/name%20eq%20'.NET')
> - [ (Azure |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure')
> - [ (Azure |AI) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'AI')
> - [ (Azure |Azure) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Azure')
> - [ (Azure |資料庫) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Databases')
> - [ (Azure |其他) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Other')
> - [ (Dynamics |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics')
> - [ (Dynamics |Dynamics) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics')
> - [ (Dynamics |Dynamics 365) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20365')
> - [ (Dynamics |Dynamics AX) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20AX')
> - [ (Dynamics |Dynamics C5) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20C5')
> - [ (Dynamics |Dynamics CRM) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20CRM')
> - [ (Dynamics |Dynamics GP) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20GP')
> - [ (Dynamics |Dynamics NAV) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20NAV')
> - [ (Dynamics |Dynamics POS) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20POS')
> - [ (Dynamics |Dynamics RMS) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20RMS')
> - [ (Dynamics |Dynamics SL) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20SL')
> - [ (Dynamics |其他) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Other')
> - [ (運算式 |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression')
> - [ (運算式 |運算式) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression'%20and%20parent/parent/name%20eq%20'Expression')
> - [ (Microsoft 365 |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365')
> - [ (Microsoft 365 |企業行動性 + 安全性) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Enterprise%20Mobility%20%2B%20Security')
> - [ (Microsoft 365 |身分識別管理) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Identity%20Management')
> - [ (Microsoft 連接的服務架構 |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework')
> - [ (Microsoft 連接的服務架構 |連接的服務框架) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework'%20and%20parent/parent/name%20eq%20'Connected%20Services%20Framework')
> - [ (Microsoft 客戶維護架構 |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework')
> - [ (Microsoft 客戶維護架構 |客戶維護框架) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework'%20and%20parent/parent/name%20eq%20'Customer%20Care%20Framework')
> - [ (Microsoft Edge |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Edge')
> - [ (Microsoft Edge |Edge) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Edge'%20and%20parent/parent/name%20eq%20'Edge')
> - [ (Microsoft Internet Explorer |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer')
> - [ (Microsoft Internet Explorer |Internet Explorer) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer'%20and%20parent/parent/name%20eq%20'Internet%20Explorer')
> - [ (Microsoft Office |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office')
> - [ (Microsoft Office |用戶端) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Client')
> - [ (Microsoft Office |安全性) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Security')
> - [ (Microsoft Office |伺服器) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Server')
> - [ (Microsoft Servers |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers')
> - [ (Microsoft Servers |BizTalk Server) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'BizTalk%20Server')
> - [ (Microsoft Servers |Commerce Server) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Commerce%20Server')
> - [ (Microsoft Servers |Content Management Server) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Content%20Management%20Server')
> - [ (Microsoft Servers |主機整合伺服器) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Host%20Integration%20Server')
> - [ (Microsoft Servers |智慧應用程式閘道) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Intelligent%20Application%20Gateway')
> - [ (Microsoft Servers |安全性) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Security')
> - [ (Microsoft System Center |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center')
> - [ (Microsoft System Center |System Center) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center'%20and%20parent/parent/name%20eq%20'System%20Center')
> - [ (Silverlight |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight')
> - [ (Silverlight |Silverlight) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight'%20and%20parent/parent/name%20eq%20'Silverlight')
> - [ (SQL Server |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server')
> - [ (SQL Server |Power BI) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'Power%20BI')
> - [ (SQL Server |SQL Server) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'SQL%20Server')
> - [ (Visual Studio |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio')
> - [ (Visual Studio |Visual Studio) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio'%20and%20parent/parent/name%20eq%20'Visual%20Studio')
> - [ (Windows |所有) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows')
> - [ (Windows |用戶端) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Client')
> - [ (Windows |IoT) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'IoT')
> - [ (Windows |行動裝置) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Mobile')
> - [ (Windows |安全性) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Security')
> - [ (Windows |伺服器) ](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Server')

## <a name="export-products-by-end-of-support-date"></a><span data-ttu-id="785bc-171">在支援日期之後匯出產品</span><span class="sxs-lookup"><span data-stu-id="785bc-171">Export products by end of support date</span></span>
<span data-ttu-id="785bc-172">選取 [一年]，以查看產品是否到達支援終止。</span><span class="sxs-lookup"><span data-stu-id="785bc-172">Select a year to see products reaching the end of support.</span></span> <span data-ttu-id="785bc-173">附注：選取 [年份] 值時，就會開始匯出。</span><span class="sxs-lookup"><span data-stu-id="785bc-173">Note: Export will begin when Year value is selected.</span></span>

> [!div class="op_single_selector"]
> - [2002](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2002))
> - [2003](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2003))
> - [2004](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2004))
> - [2005](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2005))
> - [2006](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2006))
> - [2007](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2007))
> - [2008](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2008))
> - [2009](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2009))
> - [2010](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2010))
> - [2011](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2011))
> - [2012](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2012))
> - [2013](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2013))
> - [2014](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2014))
> - [2015](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2015))
> - [2016](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [2017](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [2018](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [2019](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [2020](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
> - [2021](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2021))
> - [2022](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2022))
> - [2023](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2023))
> - [2024](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2024))
> - [2025](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2025))
> - [2026](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2026))
> - [2027](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2027))
> - [2028](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2028))
> - [2029](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2029))
> - [2030](https://app-omaha-dev.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2030))