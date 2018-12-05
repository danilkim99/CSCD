# KIM DANIL (Computer science department)
거지 키울기 (Clicker game)
* Client
  * The most famous and demanding is IOS and Android
  * My choose is Android 
    * Historical review: Android, a system developed by Andy Rubin in 2003 and later acquired by Google in 2005, has seen dramatic improvements since 2007, making it known worldwide. Today, the development of Android system is based on Linux. The initial version of the interface is too simple, and some details are modeled on iOS, such as the function of sliding to unlock. Steve Jobs was also so rampant with Google and repeated lawsuits to destroy it, but eventually failed. After several years of continuous improvements in its operation, interface, details and other aspects, with the addition of the advantages of open source systems, it ultimately defeated Symbian as the dominant mobile phone system
    * Why i choosed this platform for developing our game? 
       * Android is perhaps the most advanced mobile gaming platform, if we talk about the available tools and services. The Android development team, Google, and partners such as Intel, have invested gigantic efforts to ensure the success of the platform by providing special tools, various APIs and services to improve Android projects. Many of these tools are specifically designed to help game developers, for example:
         * Developers: Barrier to market has never been so low. Now everyone can create an application on Android and publish it. Traditionally, applications are written in Java, which is popular as a stand-alone programming language and is the most common object-oriented programming language in computer classes at most universities worldwide.
         * Development Tools: Android development tools are provided free of charge. There are no costly compilers or licensing fees. Eclipse is a well-known development environment, the release of the Android Design Studio is expected soon, standard Android tools provide all the necessary functionality and are constantly being improved. Members of the Open Handset Alliance, for example, Intel, have released a number of tools to simplify development for the x86 software environment, as well as x86-compatible Android devices.
         * Android SDK: The Android SDK is a full-featured set of programming interfaces that Java developers find familiar and easy to use. OpenGLES support allows developers to create rich graphics applications, while the built-in basic Android graphics and animation libraries make it easy for simple games to look attractive.
         * Native development: Need to port a lot of gaming libraries? Developers who want to use their existing gaming libraries in C / C ++ can use the Android NDK instead of global rework for this purpose.
         * Third-party game engines: There are many popular game engines that allow you to quickly create a game on Android without inventing a wheel. Game engines can help with porting, provide a structure that supports common game design patterns, and tools for creating game objects, such as textures and levels.
         * Third-party libraries for game developers: Developers can use third-party libraries to perform standard tasks in games, with some libraries optimized for specific processors. Using them allows you to reduce the time for developing algorithms, as well as get the most optimized code, which is not always possible to do with the compiler.
         * Gaming services: Google (Google Play Game Services) and Amazon (Amazon Game Circle) have developed a set of services that allow developers to focus on the main functionality of the game and "seamlessly" integrate social features.
         * Publication: Developers have a lot of available distribution mechanisms.
   * As you can see, game developers have a huge set of tools. They can focus on the game code and make it better and better, without devoting much of their time to developing other aspects of the game. This setup allows anyone - from an indie developer to a huge studio with Hollywood budgets - to try their luck and succeed.
   * Ideal platform for us - Android
* Server
  * The most famous is Angular. jS, Ruby on Rails, Meteor jS, EXpress jS, Zend, Djnago and etc. 
  * My choose is Corona SDK
    * What is that? 
      * Corona SDK - a framework for creating games and applications developed by Corona Labs Inc. Corona allows you to create mobile 2D applications for various platforms without having to make changes to the code. Declared support for platforms such as Android, iOS, macOS and Windows. Corona SDK uses the Lua language to implement application logic.
        * Main features
          * Ability to develop for Android and iOS platforms
          * Support for the physics engine Box2D
          * The possibility of developing and installing additional plug-ins that extend the functionality of the engine
    * Why i choosed that?
      * Corona is used by professional programmers, mobile application developers, schools, and universities to develop and develop, as well as people who simply want to understand how applications or games are developed. Corona is very simple to train those who are just starting to work with it, but at the same time it is powerful enough for experienced developers to use. Here are the benefits you will get:
        * One software platform that allows you to create powerful games, business applications and utilities.
        * Development takes place in the Lua language, a powerful and easy-to-learn scripting language.
        * Corona is cross-platform, so you can write program code once for mobile devices, desktop computers and set-top boxes.
        * Corona plug-ins give developers access to additional features and services.
        * Testing and debugging occurs on your computer before publishing to real devices.
        * More than 1000 APIs allow you to turn your ideas into stunning and innovative applications.
        * Simulator allows you to see the changes made instantly
        * Ease of setting up the working environment
        * High-quality documentation from the developers of the engine
        * Stability and speed of the engine
        * Quick error correction by developers - for many this is the weakest link          
