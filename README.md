# Spreadsheet::Compare

[![](https://github.com/tomk3003/spreadsheet-compare/workflows/linux/badge.svg)](https://github.com/tomk3003/spreadsheet-compare/actions) 
[![](https://github.com/tomk3003/spreadsheet-compare/workflows/macos/badge.svg)](https://github.com/tomk3003/spreadsheet-compare/actions) 
[![](https://github.com/tomk3003/spreadsheet-compare/workflows/windows/badge.svg)](https://github.com/tomk3003/spreadsheet-compare/actions)

## Perl module for comparing spreadsheet-like datasets

Spreadsheet::Compare analyses differences between two similar record sets.
It is designed to be used for regression testing of a large number of files,
databases or spreadsheets.

The record sets can be read from a variety of different sources like CSV files,
fixed column input, databases, Excel or Open/Libre Office Spreadsheets.

The differences can be saved in XLSX or HTML format and are visually highlighted
to allow fast access to the relevant parts.

Configuration of a single comparison, sets of comparisons or whole suites
can be defined as YAML configuration files in order to persist a setup that can be run
multiple times.

Use it on the command line with the included command line script *spreadcomp*

[Documentation on Metacpan](https://metacpan.org/pod/Spreadsheet::Compare)
