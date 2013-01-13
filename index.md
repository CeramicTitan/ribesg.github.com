---
layout: page
title: Root
tagline: cd /
---
{% include JB/setup %}

## Let's test it this work :

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

