# Image mosaics from feature matching

This is our proposed solution for the lab ["Image mosaics from feature matching"][repo] in the computer vision course [TEK5030] at the University of Oslo.

Please see the [lab guide][guide] for more information.

## Prerequisites
- [Ensure Conan is installed on your system][conan], unless you are not on a lab computer.
- Install project dependencies using conan:

   ```bash
   # git clone https://github.com/tek5030/solution-mosaic.git
   # cd solution-mosaic

   conan install . --install-folder=build --build=missing
   ```
- When you configure the project in CLion, remember to set `build` as the _Build directory_, as described in [lab_intro].

[repo]: https://github.com/tek5030/lab-mosaic
[guide]: https://github.com/tek5030/lab-mosaic/blob/master/README.md

[lab_intro]: https://github.com/tek5030/lab-intro/blob/master/cpp/lab-guide/1-open-project-in-clion.md#6-configure-project
[TEK5030]: https://www.uio.no/studier/emner/matnat/its/TEK5030/
[conan]: https://tek5030.github.io/tutorial/conan.html
