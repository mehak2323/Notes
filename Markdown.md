[Source Link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

# A first-level heading
## A second-level heading
### A third-level heading
#### Fourth level
##### Fifth level
###### Sixth level
####### seventh ,  max is 6
Normal text 


**This is bold text**

*This text is italicized*

~~This was mistaken text~~

**This text is _extremely_ important** (nested italic)

***All this text is important*** (bold and italic)

Text <sub>This is a subscript text</sub>

Text <sup>This is a superscript text</sup>


> Text that is a quote

`code or a command` within a sentence with single backticks.

The background color is `#ffffff` for light mode and `#000000` for dark mode.
`rgb(9, 105, 218)` ,`hsl(212, 92%, 45%)`.




Lists
-
- With -
	-  First nested
		- Second nested
			- Third nested 
* With *
+ With +
1. Help
2. Yourself


Tasks:
- [x] Done :tada:
- [ ] Left #2
- [ ] \(Optional) escape parantheses, as its common with link format

@github/support Tag teams name if required
#select-issue-number , #select-PR-number
@octocat :+1: This PR looks great - it's ready to merge! :shipit:

```
code 
block
<!-- comment -->
print("Hello World");
```

comment 
<!-- This content will not appear in the rendered Markdown -->

#### [Section Link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Relative Link](./docs/CONTRIBUTING.md)

![Image with link](https://myoctocat.com/assets/images/base-octocat.svg)


Here are some examples for using relative links to display an image.

- In a  `.md`  file on the same branch
`/assets/images/electrocat.png`
- In a  `.md`  file on another branch
`/../main/assets/images/electrocat.png`
- In issues, pull requests and comments of the repository
`../blob/main/assets/images/electrocat.png?raw=true`
- In a  `.md`  file in another repository
`/../../../../github/docs/blob/main/assets/images/electrocat.png`
- In issues, pull requests and comments of another repository
`../../../github/docs/blob/main/assets/images/electrocat.png?raw=true`


light and dark theme for image:
```HTML
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
```


Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
