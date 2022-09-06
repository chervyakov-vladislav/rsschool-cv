# **Chervyakov Vladislav**

+ Telegram: [@vladislav_chervyakov](https://t.me/vladislav_chervyakov)
+ Discord: Chervyakov Vladislav#4347
+ GitHub: [chervyakov-vladislav](https://github.com/chervyakov-vladislav)

## About

I've been working at different jobs for 10 years as a manager

----

## Skills

+ HTML5
+ CSS
+ JavaScript

----

## Code Example

```
const itemVertAccordeon = document.querySelectorAll('.vertical-accordeon__item');
for (i = 0; i < itemVertAccordeon.length; i++) {
	itemVertAccordeon[i].addEventListener('click', function (e) {
		e.preventDefault();
		if (e.target.closest('.vertical-accordeon__item').classList.contains('vertical-accordeon__item--active')) {
			e.target.closest('.vertical-accordeon__item').classList.remove('vertical-accordeon__item--active');
		} else {
			for (let j = 0; j < itemVertAccordeon.length; j++) {
				itemVertAccordeon[j].classList.remove('vertical-accordeon__item--active');
			}
			e.target.closest('.vertical-accordeon__item').classList.add('vertical-accordeon__item--active');
		}
	});
}
```

## Education

Tomsk State University of Control Systems and Radioelectronics

## Courses & Certificates

+ loftschool: [Web Development for Beginners](https://loftschool.com/diploma/OH1558195701/en/pdf)

## Languages

English A2