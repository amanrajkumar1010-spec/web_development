# 3 Squares -- HTML & CSS Learning

This small project was created while learning the basics of HTML and
CSS.

## What I Learned

### 1. HTML Structure

-   `<!DOCTYPE html>` tells the browser that the document uses HTML5.
-   `<html>`, `<head>`, and `<body>` form the basic HTML structure.
-   `<title>` sets the browser tab title.
-   `<link rel="stylesheet">` connects an external CSS file.

### 2. `<div>`

-   `<div>` is used to group elements.
-   A `<div>` can contain other elements.
-   It is useful for creating sections or containers.

### 3. Parent and Child

-   An element inside another element is its **child**.

-   The outer element is the **parent**.

-   Example:

    ``` html
    <main>
        <div>Box1</div>
        <div>Box2</div>
    </main>
    ```

    Here, `<main>` is the parent and the two `<div>` elements are
    children.

### 4. `<main>`

-   `<main>` is a semantic HTML element.
-   It represents the main content of a webpage.
-   It can also act as a parent/container for other elements.
-   Normally, a page should have one main `<main>` element.

### 5. Flexbox

-   `display: flex;` activates Flexbox.
-   The default `flex-direction` is `row`.
-   `row` places items side-by-side.
-   `column` places items from top to bottom.

Example:

``` css
main {
    display: flex;
}
```

This makes Box1 and Box2 appear in the same row because they are
children of `main`.

### 6. Why Box3 Appears Below

If Box3 is outside `<main>`:

``` html
<main>
    <div>Box1</div>
    <div>Box2</div>
</main>

<div>Box3</div>
```

the `display: flex` applied to `main` affects Box1 and Box2, but not
Box3.

### 7. IDs

-   `id` gives an element a unique name.
-   CSS can target an ID using `#`.

Example:

``` html
<div id="box1">Box1</div>
```

``` css
#box1 {
    background-color: green;
}
```

## Key Takeaway

**HTML creates the structure, while CSS controls the appearance and
layout.**

In this project, `<main>` groups Box1 and Box2, and `display: flex`
places those two boxes in a row.
