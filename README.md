# NinjaFoodiRecipes
Reference for accessing Ninja Kitchen Recipes via their API

**Recipe URL**: [https://www.ninjakitchen.com/api/recipe/](https://www.ninjakitchen.com/api/recipe/?q=&sort=Newest&tags=&page=1)
Parameters:
 - **q**: Search term(s), see `response.filters.q`
 - **sort**: Sorting method ("Newest", "A-Z", "Z-A"), see `response.filters.sort` and `response.filters.sortables`
 - **tags**: Search tag(s), see `response.tags`
 - **page**: Pagination number. Responds with a pagesize of 10, see `response.totalRecipeCount` to calculate # of pages

## Recipe Data
Notes on recipe json:
 - **recipeId**: Id of resource
 - **title**: UI-safe Title of Recipe
 - **prepServe**: UI-safe Recipe Prep-Time
 - **cooktime**: UI-safe Recipe Cook Time
 - **servings**: (string) Number of servings
 - **description**: UI-safe Recipe Description
 - **ingredients**: RTF Ingredients list
 - **instructions**: RTF Instructions
 - **nutritionFacts**: ???
 - **image**: Recipe image???
 - **hasTip**: (binary) Boolean of tooltip availability
 - **tip**: Tooltip text
 - **specialNote**: ???
 - **isHealthfullyBalanced**: (binary) Boolean
 - **isLowCalorie**: (binary) Boolean
 - **isGlutenFree**: (binary) Boolean
 - **isChefInspired**: (binary) Boolean
 - **isPitcher**: (binary) Boolean
 - **isSingleServeCup**: (binary) Boolean
 - **isMealMaking**: (binary) Boolean
 - **isLunchBox**: (binary) Boolean
 - **averageRating**: ???
 - **isDetoxCleanse**: (binary) Boolean
 - **isHeartHealth**: (binary) Boolean
 - **isLongevityBeauty**: (binary) Boolean
 - **isMoodImmunity**: (binary) Boolean
 - **isWeightLoss**: (binary) Boolean
 - **publishStartDate**: ???
 - **publishEndDate**: ???
 - **seoExtensionId**: ???
 - **searchKeywords**: ???
 - **variantOf**: ???
 - **recipeImage**:
   - **altText**: 
     - **large**: Alternative Image Text for Large rendering
     - **small**: Alternative Image Text for Small rendering
   - **large**: Large Image relative URL
   - **small**: Small Image relative URL
 - **titleForUrl**: Title used in the navigation URL
 - **recipeUrl**: Relative URL to the Recipe page
 - **tagsCollection**: ???
 - **tagIdsCollection**: ???
 - **mediaCollection**: ???
 - **productsCollection**: ???
 - **stepsCollection**: ???
 - **variantsCollection**: ???
 - **relatedRecipes**: ???
