# Fuse — Full-stack starter

## Run locally
1. Install Node.js 20+.
2. Copy `.env.example` to `.env`.
3. Set a strong `SESSION_SECRET`.
4. Add your Paystack **secret key** to `PAYSTACK_SECRET_KEY`.
5. Change `ADMIN_EMAIL` and `ADMIN_PASSWORD`.
6. Run `npm install`.
7. Run `npm start`.
8. Open `http://localhost:3000`.

## What is included
- Registration and login
- SQLite database
- Member dashboard
- Opt-in public profiles
- Discovery and connection requests
- Accept connections
- Reporting
- Admin login/dashboard
- Paystack ₦2,000 initialization and server-side verification

## Important production work
- Use HTTPS and secure cookies in production.
- Add CSRF protection, rate limiting, input validation, email verification and password reset.
- Configure a production database and backups.
- Configure Paystack webhook handling and verify transactions server-side.
- Add legal terms/privacy policy and clear consent controls.
- Never expose the Paystack secret key in browser code.
- Do not automatically publish or distribute a user's private WhatsApp number without explicit consent.