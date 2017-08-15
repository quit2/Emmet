## Emmet
Emmet (前身为 Zen Coding) 是一个能大幅度提高前端开发效率的一个工具。

### 使用(tab键)
- 后代：>

    缩写：nav>ul>li*5
    
        <nav>
            <ul>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
            </ul>
        </nav>

- 兄弟: +

  缩写：div+p+ul>li
  
        <div></div>
        <p></p>
        <ul>
            <li></li>
        </ul>

- 上级: ^

    缩写：div+div>p>span+em^bq
    
        <div></div>
        <div>
            <p><span></span><em></em></p>
            <blockquote></blockquote>
        </div>
        
    缩写：div+div>p>span+em^^bq
    
        <div></div>
        <div>
            <p><span></span><em></em></p>
        </div>
        <blockquote></blockquote>

- 分组: ()

    缩写：div>(header>ul>li*2>a)+footer>p
    
        <div>
            <header>
                <ul>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                </ul>
            </header>
            <footer>
                <p></p>
            </footer>
        </div>
    
    缩写：(div>dl>(dt+dd)*3)+footer>p
    
        <div>
            <dl>
                <dt></dt>
                <dd></dd>
                <dt></dt>
                <dd></dd>
                <dt></dt>
                <dd></dd>
            </dl>
        </div>
        <footer>
            <p></p>
        </footer>

- 乘法: *
   
    缩写：ul>li*5

        <ul>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
        </ul>

- 自增符号: $

    缩写：ul>li.item$*5
    
        <ul>
            <li class="item1"></li>
            <li class="item2"></li>
            <li class="item3"></li>
            <li class="item4"></li>
            <li class="item5"></li>
        </ul>

    缩写：h$[title=item$]{Header $}*3
    
        <h1 title="item1">Header 1</h1>
        <h2 title="item2">Header 2</h2>
        <h3 title="item3">Header 3</h3>
        
    缩写：ul>li.tem$$$*5
    
        <ul>
            <li class="tem001"></li>
            <li class="tem002"></li>
            <li class="tem003"></li>
            <li class="tem004"></li>
            <li class="tem005"></li>
        </ul>
    
    缩写：ul>li.item$@-*5
    
        <ul>
            <li class="item5"></li>
            <li class="item4"></li>
            <li class="item3"></li>
            <li class="item2"></li>
            <li class="item1"></li>
        </ul>
    
    缩写：ul>li.item$@3*5
    
        <ul>
            <li class="item3"></li>
            <li class="item4"></li>
            <li class="item5"></li>
            <li class="item6"></li>
            <li class="item7"></li>
        </ul>
    
- ID和类属性

    缩写：#header
    
        <div id="header"></div>
    
    缩写：.title
    
        <div class="title"></div>
    
    缩写：form#search.wide
    
        <div id="search" class="wide"></div>
    
    缩写：p.class1.class2.class3
    
        <p class="class1 class2 class3"></p>
    
- 自定义属性

    缩写：p[title="Hello"]
  
        <p title="Hello"></p>
  
    缩写：td[rowspan=2 colspan=3 title]
  
        <td rowspan="2" colspan="3" title=""></td>
        
    缩写：[a='value1' b='value2']
    
        <div a="value1" b="value2"></div>

- 文本: {}

    缩写：a{Click me}
   
        <a href="">Click me</a>
        
    缩写：p>{Click }+a{here}+{ to continue}
    
        <p>Click <a href="">here</a> to continue</p>
   
- 隐式标签
    
    缩写：.class

        <div class="class"></div>
        
    缩写：table>.row>.col
    
        <table>
            <tr class="row">
                <td class="col"></td>
            </tr>
        </table>

- 
    缩写：ul.generic-list>lorem10.item*4

        <ul class="generic-list">
            <li class="item">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid, quisquam.</li>
            <li class="item">Inventore quisquam aliquam dignissimos, harum sequi tempore unde soluta veritatis?</li>
            <li class="item">Provident accusamus voluptatibus voluptates repellendus, est! Iste dolorum ad delectus?</li>
            <li class="item">Officia nam magnam tempore provident, debitis tenetur alias a vel.</li>
        </ul>
        
- html

    缩写：!
    
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <title>Document</title>
        </head>
        <body>
            
        </body>
        </html>
    
    缩写：a
    
        <a href=""></a>
    
    缩写：a:link
    
        <a href="http://"></a>
        
    缩写：a:mail
    
        <a href="mailto:"></a>
        
    缩写：link
    
        <link rel="stylesheet" href="">
        
    缩写：link:favicon
    
        <link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
        
    缩写：meta:utf
    
        <meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
        
    缩写：img
    
        <img src="" alt="">
        
    缩写：form
    
        <form action=""></form>
        
    缩写：form:get
    
    <form action="" method="get"></form>
    
    缩写：input:text
    
        <input type="text" name="" id="">
    
    缩写：input:r
    
        <input type="radio" name="" id="">
