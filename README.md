[![Known Vulnerabilities](https://snyk.io//test/github/Yash-Handa/pbiny/badge.svg?targetFile=package.json)](https://snyk.io//test/github/Yash-Handa/pbiny?targetFile=package.json)
[![Total alerts](https://img.shields.io/lgtm/alerts/g/Yash-Handa/pbiny.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Yash-Handa/pbiny/alerts/)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/Yash-Handa/pbiny.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Yash-Handa/pbiny/context:javascript)

# pbiny

A Node.js CLI to interact with Pastebin directly from the terminal

## Sample pics

### up -f

<div>
  <img alt="up -f" title="Demo of up command with -f option" src="/Readme_Content/pbin_up_f.png">
</div><br>

### up -t

<div>
  <img alt="up -t" title="Demo of up command with -t option" src="/Readme_Content/pbin_up_t.png">
</div><br>

### up

Launches an instance of the users preferred editor on a temporary file. Once the user exits their editor, the contents of the temporary file are read in as the result. The editor to use is determined by reading the $VISUAL or $EDITOR environment variables. If neither of those are present, notepad (on Windows) or vim (Linux or Mac) is used.

Works great with cli test editors like **nano** and **vim**

<div><br>
  <img alt="up" title="Demo of up command without options" src="/Readme_Content/pbin_up.png">
</div><br>

### up -t (if editor didn't work)

If the editor does not work or returns nothing to create a paste then an option of entering data (multi-line) will pop-up.

**Note:** you cannot edit the previous lines in this option.

<div>
  <img alt="up" title="Demo of up command when editor does not work" src="/Readme_Content/pbin_up_err.png">
</div><br>