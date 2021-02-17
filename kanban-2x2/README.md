# Kanban 2x2

## Workflow + Template

Add this block anywhere in your Roam graph:

- [[roam/templates]] 2x2
    - [[2x2]]
        - {{[[kanban]]}}
            - [[Important]] + [[Urgent]]
            - [[Important]] + [[Not Urgent]]
            - [[Not Important]] + [[Urgent]]
            - [[Not Important]] + [[Not Urgent]]

> You can nest any 4 child blocks you want under `[[2x2]]` and `{{[[kanban]]}}`, this template is an example that I use

![](https://user-images.githubusercontent.com/635044/108231228-65f8c500-70f6-11eb-9a29-4ea7b2e00c29.png)

## CSS

Insert this line up top on your [[roam/css]] page along with any other @ import lines.

```css
@import url('https://itsjustmath.github.io/roam-css/kanban-2x2/styles.css');
```
