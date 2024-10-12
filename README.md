# imdbws-erdigram
Using D2 Diagram as Code for IMDB WS to draw ER Diagram

This repository demonstrates how to visualize the structure of IMDb datasets and efficiently organize D2 files. The project showcases an Entity-Relationship Diagram (ERD) for the IMDb dataset, highlighting key entities and their relationships. It also demonstrates best practices for organizing D2 files within a data engineering project.

You could play around with d2 online: [D2 Playground](https://play.d2lang.com/?script=tFVBj9NMDL3Pr7D0XT4O8ANyQEJI3FgQipA4VU7ipqaJHTwOVbTqf0dN0nS67JYglaM9z573_DyJYEubAiOXMYPHABB32FEG8UezcSwaCgBSqkTPILqx1PA4hoYsnkFn3KINmz0NxwDn8AFbOuMDQMHmu2-ElgGLB4CK8Dox13023VKMrJIBmuHw_9TjVQDYix7kg1rO3lB8en4MwU8HG9zjy0r8hpKtGnEtZyVqFZ1AZ4Zj90STUT3SXBINSt1jnWJ86H5nCoDuxkXvz51x_GRcs2CTTxcWqs1F3R-c8vVOjf3yoUv5zpD8iVS9ZrTkOb6r-sZnjgDR0Tx1laSawsvUenFu6SPLJH_C1SR2w9LS6HAPSys2Kl3tmbEfjJ3sZQrUcdSK7sGiQyPxfH1BJIwqD31b0GWyE580uXDtjKXkDpt_8QxkfWmJTrXakNj_XYskKndoWE5zn5OLCENnqe_ykvEnGdb0ZeyYwbZRHJX07VddlvAYwn_wXkWodFZJNu_NdBW8fgvpG5zT1_vxV9h0EW5XLI6u6j-PbhX29LVcBbxQkAWd_DvmbPgVAAD__w%3D%3D&sketch=1&layout=dagre&theme=100&)

# D2 Installation

Run the following command to install d2

```sh
curl -fsSL https://d2lang.com/install.sh | sh -s --
```

> Reference: https://d2lang.com/

# D2 Usage

## Export

You can export the diagram to svg/png/pdf

```sh
d2 -w input.d2 out.svg # watch
d2 --sketch imdb.d2 imdb.png # export all-in-one d2 file
d2 --sketch imdb_d2/connections.d2 output/imdb.png # export d2 files
d2 --sketch imdb_d2/connections.d2 output/imdb.pdf # export to pdf
```

## Formatter

It also comes with a formatter

```sh
d2 fmt file.d2
```

