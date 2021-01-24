# pdfcat
|     key | description
|     ---:|:---
|  script | pdfcat - concatenate pdf's
|    type | bash
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 0.00
| license | GNU General Public License

pdfcat concatenates two or more pdf's to one pdf. If a specified filename has no
.pdf extension, it is added. If no output file is specified, standard output is
used.
The output pdf page size will be A4, unless the --geometry option is used.
With the --crop option, every page will be cropped with zero margin, unless
the --margins option specifies other margins.
The --margins option implies --crop and specifies left, top, right, and
bottom margins in mm in a space separated string, which must of course be double
quoted. The value can also be a single number, which is used for all margins.
If this option is not used, --crop will apply zero margins.
