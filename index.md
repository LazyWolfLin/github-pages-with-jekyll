---
---
# Welcome to my homepage

I'm glad you are here. I plan to talk about ...

This is a site for github lab course.

```C++
#include <iostream>

int main()
{
    return 0;
}
```
<h1>Latest Posts</h1>

<ul>
    {% for post in site.posts %}
    <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
    </li>
    {% endfor %}
</ul>
