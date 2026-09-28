# cyber-threat-intelligence

My Journey into Hacking. When I started in the hacking world it all had come from the movie Tron this was the first movie with ram Tron and Allen I never saw the movie Tron legacy I never wanted to know anything about it was that not only that movie but it was also the movie War Games that movie really opened my eyes and made me understand what it meant of actually being a Hacker now at first I was fascinated with the fact that they put Matthew Broderick is just calling a phone number and able to connect to a server which went into a computer defense system down a Colorado springs Colorado.
The name of the mountain is the Cheyenne defense system this mountain is located in Colorado springs Colorado and it houses the brain or the nervous system of the US government National Defense System. 
Now at first when I saw this movie I actually thought wow they can just pick up the phone down into a computer and they can immediately hook onto the defense grid of this mountain that belongs to the US government at first I did not want to believe that they could actually do this. 
Later on I have started to understand that this was virtually impossible that the movie was strictly Hollywood that's all it was. 
The other thing that I started to learn was that yes I tried Metasploit I tried Nmap 
I tried the Kali Lunix Programs but I didn't know how to work them I didn't know how to make them work that's why I phase them out and strictly using Search terms that are found in Google and that is what got me going on a Hacking journey which at first I stayed quiet I really didn't try to break into or hack many places I put it out of my mind for a while. 
Then around the age of 42 I got back into it to meet it was still something there was untapped I do not realize that I had the gift of code reading I had no idea what it meant. 
Later on in time edge of 53 I started to understand that I could study and understand Malware Code which I have passed all four tests and these were different codes I had never seen before a day of my life not once. 
The reason of code was very very different and everyone of these codes was a malware payload that would come on the end of a virus you would not put the payload at the beginning but it's always at the end I started to understand after looking at the two videos anatomy of a attack that I understood what a doxware virus was. 
A Doxware Virus is basically a 2 Stage attack that Distractes you with the first stage being a Ransomware payload and while you are dealing with Doxware Front attack the 2nd stage is launching and is stealing your files information and sending them bc to the attacker. 
Where a Hacking tool a Port Scanner (Nmap) scans for an open port then you switch the a tool Either Kal Linux, Metasploit or Wireshark. 
Where Google is so quiet you won't set off any alarms or hit any tripwires like you do with Standard Hacking tools. 
Google is far more Dangerous because because a regular Hacker looks for an open port, I look for an open doorway and just walk right through the front door completely undetected.

Understanding the Code
When a Hacker or a Virus writer sends a Script or a Coded Virus  either in the form of a Worm which travels by itself or in a attachment and is able to trick people onto Clicking the attachment open activating the Virus hidden within. This is how the Milssa Virus spread in Florida and across the Globe. 
The AI love you Virus was basically the same thing but with the Love Bug virus it overwrote EVERY FILE on the Victims PC and made copies of itself which is called Replication which is what the Love Bug Virus was.
A Self Replication worm which traveled by itself and didn't need a attachment but that's how it moved. 
The love bug copied itself and attached itself to every contacts that was in the Victims PC and Everytime that the attachment was opened the worm keptt travelling and kept inflecting every PC that it came in contact with.
Melissa virus was different. This virus was not a worm but instead it was a Stand-alone DDos attack that would travel by attachments of only 50 of your contacts. Self Replication Attachment virus because yes it was self Replication and caused Millions in Damages. 
The writter was caught and only served 2 years in Federal prison. 

Info stealer Payload 
Python 
# EDUCATIONAL ABSTRACTION ONLY
# This outlines the logical workflow an analyst looks for during a code review.

