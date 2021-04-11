# 9R0-789sdv6394

## About this project

This project contains community derived answers of past exams and other
assessed and non-assessed material.

## Contributing

Contributions are made per module. Please read this README in its entirety
before contributing to this module. 

### Acceptable contributions

We accept all contributions that add or modify existing answers to previous
past papers and any other assessed material that is not likely to be reused
by module leaders in subsequent years.

We also accept contributions to non-assessed materials such as questions in
slides.

Hence we do not accept contributions pertaining to assessed material that is
likely to be reused in subsequent years, such as coursework.

When in doubt, please post an issue first describing what you wish to upload.

### File formats

To keep the size of the repository managable, only .tex (and accompanying style
and bibliography) are allowed to be contributed. 

This means that images and PDFs cannot be included into the repository.

Understandably most questions are only available in PDF format.
Please contact the appropriate maintainer to obtain a link to any question
resources that you do not have.

### Module Codes

Module codes are not to be mentioned explicitly anywhere in this repository.
Instead please use this caesar cipher: https://planetcalc.com/8572/
The key for encryption/decrytion is ROT15.

### Adding a new module

All new modules must be located in a new directory at the root of the project
with the encrypyed module code.

The person who adds a new module is the default maintainer of material in that
module.

This person at a minimum must upload the following files into the new directory:

README.md - This should establish guidance on contributing to this particular
module. For example, guidelines on how to name further subdirectories (if any)
and guidance on how to name files and where to place them.

MAINTAINERS - A new-line-separated list of maintainers (github usernames) of
this module that should have permission to approve contributions.

### Adding material

Before contributing make sure one has adhered to any rules and guidelines
stipulated in this README and any subsequent READMEs located in the
subdirectories that you are contributing to.

Any new additional documents should also edit .github/workflows/CI.yml and add
the root tex file to the repository for CI purposes.
