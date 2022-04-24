# Hackathon Resources

## Useful Links

- [Mayhem Free](https://mayhem.forallsecure.com/)
- [Mayhem Hacking Community](https://community.forallsecure.com/)
- [Mayhem Heroes GitHub Org](https://github.com/mayhemheroes)
- [Submission Form](https://dydbdnwi0qu.typeform.com/to/l6MK0WJp)

## Exercises

- [lighttpd exercise](lighttpd-example.md)
- [Docker + Mayhem Exercise](docker-intro.md)
- [CMake Exercise](cmake-libfuzzer-exercise.md#cmake-exercise)
- [libFuzzer Exercise](cmake-libfuzzer-exercise.md#libfuzzer-exercise)
- [Mayhem GitHub Action Exercise](gh-actions.md)

## Mayhem Heroes Workflow

1. Select a repository for integration.

    See the [Target Checklist](https://github.com/mayhemheroes/hero-resources#target-checklist).

2. Create a fork of the repo you want to integrate.

3. Integrate Mayhem into your Fork.

4. Submit this form: https://dydbdnwi0qu.typeform.com/to/l6MK0WJp

5. Once ForAllSecure validates your target and elligiblity, you'll be asked to submit a pull request to the repository under github.com/mayhemheroes. If requested during the review, make changes.

6. Once your changes have been merged, you'll be eligible for $750!

7. ForAllSecure will turn on automatic updates to the repository. At this point you should begin monitoring the repository to ensure that the Mayhem integration still works.

8. After 30 days, you'll be eligible for an additional $250!

## Target Checklist

Targets that you wish to get paid for must meet the following criteria:

* Is a public repository on github.com.  Private repositories are currently not qualified.

* Has 100 or more stars.

* All code is open source and available in source code format.

    - Code is considered Open Source if the entire code base is licensed under one (or more) of the recognized Open Source Initiative Licenses listed at https://opensource.org/licenses/alphabetical. 

* Mayhem is not already integrated. You can find a list of integrated repositories at https://github.com/mayhemheroes.

* The project is not part of oss-fuzz.

If in doubt, ask in the [Mayhem Hacking Community](https://community.forallsecure.com/).

## Troubleshooting Checklist

There are several small configuration steps that you'll need to take on your repo in order to properly integrate a repo with Mayhem. They are easy to miss, so here is a list for your reference:

* Package has public visibility.

