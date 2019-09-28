# Perl

Sample perl code

## Pre-requisites

- Perl

## Code

```pl
use strict;
use warnings;

use LWP;

sub main {
  print "Hello world!\n";
  print "This is libwww-perl-$LWP::VERSION\n";
}

main();
```

## Run

```bash
perl main.ph
```

Outputs

```bash
$ perl main.pl
Hello world!
This is libwww-perl-6.05
```

## References

- [Learn Perl by Doing - Part 1](https://app.pluralsight.com/library/courses/learn-perl-by-doing-part1/table-of-contents)