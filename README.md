# merrychristmas
New
Source Repository
Maven projects use Git or Subversion to manage their source code: decisions to stay with Subversion or move to Git are tracked on Maven's Wiki.

Instructions on Subversion use can be found in the online book Version Control with Subversion. Instructions on Git use can be found in the online book Pro Git. Instructions for using the Apache Software Foundation Git repositories are at https://git-wip-us.apache.org.

Full Maven Sources
As described in the next paragraphs, Maven full source code is dispatched in more than 100 Git repos: Maven core, but also plugins or components, skins, a few svn2git read-only mirrors...

To check out full Maven source code easily, we provide a simple way using additional Google repo tool and an additional Git repository for tool's manifest:

Apache Maven full source code	
https://gitbox.apache.org/repos/asf/maven-sources.git
(GitHub mirror)
Install a git client if needed and the Google Repo tool (see manual install instructions).
Check out a new repo workspace and prepare master branch:
repo init -u https://gitbox.apache.org/repos/asf/maven-sources.git
repo sync
repo start master --all
In your IDE, import the projects you're interested in from the repo workspace. Or directly build with command line the component you want.
Maven Sources Overview


Each component has its own Jira project or component for issue tracking: see the Issue Management report to get a summary.

Maven Site
The sources for this site are available in a distinct Git repository:

Apache Maven Site	
https://gitbox.apache.org/repos/asf/maven-site.git
(GitHub mirror)	Jira MNGSITE
Maven Core
The Git repository for Maven contains a master branch which is the current development version. There is also a branch for maven-2.2.X or maven-3.0.x. In addition, the integration tests for the Maven core have their own repository.

Apache Maven	
https://gitbox.apache.org/repos/asf/maven.git
(GitHub mirror)	Jira MNG
Apache Maven Core ITs	
https://gitbox.apache.org/repos/asf/maven-integration-testing.git
(GitHub mirror)	
Other Components
The source repositories for the various plugins are in Git, listed in the documentation of the respective plugin, reachable via the plugin index.

There are also many shared components and subsystems with their own source repositories, mainly in Git, some in Subversion.

Components in Git
The components in Git are:

