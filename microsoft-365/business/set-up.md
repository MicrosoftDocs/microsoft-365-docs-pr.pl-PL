---
title: Konfigurowanie usługi Microsoft 365 Business przy użyciu kreatora konfiguracji
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: article
f1_keywords:
- O365E_M365SetupBanner
- BCS365_M365SetupBanner
ms.service: o365-administration
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MSB365
search.appverid:
- BCS160
- MET150
ms.assetid: 6e7a2dfd-8ec4-4eb7-8390-3ee103e5fece
description: Dowiedz się, jak skonfigurować Microsoft 365 Business, wykonując cztery kroki.
ms.openlocfilehash: f57239b884bd2e186c0bc01973130a10fa4cfe84
ms.sourcegitcommit: eb1a77e4cc4e8f564a1c78d2ef53d7245fe4517a
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 11/28/2018
ms.locfileid: "26982197"
---
# <a name="set-up-microsoft-365-business-by-using-the-setup-wizard"></a><span data-ttu-id="57f79-103">Konfigurowanie usługi Microsoft 365 Business przy użyciu kreatora konfiguracji</span><span class="sxs-lookup"><span data-stu-id="57f79-103">Set up Microsoft 365 Business by using the setup wizard</span></span>

<span data-ttu-id="57f79-104">Wykonaj kroki 1-4 poniżej.</span><span class="sxs-lookup"><span data-stu-id="57f79-104">Complete steps 1-4 below.</span></span>
  
### <a name="set-up-microsoft-365-business"></a><span data-ttu-id="57f79-105">Konfigurowanie usługi Microsoft 365 Business</span><span class="sxs-lookup"><span data-stu-id="57f79-105">Set up Microsoft 365 Business</span></span>

<span data-ttu-id="57f79-106">Obejrzyj film o tym, jak skonfigurować Microsoft 365 Business, gdy nie masz usługi Active Directory na lokalnym:</span><span class="sxs-lookup"><span data-stu-id="57f79-106">Watch a video on how to set up Microsoft 365 Business when you don't have an on-premises Active Directory:</span></span>
  
