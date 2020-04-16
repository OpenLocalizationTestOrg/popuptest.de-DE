---
title: <specifiedPickupDirectory>Element (Netzwerkeinstellungen)
ms.date: 03/30/2017
f1_keywords:
- http://schemas.microsoft.com/.NetConfiguration/v2.0#specifiedPickupDirectory
- http://schemas.microsoft.com/.NetConfiguration/v2.0#configuration/system.net/mailSettings/smtp/specifiedPickupDirectory
helpviewer_keywords:
- specifiedPickupDirectory element
- <specifiedPickupDirectory> element
ms.assetid: 0121f49d-bff2-4bc6-af06-f1628dcd61f1
ms.openlocfilehash: 0d9c68f887edd33d91c894a3caa47e37132dcd5c
ms.sourcegitcommit: 7335c82f5336142f6bb802210d8c7e2736a4c022
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/16/2020
ms.locfileid: "6613564"
---
# <a name="specifiedpickupdirectory-element-network-settings"></a><span data-ttu-id="0f588-102">\<SpecifiedPickupDirectory>-Element (Netzwerkeinstellungen)</span><span class="sxs-lookup"><span data-stu-id="0f588-102">\<specifiedPickupDirectory> Element (Network Settings)</span></span>
<span data-ttu-id="0f588-103">Konfiguriert das lokale Verzeichnis für einen SMTP-Server (Simple Mail Transport Protocol).</span><span class="sxs-lookup"><span data-stu-id="0f588-103">Configures the local directory for a Simple Mail Transport Protocol (SMTP) server.</span></span>  
  
<span data-ttu-id="0f588-104">[**\<Konfigurations>**](../configuration-element.md)</span><span class="sxs-lookup"><span data-stu-id="0f588-104">[**\<configuration>**](../configuration-element.md)</span></span>\
<span data-ttu-id="0f588-105">&nbsp;&nbsp;[**\<System.net>**](system-net-element-network-settings.md)</span><span class="sxs-lookup"><span data-stu-id="0f588-105">&nbsp;&nbsp;[**\<system.net>**](system-net-element-network-settings.md)</span></span>\
<span data-ttu-id="0f588-106">&nbsp;&nbsp;&nbsp;&nbsp;[**\<mailSettings>**](mailsettings-element-network-settings.md)</span><span class="sxs-lookup"><span data-stu-id="0f588-106">&nbsp;&nbsp;&nbsp;&nbsp;[**\<mailSettings>**](mailsettings-element-network-settings.md)</span></span>\
<span data-ttu-id="0f588-107">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**\<SMTP->**](smtp-element-network-settings.md)</span><span class="sxs-lookup"><span data-stu-id="0f588-107">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**\<smtp>**](smtp-element-network-settings.md)</span></span>\
<span data-ttu-id="0f588-108">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**\<SpecifiedPickupDirectory>**</span><span class="sxs-lookup"><span data-stu-id="0f588-108">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**\<specifiedPickupDirectory>**</span></span>  
  
## <a name="syntax"></a><span data-ttu-id="0f588-109">Syntax</span><span class="sxs-lookup"><span data-stu-id="0f588-109">Syntax</span></span>  
  
```xml  
<specifiedPickupDirectory  
  pickupDirectoryLocation="directory"
/>  
```  
  
## <a name="attributes-and-elements"></a><span data-ttu-id="0f588-110">Attribute und Elemente</span><span class="sxs-lookup"><span data-stu-id="0f588-110">Attributes and Elements</span></span>  
 <span data-ttu-id="0f588-111">In den folgenden Abschnitten werden Attribute, untergeordnete Elemente und übergeordnete Elemente beschrieben.</span><span class="sxs-lookup"><span data-stu-id="0f588-111">The following sections describe attributes, child elements, and parent elements.</span></span>  
  
### <a name="attributes"></a><span data-ttu-id="0f588-112">Attribute</span><span class="sxs-lookup"><span data-stu-id="0f588-112">Attributes</span></span>  
  
