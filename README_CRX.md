# Requirements.txt 
  Requirements.txt was updated and version of packages was specified.

# Error  
 When running the program, you may see errors:    
  TypeError: Descriptors cannot not be created directly.
    If this call came from a _pb2.py file, your generated code is out of date and must be regenerated with protoc >= 3.19.0.
    If you cannot immediately regenerate your protos, some other possible workarounds are:
   1. Downgrade the protobuf package to 3.20.x or lower.
   2. Set PROTOCOL_BUFFERS_PYTHON_IMPLEMENTATION=python (but this will use pure-Python parsing and will be much slower). 

You can reinstall protobuf package in the virtual environment.
> pip install protobuf==3.19.0


