# Cum funcționează Gas Fee

**Gazul** (Gas) este o unitate utilizată pentru măsurarea **cantității de efort de calcul** (Computational Effort) necesar pentru a efectua acțiuni specifice pe Blockchain-ul Ethereum.

Numele în sine nu a fost ales întâmplător. În mod similar cu benzina care alimentează o mașină și îi permite să conducă, gazul din rețeaua Ethereum alimentează tranzacțiile și le permite să efectueze diferite operațiuni.

Fiecare operațiune pe Blockchain-ul Ethereum sau, mai exact, pe
**Ethereum Virtual Machine** (EVM), are un cost de gaz (Gas Fee) asociat.

!!!
De exemplu: adăugarea a 2 numere costă 3 gaz; obținerea soldului
unui cont – 250 gaz; trimiterea unei tranzacții – 15.000 gaz.
!!!

**Contractele inteligente** constau de obicei în mai multe operațiuni care împreună pot costa chiar și sute de mii de Gaz.

Costul gazului în sine nu ne spune cât de mult trebuie să plătim pentru o anumită tranzacție. Pentru a calcula taxa de tranzacție trebuie să înmulțim costul gazului cu prețul gazului.

Prețul gazului este măsurat în **Gwei** – o unitate mai mică decât **Ether**-ul, unde **1 gwei** este egal cu **0,000000001 ETH**. Ne putem gândi la ea ca o unitate majoră și minoră, în mod similar cu dolari și cenți.

De exemplu, să presupunem că vrem să trimitem o tranzacție simplă și prețul ETH este de **4,645.64 USD**. Cele mai multe dintre portofelele populare Ethereum, cum ar fi Metamask, estimează prețurile necesare la gaz și ne permit să alegem între viteza de confirmare a tranzacției: **rapidă, medie și mică**. Să presupunem că portofelul a estimat prețul gazului la **100 gwei** dacă dorim să avem șansa de a ne confirma tranzacția în următorul minut.

Acum putem calcula rapid că trebuie să plătim **6.97 USD** pentru o astfel de tranzacție. Înmulțim costul gazului pentru trimiterea unei tranzacții – **15.000 Gaz** – și prețul gazului – **100 gwei**. Acesta este egal cu **1.500.000 gwei**, care este **0,0015 ETH**. La prețul ETH de **4,645.64 USD**, asta ne oferă **6.97 USD**.
