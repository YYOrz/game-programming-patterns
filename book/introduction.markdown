^title Introduction

In fifth grade, my friends and I were given access to a little unused
classroom housing a couple of very beat-up TRS-80s. Hoping to inspire us, a
teacher found a printout of some simple BASIC programs for us to tinker with.

The audio cassette drives on the computers were broken, so any time we wanted to
run some code, we'd have to carefully type it in from scratch. This led us
to prefer programs that were only a few lines long:

由于电脑上的磁盘驱动已将损坏，所以每次我们想运行一些代码，都必须非常小心地从scratch上输入。这使得我们乐于仅用少量的行数编写程序。

<span name="radical"></span>

    10 PRINT "BOBBY IS RADICAL!!!"
    20 GOTO 10

<aside name="radical">

Maybe if the computer prints it enough times, it will magically become true.

可能假如程序输出足够的次数，它就能够魔幻般地成为现实。

</aside>

Even so, the process was fraught with peril. We didn't know *how* to program,
so a tiny syntax error was impenetrable to us. If the program didn't work,
which was often, we started over from the beginning.

即便如此，代码运行时充满着危险。我们不懂得如何编程，导致少量的语法错误对我们来说都是无法解决的。如果程序无法工作，我们就需要从新开始，这还是时常发生的情况。

At the back of the stack of pages was a real monster: a program that took up
several dense pages of code. It took a while before we worked up the courage
to even try it, but it was irresistible -- the title above the listing was
"Tunnels and Trolls". We had no idea what it did, but it sounded like a game,
and what could be cooler than a computer game that you programmed yourself?

在成堆的页面背后是一个真实的怪物：一个有几十页代码组成的程序。曾有段时间它被放置不管，直到我们重拾勇气并尝试它。但是标题上方的列表是“隧道与巨怪”是极其诱人的。我们对它是如何做到的没有任何概念，但是这听上去就像一个游戏。而且，还有什么比自己编写一个电脑游戏更酷的事情？

We never did get it running, and after a year, we moved out of that classroom.
(Much later when I actually knew a bit of BASIC, I realized that it was just a
character generator for the table-top game and not a game in itself.) But the
die was cast -- from there on out, I wanted to be a game programmer.

我们从未使其运行过，且在一年后我们搬出了那个课室。（在后来我了解了些许BASIC后，意识到它仅是一个游戏的角色生成器，本身并不是游戏）但是木已成舟，从此之后我励志成为一个游戏开发者。

When I was in my teens, my family got a Macintosh with QuickBASIC and later
THINK C. I spent almost all of my <span name="snakes">summer vacations</span>
hacking together games. Learning on my own was slow and painful. I'd get
something up and running easily -- maybe a map screen or a little puzzle --
but as the program grew, it got harder and harder.

在我的青年时期，家里购买了内置了QuickBASIC和最新版的THINK C的麦金塔电脑。我几乎花费了我所有的夏天假期去研究游戏开发。仅靠个人的学习是缓慢且痛苦的。我可以简单地编写并运行一些程序，例如地图屏幕或一些小难题。但是对于编程能力成长来说，正变得越来越困难。

<aside name="snakes">

Many of my summers were also spent catching snakes and turtles in the swamps
of southern Louisiana. If it wasn't so blisteringly hot outside, there's a
good chance this would be a herpetology book instead of a programming one.

</aside>

At first, the challenge was just getting something working. Then, it became
figuring out how to write programs bigger than what would fit in my head. Instead
of just reading about "How to Program in C++", I started trying to find books
about how to *organize* programs.

在一开始，挑战仅是编写能正常工作的代码。然后，变成如何编写出符合我想象中的更大型的程序。在阅读了“How to Program in C++”后，我开始尝试寻找书籍去学习如何优化程序。

Fast-forward several years, and a <span name="friend">friend</span> hands me a
book: *Design Patterns: Elements of Reusable Object-Oriented Software*.
Finally! The book I'd been looking for since I was a teenager. I read it cover
to cover in one sitting. I still struggled with my own programs, but it was
such a relief to see that other people struggled too and came up with
solutions. I felt like I finally had a couple of *tools* to use instead of
just my bare hands.

