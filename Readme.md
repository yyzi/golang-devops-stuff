## Golang Lib for DevOps
  - metrics
  - monitoring
  - servers
  - global locking / paxos / raft
  - Cloud API clients


## Locking Server/PubSub
  - http://www.reddit.com/r/golang/comments/1oqqx7/gnatsd_from_apcera_a_high_performance_nats_server/
    - NATS does not have persistence, or transactions. It is more like a nervous system, and it will protect itself at all costs and does not have SPOFs. It does publish/subscribe, and distributed queues.
    - http://www.quora.com/Cloud-Foundry/Why-does-CloudFoundry-use-NATS-a-specially-written-messaging-system-whereas-OpenStack-uses-AMQP
    AMQP, and implementations like RabbitMQ, are enterprise messaging systems built with things like durability, transactions, and formal queues. NATS was designed and built to be like a dial-tone publish-subscribe service, something that is always on and available. However, NATS does not provide durability or transactions, and its queuing model is interest-based only. It also protects itself, the NATS service, at all costs, so that it can always be available. This forms a great base platform for building scalable and reliable distributed systems, but is probably not a good fit for the typical enterprise application.


## Why Golang for DevOps?
  - [Go Language for Ops and Site Reliability Engineering](http://talks.golang.org/2013/go-sreops.slide)


  This repository is supposed to work with [DirEnv](https://github.com/zimbatm/direnv). It will set the GOPATH to current directory and append the ./bin folder to your PATH variable.


<!-- PROJECTS_LIST_START -->
    *** GENERATED BY https://github.com/mindreframer/techwatcher (ruby _sh/pull golang-devops-stuff) *** 

    abh/geodns:
      DNS server with per-client targeted responses
       230 commits, last change: 2013-10-03 00:14:57, 225 stars, 17 forks

    adnaan/hamster:
      A back end as a service based on MongoDB
       43 commits, last change: 2013-06-04 00:51:55, 44 stars, 1 forks

    apcera/gnatsd:
      High Performance NATS Server
       267 commits, last change: 2013-10-21 16:06:59, 133 stars, 5 forks

    apcera/nats:
      NATS client for Go
       206 commits, last change: 2013-10-20 12:12:17, 44 stars, 7 forks

    benbjohnson/go-raft:
      A Go implementation of the Raft distributed consensus protocol.
       362 commits, last change: 2013-10-14 12:40:20, 410 stars, 39 forks

    bitly/google_auth_proxy:
      A reverse proxy that provides authentication using Google OAuth2
       15 commits, last change: 2013-07-30 14:31:59, 105 stars, 18 forks

    bitly/nsq:
      realtime distributed message processing at scale
       942 commits, last change: 2013-10-19 10:04:38, 1,506 stars, 129 forks

    buger/gor:
      HTTP traffic replay in real-time. Replay traffic from production to staging and dev environments.
       192 commits, last change: 2013-10-21 05:42:10, 888 stars, 47 forks

    BurntSushi/cmail:
      cmail runs a command and sends the output to your email address at certain intervals.
       8 commits, last change: , 2 stars, 0 forks

    cloudfoundry/gorouter:

       336 commits, last change: 2013-08-27 16:14:13, 66 stars, 22 forks

    coreos/etcd:
      A highly-available key value store for shared configuration and service discovery
       652 commits, last change: 2013-10-22 09:45:47, 1,560 stars, 118 forks

    crowdmob/goamz:
      Fork of the GOAMZ version developed within Canonical with additional functionality with DynamoDB
       372 commits, last change: 2013-10-21 07:41:35, 51 stars, 31 forks

    dotcloud/docker:
      Docker - the open-source application container engine
       3,629 commits, last change: 2013-10-22 11:31:49, 6,703 stars, 802 forks

    errplane/errplane-go:
      Go library for metrics for Errplane
       52 commits, last change: , 7 stars, 0 forks

    flynn/go-crypto-ssh:
      Forked from go.crypto as Flynn working copy until changes merged upstream
       4 commits, last change: 2013-10-15 17:12:20, 1 stars, 0 forks

    flynn/go-discover:
      Service discovery system written in Go
       31 commits, last change: 2013-10-09 12:39:50, 50 stars, 4 forks

    flynn/rpcplus:
      Go RPC plus streaming responses (forked from vitess)
       8 commits, last change: 2013-10-06 11:26:17, 10 stars, 0 forks

    globocom/gandalf:
      Gandalf is an API to manage git repositories.
       446 commits, last change: 2013-10-21 10:15:25, 95 stars, 13 forks

    globocom/tsuru:
      Open source Platform as a Service.
       6,026 commits, last change: 2013-10-22 12:40:15, 695 stars, 54 forks

    golang/groupcache:
      groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
       19 commits, last change: 2013-10-03 20:14:56, 2,285 stars, 191 forks

    jondot/gosigar:

       13 commits, last change: , 2 stars, 15 forks

    jondot/groundcontrol:
      Manage and monitor your Raspberry Pi with ease
       50 commits, last change: 2013-08-22 07:19:32, 610 stars, 41 forks

    jordansissel/lumberjack:
      An experiment to cut logs in preparation for processing elsewhere.
       521 commits, last change: 2013-10-21 10:07:59, 233 stars, 57 forks

    juju/juju-core:

        commits, last change: ,  stars,  forks

    mindreframer/emtail:
      extract whitebox monitoring data from logs and insert into a timeseries database - mirror for https://code.google.com/p/emtail/
       273 commits, last change: 2013-09-11 01:02:07, 0 stars, 0 forks

    mitchellh/packer:
      Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
       1,992 commits, last change: 2013-10-20 21:01:51, 1,319 stars, 183 forks

    mozilla-services/heka:
      Data collection and processing made easy.
       1,530 commits, last change: 2013-10-21 12:15:03, 751 stars, 65 forks

    necrogami/watchdog:
      Watchdog
       7 commits, last change: 2012-12-06 00:30:13, 1 stars, 1 forks

    nf/gohttptun:
      A tool to tunnel TCP over HTTP, written in Go
       20 commits, last change: 2013-09-22 17:01:00, 54 stars, 13 forks

    petar/GoTeleport:
      Teleport Transport: End-to-end resilience to network outages
       6 commits, last change: 2013-08-30 10:54:44, 92 stars, 0 forks

    rackspace/gophercloud:
      A multi-cloud language binding for Go
       129 commits, last change: 2013-09-16 13:11:20, 169 stars, 9 forks

    rcrowley/go-metrics:
      Go port of Coda Hale's Metrics library
       131 commits, last change: 2013-10-21 13:54:22, 177 stars, 26 forks

    Sendhub/shipbuilder:
      The Open-source self-hosted Platform-as-a-Service written in Go
       135 commits, last change: 2013-10-21 17:24:27, 0 stars, 20 forks

    skydb/sky:
      Sky is an open source, behavioral analytics database.
       556 commits, last change: 2013-04-02 07:23:03, 218 stars, 23 forks

    skynetservices/skydns:
      DNS for skynet or any other service discovery
       67 commits, last change: 2013-10-21 17:15:11, 91 stars, 7 forks

    spf13/nitro:
      Quick and easy performance analyzer library for golang
       7 commits, last change: 2013-10-03 06:43:07, 55 stars, 3 forks

    VividCortex/robustly:
      Run functions resiliently
       21 commits, last change: 2013-07-30 08:59:36, 43 stars, 1 forks

    xtaci/gonet:
      a game server skeleton with golang
       900 commits, last change: 2013-08-31 07:06:26, 74 stars, 30 forks
<!-- PROJECTS_LIST_END -->
