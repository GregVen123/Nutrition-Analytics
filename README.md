Analyze MyFitnessPal Data

PERFECT DATA ASSUMPTION This script only is accurate when the MyFitnessPal Data is perfect, which means that breakfast, lunch, and dinner is tracked each day that you record and NO DATA IS PUT IN THE SNACKS SECTION. If you miss a meal the script won't be accurate. For example, if you record lunch and dinner but not breakfast myfitnesspal doesn't input the meal as 0 in the CSV, it skips it which messes up the script since it translates every 3 meals into one day.

STEP 1: Retrieve myfitnesspal data: Dashboard > calories > top right corner export button (next to settings) > download CSV file and select date range
STEP 2: Extract the ZIP file and find the "nutrition summary" CSV
STEP 3: Copy the file path
STEP 4: Run the script and input the file location when it asks, make sure to not include quotes (windows usually copies quotes around the file location)
STEP 5: The script should create an Excel file called "New Nutrition Dataframe", open this and your data should be presented.



