Changelog
=======

v4.0.5
-------
*Released on 7.15.2014 - US (15.7.2014 - EU)*

* Updated logic to exclude MLE/BAE when a team has completed signings with cap space.

v4.0.4
-------
*Released on 7.1.2014 - US (1.7.2014 - EU)*

* Improved logic for counting filled roster spots for unsigned first round draft picks.
* Added logic to allow for signing prior year foreign draft picks using cap exceptions.
* Updated all RFA/UFA qualifying offer decisions.
* Updated player and team option decisions.
* Updated salaries related to trade kickers.
* Fixed various cap hold values.

v4.0.3
-------
*Released on 6.29.14 - US (29.6.14 - EU)*

* The spreadsheet has been updated to reflect the recent trades and the draft picks.

v4.0.2
-------
*Released on 6.18.14 - US (18.6.14 - EU)*

* Context sensitive "Action" drop-down menus by player classification.
* Re-organization of sections.
* Fixed hold logic for unsigned draft picks.
* Improved logic for determining MLE/RME availability.
* Added cascade logic for handling team options making a player an RFA.

v4.0.1
-------
*Released on 6.18.14 - US (18.6.14 - EU)*

* Rosters and salaries are updated for the upcoming 2014-15 season.
* Some overall design changes on the spreadsheet.

v3.0
-------
*Released on 11.22.13 - US (22.11.13 - EU)*

* Improved handling of "dead money" from previously waived players.
* Fixed calculation of luxury tax for players near the two year salary minimum.
* Added logic to differentiate one- and multi-year minimum contracts in handling of league subsidies.
* Improved process for determining Bi-annual Exception eligibility.
* Corrected classification of a number of signings that actually used exceptions.
* Removed cleared cap holds to improve performance.

v2.9
-------
*Released on 08.07.13 - US (07.08.13 - EU)*

* Signed draft picks are removed from the entry section.
* Cap holds related to players previously on the roster have been switched to not assume they will be re-signed when no status is provided.

v2.8
-------
*Released on 07.10.13 - US (11.07.13 - EU)*

* Improvement to calculation of MLE, MMLE and RME based on actual signings.
* Addition of new completed action classifications.
* Better test for sign-and-trade hard cap.
* Many roster updates.

v2.7
-------
*Released on 07.06.13 - US (06.07.13 - EU)*

* Improvement to the free agent cap space formula when the user skips re-signing their players.
* Addition of message for builds possibly below the payroll minimum.
* Many transaction updates using estimated signing information.

v2.6.2
-------
*Released on 07.02.13 - US (02.07.13 - EU)*

* Fixed the way RME signings were impacting free agent cap space.
* Fixed the 10+ years free agent minimum salary guideline for signings not on the top line of the free agency box.
* Moved T. Robinson and A. Bargnani trades to "Completed Acquisitions" list as they will be processed in the 2013-14 league year.

v2.6.1
-------
*Released on 06.28.13 - US (29.06.13 - EU)*

* Enabled tracking of actual 2013/14 moves.
* Improved calculation for tracking 2+ free agent signing cap space on teams with < 12 players.
* Entered actual draft information with pick trades.
* Entered Boston/Brooklyn trade.

v2.6
-------
*Released on 06.26.13 - US (26.06.13 - EU)*

* Roster data updates.
* Classification and max salary calculation of "Bird Rights" re-signings.
* Classification of re-signings with no salary exceptions.
* Adjustment to free agent max salary formula.

v2.5
-------
*Released on 06.23.13 - US (23.06.13 - EU)*

* Fixed error in capturing players acquired via trade in the final roster list.
* Improved Reddit formatted tables so "Total" line is listed right after the last player.
* Drop down menus now work on the web app. Thanks Microsoft!

v2.4.1
-------
*Released on 06.19.13 - US (19.06.13 - EU)*

* New mock draft.
* Update to James Harden's salary based on salary cap estimate.
* Notes added to section labels.

v2.4
-------
*Released on 06.06.13 - US (06.06.13 - EU)*

* Attempt to determine when a team only has Early or Non Bird rights to their own free agent in the "Re-signing" section.
* Calculation of the maximum salary offer a team over the cap can make for an Early or Non Bird free agent.
* Re-organization of objects to accommodate new fields.

_Pick Utah and go to 'Step2' to see these updates. This should be the last logic update unless defects are found (which they always are). I (dangercart) have some desire to test the user entries for Early and Non Bird free agent salaries but this would require an extremely difficult current cap calculation that is functionally impossible without a history of prior transactions. As it only impacts a handful of players I'm not going to do it. If the user enters bad information they'll get a bad result... The next scheduled updates will all be for data. The draft is 6/27 then 7/1 is the deadline for releasing a bunch of players and helpful retirements and then the official cap and tax figures will come out during the moratorium in the first ten days of July_

v2.3.1
-------
*Released on 06.04.13 - US (04.06.13 - EU)*

* Salary cap set to $58.5M.
* Luxury Tax set to $71.6M.
* Apron set to $75.6M.
* Added an attempt to pull last year salaries and max allowable contracts (currently using 2012/13 table) into the free agent section based on comment from [/u/laughingplague](http://www.reddit.com/user/laughingplague).
* Grant Hill and Jason Kidd retired.

v2.3
-------
*Released on 05.17.13 - US (18.05.13 - EU)*

* Added a path for entering confirmed signings during the year. If the data is entered correctly, a confirmed signing will clear the player off their 2012/13 team, place them into the new team's roster and adjust the exception balances if that's what was used to sign the player.
* Added 'Step1a' sheet to display confirmed signings. Sheet is currently hidden.
* Fixed the "Sign and Trade" CBA test based on conversation with [/u/FuManChusco](http://www.reddit.com/user/FuManChusco).
* Added an attempt to pull last year salaries and max allowable contracts (currently using 2012/13 table) into the free agent section based on comment from [/u/laughingplague](http://www.reddit.com/user/laughingplague).
* Moved around some objects and put the step dependent status calculations at the top of each page to avoid side-scrolling.
* Added version indicator and last updated dates.
* Fixed issue with not being able to add in-season "dead money" because player name cells were locked.
