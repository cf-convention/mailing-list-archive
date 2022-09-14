# mailing-list-archive
Archive of all CF discussions from 2002 to 2019, including questions, standard names and enhancements.

This repo exists solely to contain the archive. Please raise any issue about it in the [`cf-convention.github.io` repo](https://github.com/cf-convention/cf-convention.github.io/issues), not in this one.

While active, the CF mailing list, called `CF-metadata`, was hosted by the <a href="https://www.cgd.ucar.edu">Climate and Global Dynamics Laboratory</a> of the US National Center for Atmospheric Science, using `mailman` software. The software provides archives of each year of traffic as a separate plain-text file in <a href="https://www.loc.gov/preservation/digital/formats/fdd/fdd000383.shtml">MBOX format</a>. The archives for each year of the CF mailing list were downloaded and concatenated into a single file `mailing-list-archive`, which can be found in the `Data` directory of this repo.

This file was converted into a directory of linked HTML files, with one file for each email, by executing `hypermail -d . -m mailing-list-archive -o hm_defaultindex=date -l "Archive of CF discussions from 2002 to 2019 on the cf-metadata mailing list"` in the `Data` directory. The HTML files of emails were subsequently edited by a script to add the links which appear as red arrows at the top and the bottom.

In order to present the `Data` directory on the web, this `mailing-list-archive` repo is used as a <a href="https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages">GitHub Pages</a> project website. The URL of a project website is _organisation_`.github.io/`_repo_, which in this case is `cf-convention.github.io/mailing-list-archive`. The domain `cfconventions.org` points to `cf-convention.github.io`. Thus [`cfconventions.org/mailing-list-archive/Data`](https://cfconventions.org/mailing-list-archive/Data) is a URL for the mailing list archive, because it points to `cf-convention.github.io/mailing-list-archive/Data`.
