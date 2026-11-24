MediaDNA — Prototype Demonstration
MediaDNA is a prototype for exploring how media mentions are clustered, ordered, compared, attributed and assessed as evidence, alongside reputation intelligence workflows.
Open the project
Welcome page: open the GitHub Pages site root.
Interactive prototype: Launch prototype.
Sample workbooks
Download an input workbook, then open the prototype and upload it on the Engine Run page.
Input files
Standard sample input
NVIDIA CEO transition sample input
Reference outputs
These are example output workbooks for reference and comparison. They are not input files.
Standard engine output
NVIDIA engine output
Repository structure
```text
MediaDNA/
├── index.html             # Welcome page served by GitHub Pages
├── prototype.html         # Interactive MediaDNA prototype
├── README.md
├── samples/
│   ├── MediaDNA_Sample_Input.xlsx
│   └── MediaDNA_Sample_Input_Nvidia_CEO_Transition.xlsx
└── sample-outputs/
    ├── MediaDNA_Engine_Output.xlsx
    └── MediaDNA_Engine_Output_Nvidia.xlsx
```
GitHub Pages
For a repository named `MediaDNA`, configure GitHub Pages to deploy from branch `main` and folder `/(root)`. The root `index.html` is the welcome page; the prototype is available at `/prototype.html`.
Important notes
GitHub Pages is static hosting. It serves the HTML and downloadable workbooks; it does not provide a server, database, authentication or backend processing.
Workbook upload and processing must run in the browser. Test both sample workbooks on the published site before sharing it.
Anyone who can access a public repository can view and download its files. Publish only sample data you are authorised to share; remove personal, confidential, client or otherwise sensitive information first.
Prototype outputs are demonstration materials and should not be treated as verified production analysis without independent validation.
