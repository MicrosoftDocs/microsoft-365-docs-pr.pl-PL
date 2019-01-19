---
title: Automatyczne instalowanie i odinstalowywanie pakietu Office na urządzeniach z systemem Windows 10
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
ms.assetid: cbc6bfe5-565a-4fb8-95f0-b06e7b74ac46
description: 'Zainstalować lub odinstalować pakiet Office na urządzeniach Windows 10 z Centrum administracyjnego Microsoft 365 Business. '
ms.openlocfilehash: 997c001ed1520f1ac989255632d36f9b7bedd16c
ms.sourcegitcommit: e491c4713115610cbe13d2fbd0d65e1a41c34d62
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 01/16/2019
ms.locfileid: "26983337"
---
# <a name="automatically-install-or-uninstall-office-on-windows-10-devices"></a>Automatyczne instalowanie i odinstalowywanie pakietu Office na urządzeniach z systemem Windows 10

Centrum administracyjne usług Microsoft 365 Business pozwala szybko i łatwo zainstalować pakiet Office na komputerach z systemem Windows 10.
  
Aby dowiedzieć się, jak to działa w przypadku wcześniej zainstalowanych aplikacji pakietu Office, przed rozpoczęciem przeczytaj artykuł na temat [przygotowywania się do instalacji aplikacji klienckich pakietu Office](prepare-for-office-client-deployment.md). 
  
## <a name="manage-office-deployments"></a>Zarządzanie wdrożeniami pakietu Office

1. Zaloguj się do [centrum administracyjnego](https://aka.ms/bcsportal), korzystając z poświadczeń administratora globalnego. 
    
2. Na karcie **Urządzenia** wybierz **Zarządzanie wdrażaniem pakietu Office**.    Jeśli nie widzisz karty **działania urządzenia** w strony **głównej** Centrum admin kliknij przycisk **Dodaj** (+), aby dodać je do domu użytkownika admin.
    
    ![Screenshot of the Devices card in the admin center](media/9982e784-dbf9-4a76-a159-bb3e2e5aa23f.png)
  
3. W okienku **Zarządzaj wdrożeniem pakietu Office**, które zostanie otwarte, wybierz pozycję **Dodaj grupę**, a następnie wybierz grupy, których chcesz użyć.
    
4. Po dodaniu grup wybierz z listy **Akcja wdrażania** pozycję **Zainstaluj pakiet Office jak najszybciej** lub **Odinstaluj pakiet Office**.
    
    ![In the Manage Office deployment pane, choose either Install Office as soon as possible, or Uninstall Office.](media/00f24a61-1848-40c0-b037-78d726c7d757.png)
  
5. Wybierz **Następny** \> Przejrzyj ustawienia, a następnie wybierz polecenie **Potwierdź**.
    
32-bitowy pakiet Office zostanie automatycznie zainstalowany lub odinstalowany na urządzeniach należących do użytkowników określonych przez wskazane grupy.
  
Aby to sprawdzić, otwórz Menedżera zadań na komputerze wybranym na potrzeby instalacji pakietu Office i znajdź proces Szybka instalacja pakietu Microsoft Office.
  


