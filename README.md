<h2> WFA - A simple AUR helper written in a shell script </h2>

<p>wfa is an AUR helper written in Bash that is being developed to replace yaourt.</p>

<p>
    <a href="https://travis-ci.com/github/Hayao0819/wfa/">
        <img src="https://img.shields.io/travis/com/Hayao0819/wfa/master?style=flat-square">
    </a>
    <a href="https://github.com/Hayao0819/wfa/blob/master/LICENSE">
        <img src="https://img.shields.io/github/license/Hayao0819/wfa?style=flat-square">
    </a>
    <a href="https://github.com/Hayao0819/wfa/issues">
        <img src="https://img.shields.io/github/issues/Hayao0819/wfa?style=flat-square">
    </a>
    <a href="https://aur.archlinux.org/packages/wfa-git">
        <img src="https://img.shields.io/aur/version/wfa-git?style=flat-square">
    </a>
    <a href="https://github.com/Hayao0819/wfa/blob/master/wfa">
        <img src="https://img.shields.io/github/size/Hayao0819/wfa/wfa?style=flat-square">
    </a>
    <a href="https://github.com/Hayao0819/wfa">
        <img src="https://img.shields.io/tokei/lines/github/hayao0819/wfa?style=flat-square">
    </a>
    <a href="https://github.com/Hayao0819/wfa">
        <img src="https://img.shields.io/github/last-commit/Hayao0819/wfa?style=flat-square">
    </a>
    <a href="https://github.com/Hayao0819/wfa">
        <img src="https://img.shields.io/github/stars/Hayao0819/wfa?style=flat-square">
    </a>
</p>

<h3> WARNING </h3>
<p>
    <b>wfa is still in its infancy.</b>
    <b>Most features have not been implemented yet and are not stable.</b>
</p>

<h3> Install </h3>
Install <code>wfa-git</code> from AUR

<h3> Feature </h3>
<ul>
    <li>Written in a shell script.</li>
    <li>Designed for multiple languages</li>
    <li>Works with a single file</li>
    <!-- <li>Supports the same arguments as pacman</li> -->
</ul>


<h3> Screen shot </h3>
<p><img src="/images/install-google-chrome.png"></p>

<h3> Dependent packages </h3>
<ul>
    <li>sudo</li>
    <li>pacman</li>
    <li>jq</li>
    <li>python3</li>
    <li>curl</li>
    <li>pyalpm</li>
    <li>python-srcinfo</li>
</ul>

<h3> Todo </h3>
- `--search`の色付き出力
- `pacman`の全オペレーションの実装
- `pacman`の全オプションの実装
- `yay`の全オプションの実装
- `pacstrap`のサポート
- パッケージのビルドとインストールの順番を変更
