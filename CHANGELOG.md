# Change Log
---


## [2.1.0] - 2017-10-21

### Added
1. Ability to provide a direct DOM element (as an alternative to providing an _id_)


## [2.0.0] - 2017-04-19

### Added
1. Ability to create the pseudo-select based on existing selects
2. [SUIT](https://suitcss.github.io/) naming convention for CSS

### Removed
- [ BREAKING ] - ability to modify CSS classes through options
- [ BREAKING ] - ability to set the pseudo-select opened through options (can be done with existing *.open()* method instead)
- [ BREAKING ] - the hidden input to store the pseudo-select value (unnecessary with setting and using the value of original select element)