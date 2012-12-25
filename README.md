My notebooks of C#
==================

Install
--------

�ǂ��炩

* Visual Studio Express
* Mono

Visual Studio�͓o�^�܂ł��낢��߂�ǂ����������肵���̂ŁA�܂�Mono�����g���ĂȂ�

Note
----

* GUI�ɂ��ẮA �Œ�� Gtk# �� Windows.Forms ��2�_�͔c�����Ă������ق����ǂ�����
  Gtk#�g���� MonoDevelop ����Ă�����ۂ�

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

�Q�l
----

### Tips

* [����d�l(MSDN)](http://msdn.microsoft.com/ja-jp/library/ms228593)
* [����d�l(ECMA-334)](http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-334.pdf)
* [Linux�œ���.NET���uMono 1.0�v�̎��́i�O�ҁj](http://www.atmarkit.co.jp/fdotnet/special/mono10_01/mono10_01_04.html)
* [Mono 2.8��C#4.0�̃v���O�������R���p�C��](http://d.hatena.ne.jp/gsf_zero1/20110226/p1)
* [.gitignore](https://raw.github.com/github/gitignore/master/CSharp.gitignore)

### Tutorial

Mono�ł̓�����ǂ����Ȃ�����

* [C# �ɂ��v���O���~���O����](http://ufcpp.net/study/csharp/index.html)
* [�v���O���~���O���� C#](http://vipprog.net/wiki/prog_lang/cs.html)

Author
------

Kenichi Kamiya
