# ng2-slim-scroll

> DISCLAIMER: This is just a draft, a PoC based on the implementation of [nanoScrollerJS](https://jamesflorentino.github.io/nanoScrollerJS/) 

Simply add the `ScrollerComponent` and `SliderDirective` to your app module and you're good to go. There is no additional dependencies at the moment.

```
<my-scroller>
  <h1>{{ post.title }}</h1>
  <my-post [id]="post.id">
  <my-post-footer [tags]="post.tags">
</my-scroller>
```