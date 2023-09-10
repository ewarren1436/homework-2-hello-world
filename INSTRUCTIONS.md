
# Assembly - Hello World!

This assignment is simple. I only want you to write a very basic program in pure assembly.

## Setting up your program

Start by entering the following command:

```console
$ make help
```

You should see a help menu explaining what recipes are available in this particular Makefile. Try the following command to build and run your program:

```console
$ make run
```

You should see a cryptic message about a missing `main.asm` file. Go ahead and make that file now, and put the following features inside:

* The basic structure of an assembly program, including:

    * A data section for your program

    * The following string inside your program's data section: *Hello, my name is Gibsen Montgomery Gibson*, with your name replacing Gibsen's name.

    * A text section for your program

    * A global _start label as the entry point of your program

    * The use of a system call to print the string above

    * The use of a system call to properly exit the program, with an exit code of `0`

Try the `make run` command again. Your program should be able to run by now, and it's definitely time to `git commit` your changes to and `git push` your code to the remote server, because you've "made significant progress". In fact, you probably should have made a `git commit` several times while working on your program. Did you?

When your program is finished, it should output the following string:

```text
Hello, my name is Gibsen Montgomery Gibson
```

(again, with Gibsen's name replaced by your own)

## Checking in Gradescope

Let's check your score in Gradescope:

1. Make sure your code has been pushed to Github.

2. Go to Gradescope, find the entry for our class, and find the entry for this assignment.

3. Submit your work using the "Github" method. Select your Github repository for this assignment.

4. Wait a few minutes for Gradescope to do its grade-scoping.

If you're lucky, you'll see you've earned some or all points in the program compilation and execution category. If you're unlucky, there are only errors. Carefully read every line of Gradescope's autograder output and look for clues regarding what went wrong, or what you have to do next.

You might see messages complaining that your program didn't compile. Even better, you may instead see messages that indicate you have more to do.

## Getting More Points

You'll probably see a complaint that you haven't created your *README.md* file yet. Go ahead and complete your *README.md* file now, then commit+push the changes with git.

## Getting Even More Points

Remember that although the output messages from Gradescope are cluttered and messy, they can contain valuable information for improving your grade. Further, the art of programming in general often involves staring at huge disgusting blobs of data and debugging output until it makes sense. It's something we all must practice.

Earning the rest of your points will be fairly straightforward, but use Gradescope's output if you get stuck or confused. The basic premise here is you'll want to do the following:

1. Write some code, doing commits and pushes with git along the way

2. Check your grade via Gradescope

3. Go back to step 1 if you don't yet have a perfect score. Otherwise, you're done.

## Conclusion

At this point, you might have earned a perfect score. If not, don't despair! Talk with other students in our discussion forums, talk with other students in our Discord chat room, and email the professor if you're still stuck at the end of the day. If enough students have the same issue, and it doesn't seem to be covered by lecture or our textbook, I may create another tutorial video to help!





