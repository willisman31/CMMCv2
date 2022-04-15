# Comprehensive Requirements
## List of Requirements
Listed below are the mandated requirements under CMMCv2 level 1 along with brief explanations of each item.
- Limit information system access to authorized users, processes acting on behalf of authorized users, or devices (including other information systems).
	- The basic requirement here is that FCI is only accessible by those with permission.  
- Limit information system access to the types of transactions and functions that authorized users are permitted to execute.
	- Only the actions that permitted users may take are allowed to operate within the system; this is kind of a way of specifying least privilege as it relates to execution of functions on FCI.
- Verify and control/limit connections to and use of external information systems.
	- Monitor and secure access to external systems; secure your network and only allow traffic to trusted domains.
- Control information posted or processed on publicly accessible information systems.
	- Keep your secure information secure; don't let controlled information be processed or transmitted on untrusted systems.
- Identify information system users, processes acting on behalf of users, or devices.
	- Know who is using your system and how.
- Authenticate (or verify) the identities of those users, processes, or devices as a prerequisite to allowing access to organizational information systems.
	- Force some kind of sign in before allowing access to controlled information.
- Sanitize or destroy information system media containing FCI before disposal or release for reuse.
	- Before disposing of any storage device that held FCI, make sure that the FCI is not recoverable; this goes beyond smashing hard drives, make sure that papers that held FCI are shredded or incinerated so they cannot be recovered.
- Limit physical access to organizational information systems, equipment, and the respective operating environments to authorized individuals.
	- Make sure that not just anybody can walk into your facilities- lock doors and file cabinets, make sure that FCI isn't left unattended in public spaces.
- Escort visitors and monitor visitor activity; maintain audit logs of physical access; and control and manage physical access devices.
	- Make sure that when people are allowed physically close to your FCI, that you are keeping record of it- this could be as simple as a sign-in log on a clipboard by the door.
- Monitor, control, and protect organizational communications (i.e., information transmitted or received by organizational information systems) at the external boundaries and key internal boundaries of the information systems.
	- Monitor and regulate network traffic at the gateway and switches within the network.
- Implement subnetworks for publicly accessible system components that are physically or logically separated from internal networks.
	- Create two networks, one for visitors, one for employees and FCI.
- Identify, report, and correct information and information system flaws in a timely manner.
	- Patch systems regularly, if you have an internal IT department or division then using a ticketing system will satisfy most of this requirement.
- Provide protection from malicious code at appropriate locations within organizational information systems.
	- Prevent uncontrolled code from executing- antivirus will work.
- Update malicious code protection mechanisms when new releases are available.
	- Update AV regularly, preferably daily.
- Perform periodic scans of the information system and real-time scans of files from external sources as files are downloaded, opened, or executed.
	- Know what information is entering your system, 
- Other requirements. This clause does not relieve the Contractor of any other specific safeguarding requirements specified by Federal agencies and departments relating to covered contractor information systems generally or other Federal safeguarding requirements for controlled unclassified information (CUI) as established by Executive Order 13556.
	- Just because you're adhering to the standards of this regulation, doesn't mean you can ignore the rest.
- Subcontracts. The Contractor shall include the substance of this clause, including this paragraph (c), in subcontracts under this contract (including subcontracts for the acquisition of commercial products or commercial services, other than commercially available off-the-shelf items), in which the subcontractor may have Federal contract information residing in or transiting through its information system.
	- Subcontractors who handle FCI have to follow the same rules as primes.
## List of Implementations
1. 
