# *Latex_Temp*
This is an _UNOFFICIAL_ NWU LaTeX template for use by NWU students. If you have suggested changes, please submit a pull-request. I will try to keep this repo maintained as much as possible and in line with the official Word template on the [NWU Library site](http://services.nwu.ac.za/it/sc/nwu-templates-postgraduate) however it remains your responsibility to ensure that the template you clone from here meets the requirements of your supervisor/lecturer. 

This template has been recreated using the latest packages as well as following the newer conventions with respects to LaTeX formatting as suggested by the package maintainers of the packages utilised in this template. 
 
## Suggested toolchain
These apps are merely suggestions based on the experiences of others. Although there are other apps these are the easiest to interface with and use.
1. [Zotero](https://www.zotero.org/) is a reference manager
2. [Better Bibtex](https://github.com/retorquere/zotero-better-bibtex/releases/) is a plugin for zotero which speeds up referencing speed
3. [Texmaker](https://www.xm1math.net/texmaker/) as a LaTeX front-end
4. [MikTex](https://miktex.org/download) as a LaTeX backend (you will very seldomly need to open this app, but it is required to get LaTeX working on windows (*MikTex is not needed for Linux installations*)

## Setup of suggested toolchain
1. Install MikTex
2. Install TeXMaker
3. Install Zotero
4. Install Better-Bibtex add-on from within zotero see [here](https://retorque.re/zotero-better-bibtex/installation/) for installation guide

## Getting started
*This quick start uses Miktex, texmaker and zotero*
### First Time Run
1. Clone the template into a local folder
2. Open from within Texmaker 
3. Run the blank template *Note that the first run will take LONG since it first needs to install all the needed packages* This process will need to be repeated a couple of times (typically 5) the first time, thereafter a single run should suffice.

### Referencing
*In order to get references working you need to change a setting within texmaker*
1. Navigate to the options tab on the navbar at the top of Texmaker
2. Select from the dropdown list "Configure Texmaker"
3. A settings window will open
4. Check the "Embed" setting in the Pdf Viewer box towards the bottom right of the settings window (optional step but advised for ease of use)
5. Select the second big Tex logo on the left-hand side of the window (the one with the Quick Build heading)
6. Select the second item in the quick build menu (that is the "PdfLaTeX + Bib(la)tex + PdfLaTeX (x2) + View Pdf" option)
7. Click ok
8. Happy referencing

### Zotero guide
*This is the easiest way to reference within LaTeX short of writing the references 1-by-1*
1. In Zotero create a new collection for each LaTeX document
2. Right click on the collection containing your references and click the "Export Collection" option
3. Make sure the Format is Better BibTex and check the "Keep Updated" box
4. Once you click ok navigate to the folder where your LaTeX document is and save the file there with a sensible name.
5. Zotero should automatically update the reference file each time you add a new reference.
6. Once you have added a new reference in Zotero, navigate to the Edit tab on the texmaker navbar and click the "Refresh Bibliography" option at the bottom of the menu. Your citations should now be imported automatically into Texmaker.

### Known bugs
The packages needed for IEEE referencing cause errors during compilation if there is not a reference in your document. As such make sure you either comment out your bibliography or have at least one citation in your document.

### Disclaimer
This is an UNOFFICIAL template derived from the official MS Word templates available on the [NWU Library site](http://services.nwu.ac.za/it/sc/nwu-templates-postgraduate). The maintainer of this repository makes no claim to any of the intellectual property belonging to the NWU and its subsidiaries as is contained within this repository. The maintainer of this package also at no time received any compensation/remuneration for the creation of this template, the creation of this template was done in a private capacity and in good faith to assist students working with LaTeX. The maintainer will not be held responsible for any damages resulting from the use of this template. This template is provided AS-IS and it is the responsibility of the end-user to ensure that it meets the requirements as set forth by their supervisor.
