# Bootstrap
- Is a CSS framework 
- Provides css classes that we can add to things on our page that will give us styling options
- Works with a grid system that allows for responsive design by dividing the page into a series of rows and columns to create a flexible and consistent layout structure.

# Bootstrap Grid System
- The grid system is divided in to 3 sections, including
- Container - wraps the grid system
- Rows - individual rows in the grid
- Columns - columns inside the rows

# Bootstrap Grid System

## Container
- **Container**: The container is the outermost element in the Bootstrap grid system. It wraps the rows and columns and provides a responsive fixed-width or fluid-width layout.
  - `.container`: Provides a responsive fixed-width container.
  - `.container-fluid`: Provides a full-width container, spanning the entire width of the viewport.

## Row
- **Row**: Rows are horizontal groups of columns that ensure proper alignment and spacing.
  - `.row`: Creates a horizontal group of columns.

## Column
- **Column**: Columns are the building blocks of the grid system. They are used inside rows to create the layout.
  - `.col`: Creates a column that spans the entire width of the row.
  - `.col-{size}-{number}`: Creates a column that spans a specific number of grid spaces for a given screen size (e.g., `.col-md-6`).

## Gutters
- **Gutters**: Gutters are the spaces between columns. They can be controlled using the `g`, `gx`, and `gy` classes.
  - `.g-{number}`: Sets both horizontal and vertical gutters to the specified size (e.g., `.g-3`).
  - `.gx-{number}`: Sets horizontal gutters to the specified size (e.g., `.gx-2`).
  - `.gy-{number}`: Sets vertical gutters to the specified size (e.g., `.gy-4`).

## Offset
- **Offset**: Offsets are used to push columns to the right by a specified number of grid spaces.
  - `.offset-{size}-{number}`: Offsets a column to the right by the specified number of grid spaces.

# In addition to the bootstrap grid system, we have
# Tables - https://getbootstrap.com/docs/5.0/content/tables/
# Forms - https://getbootstrap.com/docs/5.0/forms/overview/
