# PhysRevBST
The BibTeX bibliography style file "apsrev4-1.bst" distributed by the American Physical Society with RevTeX 4.1 does not handle reference to the Journal of High Energy Physics properly.  This is a modified version that does handle them properly.

To use this, put apsrev4-1-JHEPfix.bst in the same directory as your document or install it somewhere in the TeX search path (and don't forget to run `mktexlsr`), then use BibTeX as normal, but put `\bibliographystyle{apsrev4-1-JHEPfix}` instead of the usual `\bibliographystyle{apsrev4-1}`.  Then, any references whose `journal` field is exactly "J. High Energy Phys." will be formatted correctly.
