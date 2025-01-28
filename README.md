# CSS calc() Function Errors

This repository demonstrates a common error encountered when using the CSS `calc()` function: unexpected behavior caused by invalid calculations or inconsistent units.  The `bug.css` file contains the erroneous code, while `bugSolution.css` provides a corrected version.

The problem stems from attempting calculations resulting in invalid values (e.g., negative dimensions) or by combining units without proper conversion. This can lead to elements not rendering correctly, being hidden, or having unexpected dimensions.

The solution involves carefully reviewing the calculations within the `calc()` function to ensure valid results and consistent units, as shown in `bugSolution.css`.  Always ensure your calculations won't yield negative values, and maintain consistency in units.