This week we covered the following concepts:

* Streamlining ssh Configuration
* Setting up Github Access from ieng6
* Copying whole directories with scp -r

# Streamlining ssh Configuration

Editing my .ssh/config using vim 

<img width="1791" alt="Screen Shot 2022-05-08 at 11 40 47 PM" src="https://user-images.githubusercontent.com/65497162/167354110-619a5a04-1476-4261-9acd-35ccf154651c.png">

Using the new alias to log in to using ssh. 

<img width="874" alt="Screen Shot 2022-05-09 at 12 01 58 AM" src="https://user-images.githubusercontent.com/65497162/167357184-91dc450f-963b-4335-9000-1e15a4a1ebbd.png">

Using scp with the alias. Note how the directory did not contain an index.md file before I performed the scp command on my local machine (shown on the right tmux pane).

<img width="1792" alt="Screen Shot 2022-05-09 at 12 17 45 AM" src="https://user-images.githubusercontent.com/65497162/167359351-72694bb9-cac1-46de-a73b-d9d19de8bc0f.png">


# Setting up Github Access from ieng6

Screenshot of public key on Github.

<img width="793" alt="Screen Shot 2022-05-09 at 12 39 42 AM" src="https://user-images.githubusercontent.com/65497162/167362887-5c094fa9-3d3f-490a-af0b-1b6cc017fdec.png">

Screenshot of private key in my user account (remote server).

<img width="893" alt="Screen Shot 2022-05-09 at 12 40 16 AM" src="https://user-images.githubusercontent.com/65497162/167362971-96ae5ff7-c64d-44c6-bf7b-689077f743af.png">

Commiting and pushing change to Github on ieng6 account.

<img width="884" alt="Screen Shot 2022-05-09 at 1 06 51 AM" src="https://user-images.githubusercontent.com/65497162/167367203-4184346d-10da-46d2-87ee-b9f5544bf66b.png">

[link to commit.](https://github.com/mnaath/cse-15l-lab-reports/commit/4e9688720e297be00ad732eee44bad1b8a15c4a4)

<img width="905" alt="Screen Shot 2022-05-09 at 1 07 35 AM" src="https://user-images.githubusercontent.com/65497162/167367326-aa1de0ce-136d-4f14-a939-3b57338ff05f.png">

# Copying whole directories with scp -r

Copying markdown-parse directory to my ieng6 account.

<img width="888" alt="Screen Shot 2022-05-09 at 1 11 12 AM" src="https://user-images.githubusercontent.com/65497162/167367925-2807e9c1-d409-41af-a9c1-447d58b6d3ea.png">

Logging into my ieng6 account and compiling and running the tests for my repository.

<img width="709" alt="Screen Shot 2022-05-09 at 1 13 50 AM" src="https://user-images.githubusercontent.com/65497162/167368371-c2c1e849-9455-4bb7-9274-46fae56944d2.png">

Combining scp, ;, and ssh to copy the whole directory and run the tests in one line.

<img width="882" alt="Screen Shot 2022-05-09 at 1 31 08 AM" src="https://user-images.githubusercontent.com/65497162/167371212-30104cc5-158e-4503-94e3-72bbdd7772e7.png">


<img width="710" alt="Screen Shot 2022-05-09 at 1 31 29 AM" src="https://user-images.githubusercontent.com/65497162/167371256-f84da17b-b2b2-4879-9da0-be06e7d2f513.png">


