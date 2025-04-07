# Shivansh
**#Assignment:4**
#Task:1
file=input("Enter the file name:")
if (file== "sample.txt"):
    file1= open('sample.txt','r')
    read= file1.readline()
    read1= file1.readline()
    print("Line 1:",read)
    print("Line 2:",read1)
    file1.close()

else:
    print("The file ",file ,"was not found.")
    

#Task:2
file= input("Enter the text write to the file:")
file1=open("Output.txt","w")
write_file=file1.write(file)
print("Data sucessfully written to Output.txt.")
file1.close()


append= input("Enter additional text to append:")
file1=open("Output.txt","a")
append_file=file1.write(append)
print("Data sucessfully appended.")
file1.close()



print("Final content of output.txt:")
file1=open("Output.txt","r")
read_file= file1.read()
print(read_file)
file1.close()
    
