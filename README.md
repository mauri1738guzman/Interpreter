# Interpreter
Interpreter for python using c++

# Running project 
1> Using visual studio, had to set certain arguments 
  * In the tasks.json file we added all objects under arguments already preset
      ex: args["Parser.obj",]
  * In the launch.json, we made sure to add the file we needed and -v if we wanted to debug
      ex: "args": ["./Testcases/input.txt", "-v"],
