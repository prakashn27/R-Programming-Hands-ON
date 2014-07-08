Commands Reference
---------------------------------

####Basics####
* getwd() - prints the working Dir
```
getwd()
[1] "C:/Users/user/Documents"
````
* Function syntax
```
myfunction <- function() { 
	x <- rnorm(100)
	mean(x)
}
```
dir() - to print the elements in the woring dir
```
> dir()
 [1] "~$-Housing.docx"                     
 [2] "Bluetooth Exchange Folder"           
 [3] "Default.rdp"      
```
ls() - to print the functions in the working dir
```
> ls()
[1] "myfunction" "second" 
```
source("mtcode.R") - Load the R file
```
> source("mtcode.R")
> ls()
[1] "myfunction" "second"  
```

