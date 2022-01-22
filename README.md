# cugbthesis

A LaTeX template for Master/Ph.D. theses of China University of Geosciences, Beijing.

中国地质大学（北京）硕/博学位论文 LaTeX 模板。

本模板从 [silverriver/CUGBthesis](https://github.com/silverriver/CUGBthesis) 的基础上魔改而来，参考文献调用 [biblatex-gb7714-2015](https://github.com/hushidong/biblatex-gb7714-2015) 宏包处理，符合《地大北京硕/博士学位论文书写指南 2021 版》的格式要求。硕士学位论文与博士学位论文除了封面与页眉以外，格式要求完全相同。虽然本人使用该模板通过了格式审查，但不能保证与 word 模板完全一致，请自行检查。

编译环境：TeX Live 2021

编译顺序：xelatex -> biber -> xelatex -> xelatex
或者 latexmk -> xelatex
