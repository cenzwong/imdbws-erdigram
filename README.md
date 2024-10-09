# imdbws-erdigram
Using D2 Diagram as Code for IMDB WS to draw ER Diagram


# D2 Installation
```sh
curl -fsSL https://d2lang.com/install.sh | sh -s --
```

# D2 Usage
```sh
d2 --help
man d2

echo 'x -> y' > input.d2
d2 -w input.d2 out.svg # watch

d2 fmt file.d2
```