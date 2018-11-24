# Chocolatey
Document the software automation process with Chocolatey.

<h2>Installation</h2>
Open the PowerShell as administrator and then install Chocolatey using the following commands:

<code>
Set-ExecutionPolicy Unrestricted -Force -Scope Process;
iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex Import-Module "$env:ChocolateyInstall\helpers\chocolateyInstaller.psm1" -Force
</code>

<h2>Upgrade</h2>
To upgrading Chocolatey to the latest stable release you can use the following command:

<code>
choco upgrade chocolatey
</code>

<h2>Frequent Commands</h2>

<ul>
<li><code>choco list -l</code></li>
<li><code>choco install &lt;pkg&gt;</code></li>
<li><code>choco upgrade &lt;pkg&gt;</code></li>
<li><code>choco upgrade all</code></li>
</ul>

<h2>Links</h2>
<ul>
<li><a href="https://chocolatey.org/" rel="nofollow">Chocolatey</a></li>
<li><a href="https://chocolatey.org/packages">Chocolatey Packages</a></li>
</ul>


