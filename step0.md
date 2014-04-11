---
layout: default
title: Getting started
prev: /
next: step1.html
progress: 3%
---

You'll be completing this week's lab *remotely* on the computer next to you. It's fine if someone else is sitting there. You're working on a machine just a few feet away, but the same commands will work to connect a computer anywhere in the world as long as you have an account.

Take a look at the computer next to you, and find its nametag. If Jane Smith (username `smith22j`) is sitting next to `cslab-31.cs`, she can connect to that machine with the `ssh` command:

{% highlight sh %}
$ ssh smith22j@cslab-31.cs.mtholyoke.edu
{% endhighlight %}  

The name `ssh` is short for **s**ecure **sh**ell. This gives you access to another machine through a secure (encrypted) connection. The `$` character is called a "prompt." The terminal prints this out when it is ready to accept a command. The command won't work if you type the `$` in!

Go ahead and run the above command (with *your* username and neighboring machine). You'll get an ominous-looking warning the first time you connect to a machine. Type in `yes` to continue with the connection:

{% highlight sh %}
The authenticity of host 'cslab-31.cs.mtholyoke.edu (138.110.92.101)' can't be established.
RSA key fingerprint is 66:35:ae:35:e2:68:62:e7:cd:2c:8a:ae:9a:11:b8:bd.
Are you sure you want to continue connecting (yes/no)? yes
{% endhighlight %}

Next, you'll be asked for your password. When you're typing, *no characters will show up*. Don't worry, it's supposed to work this way!

{% highlight sh %}
Warning: Permanently added 'cslab-30.cs.mtholyoke.edu,138.110.92.100' (RSA) to the list of known hosts.
Password:
{% endhighlight %}

Once you're connected, your terminal will look just like it did when you opened it. Except, this time you're running commands on the machine you connected to instead of the local machine.

Don't believe me? Turn up the volume on the machine next to you and run the command below. Fill in `[your name here]`, and remember not to type in the `$`.

{% highlight sh %}
$ say [your name here] is running commands on this machine.
{% endhighlight %}
