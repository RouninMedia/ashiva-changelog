# Changelog for CMS3 (2016), ashiva (2017) & ashivaModules (2019), Da3SH Modules (2020), Danis³h Modules (2021), Danis³h Capsules (2021)

## 2016
### Jan 2016
 - First version of website initialiser created
 - First site (ScotiaBeauty.com) created using website intialiser

### Feb 2016
 - Second site (HandsOffHRI.org) created

### Mar 2016
 - First idea to turn website initialiser into basic CMS with login and ability to edit pages - nicknamed "CMS3"
 - First thoughts of using Responsive Web Design + Forms + PHP to build a touchphone-optimised CMS User Interface

### Jun 2016
 - First attempt to introduce editable pages (leads to learning PHP Associative Arrays)

### Dec 2016
 - `axe` (ACSSSS) pioneers 3-step approach in which CSS Stylesheet is grabbed as a JS String, then parsed and turned into a JS Array, then parsed and turned into a JS Object (in a - very long - two and a half years time, HTML, CSS, JS and SVG will all be turned into Da3SH Components (which are JSON) using the same approach

## 2017
### Oct 2017
 - The name *Ashiva* (based on *ashiba*, the Japanese word for *scaffolding*) replaces "CMS3"
 - First attempt at creating a Control Pad for *Ashiva*
 - Invention of *Ashiva* *User Roles* and associated *User Capabilities*

### Nov 2017
 - Created responsive **SiteMap Editor Interface** (to add / move / delete pages and subpages)

### Dec 2017
 - Developed first JSON serialisation of HTML for (very early) *Ashiva Console Module*


## 2018
### Jan 2018
 - First attempt to create ashivaModules in PHP with complex PHP-array-based filters
 - Spent a long time considering creating two different categories of module: separately-formatted for the front-end and back-end

### Apr 2018
 - Developed JSON serialisation of CSS while building hackPad

### Jun 2018
 - Speculated randomly and then confirmed that PHP *can* convert JSON into PHP arrays (and classes) and vice versa. Used first in NHS app and, several months later, adopted in place of PHP PageData Array

### Nov 2018
- Inspired by *The Independent*'s save to homescreen icon, learned about and then added PWA WebManifests to Ashiva

### Dec 2018
- PHP PageData Array (either in `/functions/` File or in PHP file dedicated to current webpage) evolves into JSON **PageManifest**
- Building on introduction of PWA WebManifests, added PWA Service Workers to Ashiva
- Created JSON **SiteManifest**

## 2019
### Mar 2019
 - Developed GUI for building JSON

### May 2019
 - Da3SH Modules invented

### Jun 2019
 - Da3SH CodeSheets invented (Da3SH Components by any other name)

### Aug 2019
 - Third Ashiva site (`JamesNHSWalk.org`) created

### Oct 2019
 - ModuleManifests formalised
 - Dynamic CodeSheets invented
 - ModuleLogic invented
 - ServerSheets invented

## 2020
### Jan 2020
 - Worked on WebWorkers within Da3SH
 - Worked on ESModules within Da3SH

### May 2020
 - Namespace Access added to Da3SH Style Components

### Sept 2020
 - Concho

### Dec 2020
 * Created several new routines (ultimately destined for *Code Converter UI*):
    * compressJSON
    * importJSON 
    * SVG to Data URL / Data URL to SVG 
    * JSON to Data URL / Data URL to JSON

## 2021
### Jan 2021
 - Added support for bi-directional conversion of CSS `@media` and `@keyframes` in Da3SH Style Components

### Feb 2021
 - Experimented with introducing *"DataSheets"* alongside CodeSheets and ServerSheets. *(But since Data CodeSheets already existed, something didn't seem quite right...)*
 - Made a number of improvements to packaged `ModuleManifest`
 - Developed queryString operator `updatePageModules`
 - First experiments with JS Namespacing into Da3SH Module Scriptsheet
 - Started writing Ashiva in Deno + Oak on Heroku

### Mar 2021
 - Developed **Ashiva_Roles** Da3SH Module
 - Developed `submitData()` for Synchronous Serversheet Access (originally for **Ashiva_Roles**)
 - Successfully *async-ed* **Modules Stylesheet** - leading to *dramatic* improvement in page load speed
 - Developed queryString operator `updatePageComponents`
 - Substantially rewrote **JSON Rewriter** (and, by extension, *Code Converter UI*)
 - Formalised in-Module HTTP Authentication and reconceptualised *"DataSheets"* as *"Protected DataSheets"* stored in: `/modulename/protected/`
 - Wrote **Ashiva Multi-Page Find and Replace Editor** (based on PHP Code from **Kubaru** and Front End Code from **LanguageCompass**)
 - Developed **veSPA** in the course of writing *Ashiva Multi-Page Find and Replace Editor* 
 - Developed **SB_Email_Subscribers** Da3SH Module
 - Re-named / re-framed *ServerSheets* as *SubPages* (or *Substitial Pages*)

### NEXT: Go through i) GitHub, ii) StackOverflow Questions, iii) WorkLog Notes

 - What are *ActionSheets* / *SubPages* / *DataSheets* / *protected* ??
 - Established both JSON Rewriter and MultiPage Editor as aSPs (?)
 - Async-ed Modules Scriptsheet (?)
 - Async-ed Main Scriptsheet (?)

### Apr 2021

### May 2021
 - Renamed `moduleLogic` as `ActionSheets`

### Jun 2021
 - Wrote *Scotia Beauty Document Uploader* (based, initially, on *Ashiva Multi-Page Find and Replace Editor*) and, by extension, most of *Ashiva Media Uploader*
 - Fourth Ashiva site (`EtherPhysics.net`) created
 - Started work on bringing Ashiva Installer fully up-to-date
 - Changed name from Da3SH to DaNIS³H
 - Started writing *User Guide to DaNIS³H* at: https://app.gitbook.com/@alan-lansdowne/s/danis3h/
 - Formalised HTML-style syntax describing DaNIS³H Modules
 - Added `/.restore/` folder to `/.assets/media/` as a temporary store to enable undo-ing when users accidentally delete files
 - Developed *New Scaffold* for EtherPhysics.net, using *New PageManifest* References
 - Incorporated `concho()` statements into New Scaffold
 - In `concho()`, enabled Boolean `FALSE` condition; introduced parameter enabling replacement of backticks around operators with spaces
 - In the process of developing *New Scaffold* for EtherPhysics.net, extended, expanded and improved *New PageManifest*
 - Created `link rel-danis3hmodule` to reference the DaNIS3H Modules present on each page
 - Added `link rel-danis3hmodule`, `link rel-ashiva-pagemanifest` and `link rel-ashiva-sitemanifest` to New Scaffold
 - Added **title folder** to module folders (`/modulename/#%20Module%Name/`) in which to store `modulename-package.json` (and other things)
 - Updated *DaNIS3H Brand* (the middle level between *DaNIS3H Publisher* and *DaNIS3H Module*) to ***DaNIS3H Imprint***
 - Moved **sitemaps section** from *New Page Manifest* to *Site Manifest*. Wrote new **sitemaps section** for *New Page Manifest*
 - Enabled simple string-formatting functions in `concho()` statements: `url(0::Module)` is the equivalent to applying `url()` to the output of `'0::Module'`
 - Added `/protocols/`, `/manifest/` & `/serviceworker/` subfolders to `/.well-known/` folder and updated `.htaccess` file

### Jul 2021

 - Got my head around the difference between `FileSystem Paths` and `URL Paths` which means that any file which needs a `URL Path` pointing to the root folder or the `/.well-known/` folder, can actually reside *anywhere* in the `FileSystem` and simply have a redirect (e.g. in `.htaccess`) to its true location in the `FileSystem`. Consequently... created `/.assets/scheme/meta/protocols/` (for all protocols) and then moved `/.assets/theme/` to `/.assets/scheme/theme/` and then added `/.assets/scheme/social/`, `/.assets/scheme/progressive-web-apps/`, `/.assets/scheme/meta/api/`, `/.assets/scheme/meta/manifests/` and  `/.assets/scheme/meta/sitemaps/`

  - Came up with the concept of **DA**. **UX** (*User Experience*) and **UA** (*User Accessibility*) are concepts which have been around for quite a while now. **DX** (*Developer Experience*) is newer but also well-established. At the core of **DaNIS3H** (alongside *code-as-data* and *coding environment agnosticism*) is the concept of **DA** (*Developer Accessibility*) which means making sophisticated, unlimited web-development accessible to the approximately 50% of web page developers who are not conversant and entirely at ease with javascript. This level of **DA** is only otherwise available via **Declarative WebComponents** - and often not even then.

 - [2021-07-16] Became aware of https://mavo.io/ after running across a link to it in https://github.com/whatwg/html/issues/2271

 - Massively improved sophistication and utility of *Ashiva ControlPad Module* by introducing both Ajax-based **Multi-Level Menus** *and* a **Document Viewer**
 - Added *moduleMedia* folder to **DaNIS³H Modules**. Started implementing process where *moduleMedia* SVG Components convert into inline Data URLs in CSS & HTML

### Aug 2021

  - Finally (after two years!) turned JSON-LD Structured Data into DaNIS3H Modules. Consequently slimmed down Ashiva folder structure, Core, Scaffold and Site Manifest.
  - Re-conceptualised DaNIS3H Module Parameters as _String Parameters_ and introduced _Array Parameters_ and _Object Parameters_ to DaNIS3H Module Notation, allowing each of the three types of parameter to be *unnamed* or *named*
  - Removed `$Critical` parameter from `danis3hModule()` function (I've never used it and if I ever did, it would make bugs harder to track)
  - Expanded `danis3hModule()` function's `$Context` parameter (briefly renamed as `$Setting`) - kept `element` the same, renamed `'page'` as `'pagefix'` and added 2 new **Contexts**: `'pageflow'` and `'unstyled'`
  - Made more small improvements to `ModuleManifest` JSON Package
  - Added optional `ModuleAttributes` entry to `ModuleManifest`, like this: `$moduleBlock['Attributes'] = ['Position' => 'Off'];`
  - Swapped `'pagefix'` and `'pageflow'` **Contexts** so that `'pageflow'` is now the default **Context** and `'pagefix'` needs to be explicitly stated
  - **Leap Forward:** Realised `$Context` parameter in `danis3hModule()` can now be eliminated entirely and replaced with `$ModuleProperties = ['Attributes' = [], 'LightModifiers' = []]` (!!)
  - Updated Module Registration: Removed `Parameters` Entry from Register when no Parameters; added `Requires` to Register, added `Attributes` to Register
  - Discovered something similar to `$ModuleProperties` (attributesJSON) in `renderMarkup()` (!) and updated it to be consistent with `$ModuleProperties` in `danis3hModule()`
  
  - Created **Dynamic Menus** for *Ashiva ControlPad Module* using PHP-preprocessed JSON
  - Created two custom `<meta>` elements for Ashiva, **DaNIS³H Modules Profile** and **DaNIS³H Assets Profile**:

```
<meta name="danis3h-modules-profile" content="{«ModulesProfile»: {«Module_A»: [«Markup», «Styles», «Module_C»], «Module_B»: [«Markup», «Styles»], «Module_C»: [«Markup», «Scripts»]}" />
<meta name="danis3h-assets-profile" content="{«AssetsProfile»: {«Markup»: [«Module_A», «Module_B», «Module_C»], «Styles»: [«Module_A», «Module_B»], «Scripts»: [«Module_B», «Module_C»]}" />
```

  - The two innovations immediately above (*Ashiva ControlPad Dynamic Menus* and *ModulesProfile / AssetsProfile*), made it possible for the *Ashiva ControlPad Module* to display *dynamic* and *page-relevant* menus for *Style Components*, *Script Components* and *ESModule Components*
  - Added SVG icons across *Ashiva ControlPad Module*

### Sept 2021

 - Added `modulefound="false"` attribute to both types of invalid module calls:
 
   - when `ModuleName` is *absent* from the `ModuleList` in the **PageManifest**
   - when `ModuleName` is *present* in the `ModuleList` in the **PageManifest** but the DaNIS3H Module isn't installed / uploaded

- Started building *Ashiva Desktop* in **Atom**

- Adapted *Ashiva ControlPad Document Viewer* so that it can now show individual *Style Components*, *Script Components* and *ESModule Components* excerpted from their dynamically-generated parent files: `/modules/styles/styles.css`, `/modules/scripts/scripts.js`, `/modules/esmodules/esmodules.js`

- Adapted `View HTML Source` script to build a version which displays code in the *Ashiva ControlPad Document Viewer* (rather than in a new tab)

- Added `/.assets/scheme/meta/well-known/` folder as a home for all `/.well-known/` files and folders (and added corresponding `mod_rewrite` rule in `.htaccess`)

### Oct 2021

 - Added **Namespace Toggle** to *Ashiva ControlPad Document Viewer*

 - Added Web Workers option to *Ashiva ControlPad Main Assets Menu*

 - Added **Settings Console** to Ashiva Control Pad, with 1) *Select User*, 2) *Mute/Unmute*, 3) *Fullscreen Toggle*, 4) *Tools*, 5) *Notes* and 6) *Switch Off* controls

 - Replaced both the ambiguous *empty root selector* \[`""`\] and the *leading space selector* \[`" .my-class"`\], (particularly easily missed when debugging) with the CSS pseudo-class `:root` across DaNIS3H Module stylesheets

