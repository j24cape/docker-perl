# j24cape/perl

Docker images with Perl (including some CLIs) installed via Perl-Build. The latest tag is Perl 5.22.2 installed on Debian GNU/Linux 8.x (jessie).

```
docker run -it --rm j24cape/perl
docker run -it --rm j24cape/perl cpanm --version
docker run -it --rm j24cape/perl cpan-outdated --help
```

[![Travis CI](https://img.shields.io/travis/j24cape/docker-perl.svg)](https://travis-ci.org/j24cape/docker-perl/branches)
