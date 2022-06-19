# LYOJ Extension Packages

| Extension                                                    | Version | Link                                        |
| ------------------------------------------------------------ | ------- | ------------------------------------------- |
| PHPMailer/PHPMailer                                          | 6.6.0   | https://github.com/PHPMailer/PHPMailer      |
| Semantic-Org/Semantic-UI                                     | 2.4.1   | https://github.com/Semantic-Org/Semantic-UI |
| pandao/editor.md (Modified by [@LittleYang0531](https://github.com/LittleYang0531)) | 1.6.0   | https://github.com/pandao/editor.md         |
| highlightjs/highlight.js                                     | 11.4.0  | https://github.com/highlightjs/highlight.js |
| jquery/jquery                                                | 3.6.0   | https://github.com/jquery/jquery            |
| KaTeX/KaTeX                                                  | 0.15.2  | https://github.com/KaTeX/KaTeX              |
| layui/layui                                                  | 2.6.8   | https://github.com/layui/layui              |
| microsoft/monaco-editor                                      | 0.31.1  | https://github.com/microsoft/monaco-editor  |

Note that the author [@pandao](https://github.com/pandao) of [editor.md](https://github.com/pandao/editor.md) didn't update this repository for a long time (last update 2015.1.9 for version 1.5.0). We fixed some bugs that appear in the original repository, and make its version number become 1.6.0. Here are some bugs that we fixed: 

1. Update the parsing format for inline-formulas and interline-formulas
2. Fixed the error that appear HTML tags when parsing formulas
3. Open all the options that [editor.md](https://github.com/pandao/editor.md) provide
4. Fixed the error when loading plugins and displaying Emoji
5. Fixed the error that some special characters are escaped when parsing formulas
5. Disable the autoload feature

We didn't ensure that all the extensions are the latest updated. You can download the latest releases from the original repository and update the `config.json` to use the latest extension. But attention to the compatibility of the extensions, your change to the project may cause some errors.