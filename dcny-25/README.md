## Title
From Startup to Scale: The Engineering Playbook for Growing Android Teams

## Abstract
Growing an Android team from a handful of developers to 50+ without imploding requires more than just good intentions—it demands architecture, automation, and guardrails that make the right decisions inevitable. 

At Square, we’ve built a mobile codebase that enables teams to collaborate efficiently, share components like Lego blocks, and avoid stepping on each other’s toes—even in a 2M+ line monorepo with 100 Android ICs actively contributing everyday.

But you don’t need to be at Square’s scale to benefit. If your team is 10+ and growing, the challenges of coordination, consistency, and performance creep up fast. This talk will equip you with actionable strategies you can start implementing today to keep your engineering team productive over time.

In this talk, you’ll learn how we:
* Use a consistent UI framework to enforce strict yet flexible contracts, making UI and business logic highly composable.
* Slash build times by modularizing code, separating interfaces from implementations, and structuring dependencies to minimize build times. 
* Ensure consistency at scale with custom lint rules and CI checks that enforce best practices. You’ll see real-world CI checks from Square that you can apply to your own projects—preventing dependency misuse, enforcing modularization, and maintaining architecture standards—to help engineers "fall into the pit of success" without constant oversight.

These aren’t just theories—they’re battle-tested strategies that have helped us maintain velocity without sacrificing quality. Of course, it’s not always smooth sailing.  I’ll share the challenges we’ve faced, the landmines we’ve hit, and how we’ve had to pivot along the way—so you can avoid the same pitfalls.

## Artifacts
* https://nyc.droidcon.com/speakers/eric-maxwell
* Presentation in PDF form [DroidCon25-PlaybookBuildingTeamsCodebase-Sharable.pdf](DroidCon25-PlaybookBuildingTeamsCodebase-Sharable.pdf)

![photo2](https://github.com/user-attachments/assets/c54fd7bc-ad57-407d-b8d1-a5161b7b01b7)
![photo1](https://github.com/user-attachments/assets/3d28daee-bd43-4451-8843-b5095409739d)
