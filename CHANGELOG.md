# Change Log

## [Unreleased](https://github.com/AlchemyCMS/alchemy_cms/tree/HEAD)

[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.2.0...HEAD)

**Fixed bugs:**

- Directly updates content position in database [\#917](https://github.com/AlchemyCMS/alchemy_cms/pull/917) ([tvdeyen](https://github.com/tvdeyen))

**Closed issues:**

- Picture preprocessing with ArgumentError [\#936](https://github.com/AlchemyCMS/alchemy_cms/issues/936)
- Multiple sites organizing page\_layouts [\#930](https://github.com/AlchemyCMS/alchemy_cms/issues/930)
- Elimiate a page lookup on frontend cached elements [\#898](https://github.com/AlchemyCMS/alchemy_cms/issues/898)

**Merged pull requests:**

- Do not append geometry string to preprocess option [\#938](https://github.com/AlchemyCMS/alchemy_cms/pull/938) ([tvdeyen](https://github.com/tvdeyen))
- Display year for created\_at of an attachment in the backend [\#933](https://github.com/AlchemyCMS/alchemy_cms/pull/933) ([nielspetersen](https://github.com/nielspetersen))
- Fail pull requests on hound violations [\#932](https://github.com/AlchemyCMS/alchemy_cms/pull/932) ([tvdeyen](https://github.com/tvdeyen))
- Unify Alchemy translation methods [\#931](https://github.com/AlchemyCMS/alchemy_cms/pull/931) ([tvdeyen](https://github.com/tvdeyen))
- Miscellaneous copy fixes [\#926](https://github.com/AlchemyCMS/alchemy_cms/pull/926) ([allanbreyes](https://github.com/allanbreyes))
- Relax the hound [\#925](https://github.com/AlchemyCMS/alchemy_cms/pull/925) ([tvdeyen](https://github.com/tvdeyen))
- Moves page status info into reusable partial [\#924](https://github.com/AlchemyCMS/alchemy_cms/pull/924) ([tvdeyen](https://github.com/tvdeyen))
- Respect :reverse option when sorting elements [\#919](https://github.com/AlchemyCMS/alchemy_cms/pull/919) ([dannymidnight](https://github.com/dannymidnight))
- Respect :reverse flag as per documentation [\#915](https://github.com/AlchemyCMS/alchemy_cms/pull/915) ([dannymidnight](https://github.com/dannymidnight))
- Eliminate an SQL lookup on frontend cached element partials [\#911](https://github.com/AlchemyCMS/alchemy_cms/pull/911) ([mtomov](https://github.com/mtomov))

## [v3.1.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.3) (2016-01-21)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.2.0.rc2...v3.1.3)

**Fixed bugs:**

- NoMethodError: undefined method `each\_with\_index' for nil:NilClass while sorting elements [\#860](https://github.com/AlchemyCMS/alchemy_cms/issues/860)
- Tags got concatenated when saving tags for picture  [\#849](https://github.com/AlchemyCMS/alchemy_cms/issues/849)
- Directly updates content position in database [\#916](https://github.com/AlchemyCMS/alchemy_cms/pull/916) ([tvdeyen](https://github.com/tvdeyen))

**Closed issues:**

- Refactor Alchemy::Admin::PicturesController from an F on Code Climate [\#910](https://github.com/AlchemyCMS/alchemy_cms/issues/910)
- Test ticket from Code Climate [\#909](https://github.com/AlchemyCMS/alchemy_cms/issues/909)
- AlchemyCMS can become extremly unresponsive with thousands of pages. [\#894](https://github.com/AlchemyCMS/alchemy_cms/issues/894)
- RSS feeds also show elements that are not public [\#883](https://github.com/AlchemyCMS/alchemy_cms/issues/883)
- RSS feeds not working anymore [\#880](https://github.com/AlchemyCMS/alchemy_cms/issues/880)
- Configuring an EssenceSelect from elements.yml file [\#870](https://github.com/AlchemyCMS/alchemy_cms/issues/870)
- uninitialized constant Alchemy::Alchemy::Config [\#867](https://github.com/AlchemyCMS/alchemy_cms/issues/867)
- Allow cropping in the elements.yml has no effect [\#853](https://github.com/AlchemyCMS/alchemy_cms/issues/853)
- Editor cannot access Languages page in admin interface [\#841](https://github.com/AlchemyCMS/alchemy_cms/issues/841)
- Renaming of file in the Library - strict constraints [\#839](https://github.com/AlchemyCMS/alchemy_cms/issues/839)
- Linked essence has no yellow background. [\#835](https://github.com/AlchemyCMS/alchemy_cms/issues/835)
- Installing Alchemy 3.2.0.rc1 in fresh Ruby fails with bundle issues [\#833](https://github.com/AlchemyCMS/alchemy_cms/issues/833)
- German/Sprache: "Freigeben" vs. "Veröffentlichen"  [\#832](https://github.com/AlchemyCMS/alchemy_cms/issues/832)
- Can't delete pictures from library [\#819](https://github.com/AlchemyCMS/alchemy_cms/issues/819)
- Conflict when generating new Alchemy project [\#816](https://github.com/AlchemyCMS/alchemy_cms/issues/816)
- gif are wrongly converted to jpg [\#794](https://github.com/AlchemyCMS/alchemy_cms/issues/794)
- Files permissions are too restrictive [\#781](https://github.com/AlchemyCMS/alchemy_cms/issues/781)
- trying to include custom js in backend [\#665](https://github.com/AlchemyCMS/alchemy_cms/issues/665)

**Merged pull requests:**

- 4.0/nodes: Some test fixes [\#907](https://github.com/AlchemyCMS/alchemy_cms/pull/907) ([mamhoff](https://github.com/mamhoff))
- Removes old middleware for rescueing legacy sessions [\#906](https://github.com/AlchemyCMS/alchemy_cms/pull/906) ([tvdeyen](https://github.com/tvdeyen))
- Skip the default locale in urls [\#904](https://github.com/AlchemyCMS/alchemy_cms/pull/904) ([tvdeyen](https://github.com/tvdeyen))
- Try to fix erratic failing page feature spec [\#903](https://github.com/AlchemyCMS/alchemy_cms/pull/903) ([tvdeyen](https://github.com/tvdeyen))
- Several search query param fixes. [\#902](https://github.com/AlchemyCMS/alchemy_cms/pull/902) ([tvdeyen](https://github.com/tvdeyen))
- Build for Ruby 2.3.0-preview1 [\#901](https://github.com/AlchemyCMS/alchemy_cms/pull/901) ([tvdeyen](https://github.com/tvdeyen))
- Refactor default language creation into a private method [\#893](https://github.com/AlchemyCMS/alchemy_cms/pull/893) ([mamhoff](https://github.com/mamhoff))
- Adds site request specs [\#892](https://github.com/AlchemyCMS/alchemy_cms/pull/892) ([tvdeyen](https://github.com/tvdeyen))
- Refactors factories [\#891](https://github.com/AlchemyCMS/alchemy_cms/pull/891) ([tvdeyen](https://github.com/tvdeyen))
- Use `send\_file` instead of `send\_data` [\#888](https://github.com/AlchemyCMS/alchemy_cms/pull/888) ([jrieger](https://github.com/jrieger))
- Always pass on search parameters through resource controller actions [\#887](https://github.com/AlchemyCMS/alchemy_cms/pull/887) ([mamhoff](https://github.com/mamhoff))
- Fix tag list display on load [\#886](https://github.com/AlchemyCMS/alchemy_cms/pull/886) ([chalmagean](https://github.com/chalmagean))
- Allow custom routing for admin backend [\#885](https://github.com/AlchemyCMS/alchemy_cms/pull/885) ([milj](https://github.com/milj))
- Only show published elements in RSS feed, fixes \#883 [\#884](https://github.com/AlchemyCMS/alchemy_cms/pull/884) ([IngoAlbers](https://github.com/IngoAlbers))
- Merge pull request \#861 from AlchemyCMS/fix/cache-of-global-pages [\#882](https://github.com/AlchemyCMS/alchemy_cms/pull/882) ([nielspetersen](https://github.com/nielspetersen))
- Allow PagesController to handle rss requests, fixes \#880 [\#881](https://github.com/AlchemyCMS/alchemy_cms/pull/881) ([IngoAlbers](https://github.com/IngoAlbers))
- Add `dependent: :destroy` to has\_many relation for nested elements [\#877](https://github.com/AlchemyCMS/alchemy_cms/pull/877) ([robinboening](https://github.com/robinboening))
- Enable to pass multiple page\_layouts to on\_page\_layout [\#876](https://github.com/AlchemyCMS/alchemy_cms/pull/876) ([robinboening](https://github.com/robinboening))
- Removes user class permissions. [\#875](https://github.com/AlchemyCMS/alchemy_cms/pull/875) ([tvdeyen](https://github.com/tvdeyen))
- Do not raise error if element\_ids params is missing while ordering el… [\#874](https://github.com/AlchemyCMS/alchemy_cms/pull/874) ([tvdeyen](https://github.com/tvdeyen))
- Remove invalid locale attribute from a tag in navigation [\#873](https://github.com/AlchemyCMS/alchemy_cms/pull/873) ([IngoAlbers](https://github.com/IngoAlbers))
- Fix animated gifs display [\#872](https://github.com/AlchemyCMS/alchemy_cms/pull/872) ([tvdeyen](https://github.com/tvdeyen))
- Fix/essence select grouped options tags [\#871](https://github.com/AlchemyCMS/alchemy_cms/pull/871) ([tvdeyen](https://github.com/tvdeyen))
- Fix: copies of nested elements keeping old page id. [\#866](https://github.com/AlchemyCMS/alchemy_cms/pull/866) ([tvdeyen](https://github.com/tvdeyen))
- Rename the admin body class method. [\#865](https://github.com/AlchemyCMS/alchemy_cms/pull/865) ([tvdeyen](https://github.com/tvdeyen))
- Fix linked essence color. [\#864](https://github.com/AlchemyCMS/alchemy_cms/pull/864) ([tvdeyen](https://github.com/tvdeyen))
- fix Page.public\_language\_roots [\#862](https://github.com/AlchemyCMS/alchemy_cms/pull/862) ([Salzig](https://github.com/Salzig))
- Fix/cache of global pages [\#861](https://github.com/AlchemyCMS/alchemy_cms/pull/861) ([robinboening](https://github.com/robinboening))
- More reliable essence\_picture allow\_image\_cropping test [\#859](https://github.com/AlchemyCMS/alchemy_cms/pull/859) ([tvdeyen](https://github.com/tvdeyen))
- Fix on\_page\_layout callback functionality [\#857](https://github.com/AlchemyCMS/alchemy_cms/pull/857) ([robinboening](https://github.com/robinboening))
- Fix \#853 [\#856](https://github.com/AlchemyCMS/alchemy_cms/pull/856) ([tvdeyen](https://github.com/tvdeyen))
- Refactors content\_settings\_value [\#855](https://github.com/AlchemyCMS/alchemy_cms/pull/855) ([tvdeyen](https://github.com/tvdeyen))
- Change implementation of on\_page\_layout callbacks [\#854](https://github.com/AlchemyCMS/alchemy_cms/pull/854) ([tvdeyen](https://github.com/tvdeyen))
- Image library slideshow [\#851](https://github.com/AlchemyCMS/alchemy_cms/pull/851) ([tvdeyen](https://github.com/tvdeyen))
- A Select shouldn't be too wide [\#847](https://github.com/AlchemyCMS/alchemy_cms/pull/847) ([mamhoff](https://github.com/mamhoff))
- generated missing element partials for dummy app [\#845](https://github.com/AlchemyCMS/alchemy_cms/pull/845) ([heisam](https://github.com/heisam))
- Tinymce Updates [\#843](https://github.com/AlchemyCMS/alchemy_cms/pull/843) ([tvdeyen](https://github.com/tvdeyen))
- Allow editors to visit languages page in admin area, fixes \#841 [\#842](https://github.com/AlchemyCMS/alchemy_cms/pull/842) ([IngoAlbers](https://github.com/IngoAlbers))
- Allow filenames for attachments with special characters [\#840](https://github.com/AlchemyCMS/alchemy_cms/pull/840) ([nielspetersen](https://github.com/nielspetersen))
- Better resource CSV export. [\#838](https://github.com/AlchemyCMS/alchemy_cms/pull/838) ([tvdeyen](https://github.com/tvdeyen))
- Proposal: New Image Library Overlay Layout [\#837](https://github.com/AlchemyCMS/alchemy_cms/pull/837) ([tvdeyen](https://github.com/tvdeyen))
- Resource views enhancements [\#834](https://github.com/AlchemyCMS/alchemy_cms/pull/834) ([tvdeyen](https://github.com/tvdeyen))
- Unify urlname generation in Page\#update\_urlname! and  Page\#set\_urlname. [\#825](https://github.com/AlchemyCMS/alchemy_cms/pull/825) ([Domenoth](https://github.com/Domenoth))
- Move dev/test gems to the Gemfile [\#820](https://github.com/AlchemyCMS/alchemy_cms/pull/820) ([chalmagean](https://github.com/chalmagean))
- Add a Gitter chat badge to README.md [\#801](https://github.com/AlchemyCMS/alchemy_cms/pull/801) ([gitter-badger](https://github.com/gitter-badger))

## [v3.2.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.2.0) (2015-07-30)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.2.0.rc1...v3.2.0)

**Closed issues:**

- No \(german\) translation for "show/hide element" [\#818](https://github.com/AlchemyCMS/alchemy_cms/issues/818)
- Nestable elements: Contents for nested elements not rendered [\#815](https://github.com/AlchemyCMS/alchemy_cms/issues/815)
- show\_alchemy\_picture\_path error undefined method `configuration' [\#804](https://github.com/AlchemyCMS/alchemy_cms/issues/804)
- error on reload trash view after restore element from trash v3.1.1 [\#767](https://github.com/AlchemyCMS/alchemy_cms/issues/767)
- Page\#set\_urlname and Page\#update\_urlname! generate different urlnames. [\#759](https://github.com/AlchemyCMS/alchemy_cms/issues/759)
- Suggestion: Allow sorting Elements by more than one content [\#751](https://github.com/AlchemyCMS/alchemy_cms/issues/751)

**Merged pull requests:**

- Execute bundle install right before alchemy:install is called [\#830](https://github.com/AlchemyCMS/alchemy_cms/pull/830) ([robinboening](https://github.com/robinboening))
- Execute bundle install right before alchemy:install is called [\#829](https://github.com/AlchemyCMS/alchemy_cms/pull/829) ([robinboening](https://github.com/robinboening))
- EssenceFile and Attachment refactoring. [\#828](https://github.com/AlchemyCMS/alchemy_cms/pull/828) ([tvdeyen](https://github.com/tvdeyen))
- Globally show the current locked pages tabs. [\#827](https://github.com/AlchemyCMS/alchemy_cms/pull/827) ([tvdeyen](https://github.com/tvdeyen))
- New option linkable: false for EssencePicture [\#824](https://github.com/AlchemyCMS/alchemy_cms/pull/824) ([tvdeyen](https://github.com/tvdeyen))
- Add missing german and spanish translation for element toolbar [\#823](https://github.com/AlchemyCMS/alchemy_cms/pull/823) ([nielspetersen](https://github.com/nielspetersen))
- Unify :show\_elements and :hide\_elements keys [\#822](https://github.com/AlchemyCMS/alchemy_cms/pull/822) ([mamhoff](https://github.com/mamhoff))
- Use event delegation for several element events. [\#821](https://github.com/AlchemyCMS/alchemy_cms/pull/821) ([tvdeyen](https://github.com/tvdeyen))
- Remove the duplication of decription vs. definition. [\#813](https://github.com/AlchemyCMS/alchemy_cms/pull/813) ([tvdeyen](https://github.com/tvdeyen))
- Element editor js fixes [\#812](https://github.com/AlchemyCMS/alchemy_cms/pull/812) ([tvdeyen](https://github.com/tvdeyen))
- Removes "available contents" feature. [\#810](https://github.com/AlchemyCMS/alchemy_cms/pull/810) ([tvdeyen](https://github.com/tvdeyen))
- Update generators [\#809](https://github.com/AlchemyCMS/alchemy_cms/pull/809) ([tvdeyen](https://github.com/tvdeyen))
- use ransack compatible sort headers [\#808](https://github.com/AlchemyCMS/alchemy_cms/pull/808) ([mamhoff](https://github.com/mamhoff))
- 3.2 backports from master [\#807](https://github.com/AlchemyCMS/alchemy_cms/pull/807) ([tvdeyen](https://github.com/tvdeyen))
- 4.0/green ransacking [\#805](https://github.com/AlchemyCMS/alchemy_cms/pull/805) ([mamhoff](https://github.com/mamhoff))
- 4.0/nestable elements [\#803](https://github.com/AlchemyCMS/alchemy_cms/pull/803) ([tvdeyen](https://github.com/tvdeyen))
- Update CONTRIBUTING.md [\#800](https://github.com/AlchemyCMS/alchemy_cms/pull/800) ([phaedryx](https://github.com/phaedryx))
- Update Dutch translation [\#799](https://github.com/AlchemyCMS/alchemy_cms/pull/799) ([driehuis](https://github.com/driehuis))
- Test robustness [\#798](https://github.com/AlchemyCMS/alchemy_cms/pull/798) ([tvdeyen](https://github.com/tvdeyen))
- Move Element content related methods into modules. [\#797](https://github.com/AlchemyCMS/alchemy_cms/pull/797) ([tvdeyen](https://github.com/tvdeyen))
- Allow ERB in database.yml [\#796](https://github.com/AlchemyCMS/alchemy_cms/pull/796) ([mamhoff](https://github.com/mamhoff))
- Unify urlname generation in Page\#update\_urlname! and  Page\#set\_urlname. [\#769](https://github.com/AlchemyCMS/alchemy_cms/pull/769) ([Domenoth](https://github.com/Domenoth))

## [v3.2.0.rc2](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.2.0.rc2) (2015-07-31)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.2.0...v3.2.0.rc2)

## [v3.2.0.rc1](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.2.0.rc1) (2015-06-15)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.2.0.beta...v3.2.0.rc1)

**Closed issues:**

- Alchemy Installer breaks on setting primary language [\#784](https://github.com/AlchemyCMS/alchemy_cms/issues/784)
- Multisite: order of before\_actions in pages controller - wrong site shown v3.1.1 [\#764](https://github.com/AlchemyCMS/alchemy_cms/issues/764)
- I love the angularjs Plugin ?! hatte ich euch überzeugt :\) bestimmt nicht [\#757](https://github.com/AlchemyCMS/alchemy_cms/issues/757)
- Jquery rails 4.0.3 [\#755](https://github.com/AlchemyCMS/alchemy_cms/issues/755)
- When putting a block in a cell, it's no longer possible to use it outside this cell [\#753](https://github.com/AlchemyCMS/alchemy_cms/issues/753)
- Essence presence and uniqueness validations should accept hash [\#716](https://github.com/AlchemyCMS/alchemy_cms/issues/716)
- Move user factories to alchemy\_devise [\#654](https://github.com/AlchemyCMS/alchemy_cms/issues/654)
- Capistrano 3 [\#605](https://github.com/AlchemyCMS/alchemy_cms/issues/605)

**Merged pull requests:**

- Allow custom table\_name\_prefix [\#791](https://github.com/AlchemyCMS/alchemy_cms/pull/791) ([milj](https://github.com/milj))
- Feature - site switching without changing hosts [\#790](https://github.com/AlchemyCMS/alchemy_cms/pull/790) ([nicolai86](https://github.com/nicolai86))
- Normalize Essence Type: Allow Essences outside Alchemy [\#789](https://github.com/AlchemyCMS/alchemy_cms/pull/789) ([mamhoff](https://github.com/mamhoff))
- Make the default-button extend a mixin [\#787](https://github.com/AlchemyCMS/alchemy_cms/pull/787) ([mamhoff](https://github.com/mamhoff))
- Fix image loading spinner for already loaded images [\#786](https://github.com/AlchemyCMS/alchemy_cms/pull/786) ([ajoneil](https://github.com/ajoneil))
- Fixes issue with installer \#784 [\#785](https://github.com/AlchemyCMS/alchemy_cms/pull/785) ([robinboening](https://github.com/robinboening))
- Removes duplicated test support auth helper [\#783](https://github.com/AlchemyCMS/alchemy_cms/pull/783) ([robinboening](https://github.com/robinboening))
- Extract configuration methods into its own module. [\#782](https://github.com/AlchemyCMS/alchemy_cms/pull/782) ([tvdeyen](https://github.com/tvdeyen))
- Adds a wrapper partial for breadcrumb renderer. [\#780](https://github.com/AlchemyCMS/alchemy_cms/pull/780) ([tvdeyen](https://github.com/tvdeyen))
- Better generators [\#779](https://github.com/AlchemyCMS/alchemy_cms/pull/779) ([tvdeyen](https://github.com/tvdeyen))
- Change the breadcrumb helper into a class method. [\#777](https://github.com/AlchemyCMS/alchemy_cms/pull/777) ([tvdeyen](https://github.com/tvdeyen))
- Allow hash as essence validation type [\#775](https://github.com/AlchemyCMS/alchemy_cms/pull/775) ([tvdeyen](https://github.com/tvdeyen))
- Rename user factories [\#774](https://github.com/AlchemyCMS/alchemy_cms/pull/774) ([tvdeyen](https://github.com/tvdeyen))
- Fixes \#753 [\#773](https://github.com/AlchemyCMS/alchemy_cms/pull/773) ([robinboening](https://github.com/robinboening))
- Extract SSL protection methods into Module [\#771](https://github.com/AlchemyCMS/alchemy_cms/pull/771) ([mamhoff](https://github.com/mamhoff))
- Fix: Permit picture thumbnails for guest users. [\#768](https://github.com/AlchemyCMS/alchemy_cms/pull/768) ([tvdeyen](https://github.com/tvdeyen))
- Make acts\_as\_essence work outside Alchemy namespace [\#766](https://github.com/AlchemyCMS/alchemy_cms/pull/766) ([mamhoff](https://github.com/mamhoff))
- order of before actions \(page loading\) [\#765](https://github.com/AlchemyCMS/alchemy_cms/pull/765) ([tomg65](https://github.com/tomg65))
- Introduces `on\_page\_layout` mixin. [\#762](https://github.com/AlchemyCMS/alchemy_cms/pull/762) ([tvdeyen](https://github.com/tvdeyen))
- Better routing constraints [\#756](https://github.com/AlchemyCMS/alchemy_cms/pull/756) ([tvdeyen](https://github.com/tvdeyen))

## [v3.2.0.beta](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.2.0.beta) (2015-04-02)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.9.1...v3.2.0.beta)

**Closed issues:**

- Permission problem with logged in users without roles [\#754](https://github.com/AlchemyCMS/alchemy_cms/issues/754)

**Merged pull requests:**

- Have guest user permissions for logged in users without role [\#750](https://github.com/AlchemyCMS/alchemy_cms/pull/750) ([wdspkr](https://github.com/wdspkr))

## [v2.9.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.9.1) (2015-03-31)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.1...v2.9.1)

**Closed issues:**

- I can't restore my database [\#748](https://github.com/AlchemyCMS/alchemy_cms/issues/748)
- plugin architecture [\#747](https://github.com/AlchemyCMS/alchemy_cms/issues/747)
- General issue with caching [\#744](https://github.com/AlchemyCMS/alchemy_cms/issues/744)

**Merged pull requests:**

- Patch Rspec::ActiveModel::Mocks to work with Rails 4.2.1 [\#749](https://github.com/AlchemyCMS/alchemy_cms/pull/749) ([wdspkr](https://github.com/wdspkr))
- Symlink tmp/cache on deployments [\#746](https://github.com/AlchemyCMS/alchemy_cms/pull/746) ([robinboening](https://github.com/robinboening))

## [v3.1.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.1) (2015-03-17)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.4...v3.1.1)

## [v3.0.4](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.4) (2015-03-17)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0...v3.0.4)

**Closed issues:**

- Config setting cache\_pages affects publishing in page\#edit view [\#741](https://github.com/AlchemyCMS/alchemy_cms/issues/741)
- version conflict when generating a new project [\#732](https://github.com/AlchemyCMS/alchemy_cms/issues/732)
- ActsAsTaggableOn migrations should be removed [\#721](https://github.com/AlchemyCMS/alchemy_cms/issues/721)

**Merged pull requests:**

- Overwrite cache\_key for Element [\#745](https://github.com/AlchemyCMS/alchemy_cms/pull/745) ([robinboening](https://github.com/robinboening))
- Refactors some hotspots in element class. [\#743](https://github.com/AlchemyCMS/alchemy_cms/pull/743) ([tvdeyen](https://github.com/tvdeyen))
- Fix publish button permissions. Closes \#741 [\#742](https://github.com/AlchemyCMS/alchemy_cms/pull/742) ([tvdeyen](https://github.com/tvdeyen))
- Prevent PictureController from sending Set-Cookie [\#740](https://github.com/AlchemyCMS/alchemy_cms/pull/740) ([pascalj](https://github.com/pascalj))
- Refactor request based specs. [\#738](https://github.com/AlchemyCMS/alchemy_cms/pull/738) ([tvdeyen](https://github.com/tvdeyen))
- Use correct branches when using alchemy bin [\#737](https://github.com/AlchemyCMS/alchemy_cms/pull/737) ([pascalj](https://github.com/pascalj))
- Remove condition for user role execution [\#736](https://github.com/AlchemyCMS/alchemy_cms/pull/736) ([robinboening](https://github.com/robinboening))
- Remove acts as taggable on migrations [\#722](https://github.com/AlchemyCMS/alchemy_cms/pull/722) ([tvdeyen](https://github.com/tvdeyen))

## [v3.1.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0) (2015-02-24)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.rc3...v3.1.0)

**Closed issues:**

- Non-admins can see admin area with pre-existing Rails app [\#734](https://github.com/AlchemyCMS/alchemy_cms/issues/734)

**Merged pull requests:**

- Add down migration for initial alchemy tables [\#735](https://github.com/AlchemyCMS/alchemy_cms/pull/735) ([irontoby](https://github.com/irontoby))
- Add documentation for new Alchemy.current\_user\_method config [\#733](https://github.com/AlchemyCMS/alchemy_cms/pull/733) ([irontoby](https://github.com/irontoby))
- added HTTPS source for rubygems [\#731](https://github.com/AlchemyCMS/alchemy_cms/pull/731) ([ferdinandrosario](https://github.com/ferdinandrosario))
- Rails 4.2 [\#655](https://github.com/AlchemyCMS/alchemy_cms/pull/655) ([tvdeyen](https://github.com/tvdeyen))

## [v3.1.0.rc3](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.rc3) (2015-02-20)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.rc2...v3.1.0.rc3)

**Merged pull requests:**

- Fix SimpleForm Initializer [\#730](https://github.com/AlchemyCMS/alchemy_cms/pull/730) ([jasonyork](https://github.com/jasonyork))

## [v3.1.0.rc2](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.rc2) (2015-02-20)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.rc1...v3.1.0.rc2)

**Closed issues:**

- Rails FormHelper overriden by Alchemy [\#727](https://github.com/AlchemyCMS/alchemy_cms/issues/727)
- Optional argument in BaseController\#permission\_denied is not really optional [\#715](https://github.com/AlchemyCMS/alchemy_cms/issues/715)
- Essence format validations syntax has changed without notice [\#714](https://github.com/AlchemyCMS/alchemy_cms/issues/714)
- Unable to add suggestion to the Trello board [\#712](https://github.com/AlchemyCMS/alchemy_cms/issues/712)
- PG::UndefinedColumn: ERROR: column users.id does not exist [\#710](https://github.com/AlchemyCMS/alchemy_cms/issues/710)
- Updating title of EssenceFile throws error [\#707](https://github.com/AlchemyCMS/alchemy_cms/issues/707)
- Getting locale from browser can lead to errors [\#704](https://github.com/AlchemyCMS/alchemy_cms/issues/704)
- Locale not switching correctly [\#678](https://github.com/AlchemyCMS/alchemy_cms/issues/678)

**Merged pull requests:**

- Move require `essence\_shared\_examples` after rspec in spec\_helper. [\#728](https://github.com/AlchemyCMS/alchemy_cms/pull/728) ([mtomov](https://github.com/mtomov))
- Only cache page if caching is enabled in Rails app [\#720](https://github.com/AlchemyCMS/alchemy_cms/pull/720) ([wdspkr](https://github.com/wdspkr))
- Fix file assignment [\#718](https://github.com/AlchemyCMS/alchemy_cms/pull/718) ([tvdeyen](https://github.com/tvdeyen))
- Fix thumbnail\_size calculation for 0x0 crop size values [\#717](https://github.com/AlchemyCMS/alchemy_cms/pull/717) ([tvdeyen](https://github.com/tvdeyen))
- Use primary\_key of user to find his locked pages [\#713](https://github.com/AlchemyCMS/alchemy_cms/pull/713) ([robinboening](https://github.com/robinboening))
- Use Alchemy.user\_class's primary\_key to find user. [\#711](https://github.com/AlchemyCMS/alchemy_cms/pull/711) ([tvdeyen](https://github.com/tvdeyen))
- Fixes \#704 Always check if locale is available [\#709](https://github.com/AlchemyCMS/alchemy_cms/pull/709) ([robinboening](https://github.com/robinboening))
- Fixes \#707 allow attributes for essence\_file [\#708](https://github.com/AlchemyCMS/alchemy_cms/pull/708) ([robinboening](https://github.com/robinboening))

## [v3.1.0.rc1](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.rc1) (2015-01-15)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.beta6...v3.1.0.rc1)

**Closed issues:**

- Error when updating element with picture\_gallery [\#705](https://github.com/AlchemyCMS/alchemy_cms/issues/705)
- MountPoint.get still needs Rails. [\#703](https://github.com/AlchemyCMS/alchemy_cms/issues/703)
- A second devise model breaks the url helpers [\#601](https://github.com/AlchemyCMS/alchemy_cms/issues/601)
- When saving an element with an empty essence, Alchemy complains very technically [\#597](https://github.com/AlchemyCMS/alchemy_cms/issues/597)
- Alchemy is not mounted! Falling back to root path \(/\). [\#593](https://github.com/AlchemyCMS/alchemy_cms/issues/593)

**Merged pull requests:**

- Fixes \#705 Error when params hash does not include all contents [\#706](https://github.com/AlchemyCMS/alchemy_cms/pull/706) ([robinboening](https://github.com/robinboening))

## [v3.1.0.beta6](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.beta6) (2015-01-08)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.beta5...v3.1.0.beta6)

**Closed issues:**

- inflect.acronym 'API' Global in scope, conflicts with other gems such as Spree [\#701](https://github.com/AlchemyCMS/alchemy_cms/issues/701)
- Unneeded seed on every test & extra SQL queries on every request. [\#696](https://github.com/AlchemyCMS/alchemy_cms/issues/696)
- Gem::ImpossibleDependenciesError during installation of stable 3.0.2 [\#691](https://github.com/AlchemyCMS/alchemy_cms/issues/691)
- New site creation hangs at Spring install [\#687](https://github.com/AlchemyCMS/alchemy_cms/issues/687)

**Merged pull requests:**

- Updates deploy script and generator. [\#700](https://github.com/AlchemyCMS/alchemy_cms/pull/700) ([tvdeyen](https://github.com/tvdeyen))
- Use Regexp to get Alchemy's mount point. [\#699](https://github.com/AlchemyCMS/alchemy_cms/pull/699) ([tvdeyen](https://github.com/tvdeyen))
- Adds possibility to restrict resource attributes [\#698](https://github.com/AlchemyCMS/alchemy_cms/pull/698) ([robinboening](https://github.com/robinboening))
- Do not raise, if page layout could not be found. [\#693](https://github.com/AlchemyCMS/alchemy_cms/pull/693) ([tvdeyen](https://github.com/tvdeyen))

## [v3.1.0.beta5](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.beta5) (2015-01-02)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.beta4...v3.1.0.beta5)

## [v3.1.0.beta4](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.beta4) (2015-01-02)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.3...v3.1.0.beta4)

## [v3.0.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.3) (2014-12-24)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.beta3...v3.0.3)

**Merged pull requests:**

- Fix/resource association search [\#695](https://github.com/AlchemyCMS/alchemy_cms/pull/695) ([robinboening](https://github.com/robinboening))

## [v3.1.0.beta3](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.beta3) (2014-12-18)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.beta2...v3.1.0.beta3)

**Closed issues:**

- Searching in resource association raises ActiveRecord::StatementInvalid Error [\#694](https://github.com/AlchemyCMS/alchemy_cms/issues/694)
- Custom TinyMCE config in element not working in 3.1 beta [\#683](https://github.com/AlchemyCMS/alchemy_cms/issues/683)

## [v3.1.0.beta2](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.beta2) (2014-12-17)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.1.0.beta1...v3.1.0.beta2)

**Closed issues:**

- select2 prompt text always in russian, regardless of the current locale [\#684](https://github.com/AlchemyCMS/alchemy_cms/issues/684)
- Unable to access the module created using the generator module [\#672](https://github.com/AlchemyCMS/alchemy_cms/issues/672)
- language\_root\_page factory should use Alchemy Configuration [\#669](https://github.com/AlchemyCMS/alchemy_cms/issues/669)
- Rename "Sort pages" to "Arrange pages" in English [\#668](https://github.com/AlchemyCMS/alchemy_cms/issues/668)
- Can't remove more than one tag at once. [\#659](https://github.com/AlchemyCMS/alchemy_cms/issues/659)
- Scoping attachments to specific type in EssenceFile does not work [\#626](https://github.com/AlchemyCMS/alchemy_cms/issues/626)
- No unique element can be created if element of same kind is in clipboard [\#609](https://github.com/AlchemyCMS/alchemy_cms/issues/609)
- ImageLoader doesn't work with turbolinks in FF [\#602](https://github.com/AlchemyCMS/alchemy_cms/issues/602)

**Merged pull requests:**

- Fix typo [\#692](https://github.com/AlchemyCMS/alchemy_cms/pull/692) ([seanhussey](https://github.com/seanhussey))
- Fixes \#659 [\#690](https://github.com/AlchemyCMS/alchemy_cms/pull/690) ([robinboening](https://github.com/robinboening))
- Register each essence as has\_many association. [\#688](https://github.com/AlchemyCMS/alchemy_cms/pull/688) ([tvdeyen](https://github.com/tvdeyen))
- Fix refresh event binding on preview frame. [\#686](https://github.com/AlchemyCMS/alchemy_cms/pull/686) ([tvdeyen](https://github.com/tvdeyen))
- Adds fixed resource table headers [\#685](https://github.com/AlchemyCMS/alchemy_cms/pull/685) ([tvdeyen](https://github.com/tvdeyen))
- New EssenceFile content option `only` and `except`. Closes \#626 [\#682](https://github.com/AlchemyCMS/alchemy_cms/pull/682) ([tvdeyen](https://github.com/tvdeyen))
- Fix image loading event [\#680](https://github.com/AlchemyCMS/alchemy_cms/pull/680) ([tvdeyen](https://github.com/tvdeyen))
- Fix module generator. [\#679](https://github.com/AlchemyCMS/alchemy_cms/pull/679) ([tvdeyen](https://github.com/tvdeyen))
- spanish translation for contact form [\#677](https://github.com/AlchemyCMS/alchemy_cms/pull/677) ([scambra](https://github.com/scambra))
- fix content error translation when content\_name is nested on element [\#676](https://github.com/AlchemyCMS/alchemy_cms/pull/676) ([scambra](https://github.com/scambra))
- Changed translations for sort pages to better explain the button action [\#675](https://github.com/AlchemyCMS/alchemy_cms/pull/675) ([louim](https://github.com/louim))
- translate \<page link\> in \<some pictures\> hardcoded string on picture inf... [\#674](https://github.com/AlchemyCMS/alchemy_cms/pull/674) ([scambra](https://github.com/scambra))
- copy spanish translation file [\#673](https://github.com/AlchemyCMS/alchemy_cms/pull/673) ([scambra](https://github.com/scambra))
- spanish translation [\#671](https://github.com/AlchemyCMS/alchemy_cms/pull/671) ([scambra](https://github.com/scambra))
- add delete content link to picture editor [\#670](https://github.com/AlchemyCMS/alchemy_cms/pull/670) ([scambra](https://github.com/scambra))
- Update installer [\#667](https://github.com/AlchemyCMS/alchemy_cms/pull/667) ([tvdeyen](https://github.com/tvdeyen))

## [v3.1.0.beta1](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.1.0.beta1) (2014-11-25)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.2...v3.1.0.beta1)

**Closed issues:**

- Error in new app [\#656](https://github.com/AlchemyCMS/alchemy_cms/issues/656)
- Multiple sites w. custom authentication -\> NoMethodError undefined method `login\_url' \(v 3.0.2\) [\#651](https://github.com/AlchemyCMS/alchemy_cms/issues/651)
- Dependency for jquery-ui-rails on version 5.0.0 [\#640](https://github.com/AlchemyCMS/alchemy_cms/issues/640)
- Switch to cancancan [\#633](https://github.com/AlchemyCMS/alchemy_cms/issues/633)
- Can't install into existing Rails app [\#632](https://github.com/AlchemyCMS/alchemy_cms/issues/632)
- tinymce path not prefixing asset\_host [\#596](https://github.com/AlchemyCMS/alchemy_cms/issues/596)

**Merged pull requests:**

- Updates TinyMCE config and skin to TinyMCE v4.1 [\#664](https://github.com/AlchemyCMS/alchemy_cms/pull/664) ([tvdeyen](https://github.com/tvdeyen))
- New json api namespace [\#663](https://github.com/AlchemyCMS/alchemy_cms/pull/663) ([tvdeyen](https://github.com/tvdeyen))
- Tinymce update [\#662](https://github.com/AlchemyCMS/alchemy_cms/pull/662) ([tvdeyen](https://github.com/tvdeyen))
- Ensures to use at least sass 3.2.19 [\#661](https://github.com/AlchemyCMS/alchemy_cms/pull/661) ([tvdeyen](https://github.com/tvdeyen))
- Free simple forms [\#660](https://github.com/AlchemyCMS/alchemy_cms/pull/660) ([mamhoff](https://github.com/mamhoff))
- Rspec 3 [\#658](https://github.com/AlchemyCMS/alchemy_cms/pull/658) ([tvdeyen](https://github.com/tvdeyen))
- Set positions on elements manually while ordering [\#657](https://github.com/AlchemyCMS/alchemy_cms/pull/657) ([robinboening](https://github.com/robinboening))
- Adds support for host option while dumping database [\#653](https://github.com/AlchemyCMS/alchemy_cms/pull/653) ([tvdeyen](https://github.com/tvdeyen))
- Only link sites in dashboard widgets, if login\_url is present. [\#652](https://github.com/AlchemyCMS/alchemy_cms/pull/652) ([tvdeyen](https://github.com/tvdeyen))
- Fixes picture assignment in an element editor. [\#650](https://github.com/AlchemyCMS/alchemy_cms/pull/650) ([robinboening](https://github.com/robinboening))
- Feature/export database to remote [\#649](https://github.com/AlchemyCMS/alchemy_cms/pull/649) ([tvdeyen](https://github.com/tvdeyen))
- Allow latest versions of compass-rails and sass-rails [\#648](https://github.com/AlchemyCMS/alchemy_cms/pull/648) ([tvdeyen](https://github.com/tvdeyen))
- Deprecate take\_me\_for\_preview and rename it to as\_element\_title [\#645](https://github.com/AlchemyCMS/alchemy_cms/pull/645) ([tvdeyen](https://github.com/tvdeyen))
- Adds new helper `content\_settings\_value` [\#644](https://github.com/AlchemyCMS/alchemy_cms/pull/644) ([tvdeyen](https://github.com/tvdeyen))
- Translated to Russian [\#642](https://github.com/AlchemyCMS/alchemy_cms/pull/642) ([18augst](https://github.com/18augst))

## [v3.0.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.2) (2014-09-30)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.1...v3.0.2)

**Closed issues:**

- Impossible to create new app [\#636](https://github.com/AlchemyCMS/alchemy_cms/issues/636)
- Putting an EssenceRichtext with custom TinyMCE in "available\_contents" breaks it. [\#635](https://github.com/AlchemyCMS/alchemy_cms/issues/635)

**Merged pull requests:**

- Fix published\_at setting without use of publish! [\#639](https://github.com/AlchemyCMS/alchemy_cms/pull/639) ([thomasjachmann](https://github.com/thomasjachmann))
- Set page's published\_at when not using publish! [\#638](https://github.com/AlchemyCMS/alchemy_cms/pull/638) ([thomasjachmann](https://github.com/thomasjachmann))
- Prevent to overwrite custom NonStupidDigestAssets.whitelist [\#637](https://github.com/AlchemyCMS/alchemy_cms/pull/637) ([MariuszHenn](https://github.com/MariuszHenn))
- Fix typo in ignored upload folder [\#634](https://github.com/AlchemyCMS/alchemy_cms/pull/634) ([louim](https://github.com/louim))

## [v3.0.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.1) (2014-09-11)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.0...v3.0.1)

**Closed issues:**

- Strange language behavior when extending PagesController [\#624](https://github.com/AlchemyCMS/alchemy_cms/issues/624)
- Language setting problems with thread local variables [\#623](https://github.com/AlchemyCMS/alchemy_cms/issues/623)
- assets/tinymce/langs/fr.js missing, causing the editor not to render in french [\#621](https://github.com/AlchemyCMS/alchemy_cms/issues/621)
- Feature Request: Adding "Pages" as children of Global Pages [\#620](https://github.com/AlchemyCMS/alchemy_cms/issues/620)
- I can t  install Alchemy    on my   existing Rails spree Project  [\#618](https://github.com/AlchemyCMS/alchemy_cms/issues/618)
- dependency kaminari \(~\> 0.15.0\) [\#617](https://github.com/AlchemyCMS/alchemy_cms/issues/617)
- Restricted page can be accessed without authenticating [\#614](https://github.com/AlchemyCMS/alchemy_cms/issues/614)
- Creating new project : '`const\_get': uninitialized constant User' [\#613](https://github.com/AlchemyCMS/alchemy_cms/issues/613)
- When I enter demo page [\#612](https://github.com/AlchemyCMS/alchemy_cms/issues/612)
- `Urlname` can't be less than 3 characters [\#610](https://github.com/AlchemyCMS/alchemy_cms/issues/610)
- Creating element from clipboard is not working [\#608](https://github.com/AlchemyCMS/alchemy_cms/issues/608)
- Creating a page from clipboard is not working [\#607](https://github.com/AlchemyCMS/alchemy_cms/issues/607)
- Password for a Page doesn't work [\#606](https://github.com/AlchemyCMS/alchemy_cms/issues/606)
- Can't login as admin after mounting Alchemy to /cms [\#604](https://github.com/AlchemyCMS/alchemy_cms/issues/604)
- Gem cannot be installed for rails 4.0.5 [\#598](https://github.com/AlchemyCMS/alchemy_cms/issues/598)
- Nested urlnames rake task not working. [\#594](https://github.com/AlchemyCMS/alchemy_cms/issues/594)
- Document the usage as an engine \(for the 2.9 branch\) [\#586](https://github.com/AlchemyCMS/alchemy_cms/issues/586)
- Attachment mime type not saved [\#572](https://github.com/AlchemyCMS/alchemy_cms/issues/572)
- Image cropper selection is not reflecting the default centered cropping mask for new pictures. [\#567](https://github.com/AlchemyCMS/alchemy_cms/issues/567)
- Do not suppress javascript errors in feature specs [\#562](https://github.com/AlchemyCMS/alchemy_cms/issues/562)

**Merged pull requests:**

- Rspec 3 [\#631](https://github.com/AlchemyCMS/alchemy_cms/pull/631) ([mamhoff](https://github.com/mamhoff))
- Two typos fixed in alchemy.en.yml [\#627](https://github.com/AlchemyCMS/alchemy_cms/pull/627) ([darmenise](https://github.com/darmenise))
- Avoid concurrency issues by using RequestStore [\#625](https://github.com/AlchemyCMS/alchemy_cms/pull/625) ([tbuehlmann](https://github.com/tbuehlmann))
- Fixes updating of page urlname path. [\#622](https://github.com/AlchemyCMS/alchemy_cms/pull/622) ([tvdeyen](https://github.com/tvdeyen))
- typo fix [\#611](https://github.com/AlchemyCMS/alchemy_cms/pull/611) ([georgemillo](https://github.com/georgemillo))

## [v3.0.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.0) (2014-07-03)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.0.rc8...v3.0.0)

**Closed issues:**

- Error while saving pages order with page having number as slug [\#588](https://github.com/AlchemyCMS/alchemy_cms/issues/588)
- When editing page, page properties "save button" can't be reached on small screen [\#580](https://github.com/AlchemyCMS/alchemy_cms/issues/580)

**Merged pull requests:**

- Bump act-as-taggable-on to 3.2.6 and include the necessary migrations [\#595](https://github.com/AlchemyCMS/alchemy_cms/pull/595) ([mamhoff](https://github.com/mamhoff))
- Fix typo in README.md. [\#592](https://github.com/AlchemyCMS/alchemy_cms/pull/592) ([tbuehlmann](https://github.com/tbuehlmann))
- add tests for legacy url with unknown format & parameters [\#584](https://github.com/AlchemyCMS/alchemy_cms/pull/584) ([zirni](https://github.com/zirni))
- Fix error when switching page type to external [\#574](https://github.com/AlchemyCMS/alchemy_cms/pull/574) ([wuservices](https://github.com/wuservices))

## [v3.0.0.rc8](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.0.rc8) (2014-06-18)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.9.0...v3.0.0.rc8)

**Closed issues:**

- Creating a new site with Rails 4.1.1 is failing [\#578](https://github.com/AlchemyCMS/alchemy_cms/issues/578)
- Elements from other cell should not be placable in wrong cell. [\#568](https://github.com/AlchemyCMS/alchemy_cms/issues/568)

**Merged pull requests:**

- Fixes creation of external pages. [\#577](https://github.com/AlchemyCMS/alchemy_cms/pull/577) ([tvdeyen](https://github.com/tvdeyen))
- Convert CoffeeScript views to JavaScript [\#576](https://github.com/AlchemyCMS/alchemy_cms/pull/576) ([jasonyork](https://github.com/jasonyork))

## [v2.9.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.9.0) (2014-06-16)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.8.3...v2.9.0)

**Closed issues:**

- Switching backend language from German to English does not work properly [\#530](https://github.com/AlchemyCMS/alchemy_cms/issues/530)

**Merged pull requests:**

- Adds Upgrader module with note for User model extraction in v2.9 [\#575](https://github.com/AlchemyCMS/alchemy_cms/pull/575) ([robinboening](https://github.com/robinboening))

## [v2.8.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.8.3) (2014-06-12)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.7.5...v2.8.3)

## [v2.7.5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.7.5) (2014-06-12)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.6.3...v2.7.5)

## [v2.6.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.6.3) (2014-06-12)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.0.rc7...v2.6.3)

**Closed issues:**

- Legacy Alchemy::Clipboard cookie compatibility [\#566](https://github.com/AlchemyCMS/alchemy_cms/issues/566)
- Remove temp fix for mavericks phantomjs bug? [\#554](https://github.com/AlchemyCMS/alchemy_cms/issues/554)
- Rails 4.1: Clipboard in session not serialized and breaks new element & show clipboard in admin [\#539](https://github.com/AlchemyCMS/alchemy_cms/issues/539)
- performance issue with page sorting feature [\#457](https://github.com/AlchemyCMS/alchemy_cms/issues/457)

**Merged pull requests:**

- Fixing the bug in which the urlname of an invisible page would get corru... [\#573](https://github.com/AlchemyCMS/alchemy_cms/pull/573) ([miguelpais](https://github.com/miguelpais))
- Fix/i18n translations [\#570](https://github.com/AlchemyCMS/alchemy_cms/pull/570) ([robinboening](https://github.com/robinboening))
- Faster pages sorting in O\(n\) database operations [\#569](https://github.com/AlchemyCMS/alchemy_cms/pull/569) ([miguelpais](https://github.com/miguelpais))

## [v3.0.0.rc7](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.0.rc7) (2014-06-04)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.0.rc6...v3.0.0.rc7)

**Closed issues:**

- "Couldn't find Alchemy::User without an ID" while editing an unlocked page [\#560](https://github.com/AlchemyCMS/alchemy_cms/issues/560)
- Javascript Hook [\#555](https://github.com/AlchemyCMS/alchemy_cms/issues/555)

**Merged pull requests:**

- Fixes \#560 [\#561](https://github.com/AlchemyCMS/alchemy_cms/pull/561) ([tvdeyen](https://github.com/tvdeyen))

## [v3.0.0.rc6](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.0.rc6) (2014-06-03)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.8.2...v3.0.0.rc6)

**Closed issues:**

- Refactor Cells Namespacing [\#462](https://github.com/AlchemyCMS/alchemy_cms/issues/462)

**Merged pull requests:**

- Flexible image geometry [\#559](https://github.com/AlchemyCMS/alchemy_cms/pull/559) ([mamhoff](https://github.com/mamhoff))
- Adds feature spec for admin/element trashing. [\#553](https://github.com/AlchemyCMS/alchemy_cms/pull/553) ([robinboening](https://github.com/robinboening))

## [v2.8.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.8.2) (2014-05-24)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.7.4...v2.8.2)

**Merged pull requests:**

- Fix/2.9 element position [\#545](https://github.com/AlchemyCMS/alchemy_cms/pull/545) ([robinboening](https://github.com/robinboening))

## [v2.7.4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.7.4) (2014-05-24)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.7.3...v2.7.4)

**Closed issues:**

- The mechanism for making Alchemy's routes available to JS does not support changing routes [\#541](https://github.com/AlchemyCMS/alchemy_cms/issues/541)
- broken element view after update from 3.0 beta1 to 3.0 rc5 [\#536](https://github.com/AlchemyCMS/alchemy_cms/issues/536)
- Element shows up twice, TinyMCE not loaded [\#531](https://github.com/AlchemyCMS/alchemy_cms/issues/531)
- Changing page order changes all URLs of external links [\#529](https://github.com/AlchemyCMS/alchemy_cms/issues/529)
- Add tzinfo-data to gemfile [\#524](https://github.com/AlchemyCMS/alchemy_cms/issues/524)
- Can't figure out why the rails server is unable to start [\#523](https://github.com/AlchemyCMS/alchemy_cms/issues/523)
- Alchemy command requires rails 4.0.2 [\#521](https://github.com/AlchemyCMS/alchemy_cms/issues/521)
- custom settings for tinymce in elements.yml won't work [\#500](https://github.com/AlchemyCMS/alchemy_cms/issues/500)

**Merged pull requests:**

- 2.8 backports [\#552](https://github.com/AlchemyCMS/alchemy_cms/pull/552) ([robinboening](https://github.com/robinboening))
- Fix/element position [\#549](https://github.com/AlchemyCMS/alchemy_cms/pull/549) ([robinboening](https://github.com/robinboening))
- Clean up spelling and apostrophe for English [\#547](https://github.com/AlchemyCMS/alchemy_cms/pull/547) ([wuservices](https://github.com/wuservices))
- Message model validates fields with 'email' in name with regexp for email format. [\#546](https://github.com/AlchemyCMS/alchemy_cms/pull/546) ([robinboening](https://github.com/robinboening))
- Fix/element position [\#544](https://github.com/AlchemyCMS/alchemy_cms/pull/544) ([robinboening](https://github.com/robinboening))
- 3.0/interface approvements [\#540](https://github.com/AlchemyCMS/alchemy_cms/pull/540) ([tvdeyen](https://github.com/tvdeyen))
- Split the tinymce initialization into a global and a custom "per page" p... [\#537](https://github.com/AlchemyCMS/alchemy_cms/pull/537) ([tvdeyen](https://github.com/tvdeyen))
- fix Page\#previous\_page [\#535](https://github.com/AlchemyCMS/alchemy_cms/pull/535) ([zambot](https://github.com/zambot))
- Make the regular expression for external link url matching configurable. [\#532](https://github.com/AlchemyCMS/alchemy_cms/pull/532) ([tvdeyen](https://github.com/tvdeyen))
- Validates external page urls format and prefix them with protocol if it'... [\#527](https://github.com/AlchemyCMS/alchemy_cms/pull/527) ([tvdeyen](https://github.com/tvdeyen))
- \(2.9-stable\) Prefix icon font css classes. [\#526](https://github.com/AlchemyCMS/alchemy_cms/pull/526) ([tvdeyen](https://github.com/tvdeyen))
- Adds a feature for managing the page's legacy urls [\#525](https://github.com/AlchemyCMS/alchemy_cms/pull/525) ([tvdeyen](https://github.com/tvdeyen))
- Stops enforcing users to use rails 4.0.x when using the alchemy command. [\#522](https://github.com/AlchemyCMS/alchemy_cms/pull/522) ([robinboening](https://github.com/robinboening))

## [v2.7.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.7.3) (2014-04-23)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.8.1...v2.7.3)

**Merged pull requests:**

- Changes the initialization of tinymce configuration. Closes \#500 [\#520](https://github.com/AlchemyCMS/alchemy_cms/pull/520) ([tvdeyen](https://github.com/tvdeyen))

## [v2.8.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.8.1) (2014-04-23)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v3.0.0.rc5...v2.8.1)

**Closed issues:**

- Unsuccessful Alchemy CMS installation [\#510](https://github.com/AlchemyCMS/alchemy_cms/issues/510)
- undefined method `page\_selector' for [\#509](https://github.com/AlchemyCMS/alchemy_cms/issues/509)
- Links disabled in navigation [\#505](https://github.com/AlchemyCMS/alchemy_cms/issues/505)

**Merged pull requests:**

- Adds charc ounter [\#519](https://github.com/AlchemyCMS/alchemy_cms/pull/519) ([tvdeyen](https://github.com/tvdeyen))
- Refactors and cleaning up javascript translations. [\#518](https://github.com/AlchemyCMS/alchemy_cms/pull/518) ([tvdeyen](https://github.com/tvdeyen))
- Adds short paragraph about testing Alchemy [\#517](https://github.com/AlchemyCMS/alchemy_cms/pull/517) ([nielspetersen](https://github.com/nielspetersen))
- Use `alchemy\_display\_name` to represent the currently logged in user. [\#516](https://github.com/AlchemyCMS/alchemy_cms/pull/516) ([tvdeyen](https://github.com/tvdeyen))
- Allow picture render size to be flexible in width or height [\#513](https://github.com/AlchemyCMS/alchemy_cms/pull/513) ([ChristianPeters](https://github.com/ChristianPeters))
- Use Rails' default exception handling while in page preview. [\#512](https://github.com/AlchemyCMS/alchemy_cms/pull/512) ([tvdeyen](https://github.com/tvdeyen))
- correcting 'sitemap' show flag for 2.7 [\#511](https://github.com/AlchemyCMS/alchemy_cms/pull/511) ([plapcity](https://github.com/plapcity))
- Removes left over admin users table view. [\#508](https://github.com/AlchemyCMS/alchemy_cms/pull/508) ([nielspetersen](https://github.com/nielspetersen))
- Tinymce config changes and internal anchor link option. [\#507](https://github.com/AlchemyCMS/alchemy_cms/pull/507) ([tvdeyen](https://github.com/tvdeyen))

## [v3.0.0.rc5](https://github.com/AlchemyCMS/alchemy_cms/tree/v3.0.0.rc5) (2014-03-27)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.7.2...v3.0.0.rc5)

**Closed issues:**

- Missing content is always inserted at first missing content in element [\#499](https://github.com/AlchemyCMS/alchemy_cms/issues/499)
- Page from wrong language gets displayed in page preview [\#497](https://github.com/AlchemyCMS/alchemy_cms/issues/497)
- render\_elements :only and :except options are not implemented [\#496](https://github.com/AlchemyCMS/alchemy_cms/issues/496)
- Use Paperclip for image attachments [\#495](https://github.com/AlchemyCMS/alchemy_cms/issues/495)
- Table row filter in admin-backend  [\#493](https://github.com/AlchemyCMS/alchemy_cms/issues/493)
- Alchemy CMS overrides setting my locale [\#492](https://github.com/AlchemyCMS/alchemy_cms/issues/492)
- Missing notice when one is trying to unpublish the default language [\#487](https://github.com/AlchemyCMS/alchemy_cms/issues/487)
- How not to force locale? [\#482](https://github.com/AlchemyCMS/alchemy_cms/issues/482)
- Live-Demo is not working [\#479](https://github.com/AlchemyCMS/alchemy_cms/issues/479)
- Content containers // groups [\#475](https://github.com/AlchemyCMS/alchemy_cms/issues/475)
- Visiting published, but not visible page renders 404 [\#474](https://github.com/AlchemyCMS/alchemy_cms/issues/474)
- Saving new order of pages does not refresh sitemap [\#473](https://github.com/AlchemyCMS/alchemy_cms/issues/473)
- generator for elements editor with available\_contents - missing newline with indentation \(haml\) [\#472](https://github.com/AlchemyCMS/alchemy_cms/issues/472)
- 3.0 rc4 create\_language\_tree\_form rendered with "display: none" [\#470](https://github.com/AlchemyCMS/alchemy_cms/issues/470)
- Upgrading from 2.3 to 2.7.2 [\#469](https://github.com/AlchemyCMS/alchemy_cms/issues/469)
- Validations for EssenceFile does not work [\#468](https://github.com/AlchemyCMS/alchemy_cms/issues/468)
- Uniqueness validation for essences considers trashed essences [\#467](https://github.com/AlchemyCMS/alchemy_cms/issues/467)
- Not refreshing attachment list after uploading new one \(in page edit mode\) [\#466](https://github.com/AlchemyCMS/alchemy_cms/issues/466)
- Page not refreshing after Picture destroy [\#465](https://github.com/AlchemyCMS/alchemy_cms/issues/465)
- update beta1 to rc 4 -\> undefined local variable or method `set\_translation' for \#\<Alchemy::UserSessionsController\> [\#464](https://github.com/AlchemyCMS/alchemy_cms/issues/464)
- new behavior in pages\_controller.render\_page\_or\_redirect [\#463](https://github.com/AlchemyCMS/alchemy_cms/issues/463)
- `element\#essence\_error\_messages` are blank, although validation fails [\#461](https://github.com/AlchemyCMS/alchemy_cms/issues/461)
- Authentication problem when trying to integrate alchemy\_cms 2.7.2 into an existing app with devise [\#460](https://github.com/AlchemyCMS/alchemy_cms/issues/460)
- line of translation missing/not possible [\#459](https://github.com/AlchemyCMS/alchemy_cms/issues/459)
- Show attachment in file library opens edit form. [\#458](https://github.com/AlchemyCMS/alchemy_cms/issues/458)
- resource with association throws "Association not found", when open form [\#455](https://github.com/AlchemyCMS/alchemy_cms/issues/455)
- navigation shows pages where visible flag is turned off - when logged in in backend [\#454](https://github.com/AlchemyCMS/alchemy_cms/issues/454)
- Scrollling inside 'alchemyPreviewWindow' not possible \[Backend\] [\#453](https://github.com/AlchemyCMS/alchemy_cms/issues/453)
- Cannot create pages when there's a page in the clipboard. [\#451](https://github.com/AlchemyCMS/alchemy_cms/issues/451)
- Custom essence whith richtext editor? Is this possible? [\#450](https://github.com/AlchemyCMS/alchemy_cms/issues/450)
- uninitialized constant User [\#448](https://github.com/AlchemyCMS/alchemy_cms/issues/448)
- Deprecate render\_cell\_elements [\#439](https://github.com/AlchemyCMS/alchemy_cms/issues/439)

**Merged pull requests:**

- Use ActiveModel::Model for Message model. [\#504](https://github.com/AlchemyCMS/alchemy_cms/pull/504) ([tvdeyen](https://github.com/tvdeyen))
- Refactors Element\#belonging\_cellnames [\#503](https://github.com/AlchemyCMS/alchemy_cms/pull/503) ([tvdeyen](https://github.com/tvdeyen))
- Some essence refactoring \(mainly the uniqueness validation\) [\#502](https://github.com/AlchemyCMS/alchemy_cms/pull/502) ([robinboening](https://github.com/robinboening))
- Adds support for dumping and importing PostgreSQL databases. [\#501](https://github.com/AlchemyCMS/alchemy_cms/pull/501) ([tvdeyen](https://github.com/tvdeyen))
- Fixes pages\_controller etag and last-modified headers. [\#498](https://github.com/AlchemyCMS/alchemy_cms/pull/498) ([tvdeyen](https://github.com/tvdeyen))
- Refactors essence validations and changes its API. [\#494](https://github.com/AlchemyCMS/alchemy_cms/pull/494) ([robinboening](https://github.com/robinboening))
- Adds a more helpful installer. [\#491](https://github.com/AlchemyCMS/alchemy_cms/pull/491) ([tvdeyen](https://github.com/tvdeyen))
- Adds convert to png task to legacy upgrader [\#490](https://github.com/AlchemyCMS/alchemy_cms/pull/490) ([nielspetersen](https://github.com/nielspetersen))
- Fixes for legacy upgrader in 2.0 stable [\#489](https://github.com/AlchemyCMS/alchemy_cms/pull/489) ([nielspetersen](https://github.com/nielspetersen))
- Changes error on Language from base to certain attributes [\#488](https://github.com/AlchemyCMS/alchemy_cms/pull/488) ([robinboening](https://github.com/robinboening))
- Essence validations [\#486](https://github.com/AlchemyCMS/alchemy_cms/pull/486) ([robinboening](https://github.com/robinboening))
- Fixes issue while upgrading from Alchemy v.2.2 if current value for column country\_code IS NULL [\#485](https://github.com/AlchemyCMS/alchemy_cms/pull/485) ([nielspetersen](https://github.com/nielspetersen))
- Set compatible version of authlogic. [\#484](https://github.com/AlchemyCMS/alchemy_cms/pull/484) ([nielspetersen](https://github.com/nielspetersen))
- Legacy upgrader fixes [\#481](https://github.com/AlchemyCMS/alchemy_cms/pull/481) ([nielspetersen](https://github.com/nielspetersen))
- Use only ID selector to speed up test [\#477](https://github.com/AlchemyCMS/alchemy_cms/pull/477) ([GeekOnCoffee](https://github.com/GeekOnCoffee))
- Update README.md [\#476](https://github.com/AlchemyCMS/alchemy_cms/pull/476) ([ingilniero](https://github.com/ingilniero))
- Fix syntax error in migration. [\#471](https://github.com/AlchemyCMS/alchemy_cms/pull/471) ([robinboening](https://github.com/robinboening))
- Adds shared examples for the Essence module. [\#456](https://github.com/AlchemyCMS/alchemy_cms/pull/456) ([robinboening](https://github.com/robinboening))
- Make the current\_user configurable [\#449](https://github.com/AlchemyCMS/alchemy_cms/pull/449) ([pascalj](https://github.com/pascalj))
- Refactors Admin::PagesController\#create for better readability [\#432](https://github.com/AlchemyCMS/alchemy_cms/pull/432) ([robinboening](https://github.com/robinboening))

## [v2.7.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.7.2) (2014-01-11)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.7.1...v2.7.2)

**Closed issues:**

- stable 2.7.1 subelement \(text\) throws exception - when fulltext search is enabled [\#447](https://github.com/AlchemyCMS/alchemy_cms/issues/447)
- stable 2.7.1 subelement \(image\) not directly shown [\#446](https://github.com/AlchemyCMS/alchemy_cms/issues/446)
- Logout via menubar is missing authenticity\_token [\#443](https://github.com/AlchemyCMS/alchemy_cms/issues/443)
- Upgrader should convert user role 'registered' to 'member' [\#442](https://github.com/AlchemyCMS/alchemy_cms/issues/442)
- Upgrading from 2.7 to 3.0 causes user data loss [\#440](https://github.com/AlchemyCMS/alchemy_cms/issues/440)
- dependency on turbolinks 1.3.0 [\#438](https://github.com/AlchemyCMS/alchemy_cms/issues/438)
- Cannot remove dynamically added contents from element. [\#437](https://github.com/AlchemyCMS/alchemy_cms/issues/437)
- Failed validation when adding nested elements with the same name [\#436](https://github.com/AlchemyCMS/alchemy_cms/issues/436)
- link\_target does not get set when linking elements [\#435](https://github.com/AlchemyCMS/alchemy_cms/issues/435)
- Renaming the events table? [\#431](https://github.com/AlchemyCMS/alchemy_cms/issues/431)
- rails 4 Version, NonStupidDigestAssets doesn't load [\#430](https://github.com/AlchemyCMS/alchemy_cms/issues/430)
- Element cannot be expanded after restoring from trash window. [\#411](https://github.com/AlchemyCMS/alchemy_cms/issues/411)
- elements generator creates blank partials if element has available\_contents [\#407](https://github.com/AlchemyCMS/alchemy_cms/issues/407)

**Merged pull requests:**

- Changing the way of alchemy menubar rendering. [\#444](https://github.com/AlchemyCMS/alchemy_cms/pull/444) ([robinboening](https://github.com/robinboening))
- Removes the creation and dropping of alchemy\_users. [\#441](https://github.com/AlchemyCMS/alchemy_cms/pull/441) ([robinboening](https://github.com/robinboening))
- Use stable compass-rails [\#434](https://github.com/AlchemyCMS/alchemy_cms/pull/434) ([ahx](https://github.com/ahx))
- Refactors Admin::PagesController\#copy\_language\_tree and its specs. [\#429](https://github.com/AlchemyCMS/alchemy_cms/pull/429) ([robinboening](https://github.com/robinboening))
- Adds a Tasks::Helpers module to encapsulate logic from rake and capistrano tasks. [\#428](https://github.com/AlchemyCMS/alchemy_cms/pull/428) ([robinboening](https://github.com/robinboening))
- Remove html5 and flash based uploader [\#427](https://github.com/AlchemyCMS/alchemy_cms/pull/427) ([tvdeyen](https://github.com/tvdeyen))
- Refactors the clipboard\_select\_tag helper. [\#426](https://github.com/AlchemyCMS/alchemy_cms/pull/426) ([robinboening](https://github.com/robinboening))
- Removes alchemy profile for SimpleCov [\#425](https://github.com/AlchemyCMS/alchemy_cms/pull/425) ([robinboening](https://github.com/robinboening))

## [v2.7.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.7.1) (2013-11-18)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.7.0...v2.7.1)

**Closed issues:**

- No save button in imagecropper dialogue [\#420](https://github.com/AlchemyCMS/alchemy_cms/issues/420)
- TinyMCE does not work [\#419](https://github.com/AlchemyCMS/alchemy_cms/issues/419)
- Width of the 'preview window' options [\#418](https://github.com/AlchemyCMS/alchemy_cms/issues/418)
- After adding a new element with tinymce all other tinymce editors break. [\#410](https://github.com/AlchemyCMS/alchemy_cms/issues/410)
- Global page does not show locked status [\#409](https://github.com/AlchemyCMS/alchemy_cms/issues/409)
- Adding an page that redirects\_to\_external redirects to page\#edit [\#408](https://github.com/AlchemyCMS/alchemy_cms/issues/408)
- Urlname validation does not work with nested urls anymore. [\#406](https://github.com/AlchemyCMS/alchemy_cms/issues/406)
- Fix misspelled seperator options with separator. [\#405](https://github.com/AlchemyCMS/alchemy_cms/issues/405)
- Issue while integrating with rails 3.2.13 [\#404](https://github.com/AlchemyCMS/alchemy_cms/issues/404)

**Merged pull requests:**

- Adds spec for Essence\#page [\#424](https://github.com/AlchemyCMS/alchemy_cms/pull/424) ([robinboening](https://github.com/robinboening))
- Adds spec for \#clipboard\_select\_tag in admin base helper. [\#423](https://github.com/AlchemyCMS/alchemy_cms/pull/423) ([robinboening](https://github.com/robinboening))
- Removes not used methods from admin base\_helper. [\#422](https://github.com/AlchemyCMS/alchemy_cms/pull/422) ([robinboening](https://github.com/robinboening))
- Adds specs for Admin::EssencesHelper\#essence\_picture\_thumbnail [\#421](https://github.com/AlchemyCMS/alchemy_cms/pull/421) ([robinboening](https://github.com/robinboening))
- Page\#sitemap scope now depends on the current site. [\#417](https://github.com/AlchemyCMS/alchemy_cms/pull/417) ([robinboening](https://github.com/robinboening))
- Page\#sitemap scope now depends on the current site. [\#416](https://github.com/AlchemyCMS/alchemy_cms/pull/416) ([robinboening](https://github.com/robinboening))
- Includes admin base\_helper to attachments\_helper and adds specs. [\#415](https://github.com/AlchemyCMS/alchemy_cms/pull/415) ([robinboening](https://github.com/robinboening))
- Adds specs for admin pages\_helper\#combined\_page\_status method. [\#414](https://github.com/AlchemyCMS/alchemy_cms/pull/414) ([robinboening](https://github.com/robinboening))
- Adds specs for admin pictures helper. [\#413](https://github.com/AlchemyCMS/alchemy_cms/pull/413) ([robinboening](https://github.com/robinboening))
- Removes deprecated helper methods. [\#412](https://github.com/AlchemyCMS/alchemy_cms/pull/412) ([robinboening](https://github.com/robinboening))

## [v2.7.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.7.0) (2013-10-16)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.6.2.1...v2.7.0)

**Closed issues:**

- Custom TinyMCE settings should not depend on a unique name across elements [\#400](https://github.com/AlchemyCMS/alchemy_cms/issues/400)
- Admin UI hangs when presence validation fails [\#399](https://github.com/AlchemyCMS/alchemy_cms/issues/399)
- Calling Hotkeys creator several times defines multiple hotkey callbacks [\#395](https://github.com/AlchemyCMS/alchemy_cms/issues/395)
- Dashboard: Last edited pages should be scoped on current site. [\#392](https://github.com/AlchemyCMS/alchemy_cms/issues/392)
- no attribute "slug" for in Page model in 2.6-stable branch [\#389](https://github.com/AlchemyCMS/alchemy_cms/issues/389)
- Saving pasted element from clipboard shows error "Validierung von Position ist bereits vergeben ist fehlgeschlagen" [\#388](https://github.com/AlchemyCMS/alchemy_cms/issues/388)
- Getting Alchemy not mounted warning when using alchemy new  [\#387](https://github.com/AlchemyCMS/alchemy_cms/issues/387)
- elements.yml being read multiple times [\#386](https://github.com/AlchemyCMS/alchemy_cms/issues/386)
- Image overlay layout breaks on small image preview size [\#382](https://github.com/AlchemyCMS/alchemy_cms/issues/382)
- Switch from selectboxit to select2 [\#380](https://github.com/AlchemyCMS/alchemy_cms/issues/380)
- Add the\_sortable\_tree as page sorting handler [\#372](https://github.com/AlchemyCMS/alchemy_cms/issues/372)
- Add configurable cache\_key [\#368](https://github.com/AlchemyCMS/alchemy_cms/issues/368)
- Add a mailto link option to link overlay [\#283](https://github.com/AlchemyCMS/alchemy_cms/issues/283)
- Sanity Check, Sanitizer [\#280](https://github.com/AlchemyCMS/alchemy_cms/issues/280)
- versioning for contents [\#277](https://github.com/AlchemyCMS/alchemy_cms/issues/277)
- Inplace editor while browsing in logged in state [\#276](https://github.com/AlchemyCMS/alchemy_cms/issues/276)
- Element views should be cached. [\#275](https://github.com/AlchemyCMS/alchemy_cms/issues/275)
- \[Feature\] Add dropbox support. [\#254](https://github.com/AlchemyCMS/alchemy_cms/issues/254)
- Disabled buttons should have a timeout and retry feature [\#196](https://github.com/AlchemyCMS/alchemy_cms/issues/196)
- Implement containers \(draggable cells\) [\#170](https://github.com/AlchemyCMS/alchemy_cms/issues/170)
- Add a draft mode for pages [\#141](https://github.com/AlchemyCMS/alchemy_cms/issues/141)
- pages are public-readable when language is not public [\#101](https://github.com/AlchemyCMS/alchemy_cms/issues/101)
- Make settings accessible via gui [\#86](https://github.com/AlchemyCMS/alchemy_cms/issues/86)
- Permit page access per user [\#33](https://github.com/AlchemyCMS/alchemy_cms/issues/33)
- undeletable pages depending on the page\_layout [\#25](https://github.com/AlchemyCMS/alchemy_cms/issues/25)
- Sister pages for page in other languages [\#24](https://github.com/AlchemyCMS/alchemy_cms/issues/24)
- Add a backup module [\#21](https://github.com/AlchemyCMS/alchemy_cms/issues/21)
- Mark Page as deleted instead of deleting it [\#14](https://github.com/AlchemyCMS/alchemy_cms/issues/14)

**Merged pull requests:**

- Fix custom TinyMCE init selectors [\#402](https://github.com/AlchemyCMS/alchemy_cms/pull/402) ([wuservices](https://github.com/wuservices))
- Refactors picture filtering in admin backend and adds specs. [\#398](https://github.com/AlchemyCMS/alchemy_cms/pull/398) ([robinboening](https://github.com/robinboening))
- Scopes last edited pages in admin/dashboard to current site. Closes \#392 [\#393](https://github.com/AlchemyCMS/alchemy_cms/pull/393) ([robinboening](https://github.com/robinboening))

## [v2.6.2.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.6.2.1) (2013-06-14)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.6.2...v2.6.2.1)

## [v2.6.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.6.2) (2013-06-14)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.6.1...v2.6.2)

## [v2.6.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.6.1) (2013-06-04)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.6.0...v2.6.1)

**Closed issues:**

- Sort tags alphabetical [\#383](https://github.com/AlchemyCMS/alchemy_cms/issues/383)

**Merged pull requests:**

- Adds specs and removes unused code [\#381](https://github.com/AlchemyCMS/alchemy_cms/pull/381) ([robinboening](https://github.com/robinboening))
- Fixes :from\_page option of render\_navigation helper. Adds specs. [\#379](https://github.com/AlchemyCMS/alchemy_cms/pull/379) ([robinboening](https://github.com/robinboening))

## [v2.6.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.6.0) (2013-05-14)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.6.0.rc5...v2.6.0)

**Closed issues:**

- Add more useful keyboard shortcuts [\#374](https://github.com/AlchemyCMS/alchemy_cms/issues/374)

## [v2.6.0.rc5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.6.0.rc5) (2013-04-30)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.3.1...v2.6.0.rc5)

## [v2.5.3.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.3.1) (2013-04-19)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.3...v2.5.3.1)

**Closed issues:**

- Pictures must not have full url [\#375](https://github.com/AlchemyCMS/alchemy_cms/issues/375)
- Add a page filter for admin sitemap [\#373](https://github.com/AlchemyCMS/alchemy_cms/issues/373)
- `render\_navigation` helper should not display restricted pages [\#371](https://github.com/AlchemyCMS/alchemy_cms/issues/371)
- Resource views enhancements [\#364](https://github.com/AlchemyCMS/alchemy_cms/issues/364)
- File archive should also have a tag list sidebar [\#363](https://github.com/AlchemyCMS/alchemy_cms/issues/363)
- declarative authorization: using\_access\_control in models [\#330](https://github.com/AlchemyCMS/alchemy_cms/issues/330)
- Alchemy::Resource does not work with namespaced model names [\#303](https://github.com/AlchemyCMS/alchemy_cms/issues/303)
- resource relations should be searchable [\#290](https://github.com/AlchemyCMS/alchemy_cms/issues/290)
- Resolution independent GUI [\#263](https://github.com/AlchemyCMS/alchemy_cms/issues/263)
- Link Overlay does not support url nesting yet [\#143](https://github.com/AlchemyCMS/alchemy_cms/issues/143)

**Merged pull requests:**

- Resource with namespace [\#370](https://github.com/AlchemyCMS/alchemy_cms/pull/370) ([masche842](https://github.com/masche842))

## [v2.5.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.3) (2013-03-21)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.2.2...v2.5.3)

## [v2.5.2.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.2.2) (2013-03-20)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.2.1...v2.5.2.2)

## [v2.5.2.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.2.1) (2013-03-14)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.2...v2.5.2.1)

## [v2.5.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.2) (2013-03-12)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.1...v2.5.2)

**Closed issues:**

- Issue with current page caching [\#366](https://github.com/AlchemyCMS/alchemy_cms/issues/366)
- Replace jQuery UI icons with a icon font. [\#362](https://github.com/AlchemyCMS/alchemy_cms/issues/362)
- Use dragonfly for attachments [\#361](https://github.com/AlchemyCMS/alchemy_cms/issues/361)
- broken external link generation [\#359](https://github.com/AlchemyCMS/alchemy_cms/issues/359)
- Add a sortable table for resources [\#122](https://github.com/AlchemyCMS/alchemy_cms/issues/122)

**Merged pull requests:**

- Use Attachment.file\_name in \_file\_to\_assign.html.erb [\#367](https://github.com/AlchemyCMS/alchemy_cms/pull/367) ([pascalj](https://github.com/pascalj))

## [v2.5.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.1) (2013-02-18)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.0...v2.5.1)

**Closed issues:**

- If ":image\_float\_selector =\> false" it's still be shown in the editor view [\#357](https://github.com/AlchemyCMS/alchemy_cms/issues/357)
- Image floats selector css class has to be on the figure element [\#356](https://github.com/AlchemyCMS/alchemy_cms/issues/356)
- NoMethodError undefined method `cropped\_thumbnail\_size' for nil:NilClass [\#355](https://github.com/AlchemyCMS/alchemy_cms/issues/355)
- Daypicker does not save date in Chrome Version 24.0.1312.56 [\#353](https://github.com/AlchemyCMS/alchemy_cms/issues/353)
- Set `.from\_current\_site` as default\_scope on `Page` and `Element` [\#351](https://github.com/AlchemyCMS/alchemy_cms/issues/351)

**Merged pull requests:**

- Fix for upgrader and migrations   [\#483](https://github.com/AlchemyCMS/alchemy_cms/pull/483) ([nielspetersen](https://github.com/nielspetersen))
- cleaning current\_server\_helper\_method [\#358](https://github.com/AlchemyCMS/alchemy_cms/pull/358) ([skeller1](https://github.com/skeller1))

## [v2.5.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.0) (2013-02-01)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.0.rc4...v2.5.0)

## [v2.5.0.rc4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.0.rc4) (2013-01-31)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.0.rc3...v2.5.0.rc4)

## [v2.5.0.rc3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.0.rc3) (2013-01-30)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.0.b9...v2.5.0.rc3)

**Closed issues:**

- When copying a page, the autogenerate mechanism should be skipped. [\#350](https://github.com/AlchemyCMS/alchemy_cms/issues/350)
- Alchemy::Element.available needs scope to site [\#343](https://github.com/AlchemyCMS/alchemy_cms/issues/343)
- Page.language\_roots and Page.public\_language\_roots scopes does not respect the current site [\#340](https://github.com/AlchemyCMS/alchemy_cms/issues/340)

**Merged pull requests:**

- Fixes two issues [\#352](https://github.com/AlchemyCMS/alchemy_cms/pull/352) ([robinboening](https://github.com/robinboening))

## [v2.5.0.b9](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.0.b9) (2013-01-18)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.4...v2.5.0.b9)

**Closed issues:**

- Fix Install message [\#349](https://github.com/AlchemyCMS/alchemy_cms/issues/349)
- Save every link inside of Elements [\#31](https://github.com/AlchemyCMS/alchemy_cms/issues/31)

**Merged pull requests:**

- Some minor changes... [\#348](https://github.com/AlchemyCMS/alchemy_cms/pull/348) ([robinboening](https://github.com/robinboening))

## [v2.2.4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.4) (2013-01-10)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.3.2...v2.2.4)

## [v2.3.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.3.2) (2013-01-10)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.4.1...v2.3.2)

## [v2.4.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.4.1) (2013-01-10)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.0.b5...v2.4.1)

**Closed issues:**

- Cap task alchemy:import:pictures should use rsync [\#346](https://github.com/AlchemyCMS/alchemy_cms/issues/346)
- Sites need multiple hosts.  [\#342](https://github.com/AlchemyCMS/alchemy_cms/issues/342)

## [v2.5.0.b5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.0.b5) (2012-12-20)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.5.0.b2...v2.5.0.b5)

**Closed issues:**

- Adding a build in help system [\#121](https://github.com/AlchemyCMS/alchemy_cms/issues/121)

**Merged pull requests:**

- Introduce host aliases for sites. [\#345](https://github.com/AlchemyCMS/alchemy_cms/pull/345) ([hmans](https://github.com/hmans))

## [v2.5.0.b2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.5.0.b2) (2012-12-14)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.4.0...v2.5.0.b2)

**Closed issues:**

- JS event listener not set after unfolding pages [\#341](https://github.com/AlchemyCMS/alchemy_cms/issues/341)
- Sites can not be updated [\#339](https://github.com/AlchemyCMS/alchemy_cms/issues/339)
- bad links in readme [\#338](https://github.com/AlchemyCMS/alchemy_cms/issues/338)
- Multisite: when creating a new site, it should automatically create the default language for it. [\#336](https://github.com/AlchemyCMS/alchemy_cms/issues/336)
- Do not allow to delete pictures from library that are assigned to an essence picture [\#335](https://github.com/AlchemyCMS/alchemy_cms/issues/335)
- Wrong image file format validation [\#333](https://github.com/AlchemyCMS/alchemy_cms/issues/333)
- rake alchemy:upgrade does not work with sqlite [\#321](https://github.com/AlchemyCMS/alchemy_cms/issues/321)

**Merged pull requests:**

- Add multisite support. [\#332](https://github.com/AlchemyCMS/alchemy_cms/pull/332) ([hmans](https://github.com/hmans))
- Includes UrlHelper and ElementsBlockHelper in ElementsHelper. [\#327](https://github.com/AlchemyCMS/alchemy_cms/pull/327) ([robinboening](https://github.com/robinboening))
- Use an ActiveRecord connection instead of Mysql2 provider in order to up... [\#322](https://github.com/AlchemyCMS/alchemy_cms/pull/322) ([masche842](https://github.com/masche842))

## [v2.4.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.4.0) (2012-12-01)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.4.rc4...v2.4.0)

## [v2.4.rc4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.4.rc4) (2012-11-30)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.4.rc2...v2.4.rc4)

**Closed issues:**

- Page\#create without choosing page\_layout raises exception [\#318](https://github.com/AlchemyCMS/alchemy_cms/issues/318)
- Copy element/page should also copy its tags [\#316](https://github.com/AlchemyCMS/alchemy_cms/issues/316)

**Merged pull requests:**

- Added spec for picture cropping [\#323](https://github.com/AlchemyCMS/alchemy_cms/pull/323) ([robinboening](https://github.com/robinboening))

## [v2.4.rc2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.4.rc2) (2012-11-23)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.4.rc1...v2.4.rc2)

**Closed issues:**

- Error when pasting element on page´s main cell [\#314](https://github.com/AlchemyCMS/alchemy_cms/issues/314)
- Newly filled cells display without editor content [\#313](https://github.com/AlchemyCMS/alchemy_cms/issues/313)
- Controlling selectbox via keyboard does not highlight entry [\#311](https://github.com/AlchemyCMS/alchemy_cms/issues/311)
- Alternative template engine support for generators [\#296](https://github.com/AlchemyCMS/alchemy_cms/issues/296)

**Merged pull requests:**

- Fix for Issue \#314 \(Error when pasting element on page´s main cell\) [\#315](https://github.com/AlchemyCMS/alchemy_cms/pull/315) ([robinboening](https://github.com/robinboening))

## [v2.4.rc1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.4.rc1) (2012-11-20)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.3.1...v2.4.rc1)

## [v2.3.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.3.1) (2012-11-19)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.4.beta2...v2.3.1)

**Closed issues:**

- Picture cropping: Values should not be floats, must be integers [\#302](https://github.com/AlchemyCMS/alchemy_cms/issues/302)
- Add a protocol validation for external links [\#285](https://github.com/AlchemyCMS/alchemy_cms/issues/285)

**Merged pull requests:**

- Enabled 'rails' mode for SimpleCov. [\#305](https://github.com/AlchemyCMS/alchemy_cms/pull/305) ([hmans](https://github.com/hmans))

## [v2.4.beta2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.4.beta2) (2012-11-08)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.3.2...v2.4.beta2)

**Closed issues:**

- Getting started instructions don't work. [\#297](https://github.com/AlchemyCMS/alchemy_cms/issues/297)
- Security concerns with image processing [\#295](https://github.com/AlchemyCMS/alchemy_cms/issues/295)
- Compress migrations [\#294](https://github.com/AlchemyCMS/alchemy_cms/issues/294)
- install w existing project - migrate =\> Table 'users' already exists:  [\#293](https://github.com/AlchemyCMS/alchemy_cms/issues/293)
- I18n.locale should be set from @language [\#292](https://github.com/AlchemyCMS/alchemy_cms/issues/292)
- Pasting an element from clipboard [\#291](https://github.com/AlchemyCMS/alchemy_cms/issues/291)
- Misspositioned toolbar when access to module is restricted [\#289](https://github.com/AlchemyCMS/alchemy_cms/issues/289)
- Do not use ruby-debug19 in alchemy project template [\#287](https://github.com/AlchemyCMS/alchemy_cms/issues/287)
- Elements can't be in cell and main content at the same time [\#286](https://github.com/AlchemyCMS/alchemy_cms/issues/286)
- Mass-assignment issue on alchemy\_cms 2.2 stable [\#284](https://github.com/AlchemyCMS/alchemy_cms/issues/284)
- Drop Ruby 1.8 support [\#269](https://github.com/AlchemyCMS/alchemy_cms/issues/269)
- Clickable configuration for "public", "navigation", "restricted" in page overview \(and everywhere else...\) [\#247](https://github.com/AlchemyCMS/alchemy_cms/issues/247)
- Add a deploy and or pack task into alchemy executable [\#241](https://github.com/AlchemyCMS/alchemy_cms/issues/241)
- sb \(selectbox\) shouldn't be applied automatically on selects in the backend [\#162](https://github.com/AlchemyCMS/alchemy_cms/issues/162)
- Add a essence generator [\#142](https://github.com/AlchemyCMS/alchemy_cms/issues/142)
- Configurable element insert postition [\#135](https://github.com/AlchemyCMS/alchemy_cms/issues/135)
- ElementsHelper\#render\_elements fallback from option should take a Page object [\#107](https://github.com/AlchemyCMS/alchemy_cms/issues/107)
- Filter in Element window [\#29](https://github.com/AlchemyCMS/alchemy_cms/issues/29)
- Refactor Clipboard's GUI to behave like the Trash [\#27](https://github.com/AlchemyCMS/alchemy_cms/issues/27)
- A user should be able to change the page\_layout of a page  [\#26](https://github.com/AlchemyCMS/alchemy_cms/issues/26)
- Implement an Installation Controller [\#23](https://github.com/AlchemyCMS/alchemy_cms/issues/23)
- Load Cell.elements via remote [\#17](https://github.com/AlchemyCMS/alchemy_cms/issues/17)
- Do not immediately save after changing order of pictures in picture editor [\#12](https://github.com/AlchemyCMS/alchemy_cms/issues/12)
- Admin Area should be SSL protectable [\#2](https://github.com/AlchemyCMS/alchemy_cms/issues/2)

**Merged pull requests:**

- Add support for Haml and Slim. [\#310](https://github.com/AlchemyCMS/alchemy_cms/pull/310) ([hmans](https://github.com/hmans))
- New feature and some specs [\#301](https://github.com/AlchemyCMS/alchemy_cms/pull/301) ([robinboening](https://github.com/robinboening))
- Fixes generation of invalid HTML if subnavigation-entry is not allowed f... [\#299](https://github.com/AlchemyCMS/alchemy_cms/pull/299) ([masche842](https://github.com/masche842))
- Fixes security issue with role-attribute [\#298](https://github.com/AlchemyCMS/alchemy_cms/pull/298) ([masche842](https://github.com/masche842))

## [v2.2.3.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.3.2) (2012-09-19)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.3.1...v2.2.3.2)

## [v2.2.3.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.3.1) (2012-09-19)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.3...v2.2.3.1)

## [v2.2.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.3) (2012-09-19)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.12...v2.2.3)

## [v2.1.12](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.12) (2012-09-14)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.3.0...v2.1.12)

## [v2.3.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.3.0) (2012-09-12)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.3.rc5...v2.3.0)

## [v2.3.rc5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.3.rc5) (2012-09-07)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.2...v2.3.rc5)

**Closed issues:**

- Error when saving \(without editing before\) an element that contains an EssenceBoolean [\#282](https://github.com/AlchemyCMS/alchemy_cms/issues/282)
- undefined method `merge\_conditions' for Page [\#281](https://github.com/AlchemyCMS/alchemy_cms/issues/281)
- Restoring trashed elements to nil cell does not work [\#279](https://github.com/AlchemyCMS/alchemy_cms/issues/279)
- Restoring unique elements from trash does not work [\#278](https://github.com/AlchemyCMS/alchemy_cms/issues/278)
- reinitialize javascript selectboxes after unfolding elements [\#274](https://github.com/AlchemyCMS/alchemy_cms/issues/274)
- Trashing/untrashing/moving elements is currently broken [\#273](https://github.com/AlchemyCMS/alchemy_cms/issues/273)
- Pages that redirect to external shouldn't be linkable [\#272](https://github.com/AlchemyCMS/alchemy_cms/issues/272)
- After uploading an image deleting fails [\#271](https://github.com/AlchemyCMS/alchemy_cms/issues/271)
- Add a mass delete feature for pictures in the archive. [\#270](https://github.com/AlchemyCMS/alchemy_cms/issues/270)
- Make `Attachment.filename` editable through user [\#260](https://github.com/AlchemyCMS/alchemy_cms/issues/260)
- alchemy-selectbox not accessible [\#257](https://github.com/AlchemyCMS/alchemy_cms/issues/257)
- Autogenerating elements when using cells will always create the elements in the main cell [\#232](https://github.com/AlchemyCMS/alchemy_cms/issues/232)
- Restricted files \(file upload\) [\#145](https://github.com/AlchemyCMS/alchemy_cms/issues/145)
- Add a translation select into admin views [\#126](https://github.com/AlchemyCMS/alchemy_cms/issues/126)
- Folders for files and pictures in the archive [\#30](https://github.com/AlchemyCMS/alchemy_cms/issues/30)

## [v2.2.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.2) (2012-07-07)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.1...v2.2.2)

**Closed issues:**

- New-Page overlay opens in blank window without Layout [\#266](https://github.com/AlchemyCMS/alchemy_cms/issues/266)
- Needless class-method? \(PageLayout.get\_page\_layout\_names\) [\#258](https://github.com/AlchemyCMS/alchemy_cms/issues/258)

## [v2.2.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.1) (2012-06-26)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.0...v2.2.1)

**Closed issues:**

- Faulty route in backend for external-redirect-pages [\#259](https://github.com/AlchemyCMS/alchemy_cms/issues/259)
- convention over configuration: backend stylesheets and javascripts [\#161](https://github.com/AlchemyCMS/alchemy_cms/issues/161)

**Merged pull requests:**

- Reduce travis-ci.org build matrix, per discussion in \#264 [\#265](https://github.com/AlchemyCMS/alchemy_cms/pull/265) ([michaelklishin](https://github.com/michaelklishin))

## [v2.2.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.0) (2012-06-25)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc15...v2.2.0)

**Merged pull requests:**

- added page\_layout-name as class for page-item in sitemap [\#262](https://github.com/AlchemyCMS/alchemy_cms/pull/262) ([masche842](https://github.com/masche842))
- custom stylesheets and javascripts for alchemy-backend via require\_tree [\#261](https://github.com/AlchemyCMS/alchemy_cms/pull/261) ([masche842](https://github.com/masche842))

## [v2.2.rc15](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc15) (2012-06-18)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc14...v2.2.rc15)

**Closed issues:**

- problems with elements = nil in page.rb [\#252](https://github.com/AlchemyCMS/alchemy_cms/issues/252)
- Update Page, if page\_layouts.yml was changed [\#28](https://github.com/AlchemyCMS/alchemy_cms/issues/28)

**Merged pull requests:**

- Message will now validate confirmation of :email if a field named :email\_confirmation is present. [\#256](https://github.com/AlchemyCMS/alchemy_cms/pull/256) ([hmans](https://github.com/hmans))
- fixes route for custom controller [\#253](https://github.com/AlchemyCMS/alchemy_cms/pull/253) ([masche842](https://github.com/masche842))

## [v2.2.rc14](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc14) (2012-06-11)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc13...v2.2.rc14)

**Closed issues:**

- Clipboard-Controller: undefined method contains? for Hash [\#250](https://github.com/AlchemyCMS/alchemy_cms/issues/250)
- Faulty page when picture is assigned after ajax-actions [\#249](https://github.com/AlchemyCMS/alchemy_cms/issues/249)
- Missing extension .erb for /views/alchemy/admin/pages/destroy... [\#248](https://github.com/AlchemyCMS/alchemy_cms/issues/248)
- Entities in Ajax-Responds are escaped \(i.e. after configuring a page\) [\#246](https://github.com/AlchemyCMS/alchemy_cms/issues/246)
- Add EssenceBoolean and EssenceSelect [\#245](https://github.com/AlchemyCMS/alchemy_cms/issues/245)
- EssencePicture create button is always added after destroy [\#243](https://github.com/AlchemyCMS/alchemy_cms/issues/243)

## [v2.2.rc13](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc13) (2012-06-03)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc11...v2.2.rc13)

**Closed issues:**

- TinyMCE adjustable per element´s content [\#244](https://github.com/AlchemyCMS/alchemy_cms/issues/244)
- Two post request while creating a page [\#242](https://github.com/AlchemyCMS/alchemy_cms/issues/242)
- Hide edit button if picture is newly assigned [\#239](https://github.com/AlchemyCMS/alchemy_cms/issues/239)
- Prevent adding multiple pictures to element by quick double clicking [\#20](https://github.com/AlchemyCMS/alchemy_cms/issues/20)

## [v2.2.rc11](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc11) (2012-05-29)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc8...v2.2.rc11)

**Closed issues:**

- Page\#creator\_id and updater\_id are always nil [\#233](https://github.com/AlchemyCMS/alchemy_cms/issues/233)
- alchemy executable fails to create a new site [\#231](https://github.com/AlchemyCMS/alchemy_cms/issues/231)
- Resource integration test sometimes fails on travis-ci [\#229](https://github.com/AlchemyCMS/alchemy_cms/issues/229)
- already initialized constant SKIP\_ATTRIBUTES in resource\_spec [\#228](https://github.com/AlchemyCMS/alchemy_cms/issues/228)
- Saving a page should sweep the cache from contents that are set to display\_as: select [\#226](https://github.com/AlchemyCMS/alchemy_cms/issues/226)
- Error-Message when element is missing in elements.yml [\#225](https://github.com/AlchemyCMS/alchemy_cms/issues/225)
- Title for upload-picture link should change by context [\#173](https://github.com/AlchemyCMS/alchemy_cms/issues/173)
- Documentation: list all available css-classes and icons [\#163](https://github.com/AlchemyCMS/alchemy_cms/issues/163)

**Merged pull requests:**

- Fix for \#233 [\#240](https://github.com/AlchemyCMS/alchemy_cms/pull/240) ([pascalj](https://github.com/pascalj))
- Include \#attachment\_id in list of white-listed attributes for EssenceFile [\#238](https://github.com/AlchemyCMS/alchemy_cms/pull/238) ([hmans](https://github.com/hmans))
- Fix for \#173 [\#236](https://github.com/AlchemyCMS/alchemy_cms/pull/236) ([masche842](https://github.com/masche842))
- Skip attributes, fixes \#228 [\#235](https://github.com/AlchemyCMS/alchemy_cms/pull/235) ([masche842](https://github.com/masche842))
- pull req for comment update in elements.yml [\#234](https://github.com/AlchemyCMS/alchemy_cms/pull/234) ([marcheidemann](https://github.com/marcheidemann))

## [v2.2.rc8](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc8) (2012-04-27)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc7...v2.2.rc8)

## [v2.2.rc7](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc7) (2012-04-27)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.9.1...v2.2.rc7)

**Closed issues:**

- Postgre-Compatibility [\#218](https://github.com/AlchemyCMS/alchemy_cms/issues/218)
- load\_page methods searches for alternative Page of other Language [\#210](https://github.com/AlchemyCMS/alchemy_cms/issues/210)
- Incorrect Links in Main-Navigation for custom Module [\#201](https://github.com/AlchemyCMS/alchemy_cms/issues/201)
- Dont cache page if it acts as a searchresult page [\#112](https://github.com/AlchemyCMS/alchemy_cms/issues/112)
- offset option for render\_elements helper [\#15](https://github.com/AlchemyCMS/alchemy_cms/issues/15)

**Merged pull requests:**

- fixes: reload sitemap after page has been deleted in english version [\#230](https://github.com/AlchemyCMS/alchemy_cms/pull/230) ([masche842](https://github.com/masche842))
- Fix for \#201 [\#227](https://github.com/AlchemyCMS/alchemy_cms/pull/227) ([masche842](https://github.com/masche842))

## [v2.1.9.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.9.1) (2012-04-17)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.9...v2.1.9.1)

**Closed issues:**

- Make Alchemy ready for Deployment in sub-URIs [\#220](https://github.com/AlchemyCMS/alchemy_cms/issues/220)

## [v2.1.9](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.9) (2012-04-13)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc6...v2.1.9)

## [v2.2.rc6](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc6) (2012-04-13)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.8.1...v2.2.rc6)

**Closed issues:**

- Alchemy2.2.rc3 / ruby 1.9.3 - rake alchemy:db:seed leads to: [\#224](https://github.com/AlchemyCMS/alchemy_cms/issues/224)

## [v2.1.8.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.8.1) (2012-04-11)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc3...v2.1.8.1)

## [v2.2.rc3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc3) (2012-04-11)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc2...v2.2.rc3)

**Closed issues:**

- Maximum count of elements per page\_layout [\#187](https://github.com/AlchemyCMS/alchemy_cms/issues/187)

## [v2.2.rc2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc2) (2012-04-06)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.2.rc1...v2.2.rc2)

## [v2.2.rc1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.2.rc1) (2012-04-06)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.8...v2.2.rc1)

## [v2.1.8](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.8) (2012-04-06)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.7...v2.1.8)

**Closed issues:**

- Hidden page\_layouts are displayed to the user [\#222](https://github.com/AlchemyCMS/alchemy_cms/issues/222)
- Switch back to soft-tabs [\#215](https://github.com/AlchemyCMS/alchemy_cms/issues/215)
- better page\_layout-default in new-language-form [\#207](https://github.com/AlchemyCMS/alchemy_cms/issues/207)
- Error when adding "available" content to element dynamically [\#206](https://github.com/AlchemyCMS/alchemy_cms/issues/206)
- :as-attribute in resources controller doesn't work [\#204](https://github.com/AlchemyCMS/alchemy_cms/issues/204)
- SEGFAULT In pictures\_controller for picture uploading [\#186](https://github.com/AlchemyCMS/alchemy_cms/issues/186)
- Desperately looking for a commented, designer-fit standard-template [\#165](https://github.com/AlchemyCMS/alchemy_cms/issues/165)

**Merged pull requests:**

- Respect the "hide" flag of page\_layouts. [\#223](https://github.com/AlchemyCMS/alchemy_cms/pull/223) ([pascalj](https://github.com/pascalj))
- Documented standard set, related to \#165 [\#217](https://github.com/AlchemyCMS/alchemy_cms/pull/217) ([masche842](https://github.com/masche842))
- Coffee script [\#216](https://github.com/AlchemyCMS/alchemy_cms/pull/216) ([masche842](https://github.com/masche842))
- Zoom picture fix [\#214](https://github.com/AlchemyCMS/alchemy_cms/pull/214) ([masche842](https://github.com/masche842))
- Default page layout when creating languages [\#213](https://github.com/AlchemyCMS/alchemy_cms/pull/213) ([masche842](https://github.com/masche842))
- changed 404-action in order to allow custom, dynamic error-pages [\#212](https://github.com/AlchemyCMS/alchemy_cms/pull/212) ([masche842](https://github.com/masche842))
- generalize credential-invalid-message to improve security [\#211](https://github.com/AlchemyCMS/alchemy_cms/pull/211) ([masche842](https://github.com/masche842))
- converted link\_overlay into coffee-script syntax [\#209](https://github.com/AlchemyCMS/alchemy_cms/pull/209) ([masche842](https://github.com/masche842))
- Fixes next stable [\#208](https://github.com/AlchemyCMS/alchemy_cms/pull/208) ([masche842](https://github.com/masche842))

## [v2.1.7](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.7) (2012-03-13)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.7b...v2.1.7)

## [v2.1.7b](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.7b) (2012-03-13)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.6...v2.1.7b)

**Closed issues:**

- Validation failing when saving Page if its urlname exists also in global pages scope [\#205](https://github.com/AlchemyCMS/alchemy_cms/issues/205)
- render\_elements :from\_cell =\> cell, :only =\> "element\_name" ignores given cell [\#198](https://github.com/AlchemyCMS/alchemy_cms/issues/198)
- rake routes aborts with 'can't convert Regexp to String' [\#193](https://github.com/AlchemyCMS/alchemy_cms/issues/193)
- Add multi domain support [\#156](https://github.com/AlchemyCMS/alchemy_cms/issues/156)
- Cache the configuration [\#137](https://github.com/AlchemyCMS/alchemy_cms/issues/137)
- Dynamically added contents should have a delete button [\#127](https://github.com/AlchemyCMS/alchemy_cms/issues/127)
- Add a Flashless HTML5 multiple file uploader [\#120](https://github.com/AlchemyCMS/alchemy_cms/issues/120)
- Increase Sitemap Performance [\#32](https://github.com/AlchemyCMS/alchemy_cms/issues/32)

**Merged pull requests:**

- fix for elements generator to allow empty elements [\#203](https://github.com/AlchemyCMS/alchemy_cms/pull/203) ([masche842](https://github.com/masche842))
- Fixes PathNotFound for zoom\_picture\_path when crop is active [\#202](https://github.com/AlchemyCMS/alchemy_cms/pull/202) ([masche842](https://github.com/masche842))
- more namespaced selectboxes [\#200](https://github.com/AlchemyCMS/alchemy_cms/pull/200) ([masche842](https://github.com/masche842))
- Refactored resource capabilities [\#199](https://github.com/AlchemyCMS/alchemy_cms/pull/199) ([masche842](https://github.com/masche842))
- specify partial-path, otherwise MissingPartial error is raised [\#197](https://github.com/AlchemyCMS/alchemy_cms/pull/197) ([masche842](https://github.com/masche842))

## [v2.1.6](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.6) (2012-02-22)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.5...v2.1.6)

**Closed issues:**

- When saving a Page the title will always be resetted to Page\#name [\#192](https://github.com/AlchemyCMS/alchemy_cms/issues/192)
- Copying Element living in a Cell throws error [\#189](https://github.com/AlchemyCMS/alchemy_cms/issues/189)
- Aborting Picture upload from Page\#edit redirects to /admin/pictures [\#188](https://github.com/AlchemyCMS/alchemy_cms/issues/188)

## [v2.1.5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.5) (2012-02-17)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.4...v2.1.5)

**Closed issues:**

- Remove the width and height styles on picture essence views [\#182](https://github.com/AlchemyCMS/alchemy_cms/issues/182)
- Add a option for enabling the please wait overlay for alchemy toolbar buttons [\#167](https://github.com/AlchemyCMS/alchemy_cms/issues/167)

**Merged pull requests:**

- Deleted deprecations from rails 3.2.1 update \(spec. format and handler in names\) [\#185](https://github.com/AlchemyCMS/alchemy_cms/pull/185) ([SweeD](https://github.com/SweeD))
- jquery-rails version bumped to 2.0.0 for rails 3.2.1 [\#184](https://github.com/AlchemyCMS/alchemy_cms/pull/184) ([SweeD](https://github.com/SweeD))
- Gemspec fleximage with path spec [\#183](https://github.com/AlchemyCMS/alchemy_cms/pull/183) ([SweeD](https://github.com/SweeD))

## [v2.1.4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.4) (2012-02-10)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.3...v2.1.4)

**Closed issues:**

- Better information when javascript is disabled [\#181](https://github.com/AlchemyCMS/alchemy_cms/issues/181)
- Creating Page will create it twice in the same language-tree [\#180](https://github.com/AlchemyCMS/alchemy_cms/issues/180)
- Error when assigning a file to a content of type EssenceFile [\#179](https://github.com/AlchemyCMS/alchemy_cms/issues/179)
- Cleaning picture cache in library not working [\#178](https://github.com/AlchemyCMS/alchemy_cms/issues/178)
- Sorting pages to root "hides" them from page-tree [\#177](https://github.com/AlchemyCMS/alchemy_cms/issues/177)

## [v2.1.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.3) (2012-02-06)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.2...v2.1.3)

**Closed issues:**

- Security issue in resource-controller [\#176](https://github.com/AlchemyCMS/alchemy_cms/issues/176)
- Copying page-tree throws error [\#175](https://github.com/AlchemyCMS/alchemy_cms/issues/175)
- No "create language tree"-Button if non-de is the only language [\#174](https://github.com/AlchemyCMS/alchemy_cms/issues/174)
- A EssencePicture should also be editable standalone [\#171](https://github.com/AlchemyCMS/alchemy_cms/issues/171)
- EssenceDate should be a jQuery UI Datepicker [\#118](https://github.com/AlchemyCMS/alchemy_cms/issues/118)

## [v2.1.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.2) (2012-02-01)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.1...v2.1.2)

**Closed issues:**

- Negative values for EssencePicture\#crop\_from after cropping small images [\#172](https://github.com/AlchemyCMS/alchemy_cms/issues/172)

## [v2.1.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.1) (2012-01-28)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1...v2.1.1)

## [v2.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1) (2012-01-27)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.rc6...v2.1)

**Closed issues:**

- Wrong translation in logout-overlay if no default locale set [\#169](https://github.com/AlchemyCMS/alchemy_cms/issues/169)
- Attachments: File type is always document [\#168](https://github.com/AlchemyCMS/alchemy_cms/issues/168)
- ugly layering between main menu and leave-button in backend... [\#166](https://github.com/AlchemyCMS/alchemy_cms/issues/166)
- ResourcesController: Permissions not working [\#164](https://github.com/AlchemyCMS/alchemy_cms/issues/164)
- Closing opened pages via dashboard redirects to localhost:3000//admin/dashboard [\#160](https://github.com/AlchemyCMS/alchemy_cms/issues/160)
- Default 'overlay =\> true' in base\_helper/toolbar\_button results in Error when no Overlay-Options are given [\#159](https://github.com/AlchemyCMS/alchemy_cms/issues/159)
- Errors in alchemy-managed resources residing in main app [\#149](https://github.com/AlchemyCMS/alchemy_cms/issues/149)
- Flagging pages that are not holding content \(systempages\) [\#108](https://github.com/AlchemyCMS/alchemy_cms/issues/108)

**Merged pull requests:**

- added url-scope for search-form-partial. Ugly as hell, but works for now... [\#158](https://github.com/AlchemyCMS/alchemy_cms/pull/158) ([masche842](https://github.com/masche842))

## [v2.1.rc6](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.rc6) (2012-01-20)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.rc5...v2.1.rc6)

**Closed issues:**

- "Impossible move..." error after saving order on large page trees [\#152](https://github.com/AlchemyCMS/alchemy_cms/issues/152)
- The language root page \(intro page\) icon does not refresh after unlocking a page [\#151](https://github.com/AlchemyCMS/alchemy_cms/issues/151)
- Updating EssencePicture\#edit does not finish correctly [\#150](https://github.com/AlchemyCMS/alchemy_cms/issues/150)
- close button in active page tab does not work [\#148](https://github.com/AlchemyCMS/alchemy_cms/issues/148)
- Dependencies for Debugging and Rubygems [\#147](https://github.com/AlchemyCMS/alchemy_cms/issues/147)

## [v2.1.rc5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.rc5) (2012-01-20)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.rc4...v2.1.rc5)

## [v2.1.rc4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.rc4) (2012-01-18)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.rc3...v2.1.rc4)

**Closed issues:**

- Installer raises error [\#146](https://github.com/AlchemyCMS/alchemy_cms/issues/146)
- Infinite loop if no \(default\) language is in database [\#144](https://github.com/AlchemyCMS/alchemy_cms/issues/144)

## [v2.1.rc3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.rc3) (2012-01-18)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.rc2...v2.1.rc3)

**Closed issues:**

- Pasting a copyied element does not create new essences [\#140](https://github.com/AlchemyCMS/alchemy_cms/issues/140)
- render\_navigation renders escaped string for :spacer option [\#139](https://github.com/AlchemyCMS/alchemy_cms/issues/139)

## [v2.1.rc2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.rc2) (2012-01-09)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.6.1...v2.1.rc2)

**Closed issues:**

- Elements from childpages not removed after removing parent page [\#138](https://github.com/AlchemyCMS/alchemy_cms/issues/138)

## [v2.0.6.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.6.1) (2012-01-04)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.6...v2.0.6.1)

## [v2.0.6](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.6) (2012-01-04)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.5...v2.0.6)

**Closed issues:**

- Layout gets cached with action caching [\#136](https://github.com/AlchemyCMS/alchemy_cms/issues/136)
- Element gets created twice [\#134](https://github.com/AlchemyCMS/alchemy_cms/issues/134)
- English translation for explanation of page sorting \(bottom-bar\) not found [\#133](https://github.com/AlchemyCMS/alchemy_cms/issues/133)
- Issues with pages that redirect to external [\#132](https://github.com/AlchemyCMS/alchemy_cms/issues/132)
- Cannot save a user without entering its password [\#131](https://github.com/AlchemyCMS/alchemy_cms/issues/131)
- English translation for search is broken [\#130](https://github.com/AlchemyCMS/alchemy_cms/issues/130)
- Attachements cannot be renamed [\#129](https://github.com/AlchemyCMS/alchemy_cms/issues/129)
- Image renaming does not work [\#128](https://github.com/AlchemyCMS/alchemy_cms/issues/128)
- Publish page expires wrong page url [\#125](https://github.com/AlchemyCMS/alchemy_cms/issues/125)
- Show an Alchemy bar on pages if user is logged in [\#124](https://github.com/AlchemyCMS/alchemy_cms/issues/124)

## [v2.0.5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.5) (2011-12-19)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.beta6...v2.0.5)

**Closed issues:**

- Cached picture route not working for cropped images [\#123](https://github.com/AlchemyCMS/alchemy_cms/issues/123)
- Contactform view throws error [\#119](https://github.com/AlchemyCMS/alchemy_cms/issues/119)
- image cropper does not get re-initialized after update [\#117](https://github.com/AlchemyCMS/alchemy_cms/issues/117)
- Remove Seeder class and let rails do it [\#116](https://github.com/AlchemyCMS/alchemy_cms/issues/116)
- Layoutpages appear in search results [\#114](https://github.com/AlchemyCMS/alchemy_cms/issues/114)

## [v2.1.beta6](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.beta6) (2011-12-09)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.4...v2.1.beta6)

## [v2.0.4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.4) (2011-12-09)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.beta5...v2.0.4)

**Closed issues:**

- TinyMCE does not init after creating element [\#115](https://github.com/AlchemyCMS/alchemy_cms/issues/115)
- Missing partial error after updating an essence picture [\#113](https://github.com/AlchemyCMS/alchemy_cms/issues/113)
- cleaning up page cache raises routing error [\#111](https://github.com/AlchemyCMS/alchemy_cms/issues/111)
- Dragndrop sorting pictures raises nil error [\#110](https://github.com/AlchemyCMS/alchemy_cms/issues/110)
- error on saving picture mask [\#109](https://github.com/AlchemyCMS/alchemy_cms/issues/109)
- Namespace Controllers, Helpers, Views and Models [\#106](https://github.com/AlchemyCMS/alchemy_cms/issues/106)
- Rescue all Exceptions in Admin namespace via exception\_handler [\#82](https://github.com/AlchemyCMS/alchemy_cms/issues/82)

## [v2.1.beta5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.beta5) (2011-12-02)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.3.1...v2.1.beta5)

**Closed issues:**

- set pages language\_code after updating language.code does not work [\#105](https://github.com/AlchemyCMS/alchemy_cms/issues/105)
- Set a published language to default throws error [\#104](https://github.com/AlchemyCMS/alchemy_cms/issues/104)
- uninitialized constant Rails in lib/alchemy/capistrano.rb:9 [\#103](https://github.com/AlchemyCMS/alchemy_cms/issues/103)
- new element selectbox is always showing all cells [\#102](https://github.com/AlchemyCMS/alchemy_cms/issues/102)
- if two pages have the same name in different language trees the one with default language gets rendered [\#100](https://github.com/AlchemyCMS/alchemy_cms/issues/100)
- cropping an image after beeing assigned throws 500 [\#99](https://github.com/AlchemyCMS/alchemy_cms/issues/99)
- uploading multiple images does not work [\#98](https://github.com/AlchemyCMS/alchemy_cms/issues/98)
- unfolding an element does not reinit the button observer [\#97](https://github.com/AlchemyCMS/alchemy_cms/issues/97)
- unfolded element editors do not highlight if clicked on header [\#96](https://github.com/AlchemyCMS/alchemy_cms/issues/96)
- creating new user does not work [\#95](https://github.com/AlchemyCMS/alchemy_cms/issues/95)
- tinymce plugins not found on production [\#94](https://github.com/AlchemyCMS/alchemy_cms/issues/94)
- Assets load order is wrong [\#93](https://github.com/AlchemyCMS/alchemy_cms/issues/93)
- Tinymce not initialized after element\#create [\#92](https://github.com/AlchemyCMS/alchemy_cms/issues/92)
- merge alchemy tinymce settings [\#91](https://github.com/AlchemyCMS/alchemy_cms/issues/91)
- more scopes for page [\#19](https://github.com/AlchemyCMS/alchemy_cms/issues/19)

## [v2.0.3.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.3.1) (2011-11-09)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.1.beta1...v2.0.3.1)

## [v2.1.beta1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.1.beta1) (2011-11-09)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.3...v2.1.beta1)

## [v2.0.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.3) (2011-11-08)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.2...v2.0.3)

## [v2.0.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.2) (2011-11-03)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.1...v2.0.2)

## [v2.0.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.1) (2011-11-03)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0...v2.0.1)

## [v2.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0) (2011-11-02)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.rc6...v2.0)

**Closed issues:**

- Creating a element from clipboard raises error [\#89](https://github.com/AlchemyCMS/alchemy_cms/issues/89)
- Unpublic elements getting rendered [\#88](https://github.com/AlchemyCMS/alchemy_cms/issues/88)
- flushing pages cache does not work [\#87](https://github.com/AlchemyCMS/alchemy_cms/issues/87)
- expire action caching does not work [\#85](https://github.com/AlchemyCMS/alchemy_cms/issues/85)
- action caching in pages controller includes layout [\#84](https://github.com/AlchemyCMS/alchemy_cms/issues/84)
- Deleted pages are not removed from admin pages tree [\#83](https://github.com/AlchemyCMS/alchemy_cms/issues/83)
- fallback option in render\_elements helper method finds a Page regardless of the language [\#81](https://github.com/AlchemyCMS/alchemy_cms/issues/81)

## [v2.0.rc6](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.rc6) (2011-10-30)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.rc5...v2.0.rc6)

**Closed issues:**

- Installer fails under Ruby 1.9 [\#80](https://github.com/AlchemyCMS/alchemy_cms/issues/80)
- Test against Ruby 1.9.2 [\#77](https://github.com/AlchemyCMS/alchemy_cms/issues/77)
- Add a landing\_page flag for Page [\#22](https://github.com/AlchemyCMS/alchemy_cms/issues/22)

**Merged pull requests:**

- Yaml-Syntax [\#79](https://github.com/AlchemyCMS/alchemy_cms/pull/79) ([masche842](https://github.com/masche842))

## [v2.0.rc5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.rc5) (2011-10-24)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.rc4...v2.0.rc5)

**Closed issues:**

- TypeError in Admin::AttachmentsController\#show [\#78](https://github.com/AlchemyCMS/alchemy_cms/issues/78)
- redirecting in pages controller looses query parameter [\#76](https://github.com/AlchemyCMS/alchemy_cms/issues/76)
- TinyMCE auto-height plugin is buggy [\#68](https://github.com/AlchemyCMS/alchemy_cms/issues/68)
- Check if Ferret is still working [\#7](https://github.com/AlchemyCMS/alchemy_cms/issues/7)

## [v2.0.rc4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.rc4) (2011-10-24)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.rc3...v2.0.rc4)

**Closed issues:**

- creating and rendering elements in admin namespace not possible [\#75](https://github.com/AlchemyCMS/alchemy_cms/issues/75)
- refactoring pages\_helper \#language\_switches [\#74](https://github.com/AlchemyCMS/alchemy_cms/issues/74)
- install script picks rails 3.1.0 instead of 3.0.9 [\#73](https://github.com/AlchemyCMS/alchemy_cms/issues/73)
- rake db:migrate:alchemy fails with rails \>= 3.0.7 [\#71](https://github.com/AlchemyCMS/alchemy_cms/issues/71)
- Split the alchemy\_helper into it's Controller Scopes [\#70](https://github.com/AlchemyCMS/alchemy_cms/issues/70)
- pages are displayed in wrong tree after page-sorting [\#69](https://github.com/AlchemyCMS/alchemy_cms/issues/69)
- switching language tree of global pages also switches the backend translation [\#67](https://github.com/AlchemyCMS/alchemy_cms/issues/67)
- Bilder Cache löschen geht nicht [\#66](https://github.com/AlchemyCMS/alchemy_cms/issues/66)
- Saving the page settings in page edit mode does not close the overlay [\#65](https://github.com/AlchemyCMS/alchemy_cms/issues/65)
- Copying a page does not copy its elements [\#64](https://github.com/AlchemyCMS/alchemy_cms/issues/64)
- After deleting the last page from a language tree the pages from the remaining language are displayed [\#63](https://github.com/AlchemyCMS/alchemy_cms/issues/63)
- Sometimes some images are not displayed [\#62](https://github.com/AlchemyCMS/alchemy_cms/issues/62)
- Visiting the page is not possible from edit mode [\#61](https://github.com/AlchemyCMS/alchemy_cms/issues/61)
- Translation is lost sometimes [\#60](https://github.com/AlchemyCMS/alchemy_cms/issues/60)
- After deleting the last image no add button appears [\#59](https://github.com/AlchemyCMS/alchemy_cms/issues/59)
- copying/pasting elements does not work [\#57](https://github.com/AlchemyCMS/alchemy_cms/issues/57)
- Icons need more padding between them in icons.png [\#18](https://github.com/AlchemyCMS/alchemy_cms/issues/18)
- not inserting a cutted element from trashbin correctly [\#16](https://github.com/AlchemyCMS/alchemy_cms/issues/16)

**Merged pull requests:**

- updated Readme, detailed install instructions. [\#72](https://github.com/AlchemyCMS/alchemy_cms/pull/72) ([masche842](https://github.com/masche842))

## [v2.0.rc3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.rc3) (2011-10-06)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.rc2...v2.0.rc3)

**Closed issues:**

- After adding another picture into the picture editor the button to add another image does not appear [\#58](https://github.com/AlchemyCMS/alchemy_cms/issues/58)
- Add Thumbnail Size Buttons from Archive Overlay also into Archive [\#56](https://github.com/AlchemyCMS/alchemy_cms/issues/56)
- Lost in Translation [\#55](https://github.com/AlchemyCMS/alchemy_cms/issues/55)
- Pictures can't be removed from Archive [\#54](https://github.com/AlchemyCMS/alchemy_cms/issues/54)
- After uploading a picture in the overlay the pagination is not working any more [\#53](https://github.com/AlchemyCMS/alchemy_cms/issues/53)
- One should be able to upload a file in the archive overlay [\#52](https://github.com/AlchemyCMS/alchemy_cms/issues/52)
- File Archive Overlay throws 500 [\#51](https://github.com/AlchemyCMS/alchemy_cms/issues/51)
- Error while Adding a missing content in element editor [\#50](https://github.com/AlchemyCMS/alchemy_cms/issues/50)
- Unable to close locked Page Tab in Page\#edit mode [\#49](https://github.com/AlchemyCMS/alchemy_cms/issues/49)
- picture\_editor: able to add new picture content if max\_images =\> 1 [\#44](https://github.com/AlchemyCMS/alchemy_cms/issues/44)
- Check database dependency [\#39](https://github.com/AlchemyCMS/alchemy_cms/issues/39)

## [v2.0.rc2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.rc2) (2011-10-04)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.rc1...v2.0.rc2)

## [v2.0.rc1](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.rc1) (2011-10-04)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.pre5...v2.0.rc1)

**Closed issues:**

- uploading picture will throw Internal Server Error [\#48](https://github.com/AlchemyCMS/alchemy_cms/issues/48)
- Put Alchemy Installer script into the gem as bin executable [\#10](https://github.com/AlchemyCMS/alchemy_cms/issues/10)

## [v2.0.pre5](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.pre5) (2011-10-04)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.pre4...v2.0.pre5)

## [v2.0.pre4](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.pre4) (2011-09-28)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.pre3...v2.0.pre4)

## [v2.0.pre3](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.pre3) (2011-09-15)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v2.0.pre2...v2.0.pre3)

## [v2.0.pre2](https://github.com/AlchemyCMS/alchemy_cms/tree/v2.0.pre2) (2011-09-14)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.6.0...v2.0.pre2)

**Closed issues:**

- new elements are created in wrong cell [\#47](https://github.com/AlchemyCMS/alchemy_cms/issues/47)
- copying elements does not work [\#46](https://github.com/AlchemyCMS/alchemy_cms/issues/46)
- hint for alchemy´s scaffold generator [\#45](https://github.com/AlchemyCMS/alchemy_cms/issues/45)
- 500 Error while linking image [\#43](https://github.com/AlchemyCMS/alchemy_cms/issues/43)
- RuntimeError in Admin/layoutpages\#index [\#42](https://github.com/AlchemyCMS/alchemy_cms/issues/42)
- Element not draggable after creation [\#41](https://github.com/AlchemyCMS/alchemy_cms/issues/41)
- Error while folding element [\#40](https://github.com/AlchemyCMS/alchemy_cms/issues/40)
- user-mail fails on initial signup [\#38](https://github.com/AlchemyCMS/alchemy_cms/issues/38)
- Seeding fails [\#37](https://github.com/AlchemyCMS/alchemy_cms/issues/37)
- Error while rendering elements via render\_elements helper [\#36](https://github.com/AlchemyCMS/alchemy_cms/issues/36)
- Error while dragging Elements from Trash into Elements window [\#35](https://github.com/AlchemyCMS/alchemy_cms/issues/35)
- Error: uninitialized constant Mail::Tableless while sending Mails! [\#34](https://github.com/AlchemyCMS/alchemy_cms/issues/34)
- not able to add new picture content after deleting it [\#13](https://github.com/AlchemyCMS/alchemy_cms/issues/13)
- Migrate Issues from Lighthouse [\#11](https://github.com/AlchemyCMS/alchemy_cms/issues/11)
- Update README for new usage instructions a as gem [\#9](https://github.com/AlchemyCMS/alchemy_cms/issues/9)
- Find an attachment\_fu replacement [\#8](https://github.com/AlchemyCMS/alchemy_cms/issues/8)
- html\_safe all Strings containing html [\#6](https://github.com/AlchemyCMS/alchemy_cms/issues/6)
- Find a replacement for tinymce\_hammer [\#5](https://github.com/AlchemyCMS/alchemy_cms/issues/5)
- Put all conditional finds for resources in their Model as a scope [\#4](https://github.com/AlchemyCMS/alchemy_cms/issues/4)
- Replace all rjs files with js.erb files [\#3](https://github.com/AlchemyCMS/alchemy_cms/issues/3)
- Not updating icon from nested pages after changing page\#restricted [\#1](https://github.com/AlchemyCMS/alchemy_cms/issues/1)

## [v1.6.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.6.0) (2011-08-09)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.5.5...v1.6.0)

## [v1.5.5](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.5.5) (2011-05-11)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.5.3...v1.5.5)

## [v1.5.3](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.5.3) (2011-03-14)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v.1.5.2...v1.5.3)

## [v.1.5.2](https://github.com/AlchemyCMS/alchemy_cms/tree/v.1.5.2) (2011-02-06)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.5.1...v.1.5.2)

## [v1.5.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.5.1) (2011-01-26)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.5.0...v1.5.1)

## [v1.5.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.5.0) (2011-01-21)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.3.0...v1.5.0)

## [v1.3.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.3.0) (2010-09-02)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.2.4...v1.3.0)

## [v1.2.4](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.2.4) (2010-08-24)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.2.1...v1.2.4)

## [v1.2.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.2.1) (2010-08-17)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.2.0...v1.2.1)

## [v1.2.0](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.2.0) (2010-08-13)
[Full Changelog](https://github.com/AlchemyCMS/alchemy_cms/compare/v1.1.1...v1.2.0)

## [v1.1.1](https://github.com/AlchemyCMS/alchemy_cms/tree/v1.1.1) (2010-07-29)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
