The input data for all exercises is stored in `data.txt`.

# Exercises

## 1. Basic Substitution

**Task**: Replace all occurences of the name "Alice" with "Alicia".

**Expected Output**: see `expected_output/1.txt`

**Solution**: `sed 's/Alice/Alicia/g' data.txt`


## 2. Global Substitution

**Task**: Replace all commas with semicolons.

**Expected Output**: see `expected_output/2.txt` 

**Solution**: `sed 's/,/;/g' data.txt`


## 3. Case-insensitive Substitution 

**Task**: Replace the name "frank" with "Frank, ignoring case.

**Expected Output**: see `expected_output/3.txt`

**Solution**: `sed 's/frank/Frank/ig' data.txt`


## 4. Replace Only the First Occurrence on Each Line

**Task**: Replace only the first comma on each line with a space.

**Expected Output**: see `expected_output/4.txt` 

**Solution**: `sed 's/,/ /' data.txt`


## 5. Replace Only the Second Occurrence on Each Line 

**Task**: Replace only the second comma on each line with a space.

**Expected Output**: see `expected_output/5.txt` 

**Solution**: `sed 's/,/ /2' data.txt`


## 6. Print Only Lines Where a Substitution Occurred

**Task**: Print only lines where the city "seattle" appears, replacing it with "Seattle".

**Expected Output**: see `expected_output/6.txt` 

**Solution**: `sed -n 's/seattle/Seattle/p' data.txt`


## 7. Delete Lines Matching a Pattern

**Task**: Delete all lines that contain the word "george".

**Expected Output**: see `expected_output/7.txt` 

**Solution**: `sed '/george/d' data.txt`


## 8. Insert a Line Before a Matching Line

**Task**: Insert a line with "----" before each line that contains "David".

**Expected Output**: see `expected_output/8.txt` 

**Solution**: ``

## 9. Append a Line After a Matching Line

**Task**: Insert a lint with "----" before each line that contains "David".

**Expected Output**: see `expected_output/9.txt` 

**Solution**: ``

## 10. Replace Text on Specific Lines

**Task**: Replace "Bob" with "Robert" only on line 2.

**Expected Output**: see `expected_output/10.txt` 

**Solution**: ``