- Updated `/.assets/content/scaffold/` to `/.assets/content/scaffolds/` to indicate that a single **Ashiva Site** may deploy more than one *Scaffold*

- Renamed **DaNIS³H Modules** as **DaNIS³H Capsules**

- Added **Expand Capsule Toggle** to *View HTML Source* **DocumentView** in *Ashiva ControlPad*

- Added script which appends *Empty Component Notice* to those **DaNIS³H Markup Components** which (intentionally) contain no markup

### Nov 2021

 - Changed *Light Modifier Indicators* from **Custom Data-\* Attributes** (`data-°orange`) to **Custom Attributes** (`°orange`)

 - Moved *Light Modifier Indicators* to end of **Capsule Declaration**

 - introduced `['Attributes' => ['Conditional' => TRUE]]` to `danis3hModule` function (as a gentler implementation of the Capsule-skipping functionality originally executed by the now-obsoleted `$Critical` - see Aug 2021)

 - made a plan to formalise Concho **Condition-String Syntax** (which will also be used in `['Attributes' => ['Conditional' => TRUE]]`)

 - enabled **Light Modifiers** to parse *single values* (ie. indexed array items) as well as *key-value pairs* (associative array items)
 
 - updated `getMarkup($Module, $Attributes, $LightModifiers)` to enable **Light Modifier** *key-value pairs* to be rendered properly in **HTML Markup**
 
 - re-labelled **Ashiva Console:** as **DaNIS³H Console:** everywhere
 - Fifth Ashiva site (`OurFlag.uk`) created
  