> [!VIDEO https://www.microsoft.com/videoplayer/embed/0705c337-f3e8-4d28-bb6c-530cd28e99f2?autoplay=false]
  
<span data-ttu-id="57f79-p101">Kroki konfiguracji zawiera informacje dotyczące ustawień, które zawierają lokalną usługę Active Directory. Jeśli chcesz w dalszym ciągu dostęp do urządzeń przyłączonych do domeny, przeczytanie następujących artykułów dla dwóch różnych rozwiązanie pozwalające który i wykonaj kroki przed uruchomieniem Kreatora instalacji:</span><span class="sxs-lookup"><span data-stu-id="57f79-p101">The set-up steps include information for setups that include local Active Directory. If you want to continue to access domain-joined devices, read the following articles for two different way of enabling that, and complete the steps before you run the Setup wizard:</span></span>
  
- [<span data-ttu-id="57f79-109">Włączanie zarządzania przez usługę Microsoft 365 Business dla urządzeń przyłączonych do domeny systemu Windows 10</span><span class="sxs-lookup"><span data-stu-id="57f79-109">Enable domain-joined Windows 10 devices to be managed by Microsoft 365 Business</span></span>](manage-windows-devices.md)
    
    <span data-ttu-id="57f79-110">-Jest to zalecany sposób.</span><span class="sxs-lookup"><span data-stu-id="57f79-110">-This is the recommended way.</span></span>
    
- [<span data-ttu-id="57f79-111">Dostęp do zasobów lokalnych z Azure urządzenia przyłączonych do AD w Microsoft 365 Business</span><span class="sxs-lookup"><span data-stu-id="57f79-111">Access on-premises resources from an Azure AD-joined device in Microsoft 365 Business</span></span>](access-resources.md)
    
### <a name="step-1-personalize-sign-in"></a><span data-ttu-id="57f79-112">Krok 1: Spersonalizować logowanie</span><span class="sxs-lookup"><span data-stu-id="57f79-112">Step 1: Personalize sign-in</span></span>

1. <span data-ttu-id="57f79-p102">Zaloguj się do usługi [Microsoft 365 Business](https://portal.microsoft.com) za pomocą poświadczeń administratora globalnego. Wybierz kafelek **Administrator**, aby przejść do centrum administracyjnego.</span><span class="sxs-lookup"><span data-stu-id="57f79-p102">Sign in to [Microsoft 365 Business](https://portal.microsoft.com) by using your global admin credentials. Choose the **Admin** tile to go to the admin center.</span></span> 
    
2. <span data-ttu-id="57f79-115">W centrum administracyjnym wybierz pozycję **Rozpocznij konfigurowanie** (lub pozycję **Kontynuuj konfigurowanie** w zależności od swojego stanu), aby uruchomić kreatora.</span><span class="sxs-lookup"><span data-stu-id="57f79-115">Choose **Start setup** (depending on your state you may see **Continue setup** instead) in the admin center to start the wizard.</span></span> 
    
3. <span data-ttu-id="57f79-116">Wprowadź żądaną nazwę domeny (np. contoso.com).</span><span class="sxs-lookup"><span data-stu-id="57f79-116">Enter the domain name you want to use (like contoso.com).</span></span>
    
    <span data-ttu-id="57f79-p103">Przejdź dalej i wprowadź swoją domenę, nawet jeśli po sprawdzeniu podczas używania Azure AD Connect, np. Następujące dwa kroki można pominąć Jeśli Azure AD Connect używane do zweryfikowania domeny.</span><span class="sxs-lookup"><span data-stu-id="57f79-p103">Go ahead and enter your domain even if you have verified it while using Azure AD Connect, for example. The following two steps do not apply to you if you used Azure AD Connect to verify your domain.</span></span>
    
4. <span data-ttu-id="57f79-119">Postępuj zgodnie z instrukcjami w kreatorze [Tworzenie rekordów DNS u dowolnego dostawcy usług hosta DNS dla usługi Office 365](https://support.office.com/article/7b7b075d-79f9-4e37-8a9e-fb60c1d95166) sprawdza, czy użytkownik jest właścicielem domeny.</span><span class="sxs-lookup"><span data-stu-id="57f79-119">Follow the steps in the wizard to [Create DNS records at any DNS hosting provider for Office 365](https://support.office.com/article/7b7b075d-79f9-4e37-8a9e-fb60c1d95166) that verifies you own the domain.</span></span> 
    
    <span data-ttu-id="57f79-p104">Można wyświetlić przykład wideo [wideo: Instalatora Office 365 w nowym Centrum Admin](https://support.office.com/article/a8c2002a-34bc-4ab3-93d8-9b5156c48bf8). Należy zauważyć, że ten film nie obejmuje czynności ochrony danych systemu Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="57f79-p104">You can view an example video of [Video: Setup Office 365 in the new Admin Center](https://support.office.com/article/a8c2002a-34bc-4ab3-93d8-9b5156c48bf8). Note that this video does not include the data protection steps of Microsoft 365 Business.</span></span>
    
    ![Screenshot of the Business Cloud Suite setup wizard.](media/3c4fd40c-2de1-4a87-8ee0-78d3928c7bb7.png)
  
### <a name="step-2-add-users-and-assign-licenses"></a><span data-ttu-id="57f79-123">Krok 2: Dodawanie użytkowników i przypisywanie licencji</span><span class="sxs-lookup"><span data-stu-id="57f79-123">Step 2: Add users and assign licenses</span></span>

1. <span data-ttu-id="57f79-124">Użytkowników możesz dodać od razu tutaj albo [później](add-users-m365b.md) w centrum administracyjnym.</span><span class="sxs-lookup"><span data-stu-id="57f79-124">You can add users here, or you can [add users later](add-users-m365b.md) in the admin center.</span></span> 
    
    <span data-ttu-id="57f79-125">Każdy dodany użytkownik automatycznie otrzymuje licencję na usługę Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="57f79-125">Any users you add get automatically assigned a Microsoft 365 Business license.</span></span>
    
2. <span data-ttu-id="57f79-p105">Jeśli Twoja subskrypcja usługi Microsoft 365 Business zawiera już użytkowników (na przykład użyto narzędzia Azure AD Connect), zobaczysz opcję przypisania im licencji. Możesz dodać licencje dla tych użytkowników.</span><span class="sxs-lookup"><span data-stu-id="57f79-p105">If your Microsoft 365 Business subscription has existing users (for example, if you used Azure AD Connect) , you will get an option to assign licenses to them now. Go ahead and add licenses to them as well.</span></span>
    
3. <span data-ttu-id="57f79-p106">Zobaczysz też opcję udostępnienia poświadczeń nowym użytkownikom. Możesz wydrukować te informacje, wysłać je pocztą e-mail lub pobrać.</span><span class="sxs-lookup"><span data-stu-id="57f79-p106">You will also get an option to share credentials with the new users you added. You can choose to print them out, email them, or download them.</span></span>
    
4. <span data-ttu-id="57f79-130">Pomiń migrację wiadomości e-mail i wybierz przycisk **Dalej** na stronie **Migracja wiadomości e-mail**.</span><span class="sxs-lookup"><span data-stu-id="57f79-130">Skip migrating email messages and choose **Next** on **Migrate email messages** page.</span></span> 
    
    <span data-ttu-id="57f79-131">Jeśli jest przesuwana od innego dostawcy poczty e-mail i chcesz skopiować dane później, możesz [migracji wiadomości e-mail i kontaktów do usługi Office 365](https://support.office.com/article/a3e3bddb-582e-4133-8670-e61b9f58627e).</span><span class="sxs-lookup"><span data-stu-id="57f79-131">If you are moving from another email provider and want to copy your data later, you can [Migrate email and contacts to Office 365](https://support.office.com/article/a3e3bddb-582e-4133-8670-e61b9f58627e).</span></span>
    
    ![Screenshot of two new users added in the setup wizard](media/8f729967-5c65-4ceb-b737-18119db40564.png)
  
### <a name="step-3-connect-your-domain"></a><span data-ttu-id="57f79-133">Krok 3: Łączenie domeny</span><span class="sxs-lookup"><span data-stu-id="57f79-133">Step 3: Connect your domain</span></span>

> [!NOTE]
> <span data-ttu-id="57f79-134">Jeśli wybrany do korzystania z domeny .onmicrosoft lub używane Azure Połącz AD, nie zobaczysz ten krok.</span><span class="sxs-lookup"><span data-stu-id="57f79-134">If you chose to use the .onmicrosoft domain, or used Azure AD Connect, you will not see this step.</span></span> 
  
<span data-ttu-id="57f79-135">Aby skonfigurować usługi, musisz zaktualizować niektóre rekordy na swoim hoście DNS lub u rejestratora domen.</span><span class="sxs-lookup"><span data-stu-id="57f79-135">To set up services, you have to update some records at your DNS host or domain registrar.</span></span>
  
1. <span data-ttu-id="57f79-p107">Kreator instalacji zazwyczaj wykrywa rejestratorem i zapewnia łącza do instrukcji krok po kroku aktualizować rekordy NS w witrynie sieci Web rejestratora. Jeśli tak nie jest, [Zmień serwery nazw do skonfigurowania usługi Office 365 z dowolnym domen](https://support.office.com/article/a8b487a9-2a45-4581-9dc4-5d28a47010a2).</span><span class="sxs-lookup"><span data-stu-id="57f79-p107">The setup wizard typically detects your registrar and gives you a link to step-by-step instructions for updating your NS records at the registrar website. If it doesn't, [Change nameservers to set up Office 365 with any domain registrar](https://support.office.com/article/a8b487a9-2a45-4581-9dc4-5d28a47010a2).</span></span>
    
2. <span data-ttu-id="57f79-138">Umożliwia to skonfigurowanie poczty e-mail i innych usług.</span><span class="sxs-lookup"><span data-stu-id="57f79-138">Email and other services will be set up for you</span></span>
    
### <a name="step-4-manage-devices-and-work-files"></a><span data-ttu-id="57f79-139">Krok 4: Zarządzanie urządzeniami i pliki robocze</span><span class="sxs-lookup"><span data-stu-id="57f79-139">Step 4: Manage devices and work files</span></span>

1. <span data-ttu-id="57f79-p108">**Chroń pliki robocze na urządzeniach przenośnych** strony ustawić **Chroń pliki robocze, gdy urządzenia są zagubione lub skradzione** i ustawienia **zarządzania dostęp użytkowników do plików pakietu Office na urządzeniach przenośnych** na **na**. Można także przejść każda podrzędna ustawienie klikając cudzysłów ostrokątny obok każdego ustawienia.</span><span class="sxs-lookup"><span data-stu-id="57f79-p108">On the **Protect work files on your mobile devices** page set both **Protect work files when devices are lost or stolen** and **Manage how users access Office files on mobile devices** settings to **On**. You can also access each sub-setting by clicking the chevrons next to each setting.</span></span>
  
  <span data-ttu-id="57f79-142">Wszystkie pliki prac użytkowników licencjonowanych obecnie są chronione na iOS lub androidem, tak szybko jak [zainstalować aplikacje pakietu Office](set-up-mobile-devices.md) (i uwierzytelnianie przy użyciu poświadczeń Microsoft 365 Business).</span><span class="sxs-lookup"><span data-stu-id="57f79-142">All of your licensed users' work files are now protected on iOS and Android devices, as soon as they [install Office apps](set-up-mobile-devices.md) (and authenticate with their Microsoft 365 Business credentials).</span></span> 
  
  ![Screenshot of protect work files on your mobile devices page](media/3139a9aa-6228-4e74-8166-c6a886d7319f.PNG)
  
2. <span data-ttu-id="57f79-144">Na stronie **Konfiguracja urządzenia zestaw Windows 10** ustawieniu **Bezpiecznego urządzenia z systemem Windows 10** **na**.</span><span class="sxs-lookup"><span data-stu-id="57f79-144">On the **Set Windows 10 device configuration** page, set **Secure Windows 10 Devices** setting to **On**.</span></span>
  
   <span data-ttu-id="57f79-145">Można także przejść każda podrzędna ustawienie klikając podwójną strzałkę obok niej.</span><span class="sxs-lookup"><span data-stu-id="57f79-145">You can also access each sub-setting by clicking the chevron next to it.</span></span>
  
3. <span data-ttu-id="57f79-p109">W ustawieniu **Zainstaluj pakiet Office na urządzeniach 10 systemu Windows** **Tak,** Jeśli wszyscy użytkownicy mają komputery Windows 10 i instaluje nie istniejących Office lub -Szybka instalacja pakietu Office. Jeśli nie jest to możliwe, należy ustawić tę opcję na **nie**. Można [automatycznie zainstalować pakiet Office](auto-install-or-uninstall-office.md) później z Centrum administracyjnego, po przygotowaniu komputerów użytkowników. Aby uzyskać instrukcje zobacz [Przygotowanie do instalacji klienta pakietu Office](prepare-for-office-client-deployment.md).</span><span class="sxs-lookup"><span data-stu-id="57f79-p109">Set the **Install Office on Windows 10 Devices** setting to **Yes** if all of your users have Windows 10 computers, and either no existing Office installs, or click-to-run Office installs. If this is not the case, set this option to **No**. You can [automatically install Office](auto-install-or-uninstall-office.md) later from the admin center after you have prepared the user computers. For instructions, see [prepare for Office client installation](prepare-for-office-client-deployment.md).</span></span>
  
    <span data-ttu-id="57f79-150">Pliki robocze licencjonowani użytkownicy na urządzeniach Windows 10 będą rzutowane tak szybko jak [dołączyć do swoich urządzeń Windows 10](set-up-windows-devices.md) do domeny firmy Microsoft 365 Azure AD lub [zainstalować system Windows 10 na nowym komputerze](https://support.office.com/article/c654bd23-d256-4ac7-8fba-0c993bf5a771.aspx) podczas przyłączania się jednocześnie Microsoft 365 Domeny Azure AD firmy.</span><span class="sxs-lookup"><span data-stu-id="57f79-150">The licensed users' work files on Windows 10 devices will be projected as soon as they [join their Windows 10 device](set-up-windows-devices.md) to a Microsoft 365 Business Azure AD domain or [install Windows 10 on a new computer](https://support.office.com/article/c654bd23-d256-4ac7-8fba-0c993bf5a771.aspx) while simultaneously joining the Microsoft 365 Business Azure AD domain.</span></span> 
  
4. <span data-ttu-id="57f79-151">Kliknij przycisk **Dalej** i po zakończeniu instalacji.</span><span class="sxs-lookup"><span data-stu-id="57f79-151">Click **Next** and you are done with setup.</span></span> 
  
    <span data-ttu-id="57f79-152">Proszę zostawić opinię o ten krok, aby pomóc w ulepszeniu doświadczenia.</span><span class="sxs-lookup"><span data-stu-id="57f79-152">Please leave us feedback at this step to help us improve the experience.</span></span>
  
    ![Screenshot of Prepare Windows 10 devices page](media/bff701c1-48a3-44f4-aa95-9d959d57c85b.PNG)
  
## <a name="additional-security-settings"></a><span data-ttu-id="57f79-154">Dodatkowych ustawień zabezpieczeń</span><span class="sxs-lookup"><span data-stu-id="57f79-154">Additional security settings</span></span>

<span data-ttu-id="57f79-155">Oprócz zabezpieczeń i ustawienie zgodności w Kreatorze instalacji można skonfigurować następujące dodatkowe ustawienia:</span><span class="sxs-lookup"><span data-stu-id="57f79-155">In addition to the security and compliance setting in the setup wizard, you can also set up the following additional settings:</span></span>
  
- <span data-ttu-id="57f79-p110">Konfigurowanie ochrony przed niebezpiecznymi załącznikami. **Zaawansowana ochrona przed zagrożeniami** (ATP) identyfikuje niebezpieczną zawartość, a następnie blokuje dostawy niebezpiecznych załączników, ochrona przed wyłudzeniami i infekcjami szkodnika. Aby włączyć ochronę załączników, zobacz [Ustawianie zasad Office 365 ATP bezpieczne załączniki](https://support.office.com/article/078eb946-819a-4e13-8673-fe0c0ad3a775#setpolicy).</span><span class="sxs-lookup"><span data-stu-id="57f79-p110">Set up protection against unsafe attachments. **Advanced Threat Protection** (ATP) identifies malicious content and then blocks delivery of unsafe attachments, helping protect you against phishing schemes and ransomware infections. To activate attachment protection, see [Set up Office 365 ATP Safe Attachments policies](https://support.office.com/article/078eb946-819a-4e13-8673-fe0c0ad3a775#setpolicy).</span></span>
    
- <span data-ttu-id="57f79-p111">Chronić środowisko, gdy użytkownik kliknie niebezpiecznego łącza. ATP sprawdza łącza w wiadomości e-mail w momencie użytkownik kliknie je. Jeżeli łącze jest niebezpieczny, użytkownik jest ostrzegany, nie do odwiedzenia tej witryny lub poinformowane, że witryna została zablokowana. Ułatwia to ochronę przed schematami wyłudzania informacji. [Ustawianie zasad bezpiecznego łącza Office 365 ATP](https://support.office.com/article/bdd5372d-775e-4442-9c1b-609627b94b5d#reveddefaultscc) lub [ustawienie zasady bezpiecznego łącza Office 365 ATP](https://support.office.com/article/bdd5372d-775e-4442-9c1b-609627b94b5d#addemailpolscc).</span><span class="sxs-lookup"><span data-stu-id="57f79-p111">Protect your environment when users click malicious links. ATP examines links in email at the time a user clicks them. If a link is unsafe, the user is warned not to visit the site or informed that the site has been blocked. This helps protect against phishing schemes. [Set up Office 365 ATP Safe Links policies](https://support.office.com/article/bdd5372d-775e-4442-9c1b-609627b94b5d#reveddefaultscc) or [Set up Office 365 ATP Safe Links policies](https://support.office.com/article/bdd5372d-775e-4442-9c1b-609627b94b5d#addemailpolscc).</span></span>
    
- <span data-ttu-id="57f79-p112">Można zachować całą zawartość skrzynki pocztowej, w tym elementów usuniętych przez umieszczenie całej skrzynki pocztowej użytkownika na **spory sądowe przytrzymaj**. Aby uzyskać instrukcje zobacz</span><span class="sxs-lookup"><span data-stu-id="57f79-p112">You can preserve all mailbox content including deleted items by putting a user's entire mailbox on **litigation hold**. For instructions, see</span></span> 
- <span data-ttu-id="57f79-166">[Konfigurowanie przechowywanie wiadomości e-mail z programu Exchange Online archiwizacji](security-features.md#set-up-email-retention-with-exchange-online-archiving).</span><span class="sxs-lookup"><span data-stu-id="57f79-166">[Set up email retention with Exchange Online Archiving](security-features.md#set-up-email-retention-with-exchange-online-archiving).</span></span>
    
- <span data-ttu-id="57f79-p113">Na przykład, skonfigurować niestandardowych **zasad przechowywania**do zachowania przez określoną ilość czasu lub trwale usunąć zawartość z końcem okresu przetrzymania. Można włączyć zasady przechowywania dostosowanych w Centrum zgodności, przejdź do **zarządzania danymi** i papierów wartościowych \> **zatrzymania**, a następnie wykonaj kroki w kreatorze. Aby dowiedzieć się więcej, zobacz [Omówienie zasad przechowywania](https://support.office.com/article/5e377752-700d-4870-9b6d-12bfc12d2423).</span><span class="sxs-lookup"><span data-stu-id="57f79-p113">Set up customized **retention policies**, for example, to preserve for a specific amount of time or delete content permanently at the end of the retention period. You can enable customized retention policies in the Securities and compliance center, go to **Data governance** \> **Retention**, and then follow the steps in the wizard. To learn more, see [Overview of retention policies](https://support.office.com/article/5e377752-700d-4870-9b6d-12bfc12d2423).</span></span>
    
## <a name="next-steps"></a><span data-ttu-id="57f79-170">Dalsze kroki</span><span class="sxs-lookup"><span data-stu-id="57f79-170">Next steps</span></span>

<span data-ttu-id="57f79-171">Dla użytkowników, którzy mają licencje, następnym krokiem jest skonfigurowanie urządzeń.</span><span class="sxs-lookup"><span data-stu-id="57f79-171">For the users that have their licenses, the next step is to set up devices.</span></span><br/> <span data-ttu-id="57f79-172">Zobacz [Konfigurowanie urządzeń z systemem Windows dla użytkowników usługi Microsoft 365 Business](set-up-windows-devices.md) i [Konfigurowanie urządzeń przenośnych dla użytkowników usługi Microsoft 365 Business](set-up-mobile-devices.md).</span><span class="sxs-lookup"><span data-stu-id="57f79-172">See [Set up Windows devices for Microsoft 365 Business users](set-up-windows-devices.md) and [Set up mobile devices for Microsoft 365 Business users](set-up-mobile-devices.md).</span></span> <br/><span data-ttu-id="57f79-173">Zobacz [Zarządzanie usługą Microsoft 365 Business](manage.md), aby uzyskać linki do tematów dotyczących konfigurowania zasad ochrony urządzeń i aplikacji oraz usuwania danych z urządzeń użytkowników.</span><span class="sxs-lookup"><span data-stu-id="57f79-173">See [Manage Microsoft 365 Business](manage.md) for links to topics on how to set device and app protection polices, and how to remove data from user devices.</span></span> 
  