匆匆数年后，一个朋友想我推荐了一本书：《设计模式：复用的面向对象软件的元素》。最终！我找到了青年时期想找的书，并反复阅读它。我依旧在个人程序编写中挣扎，而它向我呈现了其他人也深陷其中并寻获解决方案。我感觉到我终于找到了工具去替代我的双手。

<aside name="friend">

This was the first time we'd met, and five minutes after being introduced, I
sat down on his couch and spent the next few hours completely ignoring him and
reading. I'd like to think my social skills have improved at least a little
since then.

这发生在我们初次见面，在五分钟的简短介绍后，我在他的长椅上坐下来后就开始阅读且将他忽略了几个小时。从那之后，我认为我应该需要提高下个人的社交能力。

</aside>

In 2001, I landed my dream job: software engineer at Electronic Arts. I
couldn't wait to get a look at some real games and see how the pros put them
together. What was the architecture like for an enormous game like Madden
Football? How did the different systems interact? How did they get a single
codebase to run on multiple platforms?

2001年我获得了梦想的工作：成为EA的软件工程师。我迫不及待地想看下真实的游戏且了解程序是如何将他们组合到一起？类似Madden Football这样的巨大游戏的架构是如何的？如何使得不同的系统能够相互交互？怎么实现一份代码能够在多个平台上运行？

Cracking open the source code was a humbling and surprising experience. There
was brilliant code in graphics, AI, animation, and visual effects. We had
people who knew how to squeeze every last cycle out of a CPU and put it to
good use. Stuff I didn't even know was *possible*, these people did before
lunch.

研究源代码是一项震撼人心且充满惊喜的过程，包含了大量关于图形，AI，动画和虚拟特效的代码。我们拥有懂得如何挤进CPU每一次循环周期且保证能够良好工作的人才。他们可能是我未曾认识的职员，而且他们在午餐前就能完成工作。（。。。）

But the *architecture* this brilliant code hung from was often an
afterthought. They were so focused on *features* that organization went overlooked. Coupling was rife between modules.
New features were often bolted onto the codebase wherever they could be made
to fit. To my disillusioned eyes, it looked like many programmers, if they ever
cracked open *Design Patterns* at all, never got past <a class="pattern"
href="singleton.html">Singleton</a>.

但是架构上拥有如此巨量的代码量往往是一个意料之外的事情。他们专注于特性的实现而忽略了架构的组织。模块间的耦合度非常高。新的特性往往迅速地提交进代码库中，尽管他们应该将其优化。在我看来，这就像许多编程人员，假如他们能够考虑到设计模式，那么就不会如此依赖<a class="pattern" href="singleton.html">单例</a>。

Of course, it wasn't really that bad. I'd imagined game programmers sitting in
some ivory tower covered in whiteboards, calmly discussing architectural
minutiae for weeks on end. The reality was that the code I was looking at was
written by people working to meet intense deadlines. They did the best they
could, and, as I gradually realized, their best was often very good. The more
time I spent working on game code, the more bits of brilliance I found hiding
under the surface.

当然，这并没有想象中的那么差。我曾想象到游戏开发者坐在覆盖着白色外墙的象牙塔中，持续好几个星期冷静地讨论架构细节。在现实中我看到的代码都是程序在迫近deadline的时候加紧工作完成的。他们尽其所能完成，我也由衷地意识到，他们的能做到的最好亦是非常棒的。越多的时间花费在游戏代码上，我越发现更多隐藏在其中的细小亮点。

Unfortunately, "hiding" was often a good description. There were gems buried
in the code, but many people walked right over them. I watched coworkers
struggle to reinvent good solutions when examples of exactly what they needed
were nestled in the same codebase they were standing on.

不幸的是，“隐藏”是一种委婉的描述。有宝藏隐藏在代码中，但是大多数的人都跟它们擦肩而过。我曾见过协同的开发者被纠结于一份好的重构设计方案，但未能发现了满足他们需求的实现样例已经存在于当前正开发的代码库中。

