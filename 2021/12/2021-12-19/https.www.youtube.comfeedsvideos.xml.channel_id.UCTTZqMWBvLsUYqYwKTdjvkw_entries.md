# Source:Mateusz Chrobok, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCTTZqMWBvLsUYqYwKTdjvkw, language:pl-PL

## Dlaczego wszyscy mówią o log4j i co to ma wspólnego z Minecraftem?
 - [https://www.youtube.com/watch?v=RHN4sBe1Eew](https://www.youtube.com/watch?v=RHN4sBe1Eew)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCTTZqMWBvLsUYqYwKTdjvkw
 - date published: 2021-12-19 00:00:00+00:00

Cześć!

Dzisiaj krótki i niespodziewany jak hiszpańska inkwizycja materiał o ataku na log4j nazwany log4shell o numerze CVE-2021-44228. Co to ma wspólnego z Minecraftem? Dlaczego w ostatnich dniach log4j rce wyskakiwał nawet z lodówki? I dlaczego Wasi znajomi administratorzy chodzili ostatnio tak bardzo niewyspani? Postaram się na te pytanie odpowiedzieć w dzisiejszym, spontanicznym materiale. Dla Waszego bezpieczeństwa zaktualizujcie bibliotekę log4j do wersji 2.17.0 lub późniejszej - to rozwiązuje problem.
Możecie sprawdzić swoje logi, czy byliście celem ataku za pomocą grepa (zadziała tylko dla nieobfuskowanych poleceń):

sudo egrep -i -r '\$\{jndi:(ldap[s]?|rmi|dns)://' /var/log

Miłego oglądania i bądźcie bezpieczni!

Rozdziały:
00:00 Intro
00:23 Minecraft i Java
00:41 Czym są logi?
01:21 Jak popularny jest log4j? (SPOILER: BARDZO)
02:00 Czy powinniśmy panikować?
03:11 Jak to działa?
04:07 Przykłady zastosowania
04:34 Kalendarium
05:57 Reakcja
07:01 Próby naprawy błędu
08:12 Co Robić i Jak Żyć?

Źródła:

🐞 Oficjalna strona dedykowana podatności log4shell, autorzy perfekcyjnego logotypu
https://log4shell.com/

🇳🇱 Repozytorium git na temat ataku stworzone przez Holenderskie Centrum Cyberbezpieczeństwa
https://github.com/NCSC-NL/log4shell

🤖 Megathread na reddicie na temat ataku
https://bit.ly/3scrjvE

📜 Lista potencjalnie narażonych aplikacji, cały czas aktualizowana
https://bit.ly/3p2q1RV a także https://bit.ly/3yJ3MUr

🐛 Randori o ataku na log4j
https://bit.ly/3mdeY6W

📊 Różne odmiany ataku na log4j
https://bit.ly/30AWrd3

🇵🇱 Polski CERT ostrzega przed podatnością w log4j
https://bit.ly/3yyJ89m

🇨🇭 Szwajcarski CERT o ataku na log4j
https://bit.ly/3GOFOtR

🎩 Prezentacja Alvaro Muñoza i Oleksandra Mirosha na Black Hat o ataku JNDI/LDAP
https://bit.ly/33wOCWJ

✏️ Proof-of-Concept wykonany przez nice0e3
https://bit.ly/3p7PXvL

🔬 Tester, czy jesteśmy podatni na atak log4shell
https://bit.ly/3e3BBWI

🔥 WAF Cloudflare oraz Akamai próbują bronić swoich klientów przed atakiem
https://bit.ly/3F9pnbc i https://bit.ly/3yA3ZJu

💭 Relevant xkcd
https://xkcd.com/2347/

👤 Informacje o malware Conti, który zaczyna wykorzystywać log4shell
https://bit.ly/33FVNft

© Wszystkie znaki handlowe należą do ich prawowitych właścicieli.

🔜 Niedługo porozmawiamy o Pegasusie.

Dziękuję za gościnę Upojonym -  🍻🍕 multitapowi w Kato! 👌
https://www.facebook.com/upojenimultitap/
https://www.instagram.com/upojeni/

© Wszystkie znaki handlowe należą do ich prawowitych właścicieli.

Dziękuję za Waszą uwagę. ❤️

Znajdziecie mnie również na;
Instagramie @mateuszemsi https://www.instagram.com/mateuszemsi/
Twitterze @MateuszChrobok https://twitter.com/MateuszChrobok
LinkedInie @mateuszchrobok https://www.linkedin.com/in/mateuszchrobok/
Podcasty na Anchor https://anchor.fm/mateusz-chrobok
Podcasty na Spotify https://open.spotify.com/show/6y6oWs20HwRejktOWHTteR
Podcast na  Apple Podcasts https://podcasts.apple.com/us/podcast/mateusz-chrobok-bezpiecze%C5%84stwo-startupy-i-sztuczna-inteligencja/id1617335932 
Patronite @MateuszChrobok https://patronite.pl/MateuszChrobok

