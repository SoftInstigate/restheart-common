# archived

On 6/3/2020 we decided to use a mono repo to manage all restheart code. restheart-common has been merged in [restheart](https://github.com/SoftInstigate/restheart) and archived.

# restheart-common

![Verify build](https://github.com/SoftInstigate/restheart-common/workflows/Verify/badge.svg)
[![](https://jitpack.io/v/org.restheart/restheart-common.svg)](https://jitpack.io/#org.restheart/restheart-common)

RESTHeart common classes

See *Unified extensions API* in [RESTHeart Roadmap](https://restheart.org/docs/roadmap/#restheart-platform-42) 
for a general description of restheart-common

# Use with maven

restheart-common is published via jitpack

see https://jitpack.io/#org.restheart/restheart-common

## Step 1. Add the JitPack repository to your build file

```
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```

## Step 2. Add the dependency

```
	<dependency>
	    <groupId>org.restheart</groupId>
	    <artifactId>restheart-common</artifactId>
	    <version>Tag</version>
	</dependency>
```

Use Tag=`master-SNAPSHOT` for snapshot builds