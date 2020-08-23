# PHP
## Start/End
A Block of php should start with the full `<?php` and at the end `?>`. Don't use `<?` and `?>` or something like that. Also not allowed is `<?=` and `?>`.
## True/False/Null
The statements `True`, `False` and `Null` must be lowercase except the first Letter, which must be uppercase.
## Language constructs
A language construct (like `echo`, `include_once` and so on) must be used without brackets.

False is:
```
echo("Hi","What's going on");
```
Right is:
```
echo "Hi"."What's going on";
```
### Use tabulator
Don't use space as tabulator. Indent code right.

False is:
```
<?php
if($w){
       break;
}
?>
```
Right is:
```
<?php
  if($w){
    break;
  }
?>
```
## Use a dot to connect strings and variables.
Don't use inline variables. (Exexption: Heredoc)

Don't connect strings in a echo with a `,`. You must always use a `.`.

False is:
```
<?php
  echo "Hi","There $test";
?>
```
Right is:
```
<?php
  echo "Hi"."There".$test;
?>
```
## Heredoc
Always use as heredoc name `heredoc`. Exeption: `heredoc;` is in the heredoc code.
