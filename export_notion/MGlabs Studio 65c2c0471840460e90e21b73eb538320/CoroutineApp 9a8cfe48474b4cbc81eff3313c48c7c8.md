---
title: "CoroutineApp"
layout: default
permalink: /export_notion/mglabs-studio/coroutineapp/
---

# CoroutineApp

<aside>
<img src="Lavorattivamente%204a9240d26b164529b75faeca5f0c6760/transparent.png" alt="Lavorattivamente%204a9240d26b164529b75faeca5f0c6760/transparent.png" width="40px" /> **Coroutines forever!**

Questa app è stata creata con l’unico scopo di testare un po’ di **Kotlin Coroutines.**

Se non sapete cosa sono, potete semplicemente usarla come una normale ToDoApp ed ignorare tutte le spiegazioni.

![Screenshot_20221205-094935_ToDo.jpg](CoroutineApp%209a8cfe48474b4cbc81eff3313c48c7c8/Screenshot_20221205-094935_ToDo.jpg)

![Screenshot_20221207-212835_ToDo.jpg](CoroutineApp%209a8cfe48474b4cbc81eff3313c48c7c8/Screenshot_20221207-212835_ToDo.jpg)

- Kotlin Coroutines e RxJava sono gli attuali trend di sviluppo asincrono su piattaforma Android.
- Di base, non risolvono problemi esistenziali che non potessero essere gestiti prima ma, grazie ad una sintassi fortemente ridotta e all’uso sapiente di functional programming, eliminano i codi[...]
- La ***persistency*** di quest’app è implementata con Room e le operazioni asincrone su di esso fanno uso estensivo di Kotlin Coroutines.
- Funzionalità di ***filtering**, **export**, **sharing** ed **import***.

![Screenshot_20221209-172430_ToDo.jpg](CoroutineApp%209a8cfe48474b4cbc81eff3313c48c7c8/Screenshot_20221209-172430_ToDo.jpg)

<aside>
💡 **Tech Stack**

- View Binding
- WebView
- RecyclerView - Adapter - ViewHolder
- View Models - StateFlow (al posto di LiveData) - Repository
- Room
- Dependency Injection (Koin)
- Kotlin Coroutines
- Handlebars (*html generator*)
- OkHttp (*http client*)
- Moshi (*json parser*)
- WorkManager
</aside>

</aside>
``` ````

I passaggi pratici per applicare la modifica:
1. Clona il repo (se non l’hai già):  
   git clone https://github.com/MGLabs/mglabs.github.io.git
2. Modifica il file locale (sostituisci il contenuto con quello sopra). Puoi anche rinominare la cartella/file per rimuovere gli spazi (consigliato) ad es. export_notion/MGlabs-Studio/.../coroutineapp.md
3. Commit e push:
   git add <path-to-file>
   git commit -m "Render CoroutineApp with front matter / add permalink"
   git push
4. Controlla Settings → Pages del repo per vedere che branch è selezionato e che il deploy sia avviato. Attendi qualche minuto e visita l’URL pubblicato (se hai usato il permalink di esempio: https://mglabs.github.io/export_notion/mglabs-studio/coroutineapp/ ).

Se preferisci non modificare i nomi con spazi, il front matter con permalink risolve comunque la pubblicazione e ti dà un URL più pulito.

Se dopo il push la pagina è ancora testo puro:
- Controlla i log di build di GitHub Pages (nelle Settings → Pages o nelle GitHub Actions se usi workflow) per eventuali errori.
- Verifica che non ci siano file _config.yml che escludono la cartella, o che la cartella non inizi con underscore (es. _folder) che Jekyll ignora.

Vuoi che preparo io una commit patch (posso generare il contenuto pronto) o preferisci che ti guidi passo-passo mentre la fai tu?
