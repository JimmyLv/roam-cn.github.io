- cc x
- 
- #42SmartBlock 测试
    - articles:
        - source::
        - link::
        - topics::
        - I am reading this to::
    - book:
        - author::
        - category::
        - highlight::
        - reading status:: {{or:to read | reading | read}}
        - published year::
    - 专栏
        - author::
        - source::
        - topics::
    - video
        - source::
        - topic::
        - author::
- 
- #@Jerry mermaid 去除背景
    - mermaid css
        ```css
.rm-mermaid{
  background: transparent !important;
  min-width: 0px !important;
}

.rm-mermaid .node rect{
  stroke: #2A496F !important;
}

.rm-mermaid div{
  color: #448889 !important;
  margin-right: 15px;
}

.rm-mermaid text{
  fill: #34A5A5 !important;
  font-size: 25px !important;
}

.rm-mermaid rect{
  fill: transparent !important;
  stroke-width: 0px !important;
}

.rm-mermaid tspan{
  fill: #438BE0 !important;
  font-size: 20px !important;
}```
    - 之前
        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2FRoamCN%2FHbH5PQatsx.png?alt=media&token=bae687ce-176e-42fa-bc60-c8d3d95b3fe6)
    - 之后
        - {{mermaid}}
            - graph TD;
                - A-->D;
                - A-->B
                - B-->D;
                - A-->C;
                - C-->D
