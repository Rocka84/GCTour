GC Tour NG - Changelog
======================

version 1.2.0:
 * changed links in footer
 * rewrote README
 * removed contact form, use GitHub if you need to get in touch

version 1.1.0:
 * MISC: moved language strings to dedicated json files
  
version 1.0.0:
 * FIXED: send2cgeo working
 * FIXED: Cache downloads in Chrome
 * MISC: reimplemented some synchronus request as Promises (Chrome/Tampermonkey doesn't allow synchronous requests)
 * NEW: save GPX-file directly via JS (no request to madd.in needed)



# Forked from "GC Tour" @ https://gist.github.com/DieBatzen/5814dc7368c1034470c8

version 2.3.14271, revision 8
 * FIXED: display of last 4 logs in print preview is now independent of max. number of logs
 * MISC: option "all" in Settings - Printview - Number of logs... disabled (didn't work anyway)
 * MISC: some code review

version 2.3.14271, revision 7
 * FIXED: autoTour didn't work from map when called from http (as opposed to https)
 * NEW: automatic updates from Gist repository (probably checked once a week)
 * MISC: improved code readability by applying a code beautifier 

version 2.3.14271, revision 6
 * FIXED: print issue in Firefox
 * FIXED: number of logs in print preview was dependent of max. number of logs in GPX files
 * NEW: GCTour now supports unpublished listings
 * NEW: revision number in GPX files

version 2.3.14271, revision 5
 * FIXED: adding caches to tour from bookmark and search lists: single, marked, all
 * FIXED: completion of auotTour re-design part: German translations in dialog were missing
 * FIXED: on GS public profile page boxes with owned caches/trackables were shown at the bottom of the page
 * FIXED: route menu from "show caches on map" page removed (not working as expected)
 * UPDATED: most links now use https instead of http
 * UPDATED: improved visibility of buttons for adding all or marked caches from search/bookmark lists
 * UPDATED: autoTour dialog now shows a center point on all pages (cache coordinates on cache pages and home coordinates from GS profile settings else)
 * NEW: GitHub link to GCTour footer added
 * NEW: revision to GCTour identifier added
 * NEW: changelog for revisions added

version 2.3.14271, revision 4
 * FIXED: GS layout changes

version 2.3.14271, revision 3
 * FIXED: GS layout changes
 * FIXED: send to GPS
 * FIXED: change coordinates didn't work due to a conflict with script "Geocaching.com + Project-GC 1.4.9"
 * FIXED: now all GS date formats work

version 2.3.14271, revision 2
 * FIXED: GS layout changes

version 2.3.14271, revision 1
 * MISC: initial import to https://gist.github.com/DieBatzen/5814dc7368c1034470c8

version 2.3.14271
 * FIXED: "Add to tour" is now working from the map
 * FIXED: Setting the default width of the print view
	 - FIXED: Printview is now working again if you generate it from the gc.com map
 * UPDATED: autoTour dialog -> Coordinates are taken from geocache detail page
 * UPDATED: autoTour dialog -> special filter extended with "Only PM cache"

version 2.3.14249
 * FIXED: Printview is now working _AGAIN_
 * FIXED: Printview now contains travelbugs again
 * NEW: "send message to the author" now contains a response email address

version 2.3.14198
 * FIXED: Printview is now working again
version 2.3.13263
 * FIXED: gc.com update

version 2.3.13241
 * NEW: Notifications with proper localisations and look
 * FIXED: Issue 50 (Send to GPS always sends GC14PCD)

version  2.3.13239
 * FIXED: Issue 45, 47 and 49

version 2.3.13018
 * FIXED: Tour upload is working again

version 2.3.12356
 * FIXED: Issue 31
 * FIXED: wrong geocaches size in languages other than english
 * FIXED: wrong geocache location in languages other than english/german
 * FIXED: Bug on map that you need to log in
 * FIXED: Issue 42 "Add to tour" button on map
 * FIXED: Some minor CSS glitches

version 2.3.12147
 * FIXED: Issue 37 and 39
 * UPDATED: buttons of searchpage and bookmarkpage adjusted
 * UPDATED: jquery to 1.7.2 and jquery-ui to 1.8.18
 * UPDATED: GPX -> cache-attributes to log settings, default = false
 * NEW: printview -> icon to add and underline if user has changed the coordinates

version 2.2.12059
 * FIXED: autoTour menu button
 * NEW: maps show now details if you click on a marker

version 2.2.12058
 * FIXED: new geocaching.com maps are now supported again

version 2.2.12043
 * FIXED: autoTour - but still issues with GCVote, please disable this to use autoTour!
 * FIXED: OwnWaypoints and moveCoordinates
 * REMOVED: annoying alert on search page

version 2.2.12042
 * FIXED: printview -> Bug with GCComment version
 * FIXED: searchpage in-use with Userscript GCVote
 * FIXED: Issue 22, 32 and 33
 * REMOVED: dojo completely removed

version 2.2.12003
 * FIXED: GPX -> ALL caches were either not found or found
 * FIXED: printview -> Unsupported type for GM_setValue (Your Account Details -> Date Format)

version 2.2.12002
 * FIXED: Map issues
 * FIXED: Upload Tour
 * FIXED: exception SyntaxError JSON.parse unexpected character by download tour
 * FIXED: exception TypeError progressBar is undefined
 * FIXED: function getlogs
 * FIXED: GPX found Caches from "<sym>Geocache</sym>" to "<sym>Geocache Found</sym>" (big thanks to Vasek)
 * UPDATED: French translation - thanks pascal
 * UPDATED: css adjustments
 * NEW: Map height is now variable
 * REMOVED: geocaching.com.au Type -> Groundspeak is now the only GPX Type

version 2.1.11313
 * FIXED: GPX Download bug "...ctl00_hlSignOut... is undefined"
 * FIXED: Issue 18
 * FIXED: Update bug
 * NEW: Update added link in the error-Dialog
 * NEW: User can write a message in the error-Dialog

version 2.1.11293
 * FIXED: <=3 Logs in printout -> "Last4Logs" (L4L) in the printout
 * FIXED: Logs in GPX (Unicode hexadez.)
 * UPDATED: dutch translation
 * Add jQuery (1.6.4) and jQuery-ui (1.8.16)

version 2.1.11285
 * FIXED: autoTour
 * FIXED: GCTour on the search page
 * FIXED: Logs in printout
 * FIXED: Logs in GPX
 * UPDATED: french translation
 * GPX: New Groundspeak implementation to prevent XML errors
 * NEW: Titlepage in the printview now contains coordinates and basic informations
 * NEW: printview contains now the PM cache note!
 * NEW: delete button for current tour
 * NEW: "Last4Logs" (L4L) has been added to the printout - similar to http://www.gsak.net/help/hs11980.htm

version 2.0.11280
 * FIXED: silent update changes from gc.com

version 2.0.11239
 * FIXED: GPX bug

version 2.0.11206
 * FIXED: GPX bug after gc.com update
 * FIXED: Printview after gc.com update

version 2.0.11158
 * FIXED: scrollbar bug Firefox 3.6
 * FIXED: "Search For Geocaches" page in Firefox 3.6
 * FIXED: Bug with new GCComment version
 * FIXED: bug in popup after uploading an tour
 * UPDATED: french translation

version 2.0.11158
 * FIXED: Event-Cache bug
 * FIXED: Printout need some work
 * FIXED: Update dialog bug
 * FIXED: autoTour dialog
 * FIXED: Layout modifications from gc.com
 * FIXED: autoTour find now earthcaches
 * FIXED: own waypoints coordinates were sometimes wrong rounded
 * GPX: Logs does now have an unique id
 * GPX: Archived/Unavailable geocaches are marked so
 * MAP: Tweak code on the map site. The use of the map will now be much faster.
 * NEW: Coordinates of geocaches can now be moved.
 * NEW: Added a dialog to send me a message.
 * NEW: Geocaches can now printed directly from their detailspage
 * NEW: Tour upload has been completly redesigned
 * NEW: Support for the new beta Maps
 * NEW: Dutch translation (thanks to searchjaunt)
 * NEW: Portuguese translation (thanks to Ruben)
 * NEW: French translation (thanks to flashmoon)
 * NEW: Added support for all GC.com date formats
 * NEW: GCComment print view implementation
 * ... and much more i already forgot

version 1.97.11033
 * FIXED: gccom layout change.

version 1.97.10361
 * FIXED: autotour with new OCR program
 * FIXED: GPX/Print now contains correct hidden date
 * FIXED: geocaches lists now are shown correctly again
 * NEW: Google-Appengine program to decode D/T/Size images

version 1.97.10356
 * FIXED: GCTour is now working after gc.com update #2

version 1.97.10313
 * FIXED: GCTour is now working after gc.com update

version 1.97
 * GPX: add <groundspeak:name> to GPX
 * GPX: Additional Waypoints now named - Waypoint.Prefix + (GCID without leading GC)
 * GPX: changed Groundspeak "Multi-Cache" to "Multi-cache"
 * GPX: fixed earthcache type
 * GPX: changed log id to a usable value - Issue3
 * GPX: added attributes to Groundspeak GPX
 * FIXED: caches can remain in watchlist without error
 * FIXED: that a tour remains in list after deleting
 * FIXED: autoTour is working after update 7/28/10
 * FIXED: superscript text is now shown correct in printview
 * NEW: Bookmark Lists now have "add to tour" buttons
 * NEW: Tour can now sorted via drag n' drop
 * NEW: Add check on Firefox >= 3.5
 * NEW: Minimal-printview containing cacheheader, hint and spoiler images
 * NEW: Recode the complete update routine
 * NEW: Add check whether the script is still logged on when scraping data
 * CHANGED: Renew the buttons
 * MISC: Code Review
 * MISC: Create repository at http://code.google.com/p/gctour/
 * MISC: Start implementing http://gctour-spot.appspot.com/

version 1.96
 * gc.com layout update 6/29/10 fixed
 * new groundspeak GPX implementation
 * close-window-button get a function in printview
 * removing annoying debug messages on maps
 * add an check after 20sec if gctour is loaded - important for no script users
 * caches on printview are now numbered
 * own waypoints are now uploaded again
 * tour uploads had now a map on gctour.madd.in
 * autoTour gets an option to filter PM-Only caches
 * update to dojo 1.4

version 1.95
 * gc.com layout fixes
 * repair the "add selected caches"-to-tour button

version 1.94
 * hints are now in the printout again

version 1.93
 * fixed major functions after layout update
 * new code for the printview
 * remove the download-complete-map-button from maps page - please use autotour instead
 * some minor bugfixes

version 1.92
 * add gpx option - old groundspeak schema or new geocaching.com.au schema
 * autoTour now part of GcTour
 * GUI improvements - now every tab is up-to-date
 * strip 'GC'-Option for GPX-Files
 * add OSM-Maps to the overview maps
 * append OSM and Topo Germany to default Maptype-Option

version 1.91
 * Fast GPX-File bugfix! Type of caches is now correctly set!

version 1.9
 * New-GcTour-GPX with geocaching.com.au/opencaching.de schema! Contains now logs and description for _ALL_ users.
 * Add dojo to make some DOM operations MUCH faster. Printview e.g. is now MUCH faster.
 * GUI improvments
 * Attributes are now shown in the printview

version 1.85
 * fixed bug that own marker have wrong coordinates in printview
 * redesign of the cache list
 * redesign of "create new marker"-dialog
 * adding preview map to "create new marker"-dialog
 * adding "move to top/bottom" button to cache list - thanks to adam r
 * adding map size control in printview maps

version 1.8
 * adding overview page to printpage
 * creating map with all caches on it
 * outline map for every cache + additional waypoints
 * adding costum waypoints
 * the GPX contains now the current date
 * adding information button to show which cache is in tour before loading

version 1.7
 * adding upload feature
 * removed bug, that gctour is not able to handle multiple tabs
 * implement sorting
 * adding text size option for the printview

version 1.6
 * fixed downloaded gpxfile - html-/ no-html-mode
 * add some fancy sliding effects
 * add multiple tour function
 * add trackables to printview
 * some minor bugfix (e.g. extended table on gc.com map)

version 1.5
 * add download GPX-button
 * add additional waypoints to printview
 * add an add all button to the map. thx atornedging
 * fixed some mutated vowel bugs in GPX
 * tweak update function
 * adding changelog to updatedialog

version 1.4
 * fixing bug, that premiummembers dont have coordinates in the printview
 * adding logcounter to printview

version 1.3
 * adding buttons to the search tables
 * progress is now displayed in the print view and GPS Export
 * adding language support

version 1.2
 * optimizing printview
 * add the possibility to export the spoiler images to the printview
 * add an add-to-tour-button in the GC-Table on the right side of the map view
 * fixed minor bug in the settings

version 1.1
 * extended printview - it is now possible export logs and remove images/logs
 * update function is now working ...

version 1.0
 * initial release
 
