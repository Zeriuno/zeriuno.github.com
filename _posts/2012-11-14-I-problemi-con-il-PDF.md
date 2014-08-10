--- 
title: "I problemi con il PDF"
layout: post
status: publish
tags:
- Gestione documenti
- 
type: post
published: true
---
<abbr title="Portable Document Format" lang="en">PDF</abbr> si è oramai affermato come un formato di documenti ubiquo. <span lang="en">Fletcher Penney</span> ha tra l'altro messo a punto un rigoroso sistema di gestirli, per il suo lavoro, che io trovo un po' complesso e macchinoso, ma che non è scevro di [spunti interessanti][1].

Ciò non ostante, si tratta di un formato ben lontano dall'essere comodo ed efficiente. Innanzi tutto si fonda su un'ambiguità, quella tra immagine e testo. Benché contenga testo, non necessariamente un PDF lo rappresenta in quanto tale, informaticamente. Nulla cambia per l'occhio umano, ma molto cambia per il <span lang="en">computer</span>, e quindi per il lettore: se il testo non è riconosciuto come tale, non è neppure possibile effettuare una ricerca testuale.

<img title="Una ricerca infruttuosa" src="/immagini/pdf1.png" alt="Ricerca di testo infruttuosa in un PDF">

La parola *presidente* è ben presente in questo documento, ma non può essere trovata dal computer: il PDF (credo sia stato generato da <span lang="en">Microsoft Word</span> in una versione di <span lang="en">Windows</span> anteriore alla 8) è in formato immagine, ed il testo resta invisibile agli occhi del computer.
Storie dell'arte [segnalava][2] l'impossibilità della ricerca testuale per le pubblicazioni messe a disposizione da <span lang="en">MetPublications</span>. Il problema è analogo a quello del documento soprastante: non si tratta di libri che sono stati scanditi, ma di documenti informatici trasformati in PDF immagine.

Il PDF è inoltre un formato molto complesso. Talmente complesso che non esistono garanzie che un documento venga visualizzato correttamente da altri che il programma che l'ha prodotto. Di seguito lo stesso documento è stato aperto rispettivamente con <span lang="en">Adobe Reader</span>, visualizzato all'interno di <span lang="en">Firefox</span> e, ultimo, dal programma di sistema di <span lang="en">Mac OS X</span> Anteprima, con differenze rilevanti.

<img title="Acrobat Reader" src="/immagini/pdf2.jpg" alt="Un PDF leggibile">
<img title="Firefox" src="/immagini/pdf3.jpg" alt="Un PDF leggibile, ma tipograficamente malconcio">
<img title="Anteprima" src="/immagini/pdf4.jpg" alt="Un PDF assolutamente illeggibile">

In sintesi: un PDF pone il problema di distinguere tra formato immagine (tra l'altro, generalmente più pesante da archiviare) e testo, e se viene visualizzato male (contenuto alterato, illeggibile, o anche completamente assente), non necessariamente è perché il documento è danneggiato.

Per chi volesse leggere questi documenti con il navigatore <span lang="en">Firefox</span> (il migliore a mio avviso), consiglio l'ottima estensione [PDF.js][4], un lettore PDF in <span lang="en">Javascript</span>.

Una discussione al riguardo, che segnala anche la potenziale pericolosità di PDF è sul Forum di Tevac, [qui][3].


[1]: http://fletcherpenney.net/2012/05/workflow "Sul suo sito, in inglese"
[2]: http://storiedellarte.com/2012/10/metpublications.html "Su Storie dell'arte"
[3]: http://forum.tevac.com/topic/79856-anteprima-questo-sporco-brutto-programma/ "PDF sul Forum di Tevac"
[4]: https://addons.mozilla.org/en-US/firefox/addon/pdfjs/ "PDF.js"