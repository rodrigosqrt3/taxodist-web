# taxodist website

Documentation website for [`taxodist`](https://rodrigosqrt3.github.io/taxodist-web/), an open-source project for taxonomic hierarchy distances and lineage analysis in R, Python, and Julia.

The current coordinated release is **0.7.0**.

The site documents how `taxodist` retrieves ordered lineages from [The Taxonomicon](http://taxonomicon.taxonomy.nl), compares taxa through the depth of their most recent common ancestor, and integrates the resulting distance objects with multivariate analysis workflows.

> `taxodist` measures separation within a recorded taxonomic classification. Its values are not evolutionary time, genetic distance, morphological divergence, or phylogenetic branch length.

## Documentation

The website includes:

- installation and introductory workflows for R, Python, and Julia;
- the definition, properties, assumptions, and limitations of the distance measure;
- statistical applications using clustering, ordination, taxonomic distinctness, Mantel tests, and PERMANOVA;
- a cross-language compatibility guide;
- a complete function reference and changelog;
- citation, data-source, and reproducibility guidance.

Visit the published site at:

**https://rodrigosqrt3.github.io/taxodist-web/**

## Related projects

- [R package](https://cran.r-project.org/package=taxodist) — [source code](https://github.com/rodrigosqrt3/taxodist)
- [Python package](https://pypi.org/project/taxodist/) — [source code](https://github.com/rodrigosqrt3/taxodist-py)
- [Julia package](https://platform.juliahub.com/ui/Packages/General/Taxodist/) — [source code](https://github.com/rodrigosqrt3/taxodist-jl)
- [Interactive web application](https://3w6g1b-rodrigo-villa.shinyapps.io/taxodist_app/)

## Local preview

The website is built with [Quarto](https://quarto.org/). From this directory, run:

```bash
quarto preview
```

To render the complete static site:

```bash
quarto render
```

Rendered files are written to `_site/`.

## Data source

Lineage data retrieved by `taxodist` originate from **The Taxonomicon**, based on *Systema Naturae 2000* by S. J. Brands. Published analyses should cite both the software and the underlying classification source.

## License

The `taxodist` software is distributed under the GNU General Public License version 3 or later.
