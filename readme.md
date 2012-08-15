# PhpStorm Live Templates



## Installation

First, find your configuration folder.

- Windows: <your home directory>\.WebIde<version>\config
- Linux: ~\.WebIde<version>\config
- MacOS: ~/Library/Preferences/WebIde<version>

On my linux, it would be <code>~/.WebIde50/config</code> so you have to adjust commands to your platform. There is a <code>templates/</code> directory. It contains XML files with Live Templates.

If you don't have your own templates yet, there would be no files. So you can remove it and clone new one.

	$ cd ~/.WebIde50/config/
    $ rm -r templates/
    $ git clone https://github.com/HosipLan/phpstorm-livetemplates templates

If you have your own templates try creating a git repository and pull templates.

	$ cd ~/.WebIde50/config/templates/
	$ git init
	$ git remote add origin git://github.com/HosipLan/phpstorm-livetemplates.git
	$ git pull origin master

If this wouldn't work. You should just backup your templates, clone the repo and merge them manually.



## PHP Templates

### pri, pro, pub

Private, protected and public method

### con

Constructor, that calls parent

### thr

Throw expression

### try

Surround code with <code>try {}</code> expression

### sta

Static function



## Nette Templates

### com

Nette component factory

### inj

Inject function for Nette presenter

### sig

Signal method of Nette PresenterComponent

### att

Attached event on Nette component.

### obj

Code for including Nette\ObjectMixin into current class



## PHPUnit Templates

### test

Default empty test function for PhpUnit (todo: more)
