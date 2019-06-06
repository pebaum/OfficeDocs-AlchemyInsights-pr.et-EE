---
title: SharePoint Online'i kasutamise alustamine
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: a44b2c7b26895e09c24df772f1ada9a2e3483747
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: et-EE
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735979"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="c51a2-102">SharePointi töövood</span><span class="sxs-lookup"><span data-stu-id="c51a2-102">Workflows in SharePoint</span></span>

<span data-ttu-id="c51a2-103">Kui SharePointi töövood ei saada kirju, ettevõte on olnud Exchange Online'i saatja piire.</span><span class="sxs-lookup"><span data-stu-id="c51a2-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.</span></span>

<span data-ttu-id="c51a2-104">"Töövoog on peatatud" tõrketeade võib ilmneda juhul, kui teil on üks järgmistest:</span><span class="sxs-lookup"><span data-stu-id="c51a2-104">'Workflow is Suspended' error message may occur if you have one of the following items:</span></span>

- <span data-ttu-id="c51a2-105">Olete töövoo SharePoint Online, mis kasutab SharePoint 2010 või SharePointi 2013 töövoo platvormi tüüp.</span><span class="sxs-lookup"><span data-stu-id="c51a2-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>

- <span data-ttu-id="c51a2-106">Töövoog on konfigureeritud kohandatud e-kirja saatmiseks üle 200 kasutajatele korraga, üle 10 000 adressaati päevas või üle 30 sõnumites minutis.</span><span class="sxs-lookup"><span data-stu-id="c51a2-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>

<span data-ttu-id="c51a2-107">Kui käivitate töövoo, saadetakse e-kiri ja märkate veateate, sisemine olek kuvatakse Suspended või ei saa adressaadile saata.</span><span class="sxs-lookup"><span data-stu-id="c51a2-107">When you run the workflow, the email message isn't sent, and you notice the error message, Internal Status is set to Suspended or Unable to send to a recipient is displayed.</span></span>

<span data-ttu-id="c51a2-108">Lisateabe saamiseks vaadake [artikli](https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span><span class="sxs-lookup"><span data-stu-id="c51a2-108">For more information, please refer to the following [article](https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>