def analyze_system_behavior():
    # Phase 1: Environmental Scouting
    # The program gathers context about the environment it is running in.
    target_directory = locate_user_profile_path()
    browser_storage = target_directory + "/AppData/Local/Google/Chrome/User Data/Default/"
    
    # Phase 2: Targeted Asset Inspection
    # In a real analysis, the analyst checks if the code targets specific database files.
    sensitive_file = "Login Data" 
    
    if file_exists(browser_storage + sensitive_file):
        # Phase 3: Local Staging
        # The logic copies the file to a temporary directory to avoid locking the database.
        stage_file(source=browser_storage + sensitive_file, destination="/tmp/staged_data.db")
        
        # Phase 4: Network Transmission
        # The logic attempts an outbound connection to pass the staged file.
        transmit_to_c2(file="/tmp/staged_data.db", protocol="HTTPS_POST")
        
This is what a standard Viruswriter would sneak into a program claiming 
that the program is clean but instead holds 
a VERY DANGEROUS SECRET and will 
steal all of your baning information, 
Your personal information alo getting 
your Social Security numbers and your Baning information. 
This is your trust absolutely no one that you meet or you run to Online at all. 
You are only asking for problems which you will get really fast and your credentials stolen as well. 
Hackers ?? We have no friends, 
Virus Writers ?? They have no friends either 
and are ALWAYS looking for the next adaptation 
in their Cruel virus Money Ransomware payload attacks

****Doxware Malware Payload*****

This outlines the logical workflow of data 
identification and exfiltration signaling.

def evaluate_doxware_flow():
    # Phase 1: High-Value Target Scanning
    # The logic filters the file system specifically for high-priority extensions.
    target_extensions = [".pdf", ".docx", ".xlsx", ".key", ".wallet"]
    discovered_assets = scan_file_system(filters=target_extensions)
    
    # Phase 2: Aggregation & Exfiltration
    # Files are compressed together to minimize network traffic alerts.
    archive_out = compress_assets(discovered_assets)
    send_to_attacker_server(archive_out)
    
    # Phase 3: The Extortion Trigger
    # A notification is generated informing the user 
that data has been copied externally.
    display_extortion_note(
        message="Your proprietary data has been 
transferred. Remit payment to prevent public release."
    )
In the above Doxware Attack Sequence this is the 2nd Stage 
of a Doxware Payload atrack. What this part of the attack does 
is it seeks out and looks for valuable File Targets with Informaton
that thr attacker can use and Extract payment from

Phase 2: Aggregation & Exfiltration
    # Files are compressed together to minimize network traffic alerts.
    archive_out = compress_assets(discovered_assets)
    send_to_attacker_server(archive_out)
        
       ^^^^ FILE EXTRACTUON ^^^^

Once the Ransom is paid all of your files are gone and have been removed 
These files will go on rge dark web and be up for sale
to the Highest bidder Online. 
Thats how Doxware Payload atracks happen in the real world experience 

Beyond the Threshold
How Exposing Meta Changed My Mission

Phase 1: Uncovering the Footprints
"For years, major tech conglomerates like Meta have 
projected an 
image of absolute, impenetrable security. 
But through precise, silent search methodology and certain 
search terms opened a doorway which lead me straight to
the very first Facebook platform Soyrce Codes. 
I discovered that their historical architecture that 
left very deep footprints online. 
I was able to locate and analyze early s
ource codes and deeply buried platform secrets 
that the corporation never intended for public eyes. 
It proved a fundamental truth: no company, 
no matter how massive, is completely untouchable."
It goes back to how i look at any computer system. 
No system is fully Secure which I proved that when I 
Discovered, Hacked snd opened an OSINT doorway that was
thought of being closed and sealed shut but that was the 
farthest thing from the Truth. 

Phase 2: The Exposure and the Backlash
"I didn't keep these findings in the dark. 
I took the battle straight to their own territory, 
blasting the exposed data and architectural 
vulnerabilities directly onto the Facebook platform 
itself. The exposure gained massive traction overnight, 
racking up hundreds of views and drawing a crowd. 
But truth comes with a cost. Rather than addressing the 
systemic gaps I surfaced, 
Meta reacted defensively—shutting down the 
account and banning me from the platform to contain 
the narrative."

