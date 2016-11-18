# Chicago Police Misconduct FOIA Data Cleanup

Data can be accessed through links [here](http://thememoryhole2.org/blog/cpd-complaints)

Used `pdftohtml` with options `-s -i -c` to extract PDF with style attributes for locations.

### Notes

* `NAME_NO_INITIAL` is added to merge the pre and post 2001 data
* `_dedupe.csv` version has all duplicate `CR_NO`/`NAME_NO_INITIAL` removed
* `combined_officer_complaints.csv` leaves in redundant data because there are
  some acknowledged inconsistencies
