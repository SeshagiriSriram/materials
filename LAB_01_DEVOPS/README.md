## Lab 01: 

### Prerequisites	
- git client has been installed
- github account has been created
- docker has been installed 

### What to do 

1. There are 2 files
    dockerfile_full
    dockerfile_partial 

2. download both of them 

3. build an image test using dockerfile_full 

``` 
docker build . -t test -f dockerfile_full 
``` 

4. Note the size of the image 

5. run the image

```
    docker run --rm --name test test 
```

6. Repeat the steps with dockerfile_partial. What is the size? Why? 

7. clone the repos [Sriram's Devops Repos](https://github.com/seshagirisriram/devops) 

8. Navigate to the git_sample_code folder

9. Run the below (one after another) 

    **CAUTION:** THESE SCRIPTS DEPEND ON E:\tmp. Change the scripts accordingly. 
    
   - mergewithlineargraph.bat 
   - mergewithnonlineargraph.bat 

   What difference do you see? 

10. Run the below 

    - simulateconflict.bat 

    what output do you see? 

