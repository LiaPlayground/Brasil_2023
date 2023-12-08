<!--
author:   Sebastian Zug

email:    Sebastian.Zug@informatik.tu-freiberg.de

version:  1.0.4

language: de

mode:     Presentation

comment:  This course introduces LiaScript and explains the benefits of the new,
          open-source concept.

logo:     ./images/logo.png

import: https://raw.githubusercontent.com/LiaScript/CodeRunner/master/README.md

translation: Deutsch  translations/German.md
-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://github.com/LiaPlayground/Brasil_2023/blob/master/best_practice.md)

## My current usage

Starting in 2018 we switched the learning content of our [courses](https://github.com/TUBAF-IfI-LiaScript) completely to LiaScript.

!?[](https://github.com/LiaPlayground/LiaScript-User-Symposium-2023/raw/main/vid/TUBAF.mp4)

> __I am going to summarize my experiences and usage patterns in this talk.__

### Editing 

+ online editor in Github (press `.` to open)
+ offline editor in Visual Studio Code 

![](./pic/EAVD_github_Screen_shot.jpg)

https://github.com/TUBAF-IfI-LiaScript/VL_EAVD


### Dissemination

+ github
+ separate website via Lia exporter

![](./pic/EAVD_oer_Screen_shot.jpg)

https://github.com/TUBAF-IfI-LiaScript/TUBAF-IfI-LiaScript.github.io

https://tubaf-ifi-liascript.github.io/prozprog.html

### Classrooms 

+ verbally, based on interactive slides
+ direct, in classroom mode (click on the symbol in the upper right corner)

```c
#include <stdio.h>

int main (void){
	int i = 0;
	int max = 0;

	printf("How many hellos: ");
	scanf("%d",&max);

  for(i=0; i<max; i++)
    printf ("Hello, world %d!\n", i);

	return 0;
}
```
@LIA.eval(`["main.c"]`, `gcc -Wall main.c -o a.out`, `./a.out`)

### Student feedbacks 

> Students love to correct the professor.

![](./pic/DS_oer_Screen_shot.jpg)

https://github.com/TUBAF-IfI-LiaScript/VL_EingebetteteSysteme/pulls?q=is%3Apr+is%3Aclosed