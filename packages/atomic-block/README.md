# djs@atomic-block - Not released, please use with caution ;)

[![NPM](https://img.shields.io/npm/v/@djsp/atomic-block.svg)](https://www.npmjs.com/package/@djsp/atomic-block) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)


Example:

```jsx
<EditorContainer>
  <Editor />

  <AtomicBlock type="IMAGE">
    {(props) => <Image {...props} />}
  </AtomicBlock>

  <AtomicBlock type="VIDEO">
    {(props) => <Video {...props} />}
  </AtomicBlock>
</EditorContainer>
```
