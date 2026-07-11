Create an HTML + CSS "Sign Up" section styled as a split card:

Structure:
- A centered card, 600px wide, 400px tall, white background, subtle drop shadow
- Left half: signup form with heading "Sign Up", inputs for Username, Email, 
  Password, Retype Password, and a submit button labeled "Sign Up"
- Right half: a background image panel with "Sign in with Social Network" text 
  overlaid in white with a text shadow, plus 3 stacked buttons: 
  "Log in with Facebook" (dark blue), "Log in with X" (light blue), 
  "Log in with Google" (blue)
- A small circular "OR" badge overlapping the border between the two halves, 
  vertically centered

Layout approach:
- Use position: relative on the outer card and position: absolute for the 
  left panel, right panel, and OR badge so the OR badge can overlap the seam
- Left panel: 300px wide, 40px padding
- Right panel: 300px wide, 40px padding, background image with cover/center
- OR badge: 40x40px circle, light gray background, shadow, centered text

Styling details:
- Inputs: underline-only style (border-bottom only, no border/outline), 
  220px wide, 32px tall
- Submit button: solid brand color background, white uppercase text, 
  rounded corners, hover state that darkens slightly
- Social buttons: full width of their column, brand colors 
  (Facebook #32508e, X/Twitter #1d9bf0, Google #4285F4), white text, rounded
- Use CSS variables for font-family, primary color, and hover color so 
  they're easy to theme later

Output clean, semantic HTML with class names like .left-box, .right-box, 
.signup-section, and a separate CSS block.