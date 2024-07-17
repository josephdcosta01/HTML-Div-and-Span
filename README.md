# HTML-Div-and-Span

The HTML elements div and span are different because they have no semantic value by themselves. This means that they are the perfect HTML tags to use when you have to separate content for purely visual purposes.

By themselves, div and span will not do anything. These elements are primarily used as "hooks" for your CSS (as well as JavaScript). You use them to divide or label your HTML when another, more semantic tag will not work. These will be targeted as selectors in our CSS.

Span Tag
The span element is an inline HTML element that is used to group a set of inline elements. Generally speaking, you use span to hook text or a group of elements that you want to style differently. Often though, you can do this more semantically by using other elements like em or strong.

Example: You might use the span tag in combination with the class attribute to mark a section of text you wanted to highlight in some way.

<p>
  Lorem ipsum dolor sit amet, <span class="highlight">consectetur</span>
  adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore.
</p>
Be careful to make sure that you are not using the span tag when another HTML tag (like em or strong) would make more sense semantically.

The new mark element in HTML5 actually makes the previous example semantically incorrect. The following example is more semantically correct:
