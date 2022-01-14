<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Changing weekly menus

Final project for the Building AI course

## Summary

Weekly menus make it easy to plan your meals for the week. When you plan your menus well in advance, you may well eat leftovers from the previous day for several days or continue the next day’s meal with them. With the help of the menu, you plan varied and affordable meals for each day of the week. For example, planning a week’s meals in advance saves time and effort. The basic ingredients can be obtained on a single shopping trip and replenished with fresh produce during the week.
This project
This project utilizes @VRN sites and images as well as @Martat sites menus in design


## Background

The six-week menu is designed according to the main ingredient. There is planned one main meal a day is planned for the  list, as usually the second meal is eaten at the school, or workplace. The menu becomes varied, as vegetarian, fish, meat and other dishes alternate on different days of the week. The menu gives you plenty of choice as the recipes can vary according to your preference. The menu is designed so that on weekends the same food is eaten for lunch as for the previous day’s dinner. This reduces cooking work.

The benefits of weekly planning:
* Save time
* Reduce food waste
* Helps you eat healthier

Often on one- or three-week menus, the rotation of the same portions of food might get a bit boring, and six-week menus provide more options.

## How is it used?

The six-week menu could be an app for everyone, but especially the target group would be people who have to think "what food would I prepare today" 

<img src="https://www.ruokavirasto.fi/globalassets/teemat/terveytta-edistava-ruokavalio/kuluttaja-ja-ammattilaismateriaali/kuva-arkisto/lautasmalli_rgb_lores-2.jpg" width="300">

The application asks the user for the week for which the user wants a list, like week 45. The application prints (displays) a list with recipes for that week. the app provides the random lists.

![kuva](https://user-images.githubusercontent.com/97443916/149127772-7d4ea9df-baec-483c-9102-e92384ac5ef6.png)



```
For example, the code could be:
print("Anna viikko väliltä 1-52")
menu1 = ['1']
menu2 = ['2']
menu3 = ['3']
menu4 = ['4']
menu5 = ['5']
menu6 = ['6']

lista = [1, 2, 3, 4, 5, 6]

week_before = 0

while True:
    week = int(input("Anna viikko: "))
    menu = week + len(lista)
    if week >= 52 or week == week_before:
        break
    if week <= 52:
        print("Valitsemasi viikko on:", week)
    from random import choice
    print("Menu is:",choice(lista))

```

## Data sources and AI methods
As a source of information, the app would have a six-week changing menu entered in the background. AI methods: 

## Challenges

The project does not pay much attention to the need for a special diet, so you have to invent the variations yourself. The app also does not take into account the age or other individual needs of the user as the app is based on adult food recommendations.

## What next?
The app should be developed to provide daily recipes. The amounts and ingredients in the recipes should also be user-friendly depending on whether two or ten people are eating.
It would also be user-friendly if the app showed the nutritional content of the week’s foods on a daily basis.


## Acknowledgments

* @Martat, @VRN, https://buildingai.elementsofai.com/Conclusion/ai-idea-gallery
* @datqn7444 thanks for inspiration!
* Image source: © State Nutrition Advisory Board or © VRN (Images published by the State Nutrition Advisory Board may be used freely as long as the source
mentioned)
* 
