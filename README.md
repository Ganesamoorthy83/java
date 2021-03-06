# Sort Application

# Reuirement Understandings:
   - Application can be sort a numerical values in ascending order.
   - Sort a given amount of numerical values by randomly change position of the values.
   - Should show the sorted numbers in ascending order with time duration of sorting process and numbers of position changes swapped. 
   - Should show all previous results.
   - The previous results must also remain if the application is restarted.
  
# Technology Used
  Spring Tool Suite 3.8.3,
  Spring Boot 1.5.3,
  Bootstrap,
  AngularJS,
  Java 1.8,
  Apache Commons Lang3 API,
  Log4j
  
# Setup and Run
   - Download and unzip the source repository for this guide, or clone it using Git: git clone https://github.com/Ganesamoorthy83/java.git
   - To setup application in STS environment please download & refer document from git "Sort Application Setup Guide.docx" which contains all the screenshots of below steps. Otherwise follow the below steps.
   - Open Spring Tool Suite.
   - Go to File -> Import
   - Select Existing Maven Projects into Workspace and click on Next button.
   - Selct Root Directory of extracted source folder.
   - Click Finish.
   - Press Ctrl+Shift+R to open java resource.
   - Enter SortApplication.java
   - Click on Open button.
   - Right click on the SortApplication.java source file. Go to Run As -> Java Application
   - Make sure your embedded server started.
   - Hit application url http://localhost:8080/
   - Displays Sort Application page.
   - Enter un sorted numbers and click on Sort Numbers button.
   - Click on Sort Numbers button.
   - Displays Sorted numbers in ascending order, duration, changes of positions.
   
# Run through SortNumbers-0.0.1-SNAPSHOT.jar
   - Download SortNumbers-0.0.1-SNAPSHOT.jar using git url https://github.com/Ganesamoorthy83/java/blob/master/Sort/target/SortNumbers-0.0.1-SNAPSHOT.jar
   - Navigate to download directory
   - Double click on the SortNumbers-0.0.1-SNAPSHOT.jar file.
   - Hit url http://localhost:8080/
   - Enter un sorted numbers and click on Sort Numbers button.
   - Displays Sorted numbers in ascending order, duration, changes of positions.

# Sample Inputs
      Un sorted numbers:
      13,14,86,21,3,38,74,33,22,34,78,74,32,80,62,75,2
      49,8,7,81,9,46,62,53,83,49,39,76,55,15,62,7,45
      60,55,48,90,91,46,12,73,77,43,53,31,89,47,32,77,45
      5,48,42,35,13,29,55,84,49,95,74,24,70,43,47,12,62
      28,9,72,64,46,87,99,84,93,100,71,24,63,55,37,59,68
