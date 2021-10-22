# School
Hi my name is Sabrina Broadway and I am a Sophmore at Mizzou this year. I am majoring in Information Technology.

**Here is the link to the Mizzou website:**

[Mizzou](https://missouri.edu/)

![mizzou](https://user-images.githubusercontent.com/89413296/138403489-be616a6a-8a57-49c2-bc36-ad4cf3ad1968.PNG)


## FizzBuzz

Something I learned this year was how to write a *FizzBuzz* program.

**Here is the code:**

```
function fizzbuzz(i) {
	var display = document.getElementById('display');
	var displayHTML = "";
	var i;
	for (var i = 1; i < 101; i++) {
		displayHTML += "<p>" + i + "</p>";
		if (i % 15 == 0){
			document.write("<p>" + "fizzbuzz" + "</p>");
		}
		else if (i % 3 == 0){
			document.write("<p>" + "fizz" + "</p>");
		}
		else if (i % 5 == 0){
			document.write("<p>" + "buzz" + "</p>");
		}
		else{
			document.write("<p>" + i + "</p>");
		}
	display.innerHTML = displayHTML
	}
}
```

[Homepage](README.md) [Page 1](page1.md) [Page 2](page2.md) [Page 3](page3.md) [Page 4](page4.md)
