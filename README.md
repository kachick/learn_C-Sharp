My notebooks of C#
==================

Install
--------

どちらか

* Visual Studio Express
* Mono

Visual Studioは登録までいろいろめんどそうだったりしたので、まだMonoしか使ってない

Note
----

* GUIについては、 最低限 Gtk# と Windows.Forms の2点は把握しておいたほうが良さそう
  Gtk#使って MonoDevelop 作られているっぽい

Compile
--------------

### Basic

```bash
mcs app.cs
./app.exe
```

### GUI

http://www.mono-project.com/Gui_Toolkits

With Windows.Forms

```bash
mcs -pkg:dotnet gui.cs
./app.exe
```

Syntax
-------

Hello world

```c#
using System;
 
class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Hello :)");
    }
}
```

参考
----

### Tips

* [言語仕様(MSDN)](http://msdn.microsoft.com/ja-jp/library/ms228593)
* [言語仕様(ECMA-334)](http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-334.pdf)
* [Linuxで動く.NET環境「Mono 1.0」の実力（前編）](http://www.atmarkit.co.jp/fdotnet/special/mono10_01/mono10_01_04.html)
* [Mono 2.8でC#4.0のプログラムをコンパイル](http://d.hatena.ne.jp/gsf_zero1/20110226/p1)
* [.gitignore](https://raw.github.com/github/gitignore/master/CSharp.gitignore)

### Tutorial

Monoでの入門もどっかないかな

* [C# によるプログラミング入門](http://ufcpp.net/study/csharp/index.html)
* [プログラミング言語 C#](http://vipprog.net/wiki/prog_lang/cs.html)

Author
------

Kenichi Kamiya
