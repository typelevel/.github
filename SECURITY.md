# Security Policy

## Reporting a Vulnerability

[Responsible disclosure](https://en.wikipedia.org/wiki/Responsible_disclosure) enhances security for the entire community.

### Keybase

We prefer [keybase](https://keybase.io) as the vehicle for reporting security issues as that gives us an encrypted forum to discuss, analyze, and remediate the threat before an exploit is published.
Please request to join the [typelevelsec](https://keybase.io/team/typelevelsec) team, and we will create a subteam to discuss the issue with you.

### E-mail

E-mail is not encrypted, but is preferred to a zero-day!
If you cannot use Keybase, please email a member of the Typelevel Security Team as listed below.

## Procedure

If the issue is deemed a vulnerability, we will release a patch version of our software
and make sure that finds its way to Maven Central before we push the patch to GitHub.
After the patch is available on Maven Central, we will also provide a security advisory through GitHub.
As with every release, the source jars are published to Maven Central at the same time as the binaries.

## Scala Steward

We strongly recommend users of our libraries to use [Scala Steward](https://github.com/fthomas/scala-steward) or something similar to 
automatically receive updates.

## Typelevel Security Team

|name | github | keybase | email |
|-----|--------|---------|---------|
| Ross A. Baker | @rossabaker | @rossabaker | ross@rossabaker.com |
