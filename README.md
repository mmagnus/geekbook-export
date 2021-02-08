# Geekbook export
Table of Contents
=================

* [Geekbook export](#geekbook-export)
  * [Create a new github repository](#create-a-new-github-repository)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

## Create a new github repository
Go to https://github.com/new and type a name of your new repository, e.g., geekbook-export (you can make it public if you want, but then everyone can see your export, so mind that).

Go to a place where you want to keep your repo (/Users/magnus/Desktop/) and run

	(py37) [mx] Desktop$ git clone git@github.com:mmagnus/geekbook-export.git
	Cloning into 'geekbook-export'...
	warning: You appear to have cloned an empty repository.

Now, go to `geekbook/engine` and run  `page.py`:

	python page.py /Users/magnus/Desktop/geekbook-export geekbook-export.md --add-toc --push


