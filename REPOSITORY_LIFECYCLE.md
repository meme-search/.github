# Repository lifecycle

Every Meme Search repository should state its lifecycle in its README. The
lifecycle communicates expectations; it is not a guarantee of future work.

## Supported

Maintainers treat regressions and security issues as project responsibilities.
The repository has documented releases, verification, and an identified
maintainer.

## Experimental

The project is being evaluated and may change or stop without a compatibility
period. It must not imply support from the core application.

## Community-maintained

The project has an identified community maintainer. The organization provides a
home and shared standards, while maintenance depends on that contributor's
continued participation.

## Archived

The repository is read-only and unsupported. Its README should identify a
replacement or migration path when one exists.

## Creating a repository

A new repository is appropriate when the work has:

- a distinct release or distribution channel;
- permissions, dependencies, or security boundaries different from the core;
- an identified maintainer and a realistic verification path; and
- enough implementation to avoid an empty placeholder repository.

An extension, native app, deployment package, or localization effort should stay
in an issue, discussion, or prototype branch until those conditions are met.

## Changing lifecycle

Lifecycle changes should be documented in the README and announced to active
users. Moving a supported project to archived status requires a migration or
deprecation note when users would otherwise be stranded.
