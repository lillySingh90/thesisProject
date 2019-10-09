# thesisProject
# client: front end with vueJS
# backend: mongoDB database server part in nodejs and RestAPI.
# prediction of cost part in python

# next step have to do
1- communication between all the three module. front and back is communicating. only prediction part communication is not done.
2- sending scripts like 
              id: which will be generate by mongo
              parameter: int
              name: addition
              code: var a=10, var b= 10, var c= a+b
             
            # so front end it should send the string lenght to the prediction part code and prediction will send to the front end (communication is not possible now)
   # End part is to integrate the monaco editor or any text highlighting editor in the newscripteditor.vue code. so in front end UI by clicking edit new script it should invoke the text editor.
   
   ## project is zipped and node module is also there so youjust haveto run in your system.
   
 # for client to run:
   $ cd client
   $ npm run serve
# for the server to be up
    $ cd cd .\Server\src\RestAPI\
    $ node app.js
  # for predition part
   $ python main.py
   
   