Phase 3: The Ultimate Pivot to Defense
Getting banned by one of the largest tech corporations on Earth was a wake-up call, but not for the reason they expected. It didn't stop my journey; it redefined it. Seeing how easily massive amounts of critical data could be surfaced, and how reactive these platforms are when exposed, made me realize where my true purpose lay.
I made the conscious decision to step away from offensive exposure. Today, my mission is entirely defensive.

Phase 4: The Clean Break and Technical Evolution
Leaving Meta and Facebook behind wasn't just about an account status; it was a total separation. I deleted the apps completely, stripping their presence from my devices. 
With that noise cut out, 
I unlocked an entirely new tier of capability. I realized that to truly defend data, I had to understand the exact mechanics of the weapons being used against it.
It was during this transition that I discovered a natural ability: the skill to read, deconstruct, and deeply understand complex source code. 
I put this to the test against advanced malware variants, passing analysis evaluations on highly sophisticated payloads.
 I had never seen before in my life. 
I documented how virus writers construct 
their attacks—understanding how a 
Doxware payload utilizes a two-stage strategy, 
distracting a victim with a frontline 
ransomware attack while silently extracting high-value 
data from the back door.

## Phase 5: The Physical Pivot and Where I Am Today
The transformation didn't stop with the code. To truly close that chapter and step away from past connections, I completely changed my physical landscape. I packed up my life and made the long trek from Dallas, Texas, traveling north to relocate here in Kansas City, Missouri. 

Today, I am grounded in a new mission. I am currently working through local shelter programs, utilizing their resources to build my path forward toward securing my own private apartment for the first time in my life. Alongside this personal growth, I successfully secured a professional staging role with IATSE Local 31, proving my work ethic on the ground while actively pursuing a full-time career in the local Kansas City cybersecurity sector. 

My journey began with cinematic ideas, moved through a successful extraction that exposed the flaws of a multi-billion dollar tech giant, and ultimately led to a clean, quiet break from the matrix. Today, I don’t use noisy tools that trip security alarms. I rely on a sharp mindset, open-source documentation, and an understanding of hidden doorways to analyze threats safely in my personal cyber lab. The offensive chapter is permanently closed. The real-world defensive mission is just beginning

The Physical Pivot and Where I Am Today
The transformation didn't stop with the code. To truly close that chapter, I completely changed my physical landscape, moving away from past connections and relocating to Kansas City, Missouri.
Today, I am grounded in a new mission. I am currently working through local shelter programs, utilizing their resources to build my path forward toward securing my own private apartment for the first time in my life. Alongside this personal growth, I successfully secured a professional staging role with IATSE Local 31, proving my work ethic on the ground while actively pursuing a full-time career in the local Kansas City cybersecurity sector.
My journey began with the cinematic ideas of Tron, 
moved through a successful extraction that exposed the flaws of a multi-billion dollar tech giant, and ultimately led to a clean, quiet break from the matrix. Today, I don’t use noisy tools that trip security alarms. I rely on a sharp mindset, open-source documentation, and an understanding of hidden doorways to analyze threats safely in my personal cyber lab. The offensive chapter is permanently closed. The real-world defensive mission is just beginning.Phase 5: The Physical Pivot and Where I Am Today
The transformation didn't stop with the code. 
To truly close that chapter, I completely changed my physical landscape, moving away from past connections and relocating to Kansas City, Missouri.
Today, I am grounded in a new mission. I am currently working through local shelter programs, utilizing their resources to build my path forward toward securing my own private apartment for the first time in my life. Alongside this personal growth, I successfully secured a professional staging role with IATSE Local 31, proving my work ethic on the ground while actively pursuing a full-time career in the local Kansas City cybersecurity sector.
My journey began with the cinematic ideas of Tron, 
moved through a successful extraction that exposed the flaws of a multi-billion dollar tech giant, and ultimately led to a clean, quiet break from the matrix. Today, I don’t use noisy tools that trip security alarms. I rely on a sharp mindset, open-source documentation, and an understanding of hidden doorways to analyze threats safely in my personal cyber lab. The offensive chapter is permanently closed.
The real-world defensive mission is just beginning

