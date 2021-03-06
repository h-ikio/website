---
out: Community-Plugins.html
---

  [Bintray-For-Plugins]: Bintray-For-Plugins.html

Community Plugins
-----------------

### sbt Organization

The [sbt organization](https://github.com/sbt) is available for use by
any sbt plugin. Developers who contribute their plugins into the
community organization will still retain control over their repository
and its access. The goal of the sbt organization is to organize sbt
software into one central location.

A side benefit to using the sbt organization for projects is that you
can use gh-pages to host websites under the http://scala-sbt.org domain.

### Community Ivy Repository

[Typesafe](https://www.typesafe.com) has provided a freely available
[Ivy Repository](https://repo.scala-sbt.org/scalasbt) for sbt projects
to use. This Ivy repository is mirrored from the freely available
[Bintray service](https://bintray.com).
If you'd like to submit your plugin, please follow these instructions:
[Bintray For Plugins][Bintray-For-Plugins].

### Available Plugins

Please feel free to
[submit a pull request](https://github.com/sbt/website/pulls) that adds
your plugin to the list.

#### Plugins for IDEs

-   IntelliJ IDEA
    -   sbt Plugin to generate IDEA project configuration: <https://github.com/mpeltonen/sbt-idea>
    -   IDEA Plugin to embed an sbt Console into the IDE: <https://github.com/orfjackal/idea-sbt-plugin>
-   Netbeans (no support to create a new sbt project yet)
    -   sbt-netbeans-plugin (older): <https://github.com/remeniuk/sbt-netbeans-plugin>
    -   sbt plugin to generate NetBeans configuration: <https://github.com/dcaoyuan/nbsbt>
    -   sbt plugin to add scala support to NetBeans: <https://github.com/dcaoyuan/nbscala>
-   Eclipse: <https://github.com/typesafehub/sbteclipse>
-   Sublime Text: <https://github.com/orrsella/sbt-sublime>
-   Ensime: <https://github.com/aemoncannon/ensime-sbt-cmd>
-   sbt-mode for Emacs: <https://github.com/hvesalai/sbt-mode>
-   sbt-ctags (manage library dependency sources for vim, emacs,
    sublime) <https://github.com/kalmanb/sbt-ctags>

#### Web Plugins

-   xsbt-web-plugin:
    <https://github.com/JamesEarlDouglas/xsbt-web-plugin>
-   xsbt-webstart: <https://github.com/ritschwumm/xsbt-webstart>
-   sbt-appengine: <https://github.com/sbt/sbt-appengine>
-   sbt-gwt-plugin: <https://github.com/thunderklaus/sbt-gwt-plugin>
-   sbt-cloudbees-plugin:
    <https://github.com/timperrett/sbt-cloudbees-plugin>
-   sbt-jelastic-deploy:
    <https://github.com/casualjim/sbt-jelastic-deploy>
-   sbt-elasticbeanstalk (Deploy WAR files to AWS Elastic Beanstalk): <https://github.com/sqs/sbt-elasticbeanstalk>
-   sbt-cloudformation (AWS CloudFormation templates and stacks management): <https://github.com/tptodorov/sbt-cloudformation>
-   sbt-heroku: <https://github.com/heroku/sbt-heroku>

### Test plugins

-   junit_xml_listener: <https://github.com/ijuma/junit_xml_listener>
-   sbt-growl-plugin: <https://github.com/softprops/sbt-growl-plugin>
-   sbt-teamcity-test-reporting-plugin:
    <https://github.com/guardian/sbt-teamcity-test-reporting-plugin>
-   xsbt-cucumber-plugin:
    <https://github.com/skipoleschris/xsbt-cucumber-plugin>
-   sbt-multi-jvm: <https://github.com/typesafehub/sbt-multi-jvm>
-   sbt-testng-interface: <https://github.com/sbt/sbt-testng-interface>
-   sbt-doctest: <https://github.com/tkawachi/sbt-doctest>

#### Static Code Analysis plugins

-   cpd4sbt: <https://github.com/sbt/cpd4sbt> (copy/paste detection,
    works for Scala, too)
-   findbugs4sbt: <https://github.com/sbt/findbugs4sbt> (FindBugs only
    supports Java projects atm)
-   scalastyle: <https://github.com/scalastyle/scalastyle-sbt-plugin>
    (Scalastyle - static code checker for Scala)
-   sbt-scapegoat: <https://github.com/sksamuel/sbt-scapegoat> (Scapegoat - Scala static code analysis)
-   sbt-stats: <https://github.com/orrsella/sbt-stats> (simple,
    extensible source code statistics)

#### One jar plugins

-   sbt-assembly: <https://github.com/sbt/sbt-assembly>
-   xsbt-proguard-plugin:
    <https://github.com/adamw/xsbt-proguard-plugin>
-   sbt-deploy: <https://github.com/reaktor/sbt-deploy>
-   sbt-appbundle (os x standalone):
    <https://github.com/sbt/sbt-appbundle>
-   sbt-onejar (Packages your project using One-JAR™):
    <https://github.com/sbt/sbt-onejar>

#### Frontend development plugins

-   coffeescripted-sbt:
    <https://github.com/softprops/coffeescripted-sbt>
-   less-sbt (for less-1.3.0): <https://github.com/softprops/less-sbt>
-   sbt-less-plugin (it uses less-1.3.0):
    <https://github.com/btd/sbt-less-plugin>
-   sbt-emberjs: <https://github.com/stefri/sbt-emberjs>
-   sbt-closure: <https://github.com/eltimn/sbt-closure>
-   sbt-imagej: <https://github.com/jpsacha/sbt-imagej>
-   sbt-yui-compressor:
    <https://github.com/indrajitr/sbt-yui-compressor>
-   sbt-requirejs: <https://github.com/scalatra/sbt-requirejs>
-   sbt-vaadin-plugin:
    <https://github.com/henrikerola/sbt-vaadin-plugin>
-   sbt-purescript: <https://github.com/eamelink/sbt-purescript>
-   sbt-jasmine-plugin (Run javascript tests with jasmine within sbt):
    <https://github.com/joescii/sbt-jasmine-plugin>

#### Game development plugins

-   sbt-lwjgl-plugin (Light Weight Java Game Library):
    <https://github.com/philcali/sbt-lwjgl-plugin>
-   sbt-scage-plugin (Scala Game Engine):
    <https://github.com/mvallerie/sbt-scage-plugin>

#### Release plugins

-   sbt-aether-plugin (Published artifacts using Sonatype Aether):
    <https://github.com/arktekk/sbt-aether-deploy>
-   posterous-sbt: <https://github.com/n8han/posterous-sbt>
-   sbt-signer-plugin: <https://github.com/rossabaker/sbt-signer-plugin>
-   sbt-izpack (generates IzPack an installer):
    <http://software.clapper.org/sbt-izpack/>
-   sbt-ghpages (publishes generated site and api):
    <https://github.com/sbt/sbt-ghpages>
-   sbt-pgp (PGP signing plugin, can generate keys too):
    <https://github.com/sbt/sbt-pgp>
-   sbt-release (customizable release process):
    <https://github.com/sbt/sbt-release>
-   sbt-unique-version (emulates unique snapshots):
    <https://github.com/sbt/sbt-unique-version>
-   sbt-install4j: <https://github.com/jpsacha/sbt-install4j>
-   sbt-pack (generates packages with dependent jars and launch
    scripts): <https://github.com/xerial/sbt-pack>
-   sbt-start-script: <https://github.com/sbt/sbt-start-script>
-   sbt-native-packager: <https://github.com/sbt/sbt-native-packager>
-   sbt-sonatype-plugin (releases to Sonatype Nexus repository)
    <https://github.com/xerial/sbt-sonatype>
-   xitrum-package (collects dependency .jar files for standalone Scala
    programs): <https://github.com/ngocdaothanh/xitrum-package>

#### System plugins

-   sbt-sh (executes shell commands):
    <https://github.com/steppenwells/sbt-sh>
-   cronish-sbt (interval sbt / shell command execution):
    <https://github.com/philcali/cronish-sbt>
-   git (executes git commands): <https://github.com/sbt/sbt-git>
-   svn (execute svn commands): <https://github.com/xuwei-k/sbtsvn>
-   sbt-groll (sbt plugin to navigate the Git history):
    <https://github.com/sbt/sbt-groll>
-   sbt-twt (twitter processor for sbt):
    <https://github.com/sbt/sbt-twt>

#### Code generator plugins

-   sbt-haxe (Compiling [Haxe](http://www.haxe.org/) to Java):
    <https://bitbucket.org/qforce/sbt-haxe>
-   sbt-scalabuff (Google Protocol Buffers with native scala suppport
    thru ScalaBuff): <https://github.com/sbt/sbt-scalabuff>
-   sbt-fmpp (FreeMarker Scala/Java Templating):
    <https://github.com/sbt/sbt-fmpp>
-   sbt-scalaxb (XSD and WSDL binding):
    <https://github.com/eed3si9n/scalaxb>
-   sbt-protobuf (Google Protocol Buffers):
    <https://github.com/sbt/sbt-protobuf>
-   sbt-cppp (Cross-Project Protobuf Plugin for Sbt):
    <https://github.com/Atry/sbt-cppp>
-   sbt-avro (Apache Avro): <https://github.com/cavorite/sbt-avro>
-   sbt-xjc (XSD binding, using
    [JAXB XJC](http://download.oracle.com/javase/6/docs/technotes/tools/share/xjc.html) ):
    <https://github.com/sbt/sbt-xjc>
-   xsbt-scalate-generate (Generate/Precompile Scalate Templates):
    <https://github.com/backchatio/xsbt-scalate-generate>
-   sbt-antlr (Generate Java source code based on ANTLR3 grammars):
    <https://github.com/stefri/sbt-antlr>
-   sbt-antlr4 (Antlr4 runner for generating Java source code):
    <https://github.com/ihji/sbt-antlr4>
-   xsbt-reflect (Generate Scala source code for project name and
    version): <https://github.com/ritschwumm/xsbt-reflect>
-   sbt-buildinfo (Generate Scala source for any settings):
    <https://github.com/sbt/sbt-buildinfo>
-   lifty (Brings scaffolding to sbt): <https://github.com/lifty/lifty>
-   sbt-thrift (Thrift Code Generation):
    <https://github.com/bigtoast/sbt-thrift>
-   xsbt-hginfo (Generate Scala source code for Mercurial repository
    information):
    <https://bitbucket.org/lukas_pustina/xsbt-hginfo>
-   sbt-scalashim (Generate Scala shim like `sys.error`):
    <https://github.com/sbt/sbt-scalashim>
-   sbtend (Generate Java source code from
    [xtend](https://www.eclipse.org/xtend/) ):
    <https://github.com/xuwei-k/sbtend>
-   sbt-boilerplate (generating scala.Tuple/Function related boilerplate
    code): <https://github.com/sbt/sbt-boilerplate>
-   sbt-fxml (Generates controller classes for JavaFX FXML files):
    <https://bitbucket.org/phdoerfler/sbt-fxml>
-   sbt-clojure (Compiling Clojure code):
    <https://github.com/Geal/sbt-clojure>

#### Database plugins

-   flyway-sbt (Flyway - The agile database migration framework):
    <http://flywaydb.org/getstarted/firststeps/sbt.html>
-   sbt-liquibase (Liquibase RDBMS database migrations):
    <https://github.com/bigtoast/sbt-liquibase>
-   sbt-dbdeploy (dbdeploy, a database change management tool):
    <https://github.com/mr-ken/sbt-dbdeploy>

#### Documentation plugins

-   sbt-lwm (Convert lightweight markup files, e.g., Markdown and
    Textile, to HTML): <http://software.clapper.org/sbt-lwm/>
-   sbt-site (Site generation for SBT):
    <https://github.com/sbt/sbt-site>
-   Laika (Template-based site generation, Markdown, reStructuredText,
    no external tools): <http://planet42.github.io/Laika/>
-   literator-plugin (Converts sources into markdown documents):
    <https://github.com/laughedelic/literator>
-   sbt-class-diagram (Create a class diagram)
    <https://github.com/xuwei-k/sbt-class-diagram>

#### Library dependency plugins

-   ls-sbt (An sbt interface for ls.implicit.ly):
    <https://github.com/softprops/ls>
-   sbt-dependency-graph (Creates a graphml file of the dependency
    tree): <https://github.com/jrudolph/sbt-dependency-graph>
-   sbt-dirty-money (Cleans Ivy2 cache):
    <https://github.com/sbt/sbt-dirty-money>
-   sbt-updates (Checks Maven repos for dependency updates):
    <https://github.com/rtimush/sbt-updates>
-   sbt-lock (Locks library versions for reproducible build):
    <https://github.com/tkawachi/sbt-lock>
-   sbt-versions (Checks for updated versions of your dependencies):
    <https://github.com/sksamuel/sbt-versions>

#### Utility plugins

-   sbt-process-runner (Run your own applications from SBT console)
    <https://github.com/whysoserious/sbt-process-runner>
-   jot (Write down your ideas lest you forget them)
    <https://github.com/softprops/jot>
-   np (Dead simple new project directory generation):
    <https://github.com/softprops/np>
-   npt (Creates new project skeletons based on templates):
    <https://github.com/reikje/npt>
-   sbt-editsource (A poor man's *sed*(1), for sbt):
    <http://software.clapper.org/sbt-editsource/>
-   sbt-conflict-classes (Show conclict classes from classpath):
    <https://github.com/todesking/sbt-conflict-classes>
-   sbt-cross-building (Simplifies building your plugins for multiple
    versions of sbt): <https://github.com/jrudolph/sbt-cross-building>
-   sbt-doge (aggregates tasks across subprojects and their `crossScalaVersions`):
    <https://github.com/sbt/sbt-doge>
-   sbt-revolver (Triggered restart, hot reloading):
    <https://github.com/spray/sbt-revolver>
-   sbt-scalaedit (Open and upgrade ScalaEdit (text editor)):
    <https://github.com/kjellwinblad/sbt-scalaedit-plugin>
-   sbt-man (Looks up scaladoc): <https://github.com/sbt/sbt-man>
-   sbt-taglist (Looks for TODO-tags in the sources):
    <https://github.com/johanandren/sbt-taglist>
-   migration-manager:
    <https://github.com/typesafehub/migration-manager>
-   sbt-scalariform (adding support for source code formatting using
    Scalariform): <https://github.com/sbt/sbt-scalariform>
-   sbt-aspectj: <https://github.com/sbt/sbt-aspectj>
-   sbt-properties: <https://github.com/sbt/sbt-properties>
-   sbt-multi-publish (publish to more than one repository
    simultaneously):
    <https://github.com/davidharcombe/sbt-multi-publish>
-   sbt-about-plugins (shows some details about plugins loaded):
    <https://github.com/jozic/sbt-about-plugins>
-   sbt-one-log (make Log dependency easy):
    <https://github.com/zavakid/sbt-one-log>
-   sbt-git-stamp (include git metadata in MANIFEST.MF file in artifact):
    <https://bitbucket.org/pkaeding/sbt-git-stamp>
-   fm-sbt-s3-resolver (Resolve and Publish using Amazon S3):
    <https://github.com/frugalmechanic/fm-sbt-s3-resolver>
-   sbt-notebook (Adds scala-notebook capabilities to sbt projects):
    <https://github.com/alexarchambault/sbt-notebook>

#### Code coverage plugins

-   sbt-scct: <https://github.com/sqality/sbt-scct>
-   sbt-scoverage: <https://github.com/scoverage/sbt-scoverage>
-   jacoco4sbt: <https://github.com/sbt/jacoco4sbt>
-   sbt-coveralls: <https://github.com/scoverage/sbt-coveralls>

#### Android plugin

-   android-plugin: <https://github.com/jberkel/android-plugin>
-   android-sdk-plugin: <https://github.com/pfn/android-sdk-plugin>

#### Build interoperability plugins

-   ant4sbt: <https://github.com/sbt/ant4sbt>

#### OSGi plugin

-   sbtosgi: <https://github.com/typesafehub/sbtosgi>

#### Plugin bundles

-   tl-os-sbt-plugins (Version, Release, and Package Management, Play 2.0 and Git utilities) :
    <https://github.com/trafficland/tl-os-sbt-plugins>
