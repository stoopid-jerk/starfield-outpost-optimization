# Starfield Outpost Optimization

## Description
This spreadsheet will help you manage your outpost production rates to avoid two common and massively annoying bugs related to overproduction:

- Cargo Links breaking
- Extractors breaking

 **DO NOT CUT AND PASTE VALUES BETWEEN CELLS** - It will break the conditional formatting rules and underlying functions										

## Instructions
1. **Conventions**:
     - Grey cells: auto-populated. Do not enter anything into them
     - Green cells: this is where you put your information
     - Red cells: auto-populated, but important information you should be paying attention to
														
3. **Advice**: Using an in-game naming convention for your outposts and identifying them by resource production is super helpful here																
																
4. **Resource List**: Ensure the resources you need are listed on the "**Resource List**" tab. Add in whatever is missing.
     - If values for standard/commercial/industrial are not in the list, create an outpost and test it out. Be mindful of the random bonus from Special Projects 4. Delete and rebuild if necessary
																
5. **Locations**: Enter details about your outposts on the "**Locations**" tab
     - Make sure you maintain the 100% scanned indicator. The 10% shift can blow up your whole operation
																
6. **Target Rates**: Add the names of the farms you want to track in this spreadsheet
     - Add your farm to the list and if this is your intial creation, set the target rate to 1 for now
     - Your target rate for your farm should be the lowest "**Unit Rate**" from the "**Farm**" tab. This is your bottleneck. 
     - You may not have the lowest "**Unit Rate**" available now, but you will later and can update the values in this tab
																
7. **Production Rates**: Now it is time to use the "**Farm Production Rates**" tab.
     - This tab is the spot you will use to see if your outpost production rate exceeds cargo links. The tab assumes one resource per link per outpost.
     - Add your Outposts and the Resources that outpost is PRODUCING. If you are harvesting aluminum and iron and use a fabricators to convert those resources into adaptive frames to export through a cargo link, you should list ALL THREE in "**Farm Production Rates**"
     - Make sure you update the Constellation and Outpost Management 4 bonuses to reflect your character's situation
     - Update the number of Engineer Bots and put in details on the Extractors and/or fabricators you are using for the resource
     - Note that fabricators are always put into the "**Standard**" column
     - Now you should have information about where your posts are right now
         - Rows highlighted in red indicate where your production exceeds the rate the cargo links can move the product
         - Rows highlighted in yellow are where fabricators overproduce. Fabricators are generally mediated by their underlying resources, but it is still a smart idea to adjust them appropriately
																
8. **Farm**: Now it is time to update the Farm tab by adding your details to it
     - Fill in the "**Prod Target Rate**" you need for your list. You can add multiple farms to on Farm tab or make copies of it to keep the farms separate
     - The tab assumes that you have an outpost where all the elements you need are delivered so that you can farm xp at a crafting table or farm end products for credits
     - List out the elements for your farm(s). You can have multiple farms at your outpost (e.g., Ni, Co, Cu, and Be to one outpost would allow you to xp farm Tau Grade Rheostat and Isocentered Magnets)
     - Add the number you need for the farm (e.g., 1 Supercooled Magnet needs 1 Isocentered Magnet, 1 Isotopic Coolant, and 3 Neodymium)
     - There are seven "**Source**" columns to represent the ways an outpost can acquire the resource (harvest it locally or receive it from up to 6 cargo links)
     - Take the lowest value in the "**Unit Rates**" column and use that for the "**Rate per Min**" value for your farm (optionally, you may recognize that the lowest value is safe to increase. If that is the case, update the "**Production Rates**" tab and then re-evaluate this tab for the new bottleneck
																
9. **General Flow**: Use the "**Production Rates**" tab to maximize your outpost production without overloading your cargo links. Check the "**Farm**" tab for the lowest "**Unit Rate**" and put that value into the row corresponding with your farm in the "**Target Rates**" tab. Go back to the "**Farm**" tab to check the how optimize each resource is. Adjust your "**Production Rates**" tab to get everything as close to 100% as possible. Rinse and repeat. Being a little under is better than a little over because a 101% optimization means your resource will eventually jam something up since it is overproducing (albeit, slowly)																