<ul>
<li>  renamed:
  
<ul>
 <li><code>/.assets/modules/</code></li>
 <li><code>/.assets/scheme/</code></li>
</ul>
    
as:
    
<ul>
<li><code>/.assets/capsules/</code></li>
<li><code>/.assets/site/</code></li>
</ul>
</li>
</ul>

### Dec 2021

  - Activated **Concho** in New Scaffold of `OurFlag.uk`. (In the New Scaffold of `EtherPhysics.net` **Concho** is still theoretical.)
  - In **Concho**, updated the query demarcators from `|` to `¦`
  - Made a number of changes to **New PageManifest** and **New SiteManifest**
  - Significantly updated Scaffold Build Process for *Main Scripts*, *Main ESModules*, *Capsule Scripts* and *Capsule ESModules* and moved to `Core`
  - Significantly updated Scaffold Build Process for *Main Styles* and *Capsule Styles* and moved to `Core`
  - Made a *large* number of changes to **New Scaffold** and successfully reduced length of `OurFlag.uk` Scaffold to *under 100 lines*
  
  - Adopted clever suggestion by Jeremy Keith to reduce number of individual social media meta tags in **New Scaffold**
  - Added `<meta name="format-detection" />` entry to **New PageManifest** to handle `telephone` | `email` | `date` | `address` | `url` detection
  - Added `Protocols` section (alongside `Channels` section) to `Meta_Information::Social_Media` in **New PageManifest**
  - Added to **New Scaffold** several new social media prefixed meta tags: `og:type`, `twitter:image:alt`, `twitter:site:id`
  - Added `/.my-capsule/` admin subfolder to the top of each `/my-capsule/` capsule folder

  - Added `<link rel="license" />` entry to **New PageManifest**
  
  - Added `oEmbed`
  - Added `oEmbedProviderList` to `Ashiva SiteManifest`

