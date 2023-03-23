---
layout: post
title: Pull Request Checklist
date: 2023-03-23 09:46 -0400
---

## TL;DR
- [ ] Does your code work, and the tests pass?
- [ ] Do you have a good description?
- [ ] Do you have a appropriate title with the correct prefix?
- [ ] Did you use the proper media type?
- [ ] Did you add a label and a project?
- [ ] Did you double check your code / comments?

---

## Pull Request Checklist
This post is mainly for myself, to create a comprehensive quality checklist of things include/exclude from a PR. 


1. Make sure the Patch compiles, test pass, and it does the thing it's suppose to. It's really easy to use the [build bot](https://projects.blender.org/infrastructure/blender-bot/src/branch/main/README.md) to kick things off. Comment `@blender-bot package` on a PR to start builds for all supported platforms.

2. Look over files changes, and ensure it's the changes you want. Double check all comments for spelling errors, and proper grammar.

3. Ensure the proper title prefix is used. Use the module prefix for features (I.e, `Animation:` ). Use `Fix #00000` for bug fixes, the `#00000` references a specific [issue](https://projects.blender.org/blender/blender/issues) number, and will automatically close the issue when the PR is closed. Use `Refactor:` or `Cleanup:` when either refactoring or cleaning up the code. 

4. Add in a description of the problem that is addressed, a description of the proposed solution, and motivation.

5. Add the appropriate Label and Project to the PR.

6. Don't use GIF's, use MP4's instead. This allows for vide scrubbing, pausing, etc. Ensure there is enough verbal description for the change to be indexed by a search engine.

7. Post PR's out in the open. Keep things public.


--- 
**References**
* https://wiki.blender.org/wiki/Tools/Pull_Requests
* https://wiki.blender.org/wiki/Modules/Animation-Rigging/Code_Review