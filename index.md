---
layout: default
---

# [](#header-1)Getting Started

<ul style="width:900px;">
<li style="font-weight:bold;">Open Visual Studio and make a new project.</li>
<li style="font-weight:bold;">Add reference to Memory.dll.
<span class="highlight_this">Project</span> » <span class="highlight_this">Manage NuGet Packages...</span> » <span class="highlight_this">select Browse</span> » <span class="highlight_this">Search For Memory.dll</span>
<ul>
<li style="font-weight:bold;margin-top:5px;">Or, for manual installation...</li>
<span class="highlight_this">Project</span> » <span class="highlight_this">Add Reference</span> » <span class="highlight_this">Browse...</span> » <span class="highlight_this">Select Memory.dll</span>
</ul>
</li>
</ul>

# [](#header-1)C# App Usage

<li style="font-weight:bold;">Place using statement above namespace.</li>
```csharp
using Memory;
```
<li style="font-weight:bold;">Create a namespace for Mem in your class.</li>
```csharp
public Mem m = new Mem();
```

# [](#header-1)VB.Net App Usage

<li style="font-weight:bold;">Place Imports statement above Public Class.</li>
```vb.net
Imports Memory
```
<li style="font-weight:bold;">Create a namespace for Mem in your class.</li>
```vb.net
Dim m As New Memory.Mem
```

<span style="font-weight:bold;">IMPORTANT:</span> Your program must run with admin privileges! <a href="https://github.com/erfg12/memory.dll/wiki/Administrative-Privileges">Click here to learn how.</a>

<a href="https://github.com/erfg12/memory.dll/wiki" target="_BLANK">Now you can use m.FUNCTIONS in your project! Click here for wiki docs.</a>