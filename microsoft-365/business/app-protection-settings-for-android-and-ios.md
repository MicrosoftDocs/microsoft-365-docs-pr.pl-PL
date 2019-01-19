---
title: Konfigurowanie ustawień ochrony aplikacji dla urządzeń z systemem Android lub iOS
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
ms.assetid: 6f2b80b4-81c3-4714-a7bc-ae69313e8a33
description: Dowiedz się, jak tworzyć, edytować, lub usuwanie aplikacji zasad zarządzania i ochrony plików praca na urządzeniach Android lub iOS.
ms.openlocfilehash: ed03227496120369b94bf2396974eebfd7798678
ms.sourcegitcommit: e491c4713115610cbe13d2fbd0d65e1a41c34d62
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 01/16/2019
ms.locfileid: "26983667"
---
# <a name="set-app-protection-settings-for-android-or-ios-devices"></a>Konfigurowanie ustawień ochrony aplikacji dla urządzeń z systemem Android lub iOS

## <a name="create-an-app-management-policy"></a>Tworzenie zasad zarządzania aplikacjami

1. Zaloguj się do usługi [Microsoft 365 Business](https://portal.office.com) za pomocą poświadczeń administratora globalnego. 
    
2. W centrum administracyjnym na karcie **Zasady dotyczące urządzenia** wybierz pozycję **Dodaj zasady**.
    
    ![Device policies card in the admin center.](media/27c12b61-d112-4348-b557-4f3e46204797.png)
  
3. W okienku **Dodawanie zasad** wprowadź unikatową nazwę dla zasad. 
    
4. W sekcji **Typ zasad** wybierz pozycję **Zarządzanie aplikacjami dla systemu Android** lub **Zarządzanie aplikacjami dla systemu iOS** w zależności od tego, jaki zestaw zasad chcesz utworzyć. 
    
5. Rozwiń węzeł **Chroń pliki robocze, gdy urządzenia są zagubione lub skradzione** i **zarządzać dostęp użytkowników do plików pakietu Office na urządzeniach przenośnych** \> skonfigurować ustawienia jak. **Zarządzaj dostępem użytkowników do plików pakietu Office na urządzeniach przenośnych** jest domyślnie **wyłączone** , ale zaleca się **je włączyć**, a następnie zaakceptuj wartości domyślne. Aby uzyskać więcej informacji, zobacz temat [dostępne ustawienia](app-protection-settings-for-android-and-ios.md#bkmk_availablesettings) . 
    
    Aby zresetować ustawienia do wartości domyślnych, w dowolnej chwili możesz użyć linku **Resetuj ustawienia domyślne**. 
    
    ![Screenshot of Create a policy with Application management for Android selected](media/eabbe06d-ac0a-4f3a-8630-68c808b1e662.png)
  
6. Następnie zdecyduj **kto otrzyma te ustawienia?** Jeśli nie chcesz używać domyślnej grupy zabezpieczeń **Wszyscy użytkownicy**, wybierz **Zmień**, a następnie wybierz grupę zabezpieczeń, która otrzyma te ustawienia \> **Wybierz**.
    
7. Na koniec wybierz przycisk **Gotowe**, aby zapisać zasady i zastosować je na urządzeniach. 
    
## <a name="edit-an-app-management-policy"></a>Edytowanie zasad zarządzania aplikacjami

1. Na karcie **Zasady** wybierz polecenie **Edytuj zasady**.
    
2. W okienku **Edytowanie zasad** wybierz zasadę, którą chcesz zmienić. 
    
3. Wybierz opcję **Edytuj** obok poszczególnych ustawień, aby zmienić wartości zasad. Wszystkie zmiany są zapisywane automatycznie. 
    
4. Gdy skończysz wprowadzać zmiany, zamknij okienko **Edytowanie zasad**. 
    
## <a name="delete-an-app-management-policy"></a>Usuwanie zasad zarządzania aplikacjami

1. Na karcie **Zasady** wybierz pozycję **Usuń zasady**.
    
2. W okienku **Usuwanie zasady** wybierz zasady do usunięcia \> **Zaznacz**, a następnie **Potwierdź** usunięcie wybranej zasady lub zasad. 
    
## <a name="available-settings"></a>Dostępne ustawienia

W poniższych tabelach szczegółowo opisano dostępne ustawienia umożliwiające ochronę służbowych plików na urządzeniach i kontrolowanie dostępu użytkowników do plików pakietu Office na urządzeniach przenośnych.
  
 Aby uzyskać więcej informacji, zobacz [Jaka jest zależność między funkcjami ochrony w usłudze Microsoft 365 Business i ustawieniami usługi Intune](map-protection-features-to-intune-settings.md). 
  
### <a name="settings-that-protect-work-files"></a>Ustawienia chroniące pliki służbowe

W przypadku zagubienia lub kradzieży urządzenia użytkownika dostępne są następujące ustawienia chroniące pliki służbowe:
  
|||
|:-----|:-----|
|Ustawienie  <br/> |Opis  <br/> |
|Usuń pliki służbowe z nieaktywnego urządzenia po określonej liczbie dni  <br/> |Jeśli urządzenie nie będzie używane przez określoną w tym miejscu liczbę dni, wszelkie pliki służbowe znajdujące się na urządzeniu zostaną automatycznie usunięte.  <br/> |
|Wymuszaj na użytkownikach zapisywanie wszystkich plików służbowych w usłudze OneDrive dla Firm  <br/> |Gdy to ustawienie jest **włączone**, pliki służbowe można zapisywać tylko w usłudze OneDrive dla Firm.  <br/> |
|Szyfruj pliki służbowe  <br/> |Pozostaw to ustawienie **włączone**, aby chronić pliki służbowe przy użyciu szyfrowania. Nawet jeśli urządzenie zostanie zgubione lub ukradzione, nikt nie będzie mógł odczytać danych firmowych.  <br/> |
   
### <a name="settings-that-control-how-users-access-office-files-on-mobile-devices"></a>Ustawienia umożliwiające kontrolę dostępu użytkowników do plików pakietu Office na urządzeniach przenośnych

Na potrzeby zarządzania dostępem użytkowników do plików służbowych w pakiecie Office dostępne są następujące ustawienia:
  
|||
|:-----|:-----|
|Ustawienie  <br/> |Opis  <br/> |
|Wymagaj numeru PIN lub odcisku palca w celu uzyskania dostępu do aplikacji pakietu Office  <br/> |Gdy to ustawienie jest **włączone**, użytkownicy muszą się dodatkowo uwierzytelnić, korzystając z innej metody (oprócz podania nazwy użytkownika i hasła), aby uzyskać dostęp do aplikacji pakietu Office na urządzeniach przenośnych.  <br/> |
|Resetuj numer PIN w przypadku wielokrotnego niepowodzenia logowania  <br/> |Aby uniemożliwić nieautoryzowanym użytkownikom odgadywanie kodu PIN, ten kod jest resetowany po określonej liczbie nieudanych prób jego podania.  <br/> |
|Wymagaj ponownego logowania użytkowników po czasie bezczynności aplikacji pakietu Office  <br/> |To ustawienie określa, jak długo użytkownik może nie korzystać z aplikacji, zanim będzie wymagane ponowne zalogowanie się.  <br/> |
|Odmów dostępu do plików służbowych na urządzeniach z usuniętymi natywnymi ograniczeniami producenta  <br/> |Sprytni użytkownicy mogą mieć urządzenie z usuniętymi natywnymi ograniczeniami producenta. Umożliwia to użytkownikowi modyfikowanie systemu operacyjnego, co może narazić urządzenie na ataki złośliwym oprogramowaniem. Te urządzenia zostaną zablokowane, jeśli to ustawienie będzie **Włączone**.  <br/> |
|Zezwalaj użytkownikom na kopiowanie zawartości z aplikacji pakietu Office do aplikacji osobistych  <br/> |Zezwalamy na to domyślnie, ale jeżeli to ustawienie jest **włączone**, użytkownik może skopiować informacje w pliku roboczego do pliku osobistego. Jeśli to ustawienie jest **wyłączone**, użytkownik nie będzie mógł skopiować informacji z konta służbowego do osobistych aplikacji lub konta osobistego.<br/> |
   

  

