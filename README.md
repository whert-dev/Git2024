# ProgSoc Beginners' Git 2024

> Originally run 6pm 27th March 2024.

This is the repository for the *Beginners' Git* workshop.

If your coming from the *Live Page*, see the [`guide.md`](./guide.md) page; and the source code <https://github.com/ProgSoc/Git2024>

## Instructions

### Group Session

* Pick 2+ group members (nominate 1 person as Owner),
* Get the Owner to fork this repository,
* Add your teammates [as 'Collaborators'](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository),
* Create your own individual branches, with a feature name like `oli/event-idea`:
    * Fill out a new event or project idea in [`guide.md`](./guide.md), with your idea for a event ProgSoc could host,
    * Open a Pull Request, and get the changes merged into the `main` branch.
* Create your own individual fix branches, with similar feature names to before `oli/fix-dates`:
    * Each change the date format to a different version (one person does `27/4/2024`, another spells out the month fully `27 March 2024`, another internationally `2024-03-27`, etc)
    * Open Pull Requests, and get the changes merged into the `main` branch.
    * You'll encounter a merge-conflict, and need to decide how to resolve it.

### Live Collaboration Session

* Work on your teams' sections, and submit Pull Requests to the original repository to be merged into the `live` branch.

## Branches

It includes the `main` branch as a finished state example of the files at the end of the group session.

It also includes the changes submitted during the live website collaboration session, available in the `live` branch.

### Short-Circuit

If you want to jump in at a specific step of the workshop, there are available branches representing the repository state at that point:

* Local Development
    * `local/step-0`: Empty repository, after `git init`
    * `local/step-1`: Imported files from upstream
    * `local/step-2`: Changes made in new branch
    * `local/step-3`: Merged changes into main
* Group Development
    * `group/step-0`: Forked/cloned repository
    * `group/step-1a`: Change to full dates
    * `group/step-1b`: Change to international dates
    * `group/step-2`: State after merge conflict
    * `group/step-3`: State after resolving, and running `git commit`
