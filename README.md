
# Yjs Demos [![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/yjs/yjs-demos)
> A starting point for your own ideas - PRs welcome

* Shared Editing using the [ProseMirror](http://prosemirror.net/) editor - [Open Directory](./prosemirror/)
* Shared Editing using the [ProseMirror](http://prosemirror.net/) editor with
  versioning support - [Open Directory](./prosemirror-versions/)
* Shared Editing using the [Dat Protocol](https://dat.foundation/) - [Open Directory](./prosemirror-dat/)
* Shared Editing using the [Quill](https://quilljs.com/) editor - [Open Directory](./quill/)
* Shared Editing using the
  [Atlassian Atlaskit](https://bitbucket.org/atlassian/atlaskit-mk-2/src/master/) editor - [Open Directory](./atlaskit/)
* Shared Editing using the [Monaco](https://microsoft.github.io/monaco-editor/)
  editor - [Open Directory](./monaco/)
* Shared Editing using the [CodeMirror](https://codemirror.net/)
  editor - [Open Directory](./codemirror/)
* Shared Editing using the [TipTap](https://tiptap.scrumpy.io/)
  editor - [Open Directory](./tiptap/)

## Getting Started

If you are new to Yjs and you just want to play around clone this repository and
use one of the demo directories that interests you the most.

```sh
git clone https://github.com/yjs/yjs-demos.git
cd yjs-demos/${demo-directory}
npm install
npm start
```

The demos use a public [`y-websocket`](https://github.com/yjs/y-websocket)
instance for communication. Try using one of the [other connection providers](https://docs.yjs.dev/ecosystem/connection-provider) or setting up
your own endpoint.

### (Un)License

The demos are released to the public domain - [Unlicense](./LICENSE).
