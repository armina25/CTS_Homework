# CTS_Homework

The first method I chose to test is if the selection of the input data for my paper from the German Traffic Sign database is done correctly. 

Right B.I.C.E.P
1. Are the results right? 
In order to answer this question, I put the results into a data file and run tests to check if the results are what I expected. 
2. Are all the boundary conditions CORRECT?
I ran boundary tests to check if there are any null values, to check if the images have the desired size and number of pixels or if there is any badly formatted data, such as a blurred image. I also used exceptions, in case any of the presented situations occured. As it happened to have an empty collection, I created a new boundary test to fix it. 
3. Can you check inverse relatinships? 
I used an inverse test to check if all my input data was successfully added to my application, by searching for each traffic sign image. 
4. Can you cross-check results using other means?
I used cross-check tests to make sure that the amount of data that I put into the training dataset is complementary with the amount of data that I put in the testing dataset. 
5. Can you force error conditions to happen?
As I considered that I might encounter problems with the network or my computer memory, I created such tests and as a result I decided to write the code both locally and using the network when available. Also, everytime I did any changes, I would upload it on my Drive account, to make sure that no data is lost. 
6. Are performance characteristics within bounds?
In order to make sure that the performance curve remains stable, I wrote some tests to check how fast will my program check the input data by giving it only few pictures at first and gradually increase the number of input data. 

CORRECT
1. Conformance — Does the value conform to an expected format?
I wrote the conformance test to make sure that all my images have the exact and same number of pixels. 
2. Ordering — Is the set of values ordered or unordered as appropriate?
I did not need the data to be ordered in any way, so I did not create an ordering test.
3. Range — Is the value within reasonable minimum and maximum values?
I created a range test to check if my input data had a minimum of 15 images and a maximum of 45. In case this does not happen, I throwed exceptions. 
4. Reference — Does the code reference anything external that isn’t under direct control of the code itself?
My method does not depend on anything external, so I did not write a reference test. 
5. Existence — Does the value exist (e.g., is non-null, nonzero, present in a set, etc.)?
I ran an existence test to check if the URL that I used for my input dataset is not an empty or not working URL. I also used an existence test to check if the URL I put in the code to upload my result is not an empty one. 
6. Cardinality — Are there exactly enough values?
I used a cardinality test to see if the code will work if I have the maximum limit n, n being a value that changes. 
7. Time (absolute and relative) — Is everything happening in order? At the right time? In time?
I also ran a time test to check if the steps of the selection are done in the correct order: first to access the database URL, 2nd to extract all the data and put it into a data file, 3rd if the images are checked to have the same number of pixels and 4th if the results are uploaded on the drive URL. 

The second method I chose to test is if the output results are correct.

Right B.I.C.E.P
1. Are the results right? 
In order to answer this question, I put the results into a data file and run tests to check if the results are what I expected. 
2. Are all the boundary conditions CORRECT?
I ran boundary tests to check if there are any null values, to check if the images have the desired size and number of pixels or if there is any badly formatted data, such as a blurred image. I also used exceptions, in case any of the presented situations occured. As it happened to have an empty collection, I created a new boundary test to fix it. 
3. Can you check inverse relatinships? 
I used an inverse test to check if all my results were successfully added to my application, by searching for each traffic sign image. 
4. Can you cross-check results using other means?
I used cross-check tests to make sure that the result has the correct description of the traffic sign by checking the descriptions I wrote for each sign. 
5. Can you force error conditions to happen?
I ran tests to see if the Drive URL is correct and the network connection is stable so that the results are successfully uploaded.
6. Are performance characteristics within bounds?
In order to make sure that the performance curve remains stable, I wrote some tests to check how fast will my program check the input data by giving it only few pictures at first and gradually increase the number of input data that needed to be checked. The output was correct every time.


CORRECT
1. Conformance — Does the value conform to an expected format?
I wrote the conformance test to make sure that all my images have the exact and same number of pixels. 
2. Ordering — Is the set of values ordered or unordered as appropriate?
I wrote an ordering test to make sure that the order of the traffic signs images correspond to the ordeer of the descriptions for each image. 
3. Range — Is the value within reasonable minimum and maximum values?
I created a range test to check if my results had a minimum of 1 and maximum 5 images. In case this does not happen, I throwed exceptions. 
4. Reference — Does the code reference anything external that isn’t under direct control of the code itself?
The storing of the results depend on the network connection to be available so I can save every output.  
5. Existence — Does the value exist (e.g., is non-null, nonzero, present in a set, etc.)?
I used an existence test to check if the Drive URL I put in the code to upload my results is not an empty one. 
6. Cardinality — Are there exactly enough values?
I used a cardinality test to see if the code will work if I have the maximum limit n, n being a value that changes. 
7. Time (absolute and relative) — Is everything happening in order? At the right time? In time?
