# ashiva Changelog

## 2016
### Jan 2016
 - First version of website initialiser created
 - First site (Scotia Beauty) created

### Feb 2016
 - Second site (HandsOffHRI) created

### Mar 2016
 - First idea to turn website initialiser into basic CMS with login and ability to edit pages - nicknamed "CMS3"

### Jun 2016
 - First attempt to introduce editable pages (leads to my learning PHP Associative Arrays)

### Dec 2016
 - ACSSSS pioneers approach in which CSS Stylesheet is grabbed as a JS String, then parsed and turned into a JS Array, then parsed and turned into a JS Object

## 2017
### Oct 2017
 - The name "Ashiva" replaces "CMS3"
 - First attempt at creating Control Pad
 - Invention of Roles and Capabilities

### Nov 2017
 - Created SiteMap Editing Interface (to add / move / delete pages and subpages)

### Dec 2017
 - Developed first JSON serialisation of HTML


## 2018
### Jan 2018
 - First attempt to create ashivaModules in PHP with complex filters and ideas to create front-end and back-end modules

### Apr 2018
 - Developed JSON serialisation of CSS while building hackPad

### Nov 2018
- Added WebManifests to Ashiva

### Dec 2018
- PHP PageData... => JSON PageManifest
- Added Service Workers to Ashiva
- Created JSON SiteManifest

## 2019
### Mar 2019
 - JSON GUI

### May 2019
 - Da3SH Modules invented

### Jun 2019
 - CodeSheets invented

### Aug 2019
 - Third site (JamesNHSWalk) created

### Oct 2019
 - ModuleManifests formalised
 - Dynamic CodeSheets invented
 - ModuleLogic invented
 - ServerSheets invented

## 2020
### Jan 2020
 - Worked on WebWorkers as Da3SH
 - Worked on ESModules as Da3SH

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
 - Introduced "DataSheets" alongside CodeSheets and ServerSheets - but something wasn't quite right
 - Developed queryString operator `updatePageModules`
 - First experiments with JS Namespacing into Da3SH Module Scriptsheet
 - Started writing Ashiva in Deno + Oak on Heroku

### Mar 2021
 - Developed `submitData()` for Synchronous Serversheet Access
 - Developed **Ashiva_Roles** Da3SH Module
 - Successfully Async-ed Modules Stylesheet - dramatic improvement in page load speed
 - Developed queryString operator `updatePageComponents`
 - Completed **JSON Rewriter** (and, by extension, *Code Converter UI*)
 - Formalised in-Module HTTP Authentication and introduced Protected (after realising *this* is the key feature of "DataSheets")
 - Wrote **Ashiva Multi-Page Find and Replace Editor**
 - Developed **SB_Email_Subscribers** Da3SH Module
 - Re-named / re-framed *ServerSheets* as *SubPages* (or *Substitial Pages*)

 - Established both JSON Rewriter and MultiPage Editor as aSPs (?)
 - Async-ed Modules Scriptsheet (?)
 - Async-ed Main Scriptsheet (?)


 

______

## Developments to Add...

 - First JSON serialisation of Javascript
 - Second JSON serialisation of Javascript
 - JSON Sitemap
 - Da3SH Module Version Control
 - ModulePackages
 - IM:PACT
 - --- (the other thing alongside IM:PACT)
 - QuadTap
 - Henkan 1
 - JSON GUI Editor
 - Series Tool
 - PageManifest Editor
 - New ControlPad
 - SiteModules Tool
 - Languages Tool


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
