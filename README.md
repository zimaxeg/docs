# MindSpore Documents

![MindSpore Logo](resource/MindSpore-logo.png)

## Overview

This project provides the source files of the installation guide, tutorials, and other documents, as well as API configurations on the MindSpore official website <https://www.mindspore.cn>.

## Contributions

You are welcome to contribute documents. If you want to contribute documents, read the [CONTRIBUTING_DOC.md](./CONTRIBUTING_DOC.md). Please comply with the document writing specifications, and submit documents according to the process rules. After the documents are approved, the changes will be displayed in the document project and on the official website.

If you have any comments or suggestions on the documents, submit them in Issues.

## Directory Structure Description

```
docs
├───api // Configuration files for API generation.
│      
├───docs // Introduction to documents.
│       
├───install // Installation guide.
│      
├───resource // Resource-related documents.
│      
├───tutorials // Tutorial-related documents.
│      
└───README.md // Docs repository description.
```

## Document Construction

MindSpore tutorials and API documents can be generated by [Sphinx](https://www.sphinx-doc.org/en/master/). The following uses the API document as an example to describe the procedure.

1. Download code of the MindSpore Docs repository.
   ```shell
   git clone https://gitee.com/mindspore/docs.git
   ```
2. Go to the docs directory and install the dependency items in the ```requirements.txt``` file.
   ```shell
   cd docs/api
   pip install -r requirements.txt
   ```
3. Run the following command in the docs directory to create the build_zh_cn/html directory that stores the generated document web page. You can open ```build_zh_cn/html/index.html``` to view the API document.
   ```
   make html
   ```

## License

- [Apache License 2.0](LICENSE)
- [Creative Commons License version 4.0](LICENSE-CC-BY-4.0)
