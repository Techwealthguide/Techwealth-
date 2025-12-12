TechWealthGuide site — deployment notes

1) Required: Upload all files and folders as provided.
2) MailerLite: Embedded form used site-wide (PDyzKZ). Create a custom field named "gate" in your MailerLite account.
   - Create automations in MailerLite triggered when fields[gate] equals:
     ai-hard, crypto-hard, investing-hard, startup-hard, binance-hard, newsletter
3) Place the PDF files into /downloads/ with the exact filenames.
4) Replace /assets/logo.png and /assets/favicon.png with your actual images.
5) Test flow:
   - Open index.html, go to AI -> advanced (should redirect to gate if not submitted).
   - Submit email in gate page or fallback.
   - Confirm localStorage holds the record: open DevTools -> localStorage -> key 'twg_local'.
6) If you want me to embed your real images or produce the actual PDFs from the text I provided, reply "GENERATE PDFs" or upload the logo files.
