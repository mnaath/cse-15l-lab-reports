
This week we covered the following concepts:

* The use of vimdiff 
* output redirection
* Testing with multiple files

# Test 1

For this test, I found the results using vimdiff.

Link for test 1.

![Screen Shot 2022-05-30 at 3 17 46 PM](https://user-images.githubusercontent.com/65497162/171064018-2e8b09e5-7637-4d71-8004-37293c03ea42.png)



# Tests on my repo

<img width="731" alt="Screen Shot 2022-05-30 at 4 00 02 PM" src="https://user-images.githubusercontent.com/65497162/171066333-89a2a9e7-3dbe-4cc7-9a51-b69b9f5bac1c.png">

# Results

For snippet 1:
![Screen Shot 2022-05-30 at 4 01 31 PM](https://user-images.githubusercontent.com/65497162/171066409-169edd86-b284-4638-aa8d-93d45385e968.png)
For snippet 2:
![Screen Shot 2022-05-30 at 4 01 54 PM](https://user-images.githubusercontent.com/65497162/171066432-c8ad2676-6ce6-4c65-8bf8-9ecb1a383881.png)
For snippet 3:
![Screen Shot 2022-05-30 at 4 02 17 PM](https://user-images.githubusercontent.com/65497162/171066448-f928e1e5-f7f9-453d-8f02-3210293377a3.png)


# Tests on reviewed repo

<img width="622" alt="Screen Shot 2022-05-30 at 4 07 50 PM" src="https://user-images.githubusercontent.com/65497162/171066750-080d25e3-3ae7-4012-bb85-ca8d7d47357a.png">

# Results

<img width="798" alt="Screen Shot 2022-05-30 at 4 11 34 PM" src="https://user-images.githubusercontent.com/65497162/171066941-bf3f141a-cea4-4c63-9ef8-d5ed9ef9dc55.png">

# Write-up

## Snippet 1

The implementation needs to check if the links are within the code fences or not. A reserve search needs to be performed in this case, which is something my group's implementation does not do.

## Snippet 2 

A solution would be to disregard the brackets in the presence of a preceding backslash. For double paranthesis, ensure only the outer ones are considered.

## Snippet 3

It would be a more involved change as line breaks within links and titles need to be considered. 


