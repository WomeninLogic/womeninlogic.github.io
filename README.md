# WiL website

The repository for the Women in Logic website.


## How to update workshops

To add a new workshop, or to edit a previous one, simply modify the `workshops/workshops.yml` file.
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


## To-do:

- [] responsive design
