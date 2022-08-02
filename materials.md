---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Creating materials

We primarily produce learning materials through jupyterbook. Jupyterbook is a project that takes materials either in the jupyter notebook format or in Markdown and generates beautiful interactive websites. *This website* is created in jupyterbook!

Jupyter books can mix formatted text, math, code, images, videos and interactive demos. We also incorporate formattive assessments (e.g. multiple choice questions). This allows publishing highly interactive materials without the constraints and clunky interfaces of traditional learning management systems (LMS). Because the material is plain text, it can be easily cut, pasted, remixed and translated!

[The documentation for jupyter books is here](https://jupyterbook.org/en/stable/intro.html).

## Showcase

Jupyterbook can create formatted text:

* Hello **world**!
* This is a *second* bullet point

It handles math in LaTeX format, like $e^{i\pi}=-1$.

It can integrate images, such as our logo:

```{figure} images/c4rlogo.png
---
scale: 50%
---
Our logo
```

It can integrate and run code, for example in Python:

```{code-cell}
print(2 + 2)
```

Finally, it can generate formative quizzes such as this one:

```{quizdown}
---
primary_color: orange
secondary_color: lightgray
text_color: black
shuffle_questions: false
---

## What is the capital of Germany?

> It's the largest city in Germany.  

- [x] Berlin
- [ ] Cologne
- [ ] Frankfurt
- [ ] Munich

## Put the [days](https://en.wikipedia.org/wiki/Day) in order!

> Monday is the *first* day of the week.

1. Monday
2. Tuesday
3. Wednesday
4. Friday
5. Saturday  
```

Check out the Markdown source of this page to find out how.

## Submitting and reviewing materials

We handle back and forth between METER and CENTER through [github](https://github.com). Compared to emailing back and forth annotated `.docx` files, this method allows us to easily timestamps and diff each version, perform transparent review available to all, and track the provenance of all documents. No more `final_revision_final_final_real_final_2.0.1.docx`!