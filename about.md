FAQ
=======

### What is this tool all about?

dangercart and couple of his friends from reddit have been working on building an NBA roster management model that allows the user to enter moves and see if they comply with the CBA and what impact they have on available resources. The tool is an Excel model so it exists in two formats. We host it as a web app on [roster-builder.com](http://roster-builder.com) and also make it available to download via the link located within the embedded spreadsheet on the website.

We also have a [subreddit](http://www.reddit.com/r/capology) in which we talk about trades and their effects on salary caps. We welcome anyone who wants to engage in rational conversations about all things salary cap and the CBA.

### How does it work?

When you open the tool you can choose any team from a drop-down and it will populate their current roster. From there, the tool will lead you through the basic process to build a team. Players are classified as having been on the roster at the start of the league season or acquired during the year as this impacts available moves and for that they are listed on separate sheets. From this baseline you can select what actions you want to take; from removing players, trading them, signing new players via cap space or using exceptions.

The tool is laid out in a series of "Steps" that you can move back-and-forth through. Each move will update other sections of the tool and re-calculate your salary cap space and available contract exceptions. Many moves create a cascade so, for example, if you say you want to waive a player via the stretch provision they will then appear in that section to enter their contract details. The steps are a suggestion for how to move through your roster but you don't necessarily have to follow everything in the order that's laid out. For specific instructions, click on the "Instructions" sheet within the tool.

### Can this tool do anything? Are there some things that this tool can or can not do?

Yes. None us are programmers, so this tool is not bug/mistake proof. dangercart is trying to fix the mistakes along the way as we get feedback (which we rarely do) or we just point out mistakes that we've encountered ourselves. There are some things that this tool does well and there are some things that this tool does not do well.

Things the tool does well are:

* Gets the current roster and immediately available moves right.
* Calculates the correct cap and tax totals at the end of all your decisions.
* Calculates the maximum amount of salary cap space your decisions could create in the free agents section.
* Calculates the contract exceptions you would have available and allows you to split them up.
* Covers a wide range of moves, including the amnesty clause, stretch provision and buy-outs.
* Tries to figure out the player you are trying to acquire to give you a shortcut to their previous salary and years of service.
* Formats everything nicely at the end and tells you if you "passed" some basic CBA tests.

Things the tool doesn't do well as are:

* The tool is meant to work for a single team so trades are a challenge. You should test your trades in the ESPN Trade Machine before entering them into the model.
* We can't make you enter reasonable decisions so if you think you enter a trade for Lebron it won't tell you that it's not going to happen.
* You can type in the names of players you want to sign however you want, but it will only pull up their previous salary information if you type it exactly as it exists on their current team's sheet.
* A lot of decisions have a cascading effect. That means the order of moves makes a big deal but we can't model all of that out. We built this to assume the moves happen in an order that creates cap space but that isn't always the plan. We've entered in the moves that have already happened this year so this isn't a huge deal right now; it matter more in the offseason.

### Is this tool a replacement for the ESPN Trade Machine?

No. If anything, it's a complimentary tool to the Trade Machine. After you use the ESPN Trade Machine, you can use Roster Builder to check the effects of that trade in the books.

### Can you give me some more information about the tool?

Sure! Here's a link to an [/r/NBA](http://www.reddit.com/r/nba/comments/1rakq4/roster_builder_model_updated_with_current/) thread which contains some more information. If we have not been able to answer your question, please [email us](mailto:nba.roster.builder@gmail.com), we'd be happy to help.
