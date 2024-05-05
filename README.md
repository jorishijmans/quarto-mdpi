# MDPI (WIP - not functional yet)

<!-- REMOVE THIS IN YOUR FORMAT TEMPLATE -->
> Template for creating a new journal article format for Quarto. 
>
> This repository is a [Github Repository Template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) that you should use as a starter to create a new extension format. Click on the "Use this template" button at the top !
>
> See information about how-to use this repo template inside the template file or its rendered version at <https://quarto-journals.github.io/article-format-template/>

<!-- ALL THE BELOW SHOULD BE IN YOUR README -->

This is a Quarto template that assists you in creating a manuscript for Article Format Template journals. You can learn more about ...

## Creating a New Article

You can use this as a template to create documents for journals published by MDPI. To do this, use the following command:

```bash
quarto use template quarto-journals/mdpi
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add quarto-journals/mdpi
```

## Usage

To use the format, you can use the format names `mdpi-pdf` and `mdpi-html`. For example:

```bash
quarto render article.qmd --to mdpi-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  mdpi-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at <https://quarto-journals.github.io/article-format-template/>.

## Format Options

This format does not have specific format option. Include documentation of such option otherwise. See <https://github.com/quarto-journals/elsevier#format-options> for an example.

- [ ] ADD format options