|<span data-ttu-id="0f588-113">Attribut</span><span class="sxs-lookup"><span data-stu-id="0f588-113">Attribute</span></span>|<span data-ttu-id="0f588-114">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="0f588-114">Description</span></span>|  
|---------------|-----------------|  
|`pickupDirectoryLocation`|<span data-ttu-id="0f588-115">Das Verzeichnis, in dem Anwendungen e-Mails zur späteren Verarbeitung durch den SMTP-Server speichern.</span><span class="sxs-lookup"><span data-stu-id="0f588-115">The directory where applications save email for later processing by the SMTP server.</span></span>|  
  
### <a name="child-elements"></a><span data-ttu-id="0f588-116">Untergeordnete Elemente</span><span class="sxs-lookup"><span data-stu-id="0f588-116">Child Elements</span></span>  
 <span data-ttu-id="0f588-117">Keine.</span><span class="sxs-lookup"><span data-stu-id="0f588-117">None.</span></span>  
  
### <a name="parent-elements"></a><span data-ttu-id="0f588-118">Übergeordnete Elemente</span><span class="sxs-lookup"><span data-stu-id="0f588-118">Parent Elements</span></span>  
  
|<span data-ttu-id="0f588-119">Element</span><span class="sxs-lookup"><span data-stu-id="0f588-119">Element</span></span>|<span data-ttu-id="0f588-120">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="0f588-120">Description</span></span>|  
|-------------|-----------------|  
|[<span data-ttu-id="0f588-121">\<SMTP->-Element (Netzwerkeinstellungen)</span><span class="sxs-lookup"><span data-stu-id="0f588-121">\<smtp> Element (Network Settings)</span></span>](smtp-element-network-settings.md)|<span data-ttu-id="0f588-122">Konfiguriert die SMTP-e-Mail-Sendeoptionen (Simple Mail Transport Protocol).</span><span class="sxs-lookup"><span data-stu-id="0f588-122">Configures Simple Mail Transport Protocol (SMTP) mail sending options.</span></span>|  
  
## <a name="remarks"></a><span data-ttu-id="0f588-123">Hinweise</span><span class="sxs-lookup"><span data-stu-id="0f588-123">Remarks</span></span>  
 <span data-ttu-id="0f588-124">Das `specifiedPickupDirectory` Attribut legt das Verzeichnis fest, in dem Anwendungen e-Mail-Nachrichten speichern, die vom SMTP-Server verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="0f588-124">The `specifiedPickupDirectory` attribute sets the directory where applications save mail messages to be processed by the SMTP server.</span></span>  
  
## <a name="example"></a><span data-ttu-id="0f588-125">Beispiel</span><span class="sxs-lookup"><span data-stu-id="0f588-125">Example</span></span>  
 <span data-ttu-id="0f588-126">Im folgenden Beispiel wird c:\maildrop als e-Mail-Pickup-Verzeichnis angegeben.</span><span class="sxs-lookup"><span data-stu-id="0f588-126">The following example specifies c:\maildrop as the mail pickup directory.</span></span>  
  
```xml  
<configuration>  
  <system.net>  
    <mailSettings>  
      <smtp deliveryMethod="SpecifiedPickupDirectory">  
        <specifiedPickupDirectory  
          pickupDirectoryLocation="c:\maildrop"  
        />  
      </smtp>  
    </mailSettings>  
  </system.net>  
</configuration>  
```  
  
## <a name="see-also"></a><span data-ttu-id="0f588-127">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="0f588-127">See also</span></span>

- <xref:System.Net.Mail.SmtpClient?displayProperty=nameWithType>
- <xref:System.Net.Configuration.SmtpSection?displayProperty=nameWithType>
- <xref:System.Net.Configuration.SmtpSpecifiedPickupDirectoryElement?displayProperty=nameWithType>
- [<span data-ttu-id="0f588-128">Netzwerk Einstellungs Schema</span><span class="sxs-lookup"><span data-stu-id="0f588-128">Network Settings Schema</span></span>](index.md)