---
description: 'null'
seo-description: 'null'
seo-title: Söka&amp;Promote 8.8 Versionsinformation (04/26/2012)
solution: Target
title: Söka&amp;Promote 8.8 Versionsinformation (04/26/2012)
topic: Release Notes,Site search and merchandising
uuid: ddb9f1af-92a4-4f85-be8f-a36f34d31add
translation-type: tm+mt
source-git-commit: ef818327e1cdaad79ac47575a8dfba1de3dc5c2e

---


# Search&amp;Promote 8.8 Release Notes (04/26/2012){#search-promote-release-notes}

**Nya funktioner**

* Dynamisk faceting

   Möjlighet att dynamiskt motstå en friformsuppsättning med attribut som är kopplade till varje sida med webbplatsinnehåll, som kan ändras (nya attribut läggs till, gamla tas bort eller döps om) från index till index. Dynamisk fasettering mappar automatiskt facken med de verkliga ansiktena. Lagret för guidad sökning hjälper till att underlätta den här funktionen med affärsregler.
* Adobe Search&amp;Promote e-användargränssnitt

   Implementerat Adobe-användargränssnitt för alla Adobe Search&amp;Promote-webbsidor.
* Bättre integrering med Adobes inloggningsportal

   Adobe Search&amp;Promote-kunder kan endast använda Adobes inloggningsportal. Nuvarande [!DNL Adobe Publish]kunder, Adobe SiteSearch och Atomz kommer att fortsätta använda den gamla inloggningen.
* Ny morfologisk analyserare som stöder kinesiska och japanska

   Morfologisk analys tillämpas på index och på söktiden för stöd av kinesiska och japanska.
* Stöd för nya dokumenttyper, som Microsoft Office 2010

   Vid sökning kan olika typer av dokument, som .doc, .docx, .pdf och .mp3, konverteras till HTML innan de matas in i indexeraren.
* Nytt Adobe Search&amp;Promote onlinehjälpsystem

   Onlinehjälpsystemet har ett nytt användargränssnitt och är nu uppgiftsbaserat.

**Korrigeringar och förbättringar**

* Korrigerad överföring av en banderoll live med Stage Manager som resulterade i brutna Dynamic Media Classic-relaterade funktioner i realtid.
* Ett problem har korrigerats där redigeringen av en regel med utlösaren &quot;Frågeparametern finns inte&quot; översattes felaktigt till &quot;Nyckelordet innehåller&quot;.
* Ett problem har korrigerats där du inte kunde redigera parameter andra gången.
* Korrigerade ett problem med Index Connector där två eller flera mappningsdefinitioner inte kan peka på samma metadata/fältvärde.
* Problem med att crawla vissa PDF-dokument har åtgärdats. Uppgradering till 3.03 löser de senaste krascher.
* Lagt till möjlighet till kortare beskrivningar av affärsregler (t.ex. visning av field_table i hanteraren).
* Navigeringsmenyn Guidad sökning hade maximalt nio alternativ. Nu är maxvärdet 20.
* Prestandaförbättringar har gjorts i Index Connector.
