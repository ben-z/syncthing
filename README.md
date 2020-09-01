我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# Syncthing

[![Latest Build (Official)](https://img.shields.io/jenkins/s/http/build.syncthing.net/syncthing.svg?style=flat-square&label=unix%20build)](http://build.syncthing.net/job/syncthing/lastBuild/)
[![API Documentation](https://img.shields.io/badge/api-Godoc-blue.svg?style=flat-square)](http://godoc.org/github.com/syncthing/syncthing)
[![MPLv2 License](https://img.shields.io/badge/license-MPLv2-blue.svg?style=flat-square)](https://www.mozilla.org/MPL/2.0/)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/88/badge)](https://bestpractices.coreinfrastructure.org/projects/88)

## Goals

Syncthing is a **continous file synchronization program**. It synchronizes
files between two or more computers. We strive to fulfill the goals below.
The goals are listed in order of importance, the most important one being
the first. This is the summary version of the goal list - for more
commentary, see the full [Goals document][13].

Syncthing should be:

1. Safe From Data Loss

   Protecting the user's data is paramount. We take every reasonable
   precaution to avoid corrupting the user's files.

2. Secure Against Attackers

   Again, protecting the user's data is paramount. Regardless of our other
   goals we must never allow the user's data to be susceptible to
   eavesdropping or modification by unauthorized parties.

3. Easy to Use

   Syncthing should be approachable, understandable and inclusive.

4. Automatic

   User interaction should be required only when absolutely necessary.

5. Universally Available

   Syncthing should run on every common computer. We are mindful that the
   latest technology is not always available to any given individual.

6. For Individuals

   Syncthing is primarily about empowering the individual user with safe,
   secure and easy to use file synchronization.

7. Everything Else

   There are many things we care about that don't make it on to the list. It
   is fine to optimize for these values, as long as they are not in conflict
   with the stated goals above.

## Getting Started

Take a look at the [getting started guide][2].

There are a few examples for keeping Syncthing running in the background
on your system in [the etc directory][3]. There are also several [GUI
implementations][11] for Windows, Mac and Linux.

## Vote on features/bugs

We'd like to encourage you to [vote][12] on issues that matter to you.
This helps the team understand what are the biggest pain points for our users, and could potentially influence what is being worked on next.

## Getting in Touch

The first and best point of contact is the [Forum][8]. There is also an IRC
channel, `#syncthing` on [freenode][4] (with a [web client][9]), for talking
directly to developers and users. If you've found something that is clearly a
bug, feel free to report it in the [GitHub issue tracker][10].

## Building

Building Syncthing from source is easy, and there's a [guide][5]
that describes it for both Unix and Windows systems.

## Signed Releases

As of v0.10.15 and onwards release binaries are GPG signed with the key
D26E6ED000654A3E, available from https://syncthing.net/security.html and
most key servers.

There is also a built in automatic upgrade mechanism (disabled in some
distribution channels) which uses a compiled in ECDSA signature. Mac OS
X binaries are also properly code signed.

## Documentation

Please see the [Syncthing documentation site][6].

All code is licensed under the [MPLv2 License][7].

[1]: https://docs.syncthing.net/specs/bep-v1.html
[2]: https://docs.syncthing.net/intro/getting-started.html
[3]: https://github.com/syncthing/syncthing/blob/master/etc
[4]: http://www.freenode.net/irc_servers.shtml
[5]: https://docs.syncthing.net/dev/building.html
[6]: https://docs.syncthing.net/
[7]: https://github.com/syncthing/syncthing/blob/master/LICENSE
[8]: https://forum.syncthing.net/
[9]: https://kiwiirc.com/client/irc.freenode.net/#syncthing
[10]: https://github.com/syncthing/syncthing/issues
[11]: https://docs.syncthing.net/users/contrib.html#gui-wrappers
[12]: https://www.bountysource.com/teams/syncthing/issues
[13]: https://github.com/syncthing/syncthing/blob/master/GOALS.md
