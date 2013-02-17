---
layout: post
title: "Hello World"
tagline: "Yet another blog is born"
description: ""
category: test
tags: [test]
---
{% include JB/setup %}

Lorem Ipsum
===========

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc et purus id
mauris faucibus lacinia. Aliquam ullamcorper, nisi ut condimentum tempus,
lectus enim vehicula augue, sit amet posuere nisi neque dapibus est. Aenean
aliquam, lectus in imperdiet faucibus, diam dui dapibus leo, ut tristique
turpis dui ac nulla. Proin varius urna eu mauris elementum ut pulvinar massa
viverra. Sed mollis fermentum neque. Nulla consectetur dictum libero, quis
aliquet felis sodales vel. Morbi nec purus in leo commodo fermentum.

Curabitur porta accumsan ultricies. Nulla facilisi. Maecenas sed ligula eget
eros fermentum venenatis. Nunc id risus dui. Integer vulputate sem non tortor
varius sollicitudin. Fusce a gravida lorem. Proin nec ipsum imperdiet ipsum
dignissim congue. Nam cursus, lacus vitae feugiat tincidunt, mi dui consequat
turpis, sed eleifend nisl lectus eget urna.

Quisque nunc augue, dictum vitae ultrices vitae, auctor lobortis enim. In
eleifend adipiscing porta. Donec semper suscipit viverra. Morbi nulla tortor,
ultricies eu auctor pharetra, tincidunt at quam. In varius, eros at fringilla
rutrum, leo lacus hendrerit velit, quis placerat tellus urna non neque.
Maecenas cursus dolor et ligula tincidunt aliquet. Nulla facilisi. Vestibulum
ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae;
Donec elit velit, aliquam nec convallis ut, malesuada iaculis quam.
Pellentesque at euismod mauris. Nunc at diam nunc, id laoreet nisi. Nulla a
commodo lorem.

Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac
turpis egestas. In vulputate risus ac nisl hendrerit semper. Curabitur
fermentum aliquet diam, id porttitor neque tristique at. Phasellus vel blandit
ligula. Donec porttitor bibendum aliquam. Cras a orci turpis, sit amet
tristique est. Maecenas imperdiet molestie sem, sed volutpat sem porta sed.
Suspendisse potenti. Phasellus nec molestie sem. Etiam tristique mauris a lacus
vestibulum ultrices. Sed eget lectus quam, sit amet faucibus ante. Proin
consectetur magna in orci sagittis a mollis lacus tempor. Cras cursus, sem
vitae vulputate aliquam, arcu nulla laoreet massa, tincidunt sagittis neque
justo nec tellus.

Donec eu dolor purus. Proin tempor, elit a suscipit molestie, nibh sapien
eleifend ligula, at semper magna lectus ac dolor. Quisque faucibus eros eget
sapien varius congue. Nulla id convallis mi. Curabitur eget nibh odio, sed
lobortis nibh. Pellentesque sapien massa, hendrerit ut vehicula in, rhoncus
quis leo. Suspendisse sit amet libero metus. Vivamus dignissim magna ac mauris
ullamcorper eleifend. Nulla facilisi. Mauris venenatis augue lorem. Nulla ut
justo ut enim sagittis faucibus. Sed odio turpis, fringilla vel facilisis nec,
vulputate sed ante.

Fibonacci Examples
------------------

{% highlight ruby %}

def fib(n)
  return n if (0..1).include? n
  fib(n-1) + fib(n-2) if n > 1
end

{% endhighlight %}

{% highlight java %}

public class Fibonacci {
    public static int fib(int n) {
        if (n < 2) {
            return n;
        } else {
            return fib(n-1) + fib(n-2);
        }
    }
}

{% endhighlight %}
