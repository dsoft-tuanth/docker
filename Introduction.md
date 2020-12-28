# Introduction to Docker

# 1: Containerlization
- __What is the server model?__
>> physical server + operating system + application.

![image](https://viblo.asia/uploads/19a271ca-f444-4bd5-b04a-f1b9c5ce10fd.png)
>> - ___limitations of the server model___
>> >> Even if you have a huge hard drive and a big ram, you won't take full advantage of it.

>> >>   a server has only one os (operating system) => virtualization.

- __what is the virtualization__ 
>>  One server can install multiple os.

![image](https://viblo.asia/uploads/f83e4a3a-bc95-4a4d-af37-dbaa9e03d28f.png);

>> ex: 
>> >> Virtualbox or VMware

>> - ___limitations of the virtualization___
>> >> - resources

>> >> >> - need to configure to provide the hard drive and ram resources from the real machine to the virtual machine from the start.
>> >> >> - Turn on the virtual machine and leave it to do nothing, the real machine cannot reuse the given resource
>> >> >> - waste of resources
>> >> - time
>> >> >> The virtual machine startup and shutdown take a long time, possibly up to several minutes.

- __what is the  containerlization__
>> - On one physical server, we can install multiple virtual machines, but these machines share the parent's kernel and share the parent machine's resources.
>> - Much resources need to provide as much should avoid wasting resources.

# 2: Container
>> The softwares and programs will be packed into containers by "Container Engine"
- __what is the container__
>> >> It is a solution for reliable software transfer between different computer environments
- __create container__
>> - Create an environment that contains everything the software needs to run
>> - Not affected by factors related to the system environment.
>> - Not affect the rest of the system

>> Processes in a container are isolated from processes of other containers on the same system, but all these containers share the host OS kernel

>> It is an open platform for programmers and sysadmins to make building, transferring, and running applications easier.
- __Advantages container__
>> - flexibility: Deploy anywhere due to the application's dependence on the OS layer as well as on the infrastructure removed.
>> - Fast: Due to the shared host OS, containers can be created almost instantly. This is different from vagrant - which creates a virtual environment at the hardware level, so it takes longer to boot
>> - less Ram memory: The container also uses the same images so it does not cost many disks.
>> - homogenization: When multiple people develop on the same project, there is no environmental difference
>> - Pack: It is possible to hide the environment including the app in a package called a container. Can test containers. Dumping or rebuilding containers is very easy
- __limitations of the container__
>> - safe
>> >> Due to the sharing of the OS, if there is a hole in the kernel of the host OS, it will affect all the containers contained in the host OS.

>> >> it's easy to be hacked permission superuser

=> _docker_







