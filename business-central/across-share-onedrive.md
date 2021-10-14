---
title: Verwendung von OneDrive für Business mit Business Central
description: Sie können OneDrive for Business verwenden, um Dateien zu speichern, zu verwalten und freizugeben, z.B. Berichte oder Dateianhänge.
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.workload: na
ms.search.keywords: ''
ms.date: 06/11/2021
ms.author: bholtorf
ms.openlocfilehash: 92896af6888ef5c39288d511e61d343d3e384a83
ms.sourcegitcommit: 6ad0a834fc225cc27dfdbee4a83cf06bbbcbc1c9
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/01/2021
ms.locfileid: "7589413"
---
# <a name="opening-business-central-files-in-onedrive"></a>Öffnen von Business Central Dateien in OneDrive
[!INCLUDE[prod_short](includes/prod_short.md)] macht es Ihnen leicht, Dateien zu speichern, zu verwalten und mit anderen Personen über OneDrive for Business zu teilen. Auf den meisten Seiten, auf denen Dateien verfügbar sind, wie z.B. dem Berichtseingang oder Dateien, die an Datensätze angehängt sind, finden Sie eine **Öffnen in OneDrive** Aktion.

:::image type="content" source="media/Open in OneDrive.PNG" alt-text="Die Aktion Öffnen in OneDrive":::

 
:::image type="content" source="media/OneDrive attachment.PNG" alt-text="Freigeben von Dateianhängen in OneDrive":::

## <a name="working-with-different-types-of-files"></a>Arbeiten mit verschiedenen Dateitypen
Wenn Sie **Öffnen in OneDrive** wählen, identifiziert [!INCLUDE[prod_short](includes/prod_short.md)] Excel-, Word- und PowerPoint-Dateien und öffnet sie in den jeweiligen Online-Anwendungen, d.h. Excel online, Word online und PowerPoint online. Sie können Anmerkungen machen, bearbeiten und mit anderen zusammenarbeiten, ohne den Browser zu verlassen. 

Für andere gängige Dateitypen wie PDFs, Textdateien und Bilder bietet OneDrive Dateibetrachter, die Funktionen zum Drucken, Teilen und mehr bieten. Wenn eine Datei nicht in OneDrive angezeigt werden kann, werden Sie möglicherweise aufgefordert, sie herunterzuladen. 

## <a name="managing-multiple-copies-of-a-file"></a>Mehrere Kopien einer Datei verwalten
Wenn Sie **Öffnen in OneDrive** wählen, wird die Datei von [!INCLUDE[prod_short](includes/prod_short.md)] in Ihren Ordner in OneDrive kopiert. Wenn Sie die Datei in OneDrive bearbeiten, werden die Kopien der Datei unterschiedlich sein. Um [!INCLUDE[prod_short](includes/prod_short.md)] mit der neuesten Datei zu aktualisieren, entfernen Sie die vorhandene Datei aus [!INCLUDE[prod_short](includes/prod_short.md)] und laden dann die neueste Kopie hoch.

Wenn Sie die Aktion Öffnen in OneDrive verwenden und eine Datei mit diesem Namen bereits in OneDrive vorhanden ist, bietet Ihnen [!INCLUDE[prod_short](includes/prod_short.md)] außerdem die Möglichkeit, die Datei zu ersetzen oder beide Dateien zu behalten. Wenn Sie sich dafür entscheiden, beide Dateien beizubehalten, wird die neue Datei nach OneDrive kopiert und ihr Dateiname erhält ein Suffix, wie z.B. „Artikel (2).xlsx“, und die Originaldatei wird nicht verändert. 

Wenn Sie sich dafür entscheiden, die Datei zu ersetzen, wird die neue Datei dem Versionsverlauf für diese Datei hinzugefügt. Die Originaldatei geht dabei nicht verloren und Sie können frühere Versionen der Datei anzeigen oder wiederherstellen. 

## <a name="accessing-your-onedrive"></a>Zugriff auf Ihre OneDrive
Sie können auf Ihre OneDrive von der Seite **Meine Einstellungen** aus zugreifen, indem Sie den Link im Feld **Cloud-Speicher** wählen.

:::image type="content" source="media/my-settings-cloud-storage.PNG" alt-text="Das Feld Cloud-Speicher in Meine Einstellungen":::

<!--## Extending the Connection to OneDrive
You can create an extension and connect it to... For more information, see...-->

## <a name="see-also"></a>Weitere Informationen
[Business Central und OneDrive Integration](across-onedrive-overview.md)  
[Verwaltung der OneDrive Integration mit Business Central](admin-onedrive-integration.md)  
[OneDrive FAQ](admin-onedrive-faq.md)