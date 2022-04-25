This week, we worked extensively on a java program that extracts links from a text file. My team made 3 changes which solved different bugs of the program that caused unexpected outputs with different user inputs. 

#CHANGE 1:
● Screenshot of the code change diff from Github:
<img width="1229" alt="Screen Shot 2022-04-24 at 11 45 17 PM" src="https://user-images.githubusercontent.com/65497162/165034651-7bf063ec-9d12-4346-a531-77bf417cb7a8.png">

● Link to the test file for a failure-inducing input:
https://github.com/nathom/markdown-parser/blob/main/test-file2.md

● Symptom of failure-inducing input:
<img width="885" alt="Screen Shot 2022-04-25 at 12 16 11 AM" src="https://user-images.githubusercontent.com/65497162/165038977-51e9bae9-5c03-4ca8-bf85-69b8d51a8eee.png">



● An infinite loop occurs as we do not consider whitespaces at the end of the document, hence the currentIndex is not updated at it ends at a ")" character. The input induces failure through the presence of a whitespace at the end of the document. This causes the infinite loop to occur, which is the symptom of the bug.
##CHANGE 2:

● Screenshot of the code change diff from Github:
<img width="1237" alt="Screen Shot 2022-04-25 at 12 16 57 AM" src="https://user-images.githubusercontent.com/65497162/165039084-9c55ce86-ac0f-4bf8-9602-86a034fa5f1b.png">

● Link to the test file for a failure-inducing input:
https://github.com/nathom/markdown-parser/blob/main/test-file3.md

● Symptom of failure-inducing input:

<img width="278" alt="Screen Shot 2022-04-25 at 12 21 01 AM" src="https://user-images.githubusercontent.com/65497162/165039682-8c591c50-bdfc-47aa-ae06-b7dd2413d880.png">

● The bug here is the failure to account for embeddeed images and other objects that are not links. The input that induced failure is an markdown image identifier that is prependded with an exclamation point. As the program only reads parantheses and open brackets, it perceives the image is a link, which it should not.


###CHANGE 3:
● Screenshot of the code change diff from Github:
<img width="1220" alt="Screen Shot 2022-04-25 at 12 17 39 AM" src="https://user-images.githubusercontent.com/65497162/165039189-593baa88-e598-4317-9040-e3e23952947a.png">

● Link to the test file for a failure-inducing input:
https://github.com/nathom/markdown-parser/blob/main/test-file4.md

● Symptom of failure-inducing input:

This is what we got:
<img width="257" alt="Screen Shot 2022-04-25 at 12 29 52 AM" src="https://user-images.githubusercontent.com/65497162/165040958-3e2d74cf-7960-43ad-b668-22906c97b4b7.png">

This is what is expected: 
<img width="274" alt="Screen Shot 2022-04-25 at 12 30 14 AM" src="https://user-images.githubusercontent.com/65497162/165041000-2ca75833-a4cd-41d6-a99d-530585878279.png">

● The test result above counts the number of links within the given input, which should be 0 as it is blank. However, the bug (which in this case is the failure to account for spaces or newlines between the the parantheses and brackets), causes it to read the single input as two different links. 
