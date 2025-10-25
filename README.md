# git-for-newbies

Complete the following tasks:

There are three branches:
- main
- feature-A
- feature-B

A and B are stacked.
```text
            ┌─────────feature-B
            │
            6──7──8
            │
        ┌─────────────feature-A
        │
        4──5
        │
  ┌───────────────────main
  │
  1──2──3
```

You will:

1. Create your own versions of these three branches (e.x. alex-main, alex-feature-A, alex-feature-B)
2. Create two Pull Requests. One to merge your feature-A into your main, and another to merge your feature-B into your feature-A
3. Squash and merge your feature-A into your main
4. Restack your feature-B on top of your main
5. Squash and merge your feature-B on top of your feature-A

NOTE: If you're following the proper rebase procedure, at no point should you encounter merge conflicts!

When you squash and merge, make sure you leave the default commit messages by Github, it is a way of verifying whether you did everything correctly.

