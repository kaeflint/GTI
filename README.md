This repository contains the source code paper for our paper:  Gated Task Interaction Framework for Multi-task Sequence Tagging.   
We use the GLOVE word embedding which can be downloaded by using a simple downloader: https://github.com/chakki-works/chakin
## Figures
<img src="Figure_board.jpg" width="700" height="600"> 
<p>The basic form of the GTI architecture with a main-task <a href="https://www.codecogs.com/eqnedit.php?latex=$Y^m$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$Y^m$" title="$Y^m$" /></a> and one auxiliary task <img src="https://latex.codecogs.com/gif.latex?$Y^k$" title="$Y^k$" /> .</p>
<img src="tasks_2_mtl.jpg" width="700" height="600">
<p>
The GTI architecture with two auxiliary tasks sub-networks (<img src="https://latex.codecogs.com/gif.latex?\emph{AuxTask\textsuperscript{1}}" title="\emph{AuxTask\textsuperscript{1}}"/> and <img src="https://latex.codecogs.com/gif.latex?\emph{AuxTask\textsuperscript{2}}" title="\emph{AuxTask\textsuperscript{2}}"/>  generating the output labels <img src="https://latex.codecogs.com/gif.latex?$Y^1$" title="$Y^1$"/> and <img src="https://latex.codecogs.com/gif.latex?$Y^2$" title="$Y^2$"/> respectively) and a single main/target task sub-network (<img src="https://latex.codecogs.com/gif.latex?\emph{MT}" title="\emph{MT}"/>  generating the labels for the main Task <img src="https://latex.codecogs.com/gif.latex?$Y^m$" title="$Y^m$"/>).
</p>

## Dataset
