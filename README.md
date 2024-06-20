# Presidents
--I have done a few cleaning processes on excel file. All steps described below:

--1. First, I removed any duplicate entries. I selected all the data and then went to the Data tab to choose "Remove Duplicates."

--2. The names of presidents were not all in the right format (some were uppercase, some lowercase). I created a new column called "President name_fixed." I used a formula called =PROPER() to make sure each name starts with a capital letter.

--3. The "Prior" column wasn't useful for my analysis, so I skipped it.

--4. The "Party" column was messy with spelling issues (like "Republican" and "Republicans"). I fixed this by selecting all the data, filtering the "Party" column, choosing both "Republican" options, and removing any unnecessary "s" to make the names consistent.

--5. There were extra spaces between words in the "Vice" column. I created a new column called "Vice fixed" and used the formula =TRIM() to remove these spaces.

--6. In the "Salary" column, there was a "$" symbol before the numbers. I needed to remove this symbol for my analysis. I selected the column, went to the Home tab, chose "Number" format, and removed any extra digits from the end of the numbers.

-- original projetc: https://www.youtube.com/watch?v=_jmiEGZ6PIY

--7. The date columns had different formats. I selected both columns, went to the Home tab, and chose the "Short Date" format to make them consistent.

--8. Finally, I removed unnecessary columns like "First" and "Prior," and also the columns I had made corrections to ("Vice" and "President"). Before removing them, I copied the corrected values from the "President name_fixed" and "Vice fixed" columns and pasted them into the original "President" and "Vice" columns. This way, the corrected data stayed correct and didn't affect any other formulas that used these columns.

