Fun with formatting

Since I never remember which way round headings go in markdown, let's have a play around.

---

# Heading 1

That should be the biggest.

## Heading 2

This is normally a subheading, but might be the size of the post title on the index page?

### Heading 3

I remember this is something on the index page but not what...
Oh yes, this is the level used for blog post titles after all.

#### Heading 4

This is the level you would want to use for subheadings inside a blog post, it matches the left-indentation of the rest of the body text.
But do we dare dream to go smaller?

##### Heading 5

Nobody knows where we might end up, but that's already too small and squishy.

While we're at it, how about some other formatting?
Like a code block:

    def hello():
        print("hello world!")

That needs some specific CSS to display newlines as written, if you were to wrap it in triple-backticks.
Indenting by four spaces seems better for actual code blocks, because then there's no conflict with formatting inline monospace using single backticks.

Or a blockquote:

> On 01 July 2020 Dan wrote:
>
> This is far too much time to spend on making up a blog.

I guess we can also see what the `blog.css` does with lists, cos it has some specific settings:

- Here is one list item
- And another one
- One more for good measure

Wonder what the spacing at the bottom is like?

Tags: formatting-fun
