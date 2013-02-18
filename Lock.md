Lock the door
==

pass = "Your_password"    

print ("Lock Version 1")    
write "Password: "    
input = read()    
if input == pass then    
print ("Access Grantedfor 5 Secdons.")    
redstone.setOutput ("left", true)    
sleep(5)    
os.shutdown()       
else     
print ("Access Denied"!)     
sleep(2)    
os.shutdown()    
end    
