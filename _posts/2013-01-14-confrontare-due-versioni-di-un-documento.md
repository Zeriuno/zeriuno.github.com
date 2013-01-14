--- 
title: Confrontare due versioni di un documento
layout: post
date: 2013-01-14
status: publish
tags: 
- Scrittura
- Collaborazione
type: post
published: true
---

In uno dei primi interventi su Zeriuno ho parlato degli [strumenti di revisione][1]: imprescindibili per collaborare in maniera efficace su un testo. Tuttavia lo strumento può non essere padroneggiato da qualcuno, che potrebbe intervenire su un documento senza attivare la rilevazione dei cambiamenti. Il documento risultante non palesa i cambiamenti che sono stati effettuati, nondimeno esistono alcuni strumenti per intervenire <span lang="la">a posteriori</span>, oltre alla pazienza ed all'attenzione (sempre necessarie), s'intende.

##<span lang="en">Microsoft Word</span>
Il primo potrebbe essere <span lang="en">Microsoft Word</span>, che nella versione per <span lang="en">Mac</span> offre quest'opzione già dall'edizione 2008 (prima non saprei, ma non lo escludo). Nel menù *Strumenti*, alla voce *Revisioni*, viene offerto il comando *Confronta verisoni...*.

<img src="/immagini/word1.gif" title="" alt="Barra del menù, Strumenti, Revisioni, Confronta versioni…">

Per questa via <span lang="en">Word</span> consente di selezionare un documento che confronterà con quello già aperto, segnalando i cambiamenti in maniera analoga a quella già illustrata.

<img src="/immagini/word1.gif" title="" alt="Le revisioni sono segnalate al margine del testo">

Tra le risorse che conosco <span lang="en">Word</span> rappresenta <del>la sola a non potere essere usata solo su <span lang="en">Mac</span></del> ed è probabilmente la più efficiente.

##Le alternative

Un'applicazione, a pagamento, capace di effettuare confronti è [Kaleidoscope][2]. Avendola usata in un paio di occasioni (la versione di prova), posso dire che non è di immediata comprensione (pur considerando che molto dipende dalle differenze tra i documenti confrontati); l'eventuale integrazione dei cambiamenti deve essere effettuata in un secondo momento (una annunciata revisione dell'applicazione forse risolverà la questione). Caratteristica distintiva è la capacità di potere effettuare lo stesso compito anche con delle immagini (sempre meglio sapere).

Gli altri due strumenti che conosco sono gratuiti, ma entrambi pensati per dei programmatori, e quindi per confrontare righe di codice (già Kaleidoscope mi sembra rivolgersi soprattutto a questo pubblico). Nulla impedisce altri di servirsene, ma l'ergonomia e l'efficacia non saranno di certo paragonabili agli strumeti di revisione. [<span lang="en">DiffMerge</span>][5], appena scoperto [grazie a Nicola Losito][3] (è stato il suo intervento a farmi pensare a scrivere questo appunto). Ulteriore scoperta: esiste anche un programma analogo ed omonimo per <span lang="en">Windows</span>: [<span lang="en">DiffMerge</span>][6], a pagamento.

<span lang="en">FileMerge</span> è l'ultimo della lista: per averlo serve installare [<span lang="en">Xcode</span>][4], e benché sia gratuito, farsi carico dei diversi <abbr title="Giga Byte" lang="en">GB</abbr> che implica, sarebbe inutile per chi non lo conosce, non usa e non conta usare il terminale. Ad ogni modo una volta installato <span lang="en">Xcode</span>, <span lang="en">FileMerge</span> si trova… be', l'ultima volta mi ricordo che era nella cartella <span lang="en">/Developer/Applications/Utilities</span>, ora non lo ritrovo, ma si comunque può aprire via <span lang="en">Xcode</span>.

<img src="/immagini/filemerge.gif" title="Come aprire FileMerge, da Xcode" alt="Barra del menù, Xcode, Open Developer Tool, Filemerge">

Se qualcuno conosce altri strumenti, soprattutto per altre piattaforme, o anche dei metodi efficaci, sono in ascolto!

[1]: /2011/10/12/gli-strumenti-di-revisione.html "Gli strumenti di revisione, su Zeriuno"
[2]: http://kaleidoscopeapp.com/ "Il sito di Kaleidoscope, in inglese"
[3]: http://koolinus.tevac.com/2013/01/09/confronta-il-contenuto-di-file-e-cartelle-con-diffmerge/ "Nicola ne parla nel suo blog su Tevac"
[4]: https://itunes.apple.com/it/app/xcode/id497799835?mt=12 "Xcode"
[5]: http://www.sourcegear.com/diffmerge/index.html "DiffMerge"
[6]: http://www.diffmerge.net/ "DiffMerge per Windows"