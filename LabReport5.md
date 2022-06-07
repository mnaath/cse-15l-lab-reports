
This week we covered the following concepts:

* The use of vimdiff 
* output redirection
* Testing with multiple files

# Test 1

For this test, I found the results using vimdiff.

[Link](https://raw.githubusercontent.com/nidhidhamnani/markdown-parser/main/test-files/480.md) for test 1.


Expected output:

<img width="1204" alt="Screen Shot 2022-06-06 at 6 31 49 PM" src="https://user-images.githubusercontent.com/65497162/172276556-cbba975e-404c-4379-8138-15ca73eefabc.png">

nidhidhamnani's implementation (failed):

<img width="678" alt="Screen Shot 2022-06-06 at 7 09 37 PM" src="https://user-images.githubusercontent.com/65497162/172280665-188b8aae-62c4-41e8-8d32-56a969fbdc26.png">


My implementation (failed):

<img width="515" alt="Screen Shot 2022-06-06 at 6 58 55 PM" src="https://user-images.githubusercontent.com/65497162/172279858-1fe5df34-2387-4704-a751-8e465e2bc5c7.png">

Fix:

I will be reviewing and suggesting changes to my team's/my implementation.

This portion of the code shows that tags in HTML are not considered. The implementation should consider tags within <>, as they may contain links.

<img width="662" alt="Screen Shot 2022-06-06 at 7 21 51 PM" src="https://user-images.githubusercontent.com/65497162/172282076-fdc60cf5-b8b3-40f7-beb1-59d9bf3b98fc.png">



# Test 2

For this test, I found the results using vimdiff.

[Link](https://raw.githubusercontent.com/nidhidhamnani/markdown-parser/main/test-files/539.md) for test 1.


Expected output:
<img width="1320" alt="Screen Shot 2022-06-06 at 7 06 14 PM" src="https://user-images.githubusercontent.com/65497162/172280201-af90ddee-19b6-4889-9201-a37183540e95.png">

nidhidhamnani's implementation (failed):

<img width="558" alt="Screen Shot 2022-06-06 at 7 10 03 PM" src="https://user-images.githubusercontent.com/65497162/172280712-63438da6-1d55-4c19-afe8-a0c90c5fa357.png">


My implementation (failed):

<img width="498" alt="Screen Shot 2022-06-06 at 7 08 23 PM" src="https://user-images.githubusercontent.com/65497162/172280546-825d114f-197a-4dc0-b36e-fa13f8f956d4.png">
Fix:

I will be reviewing and suggesting changes to my team's/my implementation.

This portion of the code should be changed. The issue here is that links stored in the document are not considered. Links should be searched at the document if a paranthees isn't found after a bracket.

<img width="627" alt="Screen Shot 2022-06-06 at 7 24 19 PM" src="https://user-images.githubusercontent.com/65497162/172282322-d0e5d53d-bdd6-4fc1-ba78-e09abe37878e.png">









