# awesome-go

Crawled and sorted daily by AwesomelsBot. Source: [awesome-go](https://github.com/avelino/awesome-go)

### Contents


- [Audio and Music](#audio-and-music)

- [Authentication and OAuth](#authentication-and-oauth)

- [Command Line](#command-line)

- [Configuration](#configuration)

- [Continuous Integration](#continuous-integration)

- [CSS Preprocessors](#css-preprocessors)

- [Data Structures](#data-structures)

- [Database](#database)

- [Database Drivers](#database-drivers)

- [Date and Time](#date-and-time)

- [Distributed Systems](#distributed-systems)

- [Email](#email)

- [Embeddable Scripting Languages](#embeddable-scripting-languages)

- [Files](#files)

- [Financial](#financial)

- [Forms](#forms)

- [Game Development](#game-development)

- [Generation and Generics](#generation-and-generics)

- [Geographic](#geographic)

- [Go Compilers](#go-compilers)

- [Goroutines](#goroutines)

- [GUI](#gui)

- [Images](#images)

- [IoT (Internet of Things)](#iot-(internet-of-things))

- [Logging](#logging)

- [Machine Learning](#machine-learning)

- [Messaging](#messaging)

- [Miscellaneous](#miscellaneous)

- [Natural Language Processing](#natural-language-processing)

- [Networking](#networking)

- [OpenGL](#opengl)

- [ORM](#orm)

- [Package Management](#package-management)

- [Query Language](#query-language)

- [Resource Embedding](#resource-embedding)

- [Science and Data Analysis](#science-and-data-analysis)

- [Security](#security)

- [Serialization](#serialization)

- [Server Applications](#server-applications)

- [Template Engines](#template-engines)

- [Testing](#testing)

- [Text Processing](#text-processing)

- [Third-party APIs](#third-party-apis)

- [Utilities](#utilities)

- [Validation](#validation)

- [Version Control](#version-control)

- [Video](#video)

- [Web Frameworks](#web-frameworks)

- [Windows](#windows)

- [XML](#xml)

- [Code Analysis](#code-analysis)

- [Editor Plugins](#editor-plugins)

- [Go Generate Tools](#go-generate-tools)

- [Go Tools](#go-tools)

- [Software Packages](#software-packages)

- [Benchmarks](#benchmarks)

- [E-Books](#e-books)

- [Gophers](#gophers)

- [Websites](#websites)



## Audio and Music



* [portaudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library - ★ 222



* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams. MIT Licensed. - ★ 220



* [music-theory](https://github.com/go-music-theory/music-theory) - Go models of Note, Scale, Chord and Key - ★ 219



* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for libportmidi - ★ 178



* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps - ★ 87



* [go-sox](https://github.com/krig/go-sox) - libsox bindings for go - ★ 81



* [flac](https://github.com/eaburns/flac) - A Free Lossless Audio Codec decoder in Go - ★ 79



* [id3v2](https://github.com/bogem/id3v2) - ID3 parsing and writing library for Go - ★ 79



* [mp3](https://github.com/tcolgate/mp3) - golang mp3 frame parser - ★ 79



* [flac](https://github.com/mewkiz/flac) - Package flac provides access to FLAC (Free Lossless Audio Codec) streams. - ★ 78



* [go-taglib](https://github.com/wtolson/go-taglib) - Go wrapper for taglib - ★ 63



* [gaad](https://github.com/Comcast/gaad) - GAAD (Go Advanced Audio Decoder) - ★ 49



* [malgo](https://github.com/gen2brain/malgo) - Mini audio library - ★ 41



* [vorbis](https://github.com/mccoyst/vorbis) - A &quot;native&quot; ogg vorbis decoder for Go (uses inline stb_vorbis) - ★ 22



* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - Golang bindings for libmediainfo - ★ 18



* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - EasyMidi is a simple and reliable library for working with standard midi file (SMF) - ★ 15



* [minimp3](https://github.com/tosone/minimp3) - Decode mp3 base on - ★ 15



* [gosamplerate](https://github.com/dh1tw/gosamplerate) - Go Bindings for libsamplerate - ★ 7




## Authentication and OAuth



* [tornado](https://github.com/tornadoweb/tornado) - Tornado is a Python web framework and asynchronous networking library, originally developed at FriendFeed. - ★ 16773



* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT) - ★ 4460



* [casbin](https://github.com/hsluoyz/casbin) - An authorization library that supports access control models like ACL, RBAC, ABAC in Golang - ★ 3200



* [goth](https://github.com/markbates/goth) - Package goth provides a simple, clean, and idiomatic way to write authentication packages for Go web applications. - ★ 1922



* [oauth2](https://github.com/golang/oauth2) - Go OAuth2 - ★ 1899



* [authboss](https://github.com/volatiletech/authboss) - The boss of http auth. - ★ 1592



* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - A standalone, specification-compliant, OAuth2 server written in Golang. - ★ 1005



* [go-jose](https://github.com/square/go-jose) - An implementation of JOSE standards (JWE, JWS, JWT) in Go - ★ 972



* [gologin](https://github.com/dghubble/gologin) - Go login handlers for authentication providers (OAuth1, OAuth2) - ★ 927



* [gorbac](https://github.com/mikespook/gorbac) - goRBAC provides a lightweight role-based access control (RBAC) implementation in Golang. - ★ 779



* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2, Google, Github, htpasswd, osiam, .. - ★ 647



* [permissions2](https://github.com/xyproto/permissions2) - Middleware for keeping track of users, login states and permissions - ★ 284



* [go-aws-auth](https://github.com/smartystreets/go-aws-auth) - [DEPRECATED] Signs requests to Amazon Web Services (AWS) using IAM roles or signed signature versions 2, 3, and 4. Supports S3 and STS. - ★ 215



* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middlewares - ★ 157



* [paseto](https://github.com/o1egl/paseto) - Platform-Agnostic Security Tokens implementation in GO (Golang) - ★ 154



* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - This package provides json web token (jwt) middleware for goLang http servers - ★ 132



* [yubigo](https://github.com/GeertJohan/yubigo) - Yubigo is a Yubikey client API library that provides an easy way to integrate the Yubico Yubikey into your existing Go-based user authentication infrastructure. - ★ 94



* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE). - ★ 74



* [jwt](https://github.com/robbert229/jwt) - This is an implementation of JWT in golang! - ★ 50



* [sessions](https://github.com/adam-hanna/sessions) - A dead simple, highly performant, highly customizable sessions middleware for go http servers. - ★ 36



* [branca](https://github.com/hako/branca) - Secure alternative to JWT. Authenticated Encrypted API Tokens for Go. - ★ 33



* [securecookie](https://github.com/chmike/securecookie) - Fast, secure and efficient secure cookie encoder/decoder - ★ 24



* [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications - ★ 16



* [jwt](https://github.com/pascaldekloe/jwt) - JSON Web Token library - ★ 14



* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Driver for the SessionGate Redis module for easy session management in the Go language. - ★ 5



* [signedvalue](https://github.com/sashka/signedvalue) - Compatibility layer for tornado&#39;s signed values (and secure cookies consequently) - ★ 5



* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - cookiestxt implement parser of cookies txt format - ★ 1



* [osin](https://github.com/RangelReale/osin) - Golang OAuth2 server library - ★ 1




## Command Line



* [blessed-contrib](https://github.com/yaronn/blessed-contrib) - Build terminal dashboards using ascii/ansi art and javascript - ★ 11904



* [cobra](https://github.com/spf13/cobra) - A Commander for modern Go CLI interactions - ★ 9473



* [cli](https://github.com/urfave/cli) - A simple, fast, and fun package for building command line apps in Go - ★ 9265



* [termui](https://github.com/gizak/termui) - Golang terminal dashboard - ★ 8005



* [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - Library for building powerful interactive command line applications in Python - ★ 4870



* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline - ★ 4484



* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go package aimed at creating Console User Interfaces. - ★ 3643



* [termbox-go](https://github.com/nsf/termbox-go) - Pure Go termbox implementation - ★ 3073



* [color](https://github.com/fatih/color) - Color package for Go (golang) - ★ 2745



* [kingpin](https://github.com/alecthomas/kingpin) - A Go (golang) command line and flag parser - ★ 2108



* [go-prompt](https://github.com/c-bata/go-prompt) - Building powerful interactive prompts in Go, inspired by python-prompt-toolkit. - ★ 1869



* [readline](https://github.com/chzyer/readline) - Readline is a pure go(golang) implementation for GNU-Readline kind library - ★ 1245



* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser - ★ 1200



* [uiprogress](https://github.com/gosuri/uiprogress) - A go library to render progress bars in terminal applications - ★ 1200



* [terminal-table](https://github.com/tj/terminal-table) - Ruby ASCII Table Generator, simple and feature rich. - ★ 1062



* [docopt.go](https://github.com/docopt/docopt.go) - A command-line arguments parser that will make you smile. - ★ 996



* [cli](https://github.com/mitchellh/cli) - A Go library for implementing command-line interfaces. - ★ 877



* [gcli](https://github.com/tcnksm/gcli) - The easy way to build Golang command-line application. - ★ 845



* [uilive](https://github.com/gosuri/uilive) - uilive is a go library for updating terminal output in realtime - ★ 689



* [mow.cli](https://github.com/jawher/mow.cli) - A versatile library for building CLI applications in Go - ★ 572



* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go - ★ 536



* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go&#39;s flag package, implementing POSIX/GNU-style --flags. - ★ 531



* [complete](https://github.com/posener/complete) - bash completion written in go + bash completion for go command - ★ 517



* [liner](https://github.com/peterh/liner) - Pure Go line editor with history, inspired by linenoise - ★ 489



* [uitable](https://github.com/gosuri/uitable) - A go library to improve readability in terminal apps using tabular data - ★ 451



* [progressbar](https://github.com/schollz/progressbar) - A really basic thread-safe progress bar for Golang applications - ★ 413



* [cli](https://github.com/mkideal/cli) - CLI - A package for building command line app with go - ★ 405



* [flaggy](https://github.com/integrii/flaggy) - Idiomatic Go input parsing with subcommands, positional values, and flags at any position. No required project or package layout and no external dependencies. - ★ 390



* [aurora](https://github.com/logrusorgru/aurora) - Golang ultimate ANSI-colors that supports Printf/Sprintf methods - ★ 373



* [mpb](https://github.com/vbauerster/mpb) - multi progress bar written in Go - ★ 354



* [go-colorable](https://github.com/mattn/go-colorable) - ★ 309



* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. - ★ 278



* [go-isatty](https://github.com/mattn/go-isatty) - ★ 276



* [gommon](https://github.com/labstack/gommon/tree/master/color) - ★ 252



* [termtables](https://github.com/apcera/termtables) - Go ASCII Table Generator, ported from the Ruby terminal-tables library - ★ 193



* [go-colortext](https://github.com/daviddengcn/go-colortext) - Change the color of console text. - ★ 179



* [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go - ★ 103



* [clif](https://github.com/ukautz/clif) - Another CLI framework for Go. It works on my machine. - ★ 89



* [flag](https://github.com/cosiner/flag) - Flag is a simple but powerful command line option parsing library for Go support infinite level subcommand - ★ 85



* [commandeer](https://github.com/jaffee/commandeer) - Automatically sets up command line flags based on struct fields and tags. - ★ 66



* [sflags](https://github.com/octago/sflags) - Generate flags by parsing structures - ★ 64



* [wmenu](https://github.com/dixonwille/wmenu) - An easy to use menu structure for cli applications that prompts users to make choices. - ★ 59



* [argparse](https://github.com/akamensky/argparse) - Argparse for golang. Just because `flag` sucks - ★ 57



* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes - ★ 45



* [hiboot](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - ★ 44



* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line applications in Go - ★ 37



* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs - ★ 34



* [color](https://github.com/gookit/color) - Terminal color rendering tool library, support 8/16 colors, 256 colors, RGB color rendering output, compatible with Windows. CLI 控制台颜色渲染工具库, 简洁的使用API，支持16色，256色，RGB色彩渲染输出，兼容 Windows 环境 - ★ 31



* [wlog](https://github.com/dixonwille/wlog) - A simple logging interface that supports cross-platform color and concurrency. - ★ 26



* [flagvar](https://github.com/sgreben/flagvar) - A collection of CLI argument types for the Go `flag` package. - ★ 23



* [gocmd](https://github.com/devfacet/gocmd) - A Go library for building command line applications - ★ 23



* [strumt](https://github.com/antham/strumt) - Strumt is a library to create prompt chain - ★ 20



* [tabular](https://github.com/InVisionApp/tabular) - Tabular simplifies printing ASCII tables from command line utilities - ★ 14



* [colourize](https://github.com/TreyBastian/colourize) - An ANSI colour terminal package for Go - ★ 13



* [argv](https://github.com/cosiner/argv) - ★ 9



* [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow - ★ 7



* [go-ataman](https://github.com/workanator/go-ataman) - Another Text Attribute Manupulator - ★ 7



* [ctc](https://github.com/wzshiming/ctc) - Console Text Colors - The non-invasive cross-platform terminal color library does not need to modify the Print method - ★ 4




## Configuration



* [viper](https://github.com/spf13/viper) - Go configuration with fangs - ★ 6743



* [envconfig](https://github.com/kelseyhightower/envconfig) - Golang library for managing configuration data from environment variables - ★ 1919



* [godotenv](https://github.com/joho/godotenv) - A Go port of Ruby&#39;s dotenv library (Loads environment variables from `.env`.) - ★ 1533



* [ini](https://github.com/go-ini/ini) - Package ini provides INI file read and write functionality in Go. - ★ 1170



* [env](https://github.com/caarlos0/env) - A KISS way to deal with environment variables in Go. - ★ 615



* [store](https://github.com/tucnak/store) - A dead simple configuration manager for Go applications - ★ 235



* [config](https://github.com/joshbetz/config) - A configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP - ★ 190



* [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct - ★ 179



* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with convenient access methods. - ★ 178



* [hjson-go](https://github.com/hjson/hjson-go) - Hjson for Go - ★ 150



* [envconfig](https://github.com/vrischmann/envconfig) - Small library to read your configuration from environment variables - ★ 127



* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections - ★ 99



* [envh](https://github.com/antham/envh) - Go helpers to manage environment variables - ★ 89



* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs - ★ 88



* [goconfig](https://github.com/crgimenes/goConfig) - goconfig uses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. - ★ 83



* [gofigure](https://github.com/ian-kent/gofigure) - Go configuration made easy! - ★ 55



* [configure](https://github.com/paked/configure) - Configure is a Go package that gives you easy configuration of your project through redundancy - ★ 39



* [config](https://github.com/gookit/config) - Go config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge, parse ENV var. Go应用配置加载管理，支持多种格式，多文件加载，支持数据合并，解析环境变量名 - ★ 24



* [gone](https://github.com/One-com/gone/tree/master/jconf) - ★ 22



* [ingo](https://github.com/schachmat/ingo) - persistent storage for flags in go - ★ 21



* [mini](https://github.com/sasbury/mini) - A golang package for parsing ini-style configuration files - ★ 19



* [conflate](https://github.com/miracl/conflate) - Library providing routines to merge and validate JSON, YAML and/or TOML files - ★ 15



* [go-up](https://github.com/ufoscout/go-up) - go-up! A simple configuration library with recursive placeholders resolution and no magic. - ★ 15



* [xdg](https://github.com/OpenPeeDeeP/xdg) - A cross platform package that follows the XDG Standard - ★ 14



* [envconf](https://github.com/ian-kent/envconf) - Configure Go applications from the environment - ★ 7



* [sprbox](https://github.com/oblq/sprbox) - Build-environment aware toolbox factory &amp; agnostic, layered, config parser (supporting YAML, TOML, JSON and Environment vars). - ★ 3




## Continuous Integration



* [drone](https://github.com/drone/drone) - Drone is a Continuous Delivery platform built on Docker, written in Go - ★ 16164



* [goveralls](https://github.com/mattn/goveralls) - ★ 520



* [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls - ★ 94



* [duci](https://github.com/duck8823/duci) - The small ci server - ★ 14



* [gomason](https://github.com/nikogura/gomason) - A tool for testing, building, signing, and publishing go binaries from a clean workspace. - ★ 12



* [roveralls](https://github.com/LawrenceWoodman/roveralls) - A Go recursive coverage testing tool - ★ 10




## CSS Preprocessors



* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor - ★ 408



* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper for libsass, the only Sass 3.5 compiler for Go - ★ 107




## Data Structures



* [gods](https://github.com/emirpasic/gods) - GoDS (Go Data Structures). Containers (Sets, Lists, Stacks, Maps, Trees), Sets (HashSet, TreeSet, LinkedHashSet), Lists (ArrayList, SinglyLinkedList, DoublyLinkedList), Stacks (LinkedListStack, ArrayStack), Maps (HashMap, TreeMap, HashBidiMap, TreeBidiMap, LinkedHashMap), Trees (RedBlackTree, AVLTree, BTree, BinaryHeap), Comparators, Iterators, … - ★ 4747



* [go-datastructures](https://github.com/Workiva/go-datastructures) - ★ 4510



* [BoomFilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams. - ★ 1030



* [golang-set](https://github.com/deckarep/golang-set) - A simple set type for the Go language. Also used in Docker, Kubernetes, Ethereum. - ★ 886



* [gota](https://github.com/kniren/gota) - Gota: DataFrames and data wrangling in Go (Golang) - ★ 662



* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog with lots of sugar (Sparse, LogLog-Beta bias correction and TailCut space reduction) - ★ 617



* [bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters - ★ 542



* [roaring](https://github.com/RoaringBitmap/roaring) - Roaring bitmaps in Go (golang) - ★ 479



* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets - ★ 401



* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo Filter: Practically Better Than Bloom - ★ 387



* [trie](https://github.com/derekparker/trie) - Data structure and relevant algorithms for extremely fast prefix/fuzzy string searching. - ★ 325



* [go-geoindex](https://github.com/hailocab/go-geoindex) - Go native library for fast point tracking and K-Nearest queries - ★ 286



* [mafsa](https://github.com/smartystreets/mafsa) - Package mafsa implements Minimal Acyclic Finite State Automata in Go, essentially a high-speed, memory-efficient, Unicode-friendly set of strings. - ★ 269



* [goskiplist](https://github.com/ryszard/goskiplist) - A skip list implementation in Go - ★ 172



* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. - ★ 160



* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go. - ★ 119



* [merkletree](https://github.com/cbergoon/merkletree) - A Merkle Tree implementation written in Go. - ★ 100



* [binpacker](https://github.com/zhuangsirui/binpacker) - A binary stream packer and unpacker - ★ 98



* [algorithms](https://github.com/shady831213/algorithms) - CLRS study. Codes are written with golang. - ★ 97



* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go - ★ 88



* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - State of the art point location and neighbour finding algorithms for region quadtrees, in Go - ★ 88



* [ttlcache](https://github.com/diegobernardes/ttlcache) - An in-memory string-interface{} map with various expiration options for golang - ★ 71



* [skiplist](https://github.com/MauriceGit/skiplist) - A Go library for an efficient implementation of a skip list: - ★ 61



* [skiplist](https://github.com/gansidui/skiplist) - skiplist for golang - ★ 57



* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Adaptive Radix Trees implemented in Go - ★ 48



* [conjungo](https://github.com/InVisionApp/conjungo) - A small flexible merge library in go - ★ 45



* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation of Count-Min-Log - ★ 39



* [levenshtein](https://github.com/agnivade/levenshtein) - Go implementation to calculate Levenshtein Distance. - ★ 33



* [bit](https://github.com/yourbasic/bit) - Set data structure for positive numbers - ★ 24



* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. - ★ 21



* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library for Golang - ★ 15



* [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue) - ★ 11



* [bloom](https://github.com/yourbasic/bloom) - Probabilistic set data structure - ★ 10



* [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for bufio.Writer - ★ 10



* [goset](https://github.com/zoumo/goset) - Set is a useful collection but there is no built-in implementation in Go lang. - ★ 10



* [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding - ★ 8



* [pipeline](https://github.com/hyfather/pipeline) - Pipelines using goroutines - ★ 6



* [set](https://github.com/StudioSol/set) - A simple Set data structure implementation in Go (Golang) using LinkedHashMap. - ★ 5



* [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm Using TrieHashNode - ★ 3




## Database



* [prometheus](https://github.com/prometheus/prometheus) - The Prometheus monitoring system and time series database. - ★ 20075



* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed HTAP database compatible with the MySQL protocol - ★ 15803



* [leveldb](https://github.com/google/leveldb) - LevelDB is a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values. - ★ 15434



* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics - ★ 14795



* [cockroach](https://github.com/cockroachdb/cockroach) - CockroachDB - the open source, cloud-native SQL database. - ★ 14679



* [bolt](https://github.com/boltdb/bolt) - An embedded key/value database for Go. - ★ 9121



* [dgraph](https://github.com/dgraph-io/dgraph) - Fast, Distributed Graph DB - ★ 6881



* [vitess](https://github.com/youtube/vitess) - Vitess is a database clustering system for horizontal scaling of MySQL. - ★ 6871



* [groupcache](https://github.com/golang/groupcache) - groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. - ★ 6850



* [pgweb](https://github.com/sosedoff/pgweb) - Cross-platform client for PostgreSQL databases - ★ 5370



* [badger](https://github.com/dgraph-io/badger) - Fast key-value DB in Go. - ★ 4558



* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed relational database built on SQLite. - ★ 4092



* [kingshard](https://github.com/flike/kingshard) - A high-performance MySQL proxy - ★ 3872



* [ledisdb](https://github.com/siddontang/ledisdb) - a high performance NoSQL powered by Go - ★ 2741



* [goleveldb](https://github.com/syndtr/goleveldb) - LevelDB key/value database in Go. - ★ 2578



* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology management and HA - ★ 2237



* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang - ★ 2236



* [buntdb](https://github.com/tidwall/buntdb) - BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support - ★ 2131



* [go-cache](https://github.com/pmylund/go-cache) - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. - ★ 2077



* [prest](https://github.com/nuveo/prest) - pREST is a way to serve a RESTful API from any databases written in Go - ★ 1872



* [xo](https://github.com/knq/xo) - Command line tool to generate idiomatic Go code for SQL databases supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server - ★ 1799



* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync MySQL data into elasticsearch - ★ 1786



* [squirrel](https://github.com/Masterminds/squirrel) - Fluent SQL generation for golang - ★ 1768



* [bigcache](https://github.com/allegro/bigcache) - Efficient cache for gigabytes of data written in Go. - ★ 1692



* [go-mysql](https://github.com/siddontang/go-mysql) - a powerful mysql toolset with Go - ★ 1346



* [sql-migrate](https://github.com/rubenv/sql-migrate) - SQL schema migration tool for Go. - ★ 1135



* [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library. - ★ 1105



* [cache2go](https://github.com/muesli/cache2go) - Concurrency-safe Go caching library with expiration capabilities and access counters - ★ 684



* [diskv](https://github.com/peterbourgon/diskv) - A disk-backed key-value store. - ★ 652



* [moss](https://github.com/couchbase/moss) - moss - a simple, fast, ordered, persistable, key-val storage library for golang - ★ 647



* [gcache](https://github.com/bluele/gcache) - Cache library for golang. It supports expirable Cache, LFU, LRU and ARC. - ★ 560



* [dat](https://github.com/mgutz/dat) - Go Postgres Data Access Toolkit - ★ 543



* [pop](https://github.com/gobuffalo/pop/tree/master/soda) - ★ 505



* [eliasdb](https://github.com/krotik/eliasdb) - EliasDB is a graph-based database. - ★ 494



* [goqu](https://github.com/doug-martin/goqu) - SQL builder and query library for golang - ★ 456



* [gendry](https://github.com/didi/gendry) - a golang library for sql builder - ★ 453



* [dotsql](https://github.com/gchaincl/dotsql) - A Golang library for using SQL. - ★ 383



* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - A decentralized, peer-to-peer sharing economy, SQL database with Blockchain features. - ★ 353



* [levigo](https://github.com/jmhodges/levigo) - levigo is a Go wrapper for LevelDB - ★ 338



* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - A Go (golang) package that enhances the standard database/sql package by providing powerful data retrieval methods as well as DB-agnostic query building capabilities. - ★ 273



* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Minimalistic database migration helper for Gorm ORM - ★ 207



* [chproxy](https://github.com/Vertamedia/chproxy) - ClickHouse http proxy and load balancer - ★ 178



* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures - ★ 165



* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs. - ★ 136



* [sqrl](https://github.com/elgris/sqrl) - Fluent SQL generation for golang - ★ 132



* [myreplication](https://github.com/2tvenom/myreplication) - Golang MySql binary log replication listener - ★ 122



* [vasto](https://github.com/chrislusf/vasto) - A distributed key-value store. On Disk. Able to grow or shrink without service interruption. - ★ 98



* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects many small insterts to ClickHouse and send in big inserts - ★ 86



* [goose](https://github.com/steinbacher/goose) - Go database migration tool - ★ 85



* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go - ★ 71



* [igor](https://github.com/galeone/igor) - igor is an abstraction layer for PostgreSQL with a gorm like syntax. - ★ 69



* [slowpoke](https://github.com/recoilme/slowpoke) - Package slowpoke implements a low-level key/value store in pure Go. Keys stored in memory (with persistence), values stored on disk. - ★ 65



* [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily (now only support mysql) - ★ 48



* [couchcache](https://github.com/codingsince1985/couchcache) - A RESTful caching micro-service in Go backed by Couchbase - ★ 38



* [goforestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB - ★ 29



* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - golang bigcache with clustering as a library. - ★ 23



* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration Tool - written in Go - ★ 22



* [gondolier](https://github.com/emvicom/gondolier) - Gondolier is a database migration library for Go. - ★ 20



* [prep](https://github.com/hexdigest/prep) - Prep finds all SQL statements in a Go package and instruments db connection with prepared statements - ★ 20



* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang&#39;s excellent built-in database/sql library. - ★ 17



* [golang-scribble](https://github.com/nanobox-io/golang-scribble) - A tiny Golang JSON database - ★ 16



* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items - ★ 13



* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg. - ★ 11



* [rwdb](https://github.com/andizzle/rwdb) - Database wrapper that manage read write connections - ★ 9



* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - gorocksdb is a Go wrapper for RocksDB with additional features - ★ 6



* [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases. - ★ 0




## Database Drivers



* [cayley](https://github.com/google/cayley) - An open-source graph database - ★ 11895



* [mysql](https://github.com/go-sql-driver/mysql) - Go MySQL Driver is a MySQL driver for Go&#39;s (golang) database/sql package - ★ 6411



* [redigo](https://github.com/gomodule/redigo) - Go client for Redis - ★ 5145



* [bleve](https://github.com/blevesearch/bleve) - A modern text indexing library for go - ★ 4721



* [redis](https://github.com/go-redis/redis) - Type-safe Redis client for Golang - ★ 4444



* [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql - ★ 4345



* [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine - ★ 4068



* [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go. - ★ 3117



* [go-sqlite3](https://github.com/mattn/go-sqlite3) - sqlite3 driver for go using database/sql - ★ 2845



* [pgx](https://github.com/jackc/pgx) - PostgreSQL driver and toolkit for Go - ★ 1539



* [rethinkdb-go](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB - ★ 1385



* [mgo](https://github.com/globalsign/mgo) - The MongoDB driver for Go - ★ 1216



* [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - The Go driver for MongoDB - ★ 1127



* [gomemcache](https://github.com/bradfitz/gomemcache/) - Go Memcached client library #golang - ★ 976



* [elastigo](https://github.com/mattbaird/elastigo) - A Go (golang) based Elasticsearch client library. - ★ 923



* [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft SQL server driver written in go language - ★ 836



* [redis](https://github.com/hoisie/redis) - A simple, powerful Redis client for Go - ★ 576



* [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang - ★ 344



* [go-oci8](https://github.com/mattn/go-oci8) - oracle driver for go that using database/sql - ★ 335



* [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike Client Go - ★ 285



* [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go - ★ 282



* [gocb](https://github.com/couchbase/gocb) - The Couchbase Go SDK - ★ 271



* [elasticsql](https://github.com/cch123/elasticsql) - convert sql to elasticsearch DSL in golang(go) - ★ 233



* [redeo](https://github.com/bsm/redeo) - High-performance framework for building redis-protocol compatible TCP servers/services - ★ 227



* [goracle](https://github.com/go-goracle/goracle) - Oracle driver for Go, using the ODPI-C driver - ★ 137



* [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component - Multiple drivers - ★ 97



* [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS sql driver for Go (golang) - ★ 89



* [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that using exp/sql - ★ 84



* [gofreetds](https://github.com/minus5/gofreetds) - Go Sql Server database driver. - ★ 77



* [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang - ★ 70



* [arangolite](https://github.com/solher/arangolite) - Lightweight Golang driver for ArangoDB - ★ 65



* [dynago](https://github.com/underarmour/dynago) - A DynamoDB client for Go - ★ 60



* [skizze](https://github.com/seiflotfy/skizze) - A probabilistic data structure service and storage - ★ 55



* [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go - ★ 50



* [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Client for Go lang - ★ 24



* [goes](https://github.com/OwnLocal/goes) - A library to interact with Elasticsearch in Go! - ★ 24



* [goriak](https://github.com/zegl/goriak) - goriak - Go language driver for Riak KV - ★ 23



* [calcite-avatica-go](https://github.com/apache/calcite-avatica-go) - Mirror of Apache Calcite - Avatica Go SQL Driver - ★ 19



* [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery in go - ★ 9



* [xredis](https://github.com/shomali11/xredis) - Go Redis Client - ★ 9



* [dsc](https://github.com/viant/dsc) - Datastore Connectivity in go - ★ 6



* [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go - ★ 4



* [godscache](https://github.com/defcronyke/godscache) - An unofficial Google Cloud Platform Go Datastore wrapper that adds caching using memcached. For App Engine Flexible, Compute Engine, Kubernetes Engine, and more. - ★ 3




## Date and Time



* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang - ★ 1852



* [dateparse](https://github.com/araddon/dateparse) - GoLang Parse many date strings without knowing format in advance. - ★ 738



* [carbon](https://github.com/uniplaces/carbon) - Carbon for Golang, an extension for Time - ★ 263



* [durafmt](https://github.com/hako/durafmt) - Better time duration formatting in Go! - ★ 200



* [timeutil](https://github.com/leekchan/timeutil) - timeutil - useful extensions (Timedelta, Strftime, ...) to the golang&#39;s time package - ★ 150



* [timespan](https://github.com/SaidinWoT/timespan) - Golang package to manipulate time intervals. - ★ 57



* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang) - ★ 38



* [date](https://github.com/rickb777/date) - A Go package for working with dates - ★ 20



* [goweek](https://github.com/grsmv/goweek) - ISO 8601 compatible library for working with week entities for Go - ★ 16



* [feiertage](https://github.com/wlbr/feiertage) - Gesetzliche Feiertage und mehr in Deutschland und Österreich (Bank holidays/public holidays in Austria and Germany) - ★ 15



* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Go package for calculating the sunrise and sunset times for a given location - ★ 8



* [nulltime](https://github.com/kirillDanshin/nulltime) - ★ 7



* [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible strftime for golang - ★ 6



* [Kair](https://github.com/GuilhermeCaruso/Kair) - Date and Time - Golang Formatting Library - ★ 5



* [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter for use with Go time.Time instances. - ★ 5




## Distributed Systems



* [etcd](https://github.com/coreos/etcd/tree/master/raft) - ★ 21176



* [kit](https://github.com/go-kit/kit) - A standard library for microservices. - ★ 11792



* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC - ★ 6819



* [jaeger](https://github.com/jaegertracing/jaeger) - CNCF Jaeger, a Distributed Tracing System - ★ 6344



* [micro](https://github.com/micro/micro) - A cloud-native toolkit - ★ 5018



* [gnatsd](https://github.com/nats-io/gnatsd) - High-Performance server for NATS, the cloud native messaging system. - ★ 4823



* [libzmq](https://github.com/zeromq/libzmq) - ZeroMQ core engine in C++, implements ZMTP/3.1 - ★ 4702



* [rpcx](https://github.com/smallnest/rpcx) - Faster multil-language bidirectional RPC framework in Go, like alibaba Dubbo and weibo Motan in Java, but with more features, Scale easily. - ★ 2924



* [tendermint](https://github.com/tendermint/tendermint) - ⟁ Tendermint Core (BFT Consensus) in Go - ★ 2473



* [torrent](https://github.com/anacrolix/torrent) - Full-featured BitTorrent client package and utilities - ★ 2473



* [glow](https://github.com/chrislusf/glow) - Glow is an easy-to-use distributed computation system written in Go, similar to Hadoop Map Reduce, Spark, Flink, Storm, etc. I am also working on another similar pure Go system, , which is more flexible and more performant. - ★ 2225



* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol - ★ 2220



* [gleam](https://github.com/chrislusf/gleam) - Fast, efficient, and scalable distributed map/reduce system, DAG execution, in memory or on disk, written in pure Go, runs standalone or distributedly. - ★ 1648



* [emitter](https://github.com/emitter-io/emitter) - High performance, distributed and low latency publish-subscribe platform. - ★ 1426



* [krakend](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway with middlewares - ★ 1020



* [hprose-golang](https://github.com/hprose/hprose-golang) - Hprose is a cross-language RPC. This project is Hprose 2.0 for Golang. - ★ 856



* [heimdall](https://github.com/gojektech/heimdall) - An enhanced HTTP client for Go - ★ 599



* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications - ★ 505



* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable golang rpc library for high load - ★ 493



* [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous health checks in your service - ★ 385



* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Go Peerflix - ★ 339



* [sleuth](https://github.com/ursiform/sleuth) - A Go library for master-less peer-to-peer autodiscovery and RPC between HTTP services - ★ 279



* [digota](https://github.com/digota/digota) - ecommerce microservice - ★ 248



* [go-jump](https://github.com/dgryski/go-jump) - go-jump: Jump consistent hashing - ★ 211



* [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads in Golang - ★ 136



* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0 - ★ 85



* [redis-lock](https://github.com/bsm/redis-lock) - ★ 79



* [jsonrpc](https://github.com/ybbus/jsonrpc) - A simple go implementation of json rpc 2.0 client over http - ★ 65



* [celeriac.v1](https://github.com/svcavallar/celeriac.v1) - Golang client library for adding support for interacting and monitoring Celery workers, tasks and events. - ★ 43



* [drmaa](https://github.com/dgruber/drmaa) - Compute cluster (HPC) job submission library for Go (#golang) based on the open DRMAA standard. - ★ 21



* [flowgraph](https://github.com/vectaport/flowgraph) - Flowgraph package for scalable asynchronous system development - ★ 2




## Email



* [MailHog](https://github.com/mailhog/MailHog) - Web and API based SMTP testing - ★ 4026



* [gomail](https://github.com/go-gomail/gomail/) - The best way to send emails in Go. - ★ 1939



* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails for sending transactional mail - ★ 1366



* [email](https://github.com/jordan-wright/email) - Robust and flexible email library for Go - ★ 951



* [go-imap](https://github.com/emersion/go-imap) - An IMAP library for clients and servers - ★ 545



* [sendgrid-go](https://github.com/sendgrid/sendgrid-go) - The Official SendGrid Led, Community Driven Golang API Library - ★ 419



* [hectane](https://github.com/hectane/hectane) - Lightweight SMTP client written in Go - ★ 158



* [douceur](https://github.com/aymerick/douceur) - A simple CSS parser and inliner in Go - ★ 135



* [go-message](https://github.com/emersion/go-message) - A streaming Go library for the Internet Message Format and mail messages - ★ 70



* [smtp](https://github.com/mailhog/smtp) - MailHog SMTP Protocol - ★ 48



* [go-dkim](https://github.com/toorop/go-dkim) - DKIM package for golang - ★ 45




## Embeddable Scripting Languages



* [otto](https://github.com/robertkrimen/otto) - A JavaScript interpreter in Go (golang) - ★ 4178



* [gopher-lua](https://github.com/yuin/gopher-lua) - GopherLua: VM and compiler for Lua in Go - ★ 2408



* [gopher-lua](https://github.com/yuin/gopher-lua) - GopherLua: VM and compiler for Lua in Go - ★ 2408



* [go-lua](https://github.com/Shopify/go-lua) - A Lua VM in Go - ★ 1400



* [anko](https://github.com/mattn/anko) - Scriptable interpreter written in golang - ★ 777



* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API - ★ 759



* [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go - ★ 608



* [go-php](https://github.com/deuill/go-php) - PHP bindings for the Go programming language (Golang) - ★ 540



* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API - in progress - ★ 410



* [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go - ★ 406



* [agora](https://github.com/PuerkitoBio/agora) - a dynamically typed, garbage collected, embeddable programming language built with Go - ★ 308



* [expr](https://github.com/antonmedv/expr) - Expr is an engine that can evaluate expressions. - ★ 210



* [purl](https://github.com/ian-kent/purl) - Perl, but fluffy like a cat! - ★ 23



* [binder](https://github.com/alexeyco/binder) - High level go to Lua binder. Write less, do more. - ★ 21



* [ngaro](https://github.com/db47h/ngaro) - An embeddable implementation of the Ngaro Virtual Machine for Go programs - ★ 15




## Files



* [afero](https://github.com/spf13/afero) - A FileSystem Abstraction System for Go - ★ 1751



* [pdfcpu](https://github.com/hhrutter/pdfcpu) - A PDF processor written in Go. - ★ 697



* [notify](https://github.com/rjeczalik/notify) - File system event notification library on steroids. - ★ 398



* [skywalker](https://github.com/dixonwille/skywalker) - A package to allow one to concurrently go through a filesystem with ease - ★ 38



* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Read csv file from go using tags - ★ 34



* [tarfs](https://github.com/posener/tarfs) - An implementation of the FileSystem interface for tar files. - ★ 25



* [go-gtfs](https://github.com/artonge/go-gtfs) - Load GTFS files in golang - ★ 8



* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - copy files for humans - ★ 6




## Financial



* [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers in go - ★ 1167



* [go-finance](https://github.com/FlashBoys/go-finance) - Deprecrated in favor of - ★ 540



* [go-money](https://github.com/rhymond/go-money) - Go implementation of Fowler&#39;s Money pattern - ★ 492



* [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang - ★ 415



* [techan](https://github.com/sdcoffey/techan) - Technical Analysis Library for Golang - ★ 76



* [vat](https://github.com/dannyvankooten/vat) - Go package for dealing with EU VAT. Does VAT number validation &amp; rates retrieval. - ★ 51



* [ofxgo](https://github.com/aclindsa/ofxgo) - Golang library for querying and parsing OFX - ★ 48



* [transaction](https://github.com/claygod/transaction) - Embedded database for accounts transactions. - ★ 31



* [go-finance](https://github.com/alpeb/go-finance) - Go library containing a collection of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. - ★ 25




## Forms



* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go. - ★ 884



* [binding](https://github.com/mholt/binding) - Reflectionless data binding for Go&#39;s net/http (not yet a stable 1.0, but not likely to change much either) - ★ 713



* [csrf](https://github.com/gorilla/csrf) - gorilla/csrf provides Cross Site Request Forgery (CSRF) prevention middleware for Go web applications &amp; services. - ★ 332



* [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. - ★ 301



* [conform](https://github.com/leebenson/conform) - Trims, sanitizes &amp; scrubs data based on struct tags (go, golang) - ★ 147



* [formam](https://github.com/monoculum/formam) - a package for decode form&#39;s values into struct in Go - ★ 107



* [forms](https://github.com/albrow/forms) - A lightweight go library for parsing form data or json from an http.Request. - ★ 94



* [bind](https://github.com/robfig/bind) - ★ 20




## Game Development



* [leaf](https://github.com/name5566/leaf) - A game server framework in Go (golang) - ★ 2479



* [pixel](https://github.com/faiface/pixel) - A hand-crafted 2D game library in Go - ★ 1796



* [ebiten](https://github.com/hajimehoshi/ebiten) - A dead simple 2D game library in Go - ★ 1166



* [go-sdl2](https://github.com/veandco/go-sdl2) - SDL2 binding for Go - ★ 985



* [gonet](https://github.com/xtaci/gonet) - A Game Server Skeleton in golang. - ★ 962



* [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox - ★ 931



* [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. - ★ 892



* [goworld](https://github.com/xiaonanln/goworld) - Scalable Distributed Game Server Engine with Hot Swapping in Golang - ★ 835



* [nano](https://github.com/lonnng/nano) - Lightweight, facility, high performance golang based game server framework - ★ 733



* [oak](https://github.com/oakmound/oak) - A pure Go game engine - ★ 538



* [engine](https://github.com/g3n/engine) - Go 3D Game Engine - ★ 469



* [engine](https://github.com/azul3d/engine) - Azul3D - A 3D game engine written in Go! - ★ 390



* [GarageEngine](https://github.com/vova616/GarageEngine) - Game engine written in Go (golang). - ★ 304



* [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for raylib, a simple and easy-to-use library to learn videogames programming. - ★ 293



* [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A* search algorithm - ★ 287



* [go3d](https://github.com/ungerik/go3d) - A performance oriented 2D/3D math package for Go - ★ 142



* [pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. - ★ 78



* [glop](https://github.com/runningwild/glop) - Bare-bones osx alternative to sdl - ★ 76



* [go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format. - ★ 12




## Generation and Generics



* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ capabilities in Go - ★ 1552



* [jennifer](https://github.com/dave/jennifer) - Jennifer is a code generator for Go - ★ 976



* [gen](https://github.com/clipperhouse/gen) - Type-driven code generation for Go - ★ 939



* [goderive](https://github.com/awalterschulze/goderive) - Functional programming for Golang - ★ 626



* [gowrap](https://github.com/hexdigest/gowrap) - GoWrap is a command line tool for generating decorators for Go interfaces - ★ 148



* [interfaces](https://github.com/rjeczalik/interfaces) - Code generation tools for Go. - ★ 144



* [pkgreflect](https://github.com/ungerik/pkgreflect) - A Go preprocessor for package scoped reflection - ★ 71



* [go-enum](https://github.com/abice/go-enum) - An enum generator for go - ★ 61



* [efaceconv](https://github.com/t0pep0/efaceconv) - ★ 35




## Geographic



* [tile38](https://github.com/tidwall/tile38) - Tile38 is a geospatial database, spatial index, and realtime geofence. - ★ 5000



* [geo](https://github.com/golang/geo) - S2 geometry library in Go - ★ 746



* [geocache](https://github.com/melihmucuk/geocache) - Geocache is an in-memory cache that is suitable for geolocation based applications. - ★ 93



* [osm](https://github.com/paulmach/osm) - General purpose library for reading, writing and working with OpenStreetMap data - ★ 27



* [geoserver](https://github.com/hishamkaram/geoserver) - geoserver is a Go library for manipulating a GeoServer instance via the GeoServer REST API. - ★ 13



* [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang parser - ★ 9



* [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver - ★ 0




## Go Compilers



* [gopherjs](https://github.com/gopherjs/gopherjs) - A compiler from Go to JavaScript for running Go code in a browser - ★ 7555



* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go - ★ 930



* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang-&gt;Haxe-&gt;CPP/CSharp/Java/JavaScript transpiler - ★ 380



* [c4go](https://github.com/Konstantin8105/c4go) - transpiling C code to Go code - ★ 43



* [f4go](https://github.com/Konstantin8105/f4go) - Transpiling fortran code to golang code - ★ 7




## Goroutines



* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker that runs 10 to 100,000* times faster than Ruby-based workers. - ★ 2067



* [tunny](https://github.com/Jeffail/tunny) - A goroutine pool for Go - ★ 957



* [ants](https://github.com/panjf2000/ants) - A high-performance goroutine pool for go - ★ 930



* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool - ★ 428



* [pool](https://github.com/go-playground/pool) - a limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation - ★ 402



* [go-floc](https://github.com/workanator/go-floc) - Floc: Orchestrate goroutines with ease. - ★ 160



* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Simply way to control goroutines execution order based on dependencies - ★ 86



* [workerpool](https://github.com/gammazero/workerpool) - Concurrency limiting goroutine pool - ★ 51



* [GoSlaves](https://github.com/themester/GoSlaves) - Fast asynchonous goroutine pool for Golang - ★ 48



* [semaphore](https://github.com/marusama/semaphore) - Fast resizable golang semaphore - ★ 44



* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channels. - ★ 36



* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier golang implementation - ★ 20



* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel - ★ 20



* [worker-pool](https://github.com/vardius/worker-pool) - Go simple async worker pool - ★ 19



* [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic. It also provides an error stack aiming to facilitate fail causes discovery. - ★ 11



* [threadpool](https://github.com/shettyh/threadpool) - Golang simple thread pool implementation - ★ 6



* [stl](https://github.com/ssgreg/stl) - Software Transactional Locks - ★ 5



* [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang - ★ 4



* [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching - ★ 1




## GUI



* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. - ★ 6118



* [qt](https://github.com/therecipe/qt) - Qt binding for Go (Golang) with support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi / AsteroidOS / Ubuntu Touch / JavaScript / WebAssembly - ★ 4766



* [robotgo](https://github.com/go-vgo/robotgo) - RobotGo, Go Native cross-platform GUI automation - ★ 3561



* [webview](https://github.com/zserge/webview) - Tiny cross-platform webview library for C/C++/Golang. Uses WebKit (Gtk/Cocoa) and MSHTML (Windows) - ★ 3073



* [walk](https://github.com/lxn/walk) - A Windows GUI toolkit for the Go Programming Language - ★ 2987



* [app](https://github.com/murlokswarm/app) - Package to build GUI apps with Go, HTML and CSS. - ★ 2527



* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron) - ★ 2062



* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Golang bindings of Sciter: the Embeddable HTML/CSS/script engine for modern UI development - ★ 1202



* [systray](https://github.com/getlantern/systray) - a cross platfrom Go library to place an icon and menu in the notification area - ★ 551



* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3 - ★ 548



* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - gosx-notifier is a Go framework for sending desktop notifications to OSX 10.8 or higher - ★ 459



* [fyne](https://github.com/fyne-io/fyne) - Cross platform GUIs in Go based on EFL - ★ 199



* [gowd](https://github.com/dtylman/gowd) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by nwjs) - ★ 149



* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system&#39;s taskbar. - ★ 136




## Images



* [ln](https://github.com/fogleman/ln) - 3D line art engine. - ★ 2299



* [imaginary](https://github.com/h2non/imaginary) - Fast, simple, scalable HTTP microservice for high-level image processing with first-class Docker support - ★ 2033



* [imaging](https://github.com/disintegration/imaging) - Imaging is a simple image processing package for Go - ★ 1967



* [resize](https://github.com/nfnt/resize) - Pure golang image resizing - ★ 1927



* [bild](https://github.com/anthonynsimon/bild) - A collection of parallel image processing algorithms in pure Go - ★ 1848



* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3+ and beyond. - ★ 1688



* [pt](https://github.com/fogleman/pt) - A path tracer written in Go. - ★ 1662



* [gg](https://github.com/fogleman/gg) - Go Graphics - 2D rendering in Go with a simple API. - ★ 1542



* [smartcrop](https://github.com/muesli/smartcrop) - smartcrop finds good image crops for arbitrary crop sizes - ★ 1180



* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation - ★ 1169



* [gift](https://github.com/disintegration/gift) - Go Image Filtering Toolkit - ★ 1131



* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV / 2.x API in gocv / 1.x API in opencv - ★ 992



* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string in golang. - ★ 967



* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go - ★ 900



* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick&#39;s MagickWand C API - ★ 810



* [bimg](https://github.com/h2non/bimg) - Small Go package for fast high-level image processing powered by libvips C library - ★ 612



* [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go - ★ 335



* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. - ★ 268



* [govatar](https://github.com/o1egl/govatar) - Avatar generator library for GO language - ★ 266



* [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII - ★ 199



* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD - ★ 155



* [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package - ★ 145



* [img](https://github.com/hawx/img) - A selection of image manipulation tools - ★ 125



* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library - ★ 79



* [go-gd](https://github.com/bolknote/go-gd) - Go bingings for GD ( ) - ★ 47



* [mergi](https://github.com/noelyahan/mergi) - Imaging 4 terminal lovers (merge, crop, resize, watermark, animate) - ★ 34



* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go - ★ 24



* [tga](https://github.com/ftrvxmtrx/tga) - Go package for decoding and encoding TARGA image format - ★ 19



* [steganography](https://github.com/auyer/steganography) - Pure Golang Library that allows simple LSB steganography on images - ★ 10



* [cameron](https://github.com/aofei/cameron) - An avatar generator for Go. - ★ 9



* [mpo](https://github.com/donatj/mpo) - JPEG-MPO Decoder / Converter Library and CLI Tool - ★ 4




## IoT (Internet of Things)



* [gobot](https://github.com/hybridgroup/gobot/) - Golang framework for robotics, drones, and the Internet of Things (IoT) - ★ 4859



* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an open source ecosystem of opinionated event-driven capabilities to simplify building efficient &amp; modern serverless functions, microservices &amp; edge apps. - ★ 820



* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals - ★ 720



* [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server - ★ 218



* [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices (written in Go), experimental for x/exp/io - ★ 211



* [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT - ★ 157



* [connectordb](https://github.com/connectordb/connectordb) - An Open-Source Platform for Quantified Self &amp; IoT - ★ 122



* [eywa](https://github.com/xcodersun/eywa) - Make IoT a lot more fun with data. - ★ 22



* [iot](https://github.com/vaelen/iot/) - A Golang client for Google IoT Core - ★ 21




## Logging



* [logrus](https://github.com/Sirupsen/logrus) - Structured, pluggable logging for Go. - ★ 8917



* [logrus](https://github.com/Sirupsen/logrus) - Structured, pluggable logging for Go. - ★ 8917



* [zap](https://github.com/uber-go/zap) - Blazing fast, structured, leveled logging in Go. - ★ 5491



* [go-spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging - ★ 2688



* [glog](https://github.com/golang/glog) - Leveled execution logs for Go - ★ 2023



* [zerolog](https://github.com/rs/zerolog) - Zero Allocation JSON Logger - ★ 1486



* [tail](https://github.com/hpcloud/tail) - Go package for reading from continously updated files (tail -f) - ★ 1236



* [seelog](https://github.com/cihub/seelog) - Seelog is a native Go logging library that provides flexible asynchronous dispatching, filtering, and formatting. - ★ 1215



* [lumberjack](https://github.com/natefinch/lumberjack) - lumberjack is a log rolling package for Go - ★ 1041



* [log15](https://github.com/inconshreveable/log15) - Structured, composable logging for Go - ★ 816



* [log](https://github.com/apex/log) - Structured logging package for Go. - ★ 621



* [logxi](https://github.com/mgutz/logxi) - A 12-factor app logger built for performance and happy development - ★ 327



* [onelog](https://github.com/francoispqt/onelog) - Dead simple, super fast, zero allocation and modular logger for Golang - ★ 291



* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go. - ★ 256



* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang). - ★ 228



* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger for Go programs. Allows custom formats for messages. - ★ 199



* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go. - ★ 129



* [xlog](https://github.com/rs/xlog) - xlog is a logger for net/context aware HTTP applications - ★ 127



* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - A Go (golang) package providing high-performance asynchronous logging, message filtering by severity and category, and multiple message targets. - ★ 96



* [logvoyage](https://github.com/firstrow/logvoyage) - LogVoyage - logging SaaS written in GoLang - ★ 82



* [log](https://github.com/alexcesaro/log) - Logging packages for Go - ★ 44



* [gologger](https://github.com/sadlil/gologger) - Simple Logger for golang. Logs Into console, file or ElasticSearch. Simple, easy to use. - ★ 38



* [logex](https://github.com/chzyer/logex) - An golang log lib, supports tracking and level, wrap by standard log lib - ★ 33



* [go-log](https://github.com/ian-kent/go-log) - A logger, for Go - ★ 31



* [logrusly](https://github.com/sebest/logrusly) - Loggly Hooks for GO Logrus logger - ★ 24



* [glg](https://github.com/kpango/glg) - Simple and fast lockfree logging library for golang - ★ 23



* [gone](https://github.com/One-com/gone/tree/master/log) - ★ 22



* [go-log](https://github.com/siddontang/go-log) - a golang log lib supports level and multi handlers - ★ 19



* [log](https://github.com/teris-io/log) - Structured log interface - ★ 19



* [mlog](https://github.com/jbrodriguez/mlog) - A simple logging module for go, with a rotating file feature and console logging. - ★ 16



* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Time based rotating file writer - ★ 15



* [distillog](https://github.com/amoghe/distillog) - Logging, distilled - ★ 14



* [gomol](https://github.com/aphistic/gomol) - Gomol is a library for structured, multiple-output logging for Go with extensible logging outputs - ★ 12



* [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal&#39;s native API for logging - ★ 12



* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging - ★ 7



* [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers - ★ 6



* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers. - ★ 4



* [xlog](https://github.com/xfxdev/xlog) - plugin architecture and flexible log system for golang - ★ 3



* [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration - ★ 1




## Machine Learning



* [golearn](https://github.com/sjwhitworth/golearn) - Machine Learning for Go - ★ 6080



* [gorgonia](https://github.com/chewxy/gorgonia) - Gorgonia is a library that helps facilitate machine learning in Go. - ★ 2243



* [tfgo](https://github.com/galeone/tfgo) - Tensorflow + Go, the gopher way - ★ 981



* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go (and so much more) - ★ 924



* [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library - ★ 657



* [CloudForest](https://github.com/ryanbressler/CloudForest) - Ensembles of decision trees in go/golang. - ★ 619



* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. - ★ 578



* [eaopt](https://github.com/MaxHalford/eaopt) - Evolutionary optimization library for Go (genetic algorithm, partical swarm optimization, differential evolution) - ★ 557



* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go - ★ 293



* [regommend](https://github.com/muesli/regommend) - Recommendation engine for Go - ★ 219



* [go-deep](https://github.com/patrikeh/go-deep) - Artificial Neural Network - ★ 178



* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang - ★ 162



* [goRecommend](https://github.com/timkaye11/goRecommend) - Collaborative Filtering (CF) Algorithms in Go! - ★ 125



* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go - ★ 118



* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for FANN, library for artificial neural networks - ★ 97



* [goga](https://github.com/tomcraven/goga) - Golang Genetic Algorithm - ★ 69



* [libsvm](https://github.com/datastream/libsvm) - libsvm go version - ★ 58



* [neural-go](https://github.com/schuyler/neural-go) - A multilayer perceptron network implemented in Go, with training via backpropagation. - ★ 58



* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. - ★ 55



* [neat](https://github.com/jinyeom/neat) - NEAT (NeuroEvolution of Augmenting Topologies) implemented in Go - ★ 47



* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go - ★ 36



* [fonet](https://github.com/Fontinalis/fonet) - fonet is a deep neural network package for Go. - ★ 21



* [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML - ★ 21



* [godist](https://github.com/e-dard/godist) - Probability distributions and associated methods in Go - ★ 20



* [Varis](https://github.com/Xamber/Varis) - Golang Neural Network - ★ 17



* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - k-modes and k-prototypes clustering algorithms implementation in Go - ★ 14



* [probab](https://github.com/ThePaw/probab) - Automatically exported from code.google.com/p/probab - ★ 9



* [gomind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go - ★ 5



* [mlgo](https://github.com/NullHypothesis/mlgo) - Automatically exported from code.google.com/p/mlgo - ★ 4




## Messaging



* [sarama](https://github.com/Shopify/sarama) - Sarama is a Go library for Apache Kafka 0.8, and up. - ★ 3596



* [centrifugo](https://github.com/centrifugal/centrifugo) - Language-agnostic real-time messaging server (Websocket and SockJS) - ★ 3104



* [gorush](https://github.com/appleboy/gorush) - A push notification server written in Go (Golang). - ★ 3032



* [machinery](https://github.com/RichardKnop/machinery) - Machinery is an asynchronous task queue/job queue based on distributed message passing. - ★ 2675



* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. - ★ 2434



* [go-nats](https://github.com/nats-io/nats) - Golang client for NATS, the cloud native messaging system. - ★ 1926



* [apns2](https://github.com/sideshow/apns2) - ⚡ HTTP/2 Apple Push Notification Service (APNs) push provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps, using the APNs HTTP/2 protocol. - ★ 1871



* [apns2](https://github.com/sideshow/apns2) - ⚡ HTTP/2 Apple Push Notification Service (APNs) push provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps, using the APNs HTTP/2 protocol. - ★ 1871



* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - Golang push server cluster - ★ 1745



* [benthos](https://github.com/Jeffail/benthos) - A dull, resilient and quick to deploy stream processor - ★ 1618



* [mangos](https://github.com/go-mangos/mangos) - package mangos is an implementation in pure Go of the SP (&quot;Scalable Protocols&quot;) protocols. - ★ 1478



* [go-nsq](https://github.com/nsqio/go-nsq) - The official Go package for NSQ - ★ 1218



* [melody](https://github.com/olahol/melody) - Minimalist websocket framework for Go - ★ 1187



* [uniqush-push](https://github.com/uniqush/uniqush-push) - Uniqush is a free and open source software system which provides a unified push service for server side notification to apps on mobile devices. - ★ 1028



* [zmq4](https://github.com/pebbe/zmq4) - A Go interface to ZeroMQ version 4 - ★ 696



* [gollum](https://github.com/trivago/gollum) - An n:m message multiplexer written in Go - ★ 632



* [EventBus](https://github.com/asaskevich/EventBus) - [Go] Lightweight eventbus with async compatibility for Go - ★ 443



* [golongpoll](https://github.com/jcuga/golongpoll) - golang long polling library. Makes web pub-sub easy via HTTP long-poll server - ★ 381



* [mercure](https://github.com/dunglas/mercure) - Server-sent live updates: protocol and reference implementation - ★ 359



* [glue](https://github.com/desertbit/glue) - Glue - Robust Go and Javascript Socket Library (Alternative to Socket.io) - ★ 292



* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus - ★ 285



* [emitter](https://github.com/olebedev/emitter) - Emits events in Go way, with wildcard, predicates, cancellation possibilities and many other good wins - ★ 251



* [pubsub](https://github.com/tuxychandru/pubsub) - A simple pubsub package for go. - ★ 225



* [guble](https://github.com/smancke/guble) - websocket based messaging server written in golang - ★ 133



* [zmq3](https://github.com/pebbe/zmq3) - A Go interface to ZeroMQ version 3 - ★ 127



* [go-gcm](https://github.com/google/go-gcm) - GCM library for Go. - ★ 102



* [oplog](https://github.com/dailymotion/oplog) - A generic oplog/replication system for microservices - ★ 91



* [drone-line](https://github.com/appleboy/drone-line) - Sending line notifications using a binary, docker or Drone CI. - ★ 52



* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a pure, extremely productive, lightweight and reliable library for managing of the local messages queue - ★ 47



* [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues - ★ 46



* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel - ★ 39



* [go-notify](https://github.com/TheCreeper/go-notify) - Package notify provides an implementation of the Gnome DBus Notifications Specification. - ★ 38



* [goose](https://github.com/ian-kent/goose) - Server-Sent Events in Go - ★ 34



* [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ wire tap and swiss army knife - ★ 33



* [message-bus](https://github.com/vardius/message-bus) - Go simple async message bus - ★ 25



* [zmq2](https://github.com/pebbe/zmq2) - A Go interface to ZeroMQ version 2 - ★ 17



* [event](https://github.com/agoalofalife/event) - The implementation of the pattern observer - ★ 16



* [hub](https://github.com/leandro-lugaresi/hub) - A fast Message/Event Hub using publish/subscribe pattern with support for topics like* rabbitMQ exchanges for Go applications - ★ 12



* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - golang client library to Viessmann Vitotrol web service - ★ 10



* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go - ★ 7




## Miscellaneous



* [errors](https://github.com/pkg/errors) - Simple error handling primitives - ★ 3634



* [gopsutil](https://github.com/shirou/gopsutil) - psutil for golang - ★ 3057



* [go.uuid](https://github.com/satori/go.uuid) - UUID package for Go - ★ 2539



* [archiver](https://github.com/mholt/archiver) - Easily create and extract .zip, .tar, .tar.gz, .tar.bz2, .tar.xz, .tar.lz4, .tar.sz, and .rar (extract-only) files with Go - ★ 1653



* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go - ★ 1174



* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang - ★ 701



* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - a generic object pool for golang - ★ 550



* [xstrings](https://github.com/huandu/xstrings) - Package xstrings: A collection of useful string functions in Go. - ★ 517



* [go-multierror](https://github.com/hashicorp/go-multierror) - A Go (golang) package for representing a list of errors as a single error. - ★ 515



* [jobs](https://github.com/albrow/jobs) - A persistent and flexible background jobs library for go. - ★ 432



* [base64Captcha](https://github.com/mojocn/base64Captcha) - golang base64-captcha supports digits, numbers,alphabet, arithmetic, audio and digit-alphabet captcha - ★ 423



* [bot](https://github.com/go-chat-bot/bot) - IRC, Slack, Telegram and RocketChat bot written in go - ★ 369



* [shortid](https://github.com/teris-io/shortid) - Super short, fully unique, non-sequential and URL friendly Ids - ★ 348



* [go-conv](https://github.com/cstockton/go-conv) - Fast conversions across various Go types with a simple API. - ★ 331



* [health](https://github.com/dimiro1/health) - An easy to use, extensible health check library for Go applications. - ★ 327



* [uuid](https://github.com/gofrs/uuid) - A UUID package originally forked from github.com/satori/go.uuid - ★ 325



* [slacker](https://github.com/shomali11/slacker) - Slack Bot Framework - ★ 218



* [wuid](https://github.com/edwingeng/wuid) - An extremely fast UUID alternative written in golang - ★ 214



* [banner](https://github.com/dimiro1/banner) - An easy way to add useful startup banners into your Go applications - ★ 190



* [gofakeit](https://github.com/brianvoe/gofakeit) - Random fake data generator written in go - ★ 188



* [gountries](https://github.com/pariz/gountries) - Gountries provides: Countries (ISO-3166-1), Country Subdivisions(ISO-3166-2), Currencies (ISO 4217), Geo Coordinates(ISO-6709) as well as translations, country borders and other stuff exposed as struct data. - ★ 181



* [antch](https://github.com/antchfx/antch) - Antch, a fast, powerful and extensible web crawling &amp; scraping framework for Go - ★ 110



* [go-sarah](https://github.com/oklahomer/go-sarah) - Simple yet customizable bot framework written in Go. - ★ 109



* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... - ★ 108



* [battery](https://github.com/distatus/battery) - cross-platform, normalized battery information library - ★ 106



* [ffmt](https://github.com/go-ffmt/ffmt) - Golang beautify data display for Humans - ★ 84



* [lk](https://github.com/hyperboloide/lk) - Simple licensing library for golang. - ★ 77



* [hanu](https://github.com/sbstjn/hanu) - Golang Framework for writing Slack bots - ★ 76



* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go. - ★ 67



* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go - ★ 57



* [gommit](https://github.com/antham/gommit) - Enforce git message commit consistency - ★ 55



* [healthcheck](https://github.com/etherlabsio/healthcheck) - An simple, easily extensible and concurrent health-check library for Go services - ★ 54



* [margelet](https://github.com/zhulik/margelet) - Telegram Bot Framework for Go - ★ 48



* [go-unarr](https://github.com/gen2brain/go-unarr) - Go bindings for unarr (decompression library for RAR, TAR, ZIP and 7z archives) - ★ 44



* [indigo](https://github.com/osamingo/indigo) - A distributed unique ID generator of using Sonyflake and encoded by Base58 - ★ 41



* [morse](https://github.com/alwindoss/morse) - Morse Code Library in Go - ★ 38



* [xkg](https://github.com/go-xkg/xkg) - User level X Keyboard Grabber - ★ 36



* [strutil](https://github.com/ozgio/strutil) - String utilities for Go - ★ 34



* [alice](https://github.com/magic003/alice) - An additive dependency injection container for Golang. - ★ 29



* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for Browser Capabilities Project - ★ 27



* [datacounter](https://github.com/miolini/datacounter) - Golang counters for readers/writers - ★ 25



* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation - ★ 24



* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in Go (Golang) - ★ 22



* [autoflags](https://github.com/artyom/autoflags) - Populate go command line app flags from config struct - ★ 21



* [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests - ★ 17



* [ghorg](https://github.com/gabrie30/ghorg) - Quickly clone an entire GitHub org into one directory - ★ 13



* [Goid](https://github.com/jakehl/goid) - A UUIDv4 generation package written in go - ★ 13



* [gosh](https://github.com/osamingo/gosh) - Go Statistics Handler - ★ 11



* [url-shortener](https://github.com/pantrif/url-shortener) - A golang URL Shortener - ★ 9



* [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection - ★ 8



* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation - ★ 8



* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. - ★ 7



* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. - ★ 6



* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking hosts list - ★ 5



* [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID. - ★ 3



* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. - ★ 3



* [generators](https://github.com/azr/generators/tree/master/varhandler) - ★ 3








## Natural Language Processing



* [jieba](https://github.com/fxsjy/jieba) - 结巴中文分词 - ★ 15903



* [prose](https://github.com/jdkato/prose) - A Golang library for text processing, including tokenization, part-of-speech tagging, and named-entity extraction. - ★ 1811



* [when](https://github.com/olebedev/when) - A natural language date/time parser with pluggable rules - ★ 891



* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Translate your Go program into multiple languages. - ★ 760



* [gojieba](https://github.com/yanyiwu/gojieba) - &quot;结巴&quot;中文分词的Golang版本 - ★ 659



* [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other. Go 语言高性能分词 - ★ 615



* [go-pinyin](https://github.com/mozillazg/go-pinyin) - 汉字转拼音 - ★ 395



* [nlp](https://github.com/Shixzie/nlp) - [UNMANTEINED] Extract values from strings and fill your structs with nlp. - ★ 349



* [kagome](https://github.com/ikawaha/kagome) - Self-contained Japanese Morphological Analyzer written in pure Go - ★ 335



* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection library for Go - ★ 304



* [sentences](https://github.com/neurosnap/sentences) - A multilingual command line sentence tokenizer in Golang - ★ 240



* [nlp](https://github.com/james-bowman/nlp) - Selected Machine Learning algorithms for natural language processing and semantic analysis in Golang - ★ 168



* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work - ★ 76



* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator for #golang - ★ 59



* [textcat](https://github.com/pebbe/textcat) - A Go package for n-gram based text categorization, with support for utf-8 and raw text - ★ 58



* [MMSEGO](https://github.com/awsong/MMSEGO) - Chinese word splitting algorithm MMSEG in GO - ★ 57



* [go-stem](https://github.com/agonopol/go-stem) - Word Stemming in Go - ★ 49



* [segment](https://github.com/blevesearch/segment) - A Go library for performing Unicode Text Segmentation as described in Unicode Standard Annex #29 - ★ 43



* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English, German and Dutch stemmers. - ★ 41



* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text. - ★ 35



* [RAKE.Go](https://github.com/Obaied/RAKE.go) - A Go port of the Rapid Automatic Keyword Extraction algorithm (RAKE) - ★ 34



* [getlang](https://github.com/rylans/getlang) - Natural language detection package in pure Go - ★ 32



* [porter2](https://github.com/zhenjl/porter2) - High Performance Porter2 Stemmer - ★ 32



* [go2vec](https://github.com/danieldk/go2vec) - Read and use word2vec vectors in Go - ★ 30



* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm - ★ 24



* [snowball](https://github.com/goodsign/snowball) - Cgo binding for Snowball C library - ★ 21



* [mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - ★ 19



* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c library - ★ 17



* [petrovich](https://github.com/striker2000/petrovich) - Golang port of Petrovich - an inflector for Russian anthroponyms. - ★ 16



* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2 - ★ 15



* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library - ★ 10



* [shamoji](https://github.com/osamingo/shamoji) - The shamoji (杓文字) is word filtering package - ★ 9



* [porter](https://github.com/a2800276/porter) - porter stemmer - ★ 8



* [go-eco](https://github.com/ThePaw/go-eco) - Automatically exported from code.google.com/p/go-eco - ★ 4



* [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation) - ★ 2




## Networking



* [kcptun](https://github.com/xtaci/kcptun) - A Stable &amp; Secure Tunnel Based On KCP with N:M Multiplexing - ★ 9003



* [fasthttp](https://github.com/valyala/fasthttp) - Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http - ★ 7359



* [httplab](https://github.com/gchaincl/httplab) - The interactive web server - ★ 3225



* [dns](https://github.com/miekg/dns) - DNS library in Go - ★ 3171



* [gopacket](https://github.com/google/gopacket) - Provides packet processing capabilities for Go - ★ 2279



* [quic-go](https://github.com/lucas-clemente/quic-go) - A QUIC implementation in pure go - ★ 1831



* [kcp-go](https://github.com/xtaci/kcp-go) - A Production-Grade Reliable-UDP Library for golang - ★ 1746



* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language - ★ 1430



* [ssh](https://github.com/gliderlabs/ssh) - Easy SSH servers in Golang - ★ 862



* [water](https://github.com/songgao/water) - A simple TUN/TAP library written in native Go. - ★ 677



* [sftp](https://github.com/pkg/sftp) - SFTP support for the go.crypto/ssh package - ★ 575



* [go-getter](https://github.com/hashicorp/go-getter) - Package for downloading things from a string URL using a variety of protocols. - ★ 570



* [nff-go](https://github.com/intel-go/nff-go) - NFF-Go -Network Function Framework for GO (former YANFF) - ★ 536



* [fortio](https://github.com/fortio/fortio) - Fortio load testing library, command line tool, advanced echo server and web UI in go (golang). Allows to specify a set query-per-second load and record latency histograms and other useful stats. - ★ 514



* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS client/server library in Golang - ★ 453



* [lhttp](https://github.com/fanux/lhttp) - go websocket, a better way to buid your IM server - ★ 448



* [grab](https://github.com/cavaliercoder/grab) - A download manager package for Go - ★ 410



* [ftp](https://github.com/jlaffaye/ftp) - FTP client package for Go - ★ 395



* [gotcp](https://github.com/gansidui/gotcp) - A Go package for quickly building tcp servers - ★ 370



* [gosnmp](https://github.com/soniah/gosnmp) - An SNMP library written in GoLang. - ★ 366



* [gopcap](https://github.com/akrennmair/gopcap) - A simple wrapper around libpcap for the Go programming language - ★ 329



* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup in Golang - ★ 301



* [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure-Go library for cross-platform local peer discovery using UDP multicast - ★ 300



* [go-stun](https://github.com/ccding/go-stun) - A go implementation of the STUN client (RFC 3489 and RFC 5389) - ★ 273



* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. MIT Licensed. - ★ 238



* [tcp_server](https://github.com/firstrow/tcp_server) - golang tcp server - ★ 228



* [buffstreams](https://github.com/stabbycutyou/buffstreams) - A library to simplify writing applications using TCP sockets to stream protobuff messages - ★ 213



* [winrm](https://github.com/masterzen/winrm) - Command-line tool and library for Windows remote command execution in Go - ★ 179



* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. MIT Licensed. - ★ 161



* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. MIT Licensed. - ★ 155



* [stun](https://github.com/go-rtc/stun) - Fast RFC 5389 STUN implementation in go - ★ 153



* [utp](https://github.com/anacrolix/utp) - Use anacrolix/go-libutp instead - ★ 139



* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementing RFC 7252 for the Go Language - ★ 120



* [sslb](https://github.com/eduardonunesp/sslb) - Golang Super Simple Load Balance - ★ 107



* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple devices, similar to rancid, fetchconfig, oxidized, Sweet. - ★ 101



* [gnxi](https://github.com/google/gnxi) - gNXI Tools - gRPC Network Management/Operations Interface Tools - ★ 70



* [ether](https://github.com/songgao/ether) - A Go package for sending and receiving ethernet frames. Currently supporting Linux, Freebsd, and OS X. - ★ 57



* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. MIT Licensed. - ★ 52



* [xtcp](https://github.com/xfxdev/xtcp) - A TCP Server Framework with graceful shutdown, custom protocol. - ★ 48



* [portproxy](https://github.com/aybabtme/portproxy) - TCP proxy, highjacks HTTP to allow CORS - ★ 37



* [linkio](https://github.com/ian-kent/linkio) - Simulate network link speed - ★ 36



* [graval](https://github.com/koofr/graval) - An experimental go FTP server framework - ★ 23



* [publicip](https://github.com/polera/publicip) - Go pkg for returning your public facing IP address. - ★ 16



* [golibwireshark](https://github.com/sunwxg/golibwireshark) - ★ 12



* [goshark](https://github.com/sunwxg/goshark) - ★ 7



* [llb](https://github.com/kirillDanshin/llb) - ★ 7



* [packet](https://github.com/aerogo/packet) - Send network packets over a TCP or UDP connection. - ★ 7



* [tspool](https://github.com/two/tspool) - tcp server pool - ★ 0




## OpenGL



* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow) - ★ 534



* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3 - ★ 529



* [mathgl](https://github.com/go-gl/mathgl) - A pure Go 3D math library. - ★ 249



* [gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings. - ★ 127



* [glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. - ★ 54




## ORM



* [beego](https://github.com/astaxie/beego/tree/master/orm) - ★ 17708



* [gorm](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly - ★ 11124



* [xorm](https://github.com/go-xorm/xorm) - Simple and Powerful ORM for Go, support mysql,postgres,tidb,sqlite3,mssql,oracle - ★ 4008



* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence - an ORM-ish library for Go - ★ 2900



* [pg](https://github.com/go-pg/pg) - Golang ORM with focus on PostgreSQL features and performance - ★ 2137



* [sqlboiler](https://github.com/volatiletech/sqlboiler) - Generate a Go ORM tailored to your database schema. - ★ 1663



* [db](https://github.com/upper/db) - Productive data access layer for Go. - ★ 1383



* [reform](https://github.com/go-reform/reform) - A better ORM for Go, based on non-empty interfaces and code generation. - ★ 695



* [qbs](https://github.com/coocood/qbs) - QBS stands for Query By Struct. A Go ORM. - ★ 516



* [pop](https://github.com/gobuffalo/pop) - A Tasty Treat For All Your Database Needs - ★ 505



* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM for Go (Golang) with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support. GORM under the hood. - ★ 358



* [zoom](https://github.com/albrow/zoom) - A blazing-fast datastore and querying engine for Go built on Redis. - ★ 225



* [go-store](https://github.com/gosuri/go-store) - A simple and fast Redis backed key-value store library for Go - ★ 90



* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM. - ★ 79



* [gomodel](https://github.com/cosiner/gomodel) - A lightweight, fast, orm-like library helps interactive with database - ★ 59



* [marlow](https://github.com/dadleyy/marlow) - golang generator for type-safe sql api constructs - ★ 35



* [grimoire](https://github.com/Fs02/grimoire) - Database access layer for golang. - ★ 28



* [lore](https://github.com/abrahambotros/lore) - Light Object-Relational Environment (LORE) provides a simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go - ★ 4




## Package Management



* [dep](https://github.com/golang/dep) - Go dependency management tool - ★ 10939



* [glide](https://github.com/Masterminds/glide) - Package Management for Golang - ★ 7239



* [godep](https://github.com/tools/godep) - dependency tool for go - ★ 5529



* [govendor](https://github.com/kardianos/govendor) - Go vendor tool that works with the standard vendor file. - ★ 4023



* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager (gopm) is a package manager and build tool for Go. - ★ 2017



* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go - ★ 1339



* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go. - ★ 1201



* [goop](https://github.com/nitrous-io/goop) - A simple dependency manager for Go (golang), inspired by Bundler. - ★ 774



* [gvt](https://github.com/FiloSottile/gvt) - gvt was a minimal go vendoring tool, based on gb-vendor. Today, you want to use modules instead. - ★ 754



* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies - ★ 247



* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Barebones dependency manager for Go. - ★ 213



* [gigo](https://github.com/LyricalSecurity/gigo) - GIGO: PIP for GO - ★ 196



* [VenGO](https://github.com/DamnWidget/VenGO) - Create and manage Isolated Virtual Environments for Go - ★ 111



* [gop](https://github.com/lunny/gop) - Manage dependencies and build Go projects outside GOPATH - ★ 47




## Query Language



* [graphql](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go / Golang - ★ 3864



* [graphql-go](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use - ★ 2090



* [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data - ★ 450



* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang. - ★ 177



* [rql](https://github.com/a8m/rql) - Resource Query Language for REST - ★ 75



* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities - ★ 47



* [graphql](https://github.com/sevki/graphql) - GraphQL implementation in go - ★ 36



* [jsonslice](https://github.com/bhmj/jsonslice) - json slicer - ★ 9




## Resource Embedding



* [statik](https://github.com/rakyll/statik) - Embed files into a Go executable - ★ 1557



* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images,templates, etc very easy. - ★ 1417



* [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries. - ★ 1359



* [vfsgen](https://github.com/shurcooL/vfsgen) - Takes an input http.FileSystem (likely at go generate time) and generates Go code that statically implements it. - ★ 415



* [esc](https://github.com/mjibson/esc) - A simple file embedder for Go - ★ 358



* [fileb0x](https://github.com/UnnoTed/fileb0x) - a better customizable tool to embed files in go; also update embedded files remotely without restarting the server - ★ 349



* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding for Go with out of box http.FileSystem support. - ★ 146



* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks - ★ 49



* [templify](https://github.com/wlbr/templify) - A tool to be used with &#39;go generate&#39; to embed external template files into Go code. - ★ 15



* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable - ★ 12




## Science and Data Analysis



* [streamtools](https://github.com/nytlabs/streamtools) - tools for working with streams of data - ★ 1311



* [gosl](https://github.com/cpmech/gosl) - Go scientific library for machine learning, linear algebra, FFT, Bessel, elliptic, orthogonal polys, geometry, NURBS, numerical quadrature, 3D transfinite interpolation, random numbers, Mersenne twister, probability distributions, optimisation, graph, plotting, visualisation, tensors, eigenvalues, differential equations, more. - ★ 1168



* [plot](https://github.com/gonum/plot) - A repository for plotting and visualizing data - ★ 973



* [stats](https://github.com/montanaflynn/stats) - A statistics package with common functions that are missing from the Golang standard library. - ★ 943



* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go - ★ 555



* [goraph](https://github.com/gyuho/goraph) - Package goraph implements graph data structure and algorithms. - ★ 535



* [chart](https://github.com/vdobler/chart) - Provide basic charts in go - ★ 519



* [matrix](https://github.com/gonum/matrix) - Matrix packages for the Go language [DEPRECATED] - ★ 460



* [ewma](https://github.com/VividCortex/ewma) - Exponentially Weighted Moving Average algorithms for Go. - ★ 241



* [graph](https://github.com/yourbasic/graph) - Graph algorithms and data structures - ★ 171



* [blas](https://github.com/ziutek/blas) - Go implementation of BLAS (Basic Linear Algebra Subprograms) - ★ 124



* [gohistogram](https://github.com/VividCortex/gohistogram) - Streaming approximate histograms in Go - ★ 112



* [orb](https://github.com/paulmach/orb) - Types and utilities for working with 2d geometry in Golang - ★ 61



* [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, phrase extraction) and multithreading (goroutine) support (Go 1.8, 1.9, 1.10) - ★ 53



* [sparse](https://github.com/james-bowman/sparse) - Sparse matrix formats for linear algebra supporting scientific and machine learning applications - ★ 45



* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank implementation in Go - ★ 41



* [geom](https://github.com/skelterjohn/geom) - 2d geometry for golang - ★ 36



* [evaler](https://github.com/soniah/evaler) - Implements a simple floating point arithmetic expression evaluator in Go (golang). - ★ 33



* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - DataFrame for statistics and data manipulation - ★ 20



* [go-fn](https://github.com/ematvey/go-fn) - Automatically exported from code.google.com/p/go-fn - ★ 10



* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures - ★ 10



* [ode](https://github.com/ChristopherRabotin/ode) - An ordinary differential equation solving library in golang. - ★ 7



* [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. - ★ 7



* [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. - ★ 6



* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - tiny linear interpolation library for go (factored out from ) - ★ 5



* [go-gt](https://github.com/ThePaw/go-gt) - Automatically exported from code.google.com/p/go-gt - ★ 4



* [gocomplex](https://github.com/varver/gocomplex) - Automatically exported from code.google.com/p/gocomplex - ★ 4



* [PiHex](https://github.com/claygod/PiHex) - PiHex Library, written in Go, generates a hexadecimal number sequence in the number Pi in the range from 0 to 10,000,000. - ★ 4




## Security



* [lego](https://github.com/xenolf/lego) - Let&#39;s Encrypt client and ACME library written in Go - ★ 2950



* [acme](https://github.com/hlandau/acme) - acmetool, an automatic certificate acquisition tool for ACME (Let&#39;s Encrypt) - ★ 1619



* [cameradar](https://github.com/Ullaakut/cameradar) - Cameradar hacks its way into RTSP videosurveillance cameras - ★ 1453



* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins. - ★ 1047



* [memguard](https://github.com/awnumar/memguard) - Easy and secure handling of sensitive memory, in pure Go. - ★ 827



* [nacl](https://github.com/kevinburke/nacl) - Pure Go implementation of the NaCL set of API&#39;s - ★ 371



* [acra](https://github.com/cossacklabs/acra) - Database encryption proxy for data-driven apps: strong selective encryption, SQL injections prevention, intrusion detection, honeypots. - ★ 322



* [badactor](https://github.com/jaredfolkins/badactor) - BadActor.org An in-memory application driven jailer written in Go - ★ 225



* [passlib](https://github.com/hlandau/passlib) - Idiotproof golang password validation library inspired by Python&#39;s passlib - ★ 204



* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys - ★ 169



* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - A convenience library for generating, comparing and inspecting password hashes using the scrypt KDF in Go. - ★ 141



* [go-yara](https://github.com/hillu/go-yara) - Go bindings for YARA - ★ 103



* [yara](https://github.com/plusvic/yara) - The pattern matching swiss knife - ★ 74



* [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hashing package for go with constant time hash comparison - ★ 63



* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid Golang utility library for securely hashing and encrypting passwords based on the Dropbox method. This implementation uses Blake2b, Scrypt and XSalsa20-Poly1305 (via NaCl SecretBox) to create secure password hashes that are also encrypted using a master passphrase. - ★ 20



* [goArgonPass](https://github.com/dwin/goArgonPass) - goArgonPass is a Argon2 Password utility package for Go using the crypto library package Argon2. Argon2 was the winner of the most recent Password Hashing Competition. This is designed for use anywhere password hashing and verification might be needed and is intended to replace implementations using bcrypt or Scrypt. - ★ 7




## Serialization



* [go](https://github.com/json-iterator/go) - A high-performance 100% compatible drop-in replacement of &quot;encoding/json&quot; - ★ 3836



* [protobuf](https://github.com/golang/protobuf) - Go support for Google&#39;s protocol buffers - ★ 3671



* [structs](https://github.com/fatih/structs) - Utilities for Go structs - ★ 2496



* [protobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets - ★ 2130



* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. - ★ 1790



* [go](https://github.com/ugorji/go) - idiomatic codec and rpc lib for msgpack, cbor, json, etc. msgpack.org[Go] - ★ 1034



* [colfer](https://github.com/pascaldekloe/colfer) - binary serialization format - ★ 408



* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap&#39;n Proto library and parser for go. This is go-capnproto-1.0, and does not have rpc. See for 2.0 which has rpc and capabilities. - ★ 266



* [csvutil](https://github.com/jszwec/csvutil) - csvutil provides fast and idiomatic mapping between CSV and Go (golang) values. - ★ 246



* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - PHP session encoder/decoder written in Go - ★ 101



* [structomap](https://github.com/tuvistavie/structomap) - Easily and dynamically generate maps from Go static structures - ★ 77



* [bambam](https://github.com/glycerine/bambam) - auto-generate capnproto schema from your golang source files. Depends on go-capnproto-1.0 at - ★ 59



* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang. - ★ 33



* [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoder/decoder) in GO (golang) - ★ 6




## Server Applications



* [etcd](https://github.com/coreos/etcd) - Distributed reliable key-value store for the most critical data of a distributed system - ★ 21176



* [caddy](https://github.com/mholt/caddy) - Fast, cross-platform HTTP/2 web server with automatic HTTPS - ★ 19118



* [minio](https://github.com/minio/minio) - Minio is an open source object storage server compatible with Amazon S3 APIs - ★ 13532



* [devd](https://github.com/cortesi/devd) - A local webserver for developers - ★ 2639



* [roadrunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager written in Golang - ★ 1761



* [fider](https://github.com/getfider/fider) - Open platform to collect and prioritize product feedback - ★ 533



* [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go (Golang). - ★ 513



* [algernon](https://github.com/xyproto/algernon) - Small self-contained web server with Lua, Markdown, QUIC, Redis and PostgreSQL support - ★ 483



* [flagr](https://github.com/checkr/flagr) - Flagr is a feature flagging, A/B testing and dynamic configuration microservice - ★ 480



* [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover. - ★ 302




## Template Engines



* [gofpdf](https://github.com/jung-kurt/gofpdf) - A PDF document generator with high level support for text, drawing and images - ★ 2580



* [pongo2](https://github.com/flosch/pongo2) - Django-syntax like template-engine for Go - ★ 1336



* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine for Go. Optimized for speed, zero memory allocations in hot paths. Up to 20x faster than html/template - ★ 1142



* [hero](https://github.com/shiyanhui/hero) - A handy, fast and powerful go template engine. - ★ 1069



* [mustache](https://github.com/hoisie/mustache) - The mustache template language in Go - ★ 945



* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language, inspired from HAML and Jade - ★ 798



* [ace](https://github.com/yosssi/ace) - HTML template engine for Go - ★ 730



* [gorazor](https://github.com/sipin/gorazor) - Razor view engine for Golang - ★ 641



* [jet](https://github.com/CloudyKit/jet) - Jet template engine - ★ 515



* [ego](https://github.com/benbjohnson/ego) - An ERB-style templating language for Go. - ★ 391



* [raymond](https://github.com/aymerick/raymond) - Handlebars for golang - ★ 292



* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine for Go - ★ 226



* [soy](https://github.com/robfig/soy) - Go implementation for Soy templates (Google Closure templates) - ★ 132



* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation - ★ 70



* [liquid](https://github.com/osteele/liquid) - A complete Liquid template engine in Go - ★ 68



* [velvet](https://github.com/gobuffalo/velvet) - A sweet velvety templating package - ★ 62



* [damsel](https://github.com/dskinner/damsel) - Package damsel provides html outlining via css-selectors and common template functionality. - ★ 20



* [extemplate](https://github.com/dannyvankooten/extemplate) - Wrapper package for Go&#39;s template/html to allow for easy file-based template inheritance. - ★ 5




## Testing



* [testify](https://github.com/stretchr/testify) - A toolkit with common assertions and mocks that plays nicely with the standard library - ★ 6128



* [goconvey](https://github.com/smartystreets/goconvey/) - Go testing in the browser. Integrates with `go test`. Write behavioral tests in Go. - ★ 3992



* [chromedp](https://github.com/knq/chromedp) - A faster, simpler way to drive browsers supporting the Chrome DevTools Protocol. - ★ 2421



* [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing for Go - ★ 2420



* [mock](https://github.com/golang/mock) - GoMock is a mocking framework for the Go programming language. - ★ 1782



* [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Sql mock driver for golang to test database interactions - ★ 1125



* [httpexpect](https://github.com/gavv/httpexpect) - End-to-end HTTP and REST API testing for Go. - ★ 967



* [selenoid](https://github.com/aerokube/selenoid) - Selenium Hub successor running browsers within containers. Scalable, immutable, self hosted Selenium-Grid on any platform with single binary. - ★ 810



* [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests - ★ 695



* [gock](https://github.com/h2non/gock) - Expressive HTTP traffic mocking and testing made easy in Go ༼ʘ̚ل͜ʘ̚༽ - ★ 621



* [goblin](https://github.com/franela/goblin) - Minimal and Beautiful Go testing framework - ★ 556



* [baloo](https://github.com/h2non/baloo) - Expressive end-to-end HTTP API testing made easy in Go - ★ 553



* [godog](https://github.com/DATA-DOG/godog) - Cucumber for golang - ★ 474



* [gofuzz](https://github.com/google/gofuzz) - Fuzz testing for go. - ★ 454



* [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - A tool for generating self-contained, type-safe test doubles in go - ★ 281



* [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests - ★ 246



* [frisby](https://github.com/verdverm/frisby) - API testing framework inspired by frisby-js - ★ 233



* [testfixtures](https://github.com/go-testfixtures/testfixtures) - Rails-like test fixtures for Go. Write tests against a real database - ★ 219



* [gofight](https://github.com/appleboy/gofight) - Testing API Handler written in Golang. - ★ 201



* [cdp](https://github.com/mafredri/cdp) - Package cdp provides type-safe bindings for the Chrome DevTools Protocol (CDP), written in the Go programming language. - ★ 190



* [tavor](https://github.com/zimmski/tavor) - A generic fuzzing and delta-debugging framework - ★ 189



* [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code - ★ 182



* [go-carpet](https://github.com/msoap/go-carpet) - go-carpet - show test coverage in terminal for Go source files - ★ 181



* [charlatan](https://github.com/percolate/charlatan) - Go Interface Mocking Tool - ★ 177



* [ggr](https://github.com/aerokube/ggr) - A lightweight load balancer used to create big Selenium clusters - ★ 169



* [minimock](https://github.com/gojuno/minimock) - Powerful mock generation tool for Go programming language - ★ 145



* [gospec](https://github.com/orfjackal/gospec) - Testing framework for Go. Allows writing self-documenting tests/specifications, and executes them concurrently and safely isolated. [UNMAINTAINED] - ★ 110



* [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction sql driver for golang - ★ 90



* [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns. - ★ 64



* [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple Go snapshot testing - ★ 57



* [endly](https://github.com/viant/endly) - End to end functional test and automation framework - ★ 53



* [gospecify](https://github.com/stesla/gospecify) - A BDD library for Go - ★ 50



* [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing, inspired by database_cleaner for Ruby - ★ 49



* [restit](https://github.com/yookoala/restit) - A Go library help testing your RESTful API application - ★ 49



* [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP/HTTPS interactions for offline testing - ★ 49



* [wstest](https://github.com/posener/wstest) - go websocket client for unit testing of a websocket handler - ★ 48



* [hamcrest](https://github.com/rdrdr/hamcrest) - Hamcrest matchers for the Go programming language - ★ 24



* [bro](https://github.com/marioidival/bro) - bro watch files in directory and run tests for them - ★ 22



* [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter - ★ 22



* [dsunit](https://github.com/viant/dsunit) - Datastore Testibility - ★ 19



* [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package - ★ 18



* [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions - ★ 10



* [badio](https://github.com/cavaliercoder/badio) - Extensions to Go&#39;s testing/iotest package - ★ 8



* [gocrest](https://github.com/corbym/gocrest) - GoCrest - Hamcrest-like matchers for Go - ★ 7



* [gogiven](https://github.com/corbym/gogiven) - gogiven - BDD testing framework for go that generates readable output directly from source code - ★ 7



* [gosuite](https://github.com/pavlo/gosuite) - Test suites support for standard Go1.7 &quot;testing&quot; by leveraging Subtests feature - ★ 7



* [biff](https://github.com/fulldump/biff) - Bifurcation Framework for testing and use cases - ★ 5



* [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished. - ★ 4



* [tt](https://github.com/vcaesar/tt) - Simple and colorful test tools - ★ 2




## Text Processing



* [goquery](https://github.com/PuerkitoBio/goquery) - A little like that j-thing, only in Go. - ★ 6461



* [colly](https://github.com/asciimoo/colly) - Elegant Scraper and Crawler Framework for Golang - ★ 6214



* [blackfriday](https://github.com/russross/blackfriday) - Blackfriday: a markdown processor for Go - ★ 3352



* [toml](https://github.com/BurntSushi/toml) - TOML parser for Golang with reflection. - ★ 2316



* [go-humanize](https://github.com/dustin/go-humanize) - Go Humans! (formatters for units to human friendly sizes) - ★ 1626



* [sh](https://github.com/mvdan/sh) - A shell parser, formatter and interpreter (POSIX/Bash/mksh) - ★ 1430



* [bluemonday](https://github.com/microcosm-cc/bluemonday) - bluemonday: a fast golang HTML sanitizer (inspired by the OWASP Java HTML Sanitizer) to scrub user generated content of XSS - ★ 1027



* [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector. - ★ 1017



* [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go - ★ 929



* [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go - ★ 506



* [xurls](https://github.com/mvdan/xurls) - Extract urls from text - ★ 377



* [mxj](https://github.com/clbanning/mxj) - Decode / encode XML to/from map[string]interface{} (or JSON); extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. - ★ 293



* [gommon](https://github.com/labstack/gommon/tree/master/bytes) - ★ 252



* [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support. - ★ 240



* [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language in golang - ★ 222



* [gotabulate](https://github.com/bndr/gotabulate) - Gotabulate - Easily pretty-print your tabular data with Go - ★ 186



* [gotext](https://github.com/leonelquinteros/gotext) - Go (Golang) GNU gettext utilities package - ★ 181



* [dataflowkit](https://github.com/slotix/dataflowkit) - Extract structured data from web sites. Web sites scraping. - ★ 158



* [go-runewidth](https://github.com/mattn/go-runewidth) - ★ 157



* [goq](https://github.com/andrewstuart/goq) - A declarative struct-tag-based HTML unmarshaling or scraping package for Go built on top of the goquery library - ★ 117



* [go-nmea](https://github.com/adrianmo/go-nmea) - A NMEA parser library in pure Go - ★ 66



* [radix](https://github.com/yourbasic/radix) - A fast string sorting algorithm - ★ 56



* [genex](https://github.com/alixaxel/genex) - Genex package for Go - ★ 48



* [sdp](https://github.com/gortc/sdp) - RFC 4566 SDP implementation in go - ★ 45



* [align](https://github.com/Guitarbum722/align) - A general purpose application and library for aligning text. - ★ 43



* [guesslanguage](https://github.com/endeveit/guesslanguage) - Guess the natural language of a text in Go - ★ 39



* [htmlquery](https://github.com/antchfx/htmlquery) - htmlquery, an XPath query package for HTML document. - ★ 35



* [goregen](https://github.com/zach-klippenstein/goregen) - randexp for Go. - ★ 32



* [allot](https://github.com/sbstjn/allot) - Parse placeholder and wildcard text commands - ★ 31



* [gonameparts](https://github.com/polera/gonameparts) - Takes a full name and splits it into individual name parts - ★ 27



* [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - EditorConfig Core written in Go - ★ 26



* [slugify](https://github.com/avelino/slugify) - A Go slugify application that handles string - ★ 25



* [go-slugify](https://github.com/mozillazg/go-slugify) - Pretty Slug. - ★ 22



* [parth](https://github.com/codemodus/parth) - Path parsing for segment unmarshaling and slicing. - ★ 22



* [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Encoding and decoding for fixed-width formatted data - ★ 14



* [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml and json to go struct - ★ 14



* [go-vcard](https://github.com/emersion/go-vcard) - A Go library to parse and format vCard - ★ 13



* [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms. - ★ 8



* [bbConvert](https://github.com/CalebQ42/bbConvert) - Converter from BBCode to HTML - ★ 5



* [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for libenca - ★ 5



* [parseargs-go](https://github.com/nproc/parseargs-go) - A string argument parser that understands quotes and backslashes - ★ 4



* [encoding](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decoders - ★ 3



* [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed parser for Atom 1.0 and RSS 2.0. - ★ 3



* [doi](https://github.com/hscells/doi) - Parse and check doi objects in go. - ★ 2




## Third-party APIs



* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - AWS SDK for the Go programming language. - ★ 4292



* [go-github](https://github.com/google/go-github) - Go library for accessing the GitHub API - ★ 4063



* [slack](https://github.com/nlopes/slack) - Slack API in Go - ★ 1898



* [google-api-go-client](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go. - ★ 1580



* [google-cloud-go](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud Client Libraries for Go. - ★ 1420



* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Golang bindings for the Telegram Bot API - ★ 1249



* [anaconda](https://github.com/ChimeraCoder/anaconda) - A Go client library for the Twitter 1.1 API - ★ 924



* [stripe-go](https://github.com/stripe/stripe-go) - Go library for the Stripe API. - ★ 805



* [telebot](https://github.com/tucnak/telebot) - Telebot is a Telegram bot framework in Go. - ★ 743



* [discordgo](https://github.com/bwmarrin/discordgo) - (Golang) Go bindings for Discord - ★ 723



* [facebook](https://github.com/huandu/facebook) - A Facebook Graph API SDK For Go. - ★ 690



* [goamz](https://github.com/mitchellh/goamz) - Golang Amazon Library - ★ 677



* [minio-go](https://github.com/minio/minio-go) - Minio Client SDK for Go - ★ 554



* [go-twitter](https://github.com/dghubble/go-twitter) - Go Twitter REST and Streaming API v1.1 - ★ 543



* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for Atlassian JIRA - ★ 345



* [githubv4](https://github.com/shurcooL/githubql) - Package githubv4 is a client library for accessing GitHub GraphQL API v4 ( ). - ★ 340



* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go library to access geocoding and reverse geocoding APIs - ★ 260



* [PayPal-Go-SDK](https://github.com/logpacker/PayPal-Go-SDK) - Golang client for PayPal REST API - ★ 259



* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub, Bitbucket and GitLab - ★ 240



* [go-marathon](https://github.com/gambol99/go-marathon) - A GO API library for working with Marathon - ★ 177



* [tbot](https://github.com/yanzay/tbot) - Telegram Bot Server - ★ 168



* [ethrpc](https://github.com/onrik/ethrpc) - Golang client for ethereum json rpc api - ★ 142



* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. - ★ 114



* [hipchat](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP - ★ 112



* [hipchat](https://github.com/andybons/hipchat) - This project implements a Go client library for the Hipchat API. - ★ 108



* [medium-sdk-go](https://github.com/Medium/medium-sdk-go) - A Golang SDK for Medium&#39;s OAuth2 API - ★ 105



* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing trending repositories and developers at Github. - ★ 95



* [go-tgbot](https://github.com/olebedev/go-tgbot) - Golang telegram bot API wrapper, session-based router and middleware - ★ 76



* [trello](https://github.com/adlio/trello) - Trello API wrapper for Go - ★ 72



* [clarifai-go](https://github.com/samuelcouch/clarifai) - Clarifai library for Go - ★ 58



* [cachet](https://github.com/andygrunwald/cachet) - Go(lang) client library for Cachet (open source status page system). - ★ 57



* [megos](https://github.com/andygrunwald/megos) - Go(lang) client library for accessing information of an Apache Mesos cluster. - ★ 54



* [telegraph](https://github.com/toby3d/go-telegraph) - Official unofficial Golang bindings for Telegraph API - ★ 48



* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API - ★ 47



* [gads](https://github.com/emiddleton/gads) - Google Adwords API for Go - ★ 36



* [go-xkcd](https://github.com/nishanths/go-xkcd) - xkcd.com API client - ★ 36



* [go-amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for Amazon Product Advertising API - ★ 32



* [go-circleci](https://github.com/jszwedko/go-circleci) - Go library for interacting with CircleCI - ★ 32



* [gomusicbrainz](https://github.com/michiwend/gomusicbrainz) - a Go (Golang) MusicBrainz WS2 client library - work in progress - ★ 31



* [gcm](https://github.com/Aorioli/gcm) - Google Cloud Messaging for application servers implemented using the Go programming language. - ★ 29



* [golyrics](https://github.com/mamal72/golyrics) - A simple Go package to fetch lyrics from Wikia - ★ 28



* [fcm](https://github.com/maddevsio/fcm) - Firebase Cloud Messaging for application servers implemented using the Go programming language. - ★ 27



* [gami](https://github.com/bit4bit/gami) - GO - Asterisk AMI Interface - ★ 26



* [mixpanel](https://github.com/dukex/mixpanel) - Golang Mixpanel Client - ★ 25



* [translate](https://github.com/poorny/translate) - Go online translation package - ★ 25



* [uptimerobot](https://github.com/bitfield/uptimerobot) - Client library for UptimeRobot v2 API - ★ 24



* [go-shopify](https://github.com/rapito/go-shopify) - Simple Shopify API for the Go Programming Language - ★ 19



* [govkbot](https://github.com/nikepan/govkbot) - VK bot package for Go - ★ 18



* [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the Internet Game Database API - ★ 18



* [go-spotify](https://github.com/rapito/go-spotify) - Go library for the Spotify Web API - ★ 16



* [codeship-go](https://github.com/codeship/codeship-go) - Go library for accessing the Codeship API v2 - ★ 15



* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for API - ★ 14



* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go library for accessing the MyAnimeList API: - ★ 14



* [go-twitch](https://github.com/knspriggs/go-twitch) - A golang client for the Twitch v3 API - public APIs only (for now) - ★ 14



* [patreon-go](https://github.com/mxpv/patreon-go) - Patreon Go API client - ★ 14



* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Golang Client for the Unsplash API - ★ 13



* [go-google-analytics](https://github.com/chonthu/go-google-analytics) - Simple Reporting for Google Analytics - ★ 12



* [textbelt](https://github.com/dietsche/textbelt) - golang library for textbelt.com - ★ 12



* [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API - ★ 12



* [go-steam](https://github.com/sostronk/go-steam) - Go library for querying Source servers - ★ 11



* [go-tmdb](https://github.com/jbrodriguez/go-tmdb) - ★ 11



* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go library to use the imgur.com API - ★ 9



* [smitego](https://github.com/sergiotapia/smitego) - SmiteGo is an API wrapper for the Smite game from HiRez. It is written in Go! - ★ 9



* [micha](https://github.com/onrik/micha) - Client lib for Telegram bot api - ★ 8



* [rrdaclient](https://github.com/Omie/rrdaclient) - Go bindings for RRDA - ★ 8



* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny utility Go client for HackerNews API. - ★ 7



* [gumblr](https://github.com/mattcunningham/gumblr) - A Go Wrapper for the Tumblr v2 API - ★ 6



* [ynab.go](https://github.com/brunomvsouza/ynab.go) - Go client for the YNAB API. It covers 100% of the resources made available by the YNAB API. (UNOFFICIAL) - ★ 6



* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API. - ★ 5



* [go-google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go Client Library for G Suite Email Audit API - ★ 5



* [go-zooz](https://github.com/gojuno/go-zooz) - Zooz API client for Go - ★ 4



* [coinpaprika-api-go-client](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika&#39;s API - ★ 3



* [go-chronos](https://github.com/axelspringer/go-chronos) - Go Chronos 3.x REST API Client - ★ 2



* [go-sophos](https://github.com/esurdam/go-sophos) - Sophos UTM 9 REST API Client in Golang - ★ 2



* [playlyfe-go-sdk](https://github.com/playlyfe/playlyfe-go-sdk) - This is the official Playlyfe Golang Sdk - ★ 1








## Utilities



* [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder - ★ 17880



* [hub](https://github.com/github/hub) - hub helps you win at git. - ★ 13989



* [delve](https://github.com/derekparker/delve) - Delve is a debugger for the Go programming language. - ★ 9714



* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection - ★ 7729



* [ctop](https://github.com/bcicen/ctop) - Top-like interface for container metrics - ★ 7582



* [sqlx](https://github.com/jmoiron/sqlx) - general purpose extensions to golang&#39;s database/sql - ★ 5229



* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool - ★ 4940



* [usql](https://github.com/knq/usql) - universal command-line interface for SQL databases - ★ 4395



* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications. - ★ 3610



* [gjson](https://github.com/tidwall/gjson) - Get JSON values quickly - JSON Parser for Go - ★ 3575



* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible - ★ 3458



* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs - ★ 3351



* [xlsx](https://github.com/tealeg/xlsx) - Google Go (golang) library for reading and writing XLSX files. You should probably also checkout: - ★ 2789



* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files. - ★ 2668



* [realize](https://github.com/tockins/realize) - Realize is the #1 Golang Task Runner which enhance your workflow by automating the most common tasks and using the best performing Golang live reloading. - ★ 2573



* [goreporter](https://github.com/wgliang/goreporter) - A Golang tool that does static analysis, unit testing, code review and generate code quality report. - ★ 2233



* [gorequest](https://github.com/parnurzeal/gorequest) - GoRequest -- Simplified HTTP client ( inspired by nodejs SuperAgent ) - ★ 1963



* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON - ★ 1837



* [panicparse](https://github.com/maruel/panicparse) - Crash your app in style (Golang) - ★ 1799



* [minify](https://github.com/tdewolff/minify) - Go minifiers for web formats - ★ 1594



* [mmake](https://github.com/tj/mmake) - Modern Make - ★ 1431



* [hystrix-go](https://github.com/afex/hystrix-go) - Netflix&#39;s Hystrix latency and fault tolerance library, for Go - ★ 1422



* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client library for Go - ★ 1356



* [grequests](https://github.com/levigross/grequests) - A Go &quot;clone&quot; of the great and famous Requests library - ★ 1173



* [storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB - ★ 1148



* [task](https://github.com/go-task/task) - A task runner / simpler Make alternative written in Go - ★ 1040



* [go-underscore](https://github.com/tobyhede/go-underscore) - Helpfully Functional Go - A useful collection of Go utilities. Designed for programmer happiness. - ★ 979



* [mc](https://github.com/minio/mc) - Minio Client is a replacement for ls, cp, mkdir, diff and rsync commands for filesystems and object storage. - ★ 859



* [profile](https://github.com/pkg/profile) - Simple profiling for Go - ★ 827



* [boilr](https://github.com/tmrts/boilr) - boilerplate template manager that generates files or directories from template repositories - ★ 793



* [sling](https://github.com/dghubble/sling) - A Go HTTP client library for creating and sending API requests - ★ 751



* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go - ★ 693



* [goreq](https://github.com/franela/goreq) - Minimal and simple request library for Go language - ★ 690



* [gtm](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git - ★ 616



* [mergo](https://github.com/imdario/mergo) - Mergo: merging Go structs and maps since 2013. - ★ 616



* [spinner](https://github.com/briandowns/spinner) - Go (golang) package for providing a terminal spinner/progress indicator with options. - ★ 609



* [go-funk](https://github.com/thoas/go-funk) - A modern Go utility library which provides helpers (map, find, contains, filter, ...) - ★ 589



* [gentleman](https://github.com/h2non/gentleman) - Full-featured, plugin-oriented, extensible HTTP client toolkit for Go - ★ 567



* [immortal](https://github.com/immortal/immortal) - ⭕ A *nix cross-platform (OS agnostic) supervisor - ★ 542



* [gron](https://github.com/roylee0704/gron) - gron, Cron Jobs in Go. - ★ 530



* [jobrunner](https://github.com/bamzi/jobrunner) - Framework for performing work asynchronously, outside of the request flow - ★ 488



* [httpcontrol](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries. - ★ 475



* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility - ★ 461



* [gopencils](https://github.com/bndr/gopencils) - Easily consume REST APIs with Go (golang) - ★ 414



* [go-dry](https://github.com/ungerik/go-dry) - DRY (don&#39;t repeat yourself) package for Go - ★ 413



* [filetype](https://github.com/h2non/filetype) - Small and blazing fast package to infer file types checking the magic numbers signature in pure Go - ★ 380



* [godaemon](https://github.com/VividCortex/godaemon) - Daemonize Go applications deviously. - ★ 375



* [request](https://github.com/mozillazg/request) - A developer-friendly HTTP request library for Gopher. - ★ 327



* [pester](https://github.com/sethgrid/pester) - Go (golang) http calls with retries and backoff - ★ 281



* [go-rate](https://github.com/beefsack/go-rate) - A timed rate limiter for Go - ★ 271



* [scheduler](https://github.com/carlescere/scheduler) - Job scheduling made easy. - ★ 249



* [gohper](https://github.com/cosiner/gohper) - common libs here. - ★ 246



* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running on different ports made easy - ★ 235



* [deepcopier](https://github.com/ulule/deepcopier) - simple struct copying for golang - ★ 174



* [go-cron](https://github.com/rk/go-cron) - A simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. - ★ 168



* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go-bind-plugin generates API for exported plugin symbols (-buildmode=plugin) - go1.8+ only ( ) - ★ 158



* [go-trigger](https://github.com/sadlil/go-trigger) - A Global event triggerer for golang. Defines functions as event with id string. Trigger the event anywhere from your project. - ★ 157



* [rerun](https://github.com/ivpusic/rerun) - Configurable recompiling and rerunning go apps when source changes - ★ 150



* [moldova](https://github.com/StabbyCutyou/moldova) - A lightweight templating system for generating random data - ★ 147



* [robustly](https://github.com/VividCortex/robustly) - Run functions resiliently in Go, catching and restarting panics - ★ 129



* [gojq](https://github.com/elgs/gojq) - JSON query in Golang - ★ 128



* [apm](https://github.com/topfreegames/apm) - APM is a process manager for Golang applications. - ★ 117



* [gotenv](https://github.com/subosito/gotenv) - Load environment variables dynamically in Go. - ★ 111



* [death](https://github.com/vrecan/death) - Managing go application shutdown with signals. - ★ 103



* [kazaam](https://github.com/Qntfy/kazaam) - Arbitrary transformations of JSON in Golang - ★ 96



* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go [golang] - ★ 96



* [chyle](https://github.com/antham/chyle) - Changelog generator : use a git repository and various data sources and publish the result on external services - ★ 95



* [util](https://github.com/shomali11/util) - A collection of useful utility functions - ★ 89



* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - go-sitemap-generator is the easiest way to generate Sitemaps in Go - ★ 86



* [goreq](https://github.com/smallnest/goreq) - A Simplified Golang Http Client - ★ 83



* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects. - ★ 83



* [onecache](https://github.com/adelowo/onecache) - One caching API, Multiple backends - ★ 79



* [unis](https://github.com/esemplastic/unis) - UNIS: A Common Architecture for String Utilities within the Go Programming Language. - ★ 67



* [netbug](https://github.com/e-dard/netbug) - Package netbug provides a handler for registering profilers on your own ServeMux. - ★ 65



* [retry](https://github.com/kamilsk/retry) - Functional mechanism based on channels to perform actions repetitively until successful. - ★ 65



* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang. (Also added to ) - ★ 63



* [pm](https://github.com/VividCortex/pm) - Processlist manager with TCP listener - ★ 61



* [go-health](https://github.com/Talento90/go-health) - Health check your applications and dependencies - ★ 57



* [multitick](https://github.com/VividCortex/multitick) - A multiplexor for aligned time.Time tickers in Go - ★ 57



* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang - ★ 56



* [jsonf](https://github.com/miolini/jsonf) - Console JSON formatter with query feature - ★ 53



* [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating. - ★ 51



* [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. - ★ 50



* [abutil](https://github.com/bahlo/abutil) - [UNMAINTAINED] A collection of often-used Golang helpers - ★ 48



* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight, performant and auto balancing in mind. - ★ 47



* [mimetype](https://github.com/gabriel-vasile/mimetype) - A golang library for detecting mime types and extensions based on magic numbers - ★ 42



* [minquery](https://github.com/icza/minquery) - MongoDB / mgo query that supports efficient pagination (cursors to continue listing documents where we left off). - ★ 42



* [golog](https://github.com/mlimaloureiro/golog) - Easy and simple CLI time tracker for your tasks - ★ 41



* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code - ★ 40



* [toolbox](https://github.com/viant/toolbox) - Toolbox - go utility library - ★ 40



* [goback](https://github.com/carlescere/goback) - Golang simple exponential backoff package. - ★ 38



* [clockwork](https://github.com/whiteShtef/clockwork) - A simple and intuitive scheduling library in Go. - ★ 34



* [intrinsic](https://github.com/mengzhuo/intrinsic) - Provide Golang native SIMD intrinsics on x86/amd64 platform - ★ 34



* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events - ★ 32



* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal copy paste service, works across different machines! - ★ 30



* [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes - ★ 29



* [go-excel](https://github.com/szyhf/go-excel) - A simple and light excel file reader to read a standard excel as a table faster | 一个轻量级的Excel数据读取库，用一种更`关系数据库`的方式解析Excel。 - ★ 29



* [mimemagic](https://github.com/zRedShift/mimemagic) - Powerful and versatile MIME sniffing package using pre-compiled glob patterns, magic number signatures, XML document namespaces, and tree magic for mounted volumes, generated from the XDG shared-mime-info database. - ★ 29



* [mp](https://github.com/sanbornm/mp) - Simple Email Parser - ★ 29



* [myhttp](https://github.com/inancgumus/myhttp) - Simplest HTTP GET requester for Go with timeout support - ★ 27



* [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go - ★ 27



* [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Excel xlsx files - ★ 26



* [gpath](https://github.com/tenntenn/gpath) - gpath is a Go package to access a field by a path using reflect pacakge - ★ 25



* [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang - ★ 24



* [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client - ★ 23



* [rclient](https://github.com/zpatrick/rclient) - Minimalistic REST client for Go applications - ★ 21



* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images - ★ 20



* [ugo](https://github.com/alxrm/ugo) - Simple and expressive toolbox written in Go - ★ 19



* [dlog](https://github.com/kirillDanshin/dlog) - Simple build-time controlled debug log with ability to log where the logger was called - ★ 15



* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - A complete Golang client for SeaweedFS - ★ 15



* [filler](https://github.com/yaronsumel/filler) - fill struct data easily with fill tags - ★ 14



* [go-httpheader](https://github.com/mozillazg/go-httpheader) - A Go library for encoding structs into Header fields. - ★ 14



* [go-respond](https://github.com/nicklaw5/go-respond) - A Go package for handling common HTTP JSON responses. - ★ 13



* [okrun](https://github.com/xta/okrun) - ok, run your gofile - ★ 13



* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex - ★ 12



* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX files - ★ 12



* [rerate](https://github.com/abo/rerate) - redis-based rate counter and rate limiter - ★ 11



* [evaluator](https://github.com/nullne/evaluator) - ★ 10



* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over FastLz for GoLang - ★ 10



* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher - ★ 9



* [jsonhal](https://github.com/RichardKnop/jsonhal) - A simple Go package to make custom structs marshal into HAL compatible JSON responses. - ★ 8



* [structs](https://github.com/PumpkinSeed/structs) - Golang struct operations. - ★ 8



* [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done - ★ 7



* [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. - ★ 6



* [filter](https://github.com/gookit/filter) - Provide filtering, sanitizing, and conversion of Golang data. 提供对Golang数据的过滤，净化，转换。 - ★ 4



* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference - ★ 4



* [retry](https://github.com/percolate/retry) - Percolate&#39;s Go retry package - ★ 2



* [ctxutil](https://github.com/posener/ctxutil) - utils for Go context - ★ 0




## Validation



* [govalidator](https://github.com/asaskevich/govalidator) - [Go] Package of validators and sanitizers for strings, numerics, slices and structs - ★ 2949



* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving - ★ 2350



* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - An idiomatic Go (golang) validation package. Supports configurable and extensible validation rules (validators) using normal language constructs instead of error-prone struct tags. - ★ 806



* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel&#39;s request validation. - ★ 504



* [validate](https://github.com/markbates/validate) - This package provides a framework for writing validations for Go applications. - ★ 39



* [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support Map, Struct, Form data. Go通用的数据验证与过滤库，使用简单，内置大部分常用验证、过滤器，支持自定义验证器、自定义消息、字段翻译。 - ★ 14




## Version Control



* [git2go](https://github.com/libgit2/git2go) - Git to Go; bindings for libgit2. Like McDonald&#39;s but tastier. - ★ 1225



* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go - ★ 65



* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks. - ★ 62



* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories. - ★ 12




## Video



* [goav](https://github.com/giorgisio/goav) - Golang bindings for FFmpeg - ★ 541



* [gmf](https://github.com/3d0c/gmf) - Go Media Framework - ★ 414



* [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO - ★ 218



* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer (retired: currently I don&#39;t use/develop this package) - ★ 146



* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .ssa/.ass, .stl, .ttml, .vtt (webvtt), teletext, etc.) - ★ 130



* [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X used by the VLC media player - ★ 32



* [v4l](https://github.com/korandiz/v4l) - Facade to the Video4Linux video capture interface. - ★ 19



* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - golang library to read and write various subtitle formats - ★ 9




## Web Frameworks



* [gin](https://github.com/gin-gonic/gin) - Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance -- up to 40 times faster. If you need smashing performance, get yourself some Gin. - ★ 21908



* [beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language. - ★ 17708



* [echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework - ★ 12106



* [revel](https://github.com/revel/revel) - A high productivity, full-stack web framework for the Go language. - ★ 10443



* [httprouter](https://github.com/julienschmidt/httprouter) - A high performance HTTP request router that scales well - ★ 8062



* [mux](https://github.com/gorilla/mux) - A powerful URL router and dispatcher for golang. - ★ 7476



* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP Middleware for Golang - ★ 5887



* [chi](https://github.com/go-chi/chi) - lightweight, idiomatic and composable router for building Go HTTP services - ★ 4456



* [go-json-rest](https://github.com/ant0ine/go-json-rest) - A quick and easy way to setup a RESTful JSON API - ★ 3200



* [goa](https://github.com/raphael/goa) - Design-based APIs and microservices in Go - ★ 3121



* [macaron](https://github.com/go-macaron/macaron) - Package macaron is a high productive and modular web framework in Go. - ★ 2575



* [gizmo](https://github.com/NYTimes/gizmo) - A Microservice Toolkit from The New York Times - ★ 2438



* [utron](https://github.com/gernest/utron) - A lightweight MVC framework for Go(Golang) - ★ 2088



* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go - ★ 1671



* [web](https://github.com/gocraft/web) - Go Router + Middleware. Your Contexts. - ★ 1347



* [bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer - ★ 1170



* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, binary data, and HTML templates responses. - ★ 1164



* [pat](https://github.com/bmizerany/pat) - ★ 1149



* [tollbooth](https://github.com/didip/tollbooth) - Simple middleware to rate-limit HTTP requests. - ★ 993



* [go-tigertonic](https://github.com/rcrowley/go-tigertonic) - A Go framework for building JSON web services inspired by Dropwizard - ★ 989



* [cors](https://github.com/rs/cors) - Go net/http configurable handler to handle CORS requests - ★ 925



* [tango](https://github.com/lunny/tango) - Micro &amp; pluggable web framework for Go - ★ 741



* [go-server-timing](https://github.com/mitchellh/go-server-timing) - Go (golang) library for creating and consuming HTTP Server-Timing headers - ★ 717



* [goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer for Go (golang) - ★ 678



* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - A high performance fasthttp request router that scales well - ★ 588



* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go [NOT MAINTAINED] - ★ 514



* [stats](https://github.com/thoas/stats) - A Go middleware that stores various information about your web application (response time, status code count, etc.) - ★ 504



* [limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go. - ★ 415



* [gongular](https://github.com/mustafaakin/gongular) - A different approach to Go web frameworks - ★ 401



* [neo](https://github.com/ivpusic/neo) - Go Web Framework - ★ 378



* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. - ★ 360



* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. - ★ 358



* [siesta](https://github.com/VividCortex/siesta) - Composable framework for writing HTTP handlers in Go. - ★ 348



* [gorouter](https://github.com/xujiajun/gorouter) - xujiajun/gorouter is a simple and fast HTTP router for Go. It is easy to build RESTful APIs and your web framework. - ★ 332



* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. - ★ 330



* [gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster - ★ 312



* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. - ★ 307



* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang - ★ 287



* [vestigo](https://github.com/husobee/vestigo) - Echo Inspired Stand Alone URL Router - ★ 234



* [golf](https://github.com/dinever/golf) - The Golf web framework - ★ 229



* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight Middleware for net/http - ★ 203



* [gem](https://github.com/go-gem/gem) - no long maintain anymore - ★ 153



* [go-relax](https://github.com/codehack/go-relax) - Framework for building RESTful API&#39;s in Go - ★ 153



* [router](https://github.com/gowww/router) - A lightning fast HTTP router - ★ 149



* [zerver](https://github.com/cosiner/zerver) - a RESTful API framework - ★ 144



* [zeus](https://github.com/daryl/zeus) - Go HTTP router. - ★ 111



* [go-rest](https://github.com/ungerik/go-rest) - A small and evil REST framework for Go - ★ 110



* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go - ★ 110



* [alien](https://github.com/gernest/alien) - A lightweight and fast http router from outer space - ★ 95



* [violetear](https://github.com/nbari/violetear) - Go HTTP router - ★ 91



* [air](https://github.com/aofei/air) - An ideally refined web framework for Go. - ★ 90



* [Bxog](https://github.com/claygod/Bxog) - Bxog is a simple and fast HTTP router for Go (HTTP request multiplexer). - ★ 90



* [rye](https://github.com/InVisionApp/rye) - A tiny http middleware for Golang with added handlers for common needs. - ★ 88



* [xmux](https://github.com/rs/xmux) - xmux is a httprouter fork on top of xhandler (net/context aware) - ★ 85



* [core](https://github.com/volatile/core) - Pure handlers stack - ★ 81



* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses - ★ 77



* [aero](https://github.com/aerogo/aero) - Fast and secure web server for Go. - ★ 71



* [xff](https://github.com/sebest/xff) - A Golang Middleware to handle X-Forwarded-For Header - ★ 68



* [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing your API on a per-request basis with Bitcoin and Lightning - ★ 66



* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std &quot;net/http&quot; implementation - ★ 66



* [golax](https://github.com/fulldump/golax) - Golax, a go implementation for the Lax framework. - ★ 64



* [chain](https://github.com/codemodus/chain) - Composable chains of nested http.Handler instances. - ★ 63



* [webgo](https://github.com/bnkamalesh/webgo) - A mini-toolkit/micro-framework to build web apps; with handler chaining, middleware and context injection, with standard library compliant HTTP handlers(i.e. http.HandlerFunc). - ★ 55



* [wrap](https://github.com/go-on/wrap) - Go http.Hander based middleware stack with context sharing - ★ 54



* [florest-core](https://github.com/jabong/florest-core) - A high performance workflow based REST API framework - ★ 50



* [microservice](https://github.com/claygod/microservice) - This library provides a simple framework of microservice, which includes a configurator, a logger, metrics, and of course the handler - ★ 45



* [yarf](https://github.com/yarf-framework/yarf) - Yet Another REST Framework - ★ 45



* [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web and cli application framework with dependency injection support - ★ 44



* [fireball](https://github.com/zpatrick/fireball) - Go web framework with a natural feel - ★ 41



* [gorouter](https://github.com/vardius/gorouter) - Go Server/API micro framwework, HTTP request router, multiplexer, mux - ★ 36



* [formjson](https://github.com/rs/formjson) - Go net/http handler to transparently manage posted JSON - ★ 30



* [api](https://github.com/resoursea/api) - A REST framework for quickly writing resource based services in Golang. - ★ 29



* [rex](https://github.com/goanywhere/rex) - Pleasures for Web in Golang - ★ 24



* [medeina](https://github.com/imdario/medeina) - Go HTTP routing tree based on HttpRouter. Inspired by Roda and Cuba. - ★ 18



* [fastrouter](https://github.com/razonyang/fastrouter) - FastRouter is a fast, flexible HTTP router written in Go. - ★ 17



* [vox](https://github.com/aisk/vox) - Go web framework inspired by koa - ★ 11



* [client-timing](https://github.com/posener/client-timing) - An HTTP client for go-server-timing middleware. - ★ 10



* [catena](https://github.com/codemodus/catena) - gRPC interceptor catenation. - ★ 7



* [banjo](https://github.com/nsheremet/banjo) - BANjO is a simple web framework written in Go (golang) - ★ 3



* [sawsij](https://github.com/jaybill/sawsij) - ★ 2




## Windows



* [go-ole](https://github.com/go-ole/go-ole) - win32 ole implementation for golang - ★ 451



* [d3d9](https://github.com/gonutz/d3d9) - Direct3D9 wrapper for Go. - ★ 74




## XML



* [xquery](https://github.com/antchfx/xquery) - xquery, extract data or evaluate value from HTML/XML documents using XPath expression in Go - ★ 136



* [xpath](https://github.com/antchfx/xpath) - XPath package for Golang - ★ 94



* [XML-Comp](https://github.com/xml-comp/xml-comp) - Compare ANY markup documents. - ★ 15



* [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang - ★ 7



* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - xmlwriter is a Go library providing procedural XML generation based on libxml2&#39;s xmlwriter module - ★ 5




## Code Analysis



* [gometalinter](https://github.com/alecthomas/gometalinter) - Concurrently run Go lint tools and normalise their output - ★ 3156



* [lint](https://github.com/golang/lint) - [mirror] This is a linter for Go source code. - ★ 2737



* [go-tools](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - ★ 1908



* [go-tools](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - ★ 1908



* [go-tools](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - ★ 1908



* [errcheck](https://github.com/kisielk/errcheck) - errcheck checks that you checked errors. - ★ 1137



* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time - ★ 848



* [interfacer](https://github.com/mvdan/interfacer) - A linter that suggests interface types - ★ 717



* [php-parser](https://github.com/z7zmey/php-parser) - PHP parser written in Go - ★ 528



* [go-critic](https://github.com/go-critic/go-critic) - The most opinionated Go source code linter for code audit. - ★ 400



* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Golang AST visualizer - ★ 306



* [gostatus](https://github.com/shurcooL/gostatus) - A command line tool that shows the status of Go repositories. - ★ 226



* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source - ★ 226



* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - Clean architecture validator for go, like a The Dependency Rule and interaction between packages in your Go projects. - ★ 223



* [apicompat](https://github.com/bradleyfalzon/apicompat) - apicompat checks recent changes to a Go project for backwards incompatible changes - ★ 153



* [dupl](https://github.com/mibk/dupl) - a tool for code clone detection - ★ 127



* [checkstyle](https://github.com/qiniu/checkstyle) - checkstyle for go - ★ 85



* [validate](https://github.com/mccoyst/validate) - A Go package to automatically validate fields with tags - ★ 62



* [lint](https://github.com/surullabs/lint) - Run linters from Go code - - ★ 61



* [go-outdated](https://github.com/firstrow/go-outdated) - Find outdated golang packages - ★ 46



* [blanket](https://github.com/verygoodsoftwarenotvirus/tarp) - MOVED TO GITLAB - ★ 11




## Editor Plugins



* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim - ★ 9385



* [gocode](https://github.com/nsf/gocode) - An autocompletion daemon for the Go programming language - ★ 4496



* [vscode-go](https://github.com/Microsoft/vscode-go) - An extension for VS Code which provides support for the Go language. - ★ 4168



* [GoSublime](https://github.com/DisposaBoy/GoSublime) - A Golang plugin collection for SublimeText 3, providing code completion and other IDE-like features. - ★ 3051



* [go-plus](https://github.com/joefitzgerald/go-plus) - An Enhanced Go Experience For The Atom Editor - ★ 1420



* [go-mode.el](https://github.com/dominikh/go-mode.el) - Emacs mode for the Go programming language - ★ 837



* [goclipse](https://github.com/GoClipse/goclipse) - Eclipse IDE for the Go programming language: - ★ 776



* [Watch](https://github.com/eaburns/Watch) - Watches for changes in a directory tree and reruns a command in an acme win or just on the terminal. - ★ 153



* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim compiler plugin for Go (golang) - ★ 77



* [go-language-server](https://github.com/theia-ide/go-language-server) - A Go language server. - ★ 17



* [velour](https://github.com/velour/velour) - An IRC client for acme — the project that started it all. - ★ 16



* [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for - ★ 14



* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Theia Go Extension - ★ 8




## Go Generate Tools



* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code. - ★ 1487



* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go - ★ 745



* [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code. This repository has migrated to - ★ 160



* [gocontracts](https://github.com/Parquery/gocontracts) - A tool for design-by-contract in Go - ★ 27



* [generic](https://github.com/usk81/generic) - flexible data type for Go - ★ 22



* [gounit](https://github.com/hexdigest/gounit) - Unit tests generator for Go programming language - ★ 14




## Go Tools



* [OctoLinker](https://github.com/OctoLinker/browser-extension) - OctoLinker – Available on Chrome, Firefox and Opera - ★ 3035



* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go - ★ 2884



* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of a Go program using dot format. - ★ 1333



* [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations. - ★ 305



* [depth](https://github.com/KyleBanks/depth) - Visualize Go Dependency Trees - ★ 268



* [rts](https://github.com/galeone/rts) - RTS: request to struct. Generates Go structs from JSON server responses. - ★ 177



* [colorgo](https://github.com/songgao/colorgo) - Colorize (highlight) `go build` command output - ★ 94



* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - bash completion for go and wgo - ★ 37



* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - A teeny tiny and somewhat opinionated generator for your next golang project - ★ 6




## Software Packages



* [moby](https://github.com/moby/moby) - Moby Project - a collaborative project for the container ecosystem to assemble container-based systems - ★ 51034



* [kubernetes](https://github.com/kubernetes/kubernetes) - Production-Grade Container Scheduling and Management - ★ 43756



* [traefik](https://github.com/containous/traefik) - The Cloud Native Edge Router - ★ 18594



* [gitea](https://github.com/go-gitea/gitea) - Git with a cup of tea, painless self-hosted git service - ★ 10772



* [goreplay](https://github.com/buger/gor) - GoReplay is an open-source tool for capturing and replaying live HTTP traffic into a test environment in order to continuously test your system with real data. It can be used to increase confidence in code deployments, configuration changes and infrastructure changes. - ★ 9585



* [vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It&#39;s over 9000! - ★ 9543



* [rkt](https://github.com/coreos/rkt) - rkt is a pod-native container engine for Linux. It is composable, secure, and built on standards. - ★ 8290



* [packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. - ★ 8164



* [seaweedfs](https://github.com/chrislusf/seaweedfs) - SeaweedFS is a simple and highly scalable distributed file system. There are two objectives: to store billions of files! to serve the files fast! SeaweedFS implements an object store with O(1) disk seek, and an optional Filer with POSIX interface. - ★ 6807



* [comcast](https://github.com/tylertreat/Comcast) - Simulating shitty network connections so you can build better systems. - ★ 5838



* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul - ★ 5600



* [restic](https://github.com/restic/restic) - Fast, secure, efficient backup program - ★ 5477



* [liteide](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE. - ★ 4873



* [hey](https://github.com/rakyll/hey) - HTTP load generator, ApacheBench (ab) replacement, formerly known as rakyll/boom - ★ 4281



* [gvm](https://github.com/moovweb/gvm) - Go Version Manager - ★ 3905



* [nes](https://github.com/fogleman/nes) - NES emulator written in Go. - ★ 3821



* [webhook](https://github.com/adnanh/webhook) - webhook is a lightweight configurable incoming webhook server which can execute shell commands - ★ 3315



* [toxiproxy](https://github.com/shopify/toxiproxy) - A TCP proxy to simulate network and system conditions for chaos and resiliency testing - ★ 3197



* [gox](https://github.com/mitchellh/gox) - A dead simple, no frills Go cross compile tool - ★ 2961



* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework - ★ 2672



* [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language. - ★ 2466



* [duplicacy](https://github.com/gilbertchen/duplicacy) - A new generation cloud backup tool - ★ 2383



* [go-metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale&#39;s Metrics library - ★ 2123



* [mylg](https://github.com/mehrdadrad/mylg) - Network Diagnostic Tool - ★ 2091



* [sup](https://github.com/pressly/sup) - Super simple deployment tool - think of it like &#39;make&#39; for a network of servers - ★ 1817



* [snap](https://github.com/intelsdi-x/snap) - The open telemetry framework - ★ 1782



* [circuit](https://github.com/gocircuit/circuit) - Circuit: Dynamic cloud orchestration - ★ 1693



* [aptly](https://github.com/smira/aptly) - aptly - Debian repository management tool - ★ 1634



* [pipe](https://github.com/b3log/pipe) - 一款小而美的 Go 博客平台。 - ★ 1583



* [goxc](https://github.com/laher/goxc) - a build tool for Go, with a focus on cross-compiling, packaging and deployment - ★ 1576



* [fac](https://github.com/mkchoi212/fac) - Easy-to-use CUI for fixing git conflicts - ★ 1508



* [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter - ★ 1486



* [borg](https://github.com/crufter/borg) - Search and save shell snippets without leaving your terminal - ★ 1380



* [kala](https://github.com/ajvb/kala) - Modern Job Scheduler - ★ 1274



* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool written in Go - ★ 1178



* [statusok](https://github.com/sanathp/statusok) - Monitor your Website and APIs from your Computer. Get Notified through Slack, E-mail when your server is down or response time is more than expected. - ★ 1004



* [banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics. - ★ 996



* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Fast, concurrent, streaming access to Amazon S3, including gof3r, a CLI. - ★ 951



* [Go-Package-Store](https://github.com/shurcooL/Go-Package-Store) - An app that displays updates for the Go packages in your GOPATH. - ★ 863



* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Golang applications to self update - ★ 622



* [leaps](https://github.com/jeffail/leaps) - A pair programming service using operational transforms - ★ 615



* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. - ★ 527



* [community](https://github.com/documize/community) - Intelligent Document Environment (IDE) to author, track, deliver documentation - ★ 517



* [scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker) - ★ 467



* [vflow](https://github.com/VerizonDigital/vflow) - Enterprise Network Flow Collector (IPFIX, sFlow, Netflow) - ★ 465



* [skm](https://github.com/TimothyYe/skm) - A simple and powerful SSH keys manager - ★ 461



* [metrics](https://github.com/codahale/metrics) - This is not the Java library. - ★ 431



* [mockingjay-server](https://github.com/quii/mockingjay-server) - Fake server, Consumer Driven Contracts and help with testing performance from one configuration file with zero system dependencies and no coding whatsoever - ★ 371



* [goboy](https://github.com/Humpheh/goboy) - Multi-platform Nintendo Game Boy Color emulator written in go - ★ 349



* [aurora](https://github.com/xuri/aurora) - Cross-platform Beanstalk queue server console. - ★ 325



* [gonative](https://github.com/inconshreveable/gonative) - Build Go Toolchains /w native libs for cross-compilation - ★ 298



* [godns](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports Cloudflare, DNSPod &amp; HE.net, written in Go. - ★ 288



* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via HTTP server - ★ 287



* [govvv](https://github.com/ahmetalpbalkan/govvv) - &quot;go build&quot; wrapper to add version info to Golang applications - ★ 285



* [wellington](https://github.com/wellington/wellington) - Spriting that sass has been missing - ★ 283



* [mora](https://github.com/emicklei/mora) - MongoDB generic REST server in Go - ★ 253



* [ipe](https://github.com/dimiro1/ipe) - An open source Pusher server implementation compatible with Pusher client libraries written in GO - ★ 240



* [IDE](https://github.com/thestrukture/ide) - IDE for web browser, built for Go with Go. - ★ 235



* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application - ★ 215



* [gocc](https://github.com/goccmack/gocc) - Parser / Scanner Generator - ★ 208



* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart). - ★ 197



* [lstags](https://github.com/ivanilves/lstags) - Manipulate Docker images across different registries - ★ 192



* [manssh](https://github.com/xwjdsh/manssh) - Manage your ssh alias configs easily. - ★ 185



* [cherry](https://github.com/rafael-santiago/cherry) - A tiny webchat server in Go. - ★ 176



* [gobrew](https://github.com/cryptojuice/gobrew) - Shell script to download and set GO environmental paths to allow multiple versions. - ★ 174



* [orange-cat](https://github.com/noraesae/orange-cat) - A Markdown previewer written in Go - ★ 172



* [pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester for websites and web services - ★ 171



* [tenyks](https://github.com/kyleterry/tenyks) - The Tenyks IRC bot. - ★ 166



* [ostent](https://github.com/ostrost/ostent) - Ostent is a server tool to collect, display and report system metrics. - ★ 157



* [blast](https://github.com/dave/blast) - Blast is a simple tool for API load testing and batch jobs - ★ 152



* [grapes](https://github.com/yaronsumel/grapes) - easy way to distribute commands over ssh. - ★ 113



* [orbit](https://github.com/gulien/orbit) - A cross-platform task runner for executing commands and generating files from templates - ★ 113



* [joincap](https://github.com/assafmo/joincap) - Merge multiple pcap files together, gracefully. - ★ 106



* [boxed](https://github.com/tejo/boxed) - dropbox based blog engine, written in go. - ★ 70



* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - easyssh-proxy provides a simple implementation of some SSH protocol features in Go - ★ 67



* [ddns](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend. - ★ 58



* [go-furnace](https://github.com/go-furnace/go-furnace) - Go Hosting Solution with CloudFormation and CodeDeploy - ★ 49



* [kcli](https://github.com/cswank/kcli) - A kafka command line browser - ★ 47



* [winrm-cli](https://github.com/masterzen/winrm-cli) - Command-line tool to remotely execute commands on Windows machines through WinRM - ★ 45



* [dropship](https://github.com/chrismckenzie/dropship) - Super simple deployment tool - ★ 42



* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI. - ★ 41



* [rodent](https://github.com/alouche/rodent) - Manage Go Versions/Projects/Dependencies - ★ 31



* [jaydiff](https://github.com/yazgazan/jaydiff) - A JSON diff utility - ★ 24



* [naclpipe](https://github.com/unix4fun/naclpipe) - NaCL pipe - ★ 20



* [awsenv](https://github.com/soniah/awsenv) - AWS environment config loader - ★ 16



* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Drone plugin for trigger Jenkins jobs. - ★ 16



* [snitch](https://github.com/lucasgomide/snitch) - Keep updated about all deploys on Tsuru - ★ 15



* [term-quiz](https://github.com/crazcalm/term-quiz) - Terminal Quiz Application Written in Go - ★ 14



* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - A Chrome extension for golang users.When you&#39;re at golang&#39;s official doc site, it will show function&#39;s description as tooltip on function list - ★ 12



* [depcharge](https://github.com/centerorbit/depcharge) - DepCharge is a tool designed to help orchestrate the execution of commands across many directories at once. - ★ 6



* [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command. - ★ 5



* [sg](https://github.com/ChristopherRabotin/sg) - Stress gauge allows one to gauge response times of an HTTP service under stress. - ★ 3




## Benchmarks



* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router and web framework benchmark - ★ 1146



* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark - ★ 872



* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark - ★ 820



* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods - ★ 724



* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language - ★ 153



* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - A few miscellaneous Go microbenchmarks. - ★ 106



* [autobench](https://github.com/davecheney/autobench) - Go benchmark harness. - ★ 88



* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs - ★ 84



* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language. - ★ 51



* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - A benchmarking shootout of various db/SQL utilities for Go - ★ 47



* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Application for HTTP benchmarking via different rules and configs - ★ 18



* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of micro benchmarks. - ★ 15



* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark - ★ 14



* [go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go. - ★ 5




## E-Books



* [GoBooks](https://github.com/dariubs/GoBooks) - List of Golang books - ★ 5575



* [web-dev-golang-anti-textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) - Learn how to write webapps without a framework in Go. - ★ 2136




## Gophers



* [gophers](https://github.com/ashleymcnamara/gophers) - Gopher Artwork by Ashley McNamara - ★ 1498



* [gophers](https://github.com/egonelbre/gophers) - Free gophers - ★ 1285



* [gophericons](https://github.com/shalakhin/gophericons) - 34 gopher images for Go developers community - ★ 548



* [gopher-stickers](https://github.com/tenntenn/gopher-stickers) - gopher stickers - ★ 392



* [gopher-vector](https://github.com/golang-samples/gopher-vector) - Vector data of gopher - ★ 318



* [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize.me app - ★ 251



* [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos - ★ 48



* [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics - ★ 47



* [go-gopher](https://github.com/sillecelik/go-gopher) - The Go Gopher Amigurumi Pattern - ★ 28



* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg] - ★ 25




## Websites



* [go](https://github.com/golang/go/wiki/Projects) - ★ 49162



* [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) - A golang ebook intro how to build a web with golang - ★ 26182



* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of awesome awesomeness - ★ 22663



* [awesome-remote-job](https://github.com/lukasz-madon/awesome-remote-job) - A curated list of awesome remote jobs and resources. Inspired by - ★ 12886



* [go-lang-cheat-sheet](https://github.com/a8m/go-lang-cheat-sheet) - An overview of Go syntax and features. - ★ 3520



* [learn-go-with-tests](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development - ★ 2283



* [working-with-go](https://github.com/mkaz/working-with-go) - A set of example golang code to start learning Go - ★ 1054



* [golang-graphics](https://github.com/mholt/golang-graphics) - Community-contributed Go graphics files - ★ 137



* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - List of opensource projects looking for help - ★ 30







