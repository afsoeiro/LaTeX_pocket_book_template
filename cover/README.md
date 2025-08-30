# How Book Covers Work

In professional printing, the cover is a completely separate file from the book's interior text.

1.  **Finalize the Interior:** You compile your LaTeX code into a final PDF. This is called the "book block".
2.  **Get Final Specs:** You need three pieces of information for the cover designer:
    * **Trim Size:** The final dimensions of the book (e.g., 4.25" x 6.87").
    * **Page Count:** The exact number of pages in your final PDF.
    * **Paper Type:** The type of paper you will print on (e.g., cream or white, and its thickness).
3.  **Calculate Spine Width:** The page count and paper type determine the thickness of the book, which is the **spine width**. Print-on-demand services like Amazon KDP provide online calculators for this.
4.  **Design the Cover:** The cover designer takes the trim size and spine width to create a single, large PDF that includes the front cover, spine, and back cover.
5.  **Upload Separately:** When you upload to a printer or a service like KDP, you will upload your interior PDF and your cover PDF as two separate files.

The `cover_placeholder.pdf` in this folder is just for your reference. **It is not part of the LaTeX compile process.**