### Jan 2022
  - Spent all month working on the JS-to-JSON (2021) and JSON-to-JS (2021) conversion scripts (started in Dec 2021, substantially completed by Feb 2022)

### Feb 2022
  - Integrated the JSON-to-JS (2021) DaNIS³H conversion into *Ashiva*, alongside the legacy JSON-to-JS (2019) DaNIS³H conversion
  - Came up with the idea of *Wordlash* (ie. the *ash* library implementation of *Wordle*) to showcase to **IndieWeb** (and others) what **DaNIS³H** is capable of
  - Wrote my *first* DaNIS³H script integrant using JS-to-JSON (2021): `Ashiva:::Ashiva_roleQuery` (which promptly evolves into `Ashiva:::Ashiva_Open_Control_Pad`)
  - Replaced `Ashiva:::Ashiva_Control_Pad` Capsule on all **ScotiaBeauty** pages with `Ashiva:::Ashiva_Open_Control_Pad` Capsule
  - Added **ControlPadSettings JSON** as a semi-persistent entry in `sessionStorage` with (at present) a single setting: `audio: true / false`

### Mar 2022
 - Fixed some source-viewing functionality within the `Ashiva:::Ashiva_Control_Pad` Capsule 

### Late March to June 2022
  - Worked *a lot* on *Wordis³h* (and also learned a lot about iOS compatibility in the process)
  - Invented *ServiceShield for URA / SDA* - a low-tech, manually operated stand-in for **Service Worker** in Single Document Apps and Uniform Resource Apps

### May 2022
 - **DaNIS³H Standard Library:** renamed *Standard Library for DaNIS³H Capsules* from *Ash* to *DSL* (pronounced *diesel*) 
 - Conceived of *Blueish* (or *Blueis³h*) - a full screen `<iframe>` with JS / Bluetooth functionality enabling inter-device sharing of `data://` URIs

