# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Code Annotation 예제

### Codeblocks

some `code` goes here.

### Plain codeblock

A plain codeblock:

```
some code here
public static java()
// comment
```


### Java codeblock java

A `java` codeblock:

```java
some code here
public static java()
// comment
```



### Java codeblock title

A `java` codeblock with title:

```java title="sample.java"

public static java()
// comment
```


### Java codeblock linenums

A `java` codeblock with linenums:

```java title="sample.java" linenums="1"
package com.tibco.custom.jms.provider;

import com.tibco.bw.sr.jms.runtime.api.custom.AbstractJMSProvider;

public class CustomJMSProvider extends AbstractJMSProvider {

	/**
	 * This Method must provide an intial context factory class context to get corresponding JMS Provider object
	 * @return returns intial context factory class name 
	 */
	@Override
	public String getInitialContextFactory() {
		return "org.apache.activemq.artemis.jndi.ActiveMQInitialContextFactory";
	}

}
```


### Java codeblock with linenums highlight

A `java` codeblock with linenums:

```java title="sample.java" linenums="1" hl_lines="12 13"
package com.tibco.custom.jms.provider;

import com.tibco.bw.sr.jms.runtime.api.custom.AbstractJMSProvider;

public class CustomJMSProvider extends AbstractJMSProvider {

	/**
	 * This Method must provide an intial context factory class context to get corresponding JMS Provider object
	 * @return returns intial context factory class name 
	 */
	@Override
	public String getInitialContextFactory() {
		return "org.apache.activemq.artemis.jndi.ActiveMQInitialContextFactory";
	}

}
```

## Icons and Emojs

:smile: :cry: :pray:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }
