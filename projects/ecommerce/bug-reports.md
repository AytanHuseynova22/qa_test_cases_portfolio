## BUG-001: Social media sign-up redirects user back to sign-up page

**Environment:**  
- Website: https://genai.works/sign-up/member  
- Browser: Chrome 140.0.7339.82 (64-bit)  
- OS: Windows 10  
- Environment: Production  

**Preconditions:**  
- User is not logged in  
- User has a valid Google / LinkedIn / Facebook account  

**Steps to Reproduce:**  
1. Navigate to GenAi Works homepage  
2. Click on "Get started"  
3. Click on "Sign up with Google"  
   (same issue occurs with LinkedIn and Facebook)  
4. Grant required permissions in the social login popup  
5. Observe the redirection after authentication  

**Expected Result:**  
User should be successfully logged in and redirected to the dashboard or home page.

**Actual Result:**  
User is redirected back to the sign-up page and is not logged in.

**Severity:** High  
**Priority:** High  

**Attachments:**  
- Video recording: https://drive.google.com/file/d/1B1sP2z6A9PDGJ0EbLaliFkOIm_rk93xL/view


Bug 2 – "Forgot Password" flow	
	
"Description:
Forgot Password function fails — after entering a valid email, the system shows an error instead of sending the reset email."	
	
"Environment:
•        Website: https://genai.works/sign-up/member
•        Browser: Chrome Version: 140.0.7339.82 (Official Build) (64-bit) Desktop
•        OS: Windows 10
         Environment: Prod
"	
"Requirements
•        user signed up before
"	
	
"Steps to Reproduce:


1. Go to “GenAi Works” homepage
2. Click “Get started”
3. Go to Sign In page.
4. Click Forgot Password.
5. Enter a valid registered email.
6. Click Send / Reset password."	
	
"Expected Result:

The system should send a password reset email with a code or link.

User should see a success confirmation message (e.g., ""We’ve sent you an email with reset instructions."")."	
	
"Actual Result:

An Error message appears at the top (without explanation).

No reset email is received."	
	
Severity: 🟠 Major (blocks users from resetting password, so they cannot recover access).	
	
Attachments:	https://docs.google.com/spreadsheets/d/1-oYb08oMY5alVtDbX5PleGOQG5lCSRFzR7OP6qhVHMI/edit?gid=186965300#gid=186965300
	
	
	
	
	
	
	
	
	
	
	
	
	
	
