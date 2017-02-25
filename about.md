---
layout: page
title: About
permalink: /about/
---
Let me me introduce myself with the following lines of code.

```c#
/// <summary>
/// My name is Manuel and I currently work as a
/// developer at engelbert strauss. This blog is
/// about those everyday coding issues and the
/// .NET ecosystem in general.
/// </summary>
internal class Program
{
  public int Main(string[] args)
  {
    var out = new Action<string>(Console.WriteLine);

    out("Since I live in the .NET world");
    out("you can mostly expect topics that");
    out("are dealing with our every day's");
    out(".NET issues.");

    // To be honest, you should not expect a high
    // frequency here. I'm not that blog every
    // free minute guy.
    Thread.Sleep(int.MaxValue);
  }
}
```

There is not much left to say. I am part of the [_Git for Windows_](https://github.com/git-for-windows) project team. But to be honest most of the work is done by the well respected [Johannes Schindelin](https://github.com/dscho). Many thanks to Microsoft for supporting that work.

At work I'm the one to whom you would go if you need some crazy _git_ magic done. If somebody would ask me what my favorite git command is, I'd answer `git rebase -i`.
