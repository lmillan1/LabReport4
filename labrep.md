# Lab Report 4 

## Step 4( Log into ieng6)

First open VSCode and open a new terminal and ussing the ssh command use your own ieng6 account in my case it is

ssh cs15lsp23gm@ieng6.ucsd.edu and then press enter to log in and press enter. 


<img width="653" alt="Screen Shot 2023-05-20 at 7 29 07 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/bafaed2a-f641-4650-a9ad-eeaa5a753404">

## Step 5 Clone your fork of the repository from your Github account

To clone the fork of the repository first go to the website and click on the code and copy the git@github.com:lmillan1/lab7.git and then on your terminal on VSCode type in git clone git@github.com:lmillan1/lab7.git to fork the repository.

<img width="712" alt="Screen Shot 2023-05-20 at 7 37 20 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/013728cd-8779-49cb-9d74-2a6a42dc9376">


<img width="627" alt="Screen Shot 2023-05-20 at 7 37 06 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/ca465cf2-7600-4ab2-8cbf-153cd977cc66">

## Run the tests, demonstrating that they fail

Before even running the test we want to make sure that we are in the directory for lab7 to this first type in `ls` on the terminal then `cd` to `lab7`. After that once again press `ls` to see what file we have to run and to be able to run we have use the command `bash` and to run the test use `bash test.sh` and as you can see from the picture it fails for now.




<img width="640" alt="Screen Shot 2023-05-20 at 7 41 56 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/fb77626a-7922-4c1b-b5b8-44deb5261623">





<img width="636" alt="Screen Shot 2023-05-20 at 7 42 09 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/50003add-89ad-4266-93d4-6bb9074cebd9">






<img width="697" alt="Screen Shot 2023-05-20 at 7 45 27 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/b4149f78-1f10-4d24-93e8-573e6746a608">







## Edit the code file ListExamples.java to fix the failing test (as a reminder, the error in the code is just that index1 is used instead of index2 in the final loop in merge)

To edit the code we want to use `vim` and enter into the file from the terminal to do this we just type in `vim ListExamples.java` and enter into the vim file. To edit the file we first have to type `i` to insert to the file be able to edit. 
1.vim ListExamples.java <enter>
2./index1 nnnnnnnnn dw iindex2<_><esc> :wq <enter>
3. Press escape and type in :w to save the edits and then use escape again then :q to exit vim.
3.bash test.sh

  
  
  
  
  
 <img width="1512" alt="Screen Shot 2023-05-20 at 7 48 38 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/62aa1a37-d2ca-44ae-b341-cc9528fbfa3b">
  
  
  
<img width="1512" alt="Screen Shot 2023-05-20 at 7 48 45 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/a02e5557-d41e-4958-8890-38b76b262c86">

  ## Commit and push the resulting change to your Github account
  To do this we have to first type in the terminal `git add .m` to make sure it changes in all the files. Then `git commit -m "Edited index1 to 2" to provided context in the edited that we maid and and use the `git push` to push the change into github account.


<img width="703" alt="Screen Shot 2023-05-20 at 7 56 02 PM" src="https://github.com/lmillan1/LabReport4/assets/130090548/808ebaac-45b5-4f06-b2a2-ffa600c9cf61">

