<!--
author:  André Dietrich; Sebastian Zug

mode:    Textbook

comment: Interactive LiaScript workshop

-->

# Tutorial on Alphabet-Soup

__This is a basic course, it provides an introduction to the LiaScript syntax and its basic features. It is intended for beginners and can be used as a template for your own courses.__

[Tutorial in Live Editor](https://liascript.github.io/LiveEditor/?/show/file/https://raw.githubusercontent.com/LiaPlayground/Brasil_2023/main/basics_of_liascript.md)


A. Basics

Preparation / Working time approximately 10 minutes / Cooking time approximately 25 minutes

Total time approximately 35 minutes

Chop or slice the onions and then sauté them in a large pot with olive oil. Douse the soup with water and start boiling while adding the peeled carrots directly to the pot. Once the water is boiling, add the broth. Chop or slice the zucchini into cubes or halves and then mix it with the noodles into the soup. Let it simmer for about 10 minutes and then add the finely chopped tomatoes and peppers. If needed, add some water. Let it simmer for another 10 minutes and season with spices, salt, and pepper.

A.1 Ingredient List


100 g 	Instant noodles (Alphabet noodles)
2 TL, heaping 	Vegetable broth powder, instant
1 Liter 	Water, possibly more
1 Zucchini
2 Red bell peppers
2 Carrots
1 Onion
3 Tomatoes
Optionally
Fresh, dried or TK herbs
Salt and pepper
Sweet paprika powder
1 EL 	Olive oil 

A.2 Tables and Amounts

Nutritional values per serving: 160 kcal


Substance         Grams
Protein          6.31 g
Fat              2.75 g
Carbohydrates   26.48 g

A.3 Correct Citing

Alphabet soup is a noodle soup with alphabet noodles as an ingredient. Often, small carrot pieces and various spices are also added to the ingredient. Alphabet noodles are up to one centimeter in size and have the form of the letters A-Z and seldom also the numbers 0-9 or the @ sign. Alphabet noodles and alphabet soup have been available since at least 1867 in the United States, in Germany no later than since 1884. Alphabet noodles are usually offered in the trade as soup ingredients, alphabet soups as canned soups or as canned goods.

Wikipedia: https://de.wikipedia.org/wiki/Buchstabensuppe 


B. External References

Source: https://www.chefkoch.de/rezepte/2166951347805623/Buchstabensuppe-mit-frischem-Gemuese.html


B.1 Pictures

https://upload.wikimedia.org/wikipedia/commons/0/09/Buchstabensuppe.jpg

https://www.verbformen.de/deklination/substantive/Buchstabensuppe.png

https://upload.wikimedia.org/wikipedia/commons/e/e9/Alphabet_soup%2C_empty.jpg


B.2 Music for Cooking

https://open.spotify.com/track/24fdXLWNsc6LJZrbE8wLaJ

https://soundcloud.com/sitzhupe/barbier-von-sevillia


B.3 Videos for Cooking

https://www.youtube.com/watch?v=U_UW69w0uHE


B.4 Augmented Reality and More

https://sketchfab.com/3d-models/formschussel-fur-terra-sigillata-schalen-d4a48496f8bc4808b22277fdedba0b2b

https://phet.colorado.edu/sims/html/states-of-matter/latest/states-of-matter_all.html


C. Recipe Formats

Interactive books, folios, presentations


C.1 Animations & Comments

Today we are going to make an alphabet soup and for that we need the following ingredients:

First, chop the onions small to sauté them in a large pot with olive oil.

https://openai-labs-public-images-prod.azureedge.net/user-ANzFa46RCwWLS19qYwta4rsP/generations/generation-jnFGtapIukJDG38mOKHcDx9g/image.webp

Then douse the soup with water and start boiling while adding the peeled carrots directly to the pot.

https://openai-labs-public-images-prod.azureedge.net/user-ANzFa46RCwWLS19qYwta4rsP/generations/generation-ZddGERw9EB3CEuPYGBRs5Sbn/image.webp

Once the water is boiling, add the broth.
The zucchini is chopped into cubes or halves and then mixed with the noodles into the soup. 
Let it simmer for about 10 minutes.

https://openai-labs-public-images-prod.azureedge.net/user-ANzFa46RCwWLS19qYwta4rsP/generations/generation-rwRK8X0LqVixqeN1ah3ukoPv/image.webp


Finally, add the finely chopped tomatoes and peppers.
Add some water if needed and let it simmer for another 10 minutes and season with spices, salt, and pepper.
And then serve hot.

https://www.youtube.com/watch?v=V6paiDYJmOo&autoplay=1&mute=1


E. Programming in Cooking

Let us assume, that we want to implement a timer monitoring our cooking. Hence, we have to include code to our material.

var Guests = 4
const People = 4

var Ingredient = {
   AlphabetNoodles: 100, // Grams
   VegetableBroth: 2, // TL
   Water: 1, // L
   Zucchini: 1,
   BellPeppers: 2,
   Carrots: 2,
   Onions: 1,
   Tomatoes: 3,
   Oil: 1 // EL
}

for (const Name in Ingredient) {
   Ingredient[Name] = (Ingredient[Name] / People) * Guests
}

JSON.stringify(Ingredient, null, 2)

### ... More?

``` abc
% audio: true
% autoplay: false
% channel: 0
% debug: false
% notes: true
% program: 60
% responsive: true
% tablature: [{"instrument": "violin","tuning": ["G,", "D", "A", "e"]}]
% voicesOff: false
% chordsOff: false
% stereo: true
X: 1
T: Cooley's
M: 4/4
L: 1/8
K: Emin
|:D2|"Em"EBBA B2 EB|~B2 AB dBAG|"D"FDAD BDAD|FDAD dAFD|
"Em"EBBA B2 EB|B2 AB defg|"D"afe^c dBAF|"Em"DEFD E2:|
|:gf|"Em"eB B2 efge|eB B2 gedB|"D"A2 FA DAFA|A2 FA defg|
"Em"eB B2 eBgB|eB B2 defg|"D"afe^c dBAF|"Em"DEFD E2:|
```
@ABCJS.eval

```
<!--
import: 
 https://raw.githubusercontent.com/liaTemplates/ABCjs/main/README.md
-->
```

> Explore some of the available extensions at:
>
> https://github.com/topics/liascript-template

### Fullday-Workshop at eLearning Africa 2023

!?[1](https://www.youtube.com/watch?v=U_UW69w0uHE)
!?[1](https://www.youtube.com/watch?v=8UtlwH0o8FI)
!?[1](https://www.youtube.com/watch?v=DLk7cKb54IQ)
!?[1](https://www.youtube.com/watch?v=F1DY7_k6KtQ)