### Jun 2022
 - Started designing the process for parsing *Capsules* directly from HTML Markup - amongst other things, this makes *nested Capsules* possible
 - Stephen H very helpfully suggested ***cell*** as an alternative to *integrant*. It's perfectly ambiguous. *CodeCell*, *PageCell* etc.
 - Made strides on the *Triangular Signature* process for authenticating **distributed capsules**, so that *Capsules* can be reliably imported from anywhere 
 - Introduced logical `⊤` symbol as a markup value to indicate boolean `attributes` and `data-* attributes`. This replaces: `test="test"` & `data-test=""`
 - In *DaNIS³H*, renamed `System Attributes` as `Directives`
 - In *Ashiva*, renamed `/.assets/capsules/ash/` Standard Library Capsules folder as `/.assets/capsules/.standard-library/`
 - In *DaNIS³H Capsule Manifests*, renamed `moduleParameters` as `StrongModifiers`
 - In *DaNIS³H Capsule Manifests*, renamed `moduleBlock` as `CapsuleBlock`
 - In *DaNIS³H Capsule Manifests*, renamed `$Module` variable as `$Capsule`
 - In *DaNIS³H Capsule Manifests*, categorised `CodeSheets` and `Dynamic CodeSheets` as `codeCells`
 - In *DaNIS³H Capsule Manifests*, renamed `ModuleLogic` (aka `ActionSheet` / `sculptModule` / `Refine`) as `logicCells`
 - In *DaNIS³H Capsule Manifests*, renamed `ServerSheets` (aka `Substitial Pages` / `SubPages`) as `pageCells`
 - In *DaNIS³H Capsule Manifests*, renamed `Protected` as `lockCells`
 - In *DaNIS³H Capsule Manifests*, renamed `moduleMedia` as `mediaCells`
 - Introduced *Ashiva Console* in all environments (Markup, Stylesheets, Scripts, ESModules, SVG, Data) to report undownloaded CodeSheet
 - Updated `LightModifier` indicator in attributeNotation from `#` to `##`
 - Comprehensive update of all Unicode symbols used in *Capsule Class* syntax.
   - `StrongModifiers`: • ▸ ▪ ▾ ﴾ ﴿
   - `LightModifiers`: ◦ ▹ ▫ ▿ ﴾ ﴿
   - `Directives`: ● ► ✦ ⧫ ﴾ ﴿
   - `Attributes`: ○ ▻ ✧ ◊ ﴾ ﴿
   - `Space Separator` (used in `ClassLists` etc.): ▵
 
 - Updated *Capsule ClassSpace* syntax from:
 
   -  `sb-consoles»by»scotiaBeauty»»»veil` to `sb-consoles◈by◈scotiaBeauty◉veil`
   -  `sb-consoles»by»scotiaBeauty:my-imprint»»»veil` to `sb-consoles◈by◈scotiaBeauty▣my-imprint◉veil`


### Aug 2022

 - Added `templates` to `/.assets/content/` in Ashiva

### Sept 2022

 - Fixed error in DaNIS³H Conversion from JS to JSON when the JS source contains more than one `;` in a row (either adjacent or separate by whitespace)
 - Enabled pseudo-elements and pseudo-classes like `::before`, `::after`, `:fullscreen` etc. in DaNIS³H Conversion from CSS to JSON
 - Enabled conversion of complex, nested `ObjectLiterals` in DaNIS³H Conversion from JS to JSON
 - Wrote `Resolve_Nested_Group()` PHP function to reliably convert nested groups in DaNIS³H Conversion from JSON to JS in contexts like *array indexes*
 
 - Updated *Capsule ClassSpace* syntax (again) from:
 
   -  `sb-consoles◈by◈scotiaBeauty◉veil` to `sb-consoles◈by◈scotiaBeauty◆veil`
   -  `sb-consoles◈by◈scotiaBeauty▣my-imprint◉veil` to `sb-consoles◈by◈scotiaBeauty◇my-imprint◆veil`

 - Added `Undefined` and `Null` types to DaNIS³H Conversion from JS to JSON
 - Invented `danishPack` (or `danis³hPack`) - a *Dictionary Replacement + Brotli* compression process for **DaNIS³H** and **Ashiva**
 - Invented **Invisible Compression** which converts `danishPack` into _Percent Encoding_ and then into _Zero-Width Characters_ to produce small, easy-to-copy strings
 - Invented Dynamic Short URLs using **Invisible Compression**. Good generally for sharing URLs on (some forms of) Social Media and *especially* good for *Blueis³h* Data URI sharing
 
