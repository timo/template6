# Template6: A Template Engine for Perl 6 #

Inspired by Template Toolkit from Perl 5,
Template6 is a simple template engine designed to be
a content-neutral template language.

Eventually, I intend for this to be as powerful as
Template Toolkit, but for now I'm keeping it simple
and leaving it capable of easily adding new functionality.

I also intend to borrow features and ideas from
my own Flower and Garden projects.

## Currently implemented features

 *  get and set statements, including implicit versions.
    [% get varname %]
    [% varname %]
    [% set varname = value %]
    [% varname = value %]
 *  for statement.
    This replaces the FOREACH statement in TT2.
    It can be used in one of four ways:
    [% for listname as itemname %]
    [% for listname -> itemname %]
    [% for itemname in listname %]
    [% for itemname = listname %]
 *  if/elsif/else/unless statements.
    These as very simplistic at the moment.
  
## Author

This was build by Timothy Totten. You can find me on #perl6 with the nickname supernovus.

## License

Artistic License 2.0
