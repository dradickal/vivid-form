Vivid Form
==========

Code sample for Vivid Seats

An interesting issue with Firefox occurred when rendering the form section.
Having the label in the first position of the flex-box, and setting it to position of absolute left a white space at the left end of the form.
This should not have occurred because of `justify-content: space-between;`. By moving the label to the middle element however, the two outer elements aligned to the edges as they should.