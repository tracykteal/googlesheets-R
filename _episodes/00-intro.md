---
title: "Introduction"
teaching: 15
exercises: 3
questions:
- "What are basic principles for using spreadsheets for good data organization?"
objectives:
- "Describe best practices for organizing data so computers can make the best use of data sets."
keypoints:
- "Good data organization is the foundation of any research project."
---

Good data organization is the foundation of your
project. Most people have data or do data entry in
spreadsheets, and now very frequently that spreadsheet software is Googlesheets.
Spreadsheet programs are very useful graphical
interfaces for designing data tables and handling very basic data
quality control functions.

*Overall good data practices*

Spreadsheets are good for data entry. Therefore we have a lot of data
in spreadsheets, so that's where we want to begin!

---

### Why aren't we teaching data analysis in spreadsheets

- Data analysis in spreadsheets usually requires a lot of manual
  work. If you want to change a parameter or run an analysis with a
  new dataset, you usually have to redo everything by hand. (We do
  know that you can create macros, but see the next point.)

- It is also difficult to track or reproduce statistical or plotting
  analyses done in spreadsheet programs when you want to go back to
  your work or someone asks for details of your analysis.

### Spreadsheet programs

This lesson is going to focus on Googlesheets as our spreadsheet program.

> ## Exercise
> - How many people have used spreadsheets in their work?
> - How many people have accidentally done something that made them
> frustrated or sad?
{: .callout}

Spreadsheets encompass a lot of the things we need
to be able to do in our work. We can use them for:

- Data entry
- Organizing data
- Subsetting and sorting data
- Statistics
- Plotting

We do a lot of different operations in spreadsheets. What kind of operations do you do in spreadsheets? Which ones do you think spreadsheets are good for?


## Problems with Spreadsheets

Spreadsheets are good for data entry, but in reality we tend to
use spreadsheet programs for much more than data entry. We use them
to create data tables for sharing, to generate summary
statistics, and make figures.

Generating tables in a spreadsheet is not
optimal - often, when formatting a data table for publication, we’re
reporting key summary statistics in a way that is not really meant to
be read as data, and often involves special formatting
(merging cells, creating borders, making it pretty). We advise you to
do this sort of operation within your document editing software.

The latter two applications, generating statistics and figures, should
be used with caution: because of the graphical, drag and drop nature of
spreadsheet programs, it can be very difficult, if not impossible, to
replicate your steps (much less retrace anyone else's), particularly if your
stats or figures require you to do more complex calculations. Furthermore,
in doing calculations in a spreadsheet, it’s easy to accidentally apply a
slightly different formula to multiple adjacent cells. When using a
command-line based statistics program like R or SAS, it’s practically
impossible to apply a calculation to one observation in your
dataset but not another unless you’re doing it on purpose.

### Using Spreadsheets for Data Entry and Cleaning

However, there are circumstances where you might want to use a spreadsheet
program to produce “quick and dirty” calculations or figures, and data
cleaning will help you use some of these features. Data cleaning also
puts your data in a better format prior to importation into a
statistical analysis program. We will show you how to use some features of
spreadsheet programs to check your data quality along the way and produce
preliminary summary statistics.

In this lesson, we will assume that you are using Googlesheets as
your primary spreadsheet program - there are others (Excel, gnumeric, Calc
from OpenOffice), and their functionality is similar.
