<!DOCTYPE html>
<html>
<head>
<title>L V T/title>
</head>
<body>

<h1>Welcome to Latin Vocabulary Tester by Civis-Latii</h1>
<p>Select what to quiz on:</p>
<button type="button" onclick="abcd()">Tempta!
  <\button>
  
<yolo id="yolo">YOLO</yolo>



</body>
<script>document.getElementById("yolo").innerHTML = "Hello JavaScript!";</script>
<script>
  import java.util.*;
  function abcd(){
    alert("hello")
  }
  function lattoeng(){
    len = int(len(v)/3-1) //list is %3 so we -1 to prevent index error
    for (i in range(length))  {    
        ans = ""
        rc = random.randrange(len(v)-3,3) //prevent index error, step 3 as input format is [word form 1, word form other, english]
        if (v[rc+1] != "-")
            alert("$v[rc]}, ${v[rc+1]}") 
        else
            alert("${v[rc]}") //accounting for inquit and prepositions
        ans = input("Enter your answer: ").lower()
        if (ans (not in v[rc+2].lower().split(", ")) &&  ans != "break" && ans != "gohome")
            while (ans (not in v[rc+2].split(", ")) && (ans != "break" && ans != "gohome"))
                alert("Incorrect! Try again! ")
                ans = input("Enter your answer: ")
        if (ans == "gohome")
            return //change so that there is just an exit button
        if (ans != "break")
            alert("Correct! Answers: ${v[rc+2]}")
        else
            alert("Answers: ${v[rc+2]}")
        delete (v[rc], v[rc+1], v[rc+2])
    }
    return  
  }
  function mainfull(){
    while (True)
        alert("#Welcome to LVT")
        alert()
        alert("#Choose what you want to quiz on: ")
        alert("nouns1/2/3/4")
        alert("verbs1/2/3/4/irreg/deponent")
        alert("adj212/33/comparative")
        alert("adverbs")
        alert("pronouns")
        alert("prepositions")
        alert("conjunctions")
        alert("misc")
        alert("numerals")
        alert()
        alert("You can skip the question by inputting 'break' and exit to menu by inputting 'gohome'")
        alert()
        lattoeng(choices())
  }
</script>
</html>
