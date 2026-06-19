# standard-issue

The standard-issue template is the point of origin for new repositories within Fish Slapped Mayhem. It exists to ensure that new projects begin in approximately the same state, on the reasonable assumption that some state is preferable to none.

## What you get

A repository created from `standard-issue` arrives with the following:

- A `.devcontainer/` configuration, suitable for opening in the editor of your choice (provided that choice is one of the two or three editors anyone actually uses). The configuration references a base image maintained separately, which means the image may be updated without disturbing this template, and this template may be updated without disturbing the image. Whether this separation will produce the harmony its designer envisioned remains to be seen.
- A `/docs/` directory, pre-populated with the structure that documentation tends to want by the third week of a project. It is easier to delete sections that turn out to be unnecessary than to invent them later under deadline.

## How to use it

Use GitHub's "Use this template" button. The resulting repository will be a clean copy, with no commit history from this one, which is generally what you want.

After cloning, the recommended sequence is:

1. Replace this README with one describing the actual project.
2. Open the repository in your devcontainer of choice and confirm it builds.
3. Run the bootstrap script to pull current Claude configuration.
4. Begin the work.

The order is suggested rather than required. Reasonable people may proceed in a different order, and the template will not object.

## What this template does not include

A license file is not provided. License decisions are made per artifact, at the moment of publication, and forcing a default here would defeat that principle. New repositories are expected to add a license (or deliberately omit one) when their public status is settled.

A `.github/` directory with workflows, issue templates, or similar scaffolding is also not provided. These vary too much between project types to have a sensible default. They will be added to individual repositories as the work warrants them.

## Maintenance

This template is updated as patterns settle. Updates to the template do not propagate to repositories already created from it; this is a property of GitHub's template mechanism rather than a design choice, and it is, on balance, the correct behavior. Repositories that wish to adopt template improvements may do so manually, at their leisure.
