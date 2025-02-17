# Changelog

## [**Next release**](https://github.com/netdata/netdata/tree/HEAD)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.17.1...HEAD)

**Merged pull requests:**

- Increase dbengine default cache size [\#6997](https://github.com/netdata/netdata/pull/6997) ([mfundul](https://github.com/mfundul))
- Remove warning from Coverity [\#6992](https://github.com/netdata/netdata/pull/6992) ([thiagoftsm](https://github.com/thiagoftsm))
- Fixing broken links found via linkchecker [\#6983](https://github.com/netdata/netdata/pull/6983) ([joelhans](https://github.com/joelhans))
- Fix dbengine consistency [\#6979](https://github.com/netdata/netdata/pull/6979) ([mfundul](https://github.com/mfundul))
- Make dbengine the default memory mode [\#6977](https://github.com/netdata/netdata/pull/6977) ([mfundul](https://github.com/mfundul))
- rabbitmq: collect vhosts msg metrics from `/api/vhosts` [\#6976](https://github.com/netdata/netdata/pull/6976) ([ilyam8](https://github.com/ilyam8))
- Fix coverity erro \(CID 349552\) double lock [\#6970](https://github.com/netdata/netdata/pull/6970) ([thiagoftsm](https://github.com/thiagoftsm))
- web api: include family into allmetrics json response [\#6966](https://github.com/netdata/netdata/pull/6966) ([ilyam8](https://github.com/ilyam8))
- elasticsearch: collect metrics from \_cat/indices [\#6965](https://github.com/netdata/netdata/pull/6965) ([ilyam8](https://github.com/ilyam8))
- Reduce overhead during write io [\#6964](https://github.com/netdata/netdata/pull/6964) ([mfundul](https://github.com/mfundul))
- mysql: collect galera cluster metrics [\#6962](https://github.com/netdata/netdata/pull/6962) ([ilyam8](https://github.com/ilyam8))
- Clarification on configuring notification recipients [\#6961](https://github.com/netdata/netdata/pull/6961) ([cakrit](https://github.com/cakrit))
- netdata/packaging: Make spec file more consistent with version dependencies, plus some documentation nits [\#6948](https://github.com/netdata/netdata/pull/6948) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Fix a memory leak [\#6945](https://github.com/netdata/netdata/pull/6945) ([vlvkobal](https://github.com/vlvkobal))
- Fix Remark Lint for READMEs in Database [\#6942](https://github.com/netdata/netdata/pull/6942) ([prhomhyse](https://github.com/prhomhyse))
- Coverity 20190924 [\#6941](https://github.com/netdata/netdata/pull/6941) ([thiagoftsm](https://github.com/thiagoftsm))
- Restore original alignment behaviour of RRDR [\#6938](https://github.com/netdata/netdata/pull/6938) ([mfundul](https://github.com/mfundul))
- minor - check for curl to not get wrong error message [\#6931](https://github.com/netdata/netdata/pull/6931) ([underhood](https://github.com/underhood))
- netdata/packaging: fix broken links on web files, for deb [\#6930](https://github.com/netdata/netdata/pull/6930) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- installer: include go.d.plugin version v0.10.0 [\#6929](https://github.com/netdata/netdata/pull/6929) ([ilyam8](https://github.com/ilyam8))
- python.d: fix log warnings in start\_job [\#6928](https://github.com/netdata/netdata/pull/6928) ([ilyam8](https://github.com/ilyam8))
- zookeeper and hdfs: alarms and dashboard\_info [\#6927](https://github.com/netdata/netdata/pull/6927) ([ilyam8](https://github.com/ilyam8))
- netdata.spec.in: Do not build CUPS plugin subpackage on CentOS 6 and CentOS 7 [\#6926](https://github.com/netdata/netdata/pull/6926) ([knatsakis](https://github.com/knatsakis))
- Fix remark lint for Contrib  [\#6921](https://github.com/netdata/netdata/pull/6921) ([prhomhyse](https://github.com/prhomhyse))
- Fix remark warnings for Daemon README [\#6920](https://github.com/netdata/netdata/pull/6920) ([prhomhyse](https://github.com/prhomhyse))
- Fix Remark Lint Warnings for Backends [\#6917](https://github.com/netdata/netdata/pull/6917) ([prhomhyse](https://github.com/prhomhyse))
- Suggest using /run or /var/run for the unix socket [\#6916](https://github.com/netdata/netdata/pull/6916) ([cakrit](https://github.com/cakrit))
- Improve documentation for the SNMP collector [\#6915](https://github.com/netdata/netdata/pull/6915) ([cakrit](https://github.com/cakrit))
- netdata/ci: nits and fixes around package release workflow [\#6914](https://github.com/netdata/netdata/pull/6914) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Detect deadlock in dbengine page cache [\#6911](https://github.com/netdata/netdata/pull/6911) ([mfundul](https://github.com/mfundul))
- Correct read length of silencers file [\#6909](https://github.com/netdata/netdata/pull/6909) ([cakrit](https://github.com/cakrit))
- netdata/ci: fix branch check [\#6905](https://github.com/netdata/netdata/pull/6905) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- \#3925 implementation [\#6903](https://github.com/netdata/netdata/pull/6903) ([underhood](https://github.com/underhood))
- netdata/packaging: remove rhel7 - i386, until its settled from bug \#6849 [\#6902](https://github.com/netdata/netdata/pull/6902) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Improve changelog generation and add it back to the pipeline [\#6900](https://github.com/netdata/netdata/pull/6900) ([cakrit](https://github.com/cakrit))
- \[collector/slabinfo\] Fix pagesize not defined in non-x86 arches [\#6897](https://github.com/netdata/netdata/pull/6897) ([Saruspete](https://github.com/Saruspete))
- Permit x-auth-token in Access-Control-Allow-Headers [\#6894](https://github.com/netdata/netdata/pull/6894) ([cakrit](https://github.com/cakrit))
- netdata/packaging: fix kickstart-static64 argument parsing [\#6892](https://github.com/netdata/netdata/pull/6892) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Change the log level for chart updates [\#6887](https://github.com/netdata/netdata/pull/6887) ([vlvkobal](https://github.com/vlvkobal))
- Resolve all Kubernetes container names [\#6885](https://github.com/netdata/netdata/pull/6885) ([cakrit](https://github.com/cakrit))
- Update docs for offline install [\#6884](https://github.com/netdata/netdata/pull/6884) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Remove Dollar sign from Bash code in documentation and fix remark-lint warnings [\#6880](https://github.com/netdata/netdata/pull/6880) ([prhomhyse](https://github.com/prhomhyse))
- Markdown syntax fixes for MDX parser [\#6877](https://github.com/netdata/netdata/pull/6877) ([joelhans](https://github.com/joelhans))
- fix LGTM warnings [\#6875](https://github.com/netdata/netdata/pull/6875) ([jacekkolasa](https://github.com/jacekkolasa))
- Update python.d module checklist to match the current paths and build system. [\#6874](https://github.com/netdata/netdata/pull/6874) ([Ferroin](https://github.com/Ferroin))
- installer: include go.d.plugin version v0.9.0 [\#6872](https://github.com/netdata/netdata/pull/6872) ([ilyam8](https://github.com/ilyam8))
- Instructions for simple SMTP transport [\#6870](https://github.com/netdata/netdata/pull/6870) ([cakrit](https://github.com/cakrit))
- Add example for prometheus archiving source parameter [\#6869](https://github.com/netdata/netdata/pull/6869) ([cakrit](https://github.com/cakrit))
- dont redirect when redirectURI is the same [\#6868](https://github.com/netdata/netdata/pull/6868) ([jacekkolasa](https://github.com/jacekkolasa))
- /var/lib/netdata/registry was being left behind after purge [\#6867](https://github.com/netdata/netdata/pull/6867) ([davent](https://github.com/davent))
- python.d.plugin: no job config build fix [\#6856](https://github.com/netdata/netdata/pull/6856) ([ilyam8](https://github.com/ilyam8))
- Resolve broken links in The standard web dashboard doc [\#6854](https://github.com/netdata/netdata/pull/6854) ([prhomhyse](https://github.com/prhomhyse))
- netdata/packaging: Bring on board two scripts that build libuv and judy from source [\#6850](https://github.com/netdata/netdata/pull/6850) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: nits and fixes for packaging [\#6842](https://github.com/netdata/netdata/pull/6842) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: nit - missed trailing slash [\#6840](https://github.com/netdata/netdata/pull/6840) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: Ensure that we do not mess with CI tooling, when building stable [\#6838](https://github.com/netdata/netdata/pull/6838) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: we didnt fix changelog handling, fixes and nits now [\#6837](https://github.com/netdata/netdata/pull/6837) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Add news of 1.17.1 to README [\#6836](https://github.com/netdata/netdata/pull/6836) ([cakrit](https://github.com/cakrit))
- netdata/packaging: no need to overengineer with these checks [\#6834](https://github.com/netdata/netdata/pull/6834) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Buffer overflow [\#6817](https://github.com/netdata/netdata/pull/6817) ([amoss](https://github.com/amoss))
- Docs: Overhaul of Getting started guide [\#6811](https://github.com/netdata/netdata/pull/6811) ([joelhans](https://github.com/joelhans))
- NPM Packages version update [\#6801](https://github.com/netdata/netdata/pull/6801) ([prhomhyse](https://github.com/prhomhyse))
- Collector slabinfo [\#6800](https://github.com/netdata/netdata/pull/6800) ([Saruspete](https://github.com/Saruspete))
- Fix some errors reported by Coverity [\#6797](https://github.com/netdata/netdata/pull/6797) ([thiagoftsm](https://github.com/thiagoftsm))
- Allow hostnames in Access Control Lists [\#6796](https://github.com/netdata/netdata/pull/6796) ([amoss](https://github.com/amoss))
- update grep to be more specific [\#6794](https://github.com/netdata/netdata/pull/6794) ([n0coast](https://github.com/n0coast))
- Common pattern for web and alarms together with two bug fixes [\#6783](https://github.com/netdata/netdata/pull/6783) ([thiagoftsm](https://github.com/thiagoftsm))
- Changes to launching the python.d plugin aggregator. [\#6781](https://github.com/netdata/netdata/pull/6781) ([amoss](https://github.com/amoss))
- vcsa collector: charts descritpion and alarms [\#6772](https://github.com/netdata/netdata/pull/6772) ([ilyam8](https://github.com/ilyam8))
- netdata/packaging: Introduce separate CUPS package for debian distributions [\#6724](https://github.com/netdata/netdata/pull/6724) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: Split CUPS plugin to separate package \(RPM\) [\#6700](https://github.com/netdata/netdata/pull/6700) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/installer: Add support for offline installs using kickstart or kickstart-static64 [\#6693](https://github.com/netdata/netdata/pull/6693) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Add clang-format. Update Contribution guidelines. [\#6677](https://github.com/netdata/netdata/pull/6677) ([cosmix](https://github.com/cosmix))
- changed naming for redirect\_uri param [\#6663](https://github.com/netdata/netdata/pull/6663) ([jacekkolasa](https://github.com/jacekkolasa))
- Fixes netdata group deletion on linux for uninstall script [\#6645](https://github.com/netdata/netdata/pull/6645) ([mbarper](https://github.com/mbarper))
- Gearman plugin for Netdata [\#6567](https://github.com/netdata/netdata/pull/6567) ([agronick](https://github.com/agronick))
- Create a template for all dimensions [\#6560](https://github.com/netdata/netdata/pull/6560) ([thiagoftsm](https://github.com/thiagoftsm))
- Center the chart on timeframe when an alarm is raised [\#6391](https://github.com/netdata/netdata/pull/6391) ([thiagoftsm](https://github.com/thiagoftsm))
- Cppcheck fixes [\#6386](https://github.com/netdata/netdata/pull/6386) ([ac000](https://github.com/ac000))

## [v1.17.1](https://github.com/netdata/netdata/tree/v1.17.1) (2019-09-12)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.17.0...v1.17.1)

**Merged pull requests:**

- netdata/packaging: fix ubuntu/xenial runtime dependencies [\#6825](https://github.com/netdata/netdata/pull/6825) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/ci: Force last good version of git-semver, they broke it [\#6820](https://github.com/netdata/netdata/pull/6820) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Stress test insertions into dbengine and bugfixes [\#6814](https://github.com/netdata/netdata/pull/6814) ([mfundul](https://github.com/mfundul))
- netdata/ci: Fix author on triggering commits for packaging [\#6813](https://github.com/netdata/netdata/pull/6813) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: remove fedora/28, is no longer available [\#6808](https://github.com/netdata/netdata/pull/6808) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/ci: second batch of fixes for coverity scan script and others [\#6804](https://github.com/netdata/netdata/pull/6804) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: work around redhat complaining on build-id binary [\#6792](https://github.com/netdata/netdata/pull/6792) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: fix changelog generation failing the build [\#6778](https://github.com/netdata/netdata/pull/6778) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: override control file for debian/buster [\#6777](https://github.com/netdata/netdata/pull/6777) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- \(Documentation\) fix pfsense instructions and links [\#6768](https://github.com/netdata/netdata/pull/6768) ([Fohdeesha](https://github.com/Fohdeesha))
- netdata/packaging: Trigger stable package generation upon release process [\#6766](https://github.com/netdata/netdata/pull/6766) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- update cache hashes for js and css [\#6756](https://github.com/netdata/netdata/pull/6756) ([jacekkolasa](https://github.com/jacekkolasa))
- \[libnetdata/thread\] Set thread name from tag [\#6745](https://github.com/netdata/netdata/pull/6745) ([Saruspete](https://github.com/Saruspete))
- sidebar-info update - DB engine [\#6744](https://github.com/netdata/netdata/pull/6744) ([jacekkolasa](https://github.com/jacekkolasa))
- pythond respect prev running jobs and refactor [\#6661](https://github.com/netdata/netdata/pull/6661) ([ilyam8](https://github.com/ilyam8))
- Stop configure.ac from linking against dbengine and https libraries w… [\#6658](https://github.com/netdata/netdata/pull/6658) ([mfundul](https://github.com/mfundul))
- Add high level explanation of dashboard contents [\#6648](https://github.com/netdata/netdata/pull/6648) ([joelhans](https://github.com/joelhans))
- Fix clear notification missing [\#6638](https://github.com/netdata/netdata/pull/6638) ([thiagoftsm](https://github.com/thiagoftsm))
- dash.html [\#6603](https://github.com/netdata/netdata/pull/6603) ([tnyeanderson](https://github.com/tnyeanderson))
- HTTP response message [\#6595](https://github.com/netdata/netdata/pull/6595) ([thiagoftsm](https://github.com/thiagoftsm))

## [v1.17.0](https://github.com/netdata/netdata/tree/v1.17.0) (2019-09-03)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.16.1...v1.17.0)

**Merged pull requests:**

- Remove changelog generation from release, as it keeps breaking [\#6761](https://github.com/netdata/netdata/pull/6761) ([cakrit](https://github.com/cakrit))
- Skip issues from release changelog [\#6759](https://github.com/netdata/netdata/pull/6759) ([cakrit](https://github.com/cakrit))
- Increase minimum release for changelog [\#6758](https://github.com/netdata/netdata/pull/6758) ([cakrit](https://github.com/cakrit))
- netdata/packaging: Add python3-lxc dependency [\#6753](https://github.com/netdata/netdata/pull/6753) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- make coverity-scan.sh usable by hand [\#6747](https://github.com/netdata/netdata/pull/6747) ([ktsaou](https://github.com/ktsaou))
- netdata/packaging: fix coverity problem in travis \(2 issues\) [\#6743](https://github.com/netdata/netdata/pull/6743) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Add command-line option descriptions for apps.plugin [\#6738](https://github.com/netdata/netdata/pull/6738) ([vlvkobal](https://github.com/vlvkobal))
- netdata/packaging: Add purging logic for package cloud repositories [\#6732](https://github.com/netdata/netdata/pull/6732) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Fix corrupted transaction payload handling [\#6731](https://github.com/netdata/netdata/pull/6731) ([mfundul](https://github.com/mfundul))
- Netdata-installer warning removed [\#6715](https://github.com/netdata/netdata/pull/6715) ([thiagoftsm](https://github.com/thiagoftsm))
- Remove of unecessary NULL web server [\#6714](https://github.com/netdata/netdata/pull/6714) ([thiagoftsm](https://github.com/thiagoftsm))
- History tips [\#6711](https://github.com/netdata/netdata/pull/6711) ([jacekkolasa](https://github.com/jacekkolasa))
- netdata/installer: fix static64 installer always overwriting configuration [\#6710](https://github.com/netdata/netdata/pull/6710) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- exact path to netdata.conf in .gitignore [\#6709](https://github.com/netdata/netdata/pull/6709) ([sunflowerbofh](https://github.com/sunflowerbofh))
- Tabulatin on health/health.c [\#6691](https://github.com/netdata/netdata/pull/6691) ([thiagoftsm](https://github.com/thiagoftsm))
- netdata/packaging: Align libdir in all configure commands [\#6682](https://github.com/netdata/netdata/pull/6682) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- spigotmc module: :pencil2: fix typos. [\#6680](https://github.com/netdata/netdata/pull/6680) ([Cat7373](https://github.com/Cat7373))
- netdata/packaging: \[ci skip\] Correlate configure command [\#6678](https://github.com/netdata/netdata/pull/6678) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: Add auto-generation of packages for nightly [\#6675](https://github.com/netdata/netdata/pull/6675) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- .travis.yml: Improve template and commit\_message predicates readability [\#6673](https://github.com/netdata/netdata/pull/6673) ([knatsakis](https://github.com/knatsakis))
- .travis.yml: Build docker images in parallel [\#6672](https://github.com/netdata/netdata/pull/6672) ([knatsakis](https://github.com/knatsakis))
- add CHANGELOG.md to .remarkignore [\#6671](https://github.com/netdata/netdata/pull/6671) ([prhomhyse](https://github.com/prhomhyse))
- netdata/packaging: separately identify dependency resolution for HTTPS and DB engine [\#6670](https://github.com/netdata/netdata/pull/6670) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Bugfix 931843 1 [\#6667](https://github.com/netdata/netdata/pull/6667) ([sunflowerbofh](https://github.com/sunflowerbofh))
- Fix Markdown Lint warnings [\#6664](https://github.com/netdata/netdata/pull/6664) ([prhomhyse](https://github.com/prhomhyse))
- Remove texts inside tests/Makefile [\#6660](https://github.com/netdata/netdata/pull/6660) ([thiagoftsm](https://github.com/thiagoftsm))
- .travis.yml: packaging/docker/check\_login.sh can cause the build to fail [\#6655](https://github.com/netdata/netdata/pull/6655) ([knatsakis](https://github.com/knatsakis))
- Display uptime for processes [\#6654](https://github.com/netdata/netdata/pull/6654) ([vlvkobal](https://github.com/vlvkobal))
- Prometheus version update [\#6652](https://github.com/netdata/netdata/pull/6652) ([prhomhyse](https://github.com/prhomhyse))
- Accept \<\> around links in markdown [\#6646](https://github.com/netdata/netdata/pull/6646) ([cakrit](https://github.com/cakrit))
- netdata/installer: Fix error running kickstart as a non-privileged user [\#6642](https://github.com/netdata/netdata/pull/6642) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- fix spigotmc plugin bugs [\#6635](https://github.com/netdata/netdata/pull/6635) ([Cat7373](https://github.com/Cat7373))
- Fix 'None' in left nav [\#6632](https://github.com/netdata/netdata/pull/6632) ([joelhans](https://github.com/joelhans))
- Update terms of use for U.S. legal reasons [\#6631](https://github.com/netdata/netdata/pull/6631) ([cakrit](https://github.com/cakrit))
- Fix a segmentation fault in backends [\#6627](https://github.com/netdata/netdata/pull/6627) ([vlvkobal](https://github.com/vlvkobal))
- .travis.yml: Remove 'sudo: true' as it is now deprecated [\#6624](https://github.com/netdata/netdata/pull/6624) ([knatsakis](https://github.com/knatsakis))
-  Change "netdata" to "Netdata" in all docs [\#6621](https://github.com/netdata/netdata/pull/6621) ([joelhans](https://github.com/joelhans))
- netdata: Add cosmix as codeowner, wherever cakrit is [\#6618](https://github.com/netdata/netdata/pull/6618) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- mysql: do not remove `slave\_status` from queries in module [\#6617](https://github.com/netdata/netdata/pull/6617) ([ilyam8](https://github.com/ilyam8))
- Add alarm variables to the response of chart and data \(\#6054\) [\#6615](https://github.com/netdata/netdata/pull/6615) ([alpes214](https://github.com/alpes214))
- Better system OS detection for RHEL6 and Mac OS X [\#6612](https://github.com/netdata/netdata/pull/6612) ([dex4er](https://github.com/dex4er))
- update package version requirements for LZ4 and libuv [\#6607](https://github.com/netdata/netdata/pull/6607) ([mfundul](https://github.com/mfundul))
- netdata/installer: do not enable netdata, if it was previously disabled [\#6606](https://github.com/netdata/netdata/pull/6606) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Fix typos in: 'README.md' file. [\#6604](https://github.com/netdata/netdata/pull/6604) ([coffeina](https://github.com/coffeina))
- mysql collector: slave\_status charts per replication channel [\#6597](https://github.com/netdata/netdata/pull/6597) ([ilyam8](https://github.com/ilyam8))
- Install Netdata with Docker  [\#6596](https://github.com/netdata/netdata/pull/6596) ([prhomhyse](https://github.com/prhomhyse))
- netdata/packaging: Expect .tar.gz version of go.d plugin [\#6590](https://github.com/netdata/netdata/pull/6590) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Fix configure.ac allowing deprecated LZ4 library call [\#6589](https://github.com/netdata/netdata/pull/6589) ([mfundul](https://github.com/mfundul))
- Fix crash in malloc [\#6583](https://github.com/netdata/netdata/pull/6583) ([thiagoftsm](https://github.com/thiagoftsm))
- Build DEB and RPM packages in parallel [\#6579](https://github.com/netdata/netdata/pull/6579) ([knatsakis](https://github.com/knatsakis))
- Fixed typo 'follwing' -\> 'following' [\#6575](https://github.com/netdata/netdata/pull/6575) ([vvanouytsel](https://github.com/vvanouytsel))
- netdata/packaging: Bare OS validations [\#6574](https://github.com/netdata/netdata/pull/6574) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- vsphere collector: charts description and alarms [\#6572](https://github.com/netdata/netdata/pull/6572) ([ilyam8](https://github.com/ilyam8))
-  Documentation style guide & build instructions [\#6563](https://github.com/netdata/netdata/pull/6563) ([joelhans](https://github.com/joelhans))
- netdata/packaging: put go.d version in one place [\#6557](https://github.com/netdata/netdata/pull/6557) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Add alarm status counter api call [\#6554](https://github.com/netdata/netdata/pull/6554) ([alpes214](https://github.com/alpes214))
- netdata/packaging: Documentation on distribution support matrix and functionality availability [\#6552](https://github.com/netdata/netdata/pull/6552) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- mongodb: ssl connection [\#6546](https://github.com/netdata/netdata/pull/6546) ([ilyam8](https://github.com/ilyam8))
- Add MongoDB backend [\#6524](https://github.com/netdata/netdata/pull/6524) ([vlvkobal](https://github.com/vlvkobal))
- Netdata Cloud documentation [\#6476](https://github.com/netdata/netdata/pull/6476) ([joelhans](https://github.com/joelhans))
- Variable Granularity support for data collection [\#6430](https://github.com/netdata/netdata/pull/6430) ([mfundul](https://github.com/mfundul))
- \(re-open\) ZRAM info collector module \(proc.plugin\) [\#6424](https://github.com/netdata/netdata/pull/6424) ([RaZeR-RBI](https://github.com/RaZeR-RBI))

## [v1.16.1](https://github.com/netdata/netdata/tree/v1.16.1) (2019-07-31)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.16.0...v1.16.1)

**Merged pull requests:**

- Handle disconnected sockets in unbound collector. [\#6561](https://github.com/netdata/netdata/pull/6561) ([Ferroin](https://github.com/Ferroin))
- netdata/packaging: Notify us when CHANGELOG.md gets too old [\#6556](https://github.com/netdata/netdata/pull/6556) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging: Move tarball checksum information into lib dir of netdata [\#6555](https://github.com/netdata/netdata/pull/6555) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Add configurable default locations for trusted CA certificates [\#6549](https://github.com/netdata/netdata/pull/6549) ([thiagoftsm](https://github.com/thiagoftsm))
- smartd\_log: use `del\_dimension` instead of `hide\_dimension` to delete inactive disks [\#6547](https://github.com/netdata/netdata/pull/6547) ([ilyam8](https://github.com/ilyam8))
- redirect after clicking Nodes \> SignIn [\#6544](https://github.com/netdata/netdata/pull/6544) ([jacekkolasa](https://github.com/jacekkolasa))
- smartd\_log: Disk \_\_eq\_\_ fix [\#6540](https://github.com/netdata/netdata/pull/6540) ([ilyam8](https://github.com/ilyam8))
- minor - code readability HTTP CODES as defines && clear warnings [\#6539](https://github.com/netdata/netdata/pull/6539) ([underhood](https://github.com/underhood))
- \[ci skip\] minor/vanity - add self.name\(\) to contrib.md [\#6538](https://github.com/netdata/netdata/pull/6538) ([underhood](https://github.com/underhood))
- Docs: Remove text about nightly version [\#6534](https://github.com/netdata/netdata/pull/6534) ([joelhans](https://github.com/joelhans))
- Documentation navigation fix [\#6533](https://github.com/netdata/netdata/pull/6533) ([joelhans](https://github.com/joelhans))
- .travis.yml: Fix some yamllint errors [\#6526](https://github.com/netdata/netdata/pull/6526) ([knatsakis](https://github.com/knatsakis))
- netdata/packaging: Adopt netdata-updater to run properly for static64 installations. [\#6520](https://github.com/netdata/netdata/pull/6520) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- mongodb: change `password` to `pass` in the module config [\#6518](https://github.com/netdata/netdata/pull/6518) ([ilyam8](https://github.com/ilyam8))
- netdata/packaging: Do not deliver edit-config as part of the distribution tarball [\#6507](https://github.com/netdata/netdata/pull/6507) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Fixed broken left navbar links in translated docs [\#6505](https://github.com/netdata/netdata/pull/6505) ([cakrit](https://github.com/cakrit))
- Update CLA with intention to keep netdata FOSS [\#6504](https://github.com/netdata/netdata/pull/6504) ([cakrit](https://github.com/cakrit))
- netdata/docs: Add @joelhans as co-owner on documentation [\#6501](https://github.com/netdata/netdata/pull/6501) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Stop anonymous stats from writing log in /tmp [\#6491](https://github.com/netdata/netdata/pull/6491) ([cakrit](https://github.com/cakrit))
- Add support for plain text only emails [\#6485](https://github.com/netdata/netdata/pull/6485) ([leo-lb](https://github.com/leo-lb))
- netdata/packaging: Enable built-in support for prometheus remote write in packaging [\#6480](https://github.com/netdata/netdata/pull/6480) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Fix the snappy library check [\#6479](https://github.com/netdata/netdata/pull/6479) ([vlvkobal](https://github.com/vlvkobal))
- Add a statement about permissions for the diskspace plugin [\#6474](https://github.com/netdata/netdata/pull/6474) ([vlvkobal](https://github.com/vlvkobal))
- Get user and group names from files  [\#6472](https://github.com/netdata/netdata/pull/6472) ([vlvkobal](https://github.com/vlvkobal))
- Fix parsing SSL ACL along with others [\#6468](https://github.com/netdata/netdata/pull/6468) ([thiagoftsm](https://github.com/thiagoftsm))
- update Nginx guide with changes [\#6466](https://github.com/netdata/netdata/pull/6466) ([prhomhyse](https://github.com/prhomhyse))
- netdata/packaging: Binary distributions - clean up .DEB package generation process [\#6465](https://github.com/netdata/netdata/pull/6465) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- python sensors collector: sensor chips filtering fix [\#6463](https://github.com/netdata/netdata/pull/6463) ([ilyam8](https://github.com/ilyam8))
- Fix broken links [\#6461](https://github.com/netdata/netdata/pull/6461) ([TheLovinator1](https://github.com/TheLovinator1))
- json function could create overflow [\#6460](https://github.com/netdata/netdata/pull/6460) ([thiagoftsm](https://github.com/thiagoftsm))
- Fix nodes menu sizing \(responsive\) [\#6455](https://github.com/netdata/netdata/pull/6455) ([builat](https://github.com/builat))
- Add netdata haproxy documentation page [\#6454](https://github.com/netdata/netdata/pull/6454) ([johnramsden](https://github.com/johnramsden))
- Fix CRC and I/O error handling in dbengine [\#6452](https://github.com/netdata/netdata/pull/6452) ([mfundul](https://github.com/mfundul))
- Stop docs icon from linking to streaming page instead of docs root [\#6445](https://github.com/netdata/netdata/pull/6445) ([joelhans](https://github.com/joelhans))
- Add more supported backends to the documentation [\#6443](https://github.com/netdata/netdata/pull/6443) ([vlvkobal](https://github.com/vlvkobal))
- netdata/packaging: Remove Ventureer from demo sites [\#6442](https://github.com/netdata/netdata/pull/6442) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Safer container names [\#6441](https://github.com/netdata/netdata/pull/6441) ([ViViDboarder](https://github.com/ViViDboarder))
- Update docs health monitoring and health management api [\#6435](https://github.com/netdata/netdata/pull/6435) ([jghaanstra](https://github.com/jghaanstra))
- Fix issue with HTML docs generation [\#6433](https://github.com/netdata/netdata/pull/6433) ([cakrit](https://github.com/cakrit))
- rethinkdb collector new driver support [\#6431](https://github.com/netdata/netdata/pull/6431) ([ilyam8](https://github.com/ilyam8))
- New 'homepage' for documentation site [\#6428](https://github.com/netdata/netdata/pull/6428) ([joelhans](https://github.com/joelhans))
- Utf8 Badge Fix And URL Parser International Support \(initial\) [\#6426](https://github.com/netdata/netdata/pull/6426) ([underhood](https://github.com/underhood))
- Styling improvements to documentation [\#6425](https://github.com/netdata/netdata/pull/6425) ([joelhans](https://github.com/joelhans))
- Netdata/packaging: Add documentation for binary packages, plus draft table for distributions support [\#6422](https://github.com/netdata/netdata/pull/6422) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- netdata/packaging/doc: Update documentation dependencies [\#6421](https://github.com/netdata/netdata/pull/6421) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- Add global configuration option for zero metrics [\#6419](https://github.com/netdata/netdata/pull/6419) ([vlvkobal](https://github.com/vlvkobal))
- Updated logos in the infographic and remaining favicons [\#6417](https://github.com/netdata/netdata/pull/6417) ([cakrit](https://github.com/cakrit))
- netdata/packaging: Fix RPM packaging workflow issues, plus draft changes for .DEB packaging [\#6415](https://github.com/netdata/netdata/pull/6415) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- SSL vs. TLS consistency and clarification in documentation [\#6414](https://github.com/netdata/netdata/pull/6414) ([joelhans](https://github.com/joelhans))
- Add more codeowners to the core [\#6413](https://github.com/netdata/netdata/pull/6413) ([vlvkobal](https://github.com/vlvkobal))
- Add news of v1.16.0 to main README [\#6411](https://github.com/netdata/netdata/pull/6411) ([cakrit](https://github.com/cakrit))
- Update Running-behind-apache.md [\#6406](https://github.com/netdata/netdata/pull/6406) ([Steve8291](https://github.com/Steve8291))
- Fix Web API Health documentation  [\#6404](https://github.com/netdata/netdata/pull/6404) ([thiagoftsm](https://github.com/thiagoftsm))
- Snapshot uniqueId fix [\#6400](https://github.com/netdata/netdata/pull/6400) ([jacekkolasa](https://github.com/jacekkolasa))
- Make use of GCC's \_\_attribute\_\_\(\(unused\)\) [\#6392](https://github.com/netdata/netdata/pull/6392) ([ac000](https://github.com/ac000))
- Change default installation to stable in documentation [\#6388](https://github.com/netdata/netdata/pull/6388) ([joelhans](https://github.com/joelhans))
- Daemon fix double kills of collection threads on shutdown [\#6387](https://github.com/netdata/netdata/pull/6387) ([emmrk](https://github.com/emmrk))
- Add apps grouping debug messages [\#6375](https://github.com/netdata/netdata/pull/6375) ([vlvkobal](https://github.com/vlvkobal))
- Reimplemented mypopen\(\) function family [\#6339](https://github.com/netdata/netdata/pull/6339) ([mfundul](https://github.com/mfundul))

## [v1.16.0](https://github.com/netdata/netdata/tree/v1.16.0) (2019-07-08)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.15.0...v1.16.0)

**Merged pull requests:**

- Ignore /dev and /run space/inode usage [\#6399](https://github.com/netdata/netdata/pull/6399) ([vlvkobal](https://github.com/vlvkobal))
- Update favicon with new logo  [\#6398](https://github.com/netdata/netdata/pull/6398) ([cakrit](https://github.com/cakrit))
- Update apps\_groups.conf for time group [\#6397](https://github.com/netdata/netdata/pull/6397) ([mbarper](https://github.com/mbarper))
- Update to icons [\#6396](https://github.com/netdata/netdata/pull/6396) ([ivorjvr](https://github.com/ivorjvr))
- Changed links from my-netdata.io to netdata.cloud [\#6389](https://github.com/netdata/netdata/pull/6389) ([joelhans](https://github.com/joelhans))
- alarm-notify.sh should respect the cloud base url setting  [\#6383](https://github.com/netdata/netdata/pull/6383) ([ladakis](https://github.com/ladakis))
- Add a check for a macro declaration for the perf plugin [\#6382](https://github.com/netdata/netdata/pull/6382) ([vlvkobal](https://github.com/vlvkobal))
- Add a .gitattributes file [\#6381](https://github.com/netdata/netdata/pull/6381) ([ac000](https://github.com/ac000))
- Health fix double Free Corruption [\#6379](https://github.com/netdata/netdata/pull/6379) ([thiagoftsm](https://github.com/thiagoftsm))
- Health giving wrong message [\#6377](https://github.com/netdata/netdata/pull/6377) ([thiagoftsm](https://github.com/thiagoftsm))
- Health could not read properly the health silencers file [\#6374](https://github.com/netdata/netdata/pull/6374) ([thiagoftsm](https://github.com/thiagoftsm))
- Add more debug messages for pluginsd pipe errors [\#6373](https://github.com/netdata/netdata/pull/6373) ([vlvkobal](https://github.com/vlvkobal))
- Improve documentation about file descriptors and systemd configuration. [\#6372](https://github.com/netdata/netdata/pull/6372) ([mfundul](https://github.com/mfundul))
- netdata/packaging: Netdata binary packages generation - spec file refinement, support for nightlies \(RPM\) [\#6369](https://github.com/netdata/netdata/pull/6369) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- apps.plugin: detect openldap server processes by default on Debian [\#6364](https://github.com/netdata/netdata/pull/6364) ([nodiscc](https://github.com/nodiscc))
- Easily disable alarms, by persisting the silencers configuration [\#6360](https://github.com/netdata/netdata/pull/6360) ([thiagoftsm](https://github.com/thiagoftsm))
- Redirect old site to new site at www.netdata.cloud [\#6359](https://github.com/netdata/netdata/pull/6359) ([cakrit](https://github.com/cakrit))
- Better checks for nfacct headers [\#6351](https://github.com/netdata/netdata/pull/6351) ([vlvkobal](https://github.com/vlvkobal))
- Tomcat status invalid XML fix [\#6345](https://github.com/netdata/netdata/pull/6345) ([Danamir](https://github.com/Danamir))
- netdata/packaging/docker: Fix docker documentation and a fix to avoid failures [\#6344](https://github.com/netdata/netdata/pull/6344) ([paulkatsoulakis](https://github.com/paulkatsoulakis))
- pihole: alarms delay fix [\#6342](https://github.com/netdata/netdata/pull/6342) ([ilyam8](https://github.com/ilyam8))
- monit: obsolete service in runtime [\#6340](https://github.com/netdata/netdata/pull/6340) ([ilyam8](https://github.com/ilyam8))
- adaptec\_raid: logical device regex fix [\#6338](https://github.com/netdata/netdata/pull/6338) ([ilyam8](https://github.com/ilyam8))
- Better context name to client context [\#6336](https://github.com/netdata/netdata/pull/6336) ([thiagoftsm](https://github.com/thiagoftsm))

## [v1.15.0](https://github.com/netdata/netdata/tree/v1.15.0) (2019-05-22)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.14.0...v1.15.0)

## [v1.14.0](https://github.com/netdata/netdata/tree/v1.14.0) (2019-04-18)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.14.0-rc0...v1.14.0)

## [v1.14.0-rc0](https://github.com/netdata/netdata/tree/v1.14.0-rc0) (2019-03-30)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.13.0...v1.14.0-rc0)

## [v1.13.0](https://github.com/netdata/netdata/tree/v1.13.0) (2019-03-14)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.2...v1.13.0)

## [v1.12.2](https://github.com/netdata/netdata/tree/v1.12.2) (2019-02-28)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.1...v1.12.2)

## [v1.12.1](https://github.com/netdata/netdata/tree/v1.12.1) (2019-02-21)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0...v1.12.1)

## [v1.12.0](https://github.com/netdata/netdata/tree/v1.12.0) (2019-02-06)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc3...v1.12.0)

## [v1.12.0-rc3](https://github.com/netdata/netdata/tree/v1.12.0-rc3) (2019-01-17)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc2...v1.12.0-rc3)

## [v1.12.0-rc2](https://github.com/netdata/netdata/tree/v1.12.0-rc2) (2019-01-03)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc1...v1.12.0-rc2)

## [v1.12.0-rc1](https://github.com/netdata/netdata/tree/v1.12.0-rc1) (2018-12-19)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc0...v1.12.0-rc1)

## [v1.12.0-rc0](https://github.com/netdata/netdata/tree/v1.12.0-rc0) (2018-12-06)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.11.1...v1.12.0-rc0)

## [v1.11.1](https://github.com/netdata/netdata/tree/v1.11.1) (2018-11-22)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.11.0...v1.11.1)

## [v1.11.0](https://github.com/netdata/netdata/tree/v1.11.0) (2018-11-02)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.10.0...v1.11.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
