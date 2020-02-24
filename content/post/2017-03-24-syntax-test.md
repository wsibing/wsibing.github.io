---
categories: default
date: "2017-03-24T01:30:13Z"
tags: test syntax
title: Syntax Highlighting Test
---
Jekyll uses Rouge by default for syntax highlighting, here are some tests.

Ruby:
{{< highlight ruby >}}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{{< / highlight >}}

Python with line numbers:
{{< highlight python "linenos=table" >}}
def print_hi(name):
    print("Hi, {}".format(name))

print_hi('Tom')
# prints 'Hi, Tom' to STDOUT.
{{< / highlight >}}

C with line numbers:
{{< highlight c "linenos=table" >}}
void print_hi(string name) {
  printf("Hi, %s", name);
}
print_hi("Tom");
/* prints 'Hi, Tom' to STDOUT. */
{{< / highlight >}}