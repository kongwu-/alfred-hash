Hash for Alfred 4+
============

A simple Alfred 2 hash workflow's.

Release Node
----------------
- 2022/02/14 - **[v1.4]** Fixed a bug that didn't work on newer versions of macos

Installation
----------------

- Download the workflow [directly](https://github.com/kongwu-/alfred2-hash/raw/master/Hash.alfredworkflow) or from [Packal](http://www.packal.org/workflow/hash).
- Double click the downloaded "Hash.alfredworkflow" file to install.
- `brew install php`

*Alfred 2 and Powerpack is required*


Instructions
----------------

### String-based hashing

- md5 `<string>`
- sha1 `<string>`
- sha256 `<string>`
- sha512 `<string>`
- htpasswd `<string>`
- crc32 `<string>`
- whirlpool `<string>`
- base64_decode `<string>`
- base64_encode `<string>`

### File-based hashing

You can get a hash from a file in 2 ways:

* Navigate to the file in Alfred box then select the desired algorithm from the File Actions menu:

* Select the file in Finder, launch Alfred and type one of the following commands:

  - md5f
  - sha1f
  - sha256f
  - sha512f
  - base64f
  
