---
layout: page
title: Root
tagline: cd /
---
{% include JB/setup %}

## Let's test if this work :

{% highlight java %}
public class Main {
    public static void main(String args) {
        /*
            This a multiple-line comment
            ...With multiple lines
        */
        System.out.println("Test" + 42);
    }
    
    @Annotation(test = "Test")
    private Integer woot() {
        // This is a comment
        return 42;
    }
}
{% endhighlight %}

{% include JB/comments %}
