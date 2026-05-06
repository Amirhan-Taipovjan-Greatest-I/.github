# About this Repo.
This is "the Repo of My Profile".

It contains [My Profile's Info](https://github.com/Amirhan-Taipovjan-Greatest-I/.github/blob/main/profile/README.md) and also preserves the Role of a "Tracker" of any of My Translation Progress/Process together with [the GitHub Project](https://github.com/users/Amirhan-Taipovjan-Greatest-I/projects/3). Due to GitHub's Limitations, it also uses [the Custom Workflow](https://github.com/Amirhan-Taipovjan-Greatest-I/.github/blob/main/.github/workflows/issue_syncing.yml) Written by "the Dark Side" and Idea-Leaded by Me.

# Issues.

Issues of this Repo are mostly used as for Idea-Suggesting and Tracking Translations and their Progress.

There are two working Issue Templates:
- Translation Proposal (You want Me to translate a never-before-translated-into-Tatar Product. [Its Issue Template File](https://github.com/Amirhan-Taipovjan-Greatest-I/.github/blob/main/.github/ISSUE_TEMPLATE/translation-proposal-.md));
- Translation Support (You want Me to translate a once-translated-into-Tatar-before Product. [Its Issue Template File](https://github.com/Amirhan-Taipovjan-Greatest-I/.github/blob/main/.github/ISSUE_TEMPLATE/translation-support-.md));

Also there are two {In,Ex}ternal Links available from the Issue Template Chooser (provided by [the Special Config File](https://github.com/Amirhan-Taipovjan-Greatest-I/.github/blob/main/.github/ISSUE_TEMPLATE/config.yml)):
- [This Repo's Discussions](https://github.com/Amirhan-Taipovjan-Greatest-I/.github/discussions);
- [My Card Site](https://amirhan-taipovjan-greatest-i.github.io/main%23en) (in Case if You want to know how to contact Me).

# Discussions.

Discussions of this Repo should be treated like a Forum Platform:
- Discuss Translation Ideas, My Progress, Myself too;
- Suggest and Discuss Ideas for this Repo;
- Read, Comment Announcements of Mine;

# GitHub Actions Workflow.

Has the Special Workflow that helps auto-close Issues when linked external PRs are being closed. Also auto-updates their Project Status by My Scheme:
0. a. Issue with a Draft PR, but with "Backlog"/"Ready"/"In Process" Status -> Stays there.
   b. Issue with a Draft PR, but with "In Review" Status -> Updates to "In Process".
1. a. Issue with a Multiple PRs, but at least one of them is a Draft (all others are Opened or Merged) -> Moves to "In Process" if is in "In Review".
   b. Issue with a Multiple PRs, but at least one of them is Opened (all others are Merged) -> Moves to "In Review" if isn't there.
2. Issue with a Merged PR(s only) -> Auto-Closes itself, and thus moves to "Done" by Default GitHub Project Workflow.

These Conditions are being checked once in an Hour (full Issue List Checking) or when an Issue changes or Comments are being sent/edited in there (runs only for that mentioned Issue).
