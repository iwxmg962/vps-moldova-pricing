# VPS Moldova ieftin: ce primești la €5 pe lună, când merită să urci la un plan mai scump și cum se compară prețurile din Chișinău

Un VPS KVM în Chișinău pornește de la **€5,00 pe lună** la AvaHost, cu root complet, stocare NVMe, IPv4 dedicat, port de 1 Gbps și suport de ingineri 24/7, facturat lunar în EUR. Gama urcă până la **€40,00 pe lună**. Întrebarea care decide bugetul nu este câte vCPU are planul cel mai mic, ci ce anume cumperi cu primii cinci euro și în ce moment încetează să mai fie o afacere bună să adaugi resurse la aceeași mașină.

Mai jos găsești ce publică furnizorul despre gama lui de prețuri, o comparație cu ce cer alți provideri din același oraș pentru o configurație de 1 GB, ce poți instala pe un KVM și criteriul tehnic pe care AvaHost îl dă el însuși pentru momentul în care ar trebui să te oprești din scalat vertical.

## Ce plan ajunge pentru majoritatea proiectelor

> Un blog, un proxy personal, un mic API sau un server de test încap în planul de start din gama AvaHost: de la **€5,00/lună**, în EUR, cu facturare lunară. Ai nevoie de Windows Server, de un panou de control comercial sau de mai multe vCPU-uri pentru o bază de date activă? Alegi un plan superior din aceeași gamă, până la €40,00/lună.

