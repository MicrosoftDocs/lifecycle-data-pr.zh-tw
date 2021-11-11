---
title: 生命週期資料匯出指南
description: 匯出產品生命週期資訊指南
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546762"
---
# <a name="lifecycle-data-export-guidance"></a>生命週期資料匯出指南
這份文件說明如何使用產品匯出檔案。

## <a name="query-information"></a>查詢資訊
在 Excel 文件中，有一些欄位可協助識別產品資料表中填入的資料。

### <a name="end-of-support"></a>終止支援
支援的結束值會依據產品的支援日期或發行結束日期來篩選產品。

可能的值： 所有 (未套用任何篩選)、年份及範圍。

### <a name="family"></a>系列
系列值會根據其在階層中稱為「家族」的父系層級來篩選產品。

可能的值： 所有 (未套用任何篩選)、系列名稱

### <a name="group"></a>群組
群組值會篩選其上層層級 (系列) 特定群組中的產品。

可能的值： 所有 (未套用任何篩選)、群組名稱

## <a name="table-columns"></a>表格欄
產品資料表格包含定義產品、版本、發行及對應支援日期的欄。

> [!NOTE]
> 每個產品、版本及發行組合都會有一列。

### <a name="product"></a>產品
產品名稱。

### <a name="edition"></a>版本
當產品包含版本時，就會填入版本欄。 沒有產品版本時，此欄位會是空白的。

### <a name="release"></a>發行
產品中包含多個發行版本時，會填入發行版本欄。
當產品只有一個版本時，此欄位將會是空白的。

### <a name="support-policy"></a>支援原則
此欄位定義產品遵循的支援原則。

可能的值： [固定](/lifecycle/policies/fixed)、 [新式](/lifecycle/policies/modern)、元件

### <a name="start-date"></a>開始日期
產品的支援開始日期。

### <a name="mainstream-date"></a>主要日期
當支援原則為 **固定** 或 **元件** 時，此為產品的主要結束日期。
  
當支援原則為 **新式** 時，這會是空白的。

### <a name="extended-end-date"></a>延伸終止日期
當支援原則為 **固定** 或 **元件** 時，即為產品的延伸結束日期的日期。

當支援原則為 **新式** 時，這會是空白的。

### <a name="retirement-date"></a>淘汰日期
當支援原則為 **固定** 或 **元件** 時，這會是空白的。

當支援原則為 **新式** 時，這會是產品的淘汰日期。

### <a name="release-start-date"></a>發行版本開始日期
發行版本的支援開始日期。 當產品只有一個版本時，此欄位將會是空白的。
 
### <a name="release-end-date"></a>ESU 結束日期
發行版本的支援結束日期。
當產品只有一個版本時，此欄位將會是空白的。

### <a name="docs-url"></a>文件 Url
延伸文件的 Url。
