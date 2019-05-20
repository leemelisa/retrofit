Retrofit
========
[Retrofit][1] is a type-safe HTTP client for Android and Java by Square, Inc. The advantages of Retrofit are it can be
easily translate JSON or XML response, turn HTTP API calls into a Java interface and is easy to use.

Contributing to Code
--------------------
There are many ways to contribute to the coding project such as logging bugs, submitting pull requests, reporting issues, 
and creating suggestions. Look through the [issue list][3] to find a potential issue to start working on. To improve chances 
to get a pull request merged select issues labels with bugs. To get started look through the [issue template][4] then start 
by forking the respiratory and and sending in a pull request.

When submitting code, please make every effort to follow existing conventions and style in order to keep the code as 
readable as possible. Please also make sure your code compiles by running mvn clean verify. Checkstyle failures during 
compilation indicate errors in your style and can be viewed in the checkstyle-result.xml file.

Before your code can be accepted into the project you must also sign the [Individual Contributor License Agreement (CLA)][5].

Download
--------

Download [the latest JAR][2] or grab from Maven central at the coordinates `com.squareup.retrofit2:retrofit:2.5.0`.

Snapshots of the development version are available in [Sonatype's `snapshots` repository][snap].

Retrofit requires at minimum Java 7 or Android 2.3.


R8 / ProGuard
-------------

If you are using R8 the shrinking and obfuscation rules are included automatically.

ProGuard users must manually add the options from
[this file](https://github.com/square/retrofit/blob/master/retrofit/src/main/resources/META-INF/proguard/retrofit2.pro).
(Note: You might also need rules for OkHttp and Okio which are dependencies of this library)

Feedback
--------
* Ask a question on [Stack Overflow][6].
* Request a new feature on [GitHub][7].
* File a bug in [GitHub Issues][8].

Related Projects
----------------
For more related projects check out the following:
* [Retrofit Adapters][9]
* [Retrofit Converters][10]
* [Retrofit Mock Web Server][11]


License
=======

    Copyright 2013 Square, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


 [1]: https://square.github.io/retrofit/
 [2]: https://search.maven.org/remote_content?g=com.squareup.retrofit2&a=retrofit&v=LATEST
 [snap]: https://oss.sonatype.org/content/repositories/snapshots/
 [3]: https://github.com/square/retrofit/issues
 [4]: https://github.com/square/retrofit/blob/master/.github/ISSUE_TEMPLATE.md
 [5]: https://docs.google.com/forms/d/e/1FAIpQLSeRVQ35-gq2vdSxD1kdh7CJwRdjmUA0EZ9gRXaWYoUeKPZEQQ/viewform?formkey=dDViT2xzUHAwRkI3X3k5Z0lQM091OGc6MQ&ndplr=1
 [6]: https://stackoverflow.com/questions/tagged/retrofit?sort=active
 [7]: https://github.com/square/retrofit/blob/master/.github/CONTRIBUTING.md
 [8]: https://github.com/square/retrofit/issues
 [9]: https://github.com/square/retrofit/tree/master/retrofit-adapters
 [10]: https://github.com/square/retrofit/tree/master/retrofit-converters
 [11]: https://github.com/square/retrofit/tree/master/retrofit-mock
