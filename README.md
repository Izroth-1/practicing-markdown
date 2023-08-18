<!--this is how you make a comment in markdown-->
My first line in markdown  
add 2 space and the write a new line to add a new line  

___
This is how you add horixontal rule in markdown (by adding 3 minus "---" or "___")
___

<br>

<!-- with "#" this I am adding 6 levels of headings from bigger to smallser-->

# Example 1
## Example 2
### Example 3
#### Example 4
##### Example 5
###### Example 6

<P>With useing p tag you can make paragraph in markdown but p tag is a html syntax.Many html syntax also works in markdown.</p>

___this is how you write italic___  
__this is how you write bold__  
~~this is how you write strikethrough or deleted text(look in the   README.md file to get a better understanding)~~

### Now we are going to use inline code and multiple line inline code  

##### inline code

`print("hello world")`

##### multiple line inline code

```
#include <stdio.h>

int main ()
{
    printf("Multiple inline code block without c formate")
}

```

```c
#include <stdio.h>

int main ()
{
    printf("Multiple inline code block with c formate")
}

```

## order list and nested list  

1. Item1
2. Item2
   1. Item2.1
   2. Item2.2
3. Item3

## unorder list and nested list  

- Itme1
   1. Item1.1
- Item2
   - Item2.1
- Item3

## task list

- [x] Task1
- [x] Task2
- [] Task3

### automatic link  

https://www.facebook.com/kaoser71

### disable link  

`https://www.facebook.com/kaoser71`

### markdonw link syntax

[AuthorFacebookID][facebooklink]



### image syntax

<!--![profile](./image/profile.jpg)-->

<!--you can use the syntax from ubove (remove the comment tag to use the syntax) but you cannot manupulate the hight and the width of the photo so I suggest using html syntax-->

### html image syntax

<img src="./image/profile.jpg" width="250" title="profile"/>

<!--Here this is the html syntax-->

### Emoji

<!--just copy past emojis form eimoji pedia website-->
🫡  

### Table syntax

| Name | Email |
| ---- | ---- |
| Kaoser Alam | kaoser870440@gmail.com |
| name1 | email1 |
| name2 | email2 |

<!-- all link is here -->
[facebooklink]: https://www.facebook.com/kaoser71
