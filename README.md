## Local Shellcode Process Injection

**Description**<br />
The process of injecting shellcode into a local process starts by allocating memory in the currentt process. The shellcode then needs to be moved to the allocated memory region, and finally, a thread needs to be created to execute the shellcode.
