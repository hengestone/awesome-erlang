# awesome-erlang

# Awesome Erlang
A categorized list of awesome Erlang frameworks, libraries and software.

## [Erlang Core](#erlang-core)
* [erlang/otp](https://github.com/erlang/otp) - Erlang/OTP
* [happi/theBeamBook](https://github.com/happi/theBeamBook) - A description of the Erlang Runtime System ERTS and the virtual Machine BEAM.
* [beamparticle/beamparticle](https://github.com/beamparticle/beamparticle) - Operate at the speed of (Erlang) BEAM with BeamParticle

## [BEAM Languages](#beam-languages)
* [alpaca-lang/alpaca](https://github.com/alpaca-lang/alpaca) - Functional programming inspired by ML for the Erlang VM
* [altenwald/ephp](https://github.com/altenwald/ephp) - PHP Interpreter in pure Erlang
* [clojerl/clojerl](https://github.com/clojerl/clojerl) - Clojure for the Erlang VM
* [joxa/joxa](https://github.com/joxa/joxa) - **DEAD** A Modern Lisp for the Erlang VM
* [lasp-lang/lasp](https://github.com/lasp-lang/lasp) - Prototype implementation of Lasp in Erlang.
* [meatmachine/lol](https://github.com/meatmachine/lol) - Lol — Lisp on erLang, and programming is fun again
* [rvirding/erlog](https://github.com/rvirding/erlog) - Prolog interpreter in and for Erlang
* [rvirding/lfe](https://github.com/rvirding/lfe) - Lisp Flavoured Erlang (LFE)
* [rvirding/luerl](https://github.com/rvirding/luerl) - Lua in Erlang
* [tarcieri/reia](https://github.com/tarcieri/reia) - **DEAD** Ruby-like hybrid OOP/functional programming language for BEAM, the Erlang VM
* [extend/xerl](https://github.com/extend/xerl) - Xerl, an eXtended ERLang language, is a language for the BEAM VM.
* [maximk/teeterl](https://github.com/maximk/teeterl) - A lean portable Erlang, no BEAM
* [etnt/eml](https://github.com/etnt/eml) - **DEAD** Erlang flavored by Some ML
* [joergen7/cuneiform](https://github.com/joergen7/cuneiform) - A functional language for large-scale scientific data analysis.

## [BEAM Implementations](#beam-impl)
* [kvakvs/ErlangRT](https://github.com/kvakvs/ErlangRT) - Erlang Replacement Therapy. Another attempt to make Erlang runtime (BEAM emulator) in Rust. Good news: I know what to do. Bad news: I have no clue how to Rust
* [tonyrog/beam](https://github.com/tonyrog/beam) - BEAM emulator written in Erlang

## [Languge Interop/FFI](#language-interop)
* [hdima/erlport](https://github.com/hdima/erlport) - ErlPort - connect Erlang to other languages
* [lfex/py](https://github.com/lfex/py) - Distributed Python for the Erlang Ecosystem
* [basho/erlang_js](https://github.com/basho/erlang_js) - A linked-in driver for Erlang to Mozilla's Spidermonkey Javascript runtime.
* [johnlinvc/erruby](https://github.com/johnlinvc/erruby) - ruby on erlang
* [beamjs/erlv8](https://github.com/beamjs/erlv8) - Erlang interface for V8
* [strange/erlang-v8](https://github.com/strange/erlang-v8) - Run JavaScript from Erlang in an external OS process.

## [Parse Tools](#parse-tools)
* [seancribbs/neotoma](https://github.com/seancribbs/neotoma) - Erlang library and packrat parser-generator for parsing expression grammars.
* [uwiger/parse_trans](https://github.com/uwiger/parse_trans) - Parse transform utilities for Erlang

## [Web Servers](#web-servers)
* [elli-lib/elli](https://github.com/elli-lib/elli) - Simple, robust and performant Erlang web server
* [gar1t/psycho](https://github.com/gar1t/psycho) - Yes, another Erlang web server!
* [joedevivo/chatterbox](https://github.com/joedevivo/chatterbox) - HTTP/2 Server for Erlang. Boy, that guy was a real chatterbox waddn't he?  I didn't think he was ever going to stop with the story.
* [mashion/chloe](https://github.com/mashion/chloe) - A realtime web server that doesn't suck
* [mochi/mochiweb](https://github.com/mochi/mochiweb) - MochiWeb is an Erlang library for building lightweight HTTP servers.
* [mojombo/yaws](https://github.com/mojombo/yaws) - YAWS is an erlang web server
* [ninenines/cowboy](https://github.com/ninenines/cowboy) - Small, fast, modern HTTP server for Erlang/OTP.
* [ostinelli/bisbino](https://github.com/ostinelli/bisbino) - An Erlang HTTP server with FastCGI as backend.
* [ostinelli/misultin](https://github.com/ostinelli/misultin) - Misultin (pronounced mee-sool-téen) is an Erlang library for building fast lightweight HTTP(S) servers, which also supports websockets.

* ### [Web Server Support Libraries](#web-server-support)
    * [dvv/social](https://github.com/dvv/social) - Cowboy handler for social login via OAuth2 providers
    * [dvv/stable](https://github.com/dvv/stable) - Library of assorted helpers for Cowboy web server.
    * [EchoTeam/oauth](https://github.com/EchoTeam/oauth) - OAuth Erlang client and server
    * [fbeline/rooster](https://github.com/fbeline/rooster) - Erlang REST framework
    * [FelipeBB/rooster](https://github.com/FelipeBB/rooster) - Rest framework that runs on top of mochiweb
    * [kivra/oauth2](https://github.com/kivra/oauth2) - Erlang Oauth2 implementation
    * [martinjlogan/gen_web_server](https://github.com/martinjlogan/gen_web_server) - generic web server behaviour for conveniently building REST based interfaces
    * [ninenines/cowlib](https://github.com/ninenines/cowlib) - Support library for manipulating Web protocols.
    * [shopgun/graphql-erlang](https://github.com/shopgun/graphql-erlang) - GraphQL implementation in Erlang.
    * [sinasamavati/leptus](https://github.com/sinasamavati/leptus) - Erlang REST framework that runs on top of cowboy
    * [sockjs/sockjs-erlang](https://github.com/sockjs/sockjs-erlang) - WebSocket emulation - Erlang server
    * [tim/erlang-oauth](https://github.com/tim/erlang-oauth) - An Erlang OAuth 1.0 implementation
    * [virtan/simple_oauth2](https://github.com/virtan/simple_oauth2) - Simple erlang OAuth2 client module for any http server framework (Google, Facebook, Yandex, Vkontakte are preconfigured)


## [Web Frameworks](#web-framework)
* [ChicagoBoss/ChicagoBoss](https://github.com/ChicagoBoss/ChicagoBoss) - Erlang web MVC, now featuring Comet
* [nitrogen/nitrogen](https://github.com/nitrogen/nitrogen) - Nitrogen Web Framework for Erlang (now with websockets!)
* [tsujigiri/axiom](https://github.com/tsujigiri/axiom) - a micro-framework for web applications in Erlang
* [flashingpumpkin/spooky](https://github.com/flashingpumpkin/spooky) - Minimum viable Erlang web framework
* [devinus/fresh](https://github.com/devinus/fresh) - The freshest Erlang web framework
* [yariv/erlyweb](https://github.com/yariv/erlyweb) - The Erlang twist on web frameworks
* [gar1t/modlib](https://github.com/gar1t/modlib) - Web framework based on Erlang's inets httpd framework
* [borovsky/erlang-on-steroids](https://github.com/borovsky/erlang-on-steroids) - Erlang Web Framework inspired by Ruby on Rails
* [kivra/giallo](https://github.com/kivra/giallo) - Small and flexible web framework on top of Cowboy
* [vorn/ChicagoBoss-on-Heroku](https://github.com/vorn/ChicagoBoss-on-Heroku) - A template/tutorial project for running ChicagoBoss (Erlang MVC web framework) on Heroku (PaaS hosting platform)
* [archaelus/ejango](https://github.com/archaelus/ejango) - A Django-ish web framework for Erlang

## [Content Management](#cms)
* [zotonic/zotonic](https://github.com/zotonic/zotonic) - Zotonic - The Erlang Web Framework & CMS

## [Web Clients](#web-clients)
* [benoitc/hackney](https://github.com/benoitc/hackney) - simple HTTP client in Erlang
* [cmullaparthi/ibrowse](https://github.com/cmullaparthi/ibrowse) - Erlang HTTP client
* [ninenines/gun](https://github.com/ninenines/gun) - HTTP/1.1, HTTP/2 and Websocket client for Erlang/OTP.
* [matteoredaelli/ebot](https://github.com/matteoredaelli/ebot) - Ebot, an Opensource Web Crawler built on top of a nosql database (apache couchdb, riak), AMQP database (rabbitmq), webmachine and mochiweb. Ebot is written in Erlang and it is a very scalable, distribuited and highly configurable web cawler. See wiki pages for more details
* [jeremyong/websocket_client](https://github.com/jeremyong/websocket_client) - Erlang websocket client (ws and wss supported)
* [wooga/etest_http](https://github.com/wooga/etest_http) - etest Assertions around HTTP (client-side)
* [esl/lhttpc](https://github.com/esl/lhttpc) - lhttpc is a lightweight HTTP/1.1 client implemented in Erlang.

## [Web Development Libraries](#web-libs)
* [erlydtl/erlydtl](https://github.com/erlydtl/erlydtl) - Django templates for Erlang
* [KirinDave/fuzed](https://github.com/KirinDave/fuzed) - A new revision of Fuzed, the Erlang-based frontend for web apps. Check out the mailing list at http://groups.google.com/group/fuzed
* [mojombo/mustache.erl](https://github.com/mojombo/mustache.erl) - Mustache template engine for Erlang.

* [vim-zz/nitrogen_elements](https://github.com/vim-zz/nitrogen_elements) - Elements for Nitrogen Web Framework


## [Chat Servers](#chat-servers)
* [processone/ejabberd](https://github.com/processone/ejabberd) - Robust, ubiquitous and massively scalable Jabber / XMPP Instant Messaging platform
* [esl/MongooseIM](https://github.com/esl/MongooseIM) - MongooseIM is a mobile messaging platform with focus on performance and scalability

## [Chat Clients](#chat-clients)
* [processone/exmpp](https://github.com/processone/exmpp) - Erlang XMPP library

## [Pub/Sub](#pubsub)
* [emqtt/emqttd](https://github.com/emqtt/emqttd) - EMQ - Erlang MQTT Broker
* [erlio/vernemq](https://github.com/erlio/vernemq) - A distributed MQTT message broker based on Erlang/OTP
* [klarna/brod](https://github.com/klarna/brod) - Apache Kafka client library for Erlang/Elixir
* [cabol/erlbus](https://github.com/cabol/erlbus) - Simple, Distributed and Scalable PubSub Message Bus written in Erlang
* [rabbitmq/rabbitmq-erlang-client](https://github.com/rabbitmq/rabbitmq-erlang-client) - Erlang client for RabbitMQ
* [iij/lmq](https://github.com/iij/lmq) - Lightweight Message Queue
* [jimenezrick/mumq](https://github.com/jimenezrick/mumq) - μMQ: very simple, small and fast STOMP message broker with in-memory persistence written in Erlang

## [Chat Bots](#chat-bots)
* [OtpChatBot/Ybot](https://github.com/OtpChatBot/Ybot) - Ybot - is a helpful chat robot written with Erlang which supports different messaging protocols. [@0xAX]

## [Mail Servers](#mail-servers)
* [Vagabond/gen_smtp](https://github.com/Vagabond/gen_smtp) - A generic Erlang SMTP server and client that can be extended via callback modules

## [Benchmarking](#benchmark)
* [processone/tsung](https://github.com/processone/tsung) - Tsung is a high-performance benchmark framework for various protocols including HTTP, XMPP, LDAP, etc.
* [massemanet/eper](https://github.com/massemanet/eper) - Erlang performance and debugging tools
* [basho/basho_bench](https://github.com/basho/basho_bench) - A load-generation and testing tool for basically whatever you can write a returning Erlang function for.
* [virtan/eep](https://github.com/virtan/eep) - Erlang Easy Profiling (eep) application provides a way to analyze application performance and call hierarchy
* [ransomr/httpcbench](https://github.com/ransomr/httpcbench) - Erlang HTTP client benchmarks

## [Data Storage](#data-storage)
* [leo-project/leofs](https://github.com/leo-project/leofs) - The LeoFS Storage System
* [krestenkrab/hanoidb](https://github.com/krestenkrab/hanoidb) - Erlang LSM BTree Storage

## [Data structures](#data-structures)
* [basho/riak_dt](https://github.com/basho/riak_dt) - Convergent replicated datatypes in Erlang
* [mochi/statebox](https://github.com/mochi/statebox) - Erlang state "monad" with merge/conflict-resolution capabilities. Useful for Riak.
* [cabol/shards](https://github.com/cabol/shards) - Transparent and out-of-box Sharding support for Erlang/Elixir ETS tables!


## [Process Management/Workers](#process-worker)
* [devinus/poolboy](https://github.com/devinus/poolboy) - A hunky Erlang worker pool factory
* [uwiger/gproc](https://github.com/uwiger/gproc) - Extended process registry for Erlang
* [inaka/worker_pool](https://github.com/inaka/worker_pool) - Erlang worker pool

## [Build Tools](#build-tools)
* [erlang/rebar3](https://github.com/erlang/rebar3) - Erlang build tool that makes it easy to compile and test Erlang applications and releases.

* [rebar/rebar](https://github.com/rebar/rebar) - **Deprecated** Erlang build tool that makes it easy to compile and test Erlang applications, port drivers and releases. We encourage you to move to https://github.com/erlang/rebar3.

## [Logging](#logging)
* [erlang-lager/lager](https://github.com/erlang-lager/lager) - A logging framework for Erlang/OTP
* [ahmednawras/log4erl](https://github.com/ahmednawras/log4erl) - A logger for erlang in the spirit of Log4J.

## [Devops](#devops)
* [ferd/recon](https://github.com/ferd/recon) - Collection of functions and scripts to debug Erlang in production.
* [boundary/folsom](https://github.com/boundary/folsom) - Expose Erlang Events and Metrics
* [erlware/relx](https://github.com/erlware/relx) - Sane, simple release creation for Erlang
* [mazenharake/entop](https://github.com/mazenharake/entop) - A top-like tool for monitoring an Erlang node


## [Development Tools](#dev-tools)
* [rustyio/sync](https://github.com/rustyio/sync) - On-the-fly recompiling and reloading in Erlang. Code without friction.

* [zhongwencool/observer_cli](https://github.com/zhongwencool/observer_cli) - Visualize Erlang/Elixir Nodes On The Command Line
* [ferd/erlang-history](https://github.com/ferd/erlang-history) - Hacks to add shell history to Erlang's shell
* [erlanglab/erlangpl](https://github.com/erlanglab/erlangpl) - Tool for developers working with systems running on the Erlang VM (BEAM). It helps with performance analysis.
* [Feuerlabs/exometer](https://github.com/Feuerlabs/exometer) - Basic measurement objects and probe behavior
* [beamspirit/bigwig](https://github.com/beamspirit/bigwig) - like erlang's webtool, but trendy and new
* [krestenkrab/erlubi](https://github.com/krestenkrab/erlubi) - Ubigraph Erlang Client (and Process Visualizer)
* [ferd/vmstats](https://github.com/ferd/vmstats) - tiny Erlang app to generate information on the Erlang VM
* ### [Testing](#testing)
  * [parapluu/Concuerror](https://github.com/parapluu/Concuerror) - Concuerror is a stateless model checking tool for Erlang programs.
  * [proper-testing/proper](https://github.com/proper-testing/proper) - PropEr: a QuickCheck-inspired property-based testing tool for Erlang
  * [eproxus/meck](https://github.com/eproxus/meck) - A mocking library for Erlang
  * [moonpolysoft/effigy](https://github.com/moonpolysoft/effigy) - Effigy is a mocking library for erlang testing.  it makes it easy to mock out whole modules, stub functions, and verify behavior.
  * [komone/utest](https://github.com/komone/utest) - Simple unit testing for Erlang using text files
  * [abhay/eunit](https://github.com/abhay/eunit) - Git tracking branch of EUnit,


* ### [Editor Support](#editor-support)
    * [inaka/elvis](https://github.com/inaka/elvis) - Erlang Style Reviewer

## [Protocols/Data Formats](#protocols)
  * ### [JSON](#json)
    * [talentdeficit/jsx](https://github.com/talentdeficit/jsx) - an erlang application for consuming, producing and manipulating json. inspired by yajl
    * [seth/ej](https://github.com/seth/ej) - Helper module for working with Erlang terms representing JSON
    * [sile/jsone](https://github.com/sile/jsone) - Erlang JSON library
    * [jcomellas/kvlists](https://github.com/jcomellas/kvlists) - Lists of key-value pairs (decoded JSON) in Erlang
    * [lordnull/rec2json](https://github.com/lordnull/rec2json) - Compile erlang  record definitions into modules to convert them to/from json easily.
  * ### [YAML](#yaml)
    * [yakaz/yamerl](https://github.com/yakaz/yamerl) - YAML 1.2 and JSON parser in pure Erlang
    * [processone/fast_yaml](https://github.com/processone/fast_yaml) - Fast YAML native library for Erlang / Elixir
  * ### [MessagePack](#msgpack)
    * [msgpack/msgpack-erlang](https://github.com/msgpack/msgpack-erlang) -   MessagePack (de)serializer implementation for Erlang / msgpack.org[Erlang]
  * ### [Protocol Buffers](#protobuf)
    * [tomas-abrahamsson/gpb](https://github.com/tomas-abrahamsson/gpb) - A   Google Protobuf implementation for Erlang
    * [basho/erlang_protobuffs](https://github.com/basho/erlang_protobuffs) - An implementation of Google's Protocol Buffers for Erlang, based on ngerakines/erlang_protobuffs.
    * [ngerakines/erlang_protobuffs](https://github.com/ngerakines/erlang_protobuffs) - A set of Protocol Buffers tools and modules for Erlang applications.
  * ### [XML](#xml)
    * [willemdj/erlsom](https://github.com/willemdj/erlsom) - XML parser for Erlang
    * [bet365/soap](https://github.com/bet365/soap) - Make it easy to use SOAP from Erlang

## [Database Clients/Drivers](#db-client)
* [epgsql/epgsql](https://github.com/epgsql/epgsql) - Erlang PostgreSQL client library.
* [wooga/eredis](https://github.com/wooga/eredis) - Erlang Redis client
* [basho/riak-erlang-client](https://github.com/basho/riak-erlang-client) - The Riak client for Erlang.
* [comtihon/mongodb-erlang](https://github.com/comtihon/mongodb-erlang) - MongoDB driver for Erlang
* [mysql-otp/mysql-otp](https://github.com/mysql-otp/mysql-otp) - MySQL/OTP – MySQL driver for Erlang/OTP
* [benoitc/couchbeam](https://github.com/benoitc/couchbeam) - Apache CouchDB client in Erlang
* [matehat/cqerl](https://github.com/matehat/cqerl) - Native Erlang CQL client for Cassandra
* [dizzyd/erlang-mysql-driver](https://github.com/dizzyd/erlang-mysql-driver) - Erlang MySQL Driver (from code.google.com)
* [hiroeorz/eredis_pool](https://github.com/hiroeorz/eredis_pool) - eredis_pool is Pool of Redis clients, using eredis and poolboy.
* [VoltDB/voltdb-client-erlang](https://github.com/VoltDB/voltdb-client-erlang) - VoltDB Erlang Client Driver
* [basho/riak-erlang-http-client](https://github.com/basho/riak-erlang-http-client) - Riak Erlang client using the HTTP interface
* [epgsql/pgapp](https://github.com/epgsql/pgapp) - Erlang Postgres application that uses Poolboy and deals with the database being unavailable
* [ztmr/egtm](https://github.com/ztmr/egtm) - IDEA EGTM: Erlang binding for GT.M database engine
* [basho/riak_api](https://github.com/basho/riak_api) - Riak Client APIs
* [erlangbureau/jamdb_oracle](https://github.com/erlangbureau/jamdb_oracle) - Oracle Database driver for Erlang
* [RJ/erlang-cassandra-cql](https://github.com/RJ/erlang-cassandra-cql) - cassandra driver in erlang that speaks native cassandra protocol
* [saa/fluxer](https://github.com/saa/fluxer) - Erlang InfluxDB client
* [rpt/erlcql](https://github.com/rpt/erlcql) - Cassandra native protocol CQL client for Erlang
* [noss/pgsql](https://github.com/noss/pgsql) - Erlang postgresql driver
* [josephwecker/epgsql_pool](https://github.com/josephwecker/epgsql_pool) - Fork of Will Glozer's erlang postgresql pool server, so it can be maintained and polished.
* [erlware/dikdik](https://github.com/erlware/dikdik) - An Erlang and json interface for PostgreSQL hstore.
* [semiocast/pgsql](https://github.com/semiocast/pgsql) - Erlang PostgreSQL driver
* [jkvor/emysql](https://github.com/jkvor/emysql) - Erlang MySQL driver
* [ngerakines/erlang_mysql](https://github.com/ngerakines/erlang_mysql) - A GitHub mirror of the native Erlang MySQL client library.
* [processone/mysql](https://github.com/processone/mysql) - Erlang MySQL driver
* [SergejJurecko/erlmongo](https://github.com/SergejJurecko/erlmongo) - Erlang driver for MongoDB with gridfs that works with maps and proplists
* [eliast/mongo-erlang-driver](https://github.com/eliast/mongo-erlang-driver) - erlang driver for mongodb
* [jkvor/emongo](https://github.com/jkvor/emongo) - the most Emo of mongo drivers
* [ngerakines/erlang_couchdb](https://github.com/ngerakines/erlang_couchdb) - This is another erlang CouchDB client. It is a little simpler than most and does what I want.


## [Database Servers](#db-servert)
* [cbd/edis](https://github.com/cbd/edis) - An Erlang implementation of Redis
* [moonpolysoft/dynomite](https://github.com/moonpolysoft/dynomite) - Open source dynamo clone written in Erlang.
* [hibari/hibari](https://github.com/hibari/hibari) - Hibari is a production-ready, distributed, ordered key-value, big data store. Hibari uses chain replication for strong consistency, high-availability, and durability. Hibari has excellent performance especially for read and large value operations.
* [spawnproc/ldap](https://github.com/spawnproc/ldap) - LDAP server written in Erlang
* [apache/couchdb-couch](https://github.com/apache/couchdb-couch) - Mirror of Apache CouchDB
* [altenwald/myproto](https://github.com/altenwald/myproto) - MySQL Server Protocol in Erlang
* [flussonic/sqlapi](https://github.com/flussonic/sqlapi) - SQL API implementation of an erlang program: mimic a MySQL server
* [biokoda/actordb](https://github.com/biokoda/actordb) - ActorDB distributed SQL database
* [cloudant/mango](https://github.com/cloudant/mango) - MongoDB API layer for CouchDB
* [pavlobaron/riak_mongo](https://github.com/pavlobaron/riak_mongo) - riak_mongo is a collection of things necessary to make Riak act like MongoDB to the clients
* [jchris/hovercraft](https://github.com/jchris/hovercraft) - An easy direct Erlang CouchDB library.

## [Database ORM](#db-orm)
* [ErlyORM/boss_db](https://github.com/ErlyORM/boss_db) - BossDB: a sharded, caching, pooling, evented ORM for Erlang
* [chef/sqerl](https://github.com/chef/sqerl) - General purpose RDBMS abstraction layer
* [mmzeeman/esql](https://github.com/mmzeeman/esql) - ESQL provides an abstraction layer between Erlang programs and SQL relational databases. This lets you write database code once, in Erlang, and have it work with any number of backend SQL databases  (Sqlite, MySQL, Oracle, PostgreSQL, ODBC-compliant databases, etc.)
* [ErlyORM/aleppo](https://github.com/ErlyORM/aleppo) - Alternative Erlang Pre-Processor

## [Cloud APIs](#cloud-api)
* [erlcloud/erlcloud](https://github.com/erlcloud/erlcloud) - AWS APIs library for Erlang (Amazon EC2, S3, SQS, DDB,  ELB and etc)

## [CryptoCurrency/BlockChain](#blockchain)
* [aeternity/epoch](https://github.com/aeternity/epoch) - æternity testnet: solving scalability problems by making sense of state-channels
* [p2k/ecoinpool](https://github.com/p2k/ecoinpool) - A pool mining software written in Erlang for cryptographic currencies

## [Crypto Libraries](#crypto)
* [potatosalad/erlang-jose](https://github.com/potatosalad/erlang-jose) - JSON Object Signing and Encryption (JOSE) for Erlang and Elixir
* [jlouis/enacl](https://github.com/jlouis/enacl) - Erlang bindings for NaCl / libsodium
* [gbour/letsencrypt-erlang](https://github.com/gbour/letsencrypt-erlang) - Let's Encrypt client library for Erlang
* [andelf/erlang-proxy](https://github.com/andelf/erlang-proxy) - socks4, socks4a, socks5 proxy, encrypted, derived from yueyoum/make-proxy. Across the Great Wall we can reach every corner in the world.

## [Misc Servers/Distributed Systems](#misc-servers)
* [boundary/flake](https://github.com/boundary/flake) - A decentralized, k-ordered id generation service in Erlang
* [mojombo/ernie](https://github.com/mojombo/ernie) - Ernie is an Erlang/Ruby BERT-RPC Server.
* [xslogic/phoebus](https://github.com/xslogic/phoebus) - Phoebus is a distributed framework for large scale graph processing written in Erlang.
* [gotthardp/lorawan-server](https://github.com/gotthardp/lorawan-server) - Compact server for private LoRaWAN networks
* [yrashk/socket.io-erlang](https://github.com/yrashk/socket.io-erlang) - Socket.IO server for Erlang
* [inaka/apns4erl](https://github.com/inaka/apns4erl) - Apple Push Notification Server for Erlang
* [NetComposer/nksip](https://github.com/NetComposer/nksip) - Erlang SIP application server
* [yueyoum/make-proxy](https://github.com/yueyoum/make-proxy) - HTTP/HTTPS/Socks4/Socks5 proxy written in Erlang
* [dnsimple/erldns](https://github.com/dnsimple/erldns) - DNS server, in erlang.

* ### [Actor Libraries](#actor-libs)
  * [jlouis/fuse](https://github.com/jlouis/fuse) - A Circuit Breaker for Erlang
  * [ostinelli/syn](https://github.com/ostinelli/syn) - A global Process Registry and Process Group manager for Erlang.
  * [andrewjstone/rafter](https://github.com/andrewjstone/rafter) - An Erlang library application which implements the Raft consensus protocol
  * [duomark/epocxy](https://github.com/duomark/epocxy) - Erlang Patterns of Concurrency
  * [ferd/pobox](https://github.com/ferd/pobox) - External buffer processes to protect against mailbox overflow in Erlang
  * [jlouis/safetyvalve](https://github.com/jlouis/safetyvalve) - A safety valve for your erlang node
  * [ferd/dispcount](https://github.com/ferd/dispcount) - Erlang task dispatcher based on ETS counters.
  * [basho/riak_ensemble](https://github.com/basho/riak_ensemble) - Multi-Paxos framework in Erlang

* ### [RPC](#rpc)
  * [palkan/erlgrpc](https://github.com/palkan/erlgrpc) - GRPC client for Erlang



## [Development Documents/Tutorials](#dev-docs)
* [inaka/erlang_guidelines](https://github.com/inaka/erlang_guidelines) - Inaka's Erlang Coding Guidelines
* [erlware/Erlang-and-OTP-in-Action-Source](https://github.com/erlware/Erlang-and-OTP-in-Action-Source) - The official "Erlang and OTP in Action" source code - see the README below for more details

## [Testing](#tesing)
* [zkessin/testing-erlang-book](https://github.com/zkessin/testing-erlang-book) - A public book on testing Erlang
* [aggelgian/cuter](https://github.com/aggelgian/cuter) - A concolic testing tool for the Erlang functional programming language.
* [manopapad/proper](https://github.com/manopapad/proper) - PropEr: a QuickCheck-inspired property-based testing tool for Erlang
* [moonpolysoft/effigy](https://github.com/moonpolysoft/effigy) - Effigy is a mocking library for erlang testing.  it makes it easy to mock out whole modules, stub functions, and verify behavior.
* [ngerakines/etap](https://github.com/ngerakines/etap) - etap is a simple erlang testing library that provides TAP compliant output.

## [P2P/Redecentralize](#p2p)
* [jlouis/etorrent](https://github.com/jlouis/etorrent) - Erlang Bittorrent Client
* [lasp-lang/partisan](https://github.com/lasp-lang/partisan) - Scalable peer service for Erlang.
* [SyncFree/antidote](https://github.com/SyncFree/antidote) - SyncFree Reference Platform

## [Security](#net-sec)
* [ernw/ss7MAPer](https://github.com/ernw/ss7MAPer) - SS7 MAP (pen-)testing toolkit
* [lostcolony/damocles](https://github.com/lostcolony/damocles) - An Erlang library for generating adversarial network conditions for QAing distributed applications/systems on a single Linux box.

## [Command line](#cmdline)
* [jcomellas/getopt](https://github.com/jcomellas/getopt) - Erlang module to parse command line arguments using the GNU getopt syntax
* [karlll/kjell](https://github.com/karlll/kjell) - Erlang Shell
* [basho/clique](https://github.com/basho/clique) - CLI Framework for Erlang

## [Date/Time libraries](#date-time)
* [choptastic/qdate](https://github.com/choptastic/qdate) - Erlang date, time, and timezone management: formatting, conversion, and date arithmetic
* [erlware/erlcron](https://github.com/erlware/erlcron) - Erlang cronish system
* [seansawyer/erlang_iso8601](https://github.com/seansawyer/erlang_iso8601) - Erlang ISO 8601 date formatter/parser
* [daleharvey/dh_date](https://github.com/daleharvey/dh_date) - Date formatting / parsing library for erlang
* [erlsci/iso8601](https://github.com/erlsci/iso8601) - An ISO 8601 date formating and parsing library for Erlang

## [Networking](#networking)
* [FlowForwarding/LINC-Switch](https://github.com/FlowForwarding/LINC-Switch) - OpenFlow Software Switch written in Erlang

## [Misc Libraries](#misc-libraries)
* [joearms/elib1](https://github.com/joearms/elib1) - An Erlang library and collection of applications
* [patrickgombert/erlang-koans](https://github.com/patrickgombert/erlang-koans) - Erlang Koans
* [erlware/erlware_commons](https://github.com/erlware/erlware_commons) - Erlware Commons is an Erlware project focused on all aspects of reusable Erlang components.






* [priestjim/gen_rpc](https://github.com/priestjim/gen_rpc) - A scalable RPC library for Erlang-VM based languages

* [fredrikt/yxa](https://github.com/fredrikt/yxa) - SIP software written in Erlang

* [parapluu/Concuerror](https://github.com/parapluu/Concuerror) - Concuerror is a stateless model checking tool for Erlang programs.
* [afiniate/seresye](https://github.com/afiniate/seresye) - SERESYE means Swarm oriented ERlang Expert SYstem Engine. It is a library to write expert systems and rule processing engines using the Erlang programming language. It allows to create multiple engines, each one with its own facts and rules to be processed.
* [SpaceTime-IoT/erleans](https://github.com/SpaceTime-IoT/erleans) - Erlang Orleans
* [inaka/sumo_db](https://github.com/inaka/sumo_db) - Erlang Persistency Framework
* [ParaPhrase/skel](https://github.com/ParaPhrase/skel) - A Streaming Process-based Skeleton Library for Erlang
* [oreillymedia/etudes-for-erlang](https://github.com/oreillymedia/etudes-for-erlang) - Companion exercises for O'Reilly Media's "Introducing Erlang"
* [okeuday/uuid](https://github.com/okeuday/uuid) - Erlang Native UUID Generation


* [vascokk/rivus_cep](https://github.com/vascokk/rivus_cep) - Complex event processing in Erlang

* [joearms/erl2](https://github.com/joearms/erl2) - a new dialect of erlang
* [robbielynch/ierlang](https://github.com/robbielynch/ierlang) - An Erlang language kernel for IPython.
* [deadtrickster/prometheus.erl](https://github.com/deadtrickster/prometheus.erl) - Prometheus.io client in Erlang

* [GameAnalytics/gascheduler](https://github.com/GameAnalytics/gascheduler) - Erlang Distributed Scheduler
* [synrc/mad](https://github.com/synrc/mad) - ⚡ MAD: Erlang Containers
* [mazenharake/cecho](https://github.com/mazenharake/cecho) - An ncurses library for Erlang
* [erlyvideo/rack](https://github.com/erlyvideo/rack) - Rack handler for erlang
* [helpshift/ekaf](https://github.com/helpshift/ekaf) - A minimal, high-performance Kafka client in Erlang.
* [Random-Liu/Erlang-In-Docker](https://github.com/Random-Liu/Erlang-In-Docker) - Enable connection between Erlang VMs from different docker containers on different hosts by reimplementing the distributed connection protocol used by net_kernel.
* [Feuerlabs/exometer_core](https://github.com/Feuerlabs/exometer_core) - Core components of exometer
* [tsloughter/erlastic_search](https://github.com/tsloughter/erlastic_search) - An Erlang app for communicating with Elastic Search's rest interface.
* [huiqing/percept2](https://github.com/huiqing/percept2) - Concurrent profiling tool for Erlang


* [jtendo/binpp](https://github.com/jtendo/binpp) -  :1234: Erlang Binary Pretty Printer

* [erlang-unicode/ux](https://github.com/erlang-unicode/ux) - Unicode eXtention for Erlang (Strings, Collation)
* [basho/clique](https://github.com/basho/clique) - CLI Framework for Erlang
* [inaka/shotgun](https://github.com/inaka/shotgun) - For the times you need more than just a gun.
* [ngerakines/erlang_twitter](https://github.com/ngerakines/erlang_twitter) - An Erlang twitter client

* [vinoski/erlsha2](https://github.com/vinoski/erlsha2) - SHA-224, SHA-256, SHA-384, SHA-512 implemented in Erlang NIFs.
* [rabbitmq/ra](https://github.com/rabbitmq/ra) - A Raft implementation for Erlang and Elixir that strives to be efficient and make it easier to use multiple Raft clusters in a single system.
* [emqtt/emqttc](https://github.com/emqtt/emqttc) - Asynchronous Erlang MQTT Client
* [kudelskisecurity/scannerl](https://github.com/kudelskisecurity/scannerl) - The modular distributed fingerprinting engine
* [knutin/statman](https://github.com/knutin/statman) - Efficiently collect massive volumes of metrics inside the Erlang VM

* [selectel/yawndb](https://github.com/selectel/yawndb) - YAWNDB is an in-memory circular array database written in Erlang.
* [tonyg/erlang-rfc4627](https://github.com/tonyg/erlang-rfc4627) - Erlang RFC4627 (JSON) codec and JSON-RPC server implementation.
* [jlouis/dht](https://github.com/jlouis/dht) - DHT implementation in Erlang
* [bragful/ephp](https://github.com/bragful/ephp) - Bragful core: PHP Interpreter in pure Erlang
* [processone/stun](https://github.com/processone/stun) - STUN and TURN library for Erlang / Elixir
* [msantos/pkt](https://github.com/msantos/pkt) - Erlang network protocol library
* [hypernumbers/LuvvieScript](https://github.com/hypernumbers/LuvvieScript) - Luvvie Script. An Erlang dialect that compiles to Javascript for Actor-style DOM scripting
* [gar1t/e2](https://github.com/gar1t/e2) - Project that aims to simplify Erlang/OTP development and improve developer productivity
* [emqtt/emqtt_benchmark](https://github.com/emqtt/emqtt_benchmark) - Erlang MQTT Benchmark
* [parapluu/nifty](https://github.com/parapluu/nifty) - Erlang NIF Wrapper Generator
* [groupoid/om](https://github.com/groupoid/om) - Consistent PTS Assembler
* [archaelus/enet](https://github.com/archaelus/enet) - Pure Erlang network stack
* [lpgauth/shackle](https://github.com/lpgauth/shackle) - High-Performance Erlang Network Client Framework
* [joewilliams/merle](https://github.com/joewilliams/merle) - An Erlang Memcached Client.
* [kapok-lang/kapok](https://github.com/kapok-lang/kapok) - A Lisp on the Erlang VM
* [francescoc/scalabilitywitherlangotp](https://github.com/francescoc/scalabilitywitherlangotp) - The repository for the code of the examples in the book Designing for Scalability with Erlang/OTP
* [RJ/erlang-spdy](https://github.com/RJ/erlang-spdy) - Library implementing the SPDY protocol
* [yzh44yzh/practical_erlang](https://github.com/yzh44yzh/practical_erlang) - Курс обучения Эрланг
* [klarna/ponos](https://github.com/klarna/ponos) - ponos is a simple yet powerful load generator written in erlang
* [zeromq/chumak](https://github.com/zeromq/chumak) - Pure Erlang implementation of ZeroMQ Message Transport Protocol.
* [essen/egs](https://github.com/essen/egs) - Erlang Game Server
* [basho/enm](https://github.com/basho/enm) - Erlang driver for nanomsg
* [scalaris-team/scalaris](https://github.com/scalaris-team/scalaris) - Scalaris, a distributed, transactional key-value store
* [okeuday/pqueue](https://github.com/okeuday/pqueue) - Erlang Priority Queues
* [gar1t/lambdapad](https://github.com/gar1t/lambdapad) - Static site generator using Erlang. Yes, Erlang.
* [etrepum/kvc](https://github.com/etrepum/kvc) - KVC - Key Value Coding for Erlang data structures
* [mojombo/egitd](https://github.com/mojombo/egitd) - The Erlang git-daemon
* [esl/escalus](https://github.com/esl/escalus) - An XMPP client library in Erlang for conveniently testing XMPP servers
* [okeuday/trie](https://github.com/okeuday/trie) - Erlang Trie Implementation
* [fogfish/cache](https://github.com/fogfish/cache) - Erlang in-memory cache
* [rvirding/leex](https://github.com/rvirding/leex) - Lexical analyzer generator for Erlang
* [NetComposer/nkcluster](https://github.com/NetComposer/nkcluster) - A framework to manage jobs at huge Erlang clusters
* [emqtt/esockd](https://github.com/emqtt/esockd) - Erlang General Non-blocking TCP/SSL Socket Server
* [membase/cucumberl](https://github.com/membase/cucumberl) - pure erlang implementation of Cucumber parser & driver
* [avtobiff/erlang-uuid](https://github.com/avtobiff/erlang-uuid) - Erlang UUID
* [lasp-lang/types](https://github.com/lasp-lang/types) - Prototype implementation of Conflict-free Replicated Data Types (CRDTs) in Erlang.
* [mochi/egeoip](https://github.com/mochi/egeoip) - Erlang IP Geolocation module, currently supporting the MaxMind GeoLite City Database.
* [gebi/jungerl](https://github.com/gebi/jungerl) - The Jungle of Erlang code
* [aggelgian/erlang-algorithms](https://github.com/aggelgian/erlang-algorithms) - Implementations of popular data structures and algorithms
* [nitrogen/simple_bridge](https://github.com/nitrogen/simple_bridge) - A simple, standardized interface library to Erlang HTTP Servers.
* [jbrisbin/amqp_client](https://github.com/jbrisbin/amqp_client) - Rebar-friendly fork of rabbitmq-erlang-client
* [ferd/backoff](https://github.com/ferd/backoff) - Simple exponential backoffs in Erlang
* [chef-boneyard/erchef](https://github.com/chef-boneyard/erchef) - DEPRECATED: Erlang based Chef Server top-level OTP release project
* [RJ/estatsd](https://github.com/RJ/estatsd) - Erlang stats aggregation app that periodically flushes data to graphite
* [erlware-deprecated/sinan](https://github.com/erlware-deprecated/sinan) - Erlang/OTP oriented build system
* [CorticalComputer/Book_NeuroevolutionThroughErlang](https://github.com/CorticalComputer/Book_NeuroevolutionThroughErlang) - The resulting source code produced at the end of each chapter in Handbook of Neuroevolution Through Erlang.

* [duomark/erlangsp](https://github.com/duomark/erlangsp) - Erlang Services Platform
* [5HT/pie](https://github.com/5HT/pie) - The Erlang-Scriptable Editor


* [martinsumner/leveled](https://github.com/martinsumner/leveled) - Working prototype of a pure Erlang Key/Value store - based on a LSM-tree, optimised for HEAD requests

* [jordillonch/eggs](https://github.com/jordillonch/eggs) - Erlang Generic Game Server
* [schlagert/bootstrap](https://github.com/schlagert/bootstrap) - A simple, yet powerful Erlang cluster bootstrapping application.
* [pdincau/gcm-erlang](https://github.com/pdincau/gcm-erlang) - An Erlang application for Google Cloud Messaging
* [davebryson/erlang_websocket](https://github.com/davebryson/erlang_websocket) - WebSocket Server and Client implementation in Erlang/Mochiweb
* [benoitc-attic/barrel_tcp](https://github.com/benoitc-attic/barrel_tcp) - barrel_tcp  is a generic TCP acceptor pool with low latency in Erlang.
* [yuce/pot](https://github.com/yuce/pot) - POT is an Erlang library for generating Google Authenticator compatible one time passwords
* [videlalvaro/gen_microservice](https://github.com/videlalvaro/gen_microservice) - Microservices for Erlang
* [soranoba/bbmustache](https://github.com/soranoba/bbmustache) - Binary pattern match Based Mustache template engine for Erlang/OTP.

* [erlware/resource_discovery](https://github.com/erlware/resource_discovery) - An application used to dynamically discover resources present in an Erlang node cluster.
* [benoitc/cowboy_revproxy](https://github.com/benoitc/cowboy_revproxy) - simple TCP routing proxy (layer 7) in erlang
* [basho/sidejob](https://github.com/basho/sidejob) - Parallel worker and capacity limiting library for Erlang
* [mojombo/bert.erl](https://github.com/mojombo/bert.erl) - Erlang BERT encoder/decoder
* [maxlapshin/stockdb](https://github.com/maxlapshin/stockdb) - Database for storing Stock Exchange quotes in erlang
* [lpgauth/statsderl](https://github.com/lpgauth/statsderl) - High-Performance Erlang StatsD Client
* [gdamjan/erlang-irc-bot](https://github.com/gdamjan/erlang-irc-bot) - A simple extendable irc bot in Erlang
* [erszcz/docsh](https://github.com/erszcz/docsh) - Erlang Docs in the Shell
* [kevinlynx/dhtcrawler](https://github.com/kevinlynx/dhtcrawler) - dhtcrawler is a DHT crawler written in erlang. It can join a DHT network and crawl many P2P torrents.
* [ferd/fancyflow](https://github.com/ferd/fancyflow) - Experimental library to bring pipe and maybe operator equivalents in Erlang
* [Vagabond/erlang-syslog](https://github.com/Vagabond/erlang-syslog) - Erlang port driver for interacting with syslog via syslog(3)
* [msantos/evum](https://github.com/msantos/evum) - ["Linux VM", ["Erlang Process", ["Erlang VM"]]].
* [msantos/gen_icmp](https://github.com/msantos/gen_icmp) - Erlang interface to ICMP sockets
* [lambder/jsonerl](https://github.com/lambder/jsonerl) - yet another but slightly different erlang <-> json encoder/decoder
* [aliter/aliter](https://github.com/aliter/aliter) - Ragnarok Online server software written in Erlang.
* [uwiger/plain_fsm](https://github.com/uwiger/plain_fsm) - A behaviour/support library for writing plain Erlang FSMs.
* [tolbrino/hotwheels](https://github.com/tolbrino/hotwheels) - Erlang messaging server optimized to send 1 message to 40k subscribers to a topic in < 1s
* [tatsuhiro-t/lucid](https://github.com/tatsuhiro-t/lucid) - HTTP/2 server written in Erlang
* [rabbitmq/looking_glass](https://github.com/rabbitmq/looking_glass) - An Erlang/Elixir/BEAM profiler tool
* [okeuday/cpg](https://github.com/okeuday/cpg) - CloudI Process Groups
* [hyperthunk/hamcrest-erlang](https://github.com/hyperthunk/hamcrest-erlang) - Erlang port of Hamcrest
* [vascokk/NumEr](https://github.com/vascokk/NumEr) - Numeric Erlang - vector and matrix operations with CUDA. Heavily inspired by Pteracuda - https://github.com/kevsmith/pteracuda
* [shortishly/erlang-in-docker-from-scratch](https://github.com/shortishly/erlang-in-docker-from-scratch) - An Erlang application release in a Docker container from scratch
* [richcarl/merl](https://github.com/richcarl/merl) - Metaprogramming in Erlang
* [proger/erldocker](https://github.com/proger/erldocker) - Docker Remote API client for Erlang
* [engineyard/natter](https://github.com/engineyard/natter) - Erlang XMPP Client
* [EchoTeam/mcd](https://github.com/EchoTeam/mcd) - Fast memcached protocol client in pure Erlang
* [artemeff/eql](https://github.com/artemeff/eql) - Erlang with SQL or not
* [alavrik/erlson](https://github.com/alavrik/erlson) - Erlang Simple Object Notation - dynamic name-value dictionary data type and syntax for Erlang
* [daleharvey/erldocs](https://github.com/daleharvey/erldocs) - Alternative to the erlang documentation
* [rabbitmq/rabbitmq-web-stomp](https://github.com/rabbitmq/rabbitmq-web-stomp) - Provides support for STOMP over WebSockets
* [klarna/circuit_breaker](https://github.com/klarna/circuit_breaker) - :boom: An Erlang library for breaking out of faulty services
* [jkvor/redo](https://github.com/jkvor/redo) - pipelined erlang redis client
* [inaka/gold_fever](https://github.com/inaka/gold_fever) - A Treasure Hunt for Erlangers
* [kaos/ecapnp](https://github.com/kaos/ecapnp) - Cap'n Proto library for Erlang
* [erlangpack/mimetypes](https://github.com/erlangpack/mimetypes) - Erlang MIME types library
* [Bluehouse-Technology/otter](https://github.com/Bluehouse-Technology/otter) - Support for OpenTracing in Erlang
* [processone/fast_xml](https://github.com/processone/fast_xml) - Fast Expat based Erlang XML parsing library
* [julianduque/erlang-color](https://github.com/julianduque/erlang-color) - ANSI colors for your Erlang
* [jkvor/redgrid](https://github.com/jkvor/redgrid) - automatic Erlang node discovery via redis
* [benoitc/econfig](https://github.com/benoitc/econfig) - simple Erlang config handler using INI files
* [wooga/newrelic-erlang](https://github.com/wooga/newrelic-erlang) - Erlang library for sending metrics to New Relic
* [schacon/erlangit](https://github.com/schacon/erlangit) - Erlang Git Implementation
* [mfoemmel/erlang-otp](https://github.com/mfoemmel/erlang-otp) - All of the public Erlang/OTP source releases (since R6B-0 in 1999) in convenient git form
* [basho/merge_index](https://github.com/basho/merge_index) - MergeIndex is an Erlang library for storing ordered sets on disk. It is very similar to an SSTable (in Google's Bigtable) or an HFile (in Hadoop).
* [archaelus/esmtp](https://github.com/archaelus/esmtp) - Erlang SMTP library
* [wooga/etest](https://github.com/wooga/etest) - A lightweight, convention over configuration test framework for Erlang
* [GameAnalytics/hyper](https://github.com/GameAnalytics/hyper) - Erlang implementation of HyperLogLog
* [uwiger/sext](https://github.com/uwiger/sext) - Sortable Erlang Term Serialization
* [shopgun/turtle](https://github.com/shopgun/turtle) - A wrapper on the RabbitMQ Erlang Client (Erlang)
* [jkvor/epm](https://github.com/jkvor/epm) - Erlang Package Manager
* [freecnpro/observerweb](https://github.com/freecnpro/observerweb) - Erlang observer web frontend
* [ddosia/mekao](https://github.com/ddosia/mekao) - Erlang SQL constructor
* [puzza007/katipo](https://github.com/puzza007/katipo) - HTTP client for Erlang based on libcurl and libevent
* [kivra/restclient](https://github.com/kivra/restclient) - Erlang Rest Client
* [jlouis/erl-lenses](https://github.com/jlouis/erl-lenses) - Lens implementation in Erlang
* [selectel/tempo](https://github.com/selectel/tempo) - NIF-based date and time parsing and formatting for Erlang.
* [komone/qrcode](https://github.com/komone/qrcode) - QR Code encoder in Erlang
* [jlouis/eministat](https://github.com/jlouis/eministat) - Port of Poul-Henning Kamp's ministat to the Erlang world
* [gotthardp/gen_coap](https://github.com/gotthardp/gen_coap) - Generic Erlang CoAP Client/Server
* [cannedprimates/stdlib2](https://github.com/cannedprimates/stdlib2) - Erlang stdlib extensions.
* [boundary/gen_lb](https://github.com/boundary/gen_lb) - A generic library to load balance communication between Erlang nodes
* [spawngrid/seqbind](https://github.com/spawngrid/seqbind) - Sequential Binding Parse Transformation for Erlang
* [RJ/relflow](https://github.com/RJ/relflow) - Version-incrementing, appup-generating, relx-coaxing, workflow-assistant for Erlang projects using rebar3.
* [lambdaclass/riak_core_tutorial](https://github.com/lambdaclass/riak_core_tutorial) - An up to date riak_core tutorial, using the riak_core_ng fork, Erlang/OTP 20 and rebar3
* [KirinDave/gen_leader_revival](https://github.com/KirinDave/gen_leader_revival) - A project to unify various implementations of the Erlang library gen_leader into a modern, robust single implementation
* [huaban/erlzk](https://github.com/huaban/erlzk) - A Pure Erlang ZooKeeper Client (no C dependency)
* [skeltoac/php_app](https://github.com/skeltoac/php_app) - A PHP eval server for Erlang/OTP.
* [etnt/gettext](https://github.com/etnt/gettext) - Erlang internationalization library.
* [erlang/docker-erlang](https://github.com/erlang/docker-erlang) - HowTo Erlang in Docker
* [emirozer/beamwhale](https://github.com/emirozer/beamwhale) - minimal container runtime in erlang
* [dweldon/edate](https://github.com/dweldon/edate) - date manipulation library for erlang
* [mbbx6spp/rebar-templates](https://github.com/mbbx6spp/rebar-templates) - Rebar Erlang, OTP and other project templates. Use rebar3 for rebar3 templates and updates.
* [cstar/erldis](https://github.com/cstar/erldis) - redis erlang client library (imported from bitbucket)
* [travis/erlang-uuid](https://github.com/travis/erlang-uuid) - Erlang UUID Module
* [skruger/Surrogate](https://github.com/skruger/Surrogate) - Proxy server written in erlang.  Supports reverse proxy load balancing and forward proxy with http (including CONNECT), socks4, socks5, and transparent proxy modes.

* [ngerakines/erlang_facebook](https://github.com/ngerakines/erlang_facebook) - A simple Facebook Platform API interface in Erlang.
* [flussonic/epm](https://github.com/flussonic/epm) - Erlang package maker
* [extend/elevators](https://github.com/extend/elevators) - Elevator control system demonstrating Erlang/OTP upgrades.
* [dnsimple/dns_erlang](https://github.com/dnsimple/dns_erlang) - Erlang DNS library
* [cnwzhjs/python.erl](https://github.com/cnwzhjs/python.erl) - Python interpreter written in pure Erlang.

* [vim-erlang/vim-erlang-runtime](https://github.com/vim-erlang/vim-erlang-runtime) - Erlang indentation and syntax for Vim
* [mojombo/rebar](https://github.com/mojombo/rebar) - Ruby to Erlang Bridge And Runner
* [fogfish/datum](https://github.com/fogfish/datum) - pure functional and generic programming for Erlang
* [ferd/merklet](https://github.com/ferd/merklet) - Merkle Trees for data replication in Erlang
* [dustin/elock](https://github.com/dustin/elock) - A simple, fault-tolerant distributed lock server in erlang.
* [boundary/bear](https://github.com/boundary/bear) -  a set of statistics functions for erlang
* [knutin/bisect](https://github.com/knutin/bisect) - Ordered fixed-size binary dictionary in Erlang
* [eproxus/grapherl](https://github.com/eproxus/grapherl) - Create graphs of Erlang systems and programs
* [eltex-ecss/chronica](https://github.com/eltex-ecss/chronica) - Logger framework for Erlang applications
* [basho/riak_sysmon](https://github.com/basho/riak_sysmon) - Simple OTP app for managing Erlang VM system_monitor event messages
* [tim/erlang-oauth-examples](https://github.com/tim/erlang-oauth-examples) - Example client/server code for erlang-oauth
* [lehoff/chronos](https://github.com/lehoff/chronos) - Timer module for Erlang that makes it easy to abstact time out of the tests.
* [jtendo/confetti](https://github.com/jtendo/confetti) - Erlang configuration provider / application:get_env/2 on steroids
* [jj1bdx/sfmt-erlang](https://github.com/jj1bdx/sfmt-erlang) - sfmt-erlang: SIMD-oriented Fast Mersenne Twister (SFMT) for Erlang
* [fredlund/JavaErlang](https://github.com/fredlund/JavaErlang) - JavaErlang is a library that attempts to facilitate the communication between Java and Erlang nodes, implemented as an additional layer on top  of the JInterface Java interface.
* [kivra/oauth2_client](https://github.com/kivra/oauth2_client) - Erlang OAuth2 Client
* [bwegh/erwa](https://github.com/bwegh/erwa) - A wamp.ws router written in Erlang.
* [rabbitmq/rabbit-socks](https://github.com/rabbitmq/rabbit-socks) - Websocket and Socket.IO support for RabbitMQ (deprecated -- see https://github.com/sockjs/sockjs-erlang instead)
* [fredlund/McErlang](https://github.com/fredlund/McErlang) - The McErlang model checker for Erlang
* [chef/concrete](https://github.com/chef/concrete) - Concrete enhances your rebar based Erlang project by providing a common Makefile wrapper, a dialyzer make target that caches PLT analysis of your project's dependencies, and a mechanism to specify development only dependencies.
* [r-willis/biten](https://github.com/r-willis/biten) - Bitcoin Erlang Node - scalable bitcoin daemon
* [for-GET/jesse](https://github.com/for-GET/jesse) - jesse (JSon Schema Erlang) is an implementation of a JSON Schema validator for Erlang.
* [exercism/erlang](https://github.com/exercism/erlang) - Exercism exercises in Erlang.
* [travelping/flower](https://github.com/travelping/flower) - FlowER - a Erlang OpenFlow development platform
* [mujaheed/erlang-amf](https://github.com/mujaheed/erlang-amf) - Erlang Action Message Format Library
* [certifi/erlang-certifi](https://github.com/certifi/erlang-certifi) - SSL Certificates for Erlang
* [uwiger/setup](https://github.com/uwiger/setup) - Generic setup utility for Erlang-based systems
* [strange/erlang_v8](https://github.com/strange/erlang_v8) - Run JavaScript from Erlang in an external OS process.
* [RoadRunnr/ezmq](https://github.com/RoadRunnr/ezmq) - zMQ implemented in Erlang
* [devinus/sqerl](https://github.com/devinus/sqerl) - An Erlang-flavoured SQL DSL
* [gleber/erlfu](https://github.com/gleber/erlfu) - Futures implemented in Erlang
* [erlang/sourcer](https://github.com/erlang/sourcer) - An Erlang language server, providing IDE services.
* [devinus/detergent](https://github.com/devinus/detergent) - An emulsifying Erlang SOAP library
* [crownedgrouse/geas](https://github.com/crownedgrouse/geas) - Guess Erlang Application Scattering
* [arjan/pkgx](https://github.com/arjan/pkgx) - Build .deb packages from Erlang releases
* [refuge/cowdb](https://github.com/refuge/cowdb) - Pure Key/Value database library for Erlang Applications
* [mrallen1/gisla](https://github.com/mrallen1/gisla) - A library that implements the sagas pattern for Erlang
* [lasp-lang/lasp_pg](https://github.com/lasp-lang/lasp_pg) - Lasp driven process group registry for Erlang.
* [jchris/erlang-json-eep-parser](https://github.com/jchris/erlang-json-eep-parser) - A collection of leex and yecc definitions, along with tests
* [dustin/ememcached](https://github.com/dustin/ememcached) - A framework for building erlang memcached servers.
* [census-instrumentation/opencensus-erlang](https://github.com/census-instrumentation/opencensus-erlang) - A stats collection and distributed tracing framework
* [archaelus/edump](https://github.com/archaelus/edump) - Erlang Crashdump Analysis Suite
* [softlab-ntua/bencherl](https://github.com/softlab-ntua/bencherl) - A scalability benchmark suite for Erlang/OTP
* [proger/active](https://github.com/proger/active) - Active development for Erlang: rebuild and reload source/binary files while the VM is running
* [litaocheng/erl-redis](https://github.com/litaocheng/erl-redis) - a redis client library for erlang
* [gburd/gen_paxos](https://github.com/gburd/gen_paxos) - An Erlang/OTP-style implementation of the PAXOS distributed consensus protocol
* [comtihon/bson-erlang](https://github.com/comtihon/bson-erlang) - BSON documents in Erlang, see bsonspec.org
* [alavrik/piqi-erlang](https://github.com/alavrik/piqi-erlang) - Protocol Buffers, JSON, XML data serialization system for Erlang
* [proger/erlsh](https://github.com/proger/erlsh) - Erlang shell tools
* [NetComposer/nkdocker](https://github.com/NetComposer/nkdocker) - Erlang Docker client
* [msantos/tunctl](https://github.com/msantos/tunctl) - Erlang TUN/TAP interface
* [lemenkov/rtplib](https://github.com/lemenkov/rtplib) - Erlang library for dealing with rtp/rtcp (STILL IN A VERY EARLY STAGE)
* [lambdaclass/erlang-katana](https://github.com/lambdaclass/erlang-katana) - :ok_hand: erlang grab bag of useful functions. it should have been called swiss army knife but katanas are more deadlier ;)
* [kevsmith/herml](https://github.com/kevsmith/herml) - Erlang port of Haml
* [idubrov/covertool](https://github.com/idubrov/covertool) - Tool to convert Erlang cover data files into Cobertura XML reports
* [for-GET/katt](https://github.com/for-GET/katt) - KATT (Klarna API Testing Tool) is an HTTP-based API testing tool for Erlang.
* [FlowForwarding/lincx](https://github.com/FlowForwarding/lincx) - Erlang on Bare Metal
* [astro/erlang-collectd](https://github.com/astro/erlang-collectd) - Send collectd statistics from your Erlang applications
* [archaelus/erlirc](https://github.com/archaelus/erlirc) - Erlang IRC client/server framework
* [x6j8x/erlaws](https://github.com/x6j8x/erlaws) - Erlang Amazon WebServices
* [siberian-fast-food/alogger](https://github.com/siberian-fast-food/alogger) - Simply the best logging framework for Erlang
* [jkvor/erlmc](https://github.com/jkvor/erlmc) - Erlang memcached binary protocol client
* [inaka/niffy](https://github.com/inaka/niffy) - Inline C code in Erlang modules to build NIFs
* [etnt/eopenid](https://github.com/etnt/eopenid) - Erlang consumer library for OpenID
* [artplant/vprof](https://github.com/artplant/vprof) - Visual Erlang profiler

* [luisgabriel/erl-chat-server](https://github.com/luisgabriel/erl-chat-server) - A simple chat server written in Erlang.
* [lucaspiller/espec](https://github.com/lucaspiller/espec) - ESpec: Behaviour driven development framework for Erlang
* [inaka/sumo_rest](https://github.com/inaka/sumo_rest) - Generic cowboy handlers to work with Sumo
* [danmacklin/erlang_cep](https://github.com/danmacklin/erlang_cep) - A basic CEP package written in erlang
* [careo/rabbitmq-erlang-client-examples](https://github.com/careo/rabbitmq-erlang-client-examples) - Ports of some examples in tmm1's amqp library to use the rabbitmq erlang client.
* [archaelus/eshellcode](https://github.com/archaelus/eshellcode) - Erlang Shellcode snippets
* [windock/erlyvideo](https://github.com/windock/erlyvideo) - Erlang RTMP server
* [vim-erlang/vim-erlang-tags](https://github.com/vim-erlang/vim-erlang-tags) - Generate Vim tags for Erlang files
* [tim/erlang-decimal](https://github.com/tim/erlang-decimal) - An Erlang decimal arithmetic library
* [msantos/verx](https://github.com/msantos/verx) - Erlang implementation of the libvirtd remote protocol
* [lfex/lsci](https://github.com/lfex/lsci) - Scientific Computing on the Erlang VM - An LFE Wrapper Library for SciPy, NumPy, etc.
* [inaka/cowboy-trails](https://github.com/inaka/cowboy-trails) - A couple of improvements over Cowboy Routes
* [mattwilliamson/chordial](https://github.com/mattwilliamson/chordial) - Chord DHT implementation in erlang
* [lpgauth/buoy](https://github.com/lpgauth/buoy) - High-Performance Erlang HTTP 1.1 Client
* [julienXX/slacker](https://github.com/julienXX/slacker) - Erlang Slack REST API wrapper
* [jkingsbery/sighandler](https://github.com/jkingsbery/sighandler) - Handle UNIX signals in Erlang

* [dweldon/riakpool](https://github.com/dweldon/riakpool) - erlang riak client pool
* [benoitc/erlang-metrics](https://github.com/benoitc/erlang-metrics) - A generic interface to different metrics systems in Erlang.
* [robertoaloi/keynote-to-text](https://github.com/robertoaloi/keynote-to-text) - An Erlang script to convert Apple Keynote files to plain text.
* [richcarl/eunit](https://github.com/richcarl/eunit) - The EUnit lightweight unit testing framework for Erlang - this is the canonical development repository.
* [massemanet/redbug](https://github.com/massemanet/redbug) - erlang tracing debugger

* [dwango/moyo](https://github.com/dwango/moyo) - Erlangの便利なライブラリ集

* [ten0s/syntaxerl](https://github.com/ten0s/syntaxerl) - Syntax checker for Erlang
* [benoitc/hooks](https://github.com/benoitc/hooks) - generic plugin & hook system for Erlang applications
* [vim-erlang/vim-erlang-compiler](https://github.com/vim-erlang/vim-erlang-compiler) - Erlang syntax checking and compiler plugin for Vim
* [raycmorgan/erl-lua](https://github.com/raycmorgan/erl-lua) - An Erlang linked-in driver that allows embedding Lua into the Erlang VM
* [onlyshk/erlang-github-api](https://github.com/onlyshk/erlang-github-api) - erlang-github-api
* [mattsta/erlang-stdinout-pool](https://github.com/mattsta/erlang-stdinout-pool) - stdinout_pool: stuff goes in, stuff goes out.  there's never any miscommunication.
* [mattsta/ecache](https://github.com/mattsta/ecache) - ecache: Erlang ETS Based TTL Cache
* [lambdaclass/holiday_ping](https://github.com/lambdaclass/holiday_ping) - Erlang/Cowboy + ClojureScript/re-frame + PostgreSQL application that sends holiday reminders via slack, mail, etc
* [jkvor/dynamic_compile](https://github.com/jkvor/dynamic_compile) - compile and load erlang modules from string input
* [isaiah/transit-erlang](https://github.com/isaiah/transit-erlang) - transit format for erlang
* [dergraf/epmdpxy](https://github.com/dergraf/epmdpxy) - Simulating Netsplits using the Erlang Port Mapper Deamon
* [Bluehouse-Technology/grpc](https://github.com/Bluehouse-Technology/grpc) - Erlang library for GRPC
* [benoitc/dnssd_erlang](https://github.com/benoitc/dnssd_erlang) - Erlang interface to Apple's Bonjour DNS Service Discovery implementation
* [ttyerl/sqlite-erlang](https://github.com/ttyerl/sqlite-erlang) - Sqlite gen_server port for Erlang. Creates, reads and writes to sqlite database.
* [msantos/srly](https://github.com/msantos/srly) - Native Erlang Unix serial interface
* [mpitid/purity](https://github.com/mpitid/purity) - A side-effect analyzer for Erlang
* [maschisma/lol](https://github.com/maschisma/lol) - Lol — Lisp on erLang, and programming is fun again
* [jimmyrcom/HTML5-Canvas-Old-School-RPG-Map-with-Erlang-Websockets-Chat](https://github.com/jimmyrcom/HTML5-Canvas-Old-School-RPG-Map-with-Erlang-Websockets-Chat) - You can make MMOs now using html thanks to google. See the link for what it does. The client is pure HTML5, the server here is erlang.
* [evanmiller/jerome](https://github.com/evanmiller/jerome) - Erlang rich-text processing library
* [vim-erlang/vim-erlang-omnicomplete](https://github.com/vim-erlang/vim-erlang-omnicomplete) - Erlang omnicomplete plugin for Vim

* [richcarl/erlguten](https://github.com/richcarl/erlguten) - ErlGuten is a system for high-quality typesetting, written purely in Erlang. This is the canonical repository, representing the latest official release, now under the MIT license. (The link below points to the old, outdated project page.)
* [manifest/pal](https://github.com/manifest/pal) - Pragmatic Authentication Library
* [lambdaclass/erlings](https://github.com/lambdaclass/erlings) - Small exercises to get you used to reading and writing Erlang code
* [kvakvs/E4VM](https://github.com/kvakvs/E4VM) - A small portable virtual machine that would run Erlang on embedded systems
* [knutin/gcprof](https://github.com/knutin/gcprof) - Garbage Collection profiler for Erlang
* [klarna/erlavro](https://github.com/klarna/erlavro) - Avro support for Erlang/Elixir (http://avro.apache.org/)
* [grisp/grisp](https://github.com/grisp/grisp) - GRiSP Erlang Runtime Library

* [epappas/erl_streams](https://github.com/epappas/erl_streams) - Streams in Erlang
* [Eonblast/Erlvolt](https://github.com/Eonblast/Erlvolt) - Erlang VoltDB  server interface

* [adrienmo/eredis_cluster](https://github.com/adrienmo/eredis_cluster) - eredis_cluster is an erlang wrapper for eredis to support cluster mode of redis 3.0.0+
* [joaomilho/apalachin](https://github.com/joaomilho/apalachin) - 💬 An Erlang's ChicagoBoss websockets team chat, using Cowboy server and PostgreSQL
* [g-andrade/taskforce](https://github.com/g-andrade/taskforce) - On-demand worker pools for parallelizable tasks
* [filippo/sgte](https://github.com/filippo/sgte) - A simple Erlang Template Engine


* [dmitryme/erlang_localtime](https://github.com/dmitryme/erlang_localtime) - Erlang library for conversion from one local time to another
* [ddossot/jerg](https://github.com/ddossot/jerg) - JSON Schema to Erlang Records Generator
* [Pouriya-Jahanbakhsh/director](https://github.com/Pouriya-Jahanbakhsh/director) - Director is a production-ready supervisor and manager for Erlang/Elixir processes that focuses on speed, performance and flexibility.
* [NetComposer/nkdist](https://github.com/NetComposer/nkdist) - Erlang distributed registration and load balancing

* [lrascao/rebar3_appup_plugin](https://github.com/lrascao/rebar3_appup_plugin) - A rebar3 plugin for frictionless release upgrades
* [lpgauth/marina](https://github.com/lpgauth/marina) - High-Performance Erlang Cassandra CQL Client
* [jkvor/log_roller](https://github.com/jkvor/log_roller) - A pub/sub modeled, distributed Erlang logging system
* [dieswaytoofast/erlasticsearch](https://github.com/dieswaytoofast/erlasticsearch) - Erlang thrift interface to elastic_search
* [bfrog/hottub](https://github.com/bfrog/hottub) - Simple, Fast, Permanent Erlang Worker Pool
* [armon/erl-rstar](https://github.com/armon/erl-rstar) - An Erlang implementation of the R*-tree spacial data structure
* [Amadiro/erlang-statistics](https://github.com/Amadiro/erlang-statistics) - Simple statistic generator for erlang systems. The chart generator is written in perl.
* [processone/xmpp](https://github.com/processone/xmpp) - Erlang/Elixir XMPP parsing and serialization library on top of Fast XML
* [NetComposer/nkpacket](https://github.com/NetComposer/nkpacket) - Generic Erlang transport layer
* [ndpar/erlang](https://github.com/ndpar/erlang) - My Erlang/OTP library
* [muxspace/bunny_farm](https://github.com/muxspace/bunny_farm) - AMQP erlang client wrapper library using the RabbitMQ libraries
* [maxlapshin/gitty](https://github.com/maxlapshin/gitty) - Git access in erlang
* [clofresh/esyslog](https://github.com/clofresh/esyslog) - An Erlang implementation of the syslog server protocol
* [cabol/west](https://github.com/cabol/west) - WEST (Web/Event-driven Systems Tool) is another messaging tool written in Erlang, that enables the building of messaging-based systems
* [benoitc/nat_upnp](https://github.com/benoitc/nat_upnp) - Erlang library to map your internal port to an external using UNP IGD
* [shortishly/mdns](https://github.com/shortishly/mdns) - Multicast DNS in Erlang/OTP
* [refuge/rbeacon](https://github.com/refuge/rbeacon) - LAN discovery and presence in Erlang.
* [rabbitmq/rabbitmq-common](https://github.com/rabbitmq/rabbitmq-common) - Common library used by rabbitmq-server and rabbitmq-erlang-client
* [machinezone/mzmetrics](https://github.com/machinezone/mzmetrics) - High performance Erlang metrics library
* [lk-geimfari/nebula](https://github.com/lk-geimfari/nebula) - Small library for colored (ANSI) output in Erlang/Elixir/LFE. It's can be useful when you need to create a user-friendly command-line applications.
* [kalta/etoml](https://github.com/kalta/etoml) - TOML language erlang parser
* [hio/erlang-record_info](https://github.com/hio/erlang-record_info) - convert between record and proplist
* [heroku/stillir](https://github.com/heroku/stillir) - Cache environment variables as Erlang app variables
* [G-Corp/vice](https://github.com/G-Corp/vice) - Video, audio and Image Converter for Erlang/Elixir
* [g-andrade/locus](https://github.com/g-andrade/locus) - Geolocation and ASN lookup of IP addresses
* [erszcz/euc-2014](https://github.com/erszcz/euc-2014) - Introduction to Load Testing with Tsung for Erlang User Conference 2014
* [CarlWright/NGerlguten](https://github.com/CarlWright/NGerlguten) - Next Generation erlguten -- a PDF generation application in Erlang
* [videlalvaro/erlang-prime-sieve](https://github.com/videlalvaro/erlang-prime-sieve) -  Naive Parallel Prime Numbers Sieve
* [thorstadt/bifrost](https://github.com/thorstadt/bifrost) - Erlang FTP Server Framework
* [silviucpp/erlcass](https://github.com/silviucpp/erlcass) - High-Performance Erlang Cassandra driver based on DataStax cpp-driver
* [schlagert/syslog](https://github.com/schlagert/syslog) - An RFC 3164 and RFC 5424 compliant logging framework for Erlang.
* [paulgray/exml](https://github.com/paulgray/exml) - XML parsing library in Erlang
* [lpgauth/swirl](https://github.com/lpgauth/swirl) - High-Performance Erlang Stream Processor
* [kevinlynx/kdht](https://github.com/kevinlynx/kdht) - kdht is an erlang DHT implementation
* [gossiperl/gossiperl](https://github.com/gossiperl/gossiperl) - Gossip middleware in Erlang
* [gleber/exat](https://github.com/gleber/exat) - eXAT - The erlang eXperimental Agent Tool
* [geocar/inet_ssh_dist](https://github.com/geocar/inet_ssh_dist) - SSH distribution for erlang
* [fra/ecron](https://github.com/fra/ecron) - Cron-like scheduler for Erlang
* [FlowForwarding/of_protocol](https://github.com/FlowForwarding/of_protocol) - OpenFlow Protocol Library for Erlang
* [dmitriid/neo4j-erlang](https://github.com/dmitriid/neo4j-erlang) - Erlang client library for Neo4J's REST API
* [xinmingyao/zab_engine](https://github.com/xinmingyao/zab_engine) - zab propotocol implement by erlang
* [vjache/erlang-zlists](https://github.com/vjache/erlang-zlists) - Erlang lazy lists library.
* [ramsay-t/Smother](https://github.com/ramsay-t/Smother) - Extended code coverage metrics for Erlang.
* [Quviq/webdrv](https://github.com/Quviq/webdrv) - WebDriver implementation in Erlang
* [psyeugenic/eplot](https://github.com/psyeugenic/eplot) - A plot engine written in erlang.
* [nygge/abnfc](https://github.com/nygge/abnfc) - An ABNF parser generator for Erlang.
* [mihawk/draw](https://github.com/mihawk/draw) - demo of websocket service with ChicagoBoss, sharing a realtime drawing
* [marshall-lee/etcd.erl](https://github.com/marshall-lee/etcd.erl) - Erlang bindings for etcd key value store
* [jvantuyl/erlctl](https://github.com/jvantuyl/erlctl) - Command Line Interface Framework for Erlang
* [inaka/lasse](https://github.com/inaka/lasse) - SSE handler for Cowboy
* [huffman/twilio_erlang](https://github.com/huffman/twilio_erlang) - An Erlang library for communicating with the Twilio API and generating TwiML
* [eproxus/pretty_errors](https://github.com/eproxus/pretty_errors) - Error and stack trace pretty printers for Erlang
* [deadtrickster/ssl_verify_fun.erl](https://github.com/deadtrickster/ssl_verify_fun.erl) - Collection of ssl verification functions for Erlang
* [bet365/erpc](https://github.com/bet365/erpc) - An alternative RPC implementation for Erlang.
* [afiskon/erlang-http-proxy](https://github.com/afiskon/erlang-http-proxy) - Nontrivial HTTP proxy server in Erlang
* [stolen/autohelp](https://github.com/stolen/autohelp) - Parse_transform for erlang which adds functions help/{0,1,2} showing edoc information about module and exported functions.
* [jashmenn/chordjerl](https://github.com/jashmenn/chordjerl) - An Erlang implementation of the Chord distributed hash lookup protocol
* [inaka/xref_runner](https://github.com/inaka/xref_runner) - Erlang Xref Runner (inspired in rebar xref)
* [iamaleksey/seestar](https://github.com/iamaleksey/seestar) - The Erlang client for Cassandra 1.2+ binary protocol
* [hyperthunk/nodewatch](https://github.com/hyperthunk/nodewatch) - Erlang/OTP Node Monitoring
* [engineyard/vertebra-erl](https://github.com/engineyard/vertebra-erl) - Vertebra Erlang Pieces
* [aberman/pooly](https://github.com/aberman/pooly) - Erlang OTP Process Pool
* [a13x/aberth](https://github.com/a13x/aberth) - Generic BERT-RPC server in Erlang
* [noss/iserve](https://github.com/noss/iserve) - A small http server for erlang.
* [mujaheed/erlang-osc](https://github.com/mujaheed/erlang-osc) - Erlang Open Sound Control Application
* [MiCHiLU/shirasu](https://github.com/MiCHiLU/shirasu) - Shirasu.ws is a WebSocket server framework based on Misultin and Erlang/OTP
* [madtrick/wsock](https://github.com/madtrick/wsock) - Erlang library to build WebSocket clients and servers

* [jj1bdx/sshrpc](https://github.com/jj1bdx/sshrpc) - Erlang SSH RPC module (experimental)
* [inaka/beam_olympics](https://github.com/inaka/beam_olympics) - Let's find the fastest beamer!
* [haljin/erlesy](https://github.com/haljin/erlesy) - Visual Erlang development
* [GeneStevens/jsonpath](https://github.com/GeneStevens/jsonpath) - Fast Erlang JSON data retrieval and updates via javascript-like notation
* [eriksoe/ErlangQuest](https://github.com/eriksoe/ErlangQuest) - Learn Erlang through this set of challenges. An interactive system for getting to know Erlang.
* [darach/jch-erl](https://github.com/darach/jch-erl) - Jump Consistent Hashing Library for Erlang/OTP
* [clonejo/mc-erl](https://github.com/clonejo/mc-erl) - mc-erl is a server for Minecraft 1.4.7 written in Erlang.


* [silentsignal/DirBustErl](https://github.com/silentsignal/DirBustErl) - DirBuster successor in Erlang
* [sendtopms/Erlwebsockserver](https://github.com/sendtopms/Erlwebsockserver) - Html5 websocket protocol server for Erlang based application server
* [renatoaguiar/erlang-openflow](https://github.com/renatoaguiar/erlang-openflow) - An OpenFlow controller written in pure erlang
* [okeuday/pest](https://github.com/okeuday/pest) - :beetle: Primitive Erlang Security Tool
* [mazenharake/eirc](https://github.com/mazenharake/eirc) - An IRC client library for Erlang
* [marcelog/erws](https://github.com/marcelog/erws) - Erlang Websockets example using Cowboy
* [g-andrade/maestro](https://github.com/g-andrade/maestro) - An Erlang pool of pools.
* [francescoc/erlangprogramming](https://github.com/francescoc/erlangprogramming) - The source code of the Erlang Programming book by Francesco Cesarini and Simon Thompson, published by O'Reilly Media
* [fillmyheart/slg-server](https://github.com/fillmyheart/slg-server) - erlang 游戏服务器框架。
* [ferd/zippers](https://github.com/ferd/zippers) - A library for functional zipper data structures in Erlang. Read more on zippers @ http://ferd.ca/yet-another-article-on-zippers.html
* [erlware/erlang-camp](https://github.com/erlware/erlang-camp) - Code for the ErlangCamp teaching conference
* [coreyhaines/handbook-of-neuroevolution](https://github.com/coreyhaines/handbook-of-neuroevolution) - Code samples from the Handbook of Neuroevolution through Erlang in both Erlang and Elixir
* [Yongke/shadowsocks-erlang](https://github.com/Yongke/shadowsocks-erlang) - Totally asynchronous implementation of Shadowsocks in Erlang
* [whitenode/riak_mapreduce_utils](https://github.com/whitenode/riak_mapreduce_utils) - Library containing map/reduce utility functions for Riak implemented in erlang.
* [tonyg/erlang-smtp](https://github.com/tonyg/erlang-smtp) - Erlang SMTP and POP3 server code.
* [spawngrid/esupervisor](https://github.com/spawngrid/esupervisor) - "Least surprise" Erlang supervisor API
* [sigscale/radierl](https://github.com/sigscale/radierl) - RADIUS protocol stack for Erlang.
* [mdevilliers/erlang-mesos](https://github.com/mdevilliers/erlang-mesos) - An erlang binding for mesos - http://mesos.apache.org/
* [kivra/email](https://github.com/kivra/email) - The Erlang Mail application or Email for short
* [kevsmith/giza](https://github.com/kevsmith/giza) - Erlang client for the Sphinx search engine
* [kenpratt/erlbrake](https://github.com/kenpratt/erlbrake) - Erlang Airbrake notification client
* [jeremey/swarm](https://github.com/jeremey/swarm) - Fast and simple acceptor pool for Erlang
* [ivanos/erl_sshd](https://github.com/ivanos/erl_sshd) - Wrapper around Erlang ssh module to make it easier to add an sshd to any node
* [inaka/serpents](https://github.com/inaka/serpents) - Multi-Player Game on top of HDP protocol
* [hcvst/erlang-dns](https://github.com/hcvst/erlang-dns) - Erlang/OTP DNS server
* [ferd/simhash](https://github.com/ferd/simhash) - Simhashing for Erlang -- hashing algorithm to find near-duplicates in binary data.
* [djui/eraft](https://github.com/djui/eraft) - Raft reference implementation for Erlang
* [ctennis/erlang-modbus](https://github.com/ctennis/erlang-modbus) - A modbus RTU and TCP driver for erlang
* [bojzi/erlang-dht](https://github.com/bojzi/erlang-dht) - A very simple example of implementing a structured P2P network (DHT) in Erlang.
* [unbalancedparentheses/erlskeletor_cowboy](https://github.com/unbalancedparentheses/erlskeletor_cowboy) - :neckbeard: Erlang skeleton with cowboy and common test
* [toddlipcon/thrift_erl_skel](https://github.com/toddlipcon/thrift_erl_skel) - skeleton for thrift services in erlang
* [taybin/lethink](https://github.com/taybin/lethink) - erlang driver for rethinkdb
* [rtraschke/erlang-lua](https://github.com/rtraschke/erlang-lua) - Erlang C Node to run Lua scripts
* [proger/erlfsmon](https://github.com/proger/erlfsmon) - Erlang filesystem event watcher frontend for fswatch
* [okeuday/erlbench](https://github.com/okeuday/erlbench) - Erlang Performance Measurements
* [nmichel/ejpet](https://github.com/nmichel/ejpet) - Matching JSON nodes in Erlang
* [msantos/gen_unix](https://github.com/msantos/gen_unix) - Erlang Unix socket interface
* [mallipeddi/tora](https://github.com/mallipeddi/tora) - An Erlang client for Tokyo Tyrant (speaks Tokyo Tyrant's TCP/IP protocol).
* [lucaspiller/twerl](https://github.com/lucaspiller/twerl) - Erlang client for the Twitter Streaming API

* [hukl/Bitturret](https://github.com/hukl/Bitturret) - Bittorrent Tracker written in Erlang
* [g-andrade/backwater](https://github.com/g-andrade/backwater) - Intercluster RPC for Erlang and Elixir

* [cstar/erls3](https://github.com/cstar/erls3) - Erlang/OTP application for accessing Amazon S3
* [cloudhead/erlapp.template](https://github.com/cloudhead/erlapp.template) - minimal erlang/OTP rebar template
* [arekinath/esaml](https://github.com/arekinath/esaml) - Erlang SAML library, SSO and SLO, with Cowboy integration
* [Vagabond/erlang-rrdtool](https://github.com/Vagabond/erlang-rrdtool) - An erlang interface to rrdtool
* [unix1/nuk](https://github.com/unix1/nuk) - Generic turn based game server in Erlang/OTP
* [TypedLambda/eresye](https://github.com/TypedLambda/eresye) - This is a clone of the Sourceforge project repository of the same name. ERESYE means ERlang Expert SYstem Engine. It is a library to write expert systems and rule processing engines using the Erlang programming language. It allows to create multiple engines, each one with its own facts and rules to be processed.
* [travelping/hello](https://github.com/travelping/hello) - Erlang RPC server framework
* [tim/erlang-beanstalk](https://github.com/tim/erlang-beanstalk) - An Erlang client for beanstalkd
* [seriyps/pe4kin](https://github.com/seriyps/pe4kin) - Erlang wrapper for Telegram bot API https://core.telegram.org/bots
* [OtpChatBot/irc_lib](https://github.com/OtpChatBot/irc_lib) - Erlang irc client library
* [odo/revolver](https://github.com/odo/revolver) - round-robin load balancer for Erlang processes
* [mrallen1/parque](https://github.com/mrallen1/parque) - Erlang trading game engine
* [mccoy/medici](https://github.com/mccoy/medici) - Erlang interface for Tokyo Tyrant
* [joergen7/gen_pnet](https://github.com/joergen7/gen_pnet) - A generic Petri net OTP behavior.
* [joedevivo/hpack](https://github.com/joedevivo/hpack) - HPACK Implementation for Erlang
* [inaka/fiar](https://github.com/inaka/fiar) - Four in a Row - A game to learn Erlang
* [inaka/erlang-github](https://github.com/inaka/erlang-github) - Github API client
* [efcasado/forms](https://github.com/efcasado/forms) - A library that simplifies working with the Erlang abstract format.
* [EchoTeam/mavg](https://github.com/EchoTeam/mavg) - Erlang :: Exponential moving average library
* [drfloob/ezic](https://github.com/drfloob/ezic) - a set of erlang utilities for the Olson timezone database files
* [barrel-db/erlang-lru](https://github.com/barrel-db/erlang-lru) - a fixed size LRU cache.
* [AdRoll/kinetic](https://github.com/AdRoll/kinetic) - Erlang Kinesis Client
* [refuge/rkvs](https://github.com/refuge/rkvs) - Simple Erlang  Key/Value framework
* [rabbitmq/rabbitmq-top](https://github.com/rabbitmq/rabbitmq-top) - Adds top-like information on the Erlang VM to the management plugin.
* [project-iris/iris-erl](https://github.com/project-iris/iris-erl) - Iris Erlang binding
* [mujaheed/erlang-http](https://github.com/mujaheed/erlang-http) - Modular, RFC 2616 compliant HTTP/1.1 server and client
* [msantos/erlang-libvirt](https://github.com/msantos/erlang-libvirt) - Erlang binding to libvirt virtualization API
* [mmcdanie/erlview](https://github.com/mmcdanie/erlview) - Erlang View Server for CouchDB
* [massemanet/trane](https://github.com/massemanet/trane) - SAX style broken HTML parser in Erlang
* [markusn/coveralls-erl](https://github.com/markusn/coveralls-erl) - Erlang module to convert and send cover data to coveralls.io (or similar). Available as a hex package on https://hex.pm/packages/coveralls.
* [klajo/mockgyver](https://github.com/klajo/mockgyver) - A mocking library for Erlang
* [justinkirby/emetric](https://github.com/justinkirby/emetric) - Erlang Metric Logger
* [Damienkatz/json_stream_parse](https://github.com/Damienkatz/json_stream_parse) - An evented, streaming json parser for Erlang.
* [antoniogarrote/egearmand-server](https://github.com/antoniogarrote/egearmand-server) - erlang implementation of gearman server
* [yrashk/evfs](https://github.com/yrashk/evfs) - Erlang Virtual Filesystem
* [wozniakjan/erlcart](https://github.com/wozniakjan/erlcart) - Erlang OpenShift2 Cartridge
* [wooga/kafka-erlang](https://github.com/wooga/kafka-erlang) - Kafka consumer and producer in Erlang
* [wardbekker/search](https://github.com/wardbekker/search) - Erlang implementation of  WAND/max_score TOP-K retrieval algo.
* [tsloughter/epubnub](https://github.com/tsloughter/epubnub) - Erlang PubNub API
* [talentdeficit/json](https://github.com/talentdeficit/json) - a high level json library for erlang (17.0+)
* [spawngrid/erlang-sql-migrations](https://github.com/spawngrid/erlang-sql-migrations) - Simple Erlang library to run SQL migrations
* [ScottBrooks/Erlcraft](https://github.com/ScottBrooks/Erlcraft) - Erlang Minecraft server
* [psyeugenic/fgraph](https://github.com/psyeugenic/fgraph) - Physics engine for graph drawing written in erlang for use in wxErlang or standalone.
* [nalundgaard/jsn](https://github.com/nalundgaard/jsn) - Utilities for interacting with decoded JSON in erlang
* [lizenn/erlang-dbus](https://github.com/lizenn/erlang-dbus) - Erlang DBUS implementation (forked from unmaintained erlang-dbus)
* [lehoff/egol](https://github.com/lehoff/egol) - Erlang implementation of Conway's Game of Life
* [jpgneves/iota](https://github.com/jpgneves/iota) - iota (Inter-dependency Objective Testing Apparatus) - a tool to enforce clean separation of responsibilities in Erlang code
* [jkvor/erlang_syslog](https://github.com/jkvor/erlang_syslog) - Erlang syslog logger
* [henry-hz/erlang-trader](https://github.com/henry-hz/erlang-trader) - Porting the AlgoTrader (Java) code to Erlang  [Abandoned]
* [dustin/erl-conc](https://github.com/dustin/erl-conc) - Concurrent Lists in Erlang
* [dkataskin/erlazure](https://github.com/dkataskin/erlazure) - Windows Azure Erlang bindings
* [auser/erlfs](https://github.com/auser/erlfs) - A distributed storage system which uses distributed Erlang strongly influenced by http://dawsdesign.com/drupal/erlfs
* [vladdu/erl-pipes](https://github.com/vladdu/erl-pipes) - Hartmann pipes in Erlang
* [sasa1977/fun_chain](https://github.com/sasa1977/fun_chain) - Function chaining in Erlang
* [robertoaloi/ansible-nodetool](https://github.com/robertoaloi/ansible-nodetool) - An Ansible module to interact with Erlang nodes via Erlang RPC
* [project-fifo/dhcp](https://github.com/project-fifo/dhcp) - erlang dhcp server
* [paulzql/shadowsocks-erlang](https://github.com/paulzql/shadowsocks-erlang) - erlang port of shadowsocks (The next generation is elixir  http://github.com/paulzql/shadowsocks-ex )
* [nuex/erl_gm](https://github.com/nuex/erl_gm) - An Erlang GraphicsMagick wrapper
* [nifoc/katja](https://github.com/nifoc/katja) - A simple Riemann client written in Erlang.
* [michaelnisi/feeder](https://github.com/michaelnisi/feeder) - Parse RSS and Atom feeds
* [mdaguete/tcpbalance](https://github.com/mdaguete/tcpbalance) - Generic TCP Balancer for Erlang
* [massung/parsec](https://github.com/massung/parsec) - Parsec-style parsing for Erlang
* [marianoguerra/jwt-erl](https://github.com/marianoguerra/jwt-erl) - JSON Web Token implementation in Erlang
* [mad-cocktail/gin](https://github.com/mad-cocktail/gin) - The guards `in` and `beetween` for Erlang parse_transform
* [klajo/wpi](https://github.com/klajo/wpi) - An Erlang NIF for the WiringPi library for the Raspberry Pi
* [justinkirby/json_rec](https://github.com/justinkirby/json_rec) - JSON to erlang record
* [jj1bdx/tinymt-erlang](https://github.com/jj1bdx/tinymt-erlang) - This software is no longer maintained. For archive/reference use only. -- Tiny Mersenne Twister (TinyMT) for Erlang
* [jixiuf/helloerlang](https://github.com/jixiuf/helloerlang) - my   repos for erlang test code .
* [irr/erl-tutorials](https://github.com/irr/erl-tutorials) - Erlang/OTP sample projects
* [hpyhacking/webtekcos](https://github.com/hpyhacking/webtekcos) - a websocket server in erlang
* [etnt/edbg](https://github.com/etnt/edbg) - A simple tty interface to the Erlang debugger and tracer.
* [egobrain/emodel](https://github.com/egobrain/emodel) - Erlang data transformation/validation library
* [edgurgel/poxa-erlang](https://github.com/edgurgel/poxa-erlang) - Open Pusher server implementation compatible with Pusher libraries.
* [echou/memcached-client](https://github.com/echou/memcached-client) - an Erlang memcached client application
* [del/erserve](https://github.com/del/erserve) - Erlang/Rserve communication interface
* [bokner/gen_client](https://github.com/bokner/gen_client) - Generic XMPP client framework for Erlang

* [yandex/inet64_tcp](https://github.com/yandex/inet64_tcp) - Magic thing to make old Erlang stuff work in IPv6-only networks
* [travelping/eradius](https://github.com/travelping/eradius) - Erlang RADIUS server framework
* [tel/zeta](https://github.com/tel/zeta) - An Erlang client for Riemann.
* [stolen/webdist](https://github.com/stolen/webdist) - Erlang distribution as HTTP protocol upgrade
* [squaremo/erlmqtt](https://github.com/squaremo/erlmqtt) - MQTT library for Erlang *JUST USABLE*
* [seriyps/xhttpc](https://github.com/seriyps/xhttpc) - Extensible HTTP Client for  Erlang
* [saleyn/util](https://github.com/saleyn/util) - Erlang utility modules
* [RJ/erlang_rebar_example_project](https://github.com/RJ/erlang_rebar_example_project) - Basic project using rebar, to demonstrate upgrades and packaging etc
* [reiddraper/fn](https://github.com/reiddraper/fn) - Function utilities for Erlang
* [okeuday/quickrand](https://github.com/okeuday/quickrand) - Quick Erlang Random Number Generation
* [mattsta/stripe-erlang](https://github.com/mattsta/stripe-erlang) - Erlang interface to the stripe.com API
* [mattsta/pcache](https://github.com/mattsta/pcache) - An Erlang cache where every stored item is its own process.
* [lwes/lwes-erlang](https://github.com/lwes/lwes-erlang) - Light Weight Event System Erlang library
* [Licenser/ecrdt](https://github.com/Licenser/ecrdt) - experimenting with CRDTs in erlang
* [klarna/leveldb_manager](https://github.com/klarna/leveldb_manager) - Small service for snapshotting eleveldb without stopping the Erlang node

* [jcomellas/bstr](https://github.com/jcomellas/bstr) - Erlang library to use binaries as strings
* [hypernumbers/erlang-wtd](https://github.com/hypernumbers/erlang-wtd) - Creating a mutant army of self-discovering Raspberry Pi Erlang robots for world domination or something...
* [fogfish/esq](https://github.com/fogfish/esq) - simple persistent/transient queues for erlang
* [ferd/useragent](https://github.com/ferd/useragent) - Identify browsers and OSes from user agent strings, in Erlang
* [erlang-synrc/feeds](https://github.com/erlang-synrc/feeds) - Erlang Social Feeds and Cache Server
* [doubleyou/euthanasia](https://github.com/doubleyou/euthanasia) - Merciful killer for your Erlang processes
* [ddossot/cferl](https://github.com/ddossot/cferl) - Rackspace / Open Stack Cloud Files Erlang Client
* [ctbarbour/swim](https://github.com/ctbarbour/swim) - An Erlang implementation of the SWIM protocol
* [cstar/ec2nodefinder](https://github.com/cstar/ec2nodefinder) - erlang node auto-discovery on EC2
* [carlosgaldino/concha](https://github.com/carlosgaldino/concha) - A consistent hashing library in Erlang.
* [benoitc/sieve](https://github.com/benoitc/sieve) - sieve is a simple TCP routing proxy (layer 7) in erlang
* [anycable/erlycable](https://github.com/anycable/erlycable) - Anycable Erlang WebSocket server
* [treacheroustalks/Treacherous-Talks](https://github.com/treacheroustalks/Treacherous-Talks) - An online implementation of the Diplomacy board game in Erlang.
* [travelping/ergw](https://github.com/travelping/ergw) - erGW - Erlang implementations of GGSN or P-GW
* [spawngrid/validaterl](https://github.com/spawngrid/validaterl) - Data validation library for Erlang
* [richcarl/file_monitor](https://github.com/richcarl/file_monitor) - Erlang file monitoring service
* [ostinelli/cowbell](https://github.com/ostinelli/cowbell) - An Erlang node connection manager.

* [marianoguerra/erldn](https://github.com/marianoguerra/erldn) - edn format parser for the erlang platform
* [leandrosilva/otp_kickoff](https://github.com/leandrosilva/otp_kickoff) - Simple generator to kick-off Erlang/OTP projects
* [lambdaclass/webrtc-server](https://github.com/lambdaclass/webrtc-server) - Signaling and ICE servers for WebRTC in Erlang
* [killme2008/erlwsh](https://github.com/killme2008/erlwsh) - Erlang web shell--program erlang on web
* [jonasrichard/ejson](https://github.com/jonasrichard/ejson) - JSON library for Erlang on top of jsx
* [inaka/canillita](https://github.com/inaka/canillita) - Simple Paperboy-themed PubSub
* [HernanRivasAcosta/kafkerl](https://github.com/HernanRivasAcosta/kafkerl) - Apache Kafka producer/consumer for erlang
* [hamidreza-s/Queuesk](https://github.com/hamidreza-s/Queuesk) - Priority Task Queue for Erlang
* [graphql-erlang/graphql](https://github.com/graphql-erlang/graphql) - Erlang GraphQL implementation
* [gleber/erlgit](https://github.com/gleber/erlgit) - Erlang convenience wrapper around git executable
* [EchoTeam/corman](https://github.com/EchoTeam/corman) - Configuration reload manager for Erlang applications
* [devinus/zucchini](https://github.com/devinus/zucchini) - An Erlang INI parser
* [6/heroku-erlang-example](https://github.com/6/heroku-erlang-example) - [unmaintained] erlang example using webmachine, hosted on heroku
* [tsloughter/erl_tidy](https://github.com/tsloughter/erl_tidy) - Automatically format Erlang code.
* [tmaciejewski/see](https://github.com/tmaciejewski/see) - Search Engine in Erlang
* [processone/cache_tab](https://github.com/processone/cache_tab) - In-memory cache Erlang / Elixir library
* [ngerakines/s3imagehost](https://github.com/ngerakines/s3imagehost) - An erlang powered image store using amazon s3.
* [mrDoctorWho/ejabberd_mod_gcm](https://github.com/mrDoctorWho/ejabberd_mod_gcm) - Google Cloud Messaging API for Ejabberd (PUSH Messages)
* [maxlapshin/csv_reader](https://github.com/maxlapshin/csv_reader) - Fast erlang csv reader
* [massemanet/gtknode](https://github.com/massemanet/gtknode) - Erlang GTK binding
* [lindenbaum/eipmi](https://github.com/lindenbaum/eipmi) - A native Erlang IPMI library.
* [g-andrade/erlwitness](https://github.com/g-andrade/erlwitness) - Tracing processes by semantic group (Erlang)

* [etnt/ehotp](https://github.com/etnt/ehotp) - Erlang implementation of the HOTP algoritm (RFC-4226)
* [erszcz/pa](https://github.com/erszcz/pa) - Partial application of Erlang functions
* [cchandler/RTreeCouchDB](https://github.com/cchandler/RTreeCouchDB) - Erlang R-Tree implementation I'm going to try and move into CouchDB for n-dimensional spatial indexing
* [brendonh/erl_openid](https://github.com/brendonh/erl_openid) - Erlang OpenID
* [ates/netspire-core](https://github.com/ates/netspire-core) - The Erlang RADIUS server and NetFlow v5, v9 collector
* [asceth/nehe_erlang](https://github.com/asceth/nehe_erlang) - NeHe OpenGL tutorials ported to Erlang
* [a13x/ezmtp](https://github.com/a13x/ezmtp) - ZMTP protocol in pure Erlang.
* [yoonka/migresia](https://github.com/yoonka/migresia) - A simple Erlang tool to automatically migrate Mnesia databases between versions
* [tonyg/erlang-ircd](https://github.com/tonyg/erlang-ircd) - A pluggable IRC daemon application/library for Erlang.
* [tex/ssync](https://github.com/tex/ssync) - Stay in sync in rebarized erlang projects
* [systemd/ejournald](https://github.com/systemd/ejournald) - A Erlang binding to the systemd journal C API
* [seth/sherl](https://github.com/seth/sherl) - A URL Shortening Service Written in Erlang
* [SemanticSugar/dinerl](https://github.com/SemanticSugar/dinerl) - Erlang AWS DynamoDB client
* [samuelrivas/moka](https://github.com/samuelrivas/moka) - A mocking (more precisely moking) framework for erlang
* [rvirding/spell1](https://github.com/rvirding/spell1) - LL(1) parser generator for Erlang and LFE
* [rramsden/gen_gossip](https://github.com/rramsden/gen_gossip) - Interface for implementing Gossip Protocols in Erlang
* [richcarl/sendmail](https://github.com/richcarl/sendmail) - Erlang sendmail interface
* [puzza007/openpoker](https://github.com/puzza007/openpoker) - Wagerlabs OpenPoker from before it went closed-source
* [omarkj/erollbar](https://github.com/omarkj/erollbar) - Rollbar client in Erlang
* [okeuday/erlang_term](https://github.com/okeuday/erlang_term) - Erlang Term Info
* [ngmoco/gl_async_bully](https://github.com/ngmoco/gl_async_bully) - Dynamic Leader Election behaviour for Erlang
* [msantos/erlxc](https://github.com/msantos/erlxc) - Simple, safe erlang interface for managing Linux Containers
* [msantos/emdns](https://github.com/msantos/emdns) - Erlang multicast DNS and DNS-SD (DNS Service Discovery)
* [marianoguerra/qrly](https://github.com/marianoguerra/qrly) - jquery selectors for HTML & XML in erlang
* [lemenkov/erlpmd](https://github.com/lemenkov/erlpmd) - A drop-in replacement for epmd written in Erlang
* [Klimiec/Erlang](https://github.com/Klimiec/Erlang) - Erlang exercises with answers
* [idubrov/siperl](https://github.com/idubrov/siperl) - RFC 3261 (SIP) implementation in Erlang
* [hungryblank/emongrel2](https://github.com/hungryblank/emongrel2) - erlang mongrel2 toolkit, build mongrel2 handlers and compatible servers
* [hiroeorz/arduino-erlang](https://github.com/hiroeorz/arduino-erlang) - Arduino handler for Erlang/OTP Application.
* [heroku/ehmon](https://github.com/heroku/ehmon) - Heroku Erlang VM Monitoring library
* [gar1t/erlang-bench](https://github.com/gar1t/erlang-bench) - Various Erlang related benchmarks
* [erlang/epmd](https://github.com/erlang/epmd) - Erlang Port Mapper Daemon in Erlang
* [egobrain/erlang_decorators](https://github.com/egobrain/erlang_decorators) - This code implenets decorators for erlang.
* [ddossot/cadfaerl](https://github.com/ddossot/cadfaerl) - CAching Datastructure For Applications in ERLang
* [darrikmazey/erlmon](https://github.com/darrikmazey/erlmon) - host and network monitoring suite written in erlang
* [cavedweller/webRTC.io-erlang](https://github.com/cavedweller/webRTC.io-erlang) - An erlang implementation of the webRTC.io server built on top of cowboy/OTP
* [aaronps/enotepad](https://github.com/aaronps/enotepad) - Clone of MS Notepad using Erlang (wxWidgets)
* [xvw/coers](https://github.com/xvw/coers) - A small library for coercion to primitive Erlang types.
* [Vagabond/diemap](https://github.com/Vagabond/diemap) - An extensible IMAP server for Erlang
* [ThomasHabets/eggpd](https://github.com/ThomasHabets/eggpd) - Erlang BGP daemon
* [sheyll/erlymock](https://github.com/sheyll/erlymock) - An EasyMock inspired mocking library for erlang.
* [RJ/erlang-reup](https://github.com/RJ/erlang-reup) - Watches for .erl & .hrl changes, recompiles and reloads. You know, for development.
* [project-fifo/ensq](https://github.com/project-fifo/ensq) - NSQ Client for erlang
* [odo/nested](https://github.com/odo/nested) - a library to handle nested Erlang maps
* [metachord/mctrace](https://github.com/metachord/mctrace) - Trace Erlang process messages easy
* [litaocheng/gen-erl-app](https://github.com/litaocheng/gen-erl-app) - the script to generate an erlang app skeleton
* [klarna/kafka_protocol](https://github.com/klarna/kafka_protocol) - Kafka protocol erlang library
* [keymone/wower](https://github.com/keymone/wower) - yet another world of warcraft server emulator. implemented in Erlang for fun and learning.
* [jkakar/aws-erlang](https://github.com/jkakar/aws-erlang) - AWS clients for Erlang
* [jarrodhroberson/inet_mdns](https://github.com/jarrodhroberson/inet_mdns) - Bonjour / Zeroconf in Erlang
* [higepon/memcached-client](https://github.com/higepon/memcached-client) - A memcached client library for Erlang.
* [gossiperl/erflux](https://github.com/gossiperl/erflux) - InfluxDB client for Erlang
* [erlymon/erlymon](https://github.com/erlymon/erlymon) - Open Source GPS Tracking System
* [erlware-deprecated/ktuo](https://github.com/erlware-deprecated/ktuo) - json encoder/decoder for Erlang
* [daleharvey/erlang_util](https://github.com/daleharvey/erlang_util) - Collection of random handy erlang scripts
* [bwegh/awre](https://github.com/bwegh/awre) - A wamp.ws client written in erlang
* [bmizerany/redis-erl](https://github.com/bmizerany/redis-erl) - Minimilast Redis Client for Erlang
* [artefactop/elibphonenumber](https://github.com/artefactop/elibphonenumber) - Erlang port for use libphonenumber from erlang
* [archaelus/errd](https://github.com/archaelus/errd) - Erlang RRDTool library
* [AdRoll/erlmld](https://github.com/AdRoll/erlmld) - erlang interface to kinesis client library via MultiLangDaemon
* [wardbekker/Erltricity](https://github.com/wardbekker/Erltricity) - An Erlang Client library for the ThinkGear Socket Protocol
* [syed/erlcscope](https://github.com/syed/erlcscope) - Program which builds cscope database for erlang files
* [spawnproc/forms](https://github.com/spawnproc/forms) - Erlang Business Documents Generator
* [sile/hash_ring](https://github.com/sile/hash_ring) - Implements consistent hashing in Erlang
* [rschlaikjer/erlang-atrace-flamegraphs](https://github.com/rschlaikjer/erlang-atrace-flamegraphs) - Generate flamegraphs from Android method trace files
* [rambocoder/unistring](https://github.com/rambocoder/unistring) - Unicode utf-8 functions for Erlang


* [milindparikh/erlkafka](https://github.com/milindparikh/erlkafka) - erlkafka is a kafka client written in erlang
* [michaelmelanson/spider](https://github.com/michaelmelanson/spider) - A web spider written in Erlang. Initial support for document clustering.
* [madtrick/wsecli](https://github.com/madtrick/wsecli) - Erlang WebSockets client
* [m-2k/erlach](https://github.com/m-2k/erlach) - ☣⚫⚫ SPA Imageboad on WebSockets written on Erlang
* [jlouis/erlang-utp](https://github.com/jlouis/erlang-utp) - uTP implementation in Erlang
* [jaxl/ebosh](https://github.com/jaxl/ebosh) - BOSH (bidirectional stream over http) connection manager written on top of Erlang OTP
* [fhunleth/relsync](https://github.com/fhunleth/relsync) - Synchronize Erlang/OTP releases to remote nodes
* [erlware-deprecated/gen_socket](https://github.com/erlware-deprecated/gen_socket) - Generic Socket support for Erlang
* [barrel-db/hlc](https://github.com/barrel-db/hlc) - hlc - Hybrid Logical Clock in Erlang.
* [arrowcircle/erlypusher](https://github.com/arrowcircle/erlypusher) - Erlang server for pusher app

* [tongdao/eredis_cluster](https://github.com/tongdao/eredis_cluster) - eredis_cluster is an erlang wrapper for eredis to support cluster mode of redis 3.0.0+
* [aetrion/erl-dns](https://github.com/aetrion/erl-dns) - DNS server, in erlang.
* [aetrion/dns_erlang](https://github.com/aetrion/dns_erlang) - Erlang DNS library
* [lk-geimfari/awesomo](https://github.com/lk-geimfari/awesomo) - An extensive list of interesting open source projects written in С, C++, Clojure, Lisp, Elixir, Erlang, Elm, Golang, Haskell, JavaScript, Lua, OCaml, Python, R, Ruby, Rust, Scala etc.
* [rabbitmq/erlang-data-structures](https://github.com/rabbitmq/erlang-data-structures) - Erlang Data Structures
* [matthiasl/eproxy](https://github.com/matthiasl/eproxy) - A TCP proxy written in Erlang
* [erlang-synrc/kvs.core](https://github.com/erlang-synrc/kvs.core) - Erlang Abstract Term Database
* [jfacorro/clojerl](https://github.com/jfacorro/clojerl) - Clojure for the Erlang VM
* [unbalancedparentheses/erlang-katana](https://github.com/unbalancedparentheses/erlang-katana) - :ok_hand: erlang grab bag of useful functions. it should have been called swiss army knife but katanas are more deadlier ;)
* [FelipeBB/rooster](https://github.com/FelipeBB/rooster) - Rest framework that runs on top of mochiweb
* [rabbitmq/looking-glass](https://github.com/rabbitmq/looking-glass) - An experimental Erlang/Elixir/BEAM profiler tool

* [spawngrid/mimetypes](https://github.com/spawngrid/mimetypes) - Erlang MIME types library
* [inaka/match_stream](https://github.com/inaka/match_stream) - A sample project to show in our scale blog post
* [lenary/idris-erlang](https://github.com/lenary/idris-erlang) - Erlang Backend for Idris Compiler
* [exercism/xerlang](https://github.com/exercism/xerlang) - Exercism exercises in Erlang.
* [davisp/jiffy](https://github.com/davisp/jiffy) - JSON NIFs for Erlang
* [robertoaloi/erlang-sandbox](https://github.com/robertoaloi/erlang-sandbox) - An Experimental Sandbox for Erlang
* [klarna/tulib](https://github.com/klarna/tulib) - Standard Erlang library.
* [GOFactory/erleans](https://github.com/GOFactory/erleans) - Erlang Orleans
* [tjarvstrand/edts](https://github.com/tjarvstrand/edts) - Erlang Development Tool Suite
* [bisphone/Queuesk](https://github.com/bisphone/Queuesk) - Priority Task Queue for Erlang
* [Licenser/dhcp](https://github.com/Licenser/dhcp) - erlang dhcp server
* [tangyi1989/erl_game_server](https://github.com/tangyi1989/erl_game_server) - Erlang game server framework for fun.
* [rwbr/exmlrpc](https://github.com/rwbr/exmlrpc) - An HTTP 1.1 compliant XML-RPC library for Erlang
* [nygge/pran](https://github.com/nygge/pran) - Protocol Analyzer written in Erlang
* [mrinalwadhwa/eamf](https://github.com/mrinalwadhwa/eamf) - eAMF provides Action Message Format (AMF) support for Erlang
* [mojombo/erlang_pipe](https://github.com/mojombo/erlang_pipe) - A pipe implementation in pure Erlang
* [lemenkov/esipua](https://github.com/lemenkov/esipua) - Mirror or Erlang SIP UA library, based on Yxa.
* [goj/escalus](https://github.com/goj/escalus) - Erlang library for convenient testing of XMPP servers
* [erlware/relcool](https://github.com/erlware/relcool) - Release creation for Erlang
* [dweldon/estring](https://github.com/dweldon/estring) - string manipulation library for erlang
* [cooldaemon/ermlia](https://github.com/cooldaemon/ermlia) - The ermlia is Erlang implementation of Kademlia. This is easy key-value store.
* [charpi/erl_selenium](https://github.com/charpi/erl_selenium) - An Erlang version of Selenium remote control
* [archaelus/erms](https://github.com/archaelus/erms) - Catalyst IT Ltd's Erlang SMS Routing and Messaging system
* [wil/erlstatsd](https://github.com/wil/erlstatsd) - Erlang client for StatsD

* [thomasl/smart_exceptions](https://github.com/thomasl/smart_exceptions) - A code transform to improve Erlang exception reporting
* [rustyio/BinaryVice](https://github.com/rustyio/BinaryVice) - BinaryVice is better than term_to_binary/1 at serializing structured Erlang data.
* [nox/shippai](https://github.com/nox/shippai) - A Core Erlang transform to enhance match failures
* [mcaprari/peasy-torrent-tracker](https://github.com/mcaprari/peasy-torrent-tracker) - A torrent tracker written in Erlang
* [marcelog/simple_cache](https://github.com/marcelog/simple_cache) - Small erlang simple cache using ETS to wrap your methods with
* [kevsmith/reddy](https://github.com/kevsmith/reddy) - Exploring writing a redis client in Erlang
* [hyperthunk/fastlog](https://github.com/hyperthunk/fastlog) - Fast Logging Library for Erlang/OTP
* [gar1t/port_server](https://github.com/gar1t/port_server) - A super simple framework for extending Erlang supervision to external apps

* [derniercri/coers](https://github.com/derniercri/coers) - A small library for coercion to primitive Erlang types.
* [comptekki/esysman](https://github.com/comptekki/esysman) - Erlang Computer Systems Management Console
* [campanja/ezk](https://github.com/campanja/ezk) - Erlang-Bindings for Zookeeper
* [brendonh/erl_id3v2](https://github.com/brendonh/erl_id3v2) - Erlang id3v2 reader
* [bjorng/esdl](https://github.com/bjorng/esdl) - Esdl is a legacy library for accessing SDL and OpenGL from Erlang. (New applications are better off using wx in Erlang/OTP R13B.)

* [alavrik/piqi-rpc](https://github.com/alavrik/piqi-rpc) - RPC-over-HTTP system for Erlang supporting JSON, XML and Protocol Buffers
* [afiskon/erlang-simplicitydb](https://github.com/afiskon/erlang-simplicitydb) - SimplicityDB, simple file based key-value storage in pure Erlang
* [tim/erlang-idna](https://github.com/tim/erlang-idna) - A pure Erlang IDNA implementation
* [sthadka/fuge](https://github.com/sthadka/fuge) - An Erlang library for carefully refactoring critical paths
* [rcouch/ecsv](https://github.com/rcouch/ecsv) - Erlang CSV Parser


* [onlyshk/epmail](https://github.com/onlyshk/epmail) - epmail - mail system in Erlang
* [odo/ballermann](https://github.com/odo/ballermann) - A simple load balancer for Erlang processes
* [NetComposer/nkservice](https://github.com/NetComposer/nkservice) - Erlang Services Management
* [maxlapshin/nfs3](https://github.com/maxlapshin/nfs3) - NFS v3 client for erlang servers
* [marianoguerra/interfix](https://github.com/marianoguerra/interfix) - an experimental programming language for the erlang vm that is actually useful
* [Licenser/eplugin](https://github.com/Licenser/eplugin) - An erlang plugin manager
* [kakaranet/monitor](https://github.com/kakaranet/monitor) - Kakaranet SNMP Monitoring Erlang Application
* [hypernumbers/erlmarkdown](https://github.com/hypernumbers/erlmarkdown) - An implementation of markdown written in Erlang

* [gar1t/erlang-redis](https://github.com/gar1t/erlang-redis) - Erlang bindings for Redis
* [FabioBatSilva/efrisby](https://github.com/FabioBatSilva/efrisby) - A REST API testing framework for erlang
* [extend/goldrush](https://github.com/extend/goldrush) - @deprecated Small, Fast event processing and monitoring for Erlang/OTP applications.
* [erldb/erldb](https://github.com/erldb/erldb) - ORM implementation in Erlang
* [emedia-project/erlffmpeg](https://github.com/emedia-project/erlffmpeg) - ffmpeg for erlang
* [davide/erl_img](https://github.com/davide/erl_img) - Erlang image processing stuff (bmp, gif, jpeg, png, xpm, tiff, mpeg) - based on jungerl's erl_img-1.6
* [danw/edhcp](https://github.com/danw/edhcp) - DHCP Server written in Erlang
* [couchbaselabs/erlgeom](https://github.com/couchbaselabs/erlgeom) - Erlang binding for geometry libraries
* [arcusfelis/binary2](https://github.com/arcusfelis/binary2) - Binary functions for Erlang (trim, reverse, bxor, band)
* [archaelus/erlydtl](https://github.com/archaelus/erlydtl) - Django Template for Erlang
* [apauley/sudoku-in-erlang](https://github.com/apauley/sudoku-in-erlang) - An implementation of Norvig's sudoku solver in Erlang
* [afternoon/rolf](https://github.com/afternoon/rolf) - Munin-like monitoring system in Erlang
* [zuiderkwast/jsonrpc2-erlang](https://github.com/zuiderkwast/jsonrpc2-erlang) - JSON-RPC 2.0 for Erlang
* [zhongwencool/erlang-2048-game](https://github.com/zhongwencool/erlang-2048-game) - 2048 game  base on pure erlang
* [vjache/erlang-logmachine](https://github.com/vjache/erlang-logmachine) - A backend system for event logging, real time analisys and decision assistance.
* [tonyrog/edrone](https://github.com/tonyrog/edrone) - AR drone for Erlang
* [stolen/pipeline](https://github.com/stolen/pipeline) - Erlang pipeline parse_transform allowing to apply list of functions
* [spawngrid/erel](https://github.com/spawngrid/erel) - Erlang Release Framework (in the early development phase)
* [si14/z_validate](https://github.com/si14/z_validate) - Generic validation helpers for Erlang
* [schleyfox/erlang_ann](https://github.com/schleyfox/erlang_ann) - Simple Neural Network in Erlang (based on http://www.trapexit.org/Erlang_and_Neural_Networks)
* [noss/ifastcgi](https://github.com/noss/ifastcgi) - A FastCGI server in Erlang
* [msgpack-rpc/msgpack-rpc-erlang](https://github.com/msgpack-rpc/msgpack-rpc-erlang) - RPC with MessagePack in Erlang/OTP
* [msantos/wierl](https://github.com/msantos/wierl) - Erlang interface for manipulating 802.11 wireless devices
* [mrallen1/erlang-n-go](https://github.com/mrallen1/erlang-n-go) - Sample code for February 2016 Houston Golang Meetup
* [mochi/eswf](https://github.com/mochi/eswf) - eswf is a pure Erlang library for dealing with Adobe SWF files and related data formats.
* [mlodzianck/webrtc-sig-server](https://github.com/mlodzianck/webrtc-sig-server) - Signalling server for web-rtc-app written in Erlang
* [mattsta/cbuf](https://github.com/mattsta/cbuf) - Erlang Circular Buffer/List/LIFO Queue using ETS
* [lemenkov/erlstund](https://github.com/lemenkov/erlstund) - An educational STUN/TURN/ICE server written in Erlang
* [JonGretar/erlang_user_utilities](https://github.com/JonGretar/erlang_user_utilities) - A collection of handy user utilities for the Erlang shell.
* [jeremyong/eprotoc](https://github.com/jeremyong/eprotoc) - Erlang proto file parser and code generator
* [iriscouch/erlang-request](https://github.com/iriscouch/erlang-request) - The Node.js request API for Erlang
* [inaka/itweet](https://github.com/inaka/itweet) - Twitter Stream API on ibrowse
* [habibutsu/erlz](https://github.com/habibutsu/erlz) - Set of helpers functions for more convenient functional programming in Erlang
* [FlowForwarding/enetconf](https://github.com/FlowForwarding/enetconf) - NETCONF Library for Erlang
* [essiene/smpp34](https://github.com/essiene/smpp34) - An smpp34 library in Erlang. Built on top of smpp34pdu PDU parsing library
* [esl/tracerl](https://github.com/esl/tracerl) - Dynamic tracing tests and utilities for Erlang/OTP
* [erlware/epax](https://github.com/erlware/epax) - Erlang Package Manager
* [dizzyd/stats](https://github.com/dizzyd/stats) - Erlang Statistics Library
* [dieswaytoofast/app_cache](https://github.com/dieswaytoofast/app_cache) - mnesia management toolset, with caching built-in (erlang)
* [chovencorp/erlangzmq](https://github.com/chovencorp/erlangzmq) - Native Erlang implementation of ZeroMQ Message Transport Protocol.
* [bsmr-erlang/nodefinder](https://github.com/bsmr-erlang/nodefinder) - Erlang/OTP nodefinder (imported from http://code.google.com/p/nodefinder/)
* [brainly/hive](https://github.com/brainly/hive) - Hive is a scalable Comet/PUSH application server written in Erlang that allows you to create or integrate various Comet services into your WebApps. It supports lot’s of plugins and can easily communicate and seamlessly integrate into existing backends using HTTP or TCP!
* [biokoda/detest](https://github.com/biokoda/detest) - Tool for running tests on a cluster of erlang nodes
* [b3rnie/crontab](https://github.com/b3rnie/crontab) - crontab for Erlang
* [amtal/lfe_utils](https://github.com/amtal/lfe_utils) - Utilities for expressive functional programming on the Erlang VM.
* [AlainODea/erlang_git](https://github.com/AlainODea/erlang_git) - Pure Erlang Implementation of Git
* [2nth0nyj/ErlangGameServer](https://github.com/2nth0nyj/ErlangGameServer) - Deprecated.
* [yzh44yzh/dp-push](https://github.com/yzh44yzh/dp-push) - Erlang library for working with Apple Push Notification Service from dieselpuppet.com
* [tsloughter/eoauth2](https://github.com/tsloughter/eoauth2) - Erlang OAuth2
* [tonyfabeen/http-routing-mesh](https://github.com/tonyfabeen/http-routing-mesh) - Http Routing Mesh in Erlang
* [thepug/erlngram](https://github.com/thepug/erlngram) - An erlang implementation of ngram language detection.
* [StoneCypher/htstub](https://github.com/StoneCypher/htstub) - The HtStub erlang webserver
* [sinasamavati/mad](https://github.com/sinasamavati/mad) - Dependency manager for Erlang
* [si14/erl_json_test](https://github.com/si14/erl_json_test) - a little test of various Erlang JSON libraries
* [russ/openpoker](https://github.com/russ/openpoker) - A scalable poker server written in Erlang
* [rpip/fakerl](https://github.com/rpip/fakerl) - Erlang application for generating fake data [WIP]
* [richcarl/syntax_tools](https://github.com/richcarl/syntax_tools) - Erlang syntax tools, a library for working with abstract syntax trees. This is the canonical development repository.
* [richcarl/berk](https://github.com/richcarl/berk) - A benchmarking library for Erlang
* [pichi/epexercises](https://github.com/pichi/epexercises) - Erlang Programming Exercises
* [msantos/stk500](https://github.com/msantos/stk500) - Enough of the STK500 protocol in Erlang to control the Arduino boot loader
* [msantos/seds](https://github.com/msantos/seds) - Erlang socket over DNS tunnel server
* [loucash/eqm](https://github.com/loucash/eqm) - Erlang pub sub with supply-demand channels
* [liveforeverx/ratx](https://github.com/liveforeverx/ratx) - Rate limiter and overload protection for erlang application
* [jashmenn/gen_server_mock](https://github.com/jashmenn/gen_server_mock) - erlang mocking for gen_server (gen_server mock)
* [inaka/tirerl](https://github.com/inaka/tirerl) - Erlang interface to Elastic Search
* [inaka/pusherman](https://github.com/inaka/pusherman) - queuing system for push notifications
* [hyperthunk/appstart](https://github.com/hyperthunk/appstart) - An Erlang/OTP Application Startup Utility
* [gmr/strftimerl](https://github.com/gmr/strftimerl) - Erlang implementation of strftime
* [ferd/howistart-erlang1-code](https://github.com/ferd/howistart-erlang1-code) - Code for my tutorial on howistart.org
* [esl/erl_fuzzy_match](https://github.com/esl/erl_fuzzy_match) - Erlang Fuzzy String Matcher
* [erlware/uri](https://github.com/erlware/uri) - uri parsing module for Erlang
* [dmitryme/erlang_fast](https://github.com/dmitryme/erlang_fast) - FIX/FAST decode/encode facility
* [davisp/knit](https://github.com/davisp/knit) - Another Erlang Release/Upgrade Tool
* [chef/mini_s3](https://github.com/chef/mini_s3) - Minimal AWS S3 client for Erlang
* [blt/beat](https://github.com/blt/beat) - A hackday project for Erlang/OTP pedagogy.
* [basho/columbo](https://github.com/basho/columbo) - Columbo - the dependency detective - will highlight 3rd party dependency problems in your Erlang programs.
* [AstRonin/sgi](https://github.com/AstRonin/sgi) - Socket Gateway Interface
* [artefactop/ejwt](https://github.com/artefactop/ejwt) - erlang library for JSON Web Token
* [andelf/baiduhi](https://github.com/andelf/baiduhi) - baiduhi client, erlang version
* [yrashk/erlang](https://github.com/yrashk/erlang) - Erlang with extra unofficial patches (see branches for patches in development, alterline for merged patches)
* [snaiper80/hashids-erlang](https://github.com/snaiper80/hashids-erlang) - The Erlang port of Hashid to generate YouTube-like hashids from one or many numbers.
* [rustyio/ErlangRPCDemo](https://github.com/rustyio/ErlangRPCDemo) - Demo code for ErlangDC 2011 Conference (http://erlangdc.com)
* [mrijkeboer/euuid](https://github.com/mrijkeboer/euuid) - Erlang UUID module (versions 1, 3, 4, 5).
* [Joony/erlang-nitrogen-user-login](https://github.com/Joony/erlang-nitrogen-user-login) - A simple user login example using Nitrogen
* [inaka/zipper](https://github.com/inaka/zipper) - Generic Zipper implementation in Erlang
* [hpyhacking/erlang-programming](https://github.com/hpyhacking/erlang-programming) - "Erlang Programming" Book's exec.
* [s1n4/leptus](https://github.com/s1n4/leptus) - Erlang REST framework that runs on top of cowboy
* [chovencorp/chumak](https://github.com/chovencorp/chumak) - Pure Erlang implementation of ZeroMQ Message Transport Protocol.
* [uwiger/toker](https://github.com/uwiger/toker) - Patches Erlang compiler with pluggable token transformers and parsers
* [tomas-abrahamsson/tdiff](https://github.com/tomas-abrahamsson/tdiff) - Diff algorithm in Erlang
* [s1n4/mad](https://github.com/s1n4/mad) - Dependency manager for Erlang
* [jlouis/erl-glicko2](https://github.com/jlouis/erl-glicko2) - Glicko 2 ranking for Erlang
* [yzh44yzh/erl-proj-tpl](https://github.com/yzh44yzh/erl-proj-tpl) - This is typical structure for erlang projects.
* [twonds/erl_scribe](https://github.com/twonds/erl_scribe) - Erlang scribe client documentation
* [kennystone/strftimerl](https://github.com/kennystone/strftimerl) - strftime for erlang
* [jcomellas/mlapi](https://github.com/jcomellas/mlapi) - MercadoLibre API Client in Erlang
* [erlang-synrc/cms](https://github.com/erlang-synrc/cms) - Experimental CMS wirtten in Erlang
* [CloudI/CloudI](https://github.com/CloudI/CloudI) - A Cloud at the lowest level!
* [chef/erchef](https://github.com/chef/erchef) - DEPRECATED: Erlang based Chef Server top-level OTP release project
* [barrel-db/hooks](https://github.com/barrel-db/hooks) - generic plugin & hook system for Erlang applications
* [lk-geimfari/smokkfiskur](https://github.com/lk-geimfari/smokkfiskur) - Small library for colored (ANSI) output in Erlang. It's can be very useful when you need to create a command-line application.
* [ricardobcl/ETScache](https://github.com/ricardobcl/ETScache) - A simple erlang in-memory cache
* [Prots/olifer](https://github.com/Prots/olifer) - LIVR implementation for Erlang
* [mmullis/coverize](https://github.com/mmullis/coverize) - Erlang Coverage Analysis Made Easy!
* [matpalm/median](https://github.com/matpalm/median) - erlang experiment in distributed median finding
* [loucash/josser](https://github.com/loucash/josser) - Json Schema Generator Erlang
* [jj1bdx/erltrek](https://github.com/jj1bdx/erltrek) - An Erlang Star Trek game
* [ivaniacono/ebuggy](https://github.com/ivaniacono/ebuggy) - Demonstrator system for Erlang/ALE
* [basho/nifwait](https://github.com/basho/nifwait) - Utility to test effect of blocking NIFs on Erlang scheduler
* [meatinleather/lol](https://github.com/meatinleather/lol) - Lol — Lisp on erLang, and programming is fun again
* [rprimus/plists](https://github.com/rprimus/plists) - Fork: Drop in replacement for Erlang module lists,  where most lists operations are parallel.
* [mochi/beambag](https://github.com/mochi/beambag) - beambag is an erlang library for using beam files as a quasi-static in-memory data store.
* [lukegalea/inflector](https://github.com/lukegalea/inflector) - Inflector.erl: Rails Style String Inflection For Erlang
* [kevsmith/membox](https://github.com/kevsmith/membox) - Redis-like storage server written in Erlang
* [jkvor/excavator](https://github.com/jkvor/excavator) - An Erlang application for ingesting data from various sources (APIs, data feeds, web content, etc)
* [grogers0/erl_finger_trees](https://github.com/grogers0/erl_finger_trees) - Erlang module for finger trees - annotated sequences with amortized constant time insertion/deletion from the ends
* [ferd/hubble](https://github.com/ferd/hubble) - create, read, and update deep Erlang data structures, accessible through explicit paths.
* [processone/xml](https://github.com/processone/xml) - Fast Expat based Erlang XML parsing library
* [ostrovok-team/ejsonpath](https://github.com/ostrovok-team/ejsonpath) - JSONPath Erlang implementation
* [jkvor/hacking_erlang](https://github.com/jkvor/hacking_erlang) - Hacking Erlang through Preprocessing Presentation for EUC 2009
* [ian-plosker/seq-erlang](https://github.com/ian-plosker/seq-erlang) - Lazy sequences for Erlang
* [fredrikt/erlang-yubico](https://github.com/fredrikt/erlang-yubico) - Erlang client implementing the Yubico Validation Protocol Version 2.0.
* [eolo999/Italian-Erlang-User-Group](https://github.com/eolo999/Italian-Erlang-User-Group) - Italian Erlang User Group Site

* [brunorijsman/erlang-bgp](https://github.com/brunorijsman/erlang-bgp) - An implementation of BGP (RFC 4271) written in Erlang (only < 10% done)
* [bpuzon/eastrisk](https://github.com/bpuzon/eastrisk) - An Erlang interface to Asterisk.
* [arcusfelis/xapian-erlang-bindings](https://github.com/arcusfelis/xapian-erlang-bindings) - Xapian binding for Erlang (GSOC2012 project)
* [goertzenator/erlang_nif-sys](https://github.com/goertzenator/erlang_nif-sys) - Low level bindings to Erlang NIF API for Rust
* [cstar/erlsdb](https://github.com/cstar/erlsdb) - erlang library for accessing SimpleDB
* [trung/erling](https://github.com/trung/erling) - AMF Implementation written in Erlang
* [qingliangcn/mslog](https://github.com/qingliangcn/mslog) - a simple and easy to use erlang log app
* [janl/erl-jsonpointer](https://github.com/janl/erl-jsonpointer) - JSON Pointer implementation for Erlang
* [goj/cuesport](https://github.com/goj/cuesport) - simple Erlang pool of workers
* [freza/audit_log](https://github.com/freza/audit_log) - Audit logging application for Erlang.
* [Etsukata/erlang_websocket_server](https://github.com/Etsukata/erlang_websocket_server) - WebSocket Server implementation in Erlang.
* [boorad/erlimap](https://github.com/boorad/erlimap) - Simple IMAP library for Erlang (work in progress...)
* [baphled/chatterl](https://github.com/baphled/chatterl) - Sinan based chat system built in Erlang
* [j14159/mlfe](https://github.com/j14159/mlfe) - ML Flavoured Erlang
* [vjache/elips](https://github.com/vjache/elips) - Erlang Language Integrated Production System (ELIPS) library.
* [spawngrid/typespecs](https://github.com/spawngrid/typespecs) - Erlang typespecs toolkit
* [massemanet/abets](https://github.com/massemanet/abets) - Append-only B+tree Erlang Term Storage (pure disk based)
* [heroku/edump](https://github.com/heroku/edump) - Erlang Crashdump Analysis Library
* [graeme-defty/jaderl](https://github.com/graeme-defty/jaderl) - An implementation of the Jade templating language in Erlang
* [gburd/hamt](https://github.com/gburd/hamt) - Ideal Hash Array Mapped Tries: an Erlang functional datatype
* [dustalov/plists](https://github.com/dustalov/plists) - An Erlang module for doing list operations in parallel (svn mirror)
* [aerosol/eco](https://github.com/aerosol/eco) - Flexible Erlang Configuration Server
* [basho/lager](https://github.com/basho/lager) - A logging framework for Erlang/OTP
* [vances/radierl](https://github.com/vances/radierl) - RADIUS protocol stack for Erlang.
* [ngmoco/ngproc](https://github.com/ngmoco/ngproc) - Distributed process registry in Erlang
* [jasondavies/emdns](https://github.com/jasondavies/emdns) - Bonjour/Zeroconf/mDNS in Erlang
* [andyfinnell/kalerl](https://github.com/andyfinnell/kalerl) - An Erlang implementation of the Kaleidoscope language from the LLVM tutorial.
* [marianoguerra/match](https://github.com/marianoguerra/match) - [kept for historical reasons, see efene] a calculator implemented in erlang that will turn into a toy language if I have time
* [JoeOsborn/lergic](https://github.com/JoeOsborn/lergic) - An embedded datalog-like logic programming DSL for Erlang.
* [devaspot/syncml](https://github.com/devaspot/syncml) - SyncML OMA/DS server written in Erlang
* [burbas/Minecraft-sERLver](https://github.com/burbas/Minecraft-sERLver) - Distributed Minecraft server written in erlang
* [ahf/ircd-pony](https://github.com/ahf/ircd-pony) - A concurrent ircd written in Erlang.
* [chitika/cberl](https://github.com/chitika/cberl) - NIF based Erlang bindings for Couchbase
* [b0oh/lol](https://github.com/b0oh/lol) - Lol — Lisp on erLang, and programming is fun again
* [msantos/epcap](https://github.com/msantos/epcap) - Erlang packet capture interface using pcap
* [HaruAtari/erlang-for-the-little-ones](https://github.com/HaruAtari/erlang-for-the-little-ones) - Учебник по Erlang для самых маленьких (на русском)
* [nialscorva/erlymock](https://github.com/nialscorva/erlymock) - A mocking framework for Erlang.

* [stepankuzmin/erlang-dropbox](https://github.com/stepankuzmin/erlang-dropbox) - Dropbox API for Erlang
* [snoopaloop/erl_hs](https://github.com/snoopaloop/erl_hs) - HandlerSocket in Erlang
* [rodjek/erlesque](https://github.com/rodjek/erlesque) - Pure Erlang Resque worker
* [maxlapshin/vkontakte](https://github.com/maxlapshin/vkontakte) - Erlang vkontakte binding
* [litaocheng/erlips](https://github.com/litaocheng/erlips) - erlang ip web services
* [kuenishi/fluent-logger-erlang](https://github.com/kuenishi/fluent-logger-erlang) - Moved.
* [egobrain/tq_transform](https://github.com/egobrain/tq_transform) - Easy erlang model builder
* [domnikl/statsd-erlang](https://github.com/domnikl/statsd-erlang) - an Erlang client for statsd
* [benoitc/upnp](https://github.com/benoitc/upnp) - Erlang UPNP Module
* [goertzenator/ruster_unsafe](https://github.com/goertzenator/ruster_unsafe) - Low level bindings to Erlang NIF API for Rust
* [wrboyce/erb](https://github.com/wrboyce/erb) - Erlang/OTP IRC Bot Framework
* [robertoaloi/skerleton](https://github.com/robertoaloi/skerleton) - Bootstrap a brand new Erlang project in seconds.
* [rackerlabs/gen_batch](https://github.com/rackerlabs/gen_batch) - A batch job running library for embedded Erlang/OTP.
* [plux/docopt-erl](https://github.com/plux/docopt-erl) - Port of docopt for Erlang
* [otakup0pe/magicbeam](https://github.com/otakup0pe/magicbeam) - A small yet stylish assortment of (hopefully) easy to use utilities for the modern Erlang/OTP system
* [oscarh/gen_httpd](https://github.com/oscarh/gen_httpd) - Intended to be a lightweight HTTP server layer for Erlang applications.
* [okeuday/reltool_util](https://github.com/okeuday/reltool_util) - Erlang reltool utility functionality application
* [maxlapshin/record2ei](https://github.com/maxlapshin/record2ei) - Generates erl_interface code to decode erlang record based on their spec
* [jkvor/rbuddy](https://github.com/jkvor/rbuddy) - redis buddy (an Erlang replication proxy that helps facilitate redis slave failover)
* [jashmenn/gen_cluster](https://github.com/jashmenn/gen_cluster) - `gen_cluster` is an erlang behavior for pid clustering. It is a cascading behavior that builds on `gen_server`.
* [heroku/gobo](https://github.com/heroku/gobo) - Erlang client for Doozer
* [fjl/tetrapak](https://github.com/fjl/tetrapak) - An extensible build system for Erlang/OTP applications
* [baryluk/ral](https://github.com/baryluk/ral) - Random Access Lists for Erlang (based on Sparse Skew Binary Numbers)
* [ThomasHabets/weberl](https://github.com/ThomasHabets/weberl) - Like web.py, but for Erlang
* [2garryn/esli](https://github.com/2garryn/esli) - Web-links shortener on erlang
* [zpeters/ErlangOtpTemplate](https://github.com/zpeters/ErlangOtpTemplate) - A sample Erlang OTP Template
* [tim/erlang-streams](https://github.com/tim/erlang-streams) - An Erlang module for working with streams
* [nbowe/erlang_decorators](https://github.com/nbowe/erlang_decorators) - An example implementation of Python style decorators in Erlang
* [kbarber/erlang-mdigraph](https://github.com/kbarber/erlang-mdigraph) - Erlang Digraph library that uses mnesia as a backend
* [djui/erlang-rest-client](https://github.com/djui/erlang-rest-client) - Erlang REST Client
* [andrenth/erlang-exif](https://github.com/andrenth/erlang-exif) - EXIF reader for Erlang
* [inaka/edis](https://github.com/inaka/edis) - An Erlang implementation of Redis
* [gleber/erlcloud](https://github.com/gleber/erlcloud) - Cloud Computing library for erlang (Amazon EC2, S3, SQS, SimpleDB, Mechanical Turk, ELB)
* [kalta/nksip](https://github.com/kalta/nksip) - Erlang SIP application server
* [rebar/rebar3](https://github.com/rebar/rebar3) - Erlang build tool that makes it easy to compile and test Erlang applications and releases.
* [msantos/procket](https://github.com/msantos/procket) - Erlang interface to low level socket operations
* [klarna/jesse](https://github.com/klarna/jesse) - jesse (JSon Schema Erlang) is an implementation of a json schema validator for Erlang.
* [unbalancedparentheses/gut](https://github.com/unbalancedparentheses/gut) - :scroll: gut is a template printing, aka scaffolding, tool for Erlang. Like rails generate or yeoman
* [Nekso/nkcluster](https://github.com/Nekso/nkcluster) - A framework to manage jobs at huge Erlang clusters
* [Nekso/nkdocker](https://github.com/Nekso/nkdocker) - Erlang Docker client
* [Nekso/nkpacket](https://github.com/Nekso/nkpacket) - Generic Erlang transport layer
* [Nekso/nkdist](https://github.com/Nekso/nkdist) - Erlang distributed processes
* [synrc/feeds](https://github.com/synrc/feeds) - Erlang Social Feeds and Cache Server
* [5HT/om](https://github.com/5HT/om) - Erlang with Types Proposal
* [shortishly/erlang-mdns](https://github.com/shortishly/erlang-mdns) - MDNS in Erlang

* [talko/httpcbench](https://github.com/talko/httpcbench) - Erlang HTTP client benchmarks
* [synrc/sh](https://github.com/synrc/sh) - Erlang Shell Executor
* [refuge/hlc](https://github.com/refuge/hlc) - hlc - Hybrid Logical Clock in Erlang.
* [youngkin/supervisiontest](https://github.com/youngkin/supervisiontest) - An Erlang demonstration of different supervision strategies along with different initialization strategies and failure scenarios
* [squidfunk/gpb-bindings](https://github.com/squidfunk/gpb-bindings) - Generate bindings for gpb, Protocol Buffers for Erlang
* [seven1240/VoiceEvents](https://github.com/seven1240/VoiceEvents) - A combination of Ruby/Rails gem and Erlang to subscribe/route/deliver FreeSWITCH events
* [seriyps/gettexter](https://github.com/seriyps/gettexter) - GNU-gettext compatible Erlang translation app.

* [kevsmith/baberl](https://github.com/kevsmith/baberl) - Erlang interface to libiconv
* [jvantuyl/erl-skel](https://github.com/jvantuyl/erl-skel) - Basic Skeleton Erlang Project
* [jinsky/etcher](https://github.com/jinsky/etcher) - An Erlang implementation of the Django Template Language
* [gmr/huesos-de-vaquero](https://github.com/gmr/huesos-de-vaquero) - A skeleton project for web development using Cowboy (Erlang) for back-end development and Google Web-Starter-Kit for front-end development
* [ghaskins/edist](https://github.com/ghaskins/edist) - Erlang (release) DISTribution framework
* [essiene/mmyn](https://github.com/essiene/mmyn) - An Erlang SMPP 3.4 Application gateway

* [bradfordw/pusherl](https://github.com/bradfordw/pusherl) - An Erlang interface for Pusher


* [Licenser/hamush](https://github.com/Licenser/hamush) - erlang based mush server
* [tsloughter/eindexer](https://github.com/tsloughter/eindexer) - Simple search engine written in Erlang
* [tel/snowflake](https://github.com/tel/snowflake) - Twitter's Snowflake UUID generator in Erlang.
* [samuel/erlang-gearman](https://github.com/samuel/erlang-gearman) - Gearman library for Erlang.
* [ngerakines/syslognif](https://github.com/ngerakines/syslognif) - A small nif to tap into syslog from an Erlang node.
* [msantos/perc](https://github.com/msantos/perc) - Erlang interface for controlling Unix processes
* [michaelmelanson/monsoon](https://github.com/michaelmelanson/monsoon) - An experimental P2P system in Erlang
* [massung/erlang_oauth_web](https://github.com/massung/erlang_oauth_web) - Erlang gen_fsm for web applications.
* [lstoll/heroku-erlang](https://github.com/lstoll/heroku-erlang) - erlang app on heroku
* [lpgauth/timing](https://github.com/lpgauth/timing) - Micro benchmarking library (erlang)
* [lemenkov/erlsyslog](https://github.com/lemenkov/erlsyslog) - Another one Erlang's syslog library.
* [kbarber/erlang-yaml](https://github.com/kbarber/erlang-yaml) - Erlang YAML encoder/decoder
* [jebu/websockets](https://github.com/jebu/websockets) - WebSockets server in Erlang
* [gar1t/erlang-kung-fu](https://github.com/gar1t/erlang-kung-fu) - Code from OSCON 2012 presentation Erlang Kung Fu In Three Hours
* [essiene/smpp34pdu](https://github.com/essiene/smpp34pdu) - SMPP 3.4 PDU library in erlang
* [djui/erlang-neo4j-rest-api](https://github.com/djui/erlang-neo4j-rest-api) - Neo4j REST API client
* [djui/ehf](https://github.com/djui/ehf) - Erlang Helper Functions
* [armon/Erlang-Naive-Bayes-Movies](https://github.com/armon/Erlang-Naive-Bayes-Movies) - An Erlang naive bayes text classifier to classify movie reviews as positive or negative.
* [Zert/amqp-erlang-sample](https://github.com/Zert/amqp-erlang-sample) - Sample of AMQP dispatcher and client
* [Ball/ErlangMud](https://github.com/Ball/ErlangMud) - It's a proto-mud in erlang
* [discoproject/disco](https://github.com/discoproject/disco) - a Map/Reduce framework for distributed computing
* [webmachine/webmachine](https://github.com/webmachine/webmachine) - A REST-based system for building web applications.
* [basho/rebar](https://github.com/basho/rebar) - ATTENTION: Please find the canonical repository here:
* [rabbitmq/rabbitmq-server](https://github.com/rabbitmq/rabbitmq-server) - RabbitMQ Server
* [synrc/n2o](https://github.com/synrc/n2o) - WebSocket Application Server
* [klacke/yaws](https://github.com/klacke/yaws) - Yaws webserver
* [heroku/logplex](https://github.com/heroku/logplex) - Heroku log router
* [basho/riak_core](https://github.com/basho/riak_core) - Distributed systems infrastructure used by Riak.
* [cloudozer/ling](https://github.com/cloudozer/ling) - Erlang on Xen
* [ninenines/ranch](https://github.com/ninenines/ranch) - Socket acceptor pool for TCP protocols.
* [couchbaselabs/iOS-Couchbase](https://github.com/couchbaselabs/iOS-Couchbase) - This repository fork is obsolete; the project's been restructured and development is going on in other repos. Please follow the link below, or read the current README.
* [couchbase/geocouch](https://github.com/couchbase/geocouch) - GeoCouch, a spatial index for CouchDB
* [ericmoritz/wsdemo](https://github.com/ericmoritz/wsdemo) - A Cowboy Websocket demo
* [basho/riak_cs](https://github.com/basho/riak_cs) - Riak CS is simple, available cloud storage built on Riak.
* [basho/bitcask](https://github.com/basho/bitcask) - because you need another a key/value storage engine

* [Asana/kraken](https://github.com/Asana/kraken) - Distributed Pubsub Server for Realtime Apps
* [basho/riak_kv](https://github.com/basho/riak_kv) - Riak Key/Value Store
* [thusfresh/switchboard](https://github.com/thusfresh/switchboard) - A framework for processing email using worker plugins.
* [auser/alice](https://github.com/auser/alice) - Monitoring and REST interface to rabbitmq
* [extend/bullet](https://github.com/extend/bullet) - Simple, reliable, efficient streaming for Cowboy.
* [krestenkrab/triq](https://github.com/krestenkrab/triq) - Trifork QuickCheck
* [erlyvideo/erlyvideo-old](https://github.com/erlyvideo/erlyvideo-old) - erlyvideo
* [tonyg/rabbithub](https://github.com/tonyg/rabbithub) - Experimental RabbitMQ PubSubHubBub interface
* [basho/yokozuna](https://github.com/basho/yokozuna) - Riak + Solr
* [rabbitmq/erlando](https://github.com/rabbitmq/erlando) - Erlando
* [rabbitmq/rmq-0mq](https://github.com/rabbitmq/rmq-0mq) - ZeroMQ support in RabbitMQ
* [rzezeski/try-try-try](https://github.com/rzezeski/try-try-try) - Ryan Zezeski's "working" blog
* [seth/pooler](https://github.com/seth/pooler) - An OTP Process Pool Application
* [davebryson/beepbeep](https://github.com/davebryson/beepbeep) - BeepBeep is a simple web application framework for Mochiweb inspired by Rails and Merb
* [ubf/ubf](https://github.com/ubf/ubf) - Universal Binary Format 2.2
* [marianoguerra/efene](https://github.com/marianoguerra/efene) - OFICIAL REPO IS AT https://github.com/efene/efene
* [extend/farwest](https://github.com/extend/farwest) - Modern web application development platform
* [joearms/ezwebframe](https://github.com/joearms/ezwebframe) - websockets framework toghter with cowboy as described in book
* [basho/riak_search](https://github.com/basho/riak_search) - Full-text search engine based on Riak
* [auser/beehive](https://github.com/auser/beehive) - Honeycombs of applications
* [kevsmith/gen_nb_server](https://github.com/kevsmith/gen_nb_server) - OTP behavior for writing non-blocking servers
* [hpyhacking/openpoker](https://github.com/hpyhacking/openpoker) - Genesis Texas hold'em Game Server
* [basho/riak_pipe](https://github.com/basho/riak_pipe) - Riak Pipelines
* [uwiger/locks](https://github.com/uwiger/locks) - A scalable, deadlock-resolving resource locker
* [hurricane/hurricane](https://github.com/hurricane/hurricane) - A scalable, extensible, distributed messaging system.
* [basho/cuttlefish](https://github.com/basho/cuttlefish) -  never lose your childlike sense of wonder baby cuttlefish, promise me?
* [ferd/erlpass](https://github.com/ferd/erlpass) - A library to handle password hashing and changing in a safe manner, independent from any kind of storage whatsoever.

* [RefactoringTools/wrangler](https://github.com/RefactoringTools/wrangler) - Import of the Wrangler svn repository.
* [tuulos/ringo](https://github.com/tuulos/ringo) - Distributed key-value storage a'la Amazon Dynamo
* [extend/sheriff](https://github.com/extend/sheriff) - Parse transform for type based validation.
* [seancribbs/riak_id](https://github.com/seancribbs/riak_id) - A clone of Twitter's Snowflake, built on riak_core
* [uwiger/unsplit](https://github.com/uwiger/unsplit) - Resolves conflicts in Mnesia after network splits
* [ricardobcl/Dotted-Version-Vectors](https://github.com/ricardobcl/Dotted-Version-Vectors) - Logical Clocks for Eventually Consistent Systems
* [aweber/pgsql-listen-exchange](https://github.com/aweber/pgsql-listen-exchange) - RabbitMQ Exchange that publishes messages received from PostgreSQL Notifications.
* [twilio/chessms](https://github.com/twilio/chessms) - Play Chess over SMS!
* [processone/ejabberd-contrib](https://github.com/processone/ejabberd-contrib) - Growing and curated ejabberd contributions repository - PR or ask to join !
* [basho/luwak](https://github.com/basho/luwak) - Large-object storage interface for Riak
* [wooga/locker](https://github.com/wooga/locker) - Atomic distributed "check and set" for short-lived keys
* [the-concurrent-schemer/scm](https://github.com/the-concurrent-schemer/scm) - The Concurrent Schemer
* [ChicagoBoss/tinymq](https://github.com/ChicagoBoss/tinymq) - TinyMQ - a diminutive, in-memory message queue
* [synrc/kvs](https://github.com/synrc/kvs) - Container and Iterator
* [jbrisbin/riak-exchange](https://github.com/jbrisbin/riak-exchange) - Custom RabbitMQ exchange type for sticking messages in Riak
* [yariv/twoorl](https://github.com/yariv/twoorl) - The source code repository for twoorl.com

* [basho/riak_function_contrib](https://github.com/basho/riak_function_contrib) - Riak Function Contrib
* [astro/prittorrent](https://github.com/astro/prittorrent) - BitTorrent Content Distribution for Podcasts
* [doubleyou/dps](https://github.com/doubleyou/dps) - Distributed pub-sub

* [tonyg/rabbiter](https://github.com/tonyg/rabbiter) - Microblogging using RabbitMQ and ejabberd
* [jadahl/mod_restful](https://github.com/jadahl/mod_restful) - RESTful interface to ejabberd
* [basho/mochiweb](https://github.com/basho/mochiweb) - a branch of Mochi Media's excellent HTTP library -- their canonical source can be found at http://code.google.com/p/mochiweb/
* [jbrisbin/rabbitmq-webhooks](https://github.com/jbrisbin/rabbitmq-webhooks) - RabbitMQ Webhooks Plugin
* [ocastalabs/CouchDB-XO_Auth](https://github.com/ocastalabs/CouchDB-XO_Auth) - Authorisation module for CouchDB against external OAuth providers (e.g. Twitter, Facebook)
* [ocastalabs/CouchDB-Facebook-Authentication](https://github.com/ocastalabs/CouchDB-Facebook-Authentication) - A CouchDB Authentication Module that uses Facebook API to authenticate users
* [2600hz-archive/whistle](https://github.com/2600hz-archive/whistle) - Scalable, distributed, cloud-based telephony platform
* [AF83/ucengine](https://github.com/AF83/ucengine) - U.C.Engine is a pubsub server with persistence. You can build realtime applications or integrate realtime features to existing applications.
* [bjorng/wings](https://github.com/bjorng/wings) - Wings3D is an advanced sub-division 3D modeller.

* [paulj/trapeze](https://github.com/paulj/trapeze) - Dynamic HTTP Routing and Load Balancing via AMQP
* [couchbase/couchdb](https://github.com/couchbase/couchdb) - CouchDB
* [iriscouch/browserid_couchdb](https://github.com/iriscouch/browserid_couchdb) - Mozilla BrowserID support plugin for CouchDB

* [CorticalComputer/DXNN2](https://github.com/CorticalComputer/DXNN2) - Topology and Parameter Evolving Universal Learning Network platform DXNN MK2
* [uwiger/jobs](https://github.com/uwiger/jobs) - Job scheduler for load regulation
* [leandrosilva/cameron](https://github.com/leandrosilva/cameron) - Cameron is an asynchronous, parallel, and REST-like workflow engine
* [membase/ns_server](https://github.com/membase/ns_server) - The Membase Server Superdupervisor.
* [benoitc/couchdbproxy](https://github.com/benoitc/couchdbproxy) - Simple multinode couchdb proxy
* [rabbitmq/rabbitmq-mqtt](https://github.com/rabbitmq/rabbitmq-mqtt) - RabbitMQ MQTT gateway
* [Loveice/PFAD](https://github.com/Loveice/PFAD) - Pearls of Functional Algorithm Design
* [helium/plumtree](https://github.com/helium/plumtree) - Epidemic Broadcast Trees
* [seth/rebar_lock_deps_plugin](https://github.com/seth/rebar_lock_deps_plugin) - Helper scripts to use with rebar
* [basho/wriaki](https://github.com/basho/wriaki) - A Riak-based Wiki-like application.
* [basho/riak_test](https://github.com/basho/riak_test) - I'm in your cluster, testing your riaks
* [yueyoum/codebattle-ai](https://github.com/yueyoum/codebattle-ai) - AI Example for Codebattle
* [rabbitmq/rabbitmq-auth-backend-http](https://github.com/rabbitmq/rabbitmq-auth-backend-http) - HTTP-based authorisation and authentication for RabbitMQ
* [basho/riaknostic](https://github.com/basho/riaknostic) - A diagnostic tool for Riak installations, to find common errors asap
* [Nekso/nkbase](https://github.com/Nekso/nkbase) - NkBASE distributed database
* [khellan/Pillow](https://github.com/khellan/Pillow) - Router and rereducer for sharded CouchDB
* [hyperthunk/annotations](https://github.com/hyperthunk/annotations) - Simple code instrumentation utilities
* [cstar/riak_redis_backend](https://github.com/cstar/riak_redis_backend) - Redis storage backend for Riak
* [bdionne/bitstore](https://github.com/bdionne/bitstore) - A document based ontology development environment
* [maxlapshin/fix](https://github.com/maxlapshin/fix) - http://fixprotocol.org/  implementation.
* [videlalvaro/rabbitmq-recent-history-exchange](https://github.com/videlalvaro/rabbitmq-recent-history-exchange) - RabbitMQ Recent History Exchange
* [thepug/Mod-Http-Pre-Bind](https://github.com/thepug/Mod-Http-Pre-Bind) - An ejabberd module that pre binds an anonymous sasl session, returning the authenticated session.
* [mochi/statebox_riak](https://github.com/mochi/statebox_riak) - Convenience library that makes it easier to use statebox with riak, extracted from best practices in our production code at Mochi Media.
* [basho/cluster_info](https://github.com/basho/cluster_info) - Fork of Hibari's nifty cluster_info OTP app
* [seancribbs/eunit_formatters](https://github.com/seancribbs/eunit_formatters) - Because eunit's output sucks. Let's make it better.
* [guedes/exjson](https://github.com/guedes/exjson) - JSON parser and genarator in Elixir.
* [davisp/nif-examples](https://github.com/davisp/nif-examples) - Examples for Erlang NIFs
* [chaoslawful/zfor](https://github.com/chaoslawful/zfor) - A Fail-over Name Resolver
* [websterclay/rebar_riak_core](https://github.com/websterclay/rebar_riak_core) - rebar create template=riak_core appid=myapp
* [wulczer/tsung_ws](https://github.com/wulczer/tsung_ws) - Tsung plugin for WebSockets
* [klarna/katt](https://github.com/klarna/katt) - This repository is no longer actively maintained, please see
* [videlalvaro/rmq_patterns](https://github.com/videlalvaro/rmq_patterns) - Implementation of several messaging patterns with RabbitMQ and AMQP
* [machinezone/mzbench](https://github.com/machinezone/mzbench) - MZ Benchmarking
* [DeadZen/etsgive](https://github.com/DeadZen/etsgive) - Demonstration of Don't lose your ETS Tables
* [ranok/open-server-platform](https://github.com/ranok/open-server-platform) - A platform for easily developing multithreaded/replicated servers
* [kaos/gen_listener_tcp](https://github.com/kaos/gen_listener_tcp) - A generic tcp listener process adhering to OTP design principles
* [jbrisbin/riak-rabbitmq-commit-hooks](https://github.com/jbrisbin/riak-rabbitmq-commit-hooks) - Riak RabbitMQ commit hooks
* [isacssouza/erlgrind](https://github.com/isacssouza/erlgrind) - Convert fprof to callgring output
* [erlang/pmod_transform](https://github.com/erlang/pmod_transform) - Parse transform for parameterized modules
* [campanja/folsomite](https://github.com/campanja/folsomite) - blow up your graphite / riemann server with folsom metrics
* [basho/lager_syslog](https://github.com/basho/lager_syslog) - Syslog backend for lager
* [devinus/walrus](https://github.com/devinus/walrus) - Walrus - Mustache-like Templating

* [sgrimm/lurkers-guide](https://github.com/sgrimm/lurkers-guide) - The Lurker's Guide to Babylon 5
* [ngerakines/mochevent](https://github.com/ngerakines/mochevent) - A libevent based webserver that is somewhat compliant with mochiweb.
* [klarna/meshup](https://github.com/klarna/meshup) - Dynamo-flavored workflow engine.
* [chef/mixer](https://github.com/chef/mixer) - Mix in functions from other modules
* [basho/riak_pb](https://github.com/basho/riak_pb) - Riak Protocol Buffers Messages
* [aweber/rabbitmq-autocluster](https://github.com/aweber/rabbitmq-autocluster) - A RabbitMQ plugin that clusters nodes automatically using Consul, etcd2, or DNS
* [slfritchie/msgdropsim](https://github.com/slfritchie/msgdropsim) - Simulator for message passing protocols, supporting (really) unfair process scheduling and dropped messages
* [robertmeta/cowboy-examples](https://github.com/robertmeta/cowboy-examples) - This project will clone all the misultin examples over to cowboy ones
* [oscarh/lhttpc](https://github.com/oscarh/lhttpc) - GIT clone of http://bitbucket.org/etc/lhttpc/
* [erlyvideo/gen_tracker](https://github.com/erlyvideo/gen_tracker) - supervisor with ets handling of children and their metadata
* [tonyg/script-exchange](https://github.com/tonyg/script-exchange) - RabbitMQ "Script Exchange" plugin
* [higepon/mio](https://github.com/higepon/mio) - In short, mio is memcached + "range search".
* [LambdaCon/2015](https://github.com/LambdaCon/2015) - Slides and sources from LambdaCon 2015 edition.
* [twonds/ejabberd_couchdb](https://github.com/twonds/ejabberd_couchdb) - Couchdb backend for ejabberd
* [davisp/couchdb](https://github.com/davisp/couchdb) - Development branches
* [boundary/folsom_webmachine](https://github.com/boundary/folsom_webmachine) - folsom based metrics via HTTP and JSON
* [yrashk/rebar_elixir_plugin](https://github.com/yrashk/rebar_elixir_plugin) - Elixir Plugin for Rebar
* [wooga/warlock](https://github.com/wooga/warlock) - distributed locking thesis project
* [squaremo/rabbitmq-lvc-plugin](https://github.com/squaremo/rabbitmq-lvc-plugin) - A plugin exchange type for RabbitMQ that acts as a last-value-cache
* [rabbitmq/rabbitmq-consistent-hash-exchange](https://github.com/rabbitmq/rabbitmq-consistent-hash-exchange) - RabbitMQ Consistent Hash Exchange Type
* [rabbitmq/rabbitmq-amqp1.0](https://github.com/rabbitmq/rabbitmq-amqp1.0) - AMQP 1.0 support for RabbitMQ
* [basho/riak_err](https://github.com/basho/riak_err) - Enhanced SASL Error Logger for Riak
* [basho/riak_crdt_cookbook](https://github.com/basho/riak_crdt_cookbook) - A Cookbook full of Tutorials to get Developers started with Riak's CRDTs
* [basho/machi](https://github.com/basho/machi) - Machi file store
* [CorticalComputer/DXNN](https://github.com/CorticalComputer/DXNN) - Topology and Parameter Evolving Universal Learning Network Platform
* [lemenkov/erlrtpproxy](https://github.com/lemenkov/erlrtpproxy) - RTP/RTCP proxy for VoIP and IM applications.
* [jiangmiao/proxy](https://github.com/jiangmiao/proxy) - 支持SOCKS 5协议的高速加密通信的代理服务器脚本
* [gmr/rabbitmq-pulse](https://github.com/gmr/rabbitmq-pulse) - rabbitmq-pulse is a RabbitMQ plugin that publishes node and queue information, pushing stats instead of polling the Management API
* [dch/couchgap](https://github.com/dch/couchgap) - DEPRECATED -- USE TOUCHDB OR POUCHDB INSTEAD
* [cmeiklejohn/riak_pg](https://github.com/cmeiklejohn/riak_pg) - Distributed process groups with riak_core.
* [taotaotheripper/Erlang-In-Docker](https://github.com/taotaotheripper/Erlang-In-Docker) - Enable connection between Erlang VMs from different docker containers on different hosts by reimplementing the distributed connection protocol used by net_kernel.
* [oscarh/gen_tcpd](https://github.com/oscarh/gen_tcpd) - Generic TCP listening and accepting
* [darach/eep-erl](https://github.com/darach/eep-erl) - eep.erl - Embedded Event Processing
* [boundary/folsom_cowboy](https://github.com/boundary/folsom_cowboy) - A Cowboy based Folsom HTTP Wrapper.
* [spawnproc/cr](https://github.com/spawnproc/cr) - Chain Replication
* [skeltoac/http_prebind](https://github.com/skeltoac/http_prebind) - Ejabberd web module to create HTTP BIND sessions with a single HTTP GET. Useful for Strophe::attach().
* [rvirding/chat_demo](https://github.com/rvirding/chat_demo) - Simple demo of using websockets for a simple chat program
* [erlware/episcina](https://github.com/erlware/episcina) - A simple non intrusive resource pool for connections

* [chef/chef-server](https://github.com/chef/chef-server) - The Chef Server
* [theozaurus/mod_eventful](https://github.com/theozaurus/mod_eventful) - An ejabberd module that will turn events into HTTP requests
* [talentdeficit/jsxn](https://github.com/talentdeficit/jsxn) - jsx but with maps for people who are into that kind of thing
* [mabrek/rabbitmq-redis](https://github.com/mabrek/rabbitmq-redis) - Experimental bridge between RabbitMQ and Redis implemented as a RabbitMQ plugin
* [jbrisbin/lager_amqp_backend](https://github.com/jbrisbin/lager_amqp_backend) - AMQP RabbitMQ Lager backend
* [synrc/kai](https://github.com/synrc/kai) - DHT storage by Takeshi Inoue
* [synrc/avz](https://github.com/synrc/avz) - N2O Token System for Web Providers
* [rabbitmq/rabbitmq-delayed-message-exchange](https://github.com/rabbitmq/rabbitmq-delayed-message-exchange) - Delayed Messaging for RabbitMQ
* [knutin/kprof](https://github.com/knutin/kprof) - kprof allows you to profile the code path a request takes through your application. The trace is broken down into tiers, so you can see exactly how much time you spend in each layer of your app.
* [chadillac/ejabberd-easy_cluster](https://github.com/chadillac/ejabberd-easy_cluster) - Make multi-master Ejabberd clustering possible, make it easy. Also ease the process of a slave Ejabberd node joining an existing cluster using a traditional master->slave configuration.
* [bdionne/indexer](https://github.com/bdionne/indexer) - Full text indexing of couchdb databases

* [kuenishi/riak_scr_jp](https://github.com/kuenishi/riak_scr_jp) - Repository for Riak Source Code Reading @Tokyo
* [ferd/bertconf](https://github.com/ferd/bertconf) - Make ETS tables out of statc BERT files that are auto-reloaded

* [aweber/influxdb-storage-exchange](https://github.com/aweber/influxdb-storage-exchange) - Post JSON structured event messages to InfluxDB
* [uwiger/pots](https://github.com/uwiger/pots) - Demo program for Plain Old Telephony System (POTS) simulation
* [gotthardp/rabbitmq-email](https://github.com/gotthardp/rabbitmq-email) - SMTP Gateway Plugin for RabbitMQ
* [eproxus/unite](https://github.com/eproxus/unite) - Pretty EUnit test formatters
* [videlalvaro/rabbitmq-websockets](https://github.com/videlalvaro/rabbitmq-websockets) - RabbitMQ Plugin that bridges AMQP to Websockets
* [tonyg/udp-exchange](https://github.com/tonyg/udp-exchange) - Extends RabbitMQ Server with support for a new experimental exchange type, `x-udp`.
* [rabbitmq/rabbitmq-stomp](https://github.com/rabbitmq/rabbitmq-stomp) - RabbitMQ STOMP gateway


* [erlware-deprecated/faxien](https://github.com/erlware-deprecated/faxien) - The official Faxien repository
* [carotene/carotene](https://github.com/carotene/carotene) - Real-time server http://carotene-project.com

* [krestenkrab/riak_link_index](https://github.com/krestenkrab/riak_link_index) - Simple Indexer for Riak based on Links
* [jbrisbin/random-exchange](https://github.com/jbrisbin/random-exchange) - RabbitMQ exchange type for randomly selecting which queue to route to for load balancing.

* [erlyvideo/http_router](https://github.com/erlyvideo/http_router) - HTTP Routing mechanism
* [synrc/active](https://github.com/synrc/active) - Recompilation and Reloading on FileSystem changes
* [spawnproc/bpe](https://github.com/spawnproc/bpe) - Business Process Engine
* [rvirding/rb](https://github.com/rvirding/rb) - Red-Black tree implementations of dicts and sets.
* [ndl/mod_archive2](https://github.com/ndl/mod_archive2) - mod_archive2 is new ejabberd module implementing server-side instant messaging history support specified in XEP-136.
* [maximk/zergling](https://github.com/maximk/zergling) - A instance-per-page demo
* [kevsmith/gen_paxos2](https://github.com/kevsmith/gen_paxos2) - Snapshot of the gen_paxos repo (now missing)
* [jbrisbin/misultin-riak-core-vnode-dispatcher](https://github.com/jbrisbin/misultin-riak-core-vnode-dispatcher) - Misultin Riak Core VNode Dispatcher
* [hawk/lux](https://github.com/hawk/lux) - Lux (LUcid eXpect scripting) simplifies test automation and provides an Expect-style execution of commands
* [candy-chat/mod_log_chat_mysql5](https://github.com/candy-chat/mod_log_chat_mysql5) - Ejabberd module for logging chat messages to a MySQL DB
* [benoitc/mochicow](https://github.com/benoitc/mochicow) - mochiweb adapter for cowboy.
* [Zatvobor/couch_normalizer](https://github.com/Zatvobor/couch_normalizer) - Data mutation reactor which works in Apache CouchDB
* [SIfoxDevTeam/eavro](https://github.com/SIfoxDevTeam/eavro) - Apache Avro encoder/decoder
* [NetEase/erlyssh](https://github.com/NetEase/erlyssh) - A Parallel SSH Execution Tool
* [tty/async_search](https://github.com/tty/async_search) - Repository with demo code for blogpost blog.tty.nl
* [retnuh/mochiweb_xpath](https://github.com/retnuh/mochiweb_xpath) - XPath support for mochiweb's html parser
* [lfe/sicp](https://github.com/lfe/sicp) - SICP, the LFE Edition
* [ferd/cth_readable](https://github.com/ferd/cth_readable) - Common Test hooks for more readable logs
* [erlyvideo/publisher](https://github.com/erlyvideo/publisher) - USB/RTSP camera publisher
* [chrismoos/erl_chat_tutorial](https://github.com/chrismoos/erl_chat_tutorial) - source for erl_chat tutorial
* [chef/bookshelf](https://github.com/chef/bookshelf) - Minimal S3 Clone
* [basho-labs/riak_nagios](https://github.com/basho-labs/riak_nagios) - Nagios Scripts for monitoring Riak
* [FWeinb/metalsmith-watch](https://github.com/FWeinb/metalsmith-watch) - A metalsmith plugin to watch for a changes and trigger rebuilds.
* [marianoguerra/flaviodb](https://github.com/marianoguerra/flaviodb) - Riak Core sample project implementing fixed message stream store
* [ddossot/rabbitmq-http-safe](https://github.com/ddossot/rabbitmq-http-safe) - A store-and-forward HTTP gateway plugin for RabbitMQ.
* [rabbitmq/rabbitmq-smtp](https://github.com/rabbitmq/rabbitmq-smtp) - RabbitMQ SMTP gateway
* [rabbitmq/rabbitmq-federation](https://github.com/rabbitmq/rabbitmq-federation) - RabbitMQ Federation
* [maxlapshin/parsexml](https://github.com/maxlapshin/parsexml) - Simple DOM XML parser with convenient and very simple API
* [kivra/oauth2_example](https://github.com/kivra/oauth2_example) - Example application for oauth2
* [joearms/adapter_pattern](https://github.com/joearms/adapter_pattern) - adapter pattern for mochiweb misultin and cowboy
* [greyarea/props](https://github.com/greyarea/props) - Property structure library
* [garazdawi/cth_tools](https://github.com/garazdawi/cth_tools) - Generic Common Test hooks tools
* [extend/horse](https://github.com/extend/horse) - Integrated performance testing.
* [FlowForwarding/loom](https://github.com/FlowForwarding/loom) - LOOM Controller
* [xmppjingle/jinglenodes](https://github.com/xmppjingle/jinglenodes) - Jingle Nodes Relay
* [seancribbs/riak_zmq](https://github.com/seancribbs/riak_zmq) - Publish writes to Riak KV to 0MQ (based on linked gist)
* [kineticsocial/rabbitmq_snmp_plugin](https://github.com/kineticsocial/rabbitmq_snmp_plugin) - An experimental RabbitMQ plugin to provide SNMP statistics
* [iamaleksey/oserl](https://github.com/iamaleksey/oserl) - A fork of http://sourceforge.net/projects/oserl/ with a few patches.
* [extend/ex_apns](https://github.com/extend/ex_apns) - An APNS client
* [esl/amoc](https://github.com/esl/amoc) - amoc is simple tool for running massively parallel XMPP tests
* [cstar/modular_muc](https://github.com/cstar/modular_muc) - Refactoring of ejabberd's mod_muc, with flexible storage and chatroom handling.
* [TensorWrench/lager_extras](https://github.com/TensorWrench/lager_extras) - A collection of formatters and backends for lager that have no external dependencies.
* [RJ/mochiweb-websockets](https://github.com/RJ/mochiweb-websockets) - ***OBSOLETE, using my mochiweb repo now ***
* [Feuerlabs/kvdb](https://github.com/Feuerlabs/kvdb) - Key value data base API
* [theozaurus/mod_warm_bindings](https://github.com/theozaurus/mod_warm_bindings) - An ejabberd module that warms and authenticates a BOSH connection with a single HTTP POST
* [synrc/games](https://github.com/synrc/games) - SVG WebSockets N2O Example
* [project-fifo/wiggle](https://github.com/project-fifo/wiggle) - The FiFo API server.
* [kongo2002/ejabberd-mod-mam](https://github.com/kongo2002/ejabberd-mod-mam) - Message Archive Management (XEP-0313) for ejabberd using a MongoDB backend
* [kivra/emagick](https://github.com/kivra/emagick) - Wrapper for Graphics/ImageMagick command line tool.
* [hectcastro/docker-riak-cs](https://github.com/hectcastro/docker-riak-cs) - A Docker project to bring up a local Riak CS cluster.
* [basho-labs/ansible-riak](https://github.com/basho-labs/ansible-riak) - Ansible roles for Riak
* [archaelus/erlmail](https://github.com/archaelus/erlmail) - A fork of Stuart Jackson's erlmail library with some additions
* [abhinavsingh/mod_message_carbon](https://github.com/abhinavsingh/mod_message_carbon) - XEP-0280 Message Carbon Ejabberd Module
* [synrc/rest](https://github.com/synrc/rest) - Micro-REST with typed JSON
* [synrc/mqs](https://github.com/synrc/mqs) - Subscribe and Publish
* [refuge/coffer](https://github.com/refuge/coffer) - Versatile blob storage service
* [permelin/updo](https://github.com/permelin/updo) - Lightweight code update
* [jbrisbin/rabbit_common](https://github.com/jbrisbin/rabbit_common) - Rebar-friendly fork of RabbitMQ common code
* [jamii/erl-telehash](https://github.com/jamii/erl-telehash) - TeleHash is a p2p overlay that aims to remove the pain from developing p2p applications
* [ferd/batchio](https://github.com/ferd/batchio) - io:format middle-man that buffers and batches output sent to the io server for better throughput
* [etnt/polish](https://github.com/etnt/polish) - A text translation tool
* [erlware/rebar_vsn_plugin](https://github.com/erlware/rebar_vsn_plugin) - Provides a more reasonable versioning scheme then the rebar standard 'git' vsn extension
* [cloudant/fabric](https://github.com/cloudant/fabric) - Routing and proxying library app for BigCouch
* [chvanikoff/cowboy_session](https://github.com/chvanikoff/cowboy_session) - Cowboy session management
* [bob-p/mod_global_roster](https://github.com/bob-p/mod_global_roster) - Ejabberd module that stores a global roster in redis

* [astro/chaosbay](https://github.com/astro/chaosbay) - BitTorrent Tracker with upload & browsing, written on the 25th Chaos Communication Congress

* [spawngrid/htoad](https://github.com/spawngrid/htoad) - Provisioning tool (Experimental, expect things to change!)
* [rabbitmq/rabbitmq-shovel](https://github.com/rabbitmq/rabbitmq-shovel) - RabbitMQ Shovel plugin
* [projectcs13/sensor-cloud](https://github.com/projectcs13/sensor-cloud) - A stream search engine for the Internet of Things (back-end)
* [peerdrive/peerdrive](https://github.com/peerdrive/peerdrive) - A new approach to file systems
* [ostinelli/erlcassa](https://github.com/ostinelli/erlcassa) - A Cassandra CQL client.
* [mochi/recordset](https://github.com/mochi/recordset) - An optionally fixed-size ordered set of complex terms.
* [maximk/spawnpool](https://github.com/maximk/spawnpool) - The 'spawner' application for Zerg demo
* [liangjingyang/everrank](https://github.com/liangjingyang/everrank) - 为手游提供好友积分排行等社交交互服务和存档服务。单节点屌丝版。
* [janl/my-first-couchdb-plugin](https://github.com/janl/my-first-couchdb-plugin) - A practical guide to writing CouchDB plugins
* [hyperthunk/rebar_dist_plugin](https://github.com/hyperthunk/rebar_dist_plugin) - A Rebar Archive Packaging Plugin
* [basho/luke](https://github.com/basho/luke) - Dataflow / MapReduce coordination framework.
* [shino/kai](https://github.com/shino/kai) - Kai is a distributed key-value datastore mainly inspired by Amazon's Dynamo. (fork from sourceforge)
* [benmmurphy/ecnty](https://github.com/benmmurphy/ecnty) - Partitioned Counter Based on Riak Core
