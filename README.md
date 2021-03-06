# Media Query Basics - Amazon Charity Trust

## Setup
```sh
# (1) navigate to assignments directory:
cd ~/muktek/assignments

#(2) create the assignment:
gen-project-scss assignment--media-query-layout-amazon-charity

#(3) download the image files into images directory
curl https://raw.githubusercontent.com/muktek/assignment--media-query-layout-amazon-charity/master/project-images.zip > project-images.zip

# (4) unzip the files
unzip project-images.zip

# (5) start the scss watcher
watch-scss
```



## Context
Amazon Charitable Trust was established to enable local communities in Brazil to implement sustainable business practices that preserve Amazon rain forests. They are looking to build a responsive front-end site that gives a profile of members from the XuXiau Community.

## The Assignment
Create a responsive site that realigns the layout for various viewport widths using media queries based on the mockups below.

Don't forget to include the viewport meta tag in the `<head>`.
```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
```

The breakpoints are:
+ *768px* for tablet
+ *1,024px* for desktop


### The mockups

#### Mobile
![mobile](mockups/act-mockup-mobile.png)

#### Tablet
![tablet](mockups/act-mockup-tablet.png)

#### Desktop
![desktop](mockups/act-mockup-desktop.png)

### The text copy

```
The People
==========
Everyone in the community has a role to play to keep the Coop Xixuaú alive. Here are just a few of the important people who depend on the natural resources of the Amazon and hence act as guardians of the rainforest.

...

Elinho
----------

Formerly inheriting his leadership skills from the favela of Manaus, Elinho, a live wire, committed to putting his energy into the service of the community. A talented mediator he is determined to build deeper and more satisfying relationships with the local politicians.

...

Elisama
----------
The miracle lady and not only the wife of the president of the community who is known for grounding Elinho from the wicked ways of the favelas, Elisama is also the community secretary (and a terrific dancing partner!).

...

Emanuela
----------
Lives in the community and is a leading light in the project. When she isn’t in the Village you can probably find her on a boat observing a family of giant otters.

...

Joao
----------
Our forest comedian, João is a storyteller like no other but doesn’t hesitate to come back down to Earth to provide the community with their vital supply of cassava.

...

Naide
----------

What would one do without Naide? The solver of all the problems, the ultimate jungle housekeeper! Naide is the preferred cook of the jungle

...

Zezinho
----------
Our "professional diver", the first in the river to fix a damaged propeller, Zezinho is not only good at repairing old engine, he is also the director of the communit

```


### Design Specs



```
Fonts
--------
+ Title Fonts: 'PT Mono', monospace
+ Body Fonts : 'Roboto', sans-serif

Google fonts link :
  <link href="https://fonts.googleapis.com/css?family=PT+Mono|Roboto" rel="stylesheet">


Colors
--------------
Title Green Font Color
  #007C4C

Header Background Color
  #DDDDDD

```
