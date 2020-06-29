---
title: Защита от DMA Surface
description: В этой статье описывается Защита канала DMA на совместимых устройствах Surface
ms.prod: w10
ms.mktglfcycl: manage
ms.localizationpriority: medium
ms.sitesec: library
author: coveminer
ms.author: greglin
ms.topic: article
ms.date: 6/10/2020
ms.reviewer: carlol
manager: laurawi
audience: itpro
ms.openlocfilehash: 00994263cd61086ab86996920543a717a63d5078
ms.sourcegitcommit: 109d1d7608ac4667564fa5369e8722e569b8ea36
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/27/2020
ms.locfileid: "10835107"
---
# <span data-ttu-id="7a72f-103">Защита DMA на Surface Devices</span><span class="sxs-lookup"><span data-stu-id="7a72f-103">DMA Protection on Surface devices</span></span>

<span data-ttu-id="7a72f-104">Защита от прямого доступа к памяти (DMA) разработана для устранения потенциальных уязвимостей системы безопасности, связанных с использованием съемных твердотельных накопителей или внешних запоминающих устройств.</span><span class="sxs-lookup"><span data-stu-id="7a72f-104">Direct Memory Access (DMA) protection is designed to mitigate potential security vulnerabilities associated with using removable SSDs or external storage devices.</span></span> <span data-ttu-id="7a72f-105">Новые устройства Surface включены по умолчанию с защитой DMA.</span><span class="sxs-lookup"><span data-stu-id="7a72f-105">Newer Surface devices come with DMA Protection enabled by default.</span></span> <span data-ttu-id="7a72f-106">К ним относятся 7 Surface Pro, Ноутбуки 3 и Surface Pro X.  Чтобы проверить наличие функции защиты DMA на вашем устройстве, откройте окно "сведения о системе" (**Start**  >  **msinfo32.exe**), как показано на рисунке ниже.</span><span class="sxs-lookup"><span data-stu-id="7a72f-106">These include Surface Pro 7, Surface Laptop 3, and Surface Pro X.  To check the presence of DMA protection feature on your device, open System Information (**Start** > **msinfo32.exe**), as shown in the figure below.</span></span>

![Сведения о системе, на которой включена защита DMA](images/systeminfodma.png)

<span data-ttu-id="7a72f-108">Если съемный SSD Surface подделкиется, устройство будет shutoff Power.</span><span class="sxs-lookup"><span data-stu-id="7a72f-108">If a Surface removable SSD is tampered with, the device will shutoff power.</span></span> <span data-ttu-id="7a72f-109">Результирующая перезагрузка вызывает очистку памяти, чтобы удалить все остаточные данные.</span><span class="sxs-lookup"><span data-stu-id="7a72f-109">The resulting reboot causes UEFI to wipe memory, to erase any residual data.</span></span>
