SOUNDHIT PROMO — SISTÈM ENSKRIPSYON V11

Fonksyon ki prepare:
- Kreye kont kliyan avèk imèl ak modpas.
- Voye non konplè ak telefòn nan metadata pou trigger Supabase la.
- Konekte kliyan avèk imèl/modpas.
- Kenbe sesyon epi dekonekte.
- Montre mesaj pou verifikasyon imèl.
- Pa estoke modpas nan localStorage.
- Kont ki fèk kreye rete customer; pa gen fason piblik pou bay wòl admin.

Pou konekte:
1. Supabase > Project Settings > API.
2. Pran Project URL la.
3. Pran anon/public oswa publishable key la sèlman.
4. Mete yo nan shp-config.js.
5. Supabase > Authentication > URL Configuration: mete URL sit la nan Site URL ak Redirect URLs.
6. Authentication > Providers > Email: verifye reglaj Email confirmations.
7. Teste ak yon imèl ou kontwole, epi teste verifikasyon, koneksyon ak dekoneksyon.

Sekirite:
- Pa janm mete service_role key sou sit la.
- Pa voye modpas oswa kle sekrè nan chat.
- Trigger SQL ki deja prepare a dwe kreye yon profile customer ak full_name/phone.
- Kolòn country poko egziste nan profiles; peyi a rete nan metadata Auth pou kounye a.
- Fòm kontni, kòmand, peman ak tablodbò admin poko konekte ak backend la.
- Sa se premye entegrasyon Auth; li poko yon lansman pwodiksyon. Fòk nou teste RLS, reset modpas ak tout aksè anvan piblikasyon.

Paj services.html la se yon paj enfòmasyon estatik, li pa bezwen Supabase. Ou ka modifye deskripsyon sèvis yo dirèkteman nan fichye a.
