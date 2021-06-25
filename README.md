# ashiva Changelog

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
 - `axe` (ACSSSS) pioneers 3-step approach in which CSS Stylesheet is grabbed as a JS String, then parsed and turned into a JS Array, then parsed and turned into a JS Object (in several years time, HTML, CSS, JS and SVG will all be turned into Da3SH Components (which are JSON) using the same approach

## 2017
### Oct 2017
 - The name *Ashiva* (based on *ashiba*, the Japanese word for *scaffolding*) replaces "CMS3"
 - First attempt at creating a Control Pad for *Ashiva*
 - Invention of *Ashiva* Roles and Capabilities

### Nov 2017
 - Created SiteMap Editing Interface (to add / move / delete pages and subpages)

### Dec 2017
 - Developed first JSON serialisation of HTML for *Ashiva Console Module*


## 2018
### Jan 2018
 - First attempt to create ashivaModules in PHP with complex PHP-array-based filters and commitment to create separately formatted front-end and back-end modules

### Apr 2018
 - Developed JSON serialisation of CSS while building hackPad

### Nov 2018
- Added PWA WebManifests to Ashiva

### Dec 2018
- PHP PageData Array evolves into JSON **PageManifest**
- Added PWA Service Workers to Ashiva
- Created JSON **SiteManifest**

## 2019
### Mar 2019
 - Developed JSON GUI

### May 2019
 - Da3SH Modules invented

### Jun 2019
 - Da3SH CodeSheets invented (Da3SH Components by any other name)

### Aug 2019
 - Third site (JamesNHSWalk.org) created

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
 - Added support for bi-directional conversion of CSS @Rules in Da3SH Style Components

### Feb 2021
 - Introduced *"DataSheets"* alongside CodeSheets and ServerSheets - but since Data CodeSheets already existed, something didn't seem quite right...
 - Developed queryString operator `updatePageModules`
 - First experiments with JS Namespacing into Da3SH Module Scriptsheet
 - Started writing Ashiva in Deno + Oak on Heroku

### Mar 2021
 - Developed **Ashiva_Roles** Da3SH Module
 - Developed `submitData()` for Synchronous Serversheet Access (originally for **Ashiva_Roles**)
 - Successfully *async-ed* **Modules Stylesheet** - leading to *dramatic* improvement in page load speed
 - Developed queryString operator `updatePageComponents`
 - Substantially rewrote **JSON Rewriter** (and, by extension, *Code Converter UI*)
 - Formalised in-Module HTTP Authentication and introduced `/modulename/protected/` (after realising ***this*** is the key feature of *"DataSheets"*)
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

### Jun 2021
 - Fourth site (EtherPhysics.net) created
 - Started work on bringing Ashiva Installer fully up-to-date
 - Changed name from Da3SH to DaNIS³H
 - Started writing *User Guide to DaNIS³H* at: https://app.gitbook.com/@alan-lansdowne/s/danis3h/
 - Formalised HTML-equivalents of PHP module-call syntax:

```
danis3hModule(${'<SB_Colour_Charts>'});
danis3hModule(${'<SB_Notice::Orange::Yellow>'});
danis3hModule(${'<SB_Notice::BG:Orange::FG:Yellow>'});
danis3hModule(${'<SB_nextPage>'}, 'page');
danis3hModule(${'<SB_Body_Data>'}, 'element');
danis3hModule(${'<SB_Body_Data>'}, FALSE, 'element');
danis3hModule(${'<SB_Colour_Charts>'}, ['orange', 'yellow']);
danis3hModule(${'<SB_Colour_Charts>'}, ['bg' => 'orange', 'fg' => 'yellow']);
danis3hModule(${'<Markup[@]SB_Translations>'});
danis3hModule(${'<Language_Folder[@]SB_Translations>'});

<!--[ <SB_Colour_Charts> ]-->                         
<!--[ <SB_Notice Orange Yellow> ]-->              
<!--[ <SB_Notice Bg="Orange" Fg="Yellow"> ]-->
<!--[ <SB_nextPage :context="page"> ]-->
<!--[ <SB_Body_Data :context="element"> ]-->
<!--[ <SB_Body_Data :critical="false" :context="element"> ]-->
<!--[ <SB_Colour_Charts orange yellow> ]-->
<!--[ <SB_Colour_Charts bg="orange" fg="yellow"> ]-->
<!--[ <Markup[@]SB_Translations> ]-->
<!--[ <Language_Folder[@]SB_Translations> ]-->

HTML-comment syntax includes optional signature after the opening square bracket (eg. & or ++ etc.)
``` 
 - Added `/.restore/` folder to `/.assets/media/` as a temporary store to enable undo-ing when users accidentally delete files
 - Developed New Scaffold for EtherPhysics.net, using New PageManifest References
 - Incorporated `concho()` statements into New Scaffold
 - Improved `concho()`: enabled conditions using Boolean FALSE and introduced a parameter enabling backticks around operators to be replaced with spaces
 - In the process of developing New Scaffold for EtherPhysics.net, extended, expanded and improved New PageManifest
 - Created `link rel-danis3hmodule` to reference the DaNIS3H Modules present on each page
 - Added `link rel-danis3hmodule`, `link rel-ashiva-pagemanifest` and `link rel-ashiva-sitemanifest` to New Scaffold
 - Added **title folder** to module folders (`/modulename/#%20Module%Name/`) in which to store `modulename-package.json`




______

## Developments to Add...

 - First JSON serialisation of Javascript
 - Second JSON serialisation of Javascript
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
Aug 2020 - Re-designed Henkan 2020
Sep 2020 - Learned Web Components

--- - Started thinking about ashivaModules which can handle page state (like Redux)
--- - Started learning Deno
--- - Started thinking about giving Ashiva JAMStack / Serverless capability
--- - Started thinking about what ashivaModuleManifests (currently PHP functions) would look like if they were JS functions
