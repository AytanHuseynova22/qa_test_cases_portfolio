## BUG-004: Social media sign-up redirects user back to sign-up page

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
