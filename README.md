#About
I created this template to make my website using Flask, thought it would be useful to have a "blank" template version to create new webpages. I followed Corey Schafer's Flask Tutorials on youtube.
    [source](https://youtu.be/cYWiDiIUxQc)

##It comes with a bootstrap links
##It has a templating system from Flask for html 


[Bootstrap](https://getbootstrap.com/docs/4.1/getting-started/download/)

#What you'll need to change:
1. The name of the file
2. The flaskTemplate.py file
3. In your cli rename by using the following command, changing the filename.py, set FLASK_APP=fileName.py, for mac export FLASK_APP=filename.py
4. It is set in debug mode with the following code:
   if __name__ == '__main__':
    app.run(debug=True)

It should be updated to the following:
    if __name__ == '__main__':
    app.run(debug=True, use_evalex=False)
    [source](https://stackoverflow.com/questions/21345221/whats-the-best-way-to-disable-the-default-console-route-in-flask-debug-mode)

also, in your cli, set FLASK_DEBUG=development
5. Flask run in your cli then go to a web browser http://localhost:5000 , to run locally

