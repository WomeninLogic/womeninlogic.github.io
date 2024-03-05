# WiL website

The repository for the Women in Logic website.


## How to update workshops

To add a new workshop, or to edit a previous one, modify the `workshops/workshops.yml` file.
An example entry looks like the following:

```yaml
- title: WiL 2017
  location: Reykjavik, Iceland
  year: 2017
  website: https://sites.google.com/site/firstwomeninlogicworkshop/
  keynotes:
    - speaker: Catuscia Palamidessi
      website: http://www.lix.polytechnique.fr/~catuscia/
      talk: Differential Privacy and Applications to Location Privacy
      photo: catuscia-palamidessi.jpg
    - speaker: Claudia Nalon
      website: https://nalon.org
      talk: Strategies for Modal Theorem-Proving
      photo: claudia-nalon.jpg
```

Note that you will need to place the photos of the keynote speakers in the `workshops/photos/` folder.


## How to update SC members

To remove a member from the SC list, delete the `.yml` file (and the corresponding photo) in the `governance/sc-members/` folder.
To add a member, make a new `.yml` file with their name and with contents as follows:

```yaml
title: |
  [Valeria de Paiva](http://vcvpaiva.github.io)
year: 2025
image: sc-members/valeria-de-paiva.png
```

where `year` is the year until which they are appointed.
Note that you will need to place to photo in the `governance/sc-members/` folder as well.


## To-do:

- [] responsive design
