=============
Batch Recipes
=============

Batch Recipes are built from Raw Materials. Batch Recipe records include Ingredients & Costing, Instructions, Recipe Yield, Batch Weight, Quality Assurance, Shopping List, Nutrition Label, Claims, Recipe as Ingredient, Lab Analysis, and Expiration information. 

Use the Search function to narrow down a long list of Batch Recipes and find a specific Batch Recipe. On the Batch Recipes header, you can also quickly see how many Batch Recipes are on your list. For example, the Batch Recipes list below has three entries:

.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/batchRecipes.png


*How to Add a New Batch Recipe*
	
	1. Click the Plus icon on the Batch Recipes header to add a new Batch Recipe to your Batch Recipes list.
	
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/addNewBatchRecipe.png
	
	2. A New Item form will appear. Enter the Batch Recipe Name and a short Description. Then click Save.

		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/newBatchForm.png

	3. The New Item form will disappear, and the New Item will now be listed under the Batch Recipes list.

*How to add Raw Materials to a Batch Recipe*

	1. A newly added Batch Recipe will have no Raw Materials added as ingredients. They must be added by dragging and dropping Raw Materials to the associated Batch 			Recipe. 
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/addRawMatsToBatchRecipe.png

	
	2. When a Raw Material is added to a Batch Recipe, the Ingredients & Cost, Shopping List, and Nutrition Label is automatically populated with information from the 		Raw Material record. 
	

*How to Edit an Existing Batch Recipe*

	Once a Batch Recipe has been created, you will need to edit the Batch Recipe to add Instructions, Batch Weight (Recipe Yield), Quality Assurance, Claims, and Expiration. You will also be able to set Recipe as Ingredient and Add Lab Analysis at this point.

	1. To edit an existing (or newly created) Batch Recipe, hover over the Batch Recipe of interest.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/editBatchRecipes.png

	2. Click the Edit icon from the mini pop-up menu.
      3. The Batch Recipe form will appear. The menu on the right-hand side of the Batch Recipe form allows you to navigate to different pages of the Batch Recipe, while the page content is situated on the left-hand side. 
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/editBatchRecipe.png


	
*Ingredients & Costing*

	4. You start on the Ingredients & Costing page, which lists the following information:

		- Ingredient name – pulled directly from Raw Material record	
		- Ingredient Yield (%) – enter how much of the ingredient ends up in the Batch Recipe
		- Quantity – enter the quantity using the unit of measurement chosen on the Raw Materials Recipe Measurements page. 
		- If Bread is listed with a slice being 29g, then you would enter the number of slices of Bread in a single batch.
		- If Egg is listed with a unit of 1 gram, then you would enter the number of grams of Egg in a single batch.

		- Ingredient Percentage – automatically populated by the software by multiplying the set Quantity by the Recipe Measurements from the Raw Material entry to 			calculate the Ingredient volume, then finding the percentage of the total recipe volume.
		- 2900g of Bread (29g x 100 slices)/ 5400g * 100 = 53.70%
		- 1000g of Egg /5400g * 100 = 18.52%
		- 500g of Sandwich Shells (10g x 50 shells)/5400g = 9.26%
		- 1000g of Mayo/ 5400g = 18.52% 

		- Cost Per Ingredient – automatically populated by the software by multiplying the Ingredient Quantity by the Unit cost.
		- If Bread costs $2.51 per 200g, then a 29g slice = $0.3639
            - Therefore 100 slices of Bread = $36.39 

		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/costPerIngredient.png

		
	At the bottom of the Ingredients & Costing page is a Total tally of the Batch Recipe Ingredient volume and costs.

		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/batchVolumeAndCosts.png



*Instructions*

	5. Add preparation Instructions by clicking the Plus button. Rearrange the Instructions order as needed using the hamburger icon. To remove a step, click the X icon.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/preparedInstructions.png

	6. Print Batch Recipe Instructions in PDF format by clicking on the Printer icon on the menu.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/printBatchRecipes.png


	7. Save on your computer and open PDF. Print to enjoy a hard copy of the Instructions list.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/pdfBatch.png
		
