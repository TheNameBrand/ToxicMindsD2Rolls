# ToxicMindsD2Rolls
Repository for a custom weapon rolls wishlist text file compatible with Destiny Item Manager.
Weapon rolls are curated by ToxicMinds community members, compiled from various sources and research. Notes are provided when possible.

# How To Subscribe
Open Destiny Item Manager and pull open the settings from the hamburger menu. Click on wishlist in the sidebar to scroll down to the wishlist section.
In the "add another wishlist" field, paste this URL: "[URL]" -- This links to the weapon file in this repository.
You're done. If any changes are made to this file, it will update over a period of 24 hours (so editors, don't expect to go farming the same day you add your god-rolls to the list).
Wishlisted items will show with a "thumbs up" in the inventory overview. If configured, "trash rolls" (bad perk combos) will be a thumbs down.
Check the Triage for notes which may say why the perk combo was wishlisted, which community member included it, etc.

# How To Edit
For editing access, DM @TheNameBrand on Discord.
Editors can push changes to the TXT file here to add rolls to the list.

You're going to want to bookmark DIMs Community_Curations README https://github.com/DestinyItemManager/DIM/blob/master/docs/COMMUNITY_CURATIONS.md as it contains all the information you need to know about how the wishlist file will be processed in DIM, so you can know how to mark things in the actual text file. Definitely read it all the way through. This will inform you on how to make notes, what sites will help you build out all your rolls, etc. I'm not going to summarize everything they have to say.

For making a very large wishlist, a simple but effective site is https://wishlists.littlelight.club/#/
This site lets you quickly spec out multiple "builds" of weapons, complete with different perk combos and descriptions for each, and then you can export the bulk list (DIM FORMAT) when done. Select what you have in the text file, and move it to the one hosted on GitHub, then commit the changes. We can worry about organizing the GitHub list as we go, as there won't be an easy way to overwrite your old inclusions, or put your Edge Transit wishlist items next to MY Edge Transit trashlist items, so that'll have to be done manually (probably). The thing to do here would be to IMPORT your same list back into the site to edit and make changes so you have your own backup.

For individual God Rolls, this can be done pretty quickly in DIM itself -- click on the weapon, click on the weapon name, select the perks, select (or PREVIEW) the masterwork, then click "Copy Selected Perks as Wishlist Roll". This will copy THE 5/5 God Roll to your clipboard, but we can change it to a 2/5 easily (SOMEONE DOUBLE CHECK THIS). You'll paste that line of code into the GitHub wishlist TXT. You can remove the hash number of the perk column that "doesn't matter" (likely your barrel and mag columns which are the first and second number after [perks=] and commit. Maybe before you do, hit up a quick CTRL+F and look for the weapon name or perhaps more reliably, its hash number (i.e. [dimwishlist:item=(I'm the hash number)] to see if you could "file it" with other wishlisted rolls under that weapon.

# TXT File Examples
You can get quickly overwhelmed by skimming through one of DIMs default wishlists: https://raw.githubusercontent.com/48klocs/dim-wish-list-sources/master/voltron.txt
But if you're familiar with DIM as a user, and have read through the Community_Curations README, how this all works will just start to click for ya.

Their list is LONG and extensive because they have a lot of PERMUTATIONS for different guns, meaning, they mix and match a bunch of barrel, mag, and perk combos that work for a million different scenarios, and are all okay in the specific noted function to some degree. I'm imagining our list to be a little more curated than that. But in the case you do want to spec out a bunch of different but equally viable Edge Transit rolls there are tools to help you build out those permutations, found in the Community_Curations README above. Those tools will probably be faster than just copying the line of code right from DIM. What also would be faster is if you opened other wishlists (say, the one from above), and did a CTRL+F on the weapon you're thinking of. High chances they've done the hard work on the roll you're thinking of, can copy and paste it into the ToxicMinds TXT. Just don't forget to replace the description with your own quippy fun one haha.

Here's how I'm imagining our wishlist to look when it comes to individual weapons:

[// Tusk of the Boar (PvE 2/5)
// Slice, Deconstruct
//notes:(2/5 Roll) Deconstruct on a waveframe means you can practically use this as a primary weapon in places with high minor ad counts like Onslaught, and Slice is the icing on the cake. Definitely need one of these before Final Shape. MW:Reload -CrazedChrizz|tags: PvE, PvE-MinorSpec, PvE-EndGame dimwishlist:item=1218113510&perks=923806249,3993379141

// Tusk of the Boar GodRoll (PvE 5/5)
// Quick Launch, High-Velocity Rounds, Slice, Deconstruct
//notes:(PVE GODROLL) Deconstruct on a waveframe means you can practically use this as a primary weapon in places with high minor ad counts like Onslaught, and Slice is the icing on the cake.  -CrazedChrizz|tags: PvE, PvE-MinorSpec, PvE-EndGame, PvE-God, M+KB, Controller
dimwishlist:item=1218113510&perks=3525010810,2822142346,923806249,3993379141,2120661319

// Indebted Kindness TrashRoll
// Loose Change, Surrounded
//notes:Listen, there are some great perks for this gun, but Loose Change, Surrounded? Shard on sight. Inspired by (YouTuber name) -TheNameBrand
dimwishlist:item=-3381450498&perks=1119449540,3708227201]

We'll kinda feel it out as we go and figure out better tags and naming conventions, but all this info... should give us a nice start.
I also don't know where to add it but if you use certain weapons a ton, add those too! I think it would be fun to be able to see in the wishlist notes if I (or anyone) just so happens to pick up the exact roll of (playernames) ol' reliable (whatever weapon it is) with thousands of kills or what have you.
