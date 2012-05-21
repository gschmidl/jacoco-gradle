jacoco-gradle
=============

JaCoCo plugin for Gradle

To use, add something like

	buildscript {
		apply from: 'jacoco.gradle'
	}
	
to your build.gradle.

You can customize parameters:

	jacoco {
		excludes += [ "oracle.*" ]
	}
	
For a list of all known parameters, look at the JacocoPluginConvention and JaCoCo ant task documentation at http://www.eclemma.org/jacoco/trunk/doc/ant.html