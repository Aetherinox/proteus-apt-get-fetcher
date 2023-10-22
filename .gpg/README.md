<p align="center"><img src="https://raw.githubusercontent.com/Aetherinox/proteus-app-manager/main/docs/images/readme/banner_02.png" width="860"></p>
<h1 align="center"><b>Proteus Apt Git</b></h1>
<h3 align="center"><b>📁 .gpg</b></h3>

<div align="center">

</div>

<br />
<br />

## About
The `.gpg` folder allows you to drop your own `*.gpg` binary key inside and have Proteus Apt Git automatically import that key the next time you launch the script.

To specify the primary GPG key you wish to use when signing your repo packages, create or open the `secrets.sh` file in the root directory of your proteus-git folder and add a `GPG_KEY` value.

```shell
export GPG_KEY=ABCD1234
```

<br />

---

<br />

## Example Structure
```
📁 proteus-git
   📁 .gpg
      📄 yourkey.gpg
```