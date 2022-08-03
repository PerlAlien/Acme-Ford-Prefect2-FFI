# Acme::Ford::Prefect2::FFI ![linux](https://github.com/PerlAlien/Acme-Ford-Prefect2-FFI/workflows/linux/badge.svg)

FFI test module for Alien::Base

# SYNOPSIS

```perl
use Acme::Ford::Prefect2::FFI;

my $answer = Acme::Ford::Prefect2::FFI::answer(); # == 42 of course
```

# DESCRIPTION

[Alien::Base](https://metacpan.org/pod/Alien::Base) comprises base classes to help in the construction of `Alien::` modules.  Modules in the [Alien](https://metacpan.org/pod/Alien) namespace are used to locate and install (if necessary)
external libraries needed by other Perl modules.

This module is a toy module to test the efficacy of the [Alien::Base](https://metacpan.org/pod/Alien::Base) system with its experimental FFI interfaces.  This module depends on another toy module 
[Acme::Alien::DontPanic2](https://metacpan.org/pod/Acme::Alien::DontPanic2) which provides the needed libdontpanic library to be able to tell us the `answer` to life, the universe and everything.

# FUNCTIONS

## answer

```perl
my $answer = Acme::Ford::Prefect2::FFI::answer();
```

Returns the answer to life the universe and everything.  Not exported.

# SEE ALSO

- [FFI::Platypus](https://metacpan.org/pod/FFI::Platypus)
- [Alien::Base](https://metacpan.org/pod/Alien::Base)
- [Alien](https://metacpan.org/pod/Alien)

# AUTHOR

Graham Ollis <plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2014-2022 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
