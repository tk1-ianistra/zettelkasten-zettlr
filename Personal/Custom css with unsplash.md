:root {
  --c-primary: #333333;
}

#editor * {
    font-family: 'Overpass', sans-serif;
    font-size:1.0em;
}

#editor .cm-header-1,
#editor .cm-header-2,
#editor .cm-header-3,
#editor .cm-header-4,
#editor .cm-header-5,
#editor .cm-header-6,
#editor .cm-formatting-header{
  color: var(--c-primary);
  font-family: 'JetBrains Mono', sans-serif;
  font-weight:600;
  font-size:1.25em;
}

#editor .CodeMirror-code .mute {    /* I have no idea what this does*/
    opacity: .6;
}

#editor .CodeMirror-code {
  	margin: 25px 0;
}

#editor {
    background-color: transparent;
    background-image: url('https://source.unsplash.com/featured/?library');
    background-size: cover;
    background-position: center center;
}

body #editor .CodeMirror-sizer {
    background-color: rgba(255, 255, 255, .93);
  	padding: 20px;
}

body #editor .CodeMirror-gutter{
  	height: 100%;
}

#editor .CodeMirror {
    background-color: transparent;
	margin: 50px 100px;
  	height: 675px;
}

/* I don't plan to use dark mode so didn't do anything with this */
body.dark #editor .CodeMirror-sizer, body.dark #editor .CodeMirror-gutter {  
    background-color: rgba(0, 0, 0, .8);
}

body #file-tree, body #file-list {
  background-color: white;
}

#editor .CodeMirror-scroll {
    padding-right: 30px;
}