### Oct 2022
 - Added `HostObject` and `BuiltInObject` types to DaNIS³H Conversion from JS to JSON
 - Added `Undefined`, `Null`, `HostObject` and `BuiltInObject` types to DaNIS³H Conversion from JSON to JS

### Nov 2022
 - In **Danis³h Style Cells**, updated the shorthand which represents the Capsule from `:root` to `:capsule-root` (to avoid ambiguity with the standard CSS pseudo-class which represents the HTML document)
 
### Dec 2022
 - Considerably re-worked (until fixed) bi-directional conversion of `Object Literals` and `Array Literals` in *danis³h script codecells*
 - Corrected `sameLine` notation for short `arrow functions` in *danis³h script codecells*
 - Corrected bi-directional conversion of `try / catch` statements in *danis³h script codecells*
 - improved bi-directional conversion of `self-closing elements` in *danis³h markup codecells*
 - enabled correct bi-directional conversion of `[for="id"]` and `[form="id"]` etc. attribute selectors in *danis³h style codecells*
 - Formalised **dON** (*danis³h object notation*), long-used, in `data-danis3h-events`
 - updated `data-danis3h-attached-events` so that it now reads: `data-eventlisteners`
 - extended `addEventListener()` method in **Ashiva** *Main Script* such that it declares `data-eventlisteners` on *any* element to which an  `EventListener` is added
 - updated `Danis³h Declarative EventListeners` so that their `data` fields return `parameter-value objects` rather than `parameter-value arrays`
 - updated the only two `Capsules` (`SB_Consoles` & `Ashiva_Control_Pad`) which currently have `EventAction Functions` which use `data` from `Danis³h Declarative EventListeners`. Now, `EventAction Functions` handle `objects` (with named entries) instead of `arrays` (with numerical entries)
 
 ### Jan 2023
  - Upgraded `@sameLineComments`, `@singleLineComments` & `@multiLineComments` in **Danis³h Markup Cells** and added `@codeComments`
  - Enabled `<![CDATA[ ... ]]>` blocks in **Danis³h Markup Cells** by using `␂` and `␃` characters to demarcate **HTML Character Data** 
  - **Danis³h** now inserts the relevant `NameSpace` into `href` attribute values starting with `#` in **Markup Cells**
  - I discovered that **Danis³h** *already* pre-pended `NameSpaces` to `for` attribute values in a manner similar to `#-target href` attributes, immediately above. **Danis³h** will now apply the same `NameSpace` pre-pend to another seven attributes: `form`, `aria-activedescendant`, `aria-controls`, `aria-describedby`, `aria-flowto`, `aria-labelledby`, `aria-owns`
  - **Danis³h** bi-directional parsing of `CSS` nested inside **Markup** via `<style>...</style>` (uncommon in **HTML**, but very common in **SVG**)
  - **Danis³h** parses `<![CDATA[...]]>` as CSS-native. So **HTML CData Markers** included inside `<style>...</style>` are still treated as CSS 
  - With these additions (`@codeComments`, `<![CDATA[...]]>`, `Namespaced` targets, nested `CSS`), **Danis³h** now bi-directionally converts **`SVG`**
  

 ### Feb 2023
  - Moved `/.assets/content/scaffolds/` to `/.assets/site/theme/scaffolds/`
  - Moved `/.assets/system/` to `/.assets/site/system/`
  - Added `Site_Editorial` to `SiteManifest`
  - Added optional `Section_Editorial` to `PageManifest`
  - Moved `/.assets/site/system/core/` to `/.assets/site/core/`
  - Linux Nautilus orders files differently from Windows. Experimented with prefixing Title Folder with `$` instead of `#`. // *<= NEEDS WORK*
  - Updated `danis3hModule()` PHP function in **Core**: every **CodeCell** alias must now end in a suffix: `'Markup'`, `'Styles'`, `'Scripts'`, `'Vectors'` or `'Data'`
    1. This means mean `CustomComponent` aliases are now redundant, since **CodeCells** may now use *any* alias, as long as it has a valid suffix
    2. This also allows *any* aliased cell (even former `CustomComponents`) to be `**PrimeCell**`
   
  - Less keen on `::` as a prefix to `LightModifiers` in HTML Markup, since it's *identical* to the prefix of `StrongModifiers` in Capsule References
    1. Replaced `::` as LightModifier prefix in HTML Element Markup with `:`
    2. Replaced `:--:` as Directive (System Attribute) prefix in HTML Element Markup with `:...`
    
  - Invented the **Front-end CapsuleManifest** (via extended **xHan**) which delivers what **CapsuleManifest Files** achieve on the server-side
  - Renamed `CapsuleLogic` / `Casts` / `LogicCells` / `Logic` etc. as `Transformers` (hopefully this will settle now, finally)
  - Renamed `LockCells` / `Locks` as `Vaults`
  - After several years of intermittent review, completed second, much-revamped version of **henkan** (provisionally named *"Henkan 2020"*...!)
  - Redesigned **CodeSheet References** in **CapsuleManifest** Files so that instead of two parameters (*CellAlias*, *FileName*) there are now three: (*CellAlias*, *FileName* + *FileType*, *FilePath*)

  
  ### Mar 2023
   - Brought **CellNames** into line with **Cell Aliases**, standardising "named cells" & enabling formerly unavailable functionality
   - What used to require two separate Capsules (`Ashiva_Open_Control_Pad` for the inital button; and then `Ashiva_Control_Pad` for the asynchronously loaded interface) can now be a *single* Capsule with selectively referenced **CapsuleCells**. This takes a lot of pressure off the initial page load.
          
   - Updated `page-styles.php` and `page-scripts.php` to handle the new structure of `Capsule CodeCells`
   - Added `CellName`, `CellType` & `PrimeCell` entries to the `JSON` of individual Danis3h Cells for self-identification
   - Added `pageinsert`, a fourth Capsule Directive (System Attribute) alongside `pagecontext`, `settingslisted` & `conditional`

  - In *CapsuleReferences*, updated `Publisher` from `<Ash:::My_Imprint:::Ash_My_Capsule>` to `<Ash_My_Capsule (Ash:My_Imprint)>`

  - Realised I could utilise the new *inline CapsuleManifest* syntax to inspect *any* existing *CapsuleCell* on the front-end:

    - `<SB_nextPage>` // *reference to a **PrimeCell** within a Manifested Capsule*
    - `<Button_Markup[@]SB_nextPage>` // *reference to an active **Named Cell** within a Manifested Capsule* // <= WILL PROBABLY BE REMOVED
    - `<SB_nextPage (Scotia_Beauty) [@]Button_Markup>` // *reference to any **Named Cell** within any Capsule, Manifested or Unmanifested*
       
 - Resolved that the demarcator for the *inline* **CapsuleManifest** should be: `[#]`
 - Rewrote CellReferences, such that `<Button_Markup[@]Ashiva_Menu>` is now: `<Ashiva Menu (Ashiva) [@]Button_Markup>`
 - Came up with the idea of *implicit* inline **CapsuleManifests** and *implicit* inline **PrimeCells** for front-end **CapsuleReferences**

 - Rewrote the **CapsuleReference** syntax:
 
   `<!--<[ <Scotia_Beauty:::SB_Colour_Charts> ]>-->` is now: `<!--[<SB_Colour_Charts (Scotia Beauty)>]-->`
    
 - Resolved to bracket the **CapsuleType** prefix the same way as the **CapsuleReference**:
 
   `<!--[<PoLIS⁵H>][<SB_Colour_Charts (Scotia_Beauty)>]-->`
    
 - Formalised special extensions in xHAN to enable index-references *and* conditional statements inside inline, declarative CapsuleManifests
 
 - Found (in `SB_Email_Subscribers` Capsule) some _"LogicCells"_ (now _Transformers_) which were simply included PHP functions. That is, they definitely weren't _Transformers_ but they weren't _"ServerSheets"_ (now _Pages_) either. So I introduced _"Includes"_ as a sixth CapsuleCell category, alongside _Code, Media, Pages, Transformers, Vaults_ // <= MIGHT RENAME _"Includes"_ AS _"ServerSheets"_ or _"Servers"_

 - Updated Capsule Attribute Syntax:
   - changed `LightModifiers` prefix from `##` to `||`
   - introduced new `PrimeCell` prefix: `@@`
   - introduced new `CapsuleManifestEntry` prefix: `##`

 - Introduced a fifth system attribute, `[&]scan`, to enable **CapsuleReferences** to be as brief as possible

  ### Apr 2023
 - Introduced the `!` prefix as a negation indicator for PrimeCells and for **CellReferences** in inline **CapsuleManifests**  in **CapsuleReferences**
 - In **CapsuleManifests** changed the 3 new parameters from (*CellAlias*, *FileName* + *FileType*, *FilePath*) to (*FileName*, *FileType*, *FilePath*)
 - Derived the *CellAlias* automatically by removing any *CapsuleName* prefix from the start and adding a *CellType* suffix to the end
 - To bring everything into line with front-end inline Capsule Manifests, turned `$Capsule['Markup']`, `$Capsule['Styles']` etc. into `arrays` containing CapsuleCells, each identified by its own *CapsuleEntry* key; e.g. `$Capsule['Styles'] = $Button_Styles` becomes `$Capsule['Styles']['Button_Styles'] = $Button_Styles`. In order that every *CellAlias* remains unique, this requires that two *CapsuleCells* of the same *CellType* MAY NOT have the same name, regardless of *FilePath* and *FileType*.
  - Considered renaming `Transformers` as `Converters`. Or as `Rewriters`. Eventually settled on `SculptCells` / `Sculpts`
  - Renamed `VaultCells` / `Vaults` as... `ShieldCells` / `Shields`
  
  - For this bullet point, 1) see **QUESTIONS TO ANSWER**, then 2) move to Capsule Inspection, then 3) move to `:.`, then 4) move to `Ashiva_Toggle` on the front-end
  
  - Removed the `!` prefix from inline *CapsuleManifest* parameters and changed the _negated PrimeCell_ from `[!@]` to `[/]`
  - Considered adopting `:.` as the HTML-attribute prefix for the `PrimeCapsule` and `:..` as the HTML-attribute prefix for the `CapsuleManifest`


