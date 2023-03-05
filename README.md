[![License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/CLLPCH/react-nglviewer/blob/main/LICENSE)
[![Changelog](https://img.shields.io/badge/changelog--lightgrey.svg?style=flat)](https://github.com/CLLPCH/react-nglviewer/blob/main/CHANGELOG.md)
[![npm version](https://img.shields.io/npm/v/react-nglviewer)](https://www.npmjs.com/package/react-nglviewer)

# React NGLViewer Component

A React component designed to display and interact with molecular structures using [NGL](https://github.com/nglviewer/ngl) library, providing a visually appealing and user-friendly interface for scientific research and education.

一個 React 元件，使用 [NGL](https://github.com/nglviewer/ngl) 來顯示分子結構。

## Features

* Display molecular structures
* Check our [Discussion](https://github.com/CLLPCH/react-nglviewer/discussions) for a list of proposed features

## Installation

The react-nglviewer library is available as an NPM package. Install it either with NPM:

```
npm install --save react-nglviewer
```

or Yarn:

```
yarn add react-nglviewer
```

## Usage

A minimal example of using react-nglviewer is as follows:

```

import React from 'react';
import { ReactNglViewer } from 'react-nglviewer';

function App() {
  return (
    <div className="App" style={{ width: '100%', height: '800px' }}>
      <ReactNglViewer fileName="1crn.cif" filePath="rcsb://1crn" />
    </div>
  );
}

export default App;

```

- fileName (required) Format detection is based on the file extension.
- filePath (required) A URL or an object containing the file data.

## License

Distributed under the MIT License.

## Credits

[NGL](https://github.com/nglviewer/ngl)

* AS Rose, AR Bradley, Y Valasatava, JM Duarte, A Prlić and PW Rose. NGL viewer: web-based molecular graphics for large complexes. Bioinformatics: bty419, 2018. doi:10.1093/bioinformatics/bty419
* AS Rose and PW Hildebrand. NGL Viewer: a web application for molecular visualization. Nucl Acids Res (1 July 2015) 43 (W1): W576-W579 first published online April 29, 2015. doi:10.1093/nar/gkv402
