// [![Build](https://github.com/PeanutButter-Unicorn/{{projectName}}/actions/workflows/maven.yml/badge.svg)](https://github.com/PeanutButter-Unicorn/{{projectName}}/actions)
// ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/PeanutButter-Unicorn/{{projectName}})
// ![GitHub](https://img.shields.io/github/license/PeanutButter-Unicorn/{{projectName}})
// ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/PeanutButter-Unicorn/{{projectName}}/main)
// ![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/y/PeanutButter-Unicorn/{{projectName}})

## Summary


### Install

<details><summary>Windows</summary>
    <ol>
        <li>Download latest windows binary</li>
        <li>Move executable to dedicated directory, ie <code>"C:\Program Files\Jonathan is so cool\"</code></li>
        <li>Add directory to your PATH</li>

```PowerShell
"C:\Program Files\my-directory\" |
if (!($env:Path -like "*$_*"))
{
    $env:Path = "$( $env:Path );$_"
}
```

</ol>
</details>

<details><summary>Linux</summary>
<ol>
        <li>Download latest linux binary</li>
        <li>Add to <code>$HOME\bin\</code> directory</li>
</ol>
</details>

___



### Want to get involved? 
 See our [contributing] doc before taking a whack at any [open issues].
 
[contributing]:Contributing.md
[open issues]:issues
