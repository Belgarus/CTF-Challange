# Lösungen mini CTF

## Challenge 1:

```
 let x = 0 
 function guesser(){
     console.log(x)
     document.getElementById("password").value = x
     document.getElementById("solutionBtn").click()
     x += 1
 }
 setInterval(guesser, 10)
```

 - Passwort: sudo_Make_Me_Sandwich


## Challenge 2:

 - **Hexadezimal:** 41 6e 65 75 6b 20 6e 79 61 6e 20 6e 79 61 6e 67 20 67 65 75 68 3f  
 - **Klingonisch:** Aneuk nyan nyang geuh?
 - **Deustch:** Was willst du von mir?
 - **camelCase:** wasWillstDuVonMir?


## Challenge 3:

```
 find -name start.*
 bash ./S/start.sh
``` 

