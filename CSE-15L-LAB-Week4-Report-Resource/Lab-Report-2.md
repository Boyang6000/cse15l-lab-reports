# Lab Report 2

**Change 1 (From Darrius, Alexander, and  Andrew)**

![Image](Change1.png)

[Test File 1 for a failure-inducing input](test-file1.md)

Symptom
PS C:\Users\boyan\OneDrive\文档\GitHub\Fork-markdown-parser-original> java MarkdownParse test-file1.md 
Exception in thread "main" java.lang.OutOfMemoryError: Java heap space
        at java.base/java.lang.StringLatin1.newString(StringLatin1.java:766)
        at java.base/java.lang.String.substring(String.java:2708)
        at MarkdownParse.getLinks(MarkdownParse.java:19)
        at MarkdownParse.main(MarkdownParse.java:30)

The symptom of the program is that the system is crashing and goes out of memory. The bug is that the program goes into a infinite loop if it cannot find the first openBracket.

**Change 2 (From Darrius, Alexander, and  Andrew)**

![Image](Change2.png)

[Test File 1 for a failure-inducing input](test-file2.md)

Symptom
PS C:\Users\boyan\OneDrive\文档\GitHub\Fork-markdown-parser-original> java MarkdownParse test-file2.md
Exception in thread "main" java.lang.OutOfMemoryError: Java heap space
        at java.base/java.lang.StringLatin1.newString(StringLatin1.java:766)
        at java.base/java.lang.String.substring(String.java:2708)
        at MarkdownParse.getLinks(MarkdownParse.java:19)
        at MarkdownParse.main(MarkdownParse.java:30)

The symptom of the program is that the system is crashing and goes out of memory. The bug is that the program goes into a infinite loop if the openParen is not next to the closeBracket.


**Change 3 (From Darrius, Alexander, and  Andrew)**

![Image](Change3.png)

[Test File 1 for a failure-inducing input]


