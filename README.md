# CSS GRID

#Learning GRID System with @maykbrito from Rocketseat

## GRID

- Two-dimensional
- Division of the entire page into rows and columns
- Place elements wherever you want in that grids

---

## GRID OR FLEXBOX

- Grid: Two dimensions (columns and rows)
- Flexbox: One dimension (or column or row)
- Both are complementary
- Check which browsers are not yet accepting the Grid system


---

## PROPERTIES


Let's separate into 2 groups:
`container` and` item (s) `

---
### CONTAINER

- display: grid;
- grid-template-columns;
- grid-template-rows;
- grid-gap
  - grid-row-gap
  - grid-column-gap
- grid-template-areas;
  
# Grid: Alignment
---

There are 6 properties for alignment:
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

We will separate them into 2 groups
1. `justify` e `align`
2.  `content`, `items` e `self`


---

## Justify e Align

The grid is two-dimensional, we have the x and y axis.

The ** x-axis ** is the horizontal positioning, from left to right.

** y-axis ** is vertical positioning, from top to bottom

`Justify` for the x axis.

`Align` for the y axis.

---

## Content, Items e Self

Joining `justify`, or` align`, with these elements: `content`,` items` and `self`; we observe our properties
---

### Content


`justify-content` and` align-content` allow us to align the grid itself, relative to the space outside the grid.

The use of these properties is rare, as it is only applied if the grid is smaller than the defined area. (For example, when we use the grid size in px, we can end up with a small grid, for the size of the grid area)


We can use ** 7 values ​​**:
1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly

---
### Items

`justify-items` and` align-items` will allow you to align the items in our grid, in any available space, in the cell that it inhabits.

We can use ** 4 values ​​**:
1. start
2. end
3. center
4. stretch


---
### Self

`justify-self` and` align-self` will allow us to align the item itself.

It does the same thing as `justify-items` and` align-items`, however, applied directly to a grid item


---
## ITEM (s)

- grid-column
  - grid-column-start
  - grid-column-end
- grid-row
  - grid-row-start
  - grid-row-end
- grid-area
