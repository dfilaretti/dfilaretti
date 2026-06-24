# 👋 About 

Over the last decade I've worked across compiler engineering, audio/music software, functional programming and blockchain; today I work on building static analysis tools for Solidity smart contracts using C++ and MLIR.  

I have a PhD in Computer Science from Imperial College London, where I focused on programming languages and formal methods (mostly static analysis and abstract interpretation).   

I've worked remotely for most of my career and am comfortable collaborating in distributed, async-first teams across time zones.  

Outside of software, I'm an electronic music producer and artist.

* [🧑‍💻 stuff I'm  working on](#-stuff-im-working-on)
* [📚 stuff I'm learning](#-stuff-im-learning)
* [🎧 selected past projects](#-past-projects-audio--music-technology)
* [🧪 research & publications](#-research--publications)

For more details, please also see my [LinkedIn](https://www.linkedin.com/in/danfilaretti/) profile.

# 🧑‍💻 Stuff I'm working on

I'm currently employed as a Senior R&D Engineer at [Veridise](https://veridise.com/) where I develop static analysis tools for Solidity smart contracts using C++ & MLIR. 

# 📚 Stuff I'm learning

Lately I've been working a lot with LLM tools and trying to understand their effectiveness and limitations 
in the context of the specific projects I'm involved. 

<br><br><br>

# 🎧 Selected past projects

## Audio & music technology

### Loopcloud

<a href="https://www.loopcloud.com/"><img src="assets/img/loopcloud.png" align="right" width="550"/></a>

<em>Developer<br>2020-2024</em>

Since 2020, I contributed to the development of the Loopcloud desktop app and its companion audio plugin 
(which syncs the app to the user's DAW for a more integrated experience).

I delivered several new major features (such as <em>collections</em>, MIDI support and an onboarding interactive tutorial), 
and an extensive UI rework, in addition to countless bug fixes and workflow improvements.

<br><br><br><br>

### TATAT

<a href="https://k-devices.com/products/tatat/"><img src="assets/img/tatat-dark.png" align="right" width="500"/></a>

<em>Lead developer<br>2021-2022</em>

[TATAT](https://k-devices.com/products/tatat/) is a MIDI plugin designed for 3 main purposes: to 
create always-changing sequences, to quickly sketch and store music ideas, to add unexpected 
events to fixed patterns.

<br><br><br><br><br><br>

### df.arp

<a href="https://github.com/dfilaretti/uplift-arpeggio"><img src="assets/img/uplift-arpeggio.png" align="right" width="500"/></a>

<em>Author<br>2020-Present</em>

A Max4Live device I built for helping me quickly come up with lead 
patterns when writing trance. It started as a 2020 lockdown project 
but it's still receiving updates! 

Available [here](https://dfmusic.gumroad.com/l/df-arp)!

<br><br>

## 💻 Compilers & formal methods

### K-Framework (Haskell backend)

<a href="https://github.com/runtimeverification/haskell-backend"><img src="assets/img/k-logo-dark.png" align="right" width="200"/></a>

<em>Developer<br>2018</em>

According to its [official docs](https://kframework.org/index.html), 

<em>"K is a rewrite-based executable semantic framework in which programming languages, 
type systems and formal analysis tools can be defined using configurations and rules"</em>

I loved using K as the foundational framework for my [research work](https://www.doc.ic.ac.uk/~maffeis/phpsemantics/) as a PhD student,  
and I was privileged, a couple of years later, to be able to contribute 
back to its community (as well as practicing some [Haskell](https://www.haskell.org/)!)

<br><br>

### Solidity to IELE compiler

<a href="https://github.com/runtimeverification/haskell-backend"><img src="assets/img/iele-2.png" align="right" width="200"/></a>

<p><em>Developer<br>2018</em></p>

[IELE](https://runtimeverification.com/the-iele-virtual-machine) is an improvement on the [Ethereum blockchain virtual machine](https://ethereum.org/en/developers/docs/evm/).
 It was created after the [KEVM](https://github.com/runtimeverification/evm-semantics) project demonstrated that a K formal specification of EVM could automatically generate a VM comparable in performance to hand-crafted implementations.

I helped developing the Solidity to IELE compiler.

<br><br><br>

## 💻 Miscellaneous (apps, cool stuff)

### Yapster

<a href=""><img src="assets/img/yapster.png" align="right" width="175"/></a>
<em>Clojure Developer (full-stack)<br>2019 - 2020</em>

Helped developing [Yapster](https://www.yapster.info/) - a messaging app for the workplace; contributing new features across both frontend and backend as well as bug-fixes (Clojure/ClojureScript).

I <em> really </em> enjoyed learning and working with the [Clojure](https://clojure.org/) 
programming language! 

<br><br><br>

### DIMMAND

<a href="https://www.festoon.studio/dimmand"><img src="assets/img/dimmand.png" align="right" width="200"/></a>

<em>Lead Developer<br>2016 - 2017</em>

Lead the development of [DIMMAND](https://www.festoon.studio/dimmand), a cross-platform 
digital solution for detecting literacy difficulties 
& strengths in children.

<br><br>

### ne - the nice editor

<a href="https://github.com/vigna/ne"><img src="assets/img/ne.png" align="right" width="200"/></a>

<em>Internship<br>2009 - 2008</em>

Implemented syntax highlighting in the ne text editor. 

<br><br>

# 🧸 Toy projects 

## img2ASCII

<a href="https://github.com/dfilaretti/img2ascii_rust"><img src="assets/img/img2ascii.png" align="right" width="400"/></a>

<em>Author<br>2025-Present</em>

As I've been [learning Rust](#-stuff-im-learning) during the last couple of months, I decided to get some practice by building this fun little project
that converts image files to ASCII art. 

One of the goals was also to familiarize with functional programming techniques in Rust 
(e.g. I didn't use any `for` loop to iterate through the image pixels, but relied on iterators facilities; also tried not to use `mut`able variables)

Check out the [README](https://github.com/dfilaretti/img2ascii_rust)!

# 🧪 Research & publications

I hold a PhD in <em>Computing</em> from [Imperial College London](https://www.imperial.ac.uk/), where I worked in the field
of <em>programming language</em> theory and <em>formal methods</em>. 

My thesis was about the formalisation of the PHP programming language 
and the development of a static analysis tool derived from the formal semamtics (see below).

Here are the main research projects and publications I worked on during the years. 

## Projects

### K-PHP (Executable formal semantics of PHP)

<em>Lead Developer / PhD Student<br>2018</em>

[KPHP](https://github.com/dfilaretti/KPHP) is a <em>formal specification</em> of the PHP 
programming language written in the [K-Framework](https://kframework.org/index.html), 
together with a prototype bug finding tool based on the theory 
of [abstract interpretation](https://en.wikipedia.org/wiki/Abstract_interpretation) 
and derived directly from the formal semantics.

* [website](https://phpsemantics.org/)
* [repo](https://github.com/dfilaretti/KPHP)
* [paper](assets/publications/ecoop14.pdf)
* [PhD thesis](assets/publications/Filaretti-D-PhD-2016.pdf)

### JCCert / JSRef (Certified Javascript)

<em>Developer / PhD Student<br>2018</em>

[JSCert](https://jscert.org/) is a <em>mechanised specification</em> of JavaScript, 
written in the [Coq](https://coq.inria.fr/) proof assistant.
JSRef is a <em>reference interpreter</em> for JavaScript in OCaml, which has 
been proved correct with respect to JSCert and tested with the Test 262 test suite.

* [website](https://jscert.org/)
* [repo](https://github.com/jscert/jscert)
* [paper](assets/publications/popl14.pdf)

## Publications 

### 2019

* [IELE: A Rigorously Designed Language and Tool Ecosystem for the Blockchain](assets/publications/iele-fm-2019.pdf) with T. Kasampalis, D. Guth, B. Moore, T. Serbanuta, V. Serbanuta, G. Rosu and Ralph Johnson - International Symposium on Formal Methods 2019. 

### 2018

* [A Digital App to Aid Detection, Monitoring, and Management of Dyslexia in Young Children (DIMMAND): Protocol for a Digital Health and Education Solution](http://www.researchprotocols.org/2018/5/e135/) with MR Sood, A. Toornstra, M. Sereno, M. Boland, A. Sood - 2018 

### 2016

* [An Executable Formal Semantics of PHP with Applications to Program Analysis](assets/publications/Filaretti-D-PhD-2016.pdf). PhD Thesis, Imperial College London, 2016.

### 2014

* [An Executable Formal Semantics for PHP](assets/publications/ecoop14.pdf) - with S. Maffeis - ECOOP 2014.

* [A Trusted Mechanised JavaScript Specification](assets/publications/popl14.pdf) - with M. Bodin, A. Chargueraud, P. Gardner, S.Maffeis, D. Naudziuniene, A. Schmitt, G. Smith - POPL 2014.

### 2011

* [Building bricks with bricks, with Mathematica](assets/publications/mathematica11.pdf) - with P. Codara, O. D'Antona - Mathematica Italian User Group Meeting 2011.
