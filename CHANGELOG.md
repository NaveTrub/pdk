# Changelog

All changes to this repo will be documented in this file.
See the [release notes](https://puppet.com/docs/pdk/latest/release_notes.html) for a high-level summary.


## [v1.4.1](https://github.com/puppetlabs/pdk/tree/v1.4.1) (2018-02-26)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.4.0...v1.4.1)

**Fixed bugs:**

- pdk update and convert fixes [\#433](https://github.com/puppetlabs/pdk/pull/433) ([bmjen](https://github.com/bmjen))

**Merged pull requests:**

- Updates msg in pdk update on unconverted module [\#442](https://github.com/puppetlabs/pdk/pull/442) ([bmjen](https://github.com/bmjen))
- Release 1.4.1 amend [\#441](https://github.com/puppetlabs/pdk/pull/441) ([bmjen](https://github.com/bmjen))
- \(maint\) pdk update checks if module is pdk compat [\#440](https://github.com/puppetlabs/pdk/pull/440) ([bmjen](https://github.com/bmjen))
- Release 1.4.1 amend [\#439](https://github.com/puppetlabs/pdk/pull/439) ([bmjen](https://github.com/bmjen))
- \(maint\) add a `pdk module build` command to point to `pdk build` [\#438](https://github.com/puppetlabs/pdk/pull/438) ([DavidS](https://github.com/DavidS))
- \(maint\) unhide the `update` command [\#437](https://github.com/puppetlabs/pdk/pull/437) ([DavidS](https://github.com/DavidS))
- \(maint\) update: don't mention deleted Gemfile.lock and .bundle/config [\#436](https://github.com/puppetlabs/pdk/pull/436) ([DavidS](https://github.com/DavidS))
- Release 1.4.1 [\#435](https://github.com/puppetlabs/pdk/pull/435) ([bmjen](https://github.com/bmjen))

## [v1.4.0](https://github.com/puppetlabs/pdk/tree/v1.4.0) (2018-02-21)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.3.2...v1.4.0)

**Implemented enhancements:**

- \(PDK-771\) Wireframe `pdk update` CLI [\#419](https://github.com/puppetlabs/pdk/pull/419) ([rodjek](https://github.com/rodjek))
- \(PDK-550\) Removes unrequired questions from module interview [\#410](https://github.com/puppetlabs/pdk/pull/410) ([bmjen](https://github.com/bmjen))
-  \(PDK-506\) pdk new provider [\#409](https://github.com/puppetlabs/pdk/pull/409) ([DavidS](https://github.com/DavidS))
- \(PDK-748\) Wireframe `pdk build` CLI [\#407](https://github.com/puppetlabs/pdk/pull/407) ([rodjek](https://github.com/rodjek))

**Fixed bugs:**

- if a newer rubocop version is installed, pdk should fall-back to safe defaults [\#420](https://github.com/puppetlabs/pdk/issues/420)
- Update validation regex and error message for module name question [\#430](https://github.com/puppetlabs/pdk/pull/430) ([ardrigh](https://github.com/ardrigh))
- \(PDK-789\) Add pdk metadata to all generated templatedirs. [\#428](https://github.com/puppetlabs/pdk/pull/428) ([bmjen](https://github.com/bmjen))

**Closed issues:**

- WS1.Reputation - Symantec Endpoint Protection [\#403](https://github.com/puppetlabs/pdk/issues/403)
- task input\_method 'powershell' fails validation [\#369](https://github.com/puppetlabs/pdk/issues/369)
- PDK should have an option to disable progress indicator to make it usable in CI [\#323](https://github.com/puppetlabs/pdk/issues/323)

**Merged pull requests:**

- Release 1.4.0 [\#432](https://github.com/puppetlabs/pdk/pull/432) ([bmjen](https://github.com/bmjen))
- \(PDK-808\) Fix to pdk update when there are sync.yml changes [\#431](https://github.com/puppetlabs/pdk/pull/431) ([bmjen](https://github.com/bmjen))
- \(PDK-806\) Update metadata interview text if metadata.json already exists [\#429](https://github.com/puppetlabs/pdk/pull/429) ([rodjek](https://github.com/rodjek))
- \(FIXUP\) Make `pdk build` overwrite prompt consistent [\#427](https://github.com/puppetlabs/pdk/pull/427) ([scotje](https://github.com/scotje))
- \(maint\) Update unit tests to use exit\_zero/exit\_nonzero matchers [\#426](https://github.com/puppetlabs/pdk/pull/426) ([rodjek](https://github.com/rodjek))
- \(PDK-804\) Fixes error in build without ignore file [\#425](https://github.com/puppetlabs/pdk/pull/425) ([bmjen](https://github.com/bmjen))
- \(PDK-799\) Adds unit tests for the UX validation [\#423](https://github.com/puppetlabs/pdk/pull/423) ([bmjen](https://github.com/bmjen))
- \(PDK-754\) Interview for missing or Forge only metadata before build [\#422](https://github.com/puppetlabs/pdk/pull/422) ([bmjen](https://github.com/bmjen))
- \(PDK-772\) Refactor PDK::Module::Convert for re-use in PDK::Module::Update [\#421](https://github.com/puppetlabs/pdk/pull/421) ([rodjek](https://github.com/rodjek))
- Revert "\(maint\) pin pdk-templates version ref to workaround puppet 5.… [\#418](https://github.com/puppetlabs/pdk/pull/418) ([bmjen](https://github.com/bmjen))
- \(PDK-799\) Adds validations and checks to pdk build workflow [\#416](https://github.com/puppetlabs/pdk/pull/416) ([bmjen](https://github.com/bmjen))
- Small fixes [\#415](https://github.com/puppetlabs/pdk/pull/415) ([DavidS](https://github.com/DavidS))
- \(maint\) Make sure we use pdk-templates master if in development [\#414](https://github.com/puppetlabs/pdk/pull/414) ([bmjen](https://github.com/bmjen))
- \(maint\) bump version for dev. [\#412](https://github.com/puppetlabs/pdk/pull/412) ([bmjen](https://github.com/bmjen))
- \(PDK-758\) Initial port & cleanup of the module build code [\#411](https://github.com/puppetlabs/pdk/pull/411) ([rodjek](https://github.com/rodjek))
- \(maint\) Fix error templatedir error message [\#408](https://github.com/puppetlabs/pdk/pull/408) ([DavidS](https://github.com/DavidS))
- \(MAINT\) remove dead code [\#406](https://github.com/puppetlabs/pdk/pull/406) ([DavidS](https://github.com/DavidS))
- \(PDK-575\) Run puppet parser validate with an dummy empty puppet.conf [\#402](https://github.com/puppetlabs/pdk/pull/402) ([rodjek](https://github.com/rodjek))

## [v1.3.2](https://github.com/puppetlabs/pdk/tree/v1.3.2) (2018-01-17)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.3.1...v1.3.2)

**Closed issues:**

- "pdk convert" and "pdk new module" fails on OSX Sierra [\#396](https://github.com/puppetlabs/pdk/issues/396)
- Update shipped ruby [\#395](https://github.com/puppetlabs/pdk/issues/395)

**Merged pull requests:**

- \(maint\) Default PDK::TEMPLATE\_REF to PDK::VERSION [\#405](https://github.com/puppetlabs/pdk/pull/405) ([rodjek](https://github.com/rodjek))
- 1.3.2 Release Prep [\#404](https://github.com/puppetlabs/pdk/pull/404) ([HelenCampbell](https://github.com/HelenCampbell))
- \(PDK-552\) Soften PDK::CLI::Util.ensure\_in\_module! error messages [\#401](https://github.com/puppetlabs/pdk/pull/401) ([rodjek](https://github.com/rodjek))
- \(PDK-739\) Fall back to default template if necessary [\#400](https://github.com/puppetlabs/pdk/pull/400) ([rodjek](https://github.com/rodjek))

## [v1.3.1](https://github.com/puppetlabs/pdk/tree/v1.3.1) (2017-12-20)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.3.0...v1.3.1)

**Fixed bugs:**

- \(PDK-736\) Improve handling of old template-url and template-ref [\#397](https://github.com/puppetlabs/pdk/pull/397) ([scotje](https://github.com/scotje))

**Merged pull requests:**

- Release Prep for 1.3.1 Hotfix [\#398](https://github.com/puppetlabs/pdk/pull/398) ([HelenCampbell](https://github.com/HelenCampbell))

## [v1.3.0](https://github.com/puppetlabs/pdk/tree/v1.3.0) (2017-12-15)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.2.1...v1.3.0)

**Implemented enhancements:**

- \(PDK-715\) Transition pdk to use pdk-templates as template repo [\#380](https://github.com/puppetlabs/pdk/pull/380) ([bmjen](https://github.com/bmjen))
- \(PDK-622\) Unhide convert subcommand [\#367](https://github.com/puppetlabs/pdk/pull/367) ([bmjen](https://github.com/bmjen))
- \(maint\) Add/update template metadata on convert [\#366](https://github.com/puppetlabs/pdk/pull/366) ([rodjek](https://github.com/rodjek))
- \(PDK-625\) Formatting of modified status report and addition of full c… [\#365](https://github.com/puppetlabs/pdk/pull/365) ([HelenCampbell](https://github.com/HelenCampbell))
- \(PDK-672\) List files changed from convert [\#363](https://github.com/puppetlabs/pdk/pull/363) ([bmjen](https://github.com/bmjen))
- \(PDK-668\) Templatedir now reads .sync.yml for config when rendering t… [\#354](https://github.com/puppetlabs/pdk/pull/354) ([HelenCampbell](https://github.com/HelenCampbell))
- \(PDK-643\) Remove escape sequence spam when running in CI systems [\#353](https://github.com/puppetlabs/pdk/pull/353) ([rodjek](https://github.com/rodjek))
- \(PDK-671\) Makes module\_name optional for pdk new module. [\#344](https://github.com/puppetlabs/pdk/pull/344) ([bmjen](https://github.com/bmjen))
-  \(PDK-628\) Addition of module\_name question to interview [\#327](https://github.com/puppetlabs/pdk/pull/327) ([HelenCampbell](https://github.com/HelenCampbell))
- \(PDK-594\) mention the used template during `new module` [\#321](https://github.com/puppetlabs/pdk/pull/321) ([DavidS](https://github.com/DavidS))

**Fixed bugs:**

- add in readline support to ruby [\#305](https://github.com/puppetlabs/pdk/issues/305)
- \(PDK-643\) Disable non-exec validator spinners when noninteractive [\#385](https://github.com/puppetlabs/pdk/pull/385) ([rodjek](https://github.com/rodjek))
- \(PDK-596\) Accept "forgeuser-modulename" as argument to `new module`  [\#358](https://github.com/puppetlabs/pdk/pull/358) ([DavidS](https://github.com/DavidS))
- \(PDK-429\) Fix --tests to pass through to unit test handler. [\#351](https://github.com/puppetlabs/pdk/pull/351) ([bmjen](https://github.com/bmjen))

**Closed issues:**

- Internal Server Error on PDK Download site [\#348](https://github.com/puppetlabs/pdk/issues/348)
- PDK 1.2.1 `test unit` fails for unsupported OSes [\#338](https://github.com/puppetlabs/pdk/issues/338)

**Merged pull requests:**

- Release 1.3.0 [\#394](https://github.com/puppetlabs/pdk/pull/394) ([bmjen](https://github.com/bmjen))
- \(PDK-729\) Remove Set usage in metadata [\#393](https://github.com/puppetlabs/pdk/pull/393) ([rodjek](https://github.com/rodjek))
- \(maint\) Various UX fixes [\#391](https://github.com/puppetlabs/pdk/pull/391) ([bmjen](https://github.com/bmjen))
- Minor updates to convert dialog [\#390](https://github.com/puppetlabs/pdk/pull/390) ([HelenCampbell](https://github.com/HelenCampbell))
- \(maint\) pdk convert acceptance tests [\#389](https://github.com/puppetlabs/pdk/pull/389) ([rodjek](https://github.com/rodjek))
- \(maint\) Fixes module metadata interview to as for forge username [\#388](https://github.com/puppetlabs/pdk/pull/388) ([bmjen](https://github.com/bmjen))
- \(MAINT\) Update to released version of GCG [\#387](https://github.com/puppetlabs/pdk/pull/387) ([DavidS](https://github.com/DavidS))
- \(maint\) Manually load lib/pdk/version.rb in spec [\#386](https://github.com/puppetlabs/pdk/pull/386) ([rodjek](https://github.com/rodjek))
- \(PDK-489\) unhide experimental commands [\#384](https://github.com/puppetlabs/pdk/pull/384) ([DavidS](https://github.com/DavidS))
- \(PDK 719\) Directory layout and metadata fixes during convert [\#383](https://github.com/puppetlabs/pdk/pull/383) ([HelenCampbell](https://github.com/HelenCampbell))
- \(maint\) Some tweaks to improve UX. [\#382](https://github.com/puppetlabs/pdk/pull/382) ([bmjen](https://github.com/bmjen))
- \(PDK-722\) Remove prompt to continue from start of convert [\#378](https://github.com/puppetlabs/pdk/pull/378) ([rodjek](https://github.com/rodjek))
- \(PDK-728\) Add default\_template\_ref handler. [\#377](https://github.com/puppetlabs/pdk/pull/377) ([bmjen](https://github.com/bmjen))
- \(PDK-725\) Add timestamp to PDK Convert Report [\#376](https://github.com/puppetlabs/pdk/pull/376) ([bmjen](https://github.com/bmjen))
- \(PDK-724\) Ensure dir exist before writing new files during updates. [\#375](https://github.com/puppetlabs/pdk/pull/375) ([bmjen](https://github.com/bmjen))
- \(PDK-723\) Fixes bug where sync.yml wasn't being applied on convert [\#374](https://github.com/puppetlabs/pdk/pull/374) ([bmjen](https://github.com/bmjen))
- \(PDK-713\) Clean up old bundler env during convert [\#373](https://github.com/puppetlabs/pdk/pull/373) ([rodjek](https://github.com/rodjek))
- \(PDK-715\) Use correct module template branch/ref [\#368](https://github.com/puppetlabs/pdk/pull/368) ([bmjen](https://github.com/bmjen))
- Tweaks to dialog around module conversion [\#362](https://github.com/puppetlabs/pdk/pull/362) ([HelenCampbell](https://github.com/HelenCampbell))
- Additional user prompt [\#361](https://github.com/puppetlabs/pdk/pull/361) ([rickmonro](https://github.com/rickmonro))
- Making exit errors generic for interview qs [\#357](https://github.com/puppetlabs/pdk/pull/357) ([HelenCampbell](https://github.com/HelenCampbell))
- \(maint\) Update PDK::Test::Unit.parallel\_with\_no\_tests? for PSH \#216 changes [\#356](https://github.com/puppetlabs/pdk/pull/356) ([rodjek](https://github.com/rodjek))
- \(PDK-624\) Add UpdateManager class to handle making changes to module files [\#355](https://github.com/puppetlabs/pdk/pull/355) ([rodjek](https://github.com/rodjek))
- \(PDK-627\) Support for generating/updating metadata.json during convert [\#352](https://github.com/puppetlabs/pdk/pull/352) ([rodjek](https://github.com/rodjek))
- \(PDK-674\) UX Improvement for listing unit test files. [\#349](https://github.com/puppetlabs/pdk/pull/349) ([bmjen](https://github.com/bmjen))
- \(PDK-673\) Moving git commands into a util class [\#347](https://github.com/puppetlabs/pdk/pull/347) ([HelenCampbell](https://github.com/HelenCampbell))
- \(maint\) Fix generate/ and validate/ file layout to match namespace [\#345](https://github.com/puppetlabs/pdk/pull/345) ([rodjek](https://github.com/rodjek))
- \(PDK-626\) Templatedir can now handle multiple directories [\#340](https://github.com/puppetlabs/pdk/pull/340) ([HelenCampbell](https://github.com/HelenCampbell))
- \(maint\) Tidy up package test [\#337](https://github.com/puppetlabs/pdk/pull/337) ([james-stocks](https://github.com/james-stocks))
- \(PDK-621\) Implement a skeleton `pdk convert` command [\#335](https://github.com/puppetlabs/pdk/pull/335) ([rodjek](https://github.com/rodjek))

## [v1.2.1](https://github.com/puppetlabs/pdk/tree/v1.2.1) (2017-10-26)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.2.0...v1.2.1)

**Fixed bugs:**

- Add --relative cli argument for autoload layout testing in puppet-lint [\#325](https://github.com/puppetlabs/pdk/pull/325) ([spacepants](https://github.com/spacepants))

**Closed issues:**

- Create test layout for control repositories [\#332](https://github.com/puppetlabs/pdk/issues/332)
- Support for future parser on Puppet \< 4.0.0 [\#330](https://github.com/puppetlabs/pdk/issues/330)
- Expose other executables into main bin directory [\#328](https://github.com/puppetlabs/pdk/issues/328)
- PDK should have yum/apt/choco repos [\#324](https://github.com/puppetlabs/pdk/issues/324)
- Fails to create new task on OSX [\#316](https://github.com/puppetlabs/pdk/issues/316)
- Allow validation of control repos [\#289](https://github.com/puppetlabs/pdk/issues/289)

**Merged pull requests:**

- \(PDK-637\) Release 1.2.1 [\#334](https://github.com/puppetlabs/pdk/pull/334) ([bmjen](https://github.com/bmjen))
- \(PDK-408\) adjusts known issue in README [\#326](https://github.com/puppetlabs/pdk/pull/326) ([jbondpdx](https://github.com/jbondpdx))
- \(maint\) Bump version for 1.3.0 dev cycle [\#322](https://github.com/puppetlabs/pdk/pull/322) ([bmjen](https://github.com/bmjen))
- \(maint\) Add pdk-maintainers email to README [\#318](https://github.com/puppetlabs/pdk/pull/318) ([bmjen](https://github.com/bmjen))
- Fix link to PDK docs [\#317](https://github.com/puppetlabs/pdk/pull/317) ([turbodog](https://github.com/turbodog))

## [v1.2.0](https://github.com/puppetlabs/pdk/tree/v1.2.0) (2017-10-06)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.1.0...v1.2.0)

**Implemented enhancements:**

- \(PDK-479\) new module: create examples/, and files/ directory [\#308](https://github.com/puppetlabs/pdk/pull/308) ([DavidS](https://github.com/DavidS))
- \(PDK-470\) Validation of task metadata. [\#301](https://github.com/puppetlabs/pdk/pull/301) ([bmjen](https://github.com/bmjen))
- \(PDK-468\) `new task` command [\#299](https://github.com/puppetlabs/pdk/pull/299) ([rodjek](https://github.com/rodjek))

**Fixed bugs:**

- \(PDK-408\) Explain PowerShell escaping for -- on `bundle` [\#309](https://github.com/puppetlabs/pdk/pull/309) ([DavidS](https://github.com/DavidS))
- \(PDK-482\) Update help messages to be less ambiguous [\#307](https://github.com/puppetlabs/pdk/pull/307) ([DavidS](https://github.com/DavidS))
- \(PDK-555\) Handle windows style \(backslash separated\) paths when validating [\#306](https://github.com/puppetlabs/pdk/pull/306) ([rodjek](https://github.com/rodjek))
- \(PDK-543\) Fix spdx.org URLs in messages [\#303](https://github.com/puppetlabs/pdk/pull/303) ([farkasmate](https://github.com/farkasmate))
- \(PDK-502\) make the private git available to module commands [\#298](https://github.com/puppetlabs/pdk/pull/298) ([rodjek](https://github.com/rodjek))

**Closed issues:**

- Wrong URL in module interview [\#302](https://github.com/puppetlabs/pdk/issues/302)
- Installing Gemfile dependencies on Windows fails [\#297](https://github.com/puppetlabs/pdk/issues/297)

**Merged pull requests:**

- \(maint\) Update the default task support\_noop field to false [\#313](https://github.com/puppetlabs/pdk/pull/313) ([bmjen](https://github.com/bmjen))
- \(PDK-577\) Add info line that task metadata was also generated [\#312](https://github.com/puppetlabs/pdk/pull/312) ([DavidS](https://github.com/DavidS))
- \(PDK-554\) Release 1.2.0 [\#311](https://github.com/puppetlabs/pdk/pull/311) ([bmjen](https://github.com/bmjen))
- Tasks Generation and Validation [\#310](https://github.com/puppetlabs/pdk/pull/310) ([bmjen](https://github.com/bmjen))
- \(PDK-468\) Adding parameters field to task metadata [\#300](https://github.com/puppetlabs/pdk/pull/300) ([bmjen](https://github.com/bmjen))

## [v1.1.0](https://github.com/puppetlabs/pdk/tree/v1.1.0) (2017-09-13)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.0.1...v1.1.0)

**Implemented enhancements:**

- \(PDK-369\) Improve error context for pdk test unit failures [\#294](https://github.com/puppetlabs/pdk/pull/294) ([rodjek](https://github.com/rodjek))
- \(PDK-415\) Convert user-input related problems from FATAL to ERROR [\#293](https://github.com/puppetlabs/pdk/pull/293) ([rodjek](https://github.com/rodjek))
- \(PDK-465\) Improve output from spec\_prep/spec\_clean failures [\#290](https://github.com/puppetlabs/pdk/pull/290) ([rodjek](https://github.com/rodjek))
- \(PDK-465\) Add vendored git to PATH for package installs [\#287](https://github.com/puppetlabs/pdk/pull/287) ([rodjek](https://github.com/rodjek))
- \(PDK-370\) Adds a 'pdk module generate' redirect to 'pdk new module'. [\#286](https://github.com/puppetlabs/pdk/pull/286) ([bmjen](https://github.com/bmjen))
- \(PDK-459\) Improve error message when the generation target exists [\#285](https://github.com/puppetlabs/pdk/pull/285) ([DavidS](https://github.com/DavidS))
- \(PDK-461\) Update childprocess to current version [\#282](https://github.com/puppetlabs/pdk/pull/282) ([DavidS](https://github.com/DavidS))
- \(PDK-459\) Add defined type generator [\#280](https://github.com/puppetlabs/pdk/pull/280) ([rodjek](https://github.com/rodjek))
- \(MAINT\) Copy-edited all the user-visible messages [\#276](https://github.com/puppetlabs/pdk/pull/276) ([jbondpdx](https://github.com/jbondpdx))
- \(PDK-365\) Inform and prompt user following new module generate [\#270](https://github.com/puppetlabs/pdk/pull/270) ([bmjen](https://github.com/bmjen))
- \(maint\) Debug output GEM\_HOME and GEM\_PATH before executing module commands [\#268](https://github.com/puppetlabs/pdk/pull/268) ([james-stocks](https://github.com/james-stocks))
- \(SDK-336\) Add operating system question to the new module interview [\#262](https://github.com/puppetlabs/pdk/pull/262) ([rodjek](https://github.com/rodjek))

**Fixed bugs:**

- Remove EOL style cop from default configuration [\#267](https://github.com/puppetlabs/pdk/issues/267)
- \(PDK-450\) remove stdlib dependency [\#278](https://github.com/puppetlabs/pdk/pull/278) ([DavidS](https://github.com/DavidS))
- \(PDK-420\) Ensure Puppet and Puppet::Util modules are defined [\#277](https://github.com/puppetlabs/pdk/pull/277) ([rodjek](https://github.com/rodjek))
- \(PDK-430\) Do not cache template-url answer if using the default template [\#265](https://github.com/puppetlabs/pdk/pull/265) ([rodjek](https://github.com/rodjek))

**Closed issues:**

- Write .fixtures.yml based on metadata.json [\#283](https://github.com/puppetlabs/pdk/issues/283)
- Default Gemfile for new module need linting [\#273](https://github.com/puppetlabs/pdk/issues/273)
- pdk executable not installed in path on Debian \(8.8 Jessie\) [\#272](https://github.com/puppetlabs/pdk/issues/272)
- File mode of generated files and directories are wrong [\#271](https://github.com/puppetlabs/pdk/issues/271)
- Missing bins should not be fatal [\#253](https://github.com/puppetlabs/pdk/issues/253)

**Merged pull requests:**

- \(maint\) Sync Windows api types with latest puppet. [\#296](https://github.com/puppetlabs/pdk/pull/296) ([bmjen](https://github.com/bmjen))
- Release v1.1.0 [\#295](https://github.com/puppetlabs/pdk/pull/295) ([bmjen](https://github.com/bmjen))
- \(PDK-459\) Docs for generating defined\_type [\#292](https://github.com/puppetlabs/pdk/pull/292) ([bmjen](https://github.com/bmjen))
- \(MAINT\) Run package test commands in a login shell [\#284](https://github.com/puppetlabs/pdk/pull/284) ([scotje](https://github.com/scotje))
- \(PDK-461\) Make Version.git\_ref more forgiving [\#281](https://github.com/puppetlabs/pdk/pull/281) ([DavidS](https://github.com/DavidS))
- \(PDK-446\) Package tests should expect pdk to already be on path [\#279](https://github.com/puppetlabs/pdk/pull/279) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Add strings to POT file [\#269](https://github.com/puppetlabs/pdk/pull/269) ([austb](https://github.com/austb))
- \(maint\) Updates version to 1.1.0.pre [\#264](https://github.com/puppetlabs/pdk/pull/264) ([bmjen](https://github.com/bmjen))

## [v1.0.1](https://github.com/puppetlabs/pdk/tree/v1.0.1) (2017-08-17)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v1.0.0...v1.0.1)

**Fixed bugs:**

- \(MAINT\) Add package bin path to subprocess PATH [\#261](https://github.com/puppetlabs/pdk/pull/261) ([austb](https://github.com/austb))
- \(MAINT\) Bump tty-prompt ver, remove monkey patch [\#260](https://github.com/puppetlabs/pdk/pull/260) ([austb](https://github.com/austb))

**Merged pull requests:**

- Release Prep for 1.0.1 [\#263](https://github.com/puppetlabs/pdk/pull/263) ([bmjen](https://github.com/bmjen))
- \(MAINT\) Bump master version to 1.1.0.pre [\#259](https://github.com/puppetlabs/pdk/pull/259) ([bmjen](https://github.com/bmjen))
- Formatting fix [\#258](https://github.com/puppetlabs/pdk/pull/258) ([turbodog](https://github.com/turbodog))

## [v1.0.0](https://github.com/puppetlabs/pdk/tree/v1.0.0) (2017-08-15)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.6.0...v1.0.0)

**Implemented enhancements:**

- \(PDK-395\) Use vendored pdk-module-template repo when available [\#255](https://github.com/puppetlabs/pdk/pull/255) ([scotje](https://github.com/scotje))
- Move content from README to official docs site [\#252](https://github.com/puppetlabs/pdk/pull/252) ([jbondpdx](https://github.com/jbondpdx))
- \(PDK-367\) Update questionnaire wording [\#251](https://github.com/puppetlabs/pdk/pull/251) ([DavidS](https://github.com/DavidS))
- \(PDK-406\) Add GEM\_HOME and GEM\_PATH bin dirs to PATH when executing commands [\#249](https://github.com/puppetlabs/pdk/pull/249) ([rodjek](https://github.com/rodjek))
- \(PDK-401, PDK-402, PDK-403, PDK-404\) Update validators to handle targets better [\#248](https://github.com/puppetlabs/pdk/pull/248) ([bmjen](https://github.com/bmjen))
- \(maint\) Allow bundler to install gems in parallel [\#245](https://github.com/puppetlabs/pdk/pull/245) ([james-stocks](https://github.com/james-stocks))
- \(PDK-397\) Log output of bundler commands at appropriate levels [\#243](https://github.com/puppetlabs/pdk/pull/243) ([scotje](https://github.com/scotje))
- \(PDK-396\) Disable spinners in debug mode [\#233](https://github.com/puppetlabs/pdk/pull/233) ([rodjek](https://github.com/rodjek))
- \(PDK-388, PDK-392\) Add README, CHANGELOG, and puppet requirement to module generation [\#232](https://github.com/puppetlabs/pdk/pull/232) ([bmjen](https://github.com/bmjen))
- \(SDK-144\) Add option to run validate in parallel [\#144](https://github.com/puppetlabs/pdk/pull/144) ([austb](https://github.com/austb))

**Fixed bugs:**

- Running PDK native packages on Windows under ConEmu fails [\#220](https://github.com/puppetlabs/pdk/issues/220)
- \(PDK-407\) Validate module interview confirmation answer [\#237](https://github.com/puppetlabs/pdk/pull/237) ([rodjek](https://github.com/rodjek))
- \(PDK-386\) Remove parameter options from 'new class' [\#236](https://github.com/puppetlabs/pdk/pull/236) ([austb](https://github.com/austb))

**Merged pull requests:**

- \(maint\) monkey patch TTY::Prompt::Reader::WinConsole to make it blocking [\#257](https://github.com/puppetlabs/pdk/pull/257) ([rodjek](https://github.com/rodjek))
- \(MAINT\) Release prep for 1.0.0 [\#256](https://github.com/puppetlabs/pdk/pull/256) ([scotje](https://github.com/scotje))
- \(MAINT\) temporarily remove de translation [\#250](https://github.com/puppetlabs/pdk/pull/250) ([DavidS](https://github.com/DavidS))
- \(MAINT\) Bump master version to 1.0.0.pre [\#244](https://github.com/puppetlabs/pdk/pull/244) ([scotje](https://github.com/scotje))
- \(FIXUP\) Prevent unit tests from writing results.txt to real filesystem [\#242](https://github.com/puppetlabs/pdk/pull/242) ([scotje](https://github.com/scotje))
- \(MAINT\) Don't check coverage on gitignored files [\#241](https://github.com/puppetlabs/pdk/pull/241) ([scotje](https://github.com/scotje))
- \(MAINT\) Use non-forked tty-prompt gem [\#240](https://github.com/puppetlabs/pdk/pull/240) ([austb](https://github.com/austb))
- \(MAINT\) Add ISC to approved licenses [\#238](https://github.com/puppetlabs/pdk/pull/238) ([scotje](https://github.com/scotje))
- \(maint\) add license auditing to travis [\#205](https://github.com/puppetlabs/pdk/pull/205) ([DavidS](https://github.com/DavidS))

## [v0.6.0](https://github.com/puppetlabs/pdk/tree/v0.6.0) (2017-08-08)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.5.0...v0.6.0)

**Implemented enhancements:**

- \(MAINT\) Improve moduleroot error message [\#224](https://github.com/puppetlabs/pdk/pull/224) ([DavidS](https://github.com/DavidS))
- \(MAINT\) workaround rspec-puppt-facts being case-sensitive for operatingsystem filters [\#222](https://github.com/puppetlabs/pdk/pull/222) ([DavidS](https://github.com/DavidS))
- \(PDK-354\) Change PDK::Logger to write to STDERR [\#217](https://github.com/puppetlabs/pdk/pull/217) ([scotje](https://github.com/scotje))
- \(SDK-331\) Use vendored Gemfile.lock when available and needed [\#215](https://github.com/puppetlabs/pdk/pull/215) ([scotje](https://github.com/scotje))
- \(maint\) Expose message when FileUtils.mkdir\_p fails during module generation [\#209](https://github.com/puppetlabs/pdk/pull/209) ([rodjek](https://github.com/rodjek))
- \(SDK-323\) Change color of default answer to cyan [\#206](https://github.com/puppetlabs/pdk/pull/206) ([austb](https://github.com/austb))
- \(maint\) Remove unimplemented `add provider` from docs [\#200](https://github.com/puppetlabs/pdk/pull/200) ([DavidS](https://github.com/DavidS))
- Update PowerShell install instructions [\#194](https://github.com/puppetlabs/pdk/pull/194) ([jpogran](https://github.com/jpogran))
- \(maint\) Remove unused vcs option from 'pdk new module' [\#192](https://github.com/puppetlabs/pdk/pull/192) ([rodjek](https://github.com/rodjek))
- Document compatibility policy and upgrade strategy [\#188](https://github.com/puppetlabs/pdk/pull/188) ([turbodog](https://github.com/turbodog))
- \(MAINT\) Remove spinner for `bundle check` command [\#187](https://github.com/puppetlabs/pdk/pull/187) ([scotje](https://github.com/scotje))
- \(SDK-321\) add `pdk validate help` [\#183](https://github.com/puppetlabs/pdk/pull/183) ([DavidS](https://github.com/DavidS))
- \(SDK-317\) Ensure parent of 'pdk new module' is writable before generation [\#175](https://github.com/puppetlabs/pdk/pull/175) ([rodjek](https://github.com/rodjek))
- \(SDK-312\) Add option --parallel to `pdk test unit` [\#154](https://github.com/puppetlabs/pdk/pull/154) ([austb](https://github.com/austb))

**Fixed bugs:**

- \(SDK-325\) Validate all should run all validators [\#230](https://github.com/puppetlabs/pdk/pull/230) ([bmjen](https://github.com/bmjen))
- \(PDK-373\) Make test unit --list consistent with test unit [\#216](https://github.com/puppetlabs/pdk/pull/216) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Add --strict-dependencies to metadata-json-lint invocation [\#213](https://github.com/puppetlabs/pdk/pull/213) ([scotje](https://github.com/scotje))
- \(SDK-317\) Replace File.writable? test with actually creating a test file [\#207](https://github.com/puppetlabs/pdk/pull/207) ([scotje](https://github.com/scotje))
- \(SDK-333\) Rescue Interrupt cleanly [\#199](https://github.com/puppetlabs/pdk/pull/199) ([scotje](https://github.com/scotje))
- \(\#137\) Nicer response when binary doesn't exist [\#149](https://github.com/puppetlabs/pdk/pull/149) ([rodjek](https://github.com/rodjek))

**Closed issues:**

- Add /bin/ to .gitignore [\#208](https://github.com/puppetlabs/pdk/issues/208)
- How to run beaker with pdk? [\#138](https://github.com/puppetlabs/pdk/issues/138)
- Failed to create new module with "No such file or directory - git" [\#137](https://github.com/puppetlabs/pdk/issues/137)

**Merged pull requests:**

- \(MAINT\) Release prep for 0.6.0 [\#231](https://github.com/puppetlabs/pdk/pull/231) ([scotje](https://github.com/scotje))
- Enable rubocop for package-testing folder [\#229](https://github.com/puppetlabs/pdk/pull/229) ([james-stocks](https://github.com/james-stocks))
- \(PDK-390\) Implement spec:coverage rake task [\#228](https://github.com/puppetlabs/pdk/pull/228) ([DavidS](https://github.com/DavidS))
- \(MAINT\) Re-add package acceptance test for Gemfile.lock vendoring [\#226](https://github.com/puppetlabs/pdk/pull/226) ([scotje](https://github.com/scotje))
- \(PDK-385\) Support package testing on OSX [\#225](https://github.com/puppetlabs/pdk/pull/225) ([james-stocks](https://github.com/james-stocks))
- Pdk preview docs [\#223](https://github.com/puppetlabs/pdk/pull/223) ([jbondpdx](https://github.com/jbondpdx))
- Package testing: beaker needs to have keys configured [\#221](https://github.com/puppetlabs/pdk/pull/221) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Add find\_all and find\_first json functions [\#219](https://github.com/puppetlabs/pdk/pull/219) ([austb](https://github.com/austb))
- \(MAINT\) Fix fatal error in test unit --parallel [\#218](https://github.com/puppetlabs/pdk/pull/218) ([austb](https://github.com/austb))
- \(MAINT\) Add ability to test locally built package with beaker [\#214](https://github.com/puppetlabs/pdk/pull/214) ([scotje](https://github.com/scotje))
- Give beaker package tests their own Gemfile [\#212](https://github.com/puppetlabs/pdk/pull/212) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Update to official master of github-changelog-generator [\#211](https://github.com/puppetlabs/pdk/pull/211) ([DavidS](https://github.com/DavidS))
- Unit test baseline [\#210](https://github.com/puppetlabs/pdk/pull/210) ([james-stocks](https://github.com/james-stocks))
- \(maint\) Add unit tests for PDK::Util [\#204](https://github.com/puppetlabs/pdk/pull/204) ([rodjek](https://github.com/rodjek))
- \(maint\) Finish unit tests for PDK::Generate::PuppetObject [\#203](https://github.com/puppetlabs/pdk/pull/203) ([rodjek](https://github.com/rodjek))
- \(maint\) Add unit test for PDK.logger [\#202](https://github.com/puppetlabs/pdk/pull/202) ([rodjek](https://github.com/rodjek))
- \(maint\) enable coveralls [\#201](https://github.com/puppetlabs/pdk/pull/201) ([DavidS](https://github.com/DavidS))
- \(MAINT\) Add YARD gem and rake task [\#197](https://github.com/puppetlabs/pdk/pull/197) ([austb](https://github.com/austb))
- \(MAINT\) Replace \#sort.last with \#max [\#196](https://github.com/puppetlabs/pdk/pull/196) ([austb](https://github.com/austb))
- \(SDK-313\) Update acceptance tests following audit [\#193](https://github.com/puppetlabs/pdk/pull/193) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Move all unit tests under spec/unit [\#190](https://github.com/puppetlabs/pdk/pull/190) ([scotje](https://github.com/scotje))
- \(MAINT\) Bump version to 0.6.0.pre [\#186](https://github.com/puppetlabs/pdk/pull/186) ([scotje](https://github.com/scotje))
- Clarity on running pdk from PowerShell [\#185](https://github.com/puppetlabs/pdk/pull/185) ([turbodog](https://github.com/turbodog))
- \(maint\) Change package testing to beaker tests [\#184](https://github.com/puppetlabs/pdk/pull/184) ([james-stocks](https://github.com/james-stocks))
- \(maint\) Move contributor's notes to separate file [\#181](https://github.com/puppetlabs/pdk/pull/181) ([DavidS](https://github.com/DavidS))

## [v0.5.0](https://github.com/puppetlabs/pdk/tree/v0.5.0) (2017-07-20)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.4.4...v0.5.0)

**Implemented enhancements:**

- \(SDK-329\) implement running arbitrary commands in PDK's environment [\#179](https://github.com/puppetlabs/pdk/pull/179) ([DavidS](https://github.com/DavidS))
- \(maint\) Add 2.1.9 as the minimum required ruby version in the gemspec [\#176](https://github.com/puppetlabs/pdk/pull/176) ([rodjek](https://github.com/rodjek))

**Fixed bugs:**

- \(SDK-331\) allow additional gems to be installed [\#178](https://github.com/puppetlabs/pdk/pull/178) ([DavidS](https://github.com/DavidS))

**Merged pull requests:**

- \(maint\) Release prep for 0.5.0 [\#180](https://github.com/puppetlabs/pdk/pull/180) ([DavidS](https://github.com/DavidS))
- \(SDK-322\) Acceptance test for spec tests of new class [\#177](https://github.com/puppetlabs/pdk/pull/177) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Bump to 0.5.0.pre [\#174](https://github.com/puppetlabs/pdk/pull/174) ([scotje](https://github.com/scotje))
- \(maint\) Finish PDK::Validate::\* unit tests [\#139](https://github.com/puppetlabs/pdk/pull/139) ([rodjek](https://github.com/rodjek))

## [v0.4.4](https://github.com/puppetlabs/pdk/tree/v0.4.4) (2017-07-18)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.4.3...v0.4.4)

**Fixed bugs:**

- Cannot find bundler [\#166](https://github.com/puppetlabs/pdk/issues/166)
- Validate fails on existing module [\#158](https://github.com/puppetlabs/pdk/issues/158)
- \(\#158\) \(\#166\) Resolve issue loading bundler from gem installs [\#170](https://github.com/puppetlabs/pdk/pull/170) ([scotje](https://github.com/scotje))
- \(SDK-319\) force usage of our ruby [\#168](https://github.com/puppetlabs/pdk/pull/168) ([DavidS](https://github.com/DavidS))

**Closed issues:**

- `new module` docs differ from reality [\#159](https://github.com/puppetlabs/pdk/issues/159)

**Merged pull requests:**

- \(MAINT\) Release prep for 0.4.4 [\#173](https://github.com/puppetlabs/pdk/pull/173) ([scotje](https://github.com/scotje))
- \(maint\) mention the execution policy for windows [\#172](https://github.com/puppetlabs/pdk/pull/172) ([DavidS](https://github.com/DavidS))
- \(maint\) update README to point to current download location [\#171](https://github.com/puppetlabs/pdk/pull/171) ([DavidS](https://github.com/DavidS))
- \(maint\) fix `new module` description in README [\#169](https://github.com/puppetlabs/pdk/pull/169) ([DavidS](https://github.com/DavidS))

## [v0.4.3](https://github.com/puppetlabs/pdk/tree/v0.4.3) (2017-07-17)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.4.2...v0.4.3)

**Fixed bugs:**

- \(FIXUP\) Fix default subprocess success/failure messages on Windows [\#164](https://github.com/puppetlabs/pdk/pull/164) ([scotje](https://github.com/scotje))

**Merged pull requests:**

- \(MAINT\) Release prep 0.4.3 [\#165](https://github.com/puppetlabs/pdk/pull/165) ([scotje](https://github.com/scotje))
- \(MAINT\) Re-bump version to 0.5.0.pre [\#163](https://github.com/puppetlabs/pdk/pull/163) ([scotje](https://github.com/scotje))

## [v0.4.2](https://github.com/puppetlabs/pdk/tree/v0.4.2) (2017-07-17)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.4.1...v0.4.2)

**Fixed bugs:**

- Can't create module if new module fails to get login [\#157](https://github.com/puppetlabs/pdk/issues/157)
- \(FIXUP\) Add missing newlines in new module interview prompts [\#161](https://github.com/puppetlabs/pdk/pull/161) ([scotje](https://github.com/scotje))
- Use default username when Etc.getlogin fails [\#160](https://github.com/puppetlabs/pdk/pull/160) ([austb](https://github.com/austb))

**Merged pull requests:**

- \(MAINT\) Release prep for 0.4.2 [\#162](https://github.com/puppetlabs/pdk/pull/162) ([scotje](https://github.com/scotje))
- \(maint\) Remove beaker pre-suite for updating rubygems [\#156](https://github.com/puppetlabs/pdk/pull/156) ([james-stocks](https://github.com/james-stocks))
- \(maint\) Bumps version for next dev cycle. [\#152](https://github.com/puppetlabs/pdk/pull/152) ([bmjen](https://github.com/bmjen))

## [v0.4.1](https://github.com/puppetlabs/pdk/tree/v0.4.1) (2017-07-14)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.4.0...v0.4.1)

**Fixed bugs:**

- \(FIXUP\) Resolve conflation of cachedir concepts [\#153](https://github.com/puppetlabs/pdk/pull/153) ([scotje](https://github.com/scotje))

**Merged pull requests:**

- Release prep 0.4.1 [\#155](https://github.com/puppetlabs/pdk/pull/155) ([scotje](https://github.com/scotje))

## [v0.4.0](https://github.com/puppetlabs/pdk/tree/v0.4.0) (2017-07-14)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.3.0...v0.4.0)

**Implemented enhancements:**

- \(SDK-306\) Use vendored development gems in package install [\#145](https://github.com/puppetlabs/pdk/pull/145) ([scotje](https://github.com/scotje))
- \(SDK-299\) Check metadata.json syntax before linting [\#133](https://github.com/puppetlabs/pdk/pull/133) ([rodjek](https://github.com/rodjek))
- \(SDK-305\) Answer file to cache module interview answers, template-url etc [\#132](https://github.com/puppetlabs/pdk/pull/132) ([rodjek](https://github.com/rodjek))
- \(SDK-296\) Allow target selection for the metadata validator [\#124](https://github.com/puppetlabs/pdk/pull/124) ([rodjek](https://github.com/rodjek))

**Fixed bugs:**

- \(maint\) Remove nil values from metadata before generating JSON [\#127](https://github.com/puppetlabs/pdk/pull/127) ([rodjek](https://github.com/rodjek))
- \(SDK-298\) Handle exception raised when an invalid report format is specified on the CLI [\#125](https://github.com/puppetlabs/pdk/pull/125) ([rodjek](https://github.com/rodjek))

**Merged pull requests:**

- v0.4.0 Release Prep [\#151](https://github.com/puppetlabs/pdk/pull/151) ([bmjen](https://github.com/bmjen))
- \(FIXUP\) Fixes spec tests for answer\_file [\#150](https://github.com/puppetlabs/pdk/pull/150) ([bmjen](https://github.com/bmjen))
- \(maint\) Pin activesupport to the last release that supported Ruby 2.1.9 [\#148](https://github.com/puppetlabs/pdk/pull/148) ([bmjen](https://github.com/bmjen))
- \(FIXUP\) Change rubocop default json\_data to a hash [\#147](https://github.com/puppetlabs/pdk/pull/147) ([scotje](https://github.com/scotje))
- \(FIXUP\) Flatten parsed JSON output from puppet-lint before processing [\#146](https://github.com/puppetlabs/pdk/pull/146) ([scotje](https://github.com/scotje))
- \(maint\) Improvements to acceptance testing packages [\#142](https://github.com/puppetlabs/pdk/pull/142) ([james-stocks](https://github.com/james-stocks))
- Acceptance tidy-up [\#140](https://github.com/puppetlabs/pdk/pull/140) ([james-stocks](https://github.com/james-stocks))
- removes some incorrect info from README [\#136](https://github.com/puppetlabs/pdk/pull/136) ([jbondpdx](https://github.com/jbondpdx))
- \(maint\) Changes sdk references to pdk [\#135](https://github.com/puppetlabs/pdk/pull/135) ([bmjen](https://github.com/bmjen))
- \(SDK-275\) Run tests against VM with package install [\#134](https://github.com/puppetlabs/pdk/pull/134) ([james-stocks](https://github.com/james-stocks))
- \(maint\) Extend unit tests for PDK::Util::Bundler [\#131](https://github.com/puppetlabs/pdk/pull/131) ([rodjek](https://github.com/rodjek))
- \(maint\) Add missing unit tests for PDK::Report::Event [\#130](https://github.com/puppetlabs/pdk/pull/130) ([rodjek](https://github.com/rodjek))
- \(maint\) Add unit tests for 'pdk new class' CLI [\#129](https://github.com/puppetlabs/pdk/pull/129) ([rodjek](https://github.com/rodjek))
- \(maint\) Finish off PDK::CLI::Validate unit tests [\#128](https://github.com/puppetlabs/pdk/pull/128) ([rodjek](https://github.com/rodjek))
- \(maint\) Updating version for new dev cycle [\#126](https://github.com/puppetlabs/pdk/pull/126) ([bmjen](https://github.com/bmjen))
- \(maint\) Performance improvements [\#120](https://github.com/puppetlabs/pdk/pull/120) ([rodjek](https://github.com/rodjek))
- \(idea\) More expressive RSpec matchers for JUnit XML content [\#117](https://github.com/puppetlabs/pdk/pull/117) ([rodjek](https://github.com/rodjek))

## [v0.3.0](https://github.com/puppetlabs/pdk/tree/v0.3.0) (2017-06-29)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.2.0...v0.3.0)

**Implemented enhancements:**

- \(MAINT\) Add support for stacktrace to Report::Event class [\#112](https://github.com/puppetlabs/pdk/pull/112) ([scotje](https://github.com/scotje))
- \(MAINT\) Various CLI::Exec improvements and updates [\#111](https://github.com/puppetlabs/pdk/pull/111) ([scotje](https://github.com/scotje))
- \(SDK-148\) Add "test unit --list" [\#107](https://github.com/puppetlabs/pdk/pull/107) ([james-stocks](https://github.com/james-stocks))
- \(SDK-137\) Add puppet syntax validation [\#105](https://github.com/puppetlabs/pdk/pull/105) ([bmjen](https://github.com/bmjen))
- \(SDK-285\) Add --auto-correct flag to validators that support it [\#104](https://github.com/puppetlabs/pdk/pull/104) ([rodjek](https://github.com/rodjek))
- \(SDK-284\) Add guidance for users during new module interview [\#103](https://github.com/puppetlabs/pdk/pull/103) ([rodjek](https://github.com/rodjek))
- \(SDK-147\) Add 'test unit' runner and basic output formatting [\#98](https://github.com/puppetlabs/pdk/pull/98) ([scotje](https://github.com/scotje))

**Fixed bugs:**

- \(SDK-297\) Fixes writing reports to a file [\#119](https://github.com/puppetlabs/pdk/pull/119) ([bmjen](https://github.com/bmjen))
- \(SDK-290\) Make sure that all usernames are processed when creating a new module [\#108](https://github.com/puppetlabs/pdk/pull/108) ([austb](https://github.com/austb))
- \(SDK-277\) Exit cleanly if pdk commands are run outside of a module [\#100](https://github.com/puppetlabs/pdk/pull/100) ([rodjek](https://github.com/rodjek))

**Closed issues:**

- Function: pdk new module my\_module does not work when a user name contains non-alphanumeric characters [\#106](https://github.com/puppetlabs/pdk/issues/106)

**Merged pull requests:**

- v0.3.0 Release Prep. [\#123](https://github.com/puppetlabs/pdk/pull/123) ([bmjen](https://github.com/bmjen))
- \(maint\) Remove incorrect space character in README [\#122](https://github.com/puppetlabs/pdk/pull/122) ([james-stocks](https://github.com/james-stocks))
- \(SDK-294\) Avoid module name conflict in acceptance tests. [\#121](https://github.com/puppetlabs/pdk/pull/121) ([james-stocks](https://github.com/james-stocks))
- \(maint\) Add release instructions [\#118](https://github.com/puppetlabs/pdk/pull/118) ([DavidS](https://github.com/DavidS))
- \(maint\) Support for skipped/pending tests [\#115](https://github.com/puppetlabs/pdk/pull/115) ([james-stocks](https://github.com/james-stocks))
- \(maint\) Update validate CLI help text & README [\#114](https://github.com/puppetlabs/pdk/pull/114) ([rodjek](https://github.com/rodjek))
- \(maint\) Make binstub generation quiet unless it fails [\#113](https://github.com/puppetlabs/pdk/pull/113) ([rodjek](https://github.com/rodjek))
- Cleanup rubocop todos [\#110](https://github.com/puppetlabs/pdk/pull/110) ([rodjek](https://github.com/rodjek))
- \(SDK-260\) Acceptance tests for puppet-lint integration [\#109](https://github.com/puppetlabs/pdk/pull/109) ([rodjek](https://github.com/rodjek))
- \(maint\) update bundler on travis to current version [\#101](https://github.com/puppetlabs/pdk/pull/101) ([DavidS](https://github.com/DavidS))
- \(SDK-256\) Acceptance tests for metadata validator behavior and output [\#99](https://github.com/puppetlabs/pdk/pull/99) ([rodjek](https://github.com/rodjek))

## [v0.2.0](https://github.com/puppetlabs/pdk/tree/v0.2.0) (2017-06-21)
[Full Changelog](https://github.com/puppetlabs/pdk/compare/v0.1.0...v0.2.0)

**Implemented enhancements:**

- \(SDK-137\) Adds Puppet Parser syntax validation [\#94](https://github.com/puppetlabs/pdk/pull/94) ([bmjen](https://github.com/bmjen))
- \(SDK-274\) Adds --version option [\#90](https://github.com/puppetlabs/pdk/pull/90) ([bmjen](https://github.com/bmjen))
- \(SDK-244\) Add rubocop validation subcommand [\#75](https://github.com/puppetlabs/pdk/pull/75) ([rodjek](https://github.com/rodjek))
- \(maint\) Add hints for gem installation [\#74](https://github.com/puppetlabs/pdk/pull/74) ([DavidS](https://github.com/DavidS))
- \(SDK-240\) Adds puppet-lint validation subcommand [\#71](https://github.com/puppetlabs/pdk/pull/71) ([bmjen](https://github.com/bmjen))
- \(SDK-261\) Manage basic bundler operations for module dev [\#62](https://github.com/puppetlabs/pdk/pull/62) ([scotje](https://github.com/scotje))
- \(SDK-232\) Add operatingsystem\_support defaults [\#58](https://github.com/puppetlabs/pdk/pull/58) ([DavidS](https://github.com/DavidS))

**Fixed bugs:**

- pdk expects missing git binaries [\#61](https://github.com/puppetlabs/pdk/issues/61)
- \(maint\) avoid interfering with local ruby configs [\#86](https://github.com/puppetlabs/pdk/pull/86) ([DavidS](https://github.com/DavidS))
- \(SDK-262\) Populate default metadata to match interview defaults [\#63](https://github.com/puppetlabs/pdk/pull/63) ([rodjek](https://github.com/rodjek))
- \(maint\) nokogiri: avoid versions without ruby 2.1 support [\#60](https://github.com/puppetlabs/pdk/pull/60) ([DavidS](https://github.com/DavidS))

**Closed issues:**

- create\_process error on windows when creating a new module [\#73](https://github.com/puppetlabs/pdk/issues/73)

**Merged pull requests:**

- \(maint\) Release 0.2.0 [\#97](https://github.com/puppetlabs/pdk/pull/97) ([DavidS](https://github.com/DavidS))
- \(SDK-245\) Add acceptance tests for the output of the ruby validator [\#96](https://github.com/puppetlabs/pdk/pull/96) ([rodjek](https://github.com/rodjek))
- \(SDK-247\) Add tests for rubocop target selection [\#95](https://github.com/puppetlabs/pdk/pull/95) ([rodjek](https://github.com/rodjek))
- \(maint\) update travis badge to public instance [\#93](https://github.com/puppetlabs/pdk/pull/93) ([DavidS](https://github.com/DavidS))
- \(maint\) Guard PDK::Util::Bundle.ensure\_bundle! to only run once [\#91](https://github.com/puppetlabs/pdk/pull/91) ([rodjek](https://github.com/rodjek))
- \(maint\) release prep prep [\#89](https://github.com/puppetlabs/pdk/pull/89) ([DavidS](https://github.com/DavidS))
- \(MAINT\) Create a class-based subprocess executor. [\#88](https://github.com/puppetlabs/pdk/pull/88) ([scotje](https://github.com/scotje))
- \(maint\) Fixes travis-ci hipchat notifications [\#85](https://github.com/puppetlabs/pdk/pull/85) ([bmjen](https://github.com/bmjen))
- \(maint\) Rubocop rake task, and shared context [\#84](https://github.com/puppetlabs/pdk/pull/84) ([DavidS](https://github.com/DavidS))
- \(SDK-244\) Add basic ruby validation acceptance tests. [\#83](https://github.com/puppetlabs/pdk/pull/83) ([DavidS](https://github.com/DavidS))
- \(maint\) Expand Windows 8.3 paths in templatedir [\#82](https://github.com/puppetlabs/pdk/pull/82) ([james-stocks](https://github.com/james-stocks))
- Report format implementation [\#81](https://github.com/puppetlabs/pdk/pull/81) ([rodjek](https://github.com/rodjek))
- \(FIXUP\) Add a GEM\_PATH for bundler when running acceptance tests [\#80](https://github.com/puppetlabs/pdk/pull/80) ([scotje](https://github.com/scotje))
- Naming fix [\#79](https://github.com/puppetlabs/pdk/pull/79) ([turbodog](https://github.com/turbodog))
- \(SDK-276\) Rubocop rules and cleanup [\#78](https://github.com/puppetlabs/pdk/pull/78) ([DavidS](https://github.com/DavidS))
- \(maint\) Windows cache folder should not be roaming [\#77](https://github.com/puppetlabs/pdk/pull/77) ([james-stocks](https://github.com/james-stocks))
- \(SDK-190\) Acceptance tests for using commands outside module folder [\#76](https://github.com/puppetlabs/pdk/pull/76) ([james-stocks](https://github.com/james-stocks))
- \(FIXUP\) Fixes module\_root typo and validate nil handling [\#72](https://github.com/puppetlabs/pdk/pull/72) ([bmjen](https://github.com/bmjen))
- \(SDK-269\) Add acceptance tests for bundle management. [\#68](https://github.com/puppetlabs/pdk/pull/68) ([scotje](https://github.com/scotje))
- \(maint\) refactor CLI initialisation to recommended CRI pattern [\#67](https://github.com/puppetlabs/pdk/pull/67) ([DavidS](https://github.com/DavidS))
- \(SDK-197\) add acceptance tests for new class command [\#65](https://github.com/puppetlabs/pdk/pull/65) ([DavidS](https://github.com/DavidS))
- \(SDK-218\) Prepare for CI tests against built packages [\#64](https://github.com/puppetlabs/pdk/pull/64) ([james-stocks](https://github.com/james-stocks))
- Relax data type validation to warn when non-standard types used [\#59](https://github.com/puppetlabs/pdk/pull/59) ([rodjek](https://github.com/rodjek))

## [v0.1.0](https://github.com/puppetlabs/pdk/tree/v0.1.0) (2017-06-05)
**Implemented enhancements:**

- \(maint\) update Contributing section [\#56](https://github.com/puppetlabs/pdk/pull/56) ([DavidS](https://github.com/DavidS))
- \(SDK-197\) Add 'new class' generator command [\#48](https://github.com/puppetlabs/pdk/pull/48) ([rodjek](https://github.com/rodjek))
- \(SDK-201\) Add 'new module' generator command [\#41](https://github.com/puppetlabs/pdk/pull/41) ([rodjek](https://github.com/rodjek))
- \(maint\) make debug output optional [\#40](https://github.com/puppetlabs/pdk/pull/40) ([rodjek](https://github.com/rodjek))
- \(maint\) Print help for 'new' command if no type provided [\#35](https://github.com/puppetlabs/pdk/pull/35) ([rodjek](https://github.com/rodjek))
- \(SDK-214\) Add gettext and externalize strings [\#32](https://github.com/puppetlabs/pdk/pull/32) ([scotje](https://github.com/scotje))
- \(SDK-178\) interactive license and module name query [\#30](https://github.com/puppetlabs/pdk/pull/30) ([DavidS](https://github.com/DavidS))
- \(SDK-200\) Add user interview for `new module` info gathering [\#26](https://github.com/puppetlabs/pdk/pull/26) ([whopper](https://github.com/whopper))
- \(maint\) Replace --report-\* options with --format. [\#24](https://github.com/puppetlabs/pdk/pull/24) ([whopper](https://github.com/whopper))
- \(SDK-191\) Allow validators and targets as arguments rather than options [\#22](https://github.com/puppetlabs/pdk/pull/22) ([whopper](https://github.com/whopper))
- \(SDK-185\) Include the command in usage help output [\#19](https://github.com/puppetlabs/pdk/pull/19) ([james-stocks](https://github.com/james-stocks))

**Fixed bugs:**

- \(maint\) use correct basedir for windows execs [\#51](https://github.com/puppetlabs/pdk/pull/51) ([DavidS](https://github.com/DavidS))
- \(maint\) Update pdk.gemspec to not depend on git to assign files. [\#27](https://github.com/puppetlabs/pdk/pull/27) ([scotje](https://github.com/scotje))

**Merged pull requests:**

- \(maint\) Add CI badges to README [\#57](https://github.com/puppetlabs/pdk/pull/57) ([james-stocks](https://github.com/james-stocks))
- \(maint\) Add local acceptance tests to Github CI [\#55](https://github.com/puppetlabs/pdk/pull/55) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Ignore bundler generated binstubs but keep bin/\(setup|console\) [\#54](https://github.com/puppetlabs/pdk/pull/54) ([scotje](https://github.com/scotje))
- Fixes to acceptance [\#53](https://github.com/puppetlabs/pdk/pull/53) ([james-stocks](https://github.com/james-stocks))
- \(SDK-259\) Add NOTICE file [\#50](https://github.com/puppetlabs/pdk/pull/50) ([DavidS](https://github.com/DavidS))
- \(SDK-223\) Allow running acceptance tests against current checkout [\#49](https://github.com/puppetlabs/pdk/pull/49) ([james-stocks](https://github.com/james-stocks))
- \(SDK-222\) Enable rubocop checking in travis [\#44](https://github.com/puppetlabs/pdk/pull/44) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Fixup usage of Tempfile in PDK::CLI::Exec [\#39](https://github.com/puppetlabs/pdk/pull/39) ([scotje](https://github.com/scotje))
- \(maint\) Rephrase and tighten CLI spec test [\#38](https://github.com/puppetlabs/pdk/pull/38) ([DavidS](https://github.com/DavidS))
- \(SDK-217\) Prepare acceptance testing for CI [\#37](https://github.com/puppetlabs/pdk/pull/37) ([james-stocks](https://github.com/james-stocks))
- \(maint, l10n, de\) remove obsolete msgids [\#36](https://github.com/puppetlabs/pdk/pull/36) ([DavidS](https://github.com/DavidS))
- \(MAINT\) Add Appveyor HipChat config. [\#34](https://github.com/puppetlabs/pdk/pull/34) ([scotje](https://github.com/scotje))
- \(MAINT\) Add Hipchat notifications to Travis config. [\#33](https://github.com/puppetlabs/pdk/pull/33) ([scotje](https://github.com/scotje))
- \(SDK-195\) Initial commit of acceptance spec tests [\#29](https://github.com/puppetlabs/pdk/pull/29) ([james-stocks](https://github.com/james-stocks))
- \(MAINT\) Remove Ruby 2.3.x heredoc syntax usage and add 2.1.9 to travis. [\#25](https://github.com/puppetlabs/pdk/pull/25) ([scotje](https://github.com/scotje))
- \(maint\) SDK to Puppet Development Kit naming change [\#21](https://github.com/puppetlabs/pdk/pull/21) ([whopper](https://github.com/whopper))
- \(MAINT\) Rename "generate provider" to "add provider" in README. [\#17](https://github.com/puppetlabs/pdk/pull/17) ([scotje](https://github.com/scotje))
- \(SDK-120\) Remove old Pick logo [\#16](https://github.com/puppetlabs/pdk/pull/16) ([whopper](https://github.com/whopper))
- \(SDK-120\) Add skeleton for unit test subcommand [\#15](https://github.com/puppetlabs/pdk/pull/15) ([whopper](https://github.com/whopper))
- \(PDK-176\) Rename Pick to PDK [\#14](https://github.com/puppetlabs/pdk/pull/14) ([whopper](https://github.com/whopper))
- \(MAINT\) Add basic logging facility. [\#13](https://github.com/puppetlabs/pdk/pull/13) ([scotje](https://github.com/scotje))
- \(MAINT\) Update Pick::Report specs to use and clean up a tmpdir. [\#12](https://github.com/puppetlabs/pdk/pull/12) ([scotje](https://github.com/scotje))
- \(MAINT\) Minor adjustments to CLI setup. [\#11](https://github.com/puppetlabs/pdk/pull/11) ([scotje](https://github.com/scotje))
- \(SDK-105\) Add Cri option parsing and static analysis functionality [\#10](https://github.com/puppetlabs/pdk/pull/10) ([whopper](https://github.com/whopper))
- \(maint\) Tidy up Gemfile [\#8](https://github.com/puppetlabs/pdk/pull/8) ([james-stocks](https://github.com/james-stocks))
- \(SDK-99\) Enable travis and appveyor spec tests [\#7](https://github.com/puppetlabs/pdk/pull/7) ([james-stocks](https://github.com/james-stocks))
- Remove 'Code Management' section. [\#6](https://github.com/puppetlabs/pdk/pull/6) ([scotje](https://github.com/scotje))
- Rename 'test static' to 'validate' and refine [\#4](https://github.com/puppetlabs/pdk/pull/4) ([scotje](https://github.com/scotje))
- Rename 'generate module' to 'new' [\#2](https://github.com/puppetlabs/pdk/pull/2) ([scotje](https://github.com/scotje))
- for review: \(docs\) first edit on pick README [\#1](https://github.com/puppetlabs/pdk/pull/1) ([jbondpdx](https://github.com/jbondpdx))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*