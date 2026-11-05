Darasi na 4: Cryptography and Hashing in Bitcoin

Ilimin Cryptography da Hashing a Cikin Bitcoin

1. Gabatarwa

Bitcoin yana amfani da wasu dabarun kimiyya na lissafi domin kare kuɗaɗen masu amfani da shi da tabbatar da ingancin transactions.

Daga cikin muhimman dabarun akwai:

- Cryptography
- Hashing
- Digital Signatures
- Public Key Cryptography

Wadannan dabaru suna taimakawa wajen tabbatar da tsaro, amana da ingancin tsarin Bitcoin ba tare da buƙatar wani mutum guda ya kula da dukkan tsarin ba.

2. Menene Cryptography?

Cryptography wani fanni ne na kimiyya da fasaha wanda yake amfani da dabarun lissafi domin kare bayanai daga karantawa ko amfani da su ba tare da izini ba.

A sauƙaƙe, Cryptography yana taimakawa wajen tabbatar da cewa:

- Bayani ya kasance cikin tsaro.
- Wanda ya cancanci yin wani aiki ne kawai zai iya yin sa.
- Za a iya tabbatar da sahihancin saƙo ko transaction.
- Ba a sauya bayanai ba tare da an gano hakan ba.

A Bitcoin, Cryptography yana taka muhimmiyar rawa wajen kare ikon mallakar kuɗi da tabbatar da sahihancin transactions.

3. Menene Hashing?

Hashing wata hanya ce ta mayar da bayanai zuwa wani gajeren sakamako mai tsayayyen tsari da ake kira Hash.

Ana amfani da Hashing wajen samar da alamar bayanai ta musamman.

Misali:

Idan muka shigar da kalmar:

"Bitcoin"

Hashing algorithm zai samar da wani sakamako na musamman.

Idan aka sauya ko da ƙaramin abu a cikin bayanin, sakamakon Hash zai iya sauyawa sosai.

Muhimman siffofin Hashing:

1. Deterministic: Bayanai iri ɗaya suna samar da Hash iri ɗaya idan an yi amfani da algorithm iri ɗaya.
2. Fixed-length output: Algorithm yana samar da sakamako mai tsayayyen tsawo.
3. Avalanche Effect: Ƙaramin sauyi a cikin input yana iya haifar da babban sauyi a cikin output.
4. One-way function: Yana da wahala a samo ainihin bayanan asali daga Hash ɗinsu.
5. Collision Resistance: Yana da wahala a nemo bayanai biyu daban-daban da suke samar da Hash iri ɗaya.

4. Menene SHA-256?

SHA-256 na nufin Secure Hash Algorithm 256-bit.

Wani Hashing Algorithm ne da yake samar da sakamako mai tsawon bits 256, wanda yawanci ake rubutawa da hexadecimal characters 64.

Bitcoin yana amfani da SHA-256 a muhimman sassa na tsarin sa, ciki har da:

- Proof of Work mining.
- Block hashing.
- Transaction ID (TXID), tare da wasu matakan hashing.
- Haɗa bayanai cikin tsarin Merkle Tree.

5. Bambanci Tsakanin Encryption da Hashing

Mutane da yawa suna rikita Encryption da Hashing, amma ba abu ɗaya ba ne.

Encryption: Hanya ce ta ɓoye bayanai ta yadda za a iya dawo da su ta amfani da mabuɗin da ya dace.

Hashing: Hanya ce ta samar da Hash daga bayanai. Ba a tsara shi domin a mayar da Hash zuwa ainihin bayanan ba.

Misali:

- Encryption: Ana ɓoye saƙo, sannan wanda yake da mabuɗin da ya dace zai iya buɗe shi.
- Hashing: Ana samar da alamar bayanai domin a iya tantance su.

6. Public Key da Private Key

Bitcoin yana amfani da tsarin Public Key Cryptography.

Akwai muhimman abubuwa biyu:

Private Key

Wannan sirrin mabuɗi ne wanda yake bai wa mai shi damar sanya hannu a kan transaction.

Dole ne a kiyaye shi sosai. Wanda ya mallaki Private Key yana iya samun ikon sarrafa Bitcoin da yake da alaƙa da shi.

