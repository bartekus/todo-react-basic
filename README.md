Basic React.js ToDo App
======

Basic (**React.js**) (sticky-notes style) To Do App

#### Screenshot

![Screenshot software](https://raw.githubusercontent.com/Bartekus/todo-js-basic/master/todo-react-basic.png "screenshot software")

## Synopsis

Just a basic react with draggable sticky-notes like to do's.

## Code Example

```
renderForm: function() {
    return (
        <div className="note" style={this.style}>
        <textarea ref="newText" defaultValue={this.props.children}
        className="form-control"></textarea>
        <button onClick={this.save} className="btn btn-success btn-sm glyphicon glyphicon-floppy-disk" />
        </div>
        )
},
```

## Motivation

Learning react.js techniques and patterns.

### Directory Layout

```
.
├── /build/              # Build directory
│   ├── /Board.js        # Board class
│   ├── /main.js         # Main app
│   └── /Note.js         # Note class
├── /css/                # CSS folder
│   └── /style.css       # Basic CSS stylesheet
├── /js/                 # JavaScript folder
│   ├── /Board.js        # Board class source
│   ├── /main.js         # Main app source
│   └── /Note.js         # Note class source
├── /node_modules        # Dependancies source
├── .gitignore           # Version control omission file
├── index.html           # Main entry point
├── package.json         # Dependencies management file
├── README.md            # This file
└── todo-react-basic.png # Picture
```

## Installation

Checkout this repo, install dependencies, then open index file with the following:

```
  > git clone git@github.com:Bartekus/todo-react-basic.git
  > cd todo-react-basic
  > npm install
  > open index.html
```

## Usage

Use to add/edit/delete tasks without persistence (no backend).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

0.1.0 Finalized the example

## Tests

Basic non-automated manual browser test aka no test :P

## Contributors

Standing on the shoulders of all the giants before me.

## Contact
#### Bartek Kus
* Homepage: http://bartekus.com
* E-mail: bartekus@gmail.com
* Twitter: [@Bartekus](https://twitter.com/Bartekus "Bartekus on twitter")

## License

Copyright (c) 2015 Bartek Kus

Licensed under the MIT license
