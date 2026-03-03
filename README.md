# docassemble-texas-FM-34-109

A [DocAssemble](https://docassemble.org/) package that guides users through the **Authorization Agreement for Voluntary Adult Caregiver** (Texas form **FM-34-109**). This is a parental delegation / voluntary adult caregiver agreement for Texas, allowing a parent to authorize another adult to care for a child under Texas Family Code.

## What this interview does

The interview collects the information needed to complete FM-34-109, including:

- **Child:** full name and date of birth  
- **Submitting parent:** full name, address, phone, and other contact info  
- **Other parent:** full name, address, phone, and other contact info  
- **Voluntary adult caregiver:** full name, address, phone, and other contact info  
- **Relationship to child:** e.g. Adult Caregiver, or Parental Child Safety Placement Voluntary Caregiver (per Texas Family Code, Subchapter L)  
- **Eligibility:** confirmation the child is not subject to a conflicting authorization and court-involvement status  
- **Optional:** earlier expiration date and circumstances for termination  
- **Signatures:** parent, other parent (if present), and voluntary adult caregiver  

At the end, the user is reminded to print the form and have it notarized by a Notary Public in and for the State of Texas.

## Requirements

- A DocAssemble server (see [DocAssemble documentation](https://docassemble.org/docs/)).
- The **FM-34-109** form template. The interview is set up to use a template file; you must provide the official form (e.g. as a DOCX or PDF, depending on your template setup) in the appropriate package location so the final document can be generated.

## Installation

Install this package on your DocAssemble server. From the DocAssemble Playground, go to **Packages** and install from GitHub:

- **GitHub URL:** `https://github.com/jjasghar/docassemble-texas-FM-34-109`

Or install via pip in an environment where your DocAssemble server runs:

```bash
pip install git+https://github.com/jjasghar/docassemble-texas-FM-34-109
```

Ensure the FM-34-109 form template file is present in the package’s template/static area as expected by the interview (see the `attachments` block in `docassemble/texasFM34109/data/questions/main.yml`).

## Development

- **Package name:** `docassemble.texasFM34109`  
- **Main interview:** `docassemble/texasFM34109/data/questions/main.yml`  
- **CI:** GitHub Actions run the SuffolkLITLab `da_build` workflow on push/PR to `main` and `master`.

## License

MIT. See [LICENSE](LICENSE) for full text.

## Author

JJ Asghar – [jjasghar@gmail.com](mailto:jjasghar@gmail.com)
