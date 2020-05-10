/* Enter your custom CSS here */
body.dark #editor {
background-color: #21212b;
}
body.dark .cm-zkn-tag, body.dark .cm-zkn-id, body.dark .cm-zkn-link {
color: #aeafdc;
}
body.dark .cm-quote, body.dark .cm-link, body.dark .cm-strong, body.dark .cm-em {
color: #94c7ea;
}
body.dark #preview {
background-color: #353546;
color: #fff;
box-shadow: inset -14px 2px 54px -23px rgba(0,0,0,0.5);
margin-top: 1px;
font-size: 1em;
}
body.dark #preview ul .selected {
background-color: #21212b !important;
border-left: 5px solid #df5d33;
font-weight: bold;
color: #df5d33 #fff !important;
}
body #preview ul li {
background-color: #353546 !important;
box-shadow: inset -14px 2px 54px -23px rgba(0,0,0,0.5);
border-top-color: #444;
border-bottom-color: #444;
height: 60px;
color: #fff !important;
}
body.dark #preview ul li.directory, body.dark #preview ul li.virtual-directory {
background-color: #030304;
color: white;
font-weight: bold;
}
body #preview ul li p.file-meta .date,
body #preview ul li p.file-meta .id,
body #preview ul li p.file-meta .tags {
color: #fff !important;
background-color: #000 !important;
box-shadow: 0px 0px 70px -15px rgba(255,255,255,0.55) !important;
}
#preview ul li p.filename {
font-weight: 500;
}
.file.file-meta.ui-draggable.ui-draggable-handle p.filename {
color: #fff !important;
}
.CodeMirror .cm-escape-char,
.CodeMirror .cm-formatting-code,
.CodeMirror .cm-formatting-code-block,
.CodeMirror .cm-formatting-em,
.CodeMirror .cm-formatting-quote,
.CodeMirror .cm-formatting-strong {
opacity: .3;
display: none;
}
body.dark #preview ul li p.file-meta .directories {
background-color: #b75a3d;
}
.CodeMirror .CodeMirror-sizer {
margin-left: 30px;
border-right-width: 30px;
padding-right: 30px;
}