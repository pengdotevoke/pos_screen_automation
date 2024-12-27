This modules disable the order button in POS. Instead of printing receipt, it shows a confirm order screen then the validate button prints the receipt. 
Particularly usefull in POS Restaurant especially in cases where there is only one printer and you need the receipt to not be printed twice, both by the order and the validate button.
You can customize the final receipt to contain both order and bill sections, using a CSS page break to divide the two sections
Using firefox always_print_silent flag as true, you could set up a PDF printer, like bullzip or PDF Creator to save your receipt as PDF
You'll probably need folder automation tool like Foldermill or Automation workshop to set up any receipt saved as PDF to be sent to the printer
