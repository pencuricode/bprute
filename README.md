<h1>Bprute</h1>
<p><a href="https://github.com/penecuriCode/bprute"><img src="https://img.shields.io/badge/bprute-1.2-brightgreen.svg" alt="Version" data-canonical-src="https://img.shields.io/badge/penecuriCode-2.1-brightgreen.svg?maxAge=259200" style="max-width:100%;"></a>
<a href="https://github.com/penecuriCode/bprute"><img src="https://img.shields.io/badge/Release-Stable-orange.svg" alt="Stage" data-canonical-src="https://img.shields.io/badge/Release-Stable-orange.svg" style="max-width:100%;"></a>
<a href="https://github.com/penecuriCode/bprute"><img src="https://img.shields.io/badge/Supported%20OS-Linux%2FWindows-brightgreengreen.svg" alt="Build" data-canonical-src="https://img.shields.io/badge/Supported%20OS-Linux%2FWindows-brightgreengreen.svg" style="max-width:100%;"></a></p>
<p> Brute Force Tool 🔓 WordPress , Joomla , DruPal , OpenCart , Magento </p>

<h2>Bprute</h2>

<img src="https://github.com/penucuriCode/bprute/blob/main/result.PNG" data-canonical-src="https://github.com/penucuriCode/bprute/blob/main/result.PNG" style="max-width:100%;">

<h2>Simple brute force script </h2>

[1] WordPress (Auto Detect Username)<br>
[2] Joomla<br>
[3] DruPal<br>
[4] OpenCart (belum tersedia)<br>
[5] Magento<br>
[6] All (Auto Detect CMS)<br>

<h2>Usage</h2>

<table>
<thead>
<tr>
<th>Short Form</th>
<th>Long Form</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>-l</td>
<td>--list</td>
<td>websites list</td>
</tr>
<tr>
<td>-p</td>
<td>--passwords</td>
<td>Passwords list</td>
</tr>
</tbody></table>
<h2>Example</h2>
<code>perl bprute.pl -l list.txt -p passwords.txt</code>
<br>

## Installation [Linux](https://wikipedia.org/wiki/Linux) [![alt tag](http://icons.iconarchive.com/icons/dakirby309/simply-styled/32/OS-Linux-icon.png)](https://fr.wikipedia.org/wiki/Linux)

```bash
git clone https://github.com/penucuriCode/bprute.git
cd bprute
perl bprute.pl -l list.txt -p passwords.txt 
```

## Installation [Android](https://wikipedia.org/wiki/Android) [![alt tag](https://cdn1.iconfinder.com/data/icons/logotypes/32/android-32.png)](https://fr.wikipedia.org/wiki/Android)

Download [Termux](https://play.google.com/store/apps/details?id=com.termux)

```bash
cpan install LWP::UserAgent
cpan install HTTP::Request
git clone https://github.com/penucuriCode/bprute
cd bprute
perl bprute.pl -l list.txt -p passwords.txt 
```

## Installation [Windows ](https://wikipedia.org/wiki/Microsoft_Windows)[![alt tag](http://icons.iconarchive.com/icons/tatice/cristal-intense/32/Windows-icon.png)](https://fr.wikipedia.org/wiki/Microsoft_Windows)
```bash
Download Perl
Download bprute
Extract bprute into Desktop
Open CMD and type the following commands:
cd Desktop/bprute-master/
perl bprute.pl -l list.txt -p passwords.txt 
```
<h2>Version</h2>
<strong>Current version is 2.1</strong>
<strong>What's New (apa yang terbaru) </strong>
<p>• speed up<p>
<p>• Bug fixes<p>
