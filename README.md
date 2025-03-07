# University of Alabama Libraries Scholarly API Cookbook Archive

> [!IMPORTANT]
> This repository is a publicly available archive of recipes previously in the University of Alabama Scholarly API Cookbook. As of now, this archive includes Matlab, Mathematica, and C recipes. They are not being maintained nor updated. Please see the latest [University of Alabama Libraries Scholarly API Cookbook](https://ua-libraries-research-data-services.github.io/UALIB_ScholarlyAPI_Cookbook) for current tutorials.

## License and Reuse

Most of the code in this repository is licensed under the [MIT License](https://github.com/UA-Libraries-Research-Data-Services/Scholarly_API_Cookbook_Archive/blob/main/LICENSE). This includes code written to be used with Wolfram Mathematica and MathWorks MATLAB. However, these proprietary software packages themselves are not covered under the MIT License, and users must have valid licenses for Mathematica and MATLAB to run the associated code.

The C code in this repository is licensed under the MIT License. This repository provides only the source code, and users will need to compile the C programs to run them. Some of the C code depends on external libraries such as curl, jq, and YAZ, which are licensed under their own respective terms. These libraries will need to be obtained and installed separately by the user.

The Bash tutorials are licensed under the MIT License (Bash itself is licensed under the GNU General Public License). Some of the included scripts may rely on external tools such as curl, jq, yaz, and gnuplot, each of which is licensed under its own terms. Users must obtain and install these tools separately. Refer to the documentation of each tool for installation instructions and licensing details.

We have endeavored to follow the appropriate terms and usage policies of each scholarly API, web service, and Z39.50 server. We have linked to the terms and policies where possible. Some database APIs may require a valid library subscription, institutional access, or individual account to use their services. Please be responsible when reusing these scripts and respect the API terms and usage policies (e.g., query limits, record downloads, data sharing restrictions). Data output snippets shown in this book are for demonstration purposes and are credited to the individual API or database service. The output generated from APIs or services remains subject to the terms and conditions of the respective provider. Some outputs (e.g., U.S. Government works) may be in the public domain, while others may require attribution or adherence to other conditions.

If you reuse the code, attribution would be appreciated. Please link to the Cookbook and cite our manuscript:

Link to Cookbook: https://ua-libraries-research-data-services.github.io/UALIB_ScholarlyAPI_Cookbook

Citation: Scalfani, V. F.; Walker, K. W.; Simpson, L.; Fernandez, A. M.; Patel, V. D.; Ramig, A.; Gomes, C.; Moen, M. T.; Nguyen, A. M. Creating a Scholarly API Cookbook: Supporting Library Users with Programmatic Access to Information. Issues in Science and Technology Librarianship, 2023, No. 104. https://doi.org/10.29173/istl2766.

```bibtex
@article{scalfani_creating_2023,
        title = {Creating a {Scholarly} {API} {Cookbook}: {Supporting} {Library} {Users} with {Programmatic} {Access} to {Information}},
        issn = {1092-1206},
        shorttitle = {Creating a {Scholarly} {API} {Cookbook}},
        url = {https://journals.library.ualberta.ca/istl/index.php/istl/article/view/2766},
        doi = {10.29173/istl2766},
        abstract = {Scholarly web-based application programming interfaces (APIs) allow users to interact with information and data programmatically. Interacting with information programmatically allows users to create advanced information query workflows and quickly access machine-readable data for downstream computations. With the growing availability of scholarly APIs from open and commercial library databases, supporting access to information via an API has become a key support area for research data services in libraries. This article describes our efforts with supporting API access through the development of an online Scholarly API Cookbook. The Cookbook contains code recipes (i.e., tutorials) for getting started with 10 different scholarly APIs, including for example, Scopus, World Bank, and PubMed. API tutorials are available in Python, Bash, Matlab, and Mathematica. A tutorial for interacting with library catalog data programmatically via Z39.50 is also included, as traditional library catalog metadata is rarely available via an API. In addition to describing the Scholarly API Cookbook content, we discuss our experiences building a student research data services programming team, challenges we encountered, and ideas to improve the Cookbook. The University of Alabama Libraries Scholarly API Cookbook is freely available and hosted on GitHub. All code within the API Cookbook is licensed with the permissive MIT license, and as a result, users are free to reuse and adapt the code in their teaching and research.},
        number = {104},
        urldate = {2023-10-13},
        journal = {Issues in Science and Technology Librarianship},
        author = {Scalfani, Vincent F. and Walker, Kevin W. and Simpson, Lance and Fernandez, Avery M. and Patel, Vishank D. and Ramig, Anastasia and Gomes, Cyrus and Moen, Michael T. and Nguyen, Adam M.},
        month = oct,
        year = {2023},
}
```
