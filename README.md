# 13. Docker. Lading                                                                                                                                                                          
========

### Create a Docker file of any Python application                                                                                                                                            

```python 

from flask import Flask                                                                                                                                                                                                                                                                                                                                                                     
app = Flask(__name__)                                                                                                                                                                           
@app.route("/")                                                                                                                                                                               
def hello():                                                                                                                                                                                        
    return "hello word \n"                                                                                                                                                                    
if __name__ == "__main__":                                                                                                                                                                           
    app.run(host="0.0.0.0", port=int("5000"), debug=True)                                                                                                                                                                                                                                                                                                                                   

```                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       
### Add automated build for that image Docker hub                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
### Test it                                                                                                                                                                                                                                                                                                                                                                                 
### Send/receive API request     