*Recipe Yield*

	8. Recipe Yield is not an individual paged. Recipe Yield is auto-calculated as a percentage once the Ingredients & Costing and Batch Weight pages are filled out. No 		manual entry is possible.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/recipeYield.png

*Batch Weight*

 	9. Click Batch Weight to open a small box for entering the Total Batch Weight (once prepared) and the Units Yielded.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/batchWeight.png

		- In the Egg Sandwich example, the resulting Batch Weight is 3450g for 50 Egg Sandwiches


	10. Click Save, and the box closes.
	11. Recipe Yield now automatically populates by dividing the resulting Batch Weight by the initial weight of all Ingredients.
		
		- (3450g of Egg Sandwiches / 5400g of Ingredients for Egg Sandwiches) * 100 = 64% 

*Quality Assurance*

	12. Add Quality Assurance information by setting the QA Attribute, Data Type, and Required or Not Required. Choose from the following QA Attributes:

		- Consist
		- pH
		- Brix
		- aW
		- Moisture Content
		- Sal
		- Scoville
		- Initial Weight 
		- Water Temperature
		- Calibration Check 	
		- Humidity

		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/batchQAAtt.png
		
*Shopping List*

	13. The Shopping List is created automatically by combining information from the Batch Recipe Ingredients & Costing page and the Raw Material entries. 

		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/shoppingList.png	
		
		Any Recipe as Ingredient items, like the Mayo, are batched separately and will show 0 Units Per Batch.

	14. Print Batch Recipe Instructions in PDF format by clicking on the Printer icon on the menu.

		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/printBatchInstructions.png

*Nutrition label*

	15. The Nutrition Label page is another pre-filled page combining the information from the Raw Material entries and Ingredients & Costing page. All fields can be 		edited as needed.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/nutritionLabelBatch.png


*Claims*	

	16. Add any Claims that apply to the entire Batch Recipe by clicking the Plus icon next to Recipe Claims. Choose from the drop-down menu of previously created 			options or enter a new Claim.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/claimsBatch.png

*Recipe as Ingredient*

	17. To set a Recipe as Ingredient, meaning the Batch Recipe will be used as an Ingredient in other Batch Recipes, click the Recipe as Ingredient option on the menu. 		The checkmark denotes that the Batch Recipe now has the designation of Recipe as Ingredient. Select Also Sold Item if the Batch Recipe is also sold on the Menu 		as an individual item.  Set the Recipe Measurement.
	
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/setBatchRecipeAsIngredient.png
	18. To remove Recipe as Ingredient from a Batch Recipe, click on the checkmark, then click OK on the confirmation message.

*Add Lab Analysis*
		
	19. Drag or Drop one or more files onto the gray area to Upload a Batch Recipe Lab Analysis. Or click the gray area to open your folders so you can navigate to the 	    Lab Analysis.   

		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/labAnalysisBatch.png

		
*Expiration*		

	20. Expiration does not have its own discrete page. It is listed in line with the rest of the Batch Material menu. To add Expiration information, simply add the shelf life in Days and/or Years.

		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/expDateBatch.png

	21. You have now finished editing an existing (or newly created) Batch Recipe. Review each page and then click Save.

*How to Print a Batch Recipe*

	1. Hover over the Batch Recipe to be printed and click on the Printer icon.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/printBatchRecipe.png
	
	2. Save the Batch Recipe PDF. The overall Batch Recipe PDF contains the Batch Recipe Ingredients & Costing information, the list of Instructions, and the Expected 		Weight and Expected Yield.
		
		.. image:: C:/Users/filip/Desktop/CibosMenu/docs/setup/saveBatchToPDF.png
	
		
  

	

