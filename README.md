# Ticketing

# Phishing Incident Report  

---  

## **Ticket Information**  

| **Ticket ID** | **Alert Message** | **Severity** | **Details** | **Ticket Status** |
|--------------|------------------|------------|-----------|---------------|
| A-2703 | SERVER-MAIL Phishing attempt possible download of malware | Medium | The user may have opened a malicious email and accessed attachments or links. | Escalated |  

---  

## **Ticket Comments**  

The alert detected that an employee **downloaded and opened a malicious file** from a phishing email. Key findings include:  

- **Inconsistent sender details:**  
  - **Email address:** `76tguy6hh6tgftrt7tg.su`  
  - **Displayed name in email body:** "Clyde West"  
  - **Sender's name in email header:** "Def Communications"  

- **Indicators of Phishing:**  
  - The **email subject and body** contained **grammatical errors**.  
  - The email included a **password-protected attachment**: `bfsvc.exe`.  
  - The attachment was **downloaded and executed** on the affected machine.  
  - **File hash investigation confirmed** it is a **known malicious file**.  
  - **Alert severity reported as Medium**.  

Based on these findings, the **ticket has been escalated** to a **level-two SOC analyst** for further investigation and response.  

---  

## **Additional Information**  

### **Known Malicious File Hash:**  
`54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b`  

---  

## **Email Details**  

**From:** Def Communications `<76tguyhh6tgftrt7tg.su>` `<114.114.114.114>`  
**Sent:** Wednesday, July 20, 2022 09:30:14 AM  
**To:** `<hr@inergy.com>` `<176.157.125.93>`  
**Subject:** Re: Infrastructure Engineer role  

---  

### **Email Body:**  

> **Dear HR at Inergy,**  
>  
> I am writing for to express my interest in the engineer role posted from the website.  
>  
> There is attached my resume and cover letter. For privacy, the file is password protected. Use the password `paradise10789` to open.  
>  
> Thank you,  
>  
> **Clyde West**  

**Attachment:** `filename="bfsvc.exe"`  

---  

## **Summary**  

This phishing incident demonstrates a **malicious email campaign** attempting to deliver a **known malware file** through **social engineering tactics**. The inconsistencies in sender details, grammatical errors, and the password-protected attachment indicate a **clear phishing attempt**. The ticket has been **escalated for further investigation**.  

