---
title: Zwiększanie ochrony przed zagrożeniami dla Microsoft 365 Business Premium
f1.keywords:
- NOCSH
ms.author: sharik
author: skjerland
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.collection:
- M365-subscription-management
- M365-identity-device-management
ms.custom:
- MiniMaven
- MSB365
- OKR_SMB_M365
- seo-marvel-mar
- AdminSurgePortfolio
search.appverid:
- BCS160
- MET150
description: Skonfiguruj funkcje zgodności, aby zapobiec utracie danych i zapewnić bezpieczeństwo poufnych informacji Twoich i Twoich klientów.
ms.openlocfilehash: 945f8a283b90b89da2fbe67a073e0807b80d198f
ms.sourcegitcommit: ff20f5b4e3268c7c98a84fb1cbe7db7151596b6d
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 05/06/2021
ms.locfileid: "52245089"
---
# <a name="set-up-compliance-features"></a>Konfigurowanie funkcji zgodności

Twój Microsoft 365 Business Premium oferuje funkcje ochrony danych i urządzeń oraz pomaga zabezpieczyć poufne informacje Twoich i klientów.

## <a name="set-up-dlp-features"></a>Konfigurowanie funkcji DLP

Zobacz [Tworzenie zasad DLP](../compliance/create-a-dlp-policy-from-a-template.md) na podstawie szablonu, aby uzyskać przykład sposobu skonfigurowania zasad w celu ochrony przed utratą danych osobowych. 
  
Zasady DLP są dostępne z wieloma gotowymi do użycia szablonami zasad dla wielu różnych lokalizacji regionalnych. Na przykład Australia Financial Data, Canada Personal Information Act, Us.S. Financial Data i tak dalej. Zobacz [Co zawierają szablony zasad DLP,](../compliance/what-the-dlp-policy-templates-include.md) aby uzyskać pełną listę. Wszystkie te szablony można włączyć podobnie jak w przykładzie szablonu piI. 
  
## <a name="set-up-email-retention-with-exchange-online-archiving"></a>Konfigurowanie przechowywania poczty e-mail przy użyciu Exchange Online — archiwum

 **Exchange Online — archiwum** funkcji licencji pomagają w zachowaniu zgodności z normami i przepisami prawa, zachowując zawartość wiadomości e-mail na rzecz zbierania elektronicznych materiałów dowodowych. Pomaga to również zmniejszyć ryzyko w przypadku wystąpienia do sądu i umożliwia odzyskanie danych po naruszeniu zabezpieczeń lub potrzebie odzyskania usuniętych elementów. Aby zachować całą zawartość użytkownika, możesz użyć funkcji postępowania sądowego lub zasad przechowywania, aby dostosować to, co chcesz zachować.
  
**Zawieszenie w postępowaniem sądowym:** Całą zawartość skrzynki pocztowej, w tym elementy usunięte, można zachować, umieszczając całą skrzynkę pocztową użytkownika na postępowaniem sądowym. 
    
Aby umieścić skrzynkę pocztową w związku z postępowaniem sądowym, w centrum administracyjnym:
    
1. W lewym okienku narracji przejdź do **strony** \> **Aktywni użytkownicy użytkownicy.**
    
2. Wybierz użytkownika, którego skrzynkę pocztową chcesz umieścić w postępowaniem sądowym. W okienku użytkownika rozwiń **pozycję Ustawienia poczty**, a następnie obok **przycisku Więcej** ustawień wybierz pozycję Edytuj Exchange **właściwości**.
    
3. Na stronie skrzynki pocztowej dla użytkownika wybierz ** funkcje skrzynki pocztowej ** w lewym obszarze wyszukiwania, a następnie wybierz **link** Włącz w obszarze Zawieszenie w związku z **postępowaniem sądowym.**
    
4. W **oknie dialogowym Zawieszenie** w związku z postępowaniem sądowym w polu Czas trwania trwania w związku z postępowaniem sądowym możesz określić czas trwania trwania w związku z postępowaniem **sądowym.** Pozostaw to pole puste, jeśli chcesz umieścić nieskończoną przestrzeń. Możesz również dodawać notatki i kierować właściciela skrzynki pocztowej do witryny internetowej, w przypadku których może być konieczne dodatkowe wyjaśnienie dotyczące postępowania sądowego. \>**Zapisz**.
    
**Przechowywanie:** Można włączyć niestandardowe zasady przechowywania, na przykład w celu zachowania określonego czasu lub trwałego usuwania zawartości na koniec okresu przechowywania. Aby dowiedzieć się więcej, zobacz [Omówienie zasad przechowywania.](../compliance/retention.md)

## <a name="set-up-sensitivity-labels"></a>Konfigurowanie etykiet wrażliwości

Etykiety wrażliwości są dostępne w ramach usługi Azure Information Protection (AIP, Azure Information Protection) (plan 1) i pomagają klasyfikować oraz opcjonalnie chronić dokumenty i wiadomości e-mail, stosując etykiety. Etykiety mogą być stosowane automatycznie przez administratorów definiujących reguły i warunki, ręcznie przez użytkowników lub za pomocą kombinacji, w której użytkownicy mają zalecenia.

Aby skonfigurować etykiety wrażliwości, wyświetl [klip wideo o tworzeniu etykiet wrażliwości i zarządzaniu nimi.](../business-video/create-sensitivity-labels.md)



### <a name="install-the-azure-information-protection-client-manually"></a>Ręczne instalowanie klienta usługi Azure Information Protection

Aby ręcznie zainstalować klienta AIP:

1. Pobierz **AzinfoProtection_UL.exe** z [Centrum pobierania Microsoft](https://www.microsoft.com/download/details.aspx?id=53018).
 
2. Możesz sprawdzić, czy instalacja się działała, wyświetlając  dokument programu Word i upewnijąc się, że opcja Charakter jest dostępna na **karcie Narzędzia** główne.
<br/>![Lista rozwijana na karcie Ochrona w dokumencie programu Word.](../media/word-sensitivity.png)

Aby uzyskać więcej informacji, [zobacz Instalowanie klienta.](/azure/information-protection/infoprotect-tutorial-step3)