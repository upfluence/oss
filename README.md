# OSS (117)

![Mr Bonisseur de La Bath](https://i.imgflip.com/6orln3.jpg)

##  Deprecated and Archived

After discussions with the Upfluence frontend team, this projects has been deprecated and its files have been moved into
the **[upfluence/oss-components](https://github.com/upfluence/oss-components)** project (Pull Request: https://github.com/upfluence/oss-components/pull/200).

There reasons are that we have noticed that the split between this package (holding agnostic, Less CSS + assets only code)
and the @upfluence/oss-components package (holding more Ember-specific code) is not viable anymore and brings some pain
point that are a bit annoying:
- having to open PRs in two projects for the same tasks
- Yarn links w/ @upfluence/oss that are not always straighforward (even more if you link this package to another running app)
- Documentation being split between two packages