That problem is what this book aims to solve. I dug up and polished the best
patterns I've found in games, and presented them here so that we can spend our
time inventing new things instead of *re*-inventing them.

这是本书所希望解决的问题。我整理归纳了游戏中最好的模式，并将它们放到书中，使得我们能够节省自己的时间去重新设计。

## What's in Store

There are already dozens of game programming books out there. Why write
another?

已经有大量的游戏编程书籍，为什么还要另写一本？

Most game programming books I've seen fall into one of two categories:

在我看过的大多数的游戏编程书籍，往往可以归为以下两种类型中的一种：

* **Domain-specific books.** These narrowly-focused books give you a deep dive
  on some specific aspect of game development. They'll teach you about 3D
  graphics, real-time rendering, physics simulation, artificial intelligence,
  or audio. These are the areas that many game programmers specialize in as
  their careers progress.

* **特定领域书籍** 这些专业书籍对游戏开发环境进行深入挖掘或者具体阐述某些特定方向。它们能够传授你关于3D图像，实时渲染，物理模拟，人工智能及音效方面的只是。这些属于游戏开发者职业发展中众多的特定领域内容。

* **Whole-engine books.** In contrast, these try to span all of the different
  parts of an entire game engine. They are oriented towards building a
  complete engine suited to some specific genre of game, usually a 3D first-person shooter.

* **全引擎书籍.** 相对来说，这类书籍尝试跨越游戏引擎的不同部分。它们的目标是组建一个适配特定类型游戏的完整引擎，通常是3D第一人称射击游戏。

I like both of these kinds of books, but I think they leave some gaps. Books
specific to a domain rarely tell you how that chunk of code interacts with the
rest of the game. You may be a wizard at physics and rendering, but do you
know how to tie them together gracefully?

这两类书籍我都喜欢，但是我认为它们之间存在一些间隙。特定领域书籍几乎没能够告诉一款游戏中的大量代码是如何交织工作的。你可能精通物理和渲染，但是你又如何能够优雅地把它们捆绑到一起？

The second category covers that, but I often find whole-engine books to be too monolithic and too
genre-specific. Especially with the rise of mobile and casual gaming, we're in
a period where lots of different genres of games are being created. We aren't
all just cloning Quake anymore. Books that walk you through a single engine
aren't helpful when *your* game doesn't fit that mold.

第二种类型书籍能够覆盖到这方面内容，但我总觉得全引擎书籍太片面和太风格特意。特别随着移动休闲游戏数量不断上升，我们正处于大量不同类型游戏涌现的时期。我们不能再仅仅是克隆Quake。当你的游戏不再使用那种类型时，一本传授一款单一引擎的书籍就显得一无是处。

Instead, what I'm trying to do here is more <span name="carte">*à la
carte*</span>. Each of the chapters in this book is an independent idea that
you can apply to your code. This way, you can mix and match them in a way that
works best for the game *you* want to make.

因此，我在这里想做的事是更<span name="carte">*à la carte*</span>。书中的每一个章节都是一个可以引用到代码中的独立概念。通过这种方式，你可以依据你希望的方式去将它们揉合匹配到游戏中。

<aside name="carte">

