<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Changing weekly menus

Final project for the Building AI course

## Summary

Weekly menus make it easy to plan your meals for the week. When you plan your menus well in advance, you may well eat leftovers from the previous day for several days or continue the next day’s meal with them. With the help of the menu, you plan varied and affordable meals for each day of the week. For example, planning a week’s meals in advance saves time and effort. The basic ingredients can be obtained on a single shopping trip and replenished with fresh produce during the week.


## Background

The six-week menu is designed according to the main ingredient. There is planned one main meal a day is planned for the  list, as usually the second meal is eaten at the school, or workplace. The menu becomes varied, as vegetarian, fish, meat and other dishes alternate on different days of the week. The menu gives you plenty of choice as the recipes can vary according to your preference. The menu is designed so that on weekends the same food is eaten for lunch as for the previous day’s dinner. This reduces cooking work.

The benefits of weekly planning:
* Save time
* Reduce food waste
* Helps you eat healthier

Often on one- or three-week menus, the rotation of the same portions of food might get a bit boring, and six-week menus provide more options.

## How is it used?

The six-week menu could be an app for everyone, but especially the target group would be people who have to think "what food would I prepare todayDescribe the process of using the solution. 

<img src="https://www.ruokavirasto.fi/globalassets/teemat/terveytta-edistava-ruokavalio/kuluttaja-ja-ammattilaismateriaali/kuva-arkisto/lautasmalli_rgb_lores-2.jpg" width="300">
Kuvan lähde: ©Valtion ravitsemusneuvottelukunta tai ©VRN (Valtion ravitsemusneuvottelukunnan julkaisemia kuvia saa käyttää vapaasti, kunhan lähde
mainitaan)

For example, the code could be:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
