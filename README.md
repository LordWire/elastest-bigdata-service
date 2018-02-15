[![License badge](https://img.shields.io/badge/license-Apache2-green.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Documentation badge](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://elastest.io/docs/)
[![Build Status](https://ci.elastest.io/jenkins/buildStatus/icon?job=elastest-bigdata-service/ebs/master)](https://ci.elastest.io/jenkins/job/elastest-bigdata-service/ebs/master)
[![codecov](https://codecov.io/gh/elastest/elastest-bigdata-service/branch/master/graph/badge.svg)](https://codecov.io/gh/elastest/elastest-bigdata-service)

[![][ElasTest Logo]][ElasTest]

Copyright © 2017-2019 [<member>]. Licensed under
[Apache 2.0 License].

elastest-bigdata-service
==============================

The ElasTest Big-Data Service (EBS) is an ElasTest Test Support Service (TSS) that provides a computing engine based on [Apache Spark](http://spark.apache.org) to be utilized by tests inside ElasTest. To achieve that, tests utilizing EBS are built inside a specialized container which is launched as part of the whole Big Data stack (both EBS and EDM parts).  For usage and developer documentation, check the [component documentation](https://github.com/elastest/elastest-bigdata-service/tree/master/docs) and [ElasTest Documentation][ElasTest Doc].

What is ElasTest
-----------------

This repository is part of [ElasTest], which is a flexible open source testing
platform aimed to simplify the end-to-end testing processes for different types
of applications, including web and mobile, among others.

The objective of ElasTest is to provide advance testing capabilities aimed to
increase the scalability, robustness, security and quality of experience of
large distributed systems. All in all, ElasTest will make any software
development team capable of delivering software faster and with fewer defects.

Documentation
-------------

The ElasTest project provides detailed [documentation][ElasTest Doc] including
tutorials, installation and development guide.

Source
------

Source code for other ElasTest projects can be found in the [GitHub ElasTest
Group].

News
----

Check the [ElasTest Blog] and follow us on Twitter [@elastestio][ElasTest Twitter].

Issue tracker
-------------

Issues and bug reports should be posted to the [GitHub ElasTest Bugtracker].

Licensing and distribution
--------------------------

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Contribution policy
-------------------

You can contribute to the ElasTest community through bug-reports, bug-fixes,
new code or new documentation. For contributing to the ElasTest community,
you can use GitHub, providing full information about your contribution and its
value. In your contributions, you must comply with the following guidelines

* You must specify the specific contents of your contribution either through a
  detailed bug description, through a pull-request or through a patch.
* You must specify the licensing restrictions of the code you contribute.
* For newly created code to be incorporated in the ElasTest code-base, you
  must accept ElasTest to own the code copyright, so that its open source
  nature is guaranteed.
* You must justify appropriately the need and value of your contribution. The
  ElasTest project has no obligations in relation to accepting contributions
  from third parties.
* The ElasTest project leaders have the right of asking for further
  explanations, tests or validations of any code contributed to the community
  before it being incorporated into the ElasTest code-base. You must be ready
  to addressing all these kind of concerns before having your code approved.

Support
-------

The ElasTest project provides community support through the [ElasTest Public
Mailing List] and through [StackOverflow] using the tag *elastest*.


<p align="center">
  <img src="http://elastest.io/images/logos_elastest/ue_logo-small.png"><br>
  Funded by the European Union
</p>

[Apache 2.0 License]: http://www.apache.org/licenses/LICENSE-2.0
[ElasTest]: http://elastest.io/
[ElasTest Blog]: http://elastest.io/blog/
[ElasTest Doc]: http://elastest.io/docs/
[ElasTest Logo]: http://elastest.io/images/logos_elastest/elastest-logo-gray-small.png
[ElasTest Public Mailing List]: https://groups.google.com/forum/#!forum/elastest-users
[ElasTest Twitter]: https://twitter.com/elastestio
[GitHub ElasTest Group]: https://github.com/elastest
[GitHub ElasTest Bugtracker]: https://github.com/elastest/bugtracker
[Repository Doc]: docs/index.md
[StackOverflow]: http://stackoverflow.com/questions/tagged/elastest
[Universidad Rey Juan Carlos]: https://www.urjc.es/