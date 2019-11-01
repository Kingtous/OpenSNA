<!--
 * @Author: Kingtous
 * @Date: 2019-11-01 10:02:22
 * @LastEditors: Kingtous
 * @LastEditTime: 2019-11-01 10:40:53
 * @Description: Kingtous' Code
 -->
## OpenSNA

OpenSNA is a python toolkit to analyze social media interactions. The current implementation is a wrapper around NetworkX which is capable of doing higher order analytics on graph data. 

Run `pip install -r requirements.txt` to install dependencies for OpenSNA

### usage

1. configuration
- edit `main.py`
    - `.csv`
    - `g.link_predict(params_mlp, "MLP"` or `g.link_predict(params_mlp, "SVN")`
2. run
run `python3 main.py`