______


## ASHIVA WEBSITES OVER TIME
 - 2016 - (1) Scotia Beauty (Ashiva revamped in late 2018)
 - 2016 - (2) HandsOffHRI (Version 1 [2016-17] & Version 2 [2017-18])
 - 2019 - (3) James NHS Walk (No Capsules)
 - 2021 - (4) EtherPhysics (Full PageManifest)
 - 2021 - (5) OurFlag.uk (Concho & Revamped Scaffold)
 - 2022 - (6) HuddersfieldForUkraine (First virtual theme-based site)
 - 2023 - (7) ReadyWriteWeb (Ashiva 0.9!)

______

## Developments to Add...

 - First JSON serialisation of Javascript (2019)
 - Second JSON serialisation of Javascript (2020)
 - Third JSON serialisation of Javascript (Dec 2021 - Feb 2022... with additional work in Sept 2022, Dec 2022 & Feb 2023)
 - JSON Sitemap
 - Da3SH Module Version Control
 - ModulePackages
 - IM:PACT
 - APEx
 - QuadTap
 - Henkan 1
 - Henkan 2
 - JSON GUI Editor
 - Series Tool
 - Multiple PageManifests Editor (Kubaru)
 - New ControlPad
 - SiteModules Tool
 - Languages Tool
 - New PageManifest format
 - Social Media / Identity `<link rel="">` element


