#  Zebra-ZD410 Locally Attached Label Printer Setup 
  
## Summary
Information contained here is for the setup of a label printing system using the ZD-410 Zebra printer and the Browserprint tool from Zebra. This setup will allow the web applicaion, Eleven, the ability to print to the locally attached printer without the need to select and confirm an attached printer. The Browserprint tool is included under the Windows diretory in the Landrys google shared drive.  The instructions to set it up is also included. Before installing the browserprint tool the printer needs to be connected and working on the computer. Eleven will connect to the the printer via the browserprint tool to print labels. Please follow procedure below to get it up and running.

## Procedure
   * Setup zebra label printer on computer by following zebra instructions. Make sure it is working before proceeding.
   * Install Broserprint tool. Get it from links below or from the file(zebra-browser-print-windows-v131445.exe) included  in shared drive. Follow instructions(zebra-browser-print-user-guide-v1-3-en-us.pdf) provided by Zebra. Those are also included in shared drive or can be downloaded from provided link.
   * Set up the attached printer as the default printer using the Browserprint tool settings. Please uncheck driver search.
   * Open up Eleven
   * Click on configuration icon ( snowman on top right ).
   * Select Local Printer Configuration
   * Click setup
   * The Default printer should be selected. If other printers are there be sure to select the ZPL printer not a driver.
   * Click TEST. If ok a label should be printed.
   * On Bikescanner select ZD410 Printer for printer.
   * Scan as before. Labels should print on locally attached label printer

## Browser Print 
  I included the download in this shared directory but if you need to get it yourself use link below. Be sure to select the one for Windows.
  * Application: https://www.zebra.com/us/en/support-downloads/printer-software/by-request-software.html
  * Guide: https://www.zebra.com/content/dam/zebra_new_ia/en-us/solutions-verticals/product/Software/Printer%20Software/Link-OS/browser-print/zebra-browser-print-user-guide-v1-3-en-us.pdf

## MAC

  *  Install CUPS on MAC: https://supportcommunity.zebra.com/s/article/Install-CUPS-driver-for-Zebra-Printer-in-Mac-OS?language=en_US
  *  http://localhost:631/printers/Zebra_Technologies_ZTC_ZD410_203dpi_ZPL

## OTHER
  *  Buy One: https://www.barcodefactory.com/zebra/printers/zd410/zd41023-d01000ez
