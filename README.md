## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![](./Screenshot%202024-04-21%20at%2011-58-41%20Frontend%20Mentor%20Social%20links%20profile.png)

### Links

- Solution URL: [https://github.com/RadaidehDaniel/social-links-profile-frontend]
- Live Site URL: [https://social-links-profile-frontend-chi.vercel.app/]

## My process

### Built with

- HTML
- CSS

### What I learned

I learned display types and how to make an element fit the container's width.
The container should have a defined width, and the child's display be a block.

```css
.links-list {
  width: 27.9rem;
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 1.6rem;
}

.links-list li a {
  display: block;
  text-decoration: none;
  color: hsl(0, 0%, 100%);
  font-size: 1.4rem;
  font-weight: 600;
  background-color: hsl(0, 0%, 20%);
  text-align: center;
  border-radius: 8px;
  padding: 1.2rem;
}
```

### Continued development

I need to understand more about the relationship between HTML elements and how the box model works.

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/RadaidehDaniel]
