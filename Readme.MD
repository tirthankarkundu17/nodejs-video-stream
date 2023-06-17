# NodeJS Video Streaming Server
NodeJS Video Streaming server

# How it works
The client sends headers with range to request part of file and display it in client side.
The chunk side set if of 1MB but we can hypertune this number.

# Future Scope
Currently a sample file resides in server itself but we can leverage S3 and dynamically select video files.