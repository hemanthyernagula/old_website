# Head
> This is KeyNote continuation for keynote This is KeyNote continuation for keynote This is KeyNote continuation for keynote This is KeyNote continuation for keynote This is KeyNote continuation for keynote This is KeyNote continuation for keynote


Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it learn for themselves



```python

@app.route("/showme/<string:title>", methods=['GET'])
def showme(title):
    for i in os.listdir("blogs"):
        -if str(i).split(".")[0] == title:
            html_code = mdtohtml(os.path.join(app.root_path+"/blogs/"+i))
        else:
            print("not Found")
    # index = [i for i,blog in enumerate(blogs) if blog['title']==title]
        # html_code = mdtohtml(os.path.join(app.root_path+"/blogs/"+blogs[index[0]]['title']+".md"))
    
    return render_template('showme.html',html_code=html_code)

```


# Head2
## SubHead
* * item
* item
    * item
    * item
    * item
        * item
        * item
        * item
            1. item
            2. item
    
* item

1. Booooks 
2. Books 
3. Books

[title](https://www.example.com) :joy:


<img src="/static/pics/nn.svg" width=300 >



***





paragraph