EVOLUTION OF ASHIVA
===================

Jan 2016 - Intended as an HTML-first website initialiser
Mar 2016 - Working Name: CMS3
         - Initial thoughts about making pages user-editable (using PHP Ordinal Arrays and HTML Forms)
Jun 2016 - Learned PHP Associative Arrays
Dec 2016 - Learned JSON, Javascript Objects and Ajax

........ - Long break (learning animation, UI and visual engagement)
Sep-Dec 2017 - Started work on multiple tools to build the first version of Control Pad (iframe) with obligatory Mobile UI as well as Desktop UI
Nov 2017 - Devised a way to represent HTML as JSON

Jan 2018 - First version of Client-side Modules and Server-Side Modules (Dead end...)
Apr 2017 - Devised a way to represent CSS as JSON
........ - Long break (learning to build crude web apps, PHP+JSON, JS Module Pattern, callbacks and, finally, ES2015+)
Dec 2018 - Shifted focus from HandsOffHRI to ScotiaBeauty. Updated pageManifests from multiple PHP Associative Arrays to single JSON
         - Learned WebManifest and Service Workers and developed PWA setup for Ashiva

Jun 2019 - Superlative breakthrough on ashivaModule Architecture using Da3SH Modules
Sep 2019 - Learned IndexedDB
Oct 2019 - Devised a way to represent JS as JSON
Oct-Dec 2019 - Started creating tools which build Da3SH Modules

Apr 2020 - Developed concepts for tools (IM:PACT & APEx) which give Ashiva Decoupled (or Hybrid) CMS Capability
May 2020 - Added comments and skips (Skip:Comment & Skip:Compress) to HTML, CSS and JS Da3SH Components
Jun 2020 - Built new Ashiva Control Pad entirely out of JS - much better
Aug 2020 - Started re-designing Henkan 2020 (returned to it occasionally in 2020/2021, mostly left it in 2022 and completed it in Feb 2023)
Sep 2020 - Learned Web Components

--- - Started thinking about ashivaModules which can handle page state (like Redux)
--- - Started learning Deno
--- - Started thinking about giving Ashiva JAMStack / Serverless capability
--- - Started thinking about what ashivaModuleManifests (currently PHP functions) would look like if they were JS functions


Thought: Why does DaNIS3H have *Modules* rather than *Components*? Is it partly because *React Components* and *Vue Components* and *WebComponents* are all **UI Components** with Display Logic and Display Data. Whereas *DaNIS3H Modules* can represent anything on the front-end or the back-end. They are more than just **UI Components**.
