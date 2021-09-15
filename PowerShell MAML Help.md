# PowerShell MAML Help

## Contents

1. [Components For A Well-Formed PowerShell MAML Help](#1.)

## 1. Components For A Well-Formed PowerShell MAML Help

## 1.1. XML Declaration

XML Declaration.

```XML
<?xml version="1.0" encoding="UTF-8"?>
```

# 1.2. Help Items

Root container of this help file and of all commands. All namespaces are defined here.

```XML
<helpItems schema="maml" xmlns="http://msh" xmlns:maml="http://schemas.microsoft.com/maml/2004/10" xmlns:command="http://schemas.microsoft.com/maml/dev/command/2004/10" xmlns:dev="http://schemas.microsoft.com/maml/dev/2004/10" xmlns:MSHelp="http://msdn.microsoft.com/mshelp"><!--All help here--></helpItems>
```

# 1.3. Command

Root container for this command.

```XML
<command:command><!--All help for this command here--></command:command>
```

# 1.4. Command Name And Synopsis

Name and synopis.

```XML
<command:details><!--Name and synopsis here--></command:details>
```

# 1.4.1. Command Name

Name.

```XML
<command:name><!--Verb-noun pair here--></command:name>
<command:verb><!--Verb here--></command:verb>
<command:noun><!--Noun here--></command:noun>
```
# 1.4.2. Command Synopsis

Synopsis.

```XML
<maml:description>
    <maml:para><!--Synopsis here--></maml:para>
</maml:description>
```

# 1.5. Command Description

Description.

```XML
<maml:description>
	<maml:para><!--Description here--></maml:para>
</maml:description>
```

# 1.6. Command Syntax Configurations

Root container for all syntax configurations.

```XML
<command:syntax><!--Syntax configurations here--></command:syntax>
```
# 1.6.1. Command Syntax Configuration

Root container for this syntax configuration.

```XML
<command:syntaxItem><!--Syntax configuration here--></command:syntaxItem>
```
# <a name="1."></a>1.6.1.1. Command Name

Name.

```XML
<maml:name><!--Command verb-noun pair here--></maml:name>
```