👉 [Vezi planurile VPS AvaHost și prețurile actuale](https://my.ava.hosting/aff.php?aff=15562)

## Gama de prețuri AvaHost

Pagina oficială de VPS anunță intervalul de preț și ce include fiecare plan, iar configurația exactă (vCPU, RAM, spațiu pe disc) se stabilește în configurator, la comandă. Nu completăm noi cifre pe care furnizorul nu le publică pe pagină, pentru că o tabelă inventată te-ar costa mai mult decât un click în plus.

| Plan | Ce include | Preț | Facturare | Comandă |
| --- | --- | --- | --- | --- |
| Configurator VPS, gamă de planuri | KVM cu resurse dedicate, root complet, NVMe SSD, IPv4 dedicat, port 1 Gbps, protecție DDoS, suport ingineri 24/7 prin tichet și chat | €5,00–€40,00/lună | Lunar, în EUR; perioada de facturare se alege la finalizarea comenzii | [Alege configurația potrivită](https://my.ava.hosting/aff.php?aff=15562) |

Toate planurile din gamă includ, fără diferență de nivel:

- acces root complet și conectare prin SSH, respectiv RDP pe imaginile Windows;
- stocare NVMe SSD și port de rețea de 1 Gbps;
- un IPv4 dedicat pentru fiecare instanță, cu posibilitatea de a cere adrese suplimentare;
- protecție DDoS activă;
- suport tehnic asigurat de ingineri, non-stop, prin tichet și chat.

Furnizorul gestionează infrastructura de hosting din Chișinău din **2002**, iar pagina menționează un SLA de disponibilitate de 99,9% pentru nivelul de alimentare și rețea. Pentru cine are nevoie de un furnizor cu istoric verificabil în documentația de achiziții, această vechime contează mai mult decât un logo.

## €5 în Chișinău: ce se cumpără de fapt cu banii aceștia

Aici apare prima diferență pe care o ratată majoritatea comparațiilor: prețurile afișate sunt în monede diferite, iar unele sunt fără taxe. Tabelul de mai jos conține doar valori lunare verificate pe paginile furnizorilor, la data consultării.

| Furnizor | Configurație de start | Preț lunar | Monedă și taxe |
| --- | --- | --- | --- |
| AvaHost | gamă de la €5, configurație aleasă în configurator, IPv4 dedicat, 1 Gbps | €5,00 | EUR, fără taxe suplimentare menționate pe pagină |
| EDIS Global | 1 GB RAM, 15 GB SSD, 1 TB trafic, 1 vCPU | €4,99 | EUR |
| AlexHost | 1 vCore, 1,5 GB RAM, 10 GB NVMe, rețea partajată de 100 Mbps | €6,00 | EUR |
| LikeVPS | 1 GB RAM ECC, trafic nemăsurat, până la 10 Gbps | $9,50 | USD |
| FormoHost | 1 vCPU, 1 GB RAM, 15 GB disc, 1 TB trafic | $9,49 + 10% taxă, adică aproximativ $10,44 | USD |

Trei observații care schimbă calculul:

**Taxa de 10% de la FormoHost** se adaugă la prețul afișat, deci planul de 1 GB ajunge la circa $10,44 pe lună, nu la $9,49. **LikeVPS** are o neconcordanță pe propria pagină: antetul anunță „de la $8,50/lună”, iar tabelul de planuri listează $9,50/lună pentru configurația de 1 GB. Am luat tabelul ca referință, fiind partea detaliată a paginii. **EDIS Global** afișează €4,99 pentru 1 GB, cel mai mic preț din eșantion, dar și cea mai mică rezervă de creștere pe termen lung, despre care vorbim mai jos.

Cursul leu-euro și cel dolar-leu pot inversa ordinea între două planuri apropiate ca preț. Dacă pornești de la €5 și alegi între un plan de €4,99 și unul de $9,50, diferența reală nu este de câțiva dolari, ci de aproximativ 80–90%, în funcție de cursul zilei.

## Ce poți instala pe un VPS KVM de la AvaHost

Virtualizarea KVM înseamnă izolare la nivel de kernel: fiecare instanță are alocare fixă de vCPU și RAM, nu un pool partajat în care vecinii tăi consumă din aceleași resurse. Practic, poți încărca module de kernel, poți scrie reguli iptables sau nftables proprii și poți instala driverul WireGuard fără să ceri aprobarea nimănui. Aceleași reguli se aplică agenților de monitorizare: Prometheus, Zabbix sau Datadog rulează în interiorul mașinii tale, cu acces complet la metricile gazdei.

La instalare ai la dispoziție imagini Debian, Ubuntu, CentOS, Fedora, Windows Server și imagini personalizate. Conectarea se face prin SSH pe Linux și RDP pe Windows, cu drepturi de root sau administrator.

Panourile de control sunt opționale. ISPmanager, Plesk, DirectAdmin și cPanel se pot instala ca soluții plătite, potrivite agențiilor care administrează mai multe site-uri de client. Există și varianta gratuită, potrivită inginerilor care preferă lucrul din SSH: Webmin, HestiaCP, aaPanel, CyberPanel, ISPConfig, Virtualmin sau Froxlor. Dacă nu vrei să pierzi o oră cu instalarea, poți cere suportului tehnic să o facă.

👉 [Alege imaginea de sistem și panoul de control pentru VPS-ul tău](https://my.ava.hosting/aff.php?aff=15562)

Pe partea de stocare, NVMe contează în două locuri concrete: la scrierea sincronă din PostgreSQL (fsync pe WAL) și la persistarea Redis prin AOF sau RDB, unde o scriere lentă blochează bucla de evenimente. Pentru un blog sau un proxy, diferența este mică. Pentru un magazin WooCommerce cu comenzi simultane, este diferența dintre o pagină care se încarcă și una care dă timeout.

## Plata, moneda și pragul de intrare

AvaHost acceptă carduri Visa și Mastercard, PayPal, transfer bancar, WebMoney și peste 20 de criptomonede, inclusiv BTC, ETH și USDT. Prețurile sunt denominate în EUR, iar facturarea este lunară implicit, cu posibilitatea de a alege perioada la finalizarea comenzii.

Două lucruri de verificat înainte de a plăti. Transferul bancar și plățile în criptomonede vin cu comisioane proprii, care nu apar în prețul planului, iar la un abonament de €5 pe lună comisionul poate reprezenta o parte vizibilă din cost. Perioada de facturare aleasă la comandă se menține pe durata abonamentului, așa că merită decisă o singură dată, cu atenție.

👉 [Începe comanda și verifică metodele de plată acceptate](https://my.ava.hosting/aff.php?aff=15562)

## Când nu mai are sens să adaugi RAM și vCPU

AvaHost dă el însuși criteriul în documentația tehnică: scalarea verticală pe un VPS KVM rămâne eficientă din punct de vedere economic până când instanța ajunge la aproximativ **80% utilizare vCPU în ferestre de vârf susținute**. Trecut de acest prag, pentru sarcini cu stare (baze de date) soluția recomandată este un server dedicat, cu izolare bare-metal, controlul RAID-ului hardware și management out-of-band.

Cifra de 80% este utilă pentru că îți dă un moment clar de oprire. Sub ea, mai mulți vCPU înseamnă mai multă capacitate reală. Peste ea, plătești tot mai mult pentru aceeași arhitectură, iar latența și variance-ul încep să se vadă în aplicație.

Există și un plafon dur la vecinii din piață. EDIS Global permite creșterea unei instanțe până la 8 vCPU, 24 GB RAM și 400 GB spațiu suplimentar, iar modificările de RAM, vCPU sau stocare cer oprirea și repornirea mașinii, cu extinderea ulterioară a partiției și a sistemului de fișiere făcută de tine. Dacă proiectul tău are nevoie de 16 vCPU într-o singură mașină, nu ajungi acolo prin upgrade de plan.

Pentru servicii cu stare, recomandarea oficială a AvaHost este explicită: PostgreSQL ca nod primar, un master de cluster Redis sau liderul unei cozi de mesaje ar trebui să ruleze pe hardware dedicat cu RAID-10, nu pe un VPS. Un VPS de €5 este o alegere bună pentru un site, un proxy sau un mediu de test. Nu este o alegere bună pentru baza de date principală a unui magazin cu trafic constant.

## Cui nu i se potrivește AvaHost

**Cine are nevoie de latență minimă în Europa de Vest sau în SUA.** Serverele sunt în Chișinău, iar pentru un public exclusiv în Frankfurt sau New York vei plăti latența de traversare. FormoHost publică măsurători proprii care arată ordinul de mărime: Istanbul aproximativ 33 ms, Viena 36 ms, Frankfurt 38 ms, Amsterdam 42–50 ms, New York 122 ms. LikeVPS anunță 15–25 ms pentru Europa de Est. AvaHost nu publică o tabelă de latență, deci cere un IP de test și fă ping din locul unde sunt utilizatorii tăi.

**Cine vrea un server administrat complet.** Toate planurile vin cu root complet, ceea ce înseamnă că instalarea aplicațiilor, configurarea, securizarea și backup-urile rămân în sarcina ta. EDIS Global spune explicit că sarcinile din interiorul VPS-ului nu intră în scopul suportului, iar la AvaHost situația este similară: suportul acoperă infrastructura, nu conținutul mașinii.

**Cine are nevoie doar de un site simplu.** Un plan de shared hosting costă mai puțin și nu îți cere să administrezi un sistem de operare. Un VPS se justifică atunci când ai nevoie de root, de servicii proprii sau de izolare pe care shared hosting-ul nu o oferă.

## Întrebări frecvente

**Pot instala Windows pe un VPS AvaHost?**
Da. Imaginile disponibile la instalare includ Windows Server, cu acces la nivel de administrator prin RDP. Licențierea Microsoft rămâne responsabilitatea ta.

**Trebuie să trimit documente de verificare a identității?**
Pagina de VPS nu publică o procedură de KYC. La plățile cu cardul intervine verificarea antifraudă a procesatorului, iar la criptomonede, cea a rețelei. Dacă ai cerințe de conformitate sau ai nevoie de facturare pe firmă, întreabă în tichet înainte de comandă.

**Merge un WordPress pe planul de €5?**
Pentru un blog cu trafic redus, da. Pentru un magazin WooCommerce cu comenzi simultane, ai nevoie de suficientă RAM cât să nu fie evacuat buffer pool-ul InnoDB, iar configurația exactă o vezi în configurator înainte de a plăti. AvaHost are și medii preoptimizate pentru WordPress și Joomla, dacă nu vrei să tunezi singur stack-ul.

**Pot plăti cu Bitcoin sau USDT?**
Da, sunt acceptate peste 20 de criptomonede, inclusiv BTC, ETH și USDT, alături de carduri, PayPal, transfer bancar și WebMoney.

**În ce monedă primesc factura?**
În EUR. Facturarea este lunară implicit, iar perioada se alege la finalizarea comenzii.

**Pot primi un al doilea IPv4?**
Da, adresele suplimentare se cer la furnizor. Sunt utile când găzduiești mai multe site-uri cu certificate SSL separate sau când vrei să separi IP-ul de trimitere a e-mailurilor de cel al site-ului.

## Regula de alegere, pe scenarii

Un proxy personal, un nod WireGuard sau un blog mic pornesc de la planul minim de €5,00 pe lună. Un site WordPress cu trafic real sau un API cu o bază de date MySQL activă are nevoie de un plan de mijloc, cu suficientă RAM pentru cache-ul bazei de date. Windows Server, Plesk sau cPanel cer planul care susține sistemul de operare și panoul ales. Iar dacă ai ajuns la aproximativ 80% utilizare vCPU în vârfuri susținute, nu mai cumpăra vCPU: mută baza de date pe un server dedicat cu RAID-10.

Înainte de a da comanda, confirmă trei lucruri: moneda în care ești facturat (EUR), perioada de facturare aleasă și dacă metoda ta de plată adaugă comisioane peste prețul planului.

👉 [Deschide configuratorul AvaHost și alege planul potrivit proiectului tău](https://my.ava.hosting/aff.php?aff=15562)
