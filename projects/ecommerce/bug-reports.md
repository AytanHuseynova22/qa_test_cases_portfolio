Bug 1 -Social media sign up issue

Description: Social login redirects user back to sign-up page instead of logging in

"Environment:
•        Website: https://genai.works/sign-up/member
•        Browser: Chrome Version: 140.0.7339.82 (Official Build) (64-bit) Desktop
•        OS: Windows 10
         Environment: Prod
"

"Requirements
•        User is not logged in
•        A valid Google/LinkedIn/Facebook account exists
"

"Steps to Reproduce:
1.         Go to “GenAi Works” homepage
2.        Click “Get started”
3.        Click “Sign up with Google” (same with LinkedIn or Facebook)
4.        Grant the requested permissions in the popup
5.        Observe the redirection
"

"Expected Result:
User should be logged in and redirected to the dashboard/home page"


"Actual Result:
User is redirected back to the sign-up page instead of being logged in"

Severity: High (blocks new users from signing up via social login)

Priority: High (affects user acquisition and login flow)

Attachments: https://drive.google.com/file/d/1B1sP2z6A9PDGJ0EbLaliFkOIm_rk93xL/view?usp=sharing
