# CV Julien Caselmann

- Language: 🏴󠁧󠁢󠁥󠁮󠁧󠁿
- Template: Professional, no Image

Check [it][github_page_link] out!

## Adding a new CV template

- Checkout any branch BUT the ```main``` branch! You do NOT want to copy the main workflow, since it will publish a new version of the CV on the [Github Page][github_page_link]. Checkout any other branch!
- Adapt the .tex file name to have a name that DOES NOT EXIST YET in the ```pdfs``` branch, otherwise you will overwrite an existing pdf.
- Adapt the ```build.yml``` workflow, i.e. the file name in the build step and maybe rename the jobs to the name of you cv so it looks nicer in the GitHub Actions overview.
- Push your changes and the newly compiled PDF will appear in the ```pdfs``` branch!

Done!

## Changing the main CV

- Simply merge the branch of the CV you want to see as the main CV into the ```main``` branch. Make sure you DO NOT overwrite this README and make also sure to rename the main tex file to ```cv.tex```

Done!

[github_page_link]: https://julienandco.github.io/lebenslauf/cv.pdf
