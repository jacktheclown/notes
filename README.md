# Noter

Write notes in the sidebar
/artifacts).

## Contribute

* Step 0: If you plan on sending a pull-request, you should fork the repository.
* Step 1: Clone the [notes](https://github.com/mozilla/notes) repository or your fork.
```
git clone https://github.com/mozilla/notes.git
# or
git clone https://github.com/[yourusername]/notes.git
```
* Step 2: Navigate to the root of the directory you cloned and run:
> Make sure to use Node.js 8+.

| Command         | Description                               |
|-----------------|-------------------------------------------|
| `npm install`   | Installs required Node.js dependencies.   |
| `npm run build` | Builds the application as a Web Extension.|
| `npm start`     | Launches Firefox with the Web Extension.  |

You can also open the `test/index.html` file in your browser to run the automated tests.

## WebExtension Permissions

| Permission      | Description                                                                    |
|-----------------|--------------------------------------------------------------------------------|
| `contextMenus`  | Used for "Send to Note" feature, sends text from pages to the Notes sidebar.   |
| `storage`       | Storage for Notes.                                                             |
| `identity`      | OAuth login to Firefox Accounts to sync your notes.                            |

## Release

See [RELEASE.md](https://github.com/mozilla/notes/blob/master/RELEASE.md) for release steps.

## Licenses

* [Mozilla Public License Version 2.0](LICENSE)
* [CKEditor Text Editor License](https://github.com/ckeditor/ckeditor5/blob/master/LICENSE.md) used under MPL licence

## Design

* Design for reference: https://mozilla.invisionapp.com/share/6VBUYHMRB#/281041484_Firefox_Notes
* Mobile design for reference: https://mozilla.invisionapp.com/share/BTGS26C2FE4

## Screenshot

![Notes v4](https://i.imgur.com/kOuI2uG.png)
