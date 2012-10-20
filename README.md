Xcode Licensed Templates
------------------------

**Minimal Xcode Templates for Open Source Developers**

Xcode means well with all of its file templates and autocomplete fanciness. But more often than not, it just gets in the way, and generates dozens of lines of code that you'll delete anyway. 

These templates start your code off on the right foot: attribution and license in the header, followed by import statements and `@interface` / `@implementation`.

Select from your favorite open source licenses to be embedded in the header:

- [MIT](http://opensource.org/licenses/mit-license)
- [Apache 2.0](http://opensource.org/licenses/Apache-2.0)
- [BSD 3-Clause](http://opensource.org/licenses/BSD-3-Clause)
- [GNU General Public License, version 2 (GPL-2.0)](http://opensource.org/licenses/GPL-2.0)
- [Zlib](http://opensource.org/licenses/Zlib)

> Is your license of choice missing? Feel free to send a pull request!

## Installation & Usage

- Create a new directory in `/Library/Developer/Xcode/Templates/Application/File\ Templates` called `Licensed`.
- Copy the contents of the "File Templates" directory of this repository into `Licensed`. 
- Relaunch Xcode and select "File > New File", or use the `⌘N` keyboard shortcut.
- Select the "Licensed" category, then select the "Licensed Objective-C Class" template, and hit "Next".
- Enter the name of your class and select the desired license.

![Step 1](https://raw.github.com/mattt/Xcode-Licensed-Templates/screenshots/xcode-template-step-1.png)

![Step 2](https://raw.github.com/mattt/Xcode-Licensed-Templates/screenshots/xcode-template-step-2.png)


## Contact

Mattt Thompson

- http://github.com/mattt
- http://twitter.com/mattt
- m@mattt.me

## License

Xcode Licensed Templates is available under the MIT license. See the LICENSE file for more info.