* Cache
  * The most famous is nginx, varnish, redis, haproxy, squid etc.
  * My choose is 
    * What is that?
      * Varnish is an HTTP accelerator designed for content-heavy dynamic web sites as well as APIs. In contrast to other web accelerators, such as Squid, which began life as a client-side cache, or Apache and nginx, which are primarily origin servers, Varnish was designed as an HTTP accelerator. Varnish is focused exclusively on HTTP, unlike other proxy servers that often support FTP, SMTP and other network protocols.
      * History
        * The project was initiated by the online branch of the Norwegian tabloid newspaper Verdens Gang. The architect and lead developer is Danish independent consultant Poul-Henning Kamp (a well-known FreeBSD core developer), with management, infrastructure and additional development originally provided by the Norwegian Linux consulting company Linpro. The support, management and development of Varnish was later spun off into a separate company, Varnish Software. Varnish is free and open source software, available under a two-clause BSD license. Commercial support is available from Varnish Software, amongst others. Version 1.0 of Varnish was released in 2006, Varnish 2.0 in 2008, Varnish 3.0 in 2011, Varnish 4.0 in 2014, Varnish 5.0 in 2016, and Varnish 6.0 in March 2018
    * Why i choosed that?
      * Speed and performance are the heart of Varnish
      * Savings in server infrastructure
      * Scalability – no matter the number of visitors or requests, Varnish helps your site match the demand
      * Protection against outages—if your server fails, Varnish continues to serve cached content
      * Flexibility – Varnish Configuration Language (VCL) builds customized solutions, rules and modules
      * Improved end-user experience
* Database
  * The most famous is sqlite, ormlite, oracle, real, couchbase etc.
  * Database its:
    * Mobile OS is growing bigger and bigger and recently Android mobile OS surpassed Windows OS as the most used Operating System in the world. As mobile OS is growing larger and hardware  as powerful as any normal computing device, data computation from mobiles is also increasing. Database is the most common way of storing and managing data. For quite some time now,  databases are handled on server-side or cloud and mobile devices only communicate with them through network. However, to make applications more responsive and less dependent on network connectivity, the trend of offline usage or less dependency on network is gaining popularity. Nowadays, applications keep DB locally or make a copy of DB over cloud onto local device and sync with it once in a day or whenever there is a network connectivity. This will help in faster and responsive applications which are functional even when there is no or limited internet connectivity.
      * Databases for mobiles need to be:
        * Lightweight as storage is limited on mobile devices.
        * No server requirement.
        * In a form of library with no or very limited dependency (embeddable) so that it can be used when needed
        * Fast and secure.
        * Easy to handle through code, and option to make it private or shared with other applications.
        * Low memory and power consumption.
 * My choose is RealmDB
    * What is that?
      * Realm is an open-source object database management system, initially for mobile (Android/iOS), also available for platforms such as Xamarin or React Native, and others, including desktop applications (Windows), and is licensed under the Apache License.
In 2016 September, the Realm Mobile Platform was announced, followed by the first stable release in January 2017. It allows two-way synchronization between the Realm Object Server, and the client side databases that belong to the given logged-in user. Both a developer, and a commercial edition was released, along with a business license for integrating with other database management systems such as PostgreSQL.
    * Why i choosed that?
      * Realm is a relational database management system which is like conventional databases, data can be queried and filtered, interconnected, and persisted but also have objects which are live and fully reactive. Realm DB is developed by Realm and specially designed to run on mobile devices. Like SQLite, Realm is also serverless and cross-platform. It can be stored both on disk as well as in memory. Realm has so many advantages over native SQLite, like:
        * Objects in Realm are native Objects, You don’t have to copy objects out of the database, modify them, and save them back—you’re always working with the “live,” real object.
        * Objects always stays in sync.
        * Realm is much faster than SQLite. Realm can query up to 57 records/sec, whereas SQLite can do only up to 20 records/sec.
        * Data can be secured with transparent encryption and decryption.
        * Realm has a reactive architecture, means it can be directly connected to UI, if data changes it will automatically refresh and appear on screen. 
        * It automatically syncs to Realm Object server (if present) when there is network connectivity present.
        * One application can have multiple Realms, both local and remote
        * Can set different permissions for different users.
        * Available for Android, iOS, JavaScript etc.
