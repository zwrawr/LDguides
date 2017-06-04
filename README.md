# Ludum Dare Guides

## Overview
The purpose of the repo is to have a location where then user guides for the new Ludum Dare website can be easily collaborated on.

Checkout [Tree.md](tree.md) for a list of files in this repo.

## Contributing

### Setup
If your just making a small change, GitHub's online editor works quite well.

For larger changes, you'll need to fork/clone this repo and then download it.
Once you've downloaded it, you should run the following command to setup the project.

```bash
npm install
```

### Editing
Some things to remember when writing.

* These guides are intended to be 'official Ludum Dare' guides, try to make your writing style reflect this.
* A lot of these guides are intended for people who haven't been involved with Ludum Dare for long.
    They might well be read by people before there first LD!

### Testing

There two things you should do once you've completed your edits.

#### Proof read the files you've changed.
This is probably common sense, but you should reread you changes to make sure what you've written has made sense.

#### Run the test suite
Currently this is just a simple spell checker.
It's set to use an American English (`en-us`) dictionary.

You can run the test in the command line using the command below.
It should give you a color coded list of any spelling mistakes.
```
npm test
```

You can run the interactive version of the spellchecker using the following command.
```
npm run spellcheck
```

Correctly spelled works that are being reported as spelling mistakes should be added to the `.spelling` file.
It's likely that you'll have to add user names, company names, technological words and Ludum dare specific phrases.

Our test suite is also run via Travis CI
