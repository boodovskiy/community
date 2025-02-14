# Представяме SubQuery

## Подайте и преобразувайте световните данни за web3.0 бъдеще

![](https://miro.medium.com/max/1400/1*J5u22qNxndcuCrFJ1mfGqg.png)

Мисията на OnFinalyty е да подкрепя разработчиците на блокчейн, като предоставя инфраструктурни услуги на клиенти под всякаква форма и размери. Стартираме ново начинание, което има за цел да реши основен проблем и да развие тази мисия: SubQuery.

Почти всеки блокчейн има нужда от обработка и възможност за запитване на данни. Процъфтяващата общност на Polkadot се нуждае от услуга, която им позволява бързо и надеждно да намират и използват данни. Нашият проект е вдъхновен от [The Graph](https://thegraph.com/), услуга, която в момента е фокусирана върху Ethereum, тя позволява на клиентите да правят това с помощта на GraphQL.

Тъй като децентрализираните системи съхраняват данни в мрежи, запитването е бавно и трудно. За да бъде реализирана Web 3.0 мечтата, тя трябва да бъде толкова бърза за крайния потребител, колкото централизираните мрежи (ако не и по-бърза). В момента екипите на различните протоколите изграждат централизирани сървъри за индексиране за собствените си проекти, но това създава три проблема:

-   Екипите на Polkadot/Substrate не трябва да се притесняват за изграждането или управлението на това, докато изграждат следващия dApp
-   Екипите непрекъснато преоткриват „колелото“; Основното предимство на оперативната съвместимост на Parachain на Polkadot е да се избегне това
-   Според нас екосистемата Substrate/Polkadot е готова да достигне същото ниво на растеж, като Ethereum. Вярваме, че трябва да осигури същото ниво на обществени услуги, като това, което Ethereum вече има

![](https://miro.medium.com/max/1400/1*l4b4BXWkczVDaHyv30lLQQ.png)

Целта на SubQuery е да помогне на проектите на Polkadot/Substrate да изградят по-добри dApps, като позволят на всеки по-бързо и надеждно да намира и консумира данни. Нашата услуга ще позволи на потребителите първоначално да извличат, трансформират, запазват и заявяват данни, както и да свързват и представят данни в бъдеще. Нашата цел е да превърнем това в основна част от инфраструктурата на Substrate/Polkadot екосистемите, точно както The Graph се превърна за Ethereum.

> SubQuery е тук, за да ви помогне да трансформирате и запитвате световните данни, за бъдещето на web3.0.

![](https://miro.medium.com/max/1000/1*IHstJG-hBwQzicLdWkGR5w.png)

За да бъде реализирана мечтата за Web 3.0, тя трябва да бъде толкова бърза (ако не и по-бърза) от централизираните мрежи, за крайния потребител.

Ето защо ние сме невероятно горди да обявим SubQuery, проект с отворен код, който позволява на потребителите да стартират индексатор в тяхната верига, за да изградят набор от данни, който може да бъде изискан чрез GraphQL. Този набор от инструменти включва интерфейс на командния ред, който позволява на проектите да генерират свой собствен SubQuery проект, определяйки как индексаторът трябва да преминава и да агрегира собствената си мрежа. Има SubQuery нод пакет, който индексира мрежата и поддържа GraphQL заявки. С помощта на тези инструменти всеки може лесно да създава и изпълнява заявки.

> _Можете да започнете веднага, като следвате нашия пример в хранилището на:_ [_https://github.com/OnFinality-io/subql_](https://github.com/OnFinality-io/subql)

Освен това можете да научите повече, като прочетете нашите документи за [SubQuery docs](https://doc.subquery.network/) или посетите новия ни уебсайт на адрес [https://subquery.network/](https://subquery.network/)

![](https://miro.medium.com/max/1000/1*3oA1Hvns1vrImTsmowO_Jw.png)

Ще се фокусираме върху изграждането на управлявана хоствана услуга, базирана на това предложение, която ще бъде по-ефективна с възможност за скалиране. Ще предоставим надеждна обществена инфраструктура, която ще изгради мощен производствен SubQuery нод от вече качен SubQuery проект. След това, услугата ще индексира и ще запази състоянието на веригата и ще предостави крайна точка на GraphQL, която може да заменя самостоятелно хоствани реализации. Ще се съсредоточим върху това, за да може всички останали да се съсредоточат върху изграждането и развитието на своето dApp.

След като това е изградено, нашата последна фаза е да токенизираме бизнеса на SubQuery чрез изграждане на собствена верига (вероятно парачейн) за Polkadot. Въпреки че ще предоставим подобен модел на таксуване за корпоративни потребители и на потребители с голямо потребление (абонаментен план с нива на потребление), ние ще запазим тези данни в нашата верига, за да ги направим прозрачни за всички и участващите страни ще могат да стейкват за награди като стимули. Ще издадем токен за управление, за да осигурим стабилност на веригата и да позволим на общността да влияе върху нашата посока на развитие.

Въпреки над 10 годишното развитие от началото на биткойн, централизираните мрежи все още са мейнстрийм. Това до голяма степен се дължи на скоростта и разходите за достъп и писане в мрежата. Ethereum направи огромна крачка напред с децентрализираните умни договори (и в резултат на това Graph е невероятно успешна част от инфраструктурата), но основната мрежа се затруднява да намали транзакционните разходи.

Отрано видяхме потенциала на Polkadot и още от самото начало беше естествено да насочим усилията си там. Той решава проблемите с управлението на Ethereum, форкването, оперативната съвместимост и други. Основната цел на Polkadot е да създаде процъфтяваща общност от разработчици, потребители и бизнеси, които ще се включат в нейната многоверижна оперативна съвместимост - тази общност се нуждае от услуга, която им позволява надеждно и бързо да намират и консумират данни.

Уникалната архитектура на Polkadot означава, че можем да се съсредоточим върху една мрежа и след това да можем да поддържаме множество настоящи и бъдещи вериги с лекота. Като полагаме тези усилия сега, дори когато Polkadot все още е в процес на разработка, ние ще бъдем готови да помогнем на следващото поколение блокчейн разработчици да създаде следващото голямо dApp.

SubQuery ще бъде изграден от екипа на OnFinality, който е инфраструктурна SaaS платформа за блокчейн екипи и потребители, улеснява ги да стартират нодове и да получат достъп до широк спектър от блокчейн протоколи. Имаме набор от услуги, работещи в симбиоза, включително нашата услуга за споделени нодове за API и специални нодове, които могат да се използват при управление на инфраструктурата или като част от CI/CD тестовата линия на екипа, създаващ протоколи. Имаме връзки с най-добрите екипи на Polkadot/Substrate, опит в хостинга на управлявана инфраструктура за мрежата Substrate/Polkadot и способността да доставяме сложни инфраструктурни проекти и да ги хостваме за производствена употреба.

**Sam Zou —** изпълнителен директор ([LinkedIn](https://www.linkedin.com/in/sam-zou-5b8169a/))

Предприемач, инвеститор с повече от 20 години ИТ опит, специализиран в проектиране на инфраструктура и облачни услуги

**Ian He —** ръководител на протокола ([LinkedIn](https://www.linkedin.com/in/yin-he-7a266345/))

Блокчейн архитект, сътрудник в polkadot-js, ранен привърженик на Substrate технологията, печели второто място в първия Polkadot hackathon.

**James Xu —** архитект на решенията ([LinkedIn](https://www.linkedin.com/in/zhexu/))

Архитект на инфраструктура и приложения, носител на награди, като софтуерен инженер.

**James Bayly** — ръководител на отдел бизнес развитие ([LinkedIn](https://www.linkedin.com/in/james-bayly/))

Започнете с [SubQuery Github repository.](https://github.com/OnFinality-io/subql)

Прочетете нашата [SubQuery документация](https://doc.subquery.network/)

[Посетете нашия уебсайт](https://subquery.network/)

Следвай ни в:

-   [Telegram](https://t.me/subquerynetwork)
-   [Twitter](https://twitter.com/subquerynetwork)
-   [Matrix](https://matrix.to/#/%23subquery:matrix.org)
-   [LinkedIn](https://www.linkedin.com/company/subquery)