Apache Maven Archetype	
https://gitbox.apache.org/repos/asf/maven-archetype.git
(GitHub mirror)	Jira MARCHETYPE
Apache Maven Archetypes	
https://gitbox.apache.org/repos/asf/maven-archetypes.git
(GitHub mirror)	Jira MARCHETYPES
Apache Maven Artifact Resolver	
https://gitbox.apache.org/repos/asf/maven-resolver.git
(GitHub mirror)	Jira MRESOLVER
Apache Maven Artifact Resolver Ant Tasks	
https://gitbox.apache.org/repos/asf/maven-resolver-ant-tasks.git
(GitHub mirror)	Jira MRESOLVER
Apache Maven Distribution Checking Tool	
https://gitbox.apache.org/repos/asf/maven-dist-tool.git
(GitHub mirror)	
Apache Maven Enforcer	
https://gitbox.apache.org/repos/asf/maven-enforcer.git
(GitHub mirror)	Jira MENFORCER
Apache Maven JXR	
https://gitbox.apache.org/repos/asf/maven-jxr.git
(GitHub mirror)	Jira JXR
Apache Maven Indexer	
https://gitbox.apache.org/repos/asf/maven-indexer.git
(GitHub mirror)	Jira MINDEXER
Apache Maven Plugin Testing	
https://gitbox.apache.org/repos/asf/maven-plugin-testing.git
(GitHub mirror)	Jira MPLUGINTESTING
Apache Maven Plugin Tools	
https://gitbox.apache.org/repos/asf/maven-plugin-tools.git
(GitHub mirror)	Jira MPLUGIN
Apache Maven Release (Release api and plugin)	
https://gitbox.apache.org/repos/asf/maven-release.git
(GitHub mirror)	Jira MRELEASE
Apache Maven SCM	
https://gitbox.apache.org/repos/asf/maven-scm.git
(GitHub mirror)	Jira SCM
Apache Maven Surefire	
https://gitbox.apache.org/repos/asf/maven-surefire.git
(GitHub mirror)	Jira SUREFIRE
Apache Maven Wagon	
https://gitbox.apache.org/repos/asf/maven-wagon.git
(GitHub mirror)	Jira WAGON
Plugins
Apache Maven ACR Plugin	
https://gitbox.apache.org/repos/asf/maven-acr-plugin.git
(GitHub mirror)	
Apache Maven Ant Plugin	
https://gitbox.apache.org/repos/asf/maven-ant-plugin.git
(GitHub mirror)	
Apache Maven AntRun Plugin	
https://gitbox.apache.org/repos/asf/maven-antrun-plugin.git
(GitHub mirror)	
Apache Maven Assembly Plugin	
https://gitbox.apache.org/repos/asf/maven-assembly-plugin.git
(GitHub mirror)	
Apache Maven Changelog Plugin	
https://gitbox.apache.org/repos/asf/maven-changelog-plugin.git
(GitHub mirror)	
Apache Maven Changes Plugin	
https://gitbox.apache.org/repos/asf/maven-changes-plugin.git
(GitHub mirror)	
Apache Maven Checkstyle Plugin	
https://gitbox.apache.org/repos/asf/maven-checkstyle-plugin.git
(GitHub mirror)	
Apache Maven Clean Plugin	
https://gitbox.apache.org/repos/asf/maven-clean-plugin.git
(GitHub mirror)	
Apache Maven Compiler Plugin	
https://gitbox.apache.org/repos/asf/maven-compiler-plugin.git
(GitHub mirror)	
Apache Maven Dependency Plugin	
https://gitbox.apache.org/repos/asf/maven-dependency-plugin.git
(GitHub mirror)	
Apache Maven Deploy Plugin	
https://gitbox.apache.org/repos/asf/maven-deploy-plugin.git
(GitHub mirror)	
Apache Maven DOAP Plugin	
https://gitbox.apache.org/repos/asf/maven-doap-plugin.git
(GitHub mirror)	
Apache Maven Documentation Checker Plugin	
https://gitbox.apache.org/repos/asf/maven-docck-plugin.git
(GitHub mirror)	
Apache Maven EAR Plugin	
https://gitbox.apache.org/repos/asf/maven-ear-plugin.git
(GitHub mirror)	
Apache Maven EJB Plugin	
https://gitbox.apache.org/repos/asf/maven-ejb-plugin.git
(GitHub mirror)	
Apache Maven GPG Plugin	
https://gitbox.apache.org/repos/asf/maven-gpg-plugin.git
(GitHub mirror)	
Apache Maven Help Plugin	
https://gitbox.apache.org/repos/asf/maven-help-plugin.git
(GitHub mirror)	
Apache Maven Install Plugin	
https://gitbox.apache.org/repos/asf/maven-install-plugin.git
(GitHub mirror)	
Apache Maven Invoker Plugin	
https://gitbox.apache.org/repos/asf/maven-invoker-plugin.git
(GitHub mirror)	
Apache Maven JAR Plugin	
https://gitbox.apache.org/repos/asf/maven-jar-plugin.git
(GitHub mirror)	
Apache Maven Jarsigner Plugin	
https://gitbox.apache.org/repos/asf/maven-jarsigner-plugin.git
(GitHub mirror)	
Apache Maven Javadoc Plugin	
https://gitbox.apache.org/repos/asf/maven-javadoc-plugin.git
(GitHub mirror)	
Apache Maven JDepRScan Plugin	
https://gitbox.apache.org/repos/asf/maven-jdeprscan-plugin.git
(GitHub mirror)	
Apache Maven JDeps Plugin	
https://gitbox.apache.org/repos/asf/maven-jdeps-plugin.git
(GitHub mirror)	
Apache Maven JLink Plugin	
https://gitbox.apache.org/repos/asf/maven-jlink-plugin.git
(GitHub mirror)	
Apache Maven JMod Plugin	
https://gitbox.apache.org/repos/asf/maven-jmod-plugin.git
(GitHub mirror)	
Apache Maven Linkcheck Plugin	
https://gitbox.apache.org/repos/asf/maven-linkcheck-plugin.git
(GitHub mirror)	
Apache Maven Patch Plugin	
https://gitbox.apache.org/repos/asf/maven-patch-plugin.git
(GitHub mirror)	
Apache Maven PDF Plugin	
https://gitbox.apache.org/repos/asf/maven-pdf-plugin.git
(GitHub mirror)	
Apache Maven PMD Plugin	
https://gitbox.apache.org/repos/asf/maven-pmd-plugin.git
(GitHub mirror)	
Apache Maven Project Info Reports Plugin	
https://gitbox.apache.org/repos/asf/maven-project-info-reports-plugin.git
(GitHub mirror)	
Apache Maven RAR Plugin	
https://gitbox.apache.org/repos/asf/maven-rar-plugin.git
(GitHub mirror)	
Apache Maven Remote Resources Plugin	
https://gitbox.apache.org/repos/asf/maven-remote-resources-plugin.git
(GitHub mirror)	
Apache Maven Repository Plugin	
https://gitbox.apache.org/repos/asf/maven-repository-plugin.git
(GitHub mirror)	
Apache Maven Resources Plugin	
https://gitbox.apache.org/repos/asf/maven-resources-plugin.git
(GitHub mirror)	
Apache Maven SCM Publish Plugin	
https://gitbox.apache.org/repos/asf/maven-scm-publish-plugin.git
(GitHub mirror)	
Apache Maven Scripting Plugin	
https://gitbox.apache.org/repos/asf/maven-scripting-plugin.git
(GitHub mirror)	
Apache Maven Shade Plugin	
https://gitbox.apache.org/repos/asf/maven-shade-plugin.git
(GitHub mirror)	
Apache Maven Site Plugin	
https://gitbox.apache.org/repos/asf/maven-site-plugin.git
(GitHub mirror)	
Apache Maven Source Plugin	
https://gitbox.apache.org/repos/asf/maven-source-plugin.git
(GitHub mirror)	
Apache Maven Stage Plugin	
https://gitbox.apache.org/repos/asf/maven-stage-plugin.git
(GitHub mirror)	
Apache Maven Toolchains Plugin	
https://gitbox.apache.org/repos/asf/maven-toolchains-plugin.git
(GitHub mirror)	
Apache Maven Verifier Plugin	
https://gitbox.apache.org/repos/asf/maven-verifier-plugin.git
(GitHub mirror)	
Apache Maven WAR Plugin	
https://gitbox.apache.org/repos/asf/maven-war-plugin.git
(GitHub mirror)	
Parent POMs
Apache Parent POM	
https://gitbox.apache.org/repos/asf/maven-apache-parent.git
(GitHub mirror)	
Apache Maven Parent POMs	
https://gitbox.apache.org/repos/asf/maven-parent.git
(GitHub mirror)	
Shared Components
Apache Maven Archiver	
https://gitbox.apache.org/repos/asf/maven-archiver.git
(GitHub mirror)	
Apache Maven Artifact Resolver	
https://gitbox.apache.org/repos/asf/maven-artifact-resolver.git
(GitHub mirror)	
Apache Maven Artifact Transfer	
https://gitbox.apache.org/repos/asf/maven-artifact-transfer.git
(GitHub mirror)	
Apache MavenCommon Artifact Filters	
https://gitbox.apache.org/repos/asf/maven-common-artifact-filters.git
(GitHub mirror)	
Apache Maven Dependency Analyzer	
https://gitbox.apache.org/repos/asf/maven-dependency-analyzer.git
(GitHub mirror)	
Apache Maven Dependency Tree	
https://gitbox.apache.org/repos/asf/maven-dependency-tree.git
(GitHub mirror)	
Apache Maven Downloader	
https://gitbox.apache.org/repos/asf/maven-downloader.git
(GitHub mirror)	
Apache Maven Filtering	
https://gitbox.apache.org/repos/asf/maven-filtering.git
(GitHub mirror)	
Apache Maven Invoker	
https://gitbox.apache.org/repos/asf/maven-invoker.git
(GitHub mirror)	
Apache Maven Jarsigner	
https://gitbox.apache.org/repos/asf/maven-jarsigner.git
(GitHub mirror)	
Apache Maven Mapping	
https://gitbox.apache.org/repos/asf/maven-mapping.git
(GitHub mirror)	
Apache Maven OSGi	
https://gitbox.apache.org/repos/asf/maven-osgi.git
(GitHub mirror)	
Apache Maven Project Utils	
https://gitbox.apache.org/repos/asf/maven-project-utils.git
(GitHub mirror)	
Apache Maven Reporting API	
https://gitbox.apache.org/repos/asf/maven-reporting-api.git
(GitHub mirror)	
Apache Maven Reporting Executor	
https://gitbox.apache.org/repos/asf/maven-reporting-exec.git
(GitHub mirror)	
Apache Maven Reporting Implementation	
https://gitbox.apache.org/repos/asf/maven-reporting-impl.git
(GitHub mirror)	
Apache Maven Respository Builder	
https://gitbox.apache.org/repos/asf/maven-repository-builder.git
(GitHub mirror)	
Apache Maven Runtime	
https://gitbox.apache.org/repos/asf/maven-runtime.git
(GitHub mirror)	
Apache Maven Script Interpreter	
https://gitbox.apache.org/repos/asf/maven-script-interpreter.git
(GitHub mirror)	
Apache Maven Shared Incremental	
https://gitbox.apache.org/repos/asf/maven-shared-incremental.git
(GitHub mirror)	
Apache Maven Shared IO	
https://gitbox.apache.org/repos/asf/maven-shared-io.git
(GitHub mirror)	
Apache Maven Shared Jar	
https://gitbox.apache.org/repos/asf/maven-shared-jar.git
(GitHub mirror)	
Apache Maven Shared Resources	
https://gitbox.apache.org/repos/asf/maven-shared-resources.git
(GitHub mirror)	
Apache Maven Shared Utils	
https://gitbox.apache.org/repos/asf/maven-shared-utils.git
(GitHub mirror)	
Apache Maven Verifier	
https://gitbox.apache.org/repos/asf/maven-verifier.git
(GitHub mirror)	
Skins
Apache Maven Default Skin	
https://gitbox.apache.org/repos/asf/maven-default-skin.git
(GitHub mirror)	
Apache Maven Fluido Skin	
https://gitbox.apache.org/repos/asf/maven-fluido-skin.git
(GitHub mirror)	
Components in Subversion
Everything in Subversion can be checked-out from a single entry point, referencing each part through svn:externals

https://svn.apache.org/repos/asf/maven/trunks/
You can also check out every component separately. The components in Subversion are:

Maven Project (mainly KEYS)	
https://svn.apache.org/repos/asf/maven/project/
Apache Resource Bundles	
https://svn.apache.org/repos/asf/maven/resources/trunk/
Maven Sandbox	
https://svn.apache.org/repos/asf/maven/sandbox/trunk/
(GitHub mirror)
A variety of other subsystems (including obsolete trees replaced by git)	
https://svn.apache.org/repos/asf/maven/
© 2002–2021 The Apache Software Foundation