Another example of this *à la carte* style is the widely beloved [*Game
Programming Gems*](http://www.satori.org/game-programming-gems/) series.

另一个关于 *à la carte* 风格的介绍例子是 [*Game
Programming Gems*](http://www.satori.org/game-programming-gems/) 系列。

</aside>

## How it Relates to Design Patterns

Any programming book with <span name="alexander">"Patterns"</span> in its name
clearly bears a relationship to the classic *Design Patterns: Elements of
Reusable Object-Oriented Software* by Erich Gamma, Richard Helm, Ralph Johnson,
and John Vlissides (ominously called the "Gang of Four").

任何一本名称中包含“模式”的编程书籍都与由Erich Gamma, Richard Helm, Ralph Johnson,
和John Vlissides编写的经典书籍 *《设计模式：可复用面向对象软件》* 相关。

<aside name="alexander">

*Design Patterns* itself was in turn inspired by a previous book. The idea of
crafting a language of patterns to describe open-ended solutions to problems
comes from [*A Pattern
Language*](http://en.wikipedia.org/wiki/A_Pattern_Language), by Christopher
Alexander (along with Sarah Ishikawa and Murray Silverstein).

*设计模式* 是受到过去一本书籍所启发。概念源自由Christopher
Alexander（Sarah Ishikawa和Murray Silverstein协同）在[*A Pattern
Language*](http://en.wikipedia.org/wiki/A_Pattern_Language)中提及的关于设计一种模式语言通过开放式解决方案来解决问题。

Their book was about architecture (like *real* architecture with buildings and
walls and stuff), but they hoped others would use the same structure to
describe solutions in other fields. *Design Patterns* is the Gang of Four's
attempt to do that for software.

书籍是关于架构的，但是他们也希望其它人使用相同的结构在不同的领域中建立解决方案。*设计模式* 是编者四人组为软件开发所编著的。

</aside>

By calling this book "Game Programming Patterns", I'm not trying to imply that
the Gang of Four's book is <span name="nongames">inapplicable</span> to games.
On the contrary: the [Design Patterns Revisited](design-patterns-revisited.html)
section of this book covers many of the patterns from *Design
Patterns*, but with an emphasis on how they can be applied to game
programming.

通过书籍命名为“游戏编程模式”，我不会尝试解释《设计模式》对游戏开发是不适用的。相反地，在本书[Design Patterns Revisited](design-patterns-revisited.html)章节中大量引用了 *设计模式* 中的内容，但重点内容是如何将它们应用到游戏开发当中。

Conversely, I think this book is applicable to non-game software too. I could
just as well have called this book *More Design Patterns*, but I think games
make for more engaging examples. Do you really want to read yet another book
about employee records and bank accounts?

反过来说，我认为本书也适用于非游戏软件开发。我更倾向与将该书成为 *更多的设计模式*。但是我认为游戏制作是一个极其吸引人的例子。难道你真的希望阅读另一本关于雇员管理或者银行账户系统的书籍？

That being said, while the patterns introduced here are useful in other
software, I think they're particularly well-suited to engineering challenges
commonly encountered in games:

像之前说过的，这里介绍的设计模式对其他软件开发也是有用的，我认为以下几点是尤其非常适用于游戏开发中常见的工程开发挑战：

*   Time and sequencing are often a core part of a game's architecture. Things
    must happen in the right order and at the right time.

*   时间和时序通常是游戏架构的核心部分。事务应当在正确的时序和在正确的时间上执行。

*   Development cycles are highly compressed, and a number of programmers need
    to be able to rapidly build and iterate on a rich set of different
    behavior without stepping on each other's toes or leaving footprints all
    over the codebase.

*   开发周期是被极度压缩的，且大量的编程人员要求掌握在缺少他人指导和基于公用的代码库资源情况下，对大量不同的行为需求进行快速编程和迭代的能力。

*   After all of this behavior is defined, it starts interacting. Monsters
    bite the hero, potions are mixed together, and bombs blast enemies and
    friends alike. Those interactions must happen without the codebase turning
    into an intertwined hairball.

*   当这些行为都被定义后，游戏就开始互动。怪物攻击英雄，药水混杂到一起，炸弹爆炸的敌人和朋友的一致好评。这些交互行为脱离了代码库就必然像毛线球一样相互杂乱交织在一起。

*   And, finally, performance is critical in games. Game developers are in a
    constant race to see who can squeeze the most out of their platform.
    Tricks for shaving off cycles can mean the difference between an A-rated
    game and millions of sales or dropped frames and angry reviewers.

*   最后，表现在游戏中是至关重要的。游戏开发者通过固定的途径去观察谁可以充分利用他们的平台。对游戏表现的帧数削减的优化技巧，是一款百万销售的A级游戏跟一款丢帧且受玩家恶评的游戏之间的不同。

## How to Read the Book

*Game Programming Patterns* is divided into three broad sections. The first
introduces and frames the book. It's the chapter you're reading now along with
the [next one](architecture-performance-and-games.html).

*游戏设计模式* 分为三个主要模块。第一部分介绍本书，便是你当前正在阅读的章节和[下一章节](architecture-performance-and-games.html)

The second section, [Design Patterns Revisited](design-patterns-revisited.html),
goes through a handful of patterns from the Gang of Four book. With each chapter,
I give my spin on a pattern and how I think it relates to game programming.

第二部分，[设计模式探索](design-patterns-revisited.html)，通过各章节介绍来自《设计模式》书中设计的各类有用的设计模式。我会对各个设计模式做一些评价，并将它们与游戏开发关联起来。

The last section is the real meat of the book. It presents thirteen
design patterns that I've found useful. They're grouped into four categories:
[Sequencing Patterns](sequencing-patterns.html), [Behavioral Patterns](behavioral-patterns.html), [Decoupling Patterns](decoupling-patterns.html),
and [Optimization Patterns](optimization-patterns.html).

最后一部分是本书的真正意义所在。它介绍了十三个我认为很有用的设计模式。它们被划分归类到以下四个类型中：[排序模式](sequencing-patterns.html), [行为模式](behavioral-patterns.html), [去耦模式](decoupling-patterns.html), 和 [优化模式](optimization-patterns.html).

Each of these patterns is described using a consistent structure so that you
can use this book as a reference and quickly find what you need:

每个模式都通过统一的结构进行介绍，所以你可将本书看作一份索引，在你需要的时候可以快速检索出需要的内容。

* The **Intent** section provides a snapshot description of the pattern in
  terms of the problem it intends to solve. This is first so that you can hunt
  through the book quickly to find a pattern that will help you with your
  current struggle.

* **目标** 分节提供了一份关于模式的简短描述，阐释它企图可以解决的问题。这是你通过本书实现快速获得且帮助你解决当前困境的模式的第一个方式。

* The **Motivation** section describes an example problem that we will be
  applying the pattern to. Unlike concrete algorithms, a pattern is usually
  formless unless applied to some specific problem. Teaching a pattern without
  an example is like teaching baking without mentioning dough. This section
  provides the dough that the later sections will bake.

* **动机** 分节描述了一个应用设计模式的例子。与具体的算法不同，设计模式通常是非定型的直到应用到某些具体的问题中。脱离例子将设计模式，就教导烘培但不使用面团一样。这分节就是为后面分节提供了准备。

* The **Pattern** section distills the essence of the pattern out of the
  previous example. If you want a dry textbook description of the pattern,
  this is it. It's also a good refresher if you're familiar with a pattern
  already and want to make sure you don't forget an ingredient.

* **模式** 分节从前面的例子中剖析出模式的真实意义。假如你想获得关于模式的书面描述，那本节就是你所要的。假如你对模式已经比较了解，那么该节也是一次不错的复习机会，同时确保你不会遗忘其中的要点。

* So far, the pattern has only been explained in terms of a single example.
  But how do you know if the pattern will be good for *your* problem?
  The **When to Use It** section provides some guidelines on when the pattern
  is useful and when it's best avoided. The **Keep in Mind** section points
  out consequences and risks when using the pattern.

* 到目前为止，模式仅通过一个例子作了阐述解释。但又如何判断该模式是否适用于你的问题呢？**何时使用** 分节就提供了一些方针判断模式何时有用，何时应尽量避免使用。**谨记** 分节则指出使用模式的后果和风险。

* If, like me, you need concrete examples to really *get* something,
  then **Sample Code** is your section. It walks step by step through a full
  implementation of the pattern so you can see exactly how it works.

* 假如你像我一样，需要具体的例子才能感到真实获得收获，那么 **参考代码** 就是你需要的。它通过一个模式完整实践的样例去一步步让你明白模式是如何工作的。

* Patterns differ from single algorithms because they are open-ended. Each
  time you use a pattern, you'll likely implement it differently. The next section,
  **Design Decisions**, explores that space and shows you different options to
  consider when applying a pattern.

* 模式区分于单一的算法，因为它们是开放式的。每一次你使用模式，你将极易以不同的方式使用它。在下一分节 **设计定案** 中，探索内容并向你展示应用模式时会考虑到各个不同观点。

* To wrap it up, there's a short **See Also** section that shows how this
  pattern relates to others and points you to real-world open source code that
  uses it.

* 归纳以上内容，**See Also** 分节提供了该模式相关的一些资料和开源代码。

## About the Sample Code

Code samples in this book are in C++, but that isn't to imply that these
patterns are only useful in that language or that C++ is a better language
for them than others. Almost any language will work fine, though some patterns
do tend to presume your language has objects and classes.

本书中的代码例子使用C++编写，但并非需要该语言才能使用，或者是C++相对于其它语言更适用于该模式。绝大多数的编程语言都能够适用于该模式，但也有部分模式需要语言支持对象和类。

I chose C++ for a couple of reasons. First, it's the most popular language for
commercially shipped games. It is the *lingua franca* of the industry. More so,
the C syntax that C++ is based on is also the basis for Java, C#, JavaScript,
  and many other languages. Even if you don't know C++, the odds are good you
can understand the code samples here with a little bit of effort.

我选择C++编写基于以下两个原因，一是C++作为商业游戏中最流行的开发语言。它作为游戏行业内的通用语言。更何况，C++基于的C语法也同样作为Java，C#，JavaScript等语言的基础。即便你不懂C++，也可能只要花一小点功夫也能够明白代码例子。

The goal of this book is *not* to teach you C++. The samples are kept as
simple as possible and don't represent good C++ style or usage. Read the code
samples for the idea being expressed, not the code expressing it.

本书的目的不是传授C++。代码例子尽量保持简单，且不代表良好的C++编写风格或者用法。代码样例实现表达了模式，并不是一份代码本身表达。

In particular, the code is not written in "modern" -- C++11 or newer -- style.
It does not use the standard library and rarely uses templates. This makes for
"bad" C++ code, but I hope that by keeping it stripped down, it will be more
approachable to people coming from C, Objective-C, Java, and other languages.

尤其是代码并不是使用“现代”--C++或更新--的编写风格。代码中没有使用标准库，甚至几乎不使用模板。这虽然会是一份”不好”的C++代码，但是我希望能它能保持对C++的剥离，这样它能够对其它使用C，Objective-C，Java等其它语言的人们显得更易懂。

To avoid wasting space on code you've already seen or that isn't relevant to
the pattern, code will sometimes be omitted in examples. When this occurs, an
ellipsis will be placed in the sample to show where the missing code goes.

为了避免已经读过的代码或跟模式无关的代码浪费空间，例子中的多余代码有时会被删除。当出现这种情况的时候，会用一个省略号去表示例子中的被删除代码并链接代码内容。

Consider a function that will do some work and then return a value. The
pattern being explained is only concerned with the return value, and not the
work being done. In that case, the sample code will look like:

^code update

考虑到有些函数将执行某些逻辑并返回一个值，而模式仅通过返回值去进行解释，而不是将要执行的操作。在这类代码中，例子看上去像以下这种表述：

^code update

## Where to Go From Here

Patterns are a constantly changing and expanding part of software development.
This book continues the process started by the Gang of Four of documenting and
sharing the software patterns they saw, and that process will continue after
the ink dries on these pages.

设计模式是软件开发中经常变化和扩大的部分。本书从《设计模式：可复用面向对象软件》开始继续文档编写和软件模式分享的过程，且将在后续的内容中继续讨论。

You are a core part of that process. As you develop your own patterns and
refine (or refute!) the patterns in this book, you contribute to the software
community. If you have suggestions, corrections, or other feedback about
what's in here, please get in touch!

你是这过程中的核心部分，你开发个人模式或从本书中提炼模式，都是对软件社区的贡献。假如你对本书有建议，纠错，或者其它反馈，请进入论坛。
