---
title: 'Gewusst wie: Zusammenfassende Meldung'
description: "Mit der zusammenfassenden Meldung können Sie Informationen zu Verkaufstransaktionen mit anderen Ländern oder Regionen innerhalb der Europäischen Union (EU) an das System der Zoll- und Steuerbehördenlisten übermitteln."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 03/02/2018
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 56cd8aa034935ca37bd91bdbec76b4f7b7a4c1c8
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="declare-vat-vies-tax"></a>MwSt-VIES-Steuer angeben
[!INCLUDE[d365fin](../../includes/d365fin_md.md)] enthält die zusammenfassende Meldung, mit der Sie Informationen zu Verkaufstransaktionen mit anderen Ländern oder Regionen innerhalb der Europäischen Union (EU) an das System der Zoll- und Steuerbehördenlisten übermitteln können. Im Bericht werden Informationen in dem Format angezeigt, das auch in der Erklärungsliste der Zoll- und Steuerbehörden verwendet wird.  

Abhängig vom Volumen der verkauften Waren oder Dienstleistungen an andere EU-Länder/Regionen, müssen Sie monatliche, zweimonatliche oder vierteljährliche Meldungen senden. Hat das Unternehmen Verkäufe von mehr als 100.000 Euro pro Quartal, müssen Sie eine monatliche Meldung senden. Hat das Unternehmen Verkäufe von weniger als 100.000 Euro pro Quartal, müssen Sie eine monatliche Meldung senden. Weitere Informationen finden Sie unter  [BZSt-Website](http://go.microsoft.com/fwlink/?LinkId=204368).  

Der Bericht basiert auf Daten in der Tabelle "MwSt.-Posten".  

## <a name="to-declare-vat-vies-tax"></a>So erstellen Sie eine zusammenfassende Meldung  

1.  Wählen Sie ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol nach Seite oder Bericht suchen") und geben **Zusammenf. Meldung - Formular** ein und wählen dann den zugehörigen Link aus.  
2.  Füllen Sie im Fenster **Zusammenf. Meldung MwSt-Vies-Formular** im Inforegister **Optionen** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  

    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Meldezeitraum**|Geben Sie den Zeitraum an, den der Bericht umfasst. Dies kann ein Monat, eine zweimonatige Periode, ein Quartal oder das Kalenderjahr sein.|  
    |**Datum der Unterschrift**|Dient zum Eingeben des Datums, an dem die MwSt-VIES-Erklärung gesendet wird.|  
    |**Berichtigte Anmeldung**|Ein Häkchen im Kontrollkästchen bedeutet, dass es sich um eine korrigierte Fassung einer bereits abgegebenen zusammenfassenden MwSt-VIES-Erklärung handelt.|  
    |**Beträge in Berichtswährung ausgeben**|Gibt an, ob die ausgewerteten Beträge in der zusätzlichen Berichtswährung angezeigt werden. Weitere Informationen finden Sie unter zusätzliche Berichtswährung.|  
    |**Auf monatliche Meldung umstellen**|Wenn es ausgewählt wird, hat Ihr Unternehmen Verkäufe von mehr als 100.000 Euro pro Quartal und Sie müssen von einem Quartalsbericht zu einem monatlichen Bericht migrieren. **Wichtig:** Wählen sie nur dieses Feld aus, wenn Sie zum ersten Mal einen monatlichen Bericht senden.|  
    |**Monatliche Meldung widerrufen**|Wird dieses Kontrollkästchen aktiviert, wollen Sie vom monatlichen Bericht zu einem anderen Meldezeitraum wechseln.<br /><br /> Wenn Sie beispielsweise zuvor monatliche Erklärungen eingereicht haben, aber die EU-Umsätze weniger als 100.000 Euro pro Quartal betragen, wählen Sie das Feld und wählen Sie anschließend eines der Quartale im **Meldezeitraum** aus.|  

3.  Wählen Sie im Inforegister **MwSt.-Abrechnungszeile** die entsprechenden Filter aus.  

    > [!NOTE]  
    >  Um diesen Bericht ausführen, müssen Sie das **Buchungsdatum** als Filter auswählen und den Wert des Buchungsdatums eingegeben.  

## <a name="see-also"></a>Siehe auch  
[MwSt.-Abrechnung](vat-reporting.md)
