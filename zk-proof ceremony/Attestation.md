
## Create repository and clone to your machine 


- make a public repository on your GitHub and name it "nimiq_attestation".



<img src="https://raw.githubusercontent.com/ava-world/Nimiq/main/images/attest1.1.jpg" />



- copy the repository url and clone it using "git clone" on your terminal
- 

<img src="https://raw.githubusercontent.com/ava-world/Nimiq/main/images/attest1.2.jpg" />



```
git clone https://github.com/ava-world/nimiq-attestation
```

remember not to clone my repository, you should change the url to your own repository 


- copy your attestation file into the new repository

  ```
  cp snark-setup-operator/nimiq.attestation.txt nimiq-attestation
  ```

## publish changes on github

```
cd nimiq-attestation
```

```
git add .
```

```
git commit -m "sending attestation to github"
```

```
git branch
```

branch should be "main" or "master" , so edit the next code to master if branch is master, 

```
git push origin main
```
- enter only your GitHub username without using @


## To get password 


- go to your github setting

  

<img src="https://raw.githubusercontent.com/ava-world/Nimiq/main/images/attest.jpg" />



- select "developer settings"



  <img src="https://raw.githubusercontent.com/ava-world/Nimiq/main/images/attest1.3.jpg" />



- select "token classic"



<img src="https://raw.githubusercontent.com/ava-world/Nimiq/main/images/attest1.4.jpg" />



- generate new token


 
<img src="https://raw.githubusercontent.com/ava-world/Nimiq/main/images/attest1.5.jpg" />


- name your token and select 3 permissions
 


<img src="https://raw.githubusercontent.com/ava-world/Nimiq/main/images/attest1.6.jpg" />



- scroll down and generate token
 

<img src="https://raw.githubusercontent.com/ava-world/Nimiq/main/images/attest1.7.jpg" />



  - copy the token , that's your password (save it for future use also)
 

  By now your attestation is published on github


  now you can locate the file on GitHub,

  ## To download from GitHub to local devices

  NB: This part might be a bit vague as i wasn't able to contribute, i will still explain as best as i could

  

- click on the "attestation.txt" file (now on your GitHub.


- locate 3 dots on your top right corner and click you will see a download option.

  

- you can now go ahead and open an issue in <a href="https://github.com/nimiq/ceremony-attestations/issues">nimiq repository</a>
