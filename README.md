# Windows-Network---Unauthenticated

### When a Windows PC displays “unauthenticated” after network name and has issues connecting to domain controller.

# Instructions
Open Powershell as Admin

Reset-ComputerMachinePassword -Credential MYDOMAIN\SomeDomainAdminAccount

Enter domain admin credentials

Restart PC
