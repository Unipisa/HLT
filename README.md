# Supporting the preservation of legacy source code.

Instantiating this template creates a workbench to support the acquisition of legacy source code, according to [SWHAP](https://www.softwareheritage.org/swhap/), the [Software Heritage](https://www.softwareheritage.org/) Acquisition Process defined by the [SWHAP\@Pisa](
    #TODO:
) project.

The workbench comes with the predefined folders that are used in the supported process. Namely:

- Folder [raw materials](./raw_materials) is for the original materials, as they have been found or submitted.

- Folder [browsable source](./browsable_source) is for a browsable version of the source code. Source files, with the right extension, have to be accessible through the GitHub web interface, e.g., archives should be decompressed, code should be transcribed if provided by images, etc.

- Folder [source](./source) is for the curated revision of the source code, as a base for the reconstruction of the development history as a git repository.

- Folder [metadata](/.metadata) holds various files with meta information (catalogue, actors, journal, tags) to be updated throughout the process. 

Please note that this file need be **replaced** in the instantiated workbench.

Please look at the [SWHAPPE repository](https://github.com/Unipisa/SWHAPPE/README.md) and to the [guidelines](https://github.com/SoftwareHeritage/swhapguide/blob/master/SWHAP%40Pisa.pdf)  for more details. 
