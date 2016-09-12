# ElixirConf 2016 Summary

A collection of links that cover what happened during ElixirConf 2016. Please feel free to submit a PR!

## Day 0

#### SimAlchemy by [James Edward Gray II](https://github.com/jeg2)

- Slides:
    + [Process Basics](https://github.com/sabondano/elixirconf-2016/blob/master/process_basics_slides.pdf)
    + [GenServer and Friends](https://github.com/sabondano/elixirconf-2016/blob/master/genserver_and_friends_slides.pdf)
    + [Supervisors](https://github.com/sabondano/elixirconf-2016/blob/master/supervisors_slides.pdf)
    + [OTP Strategy](https://github.com/sabondano/elixirconf-2016/blob/master/otp_strategy_slides.pdf)
- Links:
    + [Simulations](https://github.com/JEG2/simulations)
    + [Event Sourcing](http://martinfowler.com/eaaDev/EventSourcing.html)

#### Phoenix - Getting realtime with channels

- Links:
    + [Sketchpad](https://github.com/chrismccord/sketchpad)

#### Taking Off with Phoenix

- Links: ...

#### Badge Hacking with Nerves

- Links: ...

#### Learning Elixir through TrueStory by [Bruce Tate](https://github.com/batate) and [Eric Meadows-Jönsson](https://github.com/ericmj)

- Links:
    + [Workshop](https://github.com/ericmj/workshop)
    + [TrueStory](https://hex.pm/packages/true_story)

## Day 1

### Talks

#### Erlang Solutions Message
- "supercharged observer" https://www.erlang-solutions.com/products/wombat-oam.html

#### Opening Keynote by [Chris McCord](https://twitter.com/chris_mccord)

- Video - Not uploaded yet
- Slides - Not uploaded yet. Submit a [PR](https://github.com/poteto/elixirconf-2016/pulls) if you find it!
- Links:
    + [2m connections in Phoenix](http://www.phoenixframework.org/blog/the-road-to-2-million-websocket-connections)
    + [Programming Phoenix book](http://bit.ly/phoenix_book) - Discount code: `ElixirConfUS2016_phoenix`
    + [Phoenix Presence blog post](https://dockyard.com/blog/2016/03/25/what-makes-phoenix-presence-special-sneak-peek)
    + [Nerves - Embedded Elixir](http://nerves-project.org/)
    + [New folder structure for Phoenix](https://twitter.com/antondom/status/771341202071384064)
    + [Phoenix Presence docs](https://hexdocs.pm/phoenix/Phoenix.Presence.html)
    + [Phoenix Presence podcast on the changelog](https://changelog.com/208/)
    + [CRDTs](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type)

#### Abstractions: A Tale of Keys and Values by [Ernie Miller](https://github.com/erniemiller)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/erniemiller/abstractions-a-tale-of-keys-and-values)
- Links: ...

#### Implementing binary protocols with Elixir by [Ole Michaelis](https://twitter.com/CodeStars)

- Video - Not uploaded yet
- [Slides](https://slidr.io/nesQuick/implementing-binary-protocols-with-elixir)
- Links:
    + https://github.com/nesQuick/elixir-hpack
    + https://http2.github.io/http2-spec/compression.html
    + https://http2.github.io/http2-spec/
    + http://daniel.haxx.se/http2/
    + https://github.com/ninenines/cowlib/blob/master/src/cow_hpack.erl
    + http://elixir-lang.org/docs/stable/elixir/Bitwise.html#%3C%3C%3C/2
    + http://www.slideshare.net/peychevi/http2-and-quick-protocols-optimizing-the-web-stack
    + https://ma.ttias.be/architecting-websites-http2-era/
    + https://benramsey.com/talks/2015/05/phptek-http2/
    + https://speakerdeck.com/summerwind/2-prioritization
    + http://chimera.labs.oreilly.com/books/1230000000545/ch12.html#HTTP2_HEADER_COMPRESSION
    + http://tools.ietf.org/html/rfc6585
    + https://http2.golang.org/
    + https://aprescott.com/posts/spdy-colon-headers
    + https://tools.ietf.org/html/draft-ietf-httpbis-header-compression-12
    + http://news.netcraft.com/archives/2015/06/25/june-2015-web-server-survey.html

#### pg2 and You: Getting Distributed with Elixir by [Eric Entin](https://twitter.com/antipax)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/antipax/pg2-and-you-getting-distributed-with-elixir)
- Links:
    + [pg2 docs](http://erlang.org/doc/man/pg2.html)
    + [phoenix pubsub](https://github.com/phoenixframework/phoenix_pubsub)
    + [RePG2](https://github.com/antipax/repg2)
    + [gen_server](http://erlang.org/doc/man/gen_server.html)
    + [global](http://erlang.org/doc/man/global.html)
    + [net_kernel](http://erlang.org/doc/man/net_kernel.html)

#### The future of deployment in Elixir by [Paul Schoenfelder](https://twitter.com/gotbones)

- Video - Not uploaded yet
- Slides - Not uploaded yet. Submit a [PR](https://github.com/poteto/elixirconf-2016/pulls) if you find it!
- Links:
    + [Distillery](https://github.com/bitwalker/distillery)
    + [edeliver](https://github.com/boldpoker/edeliver)
    + [OpenShift](https://www.openshift.com)

#### Code Spelunking for Knowledge and Profit by [Brian Cardarella](https://twitter.com/bcardarella)

- Video - Not uploaded yet
- Slides - Not uploaded yet. Submit a [PR](https://github.com/poteto/elixirconf-2016/pulls) if you find it!
- Links:
    + [Ecto](https://github.com/elixir-ecto/ecto)
    + [Phoenix.Naming](https://hexdocs.pm/phoenix/Phoenix.Naming.html)
    + [Compile.Phoenix](https://github.com/phoenixframework/phoenix/blob/master/lib/mix/tasks/compile.phoenix.ex)
    + [Kernel.pop_in/2](https://dockyard.com/blog/2016/06/05/elixir-1-3-kernel-pop-in)
    + [ExUnit.Case.register_attribute/3](http://elixir-lang.org/docs/stable/ex_unit/ExUnit.Case.html#register_attribute/3)
    + [elixir_rewrite](https://github.com/elixir-lang/elixir/blob/master/lib/elixir/src/elixir_rewrite.erl)
    + [Kernel.SpecialForms](http://elixir-lang.org/docs/stable/elixir/Kernel.SpecialForms.html)

#### Giving up the Object-Oriented Ghost by [Zoe Laco](https://twitter.com/morganlaco)

- Video - Not uploaded yet
- [Slides](http://slides.com/morganlaco/deck-2/)
- Links:
    + [From Imperative to Functional and Back-Monads are for Functional Languages](https://www.infoq.com/articles/Dont-graft-Monads-onto-Imperative-Languages)
    + [From Imperative to Functional: How to Make the Leap](http://loup-vaillant.fr/tutorials/from-imperative-to-functional)
    + [A Practical Introduction to Functional Programming](https://maryrosecook.com/blog/post/a-practical-introduction-to-functional-programming)
    + [Elixir Getting Started Guide](http://elixir-lang.org/getting-started/recursion.html)
    + [Destroy All Ifs](http://degoes.net/articles/destroy-all-ifs)
    + [16 Months of Functional Programming](http://www.vasinov.com/blog/16-months-of-functional-programming/#toc-immutable-state)
    + [Learn You Haskell](http://learnyouahaskell.com/introduction)
    + [How to Switch from the Imperative Mindset](http://www.lispcast.com/imperative-mindset)
    + [Functional Programming Techniques With Ruby: Part I](https://www.sitepoint.com/functional-programming-techniques-with-ruby-part-i/)
    + [From Imperative to Functional Programming (for Absolute Beginners)](http://www.slideshare.net/alexbunardzic/from-imperative-to-functional-programming-43476397)
    + [Transposing a Matrix: Thinking Recursively in Elixir](http://langintro.com/elixir/article2/)
    + [Don’t Be Scared Of Functional Programming](https://www.smashingmagazine.com/2014/07/dont-be-scared-of-functional-programming/)
    + [Myth of the Day: Functional Programmers Don't Use Loops](https://two-wrongs.com/myth-of-the-day-functional-programmers-dont-use-loops)
    + [ElixirSchool](http://www.elixirschool.com)
    + [Elixir courses at Code School (coming soon)](https://www.codeschool.com)

#### Nerves: Connected beyond the Node by [Justin Schneck](https://twitter.com/mobileoverlord)

- Video - Not uploaded yet
- Slides - Not uploaded yet. Submit a [PR](https://github.com/poteto/elixirconf-2016/pulls) if you find it!
- Links: ...

#### Selling Food With Elixir by [Chris Bell](https://twitter.com/cjbell_)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/cjbell88/selling-food-with-elixir-elixirconf-2016)
- Links:
    + [The app Chris built for his client](http://cavagrill.com/)
    + [gen_retry](https://github.com/appcues/gen_retry)
    + [ets](http://erlang.org/doc/man/ets.html)
    + [immortal](https://github.com/danielberkompas/immortal)
    + [httpotion](https://github.com/myfreeweb/httpotion)
    + [httpoison](https://github.com/edgurgel/httpoison)

#### Debugging techniques in Elixir by [Erich Kist](https://twitter.com/erichkist)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/erichkist/debugging-techniques-in-elixir-elixirconf-2016)
- Links: ...

#### Migrating an invoicing system to Elixir/Erlang by [Norberto Ortigoza](https://twitter.com/hiphoox)

- Video - Not uploaded yet
- [Slides (zip)](https://dl.dropboxusercontent.com/u/3443349/ElixirConf-ErlangFactory.zip)
- Links: ...

#### Building "learn to touch type" glove with Elixir and Arduino by [Tetiana Dushenkivska](https://twitter.com/tetiana12345678)

- Video - Not uploaded yet
- [Slides](http://goo.gl/iS5K0j)
- [Gifs used in slides](https://github.com/tetiana12345678/touch_typing_glove_pressie_orlando_gifs)
- Links:
    + [Typehero_project on github](https://github.com/tetiana12345678/typehero_project)
    + [All about Arduino](https://www.arduino.cc/)
    + [Conductive materials](http://www.kobakant.at/DIY/?cat=24)
    + [Velostat](https://www.adafruit.com/product/1361)
    + [Serial library](https://github.com/bitgamma/elixir_serial) and [Nerves_uart](https://github.com/nerves-project/nerves_uart) for hardware/software communication.

#### Phoenix Beyond the Browser - Realtime Applications with Phoenix and Swift by [David Stump](https://twitter.com/davidstump)

- Video - Not uploaded yet
- [Slides, Demo Apps, and Code Samples](https://github.com/davidstump/phoenix_beyond_the_browser)
- Links:
    + [All resources](https://github.com/davidstump/phoenix_beyond_the_browser)
    + [Birdsong](https://github.com/sjrmanning/Birdsong)
    + [SwiftPhoenixClient](https://github.com/davidstump/SwiftPhoenixClient)
    + [RayWenderlich](https://www.raywenderlich.com/)
    + [SwiftPlaygrounds](https://www.apple.com/swift/playgrounds/)
    + [phoenix_chat_example](https://github.com/chrismccord/phoenix_chat_example)

#### No REST for the wicked: Building a GraphQL API by [Ben Wilson](https://twitter.com/benwilson512)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/benwilson512/no-rest-for-the-wicked)
- Links:
    + [Absinthe GraphQL](https://github.com/absinthe-graphql/absinthe)

#### Measuring your Elixir Application by [Renan Ranelli](https://twitter.com/renanranelli)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/rranelli/elixirconf-2016-measuring-your-elixir-app)
- Links:
    + [Zed Shaw on Statistics](https://zedshaw.com/archive/programmers-need-to-learn-statistics-or-i-will-kill-them-all/)
    + [Blog post on measuring your elixir apps](http://milhouseonsoftware.com/2016/05/08/measuring-your-elixir-application/)
    + [Other blog post on measuring elixir apps](http://tech.footballaddicts.com/blog/gathering-metrics-in-elixir-applications)
    + [Grafana](http://grafana.org/)
    + [InfluxDB](https://influxdata.com/)
    + [collectd](https://collectd.org/)
    + [haproxy](http://www.haproxy.org/)
    + [clojurescript](https://github.com/clojure/clojurescript)
    + [exometer](https://github.com/Feuerlabs/exometer)
    + [elixometer](https://github.com/pinterest/elixometer)
    + [vmstats](https://github.com/ferd/vmstats)

#### Edgelixir: Distributed Graph Processing in Elixir by [Nathan Lapierre](https://twitter.com/n_lap)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/nlap/edgelixir-distributed-graph-processing-in-elixir)
- Links:
    + [Edgelixir](https://github.com/nlap/edgelixir)

#### Lightning Talks
- [René Föhring](https://twitter.com/rrrene)
    + [Credo](https://github.com/rrrene/credo)
    + [ElixirStatus](http://elixirstatus.com/)
- [Pete Gamache](https://twitter.com/gamache)
    + [gen_retry](https://github.com/appcues/gen_retry)
    + [slides](http://www.slideshare.net/petegamache/genretry-simple-exponential-backoff-in-elixir)
- [Faheem Mughal](https://twitter.com/hallx)
    + [poolboy](https://github.com/devinus/poolboy)
- [Rockwell Schrock](https://twitter.com/Schrockwell)
    + [authy](https://github.com/schrockwell/authy)
- [Luke Imhoff](https://twitter.com/kronicdeth)
    + [RabbitMQ](https://www.rabbitmq.com/)
- [Jay Hayes](https://twitter.com/iamvery)
    + [Ratchet](https://github.com/iamvery/ratchet)
    + [Phoenix Ratchet](https://github.com/iamvery/phoenix_ratchet)
    + [slatchet](https://github.com/iamvery/slatchet)
- [Josh Adams](https://twitter.com/knewter)
    + [DailyDrip](https://www.dailydrip.com/)
- [Casey Rosenthal](https://twitter.com/caseyrosenthal)
    + [SimianArmy](https://github.com/Netflix/SimianArmy)
    + [Principles of Chaos](http://principlesofchaos.org/)
    + [ChaosCommunity](http://chaos.community/)
- [Przemyslaw Krowinski](https://twitter.com/sanesquid)
    + [game](https://github.com/archdragon/game_engine_elixir_phoenix)
- [Fernand Galiana](https://twitter.com/kitesurfer)
    + [Kubernetes](http://kubernetes.io/)
    + [Docker Compose](https://docs.docker.com/compose/)
- [Aaron Renner](https://twitter.com/bayfieldcoder)
    + [Slides (Mocks, Adapters and Microservices)](http://slides.com/aaronrenner/deck)
    + [Mocks](http://blog.plataformatec.com.br/2015/10/mocks-and-explicit-contracts/)
    + [Adapters blog post](https://www.inverse.com/article/10674-here-s-how-inverse-tests-external-apis-in-elixir-with-bypass)
- [Gabe Klein](https://github.com/gabeklein)
    + [Socks](https://github.com/gabeklein/Socks)

## Day 2

### Talk

#### Keynote by [José Valim](https://twitter.com/josevalim)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/plataformatec/genstage-and-flow-by-at-josevalim-at-elixirconf)
- [Notes on slides](https://gist.github.com/sanmiguel/d73056adb6cffc9954327d8fcd89cd48)
- Links:
    + [GenStage announcement](http://elixir-lang.org/blog/2016/07/14/announcing-genstage/)
    + [GenStage](https://github.com/elixir-lang/gen_stage)
    + ["Musketeer: all for one, one for all in data processing systems"](http://www.cs.utexas.edu/users/ncrooks/2015-eurosys-musketeer.pdf). Gog, _et al_. University of Cambridge, 2015.

#### String Theory by [James Edward Gray II](https://twitter.com/JEG2) and [Nathan Long](https://twitter.com/sleeplessgeek)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/nathanl/string-theory)
- Links: ...

#### Refactoring Techniques for Elixir, Ecto, and Phoenix by [Gary Rennie](https://twitter.com/TheGazler)

- Video - Not uploaded yet
- [Slides](http://blog.gazler.com/talks/refactoring-elixir)
- Links:
    + [Oxo GitHub Repository](https://github.com/Gazler/oxo)

#### Building umbrella project by [Wojtek Mach](https://twitter.com/wojtekmach)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/wojtekmach/building-an-umbrella-project)
- Links:
    + [Umbrella apps](http://elixir-lang.org/getting-started/mix-otp/dependencies-and-umbrella-apps.html)
    + [Architecture: The Lost Years (RubyConf 2011)](https://www.youtube.com/watch?v=WpkDN78P884)
    + [Wrangling Large Rails Codebases (Rocky Mountain Ruby 2012)](https://www.youtube.com/watch?v=FElnETSIMuo)
    + [The Art of Destroying Software (Leetspeek 2014)](https://vimeo.com/108441214)
    + [AcmeBank source](https://github.com/wojtekmach/acme_bank)
    + [ExAdmin](https://github.com/smpallen99/ex_admin)
    + [distillery](https://github.com/bitwalker/distillery)

#### Collaborative Music with Elm and Phoenix by [Josh Adams](https://twitter.com/knewter)

- Video - Not uploaded yet
- [Slides](http://www.slideshare.net/JoshAdams18/collaborative-music-with-elm-and-phoenix)
- Links:
    + [Colluder](https://github.com/knewter/colluder)

#### Leveling Up With Ecto by [Darin Wilson](https://twitter.com/darinwilson)

- Video - Not uploaded yet
- [Slides](https://dl.dropboxusercontent.com/u/14884175/leveling_up_with_ecto.pdf)
- Links:
    + [MusicDB example](https://github.com/darinwilson/music_db)
    + [ecto](https://github.com/elixir-ecto/ecto)
    + [ecto docs](https://hexdocs.pm/ecto/Ecto.html)
    + [Insert_all and schemaless queries](http://blog.plataformatec.com.br/2016/05/ectos-insert_all-and-schemaless-queries/)

#### Building Available and Partition Tolerant Systems with Phoenix Tracker by [Gabi Zuniga](https://twitter.com/gabiz)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/gabiz/elixir-conf-2016-building-available-and-partition-tolerant-systems-with-phoenix-tracker)
- Links:
    + [VoiceLayer](https://voicelayer.io)
    + [Dispatch Library](https://github.com/VoiceLayer/dispatch)
    + [Dht Example](https://github.com/VoiceLayer/dht)

#### From Front End to Full Stack with Elixir and Phoenix by [Lauren Tan](https://twitter.com/sugarpirate_)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/poteto/elixirconf-2016-from-front-end-to-full-stack-with-elixir-and-phoenix)
- Links:
    + [ember-changeset](https://github.com/DockYard/ember-changeset)
    + [Erlang the Movie II](https://www.youtube.com/watch?v=rRbY3TMUcgQ)
    + [The Little Elixir and OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook)
    + [Elixir in Action](https://www.manning.com/books/elixir-in-action)
    + [Key value data types best practices](https://engineering.appcues.com/2016/02/02/too-many-dicts.html)
    + [Dialyxir](https://github.com/jeremyjh/dialyxir)
    + [TDD with typespecs](https://medium.com/@barruumrex/seeking-simple-satisfaction-2a098902ddff)
    + [Metaprogramming Elixir](https://pragprog.com/book/cmelixir/metaprogramming-elixir)
    + [Terraform - incrementally replace your API with Phoenix](https://github.com/poteto/terraform) - [blogpost](https://medium.com/@sugarpirate/rise-from-the-ashes-incremental-apis-with-phoenix-b08cd66bd142#.hll7po4x0)
    + [Functional programming patterns](https://fsharpforfunandprofit.com/fppatterns/ )

#### Nerves + Phoenix Saves a Father's Sanity! by [Joel Byler](https://twitter.com/joelbyler)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/joelbyler/nerves-plus-phoenix-saves-a-fathers-sanity)
- Links:
    + [Project Github Repository](https://github.com/joelbyler/elixir_conf_chores)
    + [Project Custom Nerves System](https://github.com/joelbyler/nerves_system_rpi3_ap)
    + [Nerves Base Buildroot Config (great README for custom systems)](https://github.com/nerves-project/nerves_system_br)
    + [Project Custom Nerves System](https://github.com/joelbyler/nerves_system_rpi3_ap)
    + [Great advice on testing, written by José Valim](http://blog.plataformatec.com.br/2015/10/mocks-and-explicit-contracts/)


#### Concurrent Feature Testing with Wallaby by [Chris Keathley](https://twitter.com/ChrisKeathley)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/keathley/concurrent-feature-tests-with-wallaby)
- Links:
  + [Wallaby](https://github.com/keathley/wallaby)

#### The new calendar types in Elixir 1.3 by [Lau Taarnskov](https://twitter.com/lauT)

- Video - Not uploaded yet
- Slides - Not uploaded yet. Submit a [PR](https://github.com/poteto/elixirconf-2016/pulls) if you find it!
- Links: ...

#### Painless Test Driven Development with Elixir and Phoenix by [Kat Tornwall](https://twitter.com/ktornwall)

- Video - Not uploaded yet
- [Slides](https://github.com/ktornwall/elixir_conf_2016_demo/raw/master/slides.pdf)
- Links:
    + [Demo App](https://github.com/ktornwall/elixir_conf_2016_demo)

#### Dialyzer: Optimistic Type Checking for Erlang and Elixir by [Jason Voegele](https://twitter.com/jvoegele)

- Video - Not uploaded yet
- Slides:
    + [PDF](https://github.com/jvoegele/ElixirConf2016_dialyzer/blob/master/Dialyzer.pdf)
    + [Speakerdeck](https://speakerdeck.com/jvoegele/elixirconf-2016-dialyzer-optimistic-type-checking-for-erlang-and-elixir)
- [Sample Code](https://github.com/jvoegele/ElixirConf2016_dialyzer/)
- Links:
    + [Dialyzer](http://erlang.org/doc/man/dialyzer.html)
    + [Dialyxir](https://github.com/jeremyjh/dialyxir)

#### The Joy of Connecting Elixir to the Physical World by [Frank Hunleth](https://twitter.com/fhunleth)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/fhunleth/the-joy-of-connecting-elixir-to-the-physical-world)
- Links:
    + [elixir_ale](https://github.com/fhunleth/elixir_ale)
    + [nerves_uart](https://github.com/nerves-project/nerves_uart)

#### Elixir in Elixir by [Jay Hayes](https://twitter.com/iamvery)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/iamvery/elixir-in-elixir)
- Links:
    + [Getting Started with Elixir Metaprogramming](https://www.bignerdranch.com/blog/getting-started-with-elixir-metaprogramming/)

#### WebRTC and Phoenix, when μ seconds aren't fast enough by [Jason Stiebs](https://twitter.com/peregrine)

- Video - Not uploaded yet
- [Slides](https://speakerdeck.com/jeregrine/webrtc-for-when-m-seconds-are-not-fast-enough)
- Links:
    + [Demo app](https://phoenix-webrtc.herokuapp.com/)
    + [Phoenix WebRTC](https://github.com/jeregrine/phoenix_webrtc)
    + [Twilio Stun Turn](https://www.twilio.com/stun-turn)
    + [stun](https://github.com/processone/stun)
    + [WebRTC](https://hpbn.co/webrtc/)

#### Closing Keynote by [Boyd Multerer](https://twitter.com/BoydMulterer)

- Video - Not uploaded yet
- [Slides](https://github.com/boydm/presentations/blob/master/elixirconf_boydm_keynote.key)
- Links:
    + [Cloak blog post](http://blog.danielberkompas.com/2015/09/22/cloak-your-ecto-data.html)
    + [Cloak source](https://github.com/danielberkompas/cloak)
    + [FPGA article](http://www.theregister.co.uk/2016/03/14/intel_xeon_fpga/)
