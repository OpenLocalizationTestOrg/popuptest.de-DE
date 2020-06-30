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
ms.openlocfilehash: 25b06619a91e43d54b92c1e2cc50b433ccf864bc
ms.sourcegitcommit: e25a89331cdb027dcfc845e774571df86e62dcb2
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2020
ms.locfileid: "6614895"
---
# <a name="update-test-on-june-23"></a><span data-ttu-id="f7c3c-102">Update Test am 23. Juni</span><span class="sxs-lookup"><span data-stu-id="f7c3c-102">Update test on June 23</span></span>
  
# <a name="specifiedpickupdirectory-element-network-settings"></a><span data-ttu-id="f7c3c-103">\<specifiedPickupDirectory>Element (Netzwerkeinstellungen)</span><span class="sxs-lookup"><span data-stu-id="f7c3c-103">\<specifiedPickupDirectory> Element (Network Settings)</span></span>
<span data-ttu-id="f7c3c-104">Konfiguriert das lokale Verzeichnis für einen SMTP-Server (Simple Mail Transport Protocol).</span><span class="sxs-lookup"><span data-stu-id="f7c3c-104">Configures the local directory for a Simple Mail Transport Protocol (SMTP) server.</span></span>  
  
[**\<configuration>**](../configuration-element.md)\
&nbsp;&nbsp;[**\<system.net>**](system-net-element-network-settings.md)\
&nbsp;&nbsp;&nbsp;&nbsp;[**\<mailSettings>**](mailsettings-element-network-settings.md)\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**\<smtp>**](smtp-element-network-settings.md)\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**\<specifiedPickupDirectory>**  
  
## <a name="syntax"></a><span data-ttu-id="f7c3c-105">Syntax</span><span class="sxs-lookup"><span data-stu-id="f7c3c-105">Syntax</span></span>  
  
```xml  
<specifiedPickupDirectory  
  pickupDirectoryLocation="directory"
/>  
```  
  
## <a name="attributes-and-elements"></a><span data-ttu-id="f7c3c-106">Attribute und Elemente</span><span class="sxs-lookup"><span data-stu-id="f7c3c-106">Attributes and Elements</span></span>  
 <span data-ttu-id="f7c3c-107">In den folgenden Abschnitten werden Attribute, untergeordnete Elemente und übergeordnete Elemente beschrieben.</span><span class="sxs-lookup"><span data-stu-id="f7c3c-107">The following sections describe attributes, child elements, and parent elements.</span></span>  
  
### <a name="attributes"></a><span data-ttu-id="f7c3c-108">Attribute</span><span class="sxs-lookup"><span data-stu-id="f7c3c-108">Attributes</span></span>  
  
|<span data-ttu-id="f7c3c-109">Attribut</span><span class="sxs-lookup"><span data-stu-id="f7c3c-109">Attribute</span></span>|<span data-ttu-id="f7c3c-110">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="f7c3c-110">Description</span></span>|  
|---------------|-----------------|  
|`pickupDirectoryLocation`|<span data-ttu-id="f7c3c-111">Das Verzeichnis, in dem Anwendungen e-Mails zur späteren Verarbeitung durch den SMTP-Server speichern.</span><span class="sxs-lookup"><span data-stu-id="f7c3c-111">The directory where applications save email for later processing by the SMTP server.</span></span>|  
  
### <a name="child-elements"></a><span data-ttu-id="f7c3c-112">Untergeordnete Elemente</span><span class="sxs-lookup"><span data-stu-id="f7c3c-112">Child Elements</span></span>  
 <span data-ttu-id="f7c3c-113">Keine.</span><span class="sxs-lookup"><span data-stu-id="f7c3c-113">None.</span></span>  
  
### <a name="parent-elements"></a><span data-ttu-id="f7c3c-114">Übergeordnete Elemente</span><span class="sxs-lookup"><span data-stu-id="f7c3c-114">Parent Elements</span></span>  
  
|<span data-ttu-id="f7c3c-115">Element</span><span class="sxs-lookup"><span data-stu-id="f7c3c-115">Element</span></span>|<span data-ttu-id="f7c3c-116">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="f7c3c-116">Description</span></span>|  
|-------------|-----------------|  
|[<span data-ttu-id="f7c3c-117">\<smtp>Element (Netzwerkeinstellungen)</span><span class="sxs-lookup"><span data-stu-id="f7c3c-117">\<smtp> Element (Network Settings)</span></span>](smtp-element-network-settings.md)|<span data-ttu-id="f7c3c-118">Konfiguriert die SMTP-e-Mail-Sendeoptionen (Simple Mail Transport Protocol).</span><span class="sxs-lookup"><span data-stu-id="f7c3c-118">Configures Simple Mail Transport Protocol (SMTP) mail sending options.</span></span>|  
  
## <a name="remarks"></a><span data-ttu-id="f7c3c-119">Hinweise</span><span class="sxs-lookup"><span data-stu-id="f7c3c-119">Remarks</span></span>  
 <span data-ttu-id="f7c3c-120">Das `specifiedPickupDirectory` Attribut legt das Verzeichnis fest, in dem Anwendungen e-Mail-Nachrichten speichern, die vom SMTP-Server verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="f7c3c-120">The `specifiedPickupDirectory` attribute sets the directory where applications save mail messages to be processed by the SMTP server.</span></span>  
  
## <a name="example"></a><span data-ttu-id="f7c3c-121">Beispiel</span><span class="sxs-lookup"><span data-stu-id="f7c3c-121">Example</span></span>  
 <span data-ttu-id="f7c3c-122">Im folgenden Beispiel wird c:\maildrop als e-Mail-Pickup-Verzeichnis angegeben.</span><span class="sxs-lookup"><span data-stu-id="f7c3c-122">The following example specifies c:\maildrop as the mail pickup directory.</span></span>  
  
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
  
## <a name="see-also"></a><span data-ttu-id="f7c3c-123">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="f7c3c-123">See also</span></span>

- <xref:System.Net.Mail.SmtpClient?displayProperty=nameWithType>
- <xref:System.Net.Configuration.SmtpSection?displayProperty=nameWithType>
- <xref:System.Net.Configuration.SmtpSpecifiedPickupDirectoryElement?displayProperty=nameWithType>
- [<span data-ttu-id="f7c3c-124">Netzwerk Einstellungs Schema</span><span class="sxs-lookup"><span data-stu-id="f7c3c-124">Network Settings Schema</span></span>](index.md)
