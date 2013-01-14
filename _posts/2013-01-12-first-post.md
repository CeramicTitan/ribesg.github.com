---
layout: post
category : main
tags : [blog, main]
---
{% include JB/setup %}

# Sample
This is a sample post to be *able* to edit the theme !

{% highlight java %}
    public class Main {

        public static void main(String args[]) {
            // This is a test sample code
            new Main();
        }

        /**
         * Example Javadoc
         * @constructor
         */
        @RandomAnnotation(randomValue = 42, lolText = "1337/(100*pi)")
        public Main() {
            System.out.println("Continue testing !");
        }

    }
{% endhighlight %}
