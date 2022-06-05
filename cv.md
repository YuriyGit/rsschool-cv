# *Yuriy Mayorov*

***

## Contacts:

>* **E-mail:**  [Yuriy.Mayorov@mail.ru]()
>* **Discord:** [Yuriy]()
>* **Telegram:** [Yuriy]()

***

## About Me

> I`m 35 years old.
> I want to change profession to web developer. While in the learning phase

***

## Skills

> ![check_mark](img/check_mark.png) Html  
> ![check_mark](img/check_mark.png) Css  
> ![check_mark](img/check_mark.png) Version control: Git  
> ![check_mark](img/check_mark.png) Figma (only for web development)  
> ![check_mark](img/check_mark.png) JavaScript (began to study)  
> ![check_mark](img/check_mark.png) React (began to study)  

***


## Code Example:

```  
Напишите скрипт, который в заданном тексте удалит два символа, выбранных случайно

function randomNumber(num) {    //получаем случайное число до числа num
	let random = Math.random() * (num + 1);
	return Math.floor(random);
}
   //////////////////////
   
function removeSymbol(str, count = 2) {
	const alwaysEmpty = str === '' || str.length <= count;
	if (!alwaysEmpty) {
		let result = str;
		for (let i = 0; i < count; i++) {
			let len = result.length;
			let randomNum = randomNumber(len);
			result = result.slice(0, randomNum) + result.slice(randomNum + 1);
		}
		return (result);
	} else {
		return ("");
	}
}
removeSymbol("Далеко-далеко, за словесными.");  
```

***

## English:
A
