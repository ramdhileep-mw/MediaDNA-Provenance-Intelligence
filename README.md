# MediaDNA — Prototype Demonstration

MediaDNA is a prototype for exploring how media mentions can be clustered, ordered, compared, attributed and assessed as evidence. This repository contains the browser-based prototype and two sample input workbooks with corresponding example outputs.

## Launch the prototype

Once GitHub Pages is enabled, open the published site URL shown in **Settings → Pages**.

## Try the sample workbooks

1. Open the prototype website.
2. Use **Load Excel input…** to select one of the sample input workbooks below.
3. Review the generated views and results in the prototype.
4. The files in `sample-outputs/` are reference examples for comparison; they are not input files.

### Sample inputs

- [Standard sample input](samples/MediaDNA_Sample_Input.xlsx)
- [NVIDIA CEO transition sample input](samples/MediaDNA_Sample_Input_Nvidia_CEO_Transition.xlsx)

### Reference outputs

- [Standard engine output](sample-outputs/MediaDNA_Engine_Output.xlsx)
- [NVIDIA engine output](sample-outputs/MediaDNA_Engine_Output_Nvidia.xlsx)

## Repository contents

```text
MediaDNA/
├── index.html
├── samples/
│   ├── MediaDNA_Sample_Input.xlsx
│   └── MediaDNA_Sample_Input_Nvidia_CEO_Transition.xlsx
├── sample-outputs/
│   ├── MediaDNA_Engine_Output.xlsx
│   └── MediaDNA_Engine_Output_Nvidia.xlsx
└── README.md
```

## Publish with GitHub Pages

1. Create a GitHub repository named `MediaDNA`.
2. Upload all files and folders from this project, keeping `index.html` at the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish and open the URL shown on the Pages settings screen. It will usually look like `https://YOUR-USERNAME.github.io/MediaDNA/`.

## Important notes

- This is a static browser-based prototype. GitHub Pages serves the HTML and downloadable workbooks; it does not provide a server, database, authentication or backend processing.
- Test workbook upload and processing on the published site before sharing it with others.
- Anyone who can access a public repository can view and download its files. Publish only sample data you are authorised to share; remove personal, confidential, client or otherwise sensitive information first.
- The prototype and sample workbooks are demonstration materials. Do not treat prototype outputs as verified production analysis without independent validation.
