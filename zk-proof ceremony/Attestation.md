
## Create repository and clone to your machine 


- make a public repository on your GitHub and name it "nimiq_attestation".

- copy the repository url and clone it using "git clone" on your terminal


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

branch should be "main" or "master" , so edit format the next code to master if branch is master

```
git push origin main
```
- enter only your GitHub username without using @


## To get password 
