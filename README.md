# PWBTestsDataGenerator

Load 

```Smalltalk

 Metacello new
    	githubUser: 'mahugnon' project: 'PWBTestsDataGenerator' commitish: 'master' path: 'src';
    	baseline: 'PWBTestsDataGenerator';
	 onConflict: [ :e | e useIncoming ];
        onUpgrade: [ :e | e useIncoming ];
        load
```
 [![Build Status](https://ci.inria.fr/pharo-contribution/job/PWBTestsDataGenerator/badge/icon)](https://ci.inria.fr/pharo-contribution/job/PWBTestsDataGenerator/) [![Build Status](https://travis-ci.com/mahugnon/PWBTestsDataGenerator.svg?branch=master)](https://travis-ci.com/mahugnon/PWBTestsDataGenerator)
