# v.1
## DataFlow
[Figma Dataflow Link](https://www.figma.com/file/KVwCEE4YyHgW0YWCgu5dIR/WhatEvs-Hangaburs---DataFlow?node-id=0%3A1)

## Wireframe
[Figma Wireframe Link](https://www.figma.com/file/j7Csul5bflgtd7lLWx48jG/WhatEvs-Hanguburs-Wireframe?node-id=0%3A1)

### Fonts
- Title:
- Subtitle:
- Body:

**NEED TO SELECT FONTS**

### Colors
| Type | Standard | Deuteranomaly |
| --- | --- | --- |
|Primary | | |
|Secondary | | |
|Tertiary | | |

[paletton check](http://paletton.com/#uid=55B0u0kiIvGcEJlYyTUOTsjoTe2)

## Components
|  | | | |
| --- | --- | --- | --- |
| App.js | Nav.js | Footer.js | Item.js | Menu.js | Button.js |
| Cart.js | Login.js | Logout.js | About.js  

### Details of Components
- App
  - Nav
    - Menu
      - Categories
        - Items
          - Item
    - About
    - Auth 
      - Login
    - Cart
  - Button
  - Logout
  - Footer


---
# Objects
## Category Object
```
{
    title: string, (unique)
    items: array[{item}],
    description: string 
}
```

## Menu Item Object
```
{
    id: int, (unique)
    title: string,
    description: string,
    ingredients: array[{ingredient}],
    price: int,
    calories: int,
    image: string,
    timeToCook: int,
    category: string (category title)
}
```
## Ingredient Object
```
{
    name: string, (unique)
    calories: int
}
```

