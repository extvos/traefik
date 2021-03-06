# Change Log

## [v1.1.0-rc2](https://github.com/containous/traefik/tree/v1.1.0-rc2) (2016-10-17)
[Full Changelog](https://github.com/containous/traefik/compare/v1.1.0-rc1...v1.1.0-rc2)

**Implemented enhancements:**

- Support healthcheck if present for docker [\#666](https://github.com/containous/traefik/issues/666)

**Closed issues:**

- Sensible configuration for consulCatalog [\#737](https://github.com/containous/traefik/issues/737)
- Traefik ignoring container listening in more than one TCP port [\#734](https://github.com/containous/traefik/issues/734)
- Error when using HA acme in kubernetes with etcd [\#725](https://github.com/containous/traefik/issues/725)
- \[Docker swarm mode\] No round robin when using service [\#718](https://github.com/containous/traefik/issues/718)
- Dose it support docker swarm mode  [\#712](https://github.com/containous/traefik/issues/712)
- Kubernetes - Undefined backend  [\#710](https://github.com/containous/traefik/issues/710)
- Constraints on Consul Catalogue not working as expected [\#703](https://github.com/containous/traefik/issues/703)
- docker run syntax in swarm example has changed [\#528](https://github.com/containous/traefik/issues/528)
- Secure WebSockets [\#467](https://github.com/containous/traefik/issues/467)

**Merged pull requests:**

- Fix case sensitive host [\#733](https://github.com/containous/traefik/pull/733) ([emilevauge](https://github.com/emilevauge))
- Update Kubernetes examples [\#731](https://github.com/containous/traefik/pull/731) ([Starefossen](https://github.com/Starefossen))
- fIx marathon template with dots in ID [\#728](https://github.com/containous/traefik/pull/728) ([emilevauge](https://github.com/emilevauge))
- Fix networkMap construction in ListServices [\#724](https://github.com/containous/traefik/pull/724) ([vincentlepot](https://github.com/vincentlepot))
- Add basic compatibility with marathon-lb [\#720](https://github.com/containous/traefik/pull/720) ([guilhem](https://github.com/guilhem))
- Add Ed's video at ContainerCamp [\#717](https://github.com/containous/traefik/pull/717) ([emilevauge](https://github.com/emilevauge))
- Add documentation for Træfik on docker swarm mode [\#715](https://github.com/containous/traefik/pull/715) ([vdemeester](https://github.com/vdemeester))
- Remove duplicated link to Kubernetes.io in README.md [\#713](https://github.com/containous/traefik/pull/713) ([oscerd](https://github.com/oscerd))
- Show current version in web UI [\#709](https://github.com/containous/traefik/pull/709) ([vhf](https://github.com/vhf))
- Add support for docker healthcheck 👼 [\#708](https://github.com/containous/traefik/pull/708) ([vdemeester](https://github.com/vdemeester))
- Fix syntax in Swarm example. Resolves \#528 [\#707](https://github.com/containous/traefik/pull/707) ([billglover](https://github.com/billglover))

## [v1.1.0-rc1](https://github.com/containous/traefik/tree/v1.1.0-rc1) (2016-09-30)
[Full Changelog](https://github.com/containous/traefik/compare/v1.0.0...v1.1.0-rc1)

**Implemented enhancements:**

- Feature Request: SSL Cipher Selection [\#535](https://github.com/containous/traefik/issues/535)
- Error with -consulcatalog and missing load balance method on 1.0.0 [\#524](https://github.com/containous/traefik/issues/524)
- Running Traefik with Docker 1.12 Swarm Mode [\#504](https://github.com/containous/traefik/issues/504)
- Kubernetes provider: should allow the master url to be override [\#501](https://github.com/containous/traefik/issues/501)
- \[FRONTEND\]\[LE\] Pre-generate SSL certificates for "Host:" rules [\#483](https://github.com/containous/traefik/issues/483)
- Frontend Rule evolution [\#437](https://github.com/containous/traefik/issues/437)
- Add a Changelog [\#388](https://github.com/containous/traefik/issues/388)
- Add label matching for kubernetes ingests [\#363](https://github.com/containous/traefik/issues/363)
- Acme in HA Traefik Scenario [\#348](https://github.com/containous/traefik/issues/348)
- HTTP Basic Auth support [\#77](https://github.com/containous/traefik/issues/77)
- Session affinity / stickiness / persistence [\#5](https://github.com/containous/traefik/issues/5)
- Kubernetes provider: traefik.frontend.rule.type logging [\#668](https://github.com/containous/traefik/pull/668) ([yvespp](https://github.com/yvespp))

**Fixed bugs:**

- traefik hangs - stops handling requests [\#662](https://github.com/containous/traefik/issues/662)
- Add long jobs in exponential backoff providers  [\#626](https://github.com/containous/traefik/issues/626)
- Tip of tree crashes on invalid pointer on Marathon provider [\#624](https://github.com/containous/traefik/issues/624)
- ACME: revoke certificate on agreement update [\#579](https://github.com/containous/traefik/issues/579)
- WebUI: Providers tabs disappeared [\#577](https://github.com/containous/traefik/issues/577)
- traefik version command contains incorrect information when building from master branch [\#569](https://github.com/containous/traefik/issues/569)
- Flag --etcd.endpoint default [\#508](https://github.com/containous/traefik/issues/508)
- Conditional ACME on demand generation [\#505](https://github.com/containous/traefik/issues/505)
- Important delay with streams \(Mozilla EventSource\) [\#503](https://github.com/containous/traefik/issues/503)
- Traefik crashing [\#458](https://github.com/containous/traefik/issues/458)
- traefik.toml constraints error: `Expected map but found 'string'.` [\#451](https://github.com/containous/traefik/issues/451)
- Multiple path separators in the url path causing redirect [\#167](https://github.com/containous/traefik/issues/167)

**Closed issues:**

- Global InsecureSkipVerify does not work [\#700](https://github.com/containous/traefik/issues/700)
- \[documentation/feature\] Consul/etcd support atomic multiple key changes now [\#698](https://github.com/containous/traefik/issues/698)
- How to configure which network to use when starting traefik binary? [\#694](https://github.com/containous/traefik/issues/694)
- How to get multiple host headers working for docker labels? [\#692](https://github.com/containous/traefik/issues/692)
- Requests with URL-encoded characters are not forwarded correctly [\#684](https://github.com/containous/traefik/issues/684)
- Issue with global InsecureSkipVerify = true and self signed certificates [\#667](https://github.com/containous/traefik/issues/667)
- Docker exposedbydefault = false didn't work [\#663](https://github.com/containous/traefik/issues/663)
- \[ACME\] Auto SAN Detection [\#655](https://github.com/containous/traefik/issues/655)
- Fronting a domain with DNS A-record round-robin & ACME [\#654](https://github.com/containous/traefik/issues/654)
- Overriding toml configuration with environment variables [\#650](https://github.com/containous/traefik/issues/650)
- marathon provider exposedByDefault = false [\#647](https://github.com/containous/traefik/issues/647)
- Add status URL for service up checks [\#642](https://github.com/containous/traefik/issues/642)
- acme's storage file, containing private key, is word readable [\#638](https://github.com/containous/traefik/issues/638)
- wildcard domain with exclusions [\#633](https://github.com/containous/traefik/issues/633)
- Enable evenly distribution among backend [\#631](https://github.com/containous/traefik/issues/631)
- Traefik sporadically failing when proxying requests [\#615](https://github.com/containous/traefik/issues/615)
- TCP Proxy [\#608](https://github.com/containous/traefik/issues/608)
- How to use in Windows? [\#605](https://github.com/containous/traefik/issues/605)
- `ClientCAFiles` ignored [\#604](https://github.com/containous/traefik/issues/604)
- Let`s Encrypt enable in etcd [\#600](https://github.com/containous/traefik/issues/600)
- Support HTTP Basic Auth [\#599](https://github.com/containous/traefik/issues/599)
- Consul KV seem broken [\#587](https://github.com/containous/traefik/issues/587)
- HTTPS entryPoint not working [\#574](https://github.com/containous/traefik/issues/574)
- Traefik stuck when used as frontend for a streaming API [\#560](https://github.com/containous/traefik/issues/560)
- Exclude some frontends in consul catalog [\#555](https://github.com/containous/traefik/issues/555)
- Can I use Traefik without a domain name? [\#539](https://github.com/containous/traefik/issues/539)
- Priortities in 1.0.0 not behaving [\#506](https://github.com/containous/traefik/issues/506)
- Route by path [\#500](https://github.com/containous/traefik/issues/500)
- Container IP Lost [\#375](https://github.com/containous/traefik/issues/375)

**Merged pull requests:**

- Add HTTP compression [\#702](https://github.com/containous/traefik/pull/702) ([tuier](https://github.com/tuier))
- Carry PR 446 - Add sticky session support \(round two!\) [\#701](https://github.com/containous/traefik/pull/701) ([emilevauge](https://github.com/emilevauge))
- Remove unused endpoint when using constraints with Marathon provider [\#697](https://github.com/containous/traefik/pull/697) ([tuier](https://github.com/tuier))
- Replace imagelayers.io with microbadger [\#696](https://github.com/containous/traefik/pull/696) ([solidnerd](https://github.com/solidnerd))
- Selectable TLS Versions [\#690](https://github.com/containous/traefik/pull/690) ([dtomcej](https://github.com/dtomcej))
- Carry pr 439 [\#689](https://github.com/containous/traefik/pull/689) ([emilevauge](https://github.com/emilevauge))
- Disable gorilla/mux URL cleaning to prevent sending redirect [\#688](https://github.com/containous/traefik/pull/688) ([ydubreuil](https://github.com/ydubreuil))
- Some fixes [\#687](https://github.com/containous/traefik/pull/687) ([emilevauge](https://github.com/emilevauge))
- feat\(constraints\): Supports constraints for Marathon provider [\#686](https://github.com/containous/traefik/pull/686) ([tuier](https://github.com/tuier))
- Update docs to improve contribution setup [\#685](https://github.com/containous/traefik/pull/685) ([dtomcej](https://github.com/dtomcej))
- Add basic auth support for web backend [\#677](https://github.com/containous/traefik/pull/677) ([SantoDE](https://github.com/SantoDE))
- Document accepted values for logLevel. [\#676](https://github.com/containous/traefik/pull/676) ([jimmycuadra](https://github.com/jimmycuadra))
- If Marathon doesn't have healthcheck, assume it's ok [\#665](https://github.com/containous/traefik/pull/665) ([gomes](https://github.com/gomes))
- ACME: renew certificates 30 days before expiry [\#660](https://github.com/containous/traefik/pull/660) ([JayH5](https://github.com/JayH5))
- Update broken link and add a comment to sample config file  [\#658](https://github.com/containous/traefik/pull/658) ([Yggdrasil](https://github.com/Yggdrasil))
- Add possibility to use BindPort IPAddress 👼 [\#657](https://github.com/containous/traefik/pull/657) ([vdemeester](https://github.com/vdemeester))
- Update marathon [\#648](https://github.com/containous/traefik/pull/648) ([emilevauge](https://github.com/emilevauge))
- Add backend features to docker [\#646](https://github.com/containous/traefik/pull/646) ([jangie](https://github.com/jangie))
- enable consul catalog to use maxconn [\#645](https://github.com/containous/traefik/pull/645) ([jangie](https://github.com/jangie))
- Adopt the Code Of Coduct from http://contributor-covenant.org [\#641](https://github.com/containous/traefik/pull/641) ([errm](https://github.com/errm))
- Use secure mode 600 instead of 644 for acme.json [\#639](https://github.com/containous/traefik/pull/639) ([discordianfish](https://github.com/discordianfish))
- docker clarification, fix dead urls, misc typos [\#637](https://github.com/containous/traefik/pull/637) ([djalal](https://github.com/djalal))
- add PING handler to dashboard API [\#630](https://github.com/containous/traefik/pull/630) ([jangie](https://github.com/jangie))
- Migrate to JobBackOff [\#628](https://github.com/containous/traefik/pull/628) ([emilevauge](https://github.com/emilevauge))
- Add long job exponential backoff [\#627](https://github.com/containous/traefik/pull/627) ([emilevauge](https://github.com/emilevauge))
- HA acme support [\#625](https://github.com/containous/traefik/pull/625) ([emilevauge](https://github.com/emilevauge))
- Bump go v1.7 [\#620](https://github.com/containous/traefik/pull/620) ([emilevauge](https://github.com/emilevauge))
- Make duration logging consistent [\#619](https://github.com/containous/traefik/pull/619) ([jangie](https://github.com/jangie))
- fix for nil clientTLS causing issue [\#617](https://github.com/containous/traefik/pull/617) ([jangie](https://github.com/jangie))
- Add ability for marathon provider to set maxconn values, loadbalancer algorithm, and circuit breaker expression [\#616](https://github.com/containous/traefik/pull/616) ([jangie](https://github.com/jangie))
- Make systemd unit installable [\#613](https://github.com/containous/traefik/pull/613) ([keis](https://github.com/keis))
- Merge v1.0.2 master [\#610](https://github.com/containous/traefik/pull/610) ([emilevauge](https://github.com/emilevauge))
- update staert and flaeg [\#609](https://github.com/containous/traefik/pull/609) ([cocap10](https://github.com/cocap10))
- \#504 Initial support for Docker 1.12 Swarm Mode [\#602](https://github.com/containous/traefik/pull/602) ([diegofernandes](https://github.com/diegofernandes))
- Add Host cert ACME generation [\#601](https://github.com/containous/traefik/pull/601) ([emilevauge](https://github.com/emilevauge))
- Fixed binary script so traefik version command doesn't just print default values [\#598](https://github.com/containous/traefik/pull/598) ([keiths-osc](https://github.com/keiths-osc))
- Name servers after thier pods [\#596](https://github.com/containous/traefik/pull/596) ([errm](https://github.com/errm))
- Fix Consul prefix [\#589](https://github.com/containous/traefik/pull/589) ([jippi](https://github.com/jippi))
- Prioritize kubernetes routes by path length [\#588](https://github.com/containous/traefik/pull/588) ([philk](https://github.com/philk))
- beautify help [\#580](https://github.com/containous/traefik/pull/580) ([cocap10](https://github.com/cocap10))
- Upgrade directives name since we use angular-ui-bootstrap [\#578](https://github.com/containous/traefik/pull/578) ([micaelmbagira](https://github.com/micaelmbagira))
- Fix basic docs for configuration of multiple rules [\#576](https://github.com/containous/traefik/pull/576) ([ajaegle](https://github.com/ajaegle))
- Fix k8s watch [\#573](https://github.com/containous/traefik/pull/573) ([errm](https://github.com/errm))
- Add requirements.txt for netlify [\#567](https://github.com/containous/traefik/pull/567) ([emilevauge](https://github.com/emilevauge))
- Merge v1.0.1 master [\#565](https://github.com/containous/traefik/pull/565) ([emilevauge](https://github.com/emilevauge))
-  Move webui to FountainJS with Webpack [\#558](https://github.com/containous/traefik/pull/558) ([micaelmbagira](https://github.com/micaelmbagira))
- Add global InsecureSkipVerify option to disable certificate checking [\#557](https://github.com/containous/traefik/pull/557) ([stuart-c](https://github.com/stuart-c))
- Move version.go in its own package… [\#553](https://github.com/containous/traefik/pull/553) ([vdemeester](https://github.com/vdemeester))
- Upgrade libkermit and dependencies [\#552](https://github.com/containous/traefik/pull/552) ([vdemeester](https://github.com/vdemeester))
- Add command storeconfig [\#551](https://github.com/containous/traefik/pull/551) ([cocap10](https://github.com/cocap10))
- Add basic/digest auth [\#547](https://github.com/containous/traefik/pull/547) ([emilevauge](https://github.com/emilevauge))
- Bump node to 6 for webui [\#546](https://github.com/containous/traefik/pull/546) ([vdemeester](https://github.com/vdemeester))
- Bump golang to 1.6.3 [\#545](https://github.com/containous/traefik/pull/545) ([vdemeester](https://github.com/vdemeester))
- Fix typos [\#538](https://github.com/containous/traefik/pull/538) ([jimt](https://github.com/jimt))
- Kubernetes user-guide [\#519](https://github.com/containous/traefik/pull/519) ([errm](https://github.com/errm))
- Implement Kubernetes Selectors, minor kube endpoint fix [\#516](https://github.com/containous/traefik/pull/516) ([pnegahdar](https://github.com/pnegahdar))
- Carry \#358 : Option to disable expose of all docker containers [\#514](https://github.com/containous/traefik/pull/514) ([vdemeester](https://github.com/vdemeester))
- Remove traefik.frontend.value support in docker… [\#510](https://github.com/containous/traefik/pull/510) ([vdemeester](https://github.com/vdemeester))
- Use KvStores as global config sources [\#481](https://github.com/containous/traefik/pull/481) ([cocap10](https://github.com/cocap10))
- Add endpoint option to authenticate by client tls cert. [\#461](https://github.com/containous/traefik/pull/461) ([andersbetner](https://github.com/andersbetner))
- add mesos provider inspired by mesos-dns & marathon provider [\#353](https://github.com/containous/traefik/pull/353) ([skydjol](https://github.com/skydjol))

## [v1.0.2](https://github.com/containous/traefik/tree/v1.0.2) (2016-08-02)
[Full Changelog](https://github.com/containous/traefik/compare/v1.0.1...v1.0.2)

**Fixed bugs:**

- ACME: revoke certificate on agreement update [\#579](https://github.com/containous/traefik/issues/579)

**Closed issues:**

- Exclude some frontends in consul catalog [\#555](https://github.com/containous/traefik/issues/555)

**Merged pull requests:**

- Bump oxy version, fix streaming [\#584](https://github.com/containous/traefik/pull/584) ([emilevauge](https://github.com/emilevauge))
- Fix ACME TOS [\#582](https://github.com/containous/traefik/pull/582) ([emilevauge](https://github.com/emilevauge))

## [v1.0.1](https://github.com/containous/traefik/tree/v1.0.1) (2016-07-19)
[Full Changelog](https://github.com/containous/traefik/compare/v1.0.0...v1.0.1)

**Implemented enhancements:**

- Error with -consulcatalog and missing load balance method on 1.0.0 [\#524](https://github.com/containous/traefik/issues/524)
- Kubernetes provider: should allow the master url to be override [\#501](https://github.com/containous/traefik/issues/501)

**Fixed bugs:**

- Flag --etcd.endpoint default [\#508](https://github.com/containous/traefik/issues/508)
- Conditional ACME on demand generation [\#505](https://github.com/containous/traefik/issues/505)
- Important delay with streams \(Mozilla EventSource\) [\#503](https://github.com/containous/traefik/issues/503)

**Closed issues:**

- Can I use Traefik without a domain name? [\#539](https://github.com/containous/traefik/issues/539)
- Priortities in 1.0.0 not behaving [\#506](https://github.com/containous/traefik/issues/506)
- Route by path [\#500](https://github.com/containous/traefik/issues/500)

**Merged pull requests:**

- Update server.go [\#531](https://github.com/containous/traefik/pull/531) ([Jsewill](https://github.com/Jsewill))
- Add sse support [\#527](https://github.com/containous/traefik/pull/527) ([emilevauge](https://github.com/emilevauge))
- Fix acme checkOnDemandDomain [\#512](https://github.com/containous/traefik/pull/512) ([emilevauge](https://github.com/emilevauge))
- Fix default etcd port [\#511](https://github.com/containous/traefik/pull/511) ([errm](https://github.com/errm))

## [v1.0.0](https://github.com/containous/traefik/tree/v1.0.0) (2016-07-05)
[Full Changelog](https://github.com/containous/traefik/compare/v1.0.0-rc3...v1.0.0)

**Fixed bugs:**

- Enable to define empty TLS option by flag for Let's Encrypt [\#488](https://github.com/containous/traefik/issues/488)
- \[Docker\] No IP in backend in host networking mode [\#487](https://github.com/containous/traefik/issues/487)
- Response is compressed when not requested [\#485](https://github.com/containous/traefik/issues/485)
- loadConfig modifies configuration causing same config check to fail [\#480](https://github.com/containous/traefik/issues/480)

**Closed issues:**

- svg logo [\#482](https://github.com/containous/traefik/issues/482)
- etcd tries to connect with TLS even with --etcd.tls=false [\#456](https://github.com/containous/traefik/issues/456)
- Zookeeper - KV connection error: Failed to test KV store connection [\#455](https://github.com/containous/traefik/issues/455)
- "Not Found" api response needed instead of 404  [\#454](https://github.com/containous/traefik/issues/454)
- domain label doesn't work on docker [\#447](https://github.com/containous/traefik/issues/447)
- Any chance of a windows release? [\#425](https://github.com/containous/traefik/issues/425)

**Merged pull requests:**

- Fix windows builds [\#495](https://github.com/containous/traefik/pull/495) ([emilevauge](https://github.com/emilevauge))
- Fix host Docker network [\#494](https://github.com/containous/traefik/pull/494) ([emilevauge](https://github.com/emilevauge))
- Fix empty tls flag [\#493](https://github.com/containous/traefik/pull/493) ([emilevauge](https://github.com/emilevauge))
- Fix webui proxying [\#492](https://github.com/containous/traefik/pull/492) ([emilevauge](https://github.com/emilevauge))
- Fix default weight in server.LoadConfig [\#491](https://github.com/containous/traefik/pull/491) ([emilevauge](https://github.com/emilevauge))
- Fix retry headers, simplify ResponseRecorder [\#490](https://github.com/containous/traefik/pull/490) ([emilevauge](https://github.com/emilevauge))

## [v1.0.0-rc3](https://github.com/containous/traefik/tree/v1.0.0-rc3) (2016-06-23)
[Full Changelog](https://github.com/containous/traefik/compare/v1.0.0-rc2...v1.0.0-rc3)

**Implemented enhancements:**

- support more than one rule to Docker backend [\#419](https://github.com/containous/traefik/issues/419)

**Fixed bugs:**

- consulCatalog issue when serviceName contains a dot [\#475](https://github.com/containous/traefik/issues/475)
- Issue with empty responses [\#463](https://github.com/containous/traefik/issues/463)
- Severe memory leak in beta.470 and beyond crashes Traefik server  [\#462](https://github.com/containous/traefik/issues/462)
- Marathon that starts with a space causes parsing errors. [\#459](https://github.com/containous/traefik/issues/459)
- A frontend route without a rule \(or empty rule\) causes a crash when traefik starts [\#453](https://github.com/containous/traefik/issues/453)
- container dropped out when connecting to Docker Swarm [\#442](https://github.com/containous/traefik/issues/442)
- Traefik setting Accept-Encoding: gzip on requests \(Traefik may also be broken with chunked responses\) [\#421](https://github.com/containous/traefik/issues/421)

**Closed issues:**

- HTTP headers case gets modified [\#466](https://github.com/containous/traefik/issues/466)
- File frontend \> Marathon Backend [\#465](https://github.com/containous/traefik/issues/465)
- Websocket: Unable to hijack the connection [\#452](https://github.com/containous/traefik/issues/452)
- kubernetes: Received event spamming? [\#449](https://github.com/containous/traefik/issues/449)
- kubernetes: backends not updated when i scale replication controller? [\#448](https://github.com/containous/traefik/issues/448)
- Add href link on frontend [\#436](https://github.com/containous/traefik/issues/436)
- Multiple Domains Rule [\#430](https://github.com/containous/traefik/issues/430)

**Merged pull requests:**

- Disable constraints in doc until 1.1 [\#479](https://github.com/containous/traefik/pull/479) ([emilevauge](https://github.com/emilevauge))
- Sort nodes before creating consul catalog config [\#478](https://github.com/containous/traefik/pull/478) ([keis](https://github.com/keis))
- Fix spamming events in listenProviders [\#477](https://github.com/containous/traefik/pull/477) ([emilevauge](https://github.com/emilevauge))
- Fix empty responses [\#476](https://github.com/containous/traefik/pull/476) ([emilevauge](https://github.com/emilevauge))
- Fix acme renew [\#472](https://github.com/containous/traefik/pull/472) ([emilevauge](https://github.com/emilevauge))
- Fix typo in error message. [\#471](https://github.com/containous/traefik/pull/471) ([KevinBusse](https://github.com/KevinBusse))
- Fix errors load config [\#470](https://github.com/containous/traefik/pull/470) ([emilevauge](https://github.com/emilevauge))
- Typo: Replace French words by English ones [\#469](https://github.com/containous/traefik/pull/469) ([kumy](https://github.com/kumy))
- Fix marathon TLS/basic auth [\#468](https://github.com/containous/traefik/pull/468) ([emilevauge](https://github.com/emilevauge))
- Fix memory leak in listenProviders [\#464](https://github.com/containous/traefik/pull/464) ([emilevauge](https://github.com/emilevauge))
- Fix websocket connection Hijack [\#460](https://github.com/containous/traefik/pull/460) ([emilevauge](https://github.com/emilevauge))
- Fix default KV configuration [\#450](https://github.com/containous/traefik/pull/450) ([emilevauge](https://github.com/emilevauge))
- Fix panic if listContainers fails… [\#443](https://github.com/containous/traefik/pull/443) ([vdemeester](https://github.com/vdemeester))
- mount acme folder instead of file [\#441](https://github.com/containous/traefik/pull/441) ([NicolasGeraud](https://github.com/NicolasGeraud))
- feat\(constraints\): Supports constraints for docker backend [\#438](https://github.com/containous/traefik/pull/438) ([samber](https://github.com/samber))

## [v1.0.0-rc2](https://github.com/containous/traefik/tree/v1.0.0-rc2) (2016-06-07)
[Full Changelog](https://github.com/containous/traefik/compare/v1.0.0-rc1...v1.0.0-rc2)

**Implemented enhancements:**

- Add @samber to maintainers [\#440](https://github.com/containous/traefik/pull/440) ([emilevauge](https://github.com/emilevauge))

**Fixed bugs:**

- Panic on help [\#429](https://github.com/containous/traefik/issues/429)
- Bad default values in configuration [\#427](https://github.com/containous/traefik/issues/427)

**Closed issues:**

- Traefik doesn't listen on IPv4 ports [\#434](https://github.com/containous/traefik/issues/434)
- Not listening on port 80 [\#432](https://github.com/containous/traefik/issues/432)
- docs need updating for new frontend rules format [\#423](https://github.com/containous/traefik/issues/423)
- Does traefik supports for Mac? \(For devlelopment\)  [\#417](https://github.com/containous/traefik/issues/417)

**Merged pull requests:**

- Allow multiple rules [\#435](https://github.com/containous/traefik/pull/435) ([fclaeys](https://github.com/fclaeys))
- Add routes priorities [\#433](https://github.com/containous/traefik/pull/433) ([emilevauge](https://github.com/emilevauge))
- Fix default configuration [\#428](https://github.com/containous/traefik/pull/428) ([emilevauge](https://github.com/emilevauge))
- Fix marathon groups subdomain [\#426](https://github.com/containous/traefik/pull/426) ([emilevauge](https://github.com/emilevauge))
- Fix travis tag check [\#422](https://github.com/containous/traefik/pull/422) ([emilevauge](https://github.com/emilevauge))
- log info about TOML configuration file using [\#420](https://github.com/containous/traefik/pull/420) ([cocap10](https://github.com/cocap10))
- Doc about skipping some integration tests with '-check.f ConsulCatalogSuite' [\#418](https://github.com/containous/traefik/pull/418) ([samber](https://github.com/samber))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*