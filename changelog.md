This is the changelog for this project. New entries will be added at the bottom of the file.

eg. "Sept 27 2:30pm Example

Sept 28 4:00 Later entry"

Oct 1 3:53pm
Setup starter project to be pulled from.
-Spencer

Oct 1st 4:16pm
Combined work with newly established repository. Work included Css theme addition, creation of header with image, and
template modification for basic rendering of home page.
-Francis

Oct 1st 7:44pm
Added a receiving controller and view to display name and price of data in the supply model. Fixed the nav bar links and added routes for the future controllers.
-Francis

Oct 2nd 11:45am
Added a form column to receiving and Quantity column for a more detailed display. Modified the Receiving controller to allow for the quantity to be fetched from the supply model. Added a submission button for future logging function.

Oct 2nd 5:02pm
Created a recipe model that contains all of the data for the recipes as well as some methods for accessing.
Created a production controller to handle displaying all of the recipes as well as the details for each of the recipes.
I also created some views that are used to display the recipes, although I have a small issue with routing or the links from the show page, everything works as it should, it will just require some touching up once I figure out how to route and link with views inside folders.
-Spencer

Oct 3rd 7:36
Added a details view and function for supplies (receiving controller).
-Jason

Oct 3rd 9:00pm
Fixed the link issues I was having with the 'show' view for the recipes.
-Spencer

Oct 3rd 9:32pm
Added Sales controller with index and details function.
Added Product model; References Recipe model for name and description. 
Reordered nav bar links. 
Fixed broken nav bar link (Sales).
Cleaned up routes files. 
-Jason

Oct 6 5:53PM
Redid recipe model and recipe controller(production) so that the views are consistent and so that we now check the quantity of the items.
Adjusted the Supplies model as well to now have a new field to keep track of the stock that we have.
Adjusted some values in sales and in receiving to work with the new changes.
-Spencer/Francis/Jason (Worked on this in class collaboratively from Spencer's laptop)

Oct 6 9:25PM
Made code formatting consistent. 
Basic route validation (ex. controller/show, controller/show/888, controller/show/asdf)
Fixed views (Receiving shows onHand, detail/show views can return to index, no view contains PHP)
-Jason

Oct 8 3:00PM
Sales Order and Inventory Receipt pages finished,
welcome page shows values (no logic currently. not necessary for first assignment I dont think),
changed all Quantity labels to InStock,
formatted all money values
-Alex

Oct 8 8:20PM
Sale Receipt view content is now calculated and generated in the receipt function in Sales controller.
Added helper method for moneyFormat
-Jason

Oct 9 12:34AM
Made things more consistent throughout, changed the names of the detail views to 'show'. Changed the receipt views so
that they no longer used any PHP, updated the controllers to work with the views. Had to make some changes to the show
view as well so that it would work with the updated controller functionality. Updated the readme to be relevant to the
current state of the project.
-Spencer