Public Key

Wannan mabuɗi ne da ake iya amfani da shi wajen tantance sahihancin Digital Signature.

Ba daidai yake da Private Key ba, kuma bai kamata a rikita shi da Bitcoin Address ba.

7. Menene Digital Signature?

Digital Signature wata shaida ce ta lissafi da ake amfani da ita wajen tabbatar da cewa transaction ya samu izini daga wanda yake da ikon sanya hannu.

A Bitcoin:

1. Mai amfani yana ƙirƙirar transaction.
2. Wallet yana amfani da Private Key wajen samar da signature.
3. Nodes suna duba sahihancin signature da sauran dokokin transaction.
4. Idan komai ya dace, transaction zai iya shiga mempool kuma daga baya a saka shi cikin block.

Muhimmi: Digital Signature ba yana nufin an ɓoye transaction ba ne. Transactions na Bitcoin suna bayyane a blockchain.

8. Yadda Hashing yake taimakawa wajen Mining

Mining yana amfani da Proof of Work.

Masu hakar Bitcoin suna ƙoƙarin nemo wani block header da SHA-256 hashing zai samar da sakamakon da ya cika sharadin difficulty na network.

Ana yin hakan ta hanyar sauya wasu bayanai, musamman nonce, da sake yin hashing.

Wannan aiki yana buƙatar ƙarfi da makamashi daga kwamfuta.

Mining yana taimakawa wajen:

- Tabbatar da tsarin haɗa blocks.
- Kare network daga wasu nau'ikan hare-hare.
- Tabbatar da cewa an bi dokokin Proof of Work.

9. Menene Merkle Tree?

Merkle Tree wani tsari ne na haɗa Hashes na transactions cikin tsarin bishiya.

Ana amfani da shi wajen samar da Merkle Root wanda yake wakiltar transactions da ke cikin block.

Wannan yana taimakawa wajen tabbatar da cewa wani transaction yana cikin block ba tare da sai an sauke dukkan bayanan blockchain ba.

10. Aikin Gwaji (Practical Exercise)

Dalibai su gwada SHA-256 hashing ta amfani da wannan kayan aiki:

https://emn178.github.io/online-tools/sha256.html

Matakai:

1. Buɗe shafin.
2. Rubuta "Bitcoin".
3. Duba sakamakon SHA-256.
4. Sauya kalmar zuwa "bitcoin".
5. Kwatanta sakamakon.
6. Gwada rubuta "Bitcoin is freedom".
7. Lura da yadda sakamakon yake sauyawa.

Gargaɗi: Kada a taɓa shigar da Private Key, Seed Phrase ko wani sirrin wallet a shafin gwaji ko wani website.

11. Tambayoyin Fahimta

1. Menene Cryptography?
2. Menene Hashing?
3. Menene SHA-256?
4. Wane bambanci ne tsakanin Encryption da Hashing?
5. Menene bambanci tsakanin Public Key da Private Key?
6. Menene Digital Signature?
7. Ta yaya Hashing yake taimakawa wajen Bitcoin Mining?
8. Menene Merkle Tree?

12. Abubuwan da Dalibi Ya Kamata Ya Koya

Bayan wannan darasi, dalibi ya kamata ya iya:

- Bayyana ma'anar Cryptography da Hashing.
- Fahimtar yadda SHA-256 yake aiki.
- Bambance Encryption da Hashing.
- Fahimtar Public Key da Private Key.
- Bayyana aikin Digital Signature.
- Fahimtar rawar Hashing a Mining da Merkle Tree.

13. Manazarta

1. Bitcoin Developer Documentation: https://developer.bitcoin.org/
2. Bitcoin Whitepaper: https://bitcoin.org/bitcoin.pdf
3. NIST Secure Hash Standard (FIPS 180-4): https://csrc.nist.gov/pubs/fips/180-4/upd1/final
4. Bitcoin Optech: https://bitcoinops.org/

Lura: Wannan darasi na koyarwa ne. Ba shawarar zuba jari ba ne.

Hausa Bitcoin Initiative (HBI)

Our Mission: Making Bitcoin knowledge, technical education and open-source learning resources accessible to Hausa speakers worldwide.
