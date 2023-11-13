
# A fork from Steve’s R Markdown Templates

`rmarkdownTemplates` is a fork of `stevetemplates` that help you create lovely R Markdown
documents, primarily for conversion to LaTeX PDFs. 

## Installation

`rmarkdownTemplates` is and will always be a "development" version package intended for
my personal use, others are welcome to fork/use though. You can install the development version of
`rmarkdownTemplates` from Github via the `devtools` package. The `remotes` package would probably 
work too.

``` r
devtools::install_github("AldridgeCaleb/rmarkdownTemplates")
```

## Usage

The easiest way to use the templates is within Rstudio. Go to *File \>
New File \> R Markdown*. Here, select any template you’d like to use.
The version on CRAN should lag behind the development version, but the
development version includes the following templates:

  - **Academic CV Template**: This is an academic CV template I *began*
    modifying from `stevetemplates` in 2023. You can call it in the YAML
    with `rmarkdownTemplates::cv`.
  - **Cover Letter Template**: This is an cover letter template I *began*
    modifying from `stevetemplates` in 2023. You can call it in the YAML
    with `rmarkdownTemplates::cover_letter`.
  - **Cover Letter Template**: This is an "statement" (e.g., research
    statement) template I *began* modifying from `stevetemplates` in 2023.
    You can call it in the YAML with `rmarkdownTemplates::statement`.

The user should notice that the YAML contains the functions (loaded in
this package) to compile these documents. They are basic wrappers for
`rmarkdown::pdf_document`. Please consult Steve's posts and
[the template
repository](https://github.com/svmiller/stevetemplates/tree/master/inst/rmarkdown/templates)
for rudimentary examples and the underlying code to help guide your
usage.
